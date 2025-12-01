# Greater Restaurant – Responsive Frontend Website

A fully responsive restaurant website built within 2 days, designed from scratch including logo creation (Figma) and complete mobile-first adjustments.  
Live Demo: https://greaterrestaurant.netlify.app/

---

## Overview
A modern single-page restaurant website featuring:
- Custom Figma-designed logo  
- Clean navigation with smooth scrolling  
- Fully mobile-optimized layout  
- Interactive menu, order form, and reviews  
- Consistent color theme (Red × White)  
- Pixel-perfect spacing and alignment across devices

---

## Tech Stack
- **HTML5** – semantic structure  
- **CSS3** – flexbox, grid, media queries, animations  
- **Figma** – logo design  
- **Netlify** – deployment with continuous updates  

---

## Desktop Preview

<div style="display:flex; flex-wrap:wrap; gap:6px;"> <img src="https://github.com/user-attachments/assets/9cd00613-9d5c-420b-b932-e9df5563c1f3" width="48%" /> <img src="https://github.com/user-attachments/assets/ddd9559b-e9d4-4aab-a296-be1e6778e2d1" width="48%" /> <img src="https://github.com/user-attachments/assets/3677a125-e58a-4081-a937-a78f725f9a6d" width="48%" /> <img src="https://github.com/user-attachments/assets/342cc363-c723-47ba-af47-df0f538f4a6a" width="48%" /> <img src="https://github.com/user-attachments/assets/7243dca3-d928-470c-b752-264accb231aa" width="48%" /> </div>


---

## Mobile Preview
<div style="display:flex; flex-wrap:wrap; gap:6px;"> <img src="https://github.com/user-attachments/assets/cfd075a2-2421-4524-bb08-1c84e459cf99" width="30%" /> <img src="https://github.com/user-attachments/assets/cd734c6c-5d14-4fc8-b29a-650ab8b318ef" width="30%" /> <img src="https://github.com/user-attachments/assets/18a5116a-83ef-467a-9b6b-ea34b66b382a" width="30%" /> <img src="https://github.com/user-attachments/assets/69b99415-060e-46bd-bc95-e06a78994eaf" width="30%" /> <img src="https://github.com/user-attachments/assets/12591e5f-36b7-453c-ba18-0f7534d42966" width="30%" /> </div>


---

## Key Features

### Responsive Layout
- Custom breakpoints  
- Grid → stacked layout transitions  
- No horizontal scroll  
- Auto-scaled images and text sizes  

### Menu Section
- Uniform card layout  
- Image scaling without cropping  
- Hover-highlight effects  

### Order Section
- Clean two-column → single-column conversion  
- Styled input fields  
- Proper increment/decrement number selector  
- Enhancements for usability on small screens  

### Review Section
- Structured review cards  
- Smooth spacing and padding adjustments  
- Clear contrast for readability  

---

## Folder Structure
```text
root/
├── index.html
├── style.css
├── image/
│   ├── logo.png
│   ├── bg.png
│   ├── menu1.png
│   ├── menu2.png
│   └── ...
└── README.md
```
# Responsive Styles (Media Query Highlight)
```
@media (max-width: 768px) {
    .menu_box {
        grid-template-columns: 1fr;
        padding: 20px;
    }

    .order_main {
        flex-direction: column;
        text-align: center;
    }

    .review_box {
        grid-template-columns: 1fr;
    }
}

```
---
# What I Focused On

- Strong spacing discipline
- Consistent UI components
- Fully fluid responsive behavior
- Organized CSS structure
- Clean color palette and typography
- Zero layout breakage at any width
---
# Live Project

View the fully responsive version here:
https://greaterrestaurant.netlify.app/

# Future Improvements

- Add animations for section transitions

- Add menu filtering

- Add cart + ordering flow
