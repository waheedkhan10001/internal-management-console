# 📊 Internal Management Console (HTML + CSS)

A clean, desktop-first **internal operations dashboard** built using **pure HTML and CSS**.  
Designed to demonstrate strong fundamentals in **semantic HTML, layout architecture, spacing systems, and UI hierarchy** — without JavaScript or frameworks.

🔗 **Live Demo:**  
👉 https://waheedkhan10001.github.io/internal-management-console/

📁 **GitHub Repository:**  
👉 https://github.com/waheedkhan10001/internal-management-console

---

## ✨ Features

- Semantic HTML5 structure (`header`, `nav`, `main`, `section`, `table`, `footer`)
- CSS Grid–based application shell
- Flexbox for component-level layout
- Tokenized design system using CSS variables
- KPI cards with clear visual hierarchy
- Data table with hover states and readable typography
- Sidebar navigation with active and hover states
- No JavaScript, no frameworks, no libraries

---

## 🧱 Project Structure

internal-management-console/
│
├── index.html # Main HTML layout (semantic & accessible)
├── style.css # Global styles, layout, components
├── LICENSE # MIT License
└── README.md # Project documentation

---

## 🎨 Design System

All core design tokens are defined in `:root`:

- Brand colors (primary, secondary, accent)
- State colors (success, danger, warning)
- Neutral palette (backgrounds, borders, text)
- Border radius and shadow tokens
- Consistent typography and spacing decisions

This ensures:

- Predictable styling
- Easy refactoring
- Professional CSS architecture

---

## 📐 Layout Architecture

- **Header**  
  Application identity and logged-in user status

- **Sidebar Navigation**  
  Hierarchical navigation (Core / Operations / Admin)

- **Main Content**

  - Dashboard title
  - KPI summary grid
  - Active projects data table

- **Insights Panel**

  - Alerts
  - Team availability
  - Notes

- **Footer**
  - Environment metadata
  - Versioning information

Layout responsibility is handled at the **parent level** using Grid and Flexbox.

---

## 🚫 Constraints (Intentional)

- ❌ No JavaScript
- ❌ No CSS frameworks (Bootstrap, Tailwind, etc.)
- ❌ No resets or normalize.css
- ❌ No inline styles

This project focuses purely on **core frontend fundamentals**.

---

## 🧠 Learning Focus

This project demonstrates understanding of:

- Default browser behavior vs explicit CSS control
- Spacing responsibility (parent vs child)
- Flexbox vs Grid decision-making
- Table layout models (`border-collapse`)
- Visual hierarchy and density control
- Real-world dashboard UI patterns

---

## 📄 License

This project is licensed under the **MIT License**.  
See the [LICENSE](LICENSE) file for details.

---

## 👤 Author

**Abdul Waheed Khan**  
Frontend Learning Project — 2025
