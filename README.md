# QuackUI 🦆

UI component library for **Go + Templ + HTMX + Tailwind**.  
Designed to bring a **Flutter-like developer experience** to server-driven UIs.

---

## ✨ Features
- 🧩 Reusable components (Button, Card, Modal, Input, Navbar, …)
- 🎨 Clean Tailwind-based styling with variants and sizes
- ⚡ Powered by HTMX for interactivity (no heavy frontend framework)
- 🦆 Flutter-inspired API (`@Button("Save", Solid)`)
- 📦 Drop-in ready for your Go + Templ projects

---

## 🚀 Getting Started
Install via Go modules:

```bash
go get github.com/yourusername/quackui
Use inside your Templ code:

go
Copier le code
templ Page() {
    <div class="space-x-2">
        @quackui.Button("Save", quackui.Solid)
        @quackui.Button("Cancel", quackui.Outline)
    </div>
}
📚 Components (WIP)
 Button (variants: solid, outline, ghost, soft, white, link)

 Card

 Modal

 Input

 Navbar

🛠 Development
Clone the repo and run the demo app:

bash
Copier le code
git clone https://github.com/yourusername/quackui
cd quackui/cmd/demo
go run .
This starts a local showcase app (like Storybook) to explore components.

💡 Philosophy
QuackUI is built with three core principles:

Simplicity → Minimal API, predictable defaults.

Composability → Components you can nest and extend.

Server-driven First → Optimized for HTMX, not a client-heavy SPA.

🗺 Roadmap
Buttons (variants, sizes, icons)

Core layout primitives (Card, Container, Grid)

Common form elements (Input, Select, Checkbox)

Navigation (Navbar, Tabs, Sidebar)

Overlays (Modal, Drawer, Tooltip)

📣 Stay Tuned
This project is in early development.
Follow progress, star the repo ⭐, and join the ride as we make Go + Templ UI development a lot more quackin’ fun.

yaml
Copier le code

---

This way, even with just a `Button` component, it **looks like a real OSS project** already.  
People will star it early and follow your updates.  

---

Want me to also draft a **first commit roadmap issue template** (so you can use GitHub Issues to track progress like “QuackUI v0.1 Milestone”)? That helps a lot with showing direction.
