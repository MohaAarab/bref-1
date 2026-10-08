# Portfolio — Mohamed

A personal portfolio website built with **HTML and CSS only** (no JavaScript, no framework). It presents who I am, my skills, my projects, and a way to contact me. The project started from a provided Figma template and HTML/CSS base, which I personalized and extended from 1 page to 4.

## 🌐 Pages

| Page | File | Content |
|------|------|---------|
| Accueil | `index.html` | Personal presentation, title, photo, short intro, button to Projets, skills|
| Projets | `projets.html` | 4+ project cards displayed with CSS Grid |
| À propos | `a-propos.html` | Background, skills, professional objectives |
| Contact | `contact.html` | Contact form, GitHub and LinkedIn links |

## 🎨 Figma

Design made **before** the corresponding code (including the À propos page, which did not exist in the original template).

👉 **Figma link:** [maquette](https://www.figma.com/design/jXzLT5rLnHGEdi6QbzMjZW/Brief-1-%E2%80%94-Portfolio-personnel?node-id=4-214&t=r9iaCiKs3oRGuFeI-1)

## 🔧 Changes made to the original template

- Personalized the content: name, job title, presentation, photo, GitHub and LinkedIn links
- Replaced the generic colors and fonts with my own visual identity
- Defined **CSS variables** for colors and fonts in `:root`
- Created 3 new pages: `projets.html`, `a-propos.html`, `contact.html`
- Moved the **Compétences** section from Accueil to À propos
- Added at least 4 project cards (image, title, description, technologies, link)
- Displayed the projects with **CSS Grid**; used **Flexbox** for the header/navigation and other layouts
- Built the contact form (name, email, subject, message) with labels, correct input types and `required`
- Added a navigation bar working on every page, with the **current page highlighted**
- Applied the same header and footer on all 4 pages
- Used semantic HTML (`header`, `nav`, `main`, `section`, `article`, `footer`), one `h1` per page, and descriptive `alt` text on all images
- Used a single shared stylesheet (`css/style.css`), no inline styles
- Validated all 4 pages with the W3C validator (0 errors)


## 📁 Project structure

```text
portfolio/
├── index.html
├── projets.html
├── a-propos.html
├── contact.html
├── README.md
├── css/
│   └── style.css
└── images/
    ├── about-me.jpg
    ├── projet-1.jpg
    ├── projet-2.jpg
    ├── projet-3.jpg
    ├── projet-4.jpg
```

## 🛠️ Technologies

- HTML5 (semantic)
- CSS3 (variables, Flexbox, Grid)
- Figma (design)
- Git & GitHub (version control)

## ✅ Validation

All pages were checked with the [W3C Markup Validator](https://validator.w3.org/): **0 errors** on `index.html`, `projets.html`, `a-propos.html` and `contact.html`.

> Note: the contact form is front-end only and does not send emails.

## 👤 Author

**Mohamed**
- [GitHub](https://github.com/MohaAarab/bref-1.git)
- [LinkedIn](https://www.linkedin.com/in/mohamed-aarab-automation-specialist?utm_source=share_via&utm_content=profile&utm_medium=member_ios)