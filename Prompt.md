# 🧠 Project Prompt – Storybook Setup (Component Driven Development)

## 🎯 Objective
The goal of this project is to implement **Component Driven Development (CDD)** using Storybook in a React/Next.js application.

Instead of building UI components inside the main app, we develop and test them in isolation to ensure:
- Reusability
- Scalability
- Visual consistency

---

## 📌 Background
In large-scale companies like Spotify and Airbnb, frontend teams use tools like **Storybook** to create a centralized **design system**.

This approach helps teams:
- Build components independently
- Test UI variations easily
- Maintain consistency across the application

---

## 🧩 Project Requirements

### 🔰 Level 1 (Beginner)
- Install Storybook in an existing React/Next.js project:
  ```bash
  npx storybook@latest init
  Create at least 3 reusable components:
Button
Input Field
Product Card
Write stories for each component
Run Storybook independently using:

⚙️ Level 2 (Intermediate)
Implement Args (Props Controls) in Storybook
Button component supports:
Primary
Secondary
Disabled states
Enable interactive controls panel
Add Light Mode / Dark Mode support
🚀 Level 3 (Advanced)

Build Storybook as a static application:

npm run build-storybook
Deploy the build to:
Vercel (Completed)
Provide a live deployed URL
🧠 Key Concepts Covered
Component Driven Development (CDD)
Storybook UI Explorer
Props & Variants (Args)
Component Isolation
Theming (Dark/Light mode)
Static Deployment
📦 Deliverables
Functional Storybook setup
Reusable UI components
Interactive stories with controls
Live deployed Storybook link
GitHub repository with documentation
💡 Optional Enhancements
Add more components (Navbar, Modal, Cards)
Integrate Tailwind CSS
Add Storybook Addons (Docs, Actions, Controls)
Improve accessibility (ARIA roles)
📍 Final Goal

To build a production-ready UI component library that can be reused across multiple applications and teams.
