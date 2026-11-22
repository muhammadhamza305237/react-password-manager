# 🔐 Password Manager

A responsive client-side password manager built with **React**, **Tailwind CSS**, and **Vite**, using browser `localStorage` for data persistence.

**Live Demo:** https://password-manager-roan-three.vercel.app

## 🛠️ Tech Stack
- **Framework:** React.js (Vite)
- **Styling:** Tailwind CSS
- **State & Persistence:** React hooks (`useState`, `useEffect`, `useRef`), Browser `localStorage`
- **Utilities & UI Feedback:** `uuid`, `react-toastify`, Lordicon, custom static icons

## ✨ Key Features
- **Add & Validate Credentials:** Save website URLs, usernames, and passwords with length validation and unique IDs via `uuid`.
- **Show / Hide Password Toggle:** Toggle password input visibility between masked (`password`) and plain text (`text`).
- **Credentials Table:** View saved credentials with external website links (`target="_blank"`) or a fallback message when empty.
- **One-Click Clipboard Copy:** Copy site URLs, usernames, or passwords directly using `navigator.clipboard.writeText()`.
- **Edit & Delete Entries:** Load entries back into the form to edit or remove entries after confirmation.
- **Toast Notifications:** Instant feedback for saves, copies, deletions, and validation errors via `react-toastify`.

## 🚀 How to run locally
1. Clone the repository
2. Run `npm install`
3. Run `npm run dev`