# Pure CSS Sidebar Toggle Menu

A slide-out sidebar menu built with HTML & CSS only. A hidden checkbox controls the open/close state, and the hamburger icon animates into a close (X) icon. No JavaScript.

🔗 **Live Demo:** https://muhammaduzairkhalid15.github.io/Sidebar-Toggle-Menu/
💻 **Repository:** https://github.com/MuhammadUzairKhalid15/Sidebar-Toggle-Menu

## ✨ Features

- 🍔 Animated three-bar icon that morphs into an X when the menu opens
- 📲 Smooth slide-in sidebar using `transform: translateX()` with a transition
- 🎨 Pink-to-blue gradient sidebar panel with a fixed header bar
- ✨ Hover effect on menu items
- 🔗 Menu items: Portfolio, Social Media, Contact Me
- 🚫 No JavaScript used

## 🔧 Built With

- **HTML5**
- **CSS3** – checkbox hack, sibling selectors, transforms, transitions
- **Google Fonts** – Varela Round

## 📂 Project Structure

```
Sidebar-Toggle-Menu/
├── index.html
└── style.css
```

## 🚀 Getting Started

1. Clone the repository
   ```
   git clone https://github.com/MuhammadUzairKhalid15/Sidebar-Toggle-Menu.git
   ```
2. Open `index.html` in your browser, then click the icon in the header to open the sidebar.

## 💡 What I Practiced

- The checkbox hack (`input:checked ~ #sidebarmenu`) to toggle UI state without JavaScript
- Sibling (`~`) and child (`>`) selectors to control other elements from a hidden checkbox
- Using `transform: translateX()` instead of `left` for smoother, GPU-accelerated slides
- Turning three bars into an X with `rotate()`, `opacity` and transitions
- Gradient backgrounds with `linear-gradient`

## 📬 Feedback

Feedback and suggestions are always welcome. Feel free to open an issue or reach out on LinkedIn!
