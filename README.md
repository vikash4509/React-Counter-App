# React Counter App

## Project Objective
To develop a simple and interactive counter application using React that demonstrates:
- State management using **useState**
- Event handling
- Conditional rendering

This project aims to build a strong foundation in React’s core concepts through practical implementation.

---

## Brief Description
A simple React counter app demonstrating state management, event handling, and conditional rendering.  
Includes customizable step size, upper/lower bounds, option to allow/disallow negative values, and `localStorage` persistence.

---

## Links
- **GitHub Repository:** [Add your GitHub Repo Link here]
- **Live Demo:** [Add your Netlify/Vercel Live Demo Link here]

---

## Technologies Used
- **HTML5**
- **CSS3**
- **JavaScript (ES6)**
- **React.js**

---

## How to Run Locally
- **Clone the repository**
```bash
git clone [Your GitHub Repo URL]
```
- **Navigate into the project folder**
```bash
cd react-counter-app
```
- **Install dependencies**
```bash
npm install
```
- **Start the development server**
```bash
npm start
```

## Challenges Faced & Solutions
- **Challenge:** Maintaining counter state after page reload  
  **Solution:** Used `localStorage` to persist data.

- **Challenge:** Disabling buttons at bounds  
  **Solution:** Conditional rendering & state checks.

## Screenshots
(Add screenshots here after running the app)

Example:

![Screenshot Example](./screenshot.png)

---

## Feature List
- Increment, decrement, reset counter value
- Customizable step size
- Upper/lower bounds with button disable
- Toggle for allowing negative values
- Dynamic text color based on state
- Persist state with `localStorage`

---

## Sample Input & Output

| Action              | Expected Output                   |
|---------------------|---------------------------------|
| Click +             | Counter increases by step size  |
| Click -             | Counter decreases by step size  |
| Change step size    | Increment/Decrement changes accordingly |
| Reach upper bound   | + button disabled                |
| Reach lower bound   | - button disabled                |
| Toggle negative off | Counter min = 0                  |
| Click reset         | Counter = 0                     |

---

## Evaluation Criteria Mapping

| Criteria          | Status                               |
|-------------------|------------------------------------|
| Functionality     | ✅ All core features working as specified |
| React Concepts    | ✅ Correct use of `useState`, event handling, conditional rendering |
| UI/UX             | ✅ Clean layout, intuitive interface |
| Edge Handling     | ✅ Bounds enforced, buttons disabled at limits |
| Code Quality      | ✅ Modular, commented, readable    |
| Bonus Features    | ✅ `localStorage` persistence, dynamic styling |
| Deployment        | ✅ Ready for GitHub Pages, Vercel, or Netlify |
| Documentation     | ✅ Complete README.md with all sections |

---

## Author

**Name:** Vikash Kumar Gupta  
**Date:** August 2025
