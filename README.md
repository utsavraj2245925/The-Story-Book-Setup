# Story-book Design System Setup 

## 📌 Project Overview
This project demonstrates **Component Driven Development (CDD)** using **Storybook** in a React/Next.js environment.

Instead of building UI components directly inside the main application, components are developed, tested, and documented in isolation using Storybook—just like in companies such as Spotify and Airbnb.

---

## 🚀 Features

### ✅ Level 1 (Beginner)
- Installed and configured Storybook
- Created reusable UI components:
  - Button
  - Input Field
  - Product Card
- Built stories for each component
- Run Storybook independently from the main app

---

### ⚙️ Level 2 (Intermediate)
- Added **Args (Props Controls)** for dynamic interaction
- Button component supports:
  - Primary
  - Secondary
  - Disabled states
- Integrated **Light/Dark mode preview**

---

### 🚀 Level 3 (Advanced)
- Built Storybook as a static site
- Deployed to a live platform (Vercel / Chromatic)

---

## 🛠️ Tech Stack
- React / Next.js
- Storybook
- CSS / Tailwind (if used)
- Vercel / Chromatic (for deployment)

---

## 📂 Project Structure

├── components/
│ ├── Button.jsx
│ ├── Input.jsx
│ └── ProductCard.jsx
│
├── stories/
│ ├── Button.stories.jsx
│ ├── Input.stories.jsx
│ └── ProductCard.stories.jsx
│
├── .storybook/
├── package.json


---

## ⚡ Getting Started

### 1. Install dependencies
```bash

npm install
2. Run Storybook
npm run storybook
3. Build Storybook
npm run build-storybook
🌐 Live Preview

👉 Add your deployed Storybook link here
Example: https://your-storybook.vercel.app

🎯 Learning Outcomes
Component isolation & reusability
Design system fundamentals
UI consistency across applications
Faster frontend development workflow
📸 Screenshots

(Add screenshots of your Storybook UI here)

🤝 Contributing

Feel free to fork and improve this project.

📄 License

This project is open-source and available under the MIT License.


---

# 📄 prompt.md

```markdown
# 🧠 Project Prompt – Storybook Design System

## 🎯 Objective
Build a scalable frontend component system using Storybook, following Component Driven Development (CDD) principles.

---

## 📌 Problem Statement
In large-scale applications, UI components must be:
- Reusable
- Testable
- Consistent

Instead of building components directly inside the app, they should be developed in isolation using Storybook.

---

## 🧩 Requirements

### 🔰 Level 1 (Beginner)
- Initialize Storybook in a React/Next.js project
- Create at least 3 components:
  - Button
  - Input Field
  - Product Card
- Write stories for each component
- Run Storybook independently

---

### ⚙️ Level 2 (Intermediate)
- Implement **args (props controls)** in Storybook
- Button component must support:
  - Primary
  - Secondary
  - Disabled states
- Add **Dark Mode / Light Mode preview**

---

### 🚀 Level 3 (Advanced)
- Build Storybook as a static site
- Deploy to:
  - Vercel OR
  - Chromatic
- Share the live URL

---

## 🧠 Key Concepts
- Component Driven Development (CDD)
- Design Systems
- Storybook UI Explorer
- Props & Variants (Args)
- Theming (Dark/Light Mode)

---

## 📦 Expected Output
- Working Storybook setup
- Interactive component library
- Live deployed Storybook link
- Clean GitHub repository with documentation

---

## 💡 Bonus Ideas
- Add more components (Navbar, Modal, Cards)
- Use Tailwind or Styled Components
- Add accessibility support (ARIA)
- Add Storybook addons (Docs, Controls, Actions)

---

## 📍 Goal
Create a production-ready UI component system that can scale and be reused across multiple applications.
