# 📝 Atomic Blog
A simple blog application where you can **create**, **archive**, **restore**, and **delete** blog posts.
Built with **Create React App (CRA)** and designed to practice **advanced React state management and performance optimization patterns**.

## 🚀 Features
- ✍️ Create your own blog posts
- 📦 Archive posts (hide without deleting)
- 🔄 Restore archived posts
- 🗑️ Permanently delete posts
- 🌓 Dark & light theme toggle
- ⚛️ Global state management using **Context API + useReducer**
- 🧠 Performance optimizations using:
  - React.memo
  - useMemo
  - useCallback
- 🧪 Multiple implementations available to compare approaches
- 📱 Desktop-first (not responsive yet)

## 🛠️ Tech Stack
- React (Create React App)
- Context API
- useReducer
- React.memo
- useMemo
- useCallback
- CSS

## 📂 Project Structure & Versions
Inside the `src` folder, you can find **different versions of the app**, each showcasing a different approach to state management and optimization:
- Basic Context API usage
- Context API + useReducer
- Optimized versions using memo, useMemo, and useCallback

This structure allows you to compare different patterns and understand when optimizations are actually needed.

## 🎯 Project Purpose
This project was created to practice:
- Context API as a main state management solution
- useReducer for predictable and scalable state updates
- Preventing unnecessary re-renders
- Correct usage of memoization techniques
- CRUD operations in React
- Theme toggling with global state

## ⭐Installation
```bash
git clone https://github.com/Sogand-mohamadiPour/atomic-blog.git
cd atomic-blog
npm install
npm start
```

## 📌 Notes
- This is a learning-focused project, not production-ready.
- Responsiveness is not implemented yet.
- Each version exists for educational comparison purposes.
