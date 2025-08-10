# React-Counter-App
A simple React counter app demonstrating state management and event handling.

#  React Counter App

## Project Objective
To develop a simple and interactive counter application using React that demonstrates:
- State management using **useState**
- Event handling
- Conditional rendering

---

## Brief Description
A simple React counter app demonstrating state management, event handling, and conditional rendering.  
Includes customizable step size, upper/lower bounds, option to allow/disallow negative values, and localStorage persistence.

---

## 🔗 Links
- **GitHub Repository:** https://github.com/vikash4509/React-Counter-App.git
- **Live Demo:** [Your Live Demo Link]

---

## Technologies Used
- **HTML5**
- **CSS3**
- **JavaScript (ES6)**
- **React.js**

---

## How to Run Locally
```bash
# Clone the repository
git clone https://github.com/vikash4509/React-Counter-App.git

# Navigate into project folder
cd react-counter-app

# Install dependencies
npm install

# Start the development server
npm start
```
---

##
🧪 Challenges Faced & Solutions
Challenge: Maintaining counter state after page reload
Solution: Used localStorage to persist data.

Challenge: Disabling buttons at bounds
Solution: Conditional rendering & state checks.

## 📸 Screenshots
![Counter_Photo_01](images/Counter_Photo_01.jpg)


🔧 Feature List
Increment, decrement, reset counter value

Customizable step size

Upper/lower bounds with button disable

Toggle for allowing negative values

Dynamic text color based on state

Persist state with localStorage

🧮 Sample Input & Output
Action	Expected Output
Click +	Counter increases by step size
Click -	Counter decreases by step size
Change step size	Increment/Decrement changes accordingly
Reach upper bound	+ disabled
Reach lower bound	- disabled
Toggle negative off	Counter min = 0
Click reset	Counter = 0
