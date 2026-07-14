const root = document.documentElement;
const themeToggle = document.querySelector(".theme-toggle");
const menuToggle = document.querySelector(".menu-toggle");
const mobileNav = document.querySelector(".mobile-nav");
const desktopLinks = [...document.querySelectorAll(".desktop-nav a")];
const sections = [...document.querySelectorAll("main section[id]")];

const savedTheme = localStorage.getItem("asal-theme");
if (savedTheme) {
  root.dataset.theme = savedTheme;
}

themeToggle.addEventListener("click", () => {
  const nextTheme = root.dataset.theme === "light" ? "dark" : "light";
  root.dataset.theme = nextTheme;
  localStorage.setItem("asal-theme", nextTheme);
});

menuToggle.addEventListener("click", () => {
  const isOpen = document.body.classList.toggle("menu-open");
  menuToggle.setAttribute("aria-expanded", String(isOpen));
});

mobileNav.addEventListener("click", (event) => {
  if (event.target.matches("a")) {
    document.body.classList.remove("menu-open");
    menuToggle.setAttribute("aria-expanded", "false");
  }
});

document.addEventListener("keydown", (event) => {
  if (event.key === "Escape") {
    document.body.classList.remove("menu-open");
    menuToggle.setAttribute("aria-expanded", "false");
  }
});

function updateActiveNavigation() {
  let activeId = "";

  for (const section of sections) {
    const top = section.getBoundingClientRect().top;
    if (top <= 150) {
      activeId = section.id;
    }
  }

  desktopLinks.forEach((link) => {
    link.classList.toggle(
      "active",
      link.getAttribute("href") === `#${activeId}`
    );
  });
}

window.addEventListener("scroll", updateActiveNavigation, { passive: true });
updateActiveNavigation();

document.getElementById("year").textContent = new Date().getFullYear();
