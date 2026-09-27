# Assignment 2.
**Name**: Alish Medina
**Group**: SE-2538

---

## Project Overview:
This project demonstrates modern CSS layout techniques using Flexbox and CSS Grid to build a responsive portfolio page. The project is divided into three parts: Flexbox, Grid System, and Combining Both.

| File | Description |
|---|---|
| `index.html` | HTML structure |
| `style.css` | All styling |
| 15 images | Assets for cards and gallery |

---

## Part 1. Flexbox
### Task 1. Header with Logo and Navigation
The <header> is a flex container using justify-content: space-between to push the logo left and nav right, and align-items: center to vertically center both. The <nav> is also flex with gap: 20px for spacing between links.
<img width="475" height="442" alt="Снимок экрана 2026-09-27 183857" src="https://github.com/user-attachments/assets/02c9d712-462e-44c3-a7e3-cb0c377c61a7" />
<img width="1420" height="841" alt="Снимок экрана 2026-09-27 183908" src="https://github.com/user-attachments/assets/df6770b0-e7f0-480a-af04-b160c880e649" />

### Task 2. Card Row
The .project-list is a flex container with gap: 30px and align-items: stretch so all cards have equal height. Each .project uses flex: 1 and flex-direction: column so the button sticks to the bottom with margin-top: auto. Hover adds shadow and scale.
<img width="402" height="377" alt="Снимок экрана 2026-09-27 184013" src="https://github.com/user-attachments/assets/a8f684f9-b733-4b9d-9a96-3fa62392b0ca" />
<img width="508" height="355" alt="Снимок экрана 2026-09-27 184020" src="https://github.com/user-attachments/assets/6e18655b-e85d-431e-bc30-67446d83bfe2" />
<img width="1420" height="841" alt="Снимок экрана 2026-09-27 183908" src="https://github.com/user-attachments/assets/faa56525-1582-4202-b4e9-9f515e486f8e" />

---

## Part 2. Grid System
### Task 3. Page Layout with Grid Areas
The .page is a grid container with two columns and three rows. Named grid areas place the header on top, sidebar left, main right, and footer at the bottom.
<img width="563" height="507" alt="Снимок экрана 2026-09-27 184126" src="https://github.com/user-attachments/assets/1de290fc-0601-408d-8955-3db6b71e031d" />
<img width="462" height="472" alt="Снимок экрана 2026-09-27 184158" src="https://github.com/user-attachments/assets/ac1aa818-3eda-4718-b9cb-38051275a57f" />
<img width="503" height="357" alt="Снимок экрана 2026-09-27 184203" src="https://github.com/user-attachments/assets/6c11328a-6627-4a81-ba35-ec1548fa9cc0" />
<img width="1412" height="836" alt="Снимок экрана 2026-09-27 173855" src="https://github.com/user-attachments/assets/b5cc9928-852a-44ba-9113-88eae081ab66" />
<img width="1405" height="733" alt="Снимок экрана 2026-09-27 173859" src="https://github.com/user-attachments/assets/1ebfaf4d-4e1c-47b1-bba5-71d7632c8d81" />
<img width="1422" height="836" alt="Снимок экрана 2026-09-27 173851" src="https://github.com/user-attachments/assets/563a9e43-9bee-410e-a4f6-6e98d97541b2" />

### Task 4. Image Gallery
The .gallery is a grid container with 3 equal columns and 4 rows, plus gap: 15px. Each item has a caption overlay that appears on hover using position: absolute and opacity.
<img width="503" height="357" alt="Снимок экрана 2026-09-27 184203" src="https://github.com/user-attachments/assets/0dc16b34-dee6-4d87-8760-670e383f8651" />
<img width="503" height="158" alt="Снимок экрана 2026-09-27 184257" src="https://github.com/user-attachments/assets/82308b71-2fe0-4a1b-b0a7-d45c8ef9404f" />
<img width="496" height="355" alt="Снимок экрана 2026-09-27 184312" src="https://github.com/user-attachments/assets/cbf08ee7-2e66-420c-9e19-c2c4a12bd98e" />
<img width="1412" height="836" alt="Снимок экрана 2026-09-27 173855" src="https://github.com/user-attachments/assets/4c5c728a-1d92-446b-b0aa-a042b15e8def" />
<img width="1405" height="733" alt="Снимок экрана 2026-09-27 173859" src="https://github.com/user-attachments/assets/203712d1-08b7-47ac-850f-145de845dd46" />

---

## Part 3. Combining Flexbox & Grid
This page combines both techniques:
-**Grid** for the overall page layout (header, sidebar, main, footer).
-**Flexbox** in the header for navigation.
-**Flexbox** inside each project card (title, text, button).
-**Footer** spans the bottom via grid-area: footer.
<img width="1422" height="836" alt="Снимок экрана 2026-09-27 173851" src="https://github.com/user-attachments/assets/bdacf4e7-b7b8-4d3c-be18-28b229d8c853" />
<img width="1412" height="836" alt="Снимок экрана 2026-09-27 173855" src="https://github.com/user-attachments/assets/4bc0059a-ca6e-4443-b486-c7341c59d846" />
<img width="1405" height="733" alt="Снимок экрана 2026-09-27 173859" src="https://github.com/user-attachments/assets/3f2d3b18-31d2-42de-af46-3e2d79509783" />

---

## Summary of Work Process
-Planned the page structure: header, sidebar, main (portfolio + gallery), footer.
-Built index.html with semantic tags, 3 project cards, and 12 gallery items.
-**Part 1**: Used Flexbox for the header and card row. Ensured equal card heights and added hover effects.
-**Part 2**: Used Grid for the page layout with named areas, and for the gallery with 3×4 columns/rows. Added caption overlays on hover.
-**Part 3**: Combined Grid (page layout) with Flexbox (header and card content). Verified footer spans the bottom.
-Tested in browser, fixed spacing issues, and uploaded everything to GitHub.
