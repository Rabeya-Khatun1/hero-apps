# 🚀 Hero IO – App Discovery Platform

Hero IO is a modern and responsive app discovery platform where users can explore popular applications, view detailed app information, install apps, and manage their installed apps.  
This project is designed to practice **React fundamentals, routing, state management, data visualization, and localStorage usage**, following real-world application behavior.

---

## 🔗 Live Project
- **Live Link:** [http://faded-bo-hero-apps08y.surge.sh/](http://faded-bo-hero-apps08y.surge.sh/)  
- **GitHub Repository:** [https://github.com/Rabeya-Khatun1/hero-apps](https://github.com/Rabeya-Khatun1/hero-apps)

---

## 🖼️ Project Preview
A clean, user-friendly, and fully responsive interface inspired by the provided Figma design.

![Hero IO Screenshot](https://i.ibb.co.com/ZzdQrMfX/Screenshot-2025-12-31-110911.png)

---

## 🛠️ Technologies Used
- **React** – Component-based UI development  
- **React Router DOM** – Client-side routing  
- **Recharts** – Charting and data visualization  
- **Tailwind CSS / DaisyUI** – Styling and responsive layout  
- **JavaScript (ES6+)** – Dynamic functionality  
- **LocalStorage** – Persistent app installation management  

---

## ✨ Project Overview
Hero IO displays a collection of featured apps using structured JSON data.  
Users can browse apps, search by name, view app details, install apps, and manage their installed apps.  
The application is fully responsive, with smooth navigation, real-time search, and interactive UI elements.

---

## 🔑 Core Features

### 🏠 Home Page
- Header with logo (clickable to navigate home), navigation links with active state, and contribution button linking to GitHub profile  
- Hero banner with center-aligned heading, description, and App Store / Play Store buttons  
- Three state cards showing key statistics  
- Top Apps section displaying 8 apps in a 4-column layout  
- “Show All” button navigating to All Apps page  

### 📱 All Apps Page
- Displays all apps from JSON data  
- Live, case-insensitive search by app title  
- Total app count displayed  
- “No App Found” message for empty search results  

### 📊 App Details Page
- App information including title, image, rating, reviews, and downloads  
- Install button:
  - Becomes disabled after installation  
  - Shows a success toast notification  
- Review chart using **Recharts**  
- Full app description section  

### 💾 Installation & LocalStorage
- Installed apps saved in **localStorage**  
- Prevents duplicate installation  
- “My Installation” page shows all installed apps  
- Uninstall feature removes apps from UI and localStorage  
- Toast notification on uninstall  

### 🔄 Sorting & Loading
- Sort apps by download count:
  - High → Low  
  - Low → High  
- Loading animations during page navigation and search operations  

### ❌ Error Handling
- Custom error page for invalid routes  
- App Not Found message in app details page  
- Route reload support after deployment (no 404 errors)  

---

## 📦 Dependencies
- React  
- React Router DOM  
- Recharts  
- Tailwind CSS  
- DaisyUI  

---

## 🔄 Hero IO – Beginner Workflow

This section guides first-time users on how to navigate and use the Hero IO web application.

### 1. Landing on the Home Page
- When you open the website, the **Header** shows:  
  - **Logo**: Click to navigate back to the Home Page  
  - **Navigation Links**: Home | Apps | Installation  
  - **Contribution Button**: Click to visit the GitHub profile  
- The center-aligned **Hero Banner** includes:  
  - Main title and short description  
  - App Store / Play Store buttons  

### 2. Understanding Key Stats
- Below the Hero Banner, **3 State Cards** display:  
  - Total apps  
  - Total downloads  
  - Average rating  
- This provides a quick visual overview of app data.  

### 3. Browsing Top Apps
- The **Top Apps Section** shows 8 featured apps in a 4-column layout.  
- Each card displays:  
  - App Image  
  - Title  
  - Downloads  
  - Average Rating  
- Click a card to view **App Details Page**  
- Click **“Show All”** to see all available apps  

### 4. Exploring All Apps
- **All Apps Page** displays every app from JSON data  
- Use the **search bar** to find apps (live, case-insensitive)  
- Search results filter apps instantly  
- If no match is found, a **“No App Found”** message appears  

### 5. Checking App Details
- On the **App Details Page**:  
  - View App Image, Title, Rating, Reviews, and Downloads  
  - **Install Button**:  
    - Click to install the app  
    - Shows a success toast notification  
    - Becomes disabled after installation and shows “Installed”  
  - **Review Chart**: Visual representation of app ratings using Recharts  
  - Full app description section  

### 6. Managing Installed Apps
- **My Installation Page** displays all installed apps  
- **Uninstall Button** removes apps from both UI and localStorage  
- Toast notification confirms uninstallation  
- Installed apps are saved in **localStorage** for persistence  

### 7. Sorting & Navigation
- Sort apps by download count (High → Low / Low → High)  
- Loading animations are displayed during:  
  - Page navigation  
  - Search operations  

### 8. Handling Errors / Invalid Routes
- Custom error page for invalid URLs  
- App details page shows **“App Not Found”** if the app does not exist  
- Page reloads after deployment will work without 404 errors  

---

### ✅ Summary – First Time User Flow
1. Open Hero IO → see Hero Banner & Stats  
2. Browse Top Apps or click “Show All”  
3. Search or filter apps  
4. Click an app → check details → install if desired  
5. Go to “My Installation” → manage installed apps  
6. Sort apps by downloads → explore smoothly  
7. Encounter invalid route? → custom error message displayed  



## 📘 What I Learned
- Structuring a large React application  
- Dynamic routing and route protection  
- State management and localStorage integration  
- Implementing charts and analytics with Recharts  
- Building responsive UI from Figma  
- Handling loading states, search functionality, and edge cases  

---

## 👩‍💻 Author
**Rabeya Khatun** – Frontend Developer (Learner)
