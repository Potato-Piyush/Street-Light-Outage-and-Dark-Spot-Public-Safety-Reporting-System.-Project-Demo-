# 💡 Street Light Outage and Dark Spot Public Safety Reporting System

A responsive, frontend-only website that lets citizens report non-working streetlights and track municipal repair progress. Built with **pure HTML and CSS**: no JavaScript, no backend, no frameworks.

## 📌 Problem Statement

Non-functional streetlights create dangerous dark spots along pedestrian walkways and roads, increasing the risk of nighttime accidents and street crimes. This project gives citizens a simple way to report broken streetlamps by pole number and lets them follow the repair status of municipal electrical teams.

## ✨ Features

- **Outage Report Form**: capture Pole Number / Street Landmark, Ward Number and Outage Type (Completely Dark, Flickering, Damaged Pole), with built-in form validation.
- **Safety Priority Indicator**: choose what is near the pole (school, bus stop, dark alleyway or normal road) and the page instantly shows the priority level and repair time (Critical, High or Normal).
- **Repair Status Dashboard**: summary counts, overall and ward-wise progress bars, and a pole-by-pole tracker with filter buttons (All / Pending / In Progress / Repaired).
- **Repair Team Tracker**: shows which municipal electrical team is working on which pole.
- **Helpline Buttons**: one-tap call to the municipal electrical helpline and a direct emergency dispatcher extension.
- **Fully Responsive**: works on mobile, tablet and desktop.

## 🛠️ Tech Stack

| Technology | Usage |
|------------|-------|
| HTML5 | Page structure, form, table, `tel:` call links |
| CSS3 | Layout, styling, animations, responsive design |

All interactivity is done in **pure CSS**:
- `:checked` with the `~` sibling selector shows the priority indicator and powers the dashboard filter
- `:target` opens the "Report Submitted" popup
- `:has()`, `:hover` and `:focus` provide visual feedback

## 📁 Project Structure

```
├── index.html     # Page structure and content
├── style1.css     # Layout & look: header, hero, buttons, cards, helpline, footer, responsive rules
└── style2.css     # Interactive features: form, priority indicator, dashboard, filter, popup
```

## 🚀 How to Run

1. Download or clone this repository.
2. Keep `index.html`, `style1.css` and `style2.css` in the same folder.
3. Open `index.html` in any modern web browser.

## 📞 Helpline Setup

The phone number and extension in the project are placeholders. To use your city's real numbers, edit these lines in `index.html`:

```html
<a href="tel:1800000000">...</a>
<a href="tel:1800000000,,101">...</a>
```

The commas add a pause before the emergency extension is dialled.

## ⚠️ Note

This is a frontend-only college project. Submitted reports are not stored, and all dashboard data is sample data. A real deployment would connect the form to a backend and database.

## 👥 Team

- HTML: *Shreyash Kumar*
- CSS (Layout & Look): *Piyush Kumar*
- CSS (Interactive Features): *Abhinav Katiyar*

## 📄 License

This project is for educational purposes.
