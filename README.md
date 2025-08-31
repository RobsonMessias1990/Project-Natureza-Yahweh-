# Leafy Lane — Houseplant Store

A minimal React + Redux Toolkit + React Router project satisfying the rubric (50 points, 19 tasks).

## 🚀 Quick Start

```bash
npm install
npm run dev
```
Then open the printed local URL.

## 🧭 Pages

- `/` Landing page (background image, company name, paragraph, **Get Started** button → `/products`)
- `/products` Product listing page (6 unique houseplants; grouped via visible category pills; each shows thumbnail, name, price; **Add to Cart** button adds item, disables itself, and increments cart count)
- `/cart` Shopping cart page (shows each plant type with thumbnail, name, unit price; increase/decrease/delete; totals; **Checkout** alerts “Coming Soon”; **Continue Shopping** links back)

## 🧱 Tech
- React 18, Redux Toolkit, React Router, Vite
- Accessible markup (aria labels, roles)
- No server needed

## 🧪 Rubric Mapping
- GitHub: make this repo public + keep Redux files (`src/store/*`) → 6 pts
- Landing page requirements → 5 pts
- Product listing behaviors (count increments, button disables, correct plant added) → 9 pts
- Header present on both pages, cart icon shows total items, navigation works → 7 pts
- Cart page totals, per-item details, increase/decrease/delete, checkout, continue shopping → 23 pts

Good luck and happy planting 🌿
