# tailwindlens
"A lightweight frontend development tool that inspects web pages and instantly extracts clean, responsive Tailwind CSS components."
# Tailwind Lens 🔍✨

> *Paste a page. Click a section. Get the Tailwind.*

**Tailwind Lens** is a lightweight, modern, single-page web development utility designed to help developers and designers inspect layout structures, preview web page elements, and generate clean, responsive Tailwind CSS code instantly.

---

## 🚀 Live Preview / Landing Page Review

The user interface (UI) and user experience (UX) of the landing page have been meticulously crafted to provide a clean, modern, and high-converting developer tool aesthetic. 

### 🌟 Key UI/UX Highlights of Page 1:
1. **Subtle Grid Background Pattern (`bg-grid-pattern`)**: 
   * Uses custom CSS linear gradients to render a subtle blueprint/engineering grid layout across the viewport, giving it a technical, designer-focused feel reminiscent of modern developer tools.
2. **Minimalist Navigation Header**: 
   * Features a crisp brand title (*Tailwind Lens*), clean anchor links (*How it works*, *What it's for*), and a high-contrast call-to-action button.
3. **High-Impact Hero Section**: 
   * Features a bold, extra-large typography headline (`5xl` to `7xl` scaling) that immediately communicates the tool's core value proposition.
4. **Interactive URL Input Bar**: 
   * A prominent, shadow-elevated search bar allowing users to quickly input target public URLs (`https://example.com`) alongside quick-fill testing links (e.g., `example.com`, `news.ycombinator.com`, `wikipedia.org`).
5. **Split Workspace Preview Panel**: 
   * Implements a dual-pane layout separating the **Original (scripts disabled)** view from the **Tailwind Code / Rebuilt Preview** workspace, complete with built-in action buttons for instant code copying and file downloading (`component.html`).

---

## 🛠️ Tech Stack

* **HTML5**: Semantic markup structure.
* **Tailwind CSS (CDN)**: Fast utility-first styling and layout structure.
* **Vanilla JavaScript (ES6)**: DOM manipulation, quick sample injections, copy-to-clipboard functionality, and dynamic file blob downloads.

---

## 📂 Project Structure

```text
tailwind-lens/
├── index.html       # Main single-file frontend application & styling
└── README.md        # Project documentation and review
