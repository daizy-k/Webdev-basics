# Webdev-basics

A collection of foundational web development exercises and projects. Developed as part of a scholarship training program to sharpen core coding skills.

---

##  Projects & Modules Overview

This repository contains clean, semantic HTML5 implementations and modern CSS styling covering foundational web design concepts:

| File | Module Name | Key Concepts Covered |
| :--- | :--- | :--- |
| **[`index.html`](index.html)** | Learning Hub &amp; Dashboard | Central portal, semantic navigation, responsive overview cards |
| **[`list.html`](list.html)** | HTML Lists | Unordered lists (`<ul>`), ordered lists (`<ol>`) with `type="A"`, `type="a"`, `type="I"`, `type="i"`, nested lists, Emmet shortcuts (`li*4 + Tab`) |
| **[`tables.html`](tables.html)** | HTML Tables | Table hierarchy (`<table>`, `<thead>`, `<tbody>`, `<tr>`, `<th>`, `<td>`), `border-collapse: collapse`, cell padding, hex colors, zebra striping |
| **[`forms.html`](forms.html)** | HTML Forms | Inputs (`text`, `email`, `password`, `number`, `date`), validation (`required`, `min`, `max`, `step`), shared-name radio buttons, checkboxes, dropdown select |
| **[`links.html`](links.html)** | HTML Links | Internal relative links, external links (`target="_blank"`, `rel="noopener noreferrer"`), clickable image links, combined card links |
| **[`divs.html`](divs.html)** | Divs &amp; CSS Basics | Container division, nested divs, inline CSS vs. `<style>` tag, CSS box model (margin, padding, border), hex codes, `rem` font scaling, class selectors |

---

##  Core CSS & Design Concepts Applied

- **Box Model**: Margin (outer spacing & horizontal centering via `margin: auto`), Border (`solid`, `dotted`, `dashed`), Padding (inner spacing between content and edge).
- **Table Borders**: `border-collapse: collapse;` to merge double borders into crisp single lines.
- **Color Systems**: Hexadecimal color codes (e.g. `#4f46e5`, `#1e293b`, `#f8fafc`) preferred over generic named colors.
- **Typography**: Responsive scaling with `rem` units and Google Fonts (`Inter` & `Outfit`) for reliable cross-browser typography.
- **Selectors**: Tag selectors for default element behaviors, class selectors (`.classname`) for granular styling, and compound classes.

---

##  Project Structure

```text
Webdev-basics/
├── index.html       # Main landing page & navigation hub
├── list.html        # HTML lists module (unordered, ordered, nested)
├── tables.html      # HTML tables module with CSS border-collapse
├── forms.html       # HTML forms with validation, radio & checkboxes
├── links.html       # HTML hyperlinks, target="_blank", and image links
├── divs.html        # HTML divs, nested containers & CSS box model
├── README.md        # Course notes & documentation
└── .gitignore       # Git ignore rules
```

---

##  How to View Locally

1. Clone or download the repository:
   ```bash
   git clone https://github.com/daizy-k/Webdev-basics.git
   ```
2. Open any `.html` file directly in your favorite web browser (Chrome, Edge, Firefox, Safari) or use a local dev server (e.g., Live Server in VS Code).

---

##  Curriculum Roadmap

- [x] HTML Basics (lists, tables, links, forms, divs)
- [x] CSS Foundations (box model, hex colors, font-family, rem units, style tags)
- [ ] Git & GitHub workflow and remote pushing
- [ ] Horizontal layouts with CSS Flexbox
- [ ] Responsive CSS frameworks (Bootstrap)
