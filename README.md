# 🍽️ Forkify Recipe App

## 📌 Overview
Forkify is a JavaScript-based recipe search application that allows users to search for recipes, view details, and save their favorite recipes. It fetches data from the **Forkify API** and provides a modern UI for an enhanced cooking experience.

---

## 🚀 Features
- 🔎 **Search recipes** by keywords (e.g., "pasta", "pizza").
- 📜 **View recipe details** including ingredients & cooking time.
- ❤️ **Bookmark favorite recipes** for easy access.
- 📝 **Add custom recipes** and save them locally.
- 🎭 **Dynamic UI updates** without page reloads.

---

## 🛠️ Tech Stack
- **Frontend:** JavaScript (ES6+), HTML, CSS, Sass
- **State Management:** JavaScript Modules & Local Storage
- **API:** [Forkify API](https://forkify-api.herokuapp.com/)
- **Build Tool:** Parcel.js

---

## 📂 Project Structure
```
📦 Forkify
├── 📂 src
│   ├── 📂 js
│   │   ├── model.js      # Handles API fetching & state management
│   │   ├── view.js       # Manages UI updates & rendering
│   │   ├── controller.js # Controls app logic
│   ├── 📜 index.html     # Main HTML file
│   ├── 📜 style.scss     # Main SCSS file
├── 📜 package.json       # Project dependencies
├── 📜 README.md          # Documentation
```

---

## 🔧 Setup & Installation
### **1️⃣ Clone the Repository**
```bash
git clone https://github.com/YOUR_GITHUB_USERNAME/Forkify.git
cd Forkify
```

### **2️⃣ Install Dependencies**
```bash
npm install
```

### **3️⃣ Run the Application**
```bash
npm start  # Starts development server
```

### **4️⃣ Build for Production**
```bash
npm run build  # Creates optimized `dist/` folder
```

---

## 🖥️ Usage
1. Enter a **recipe keyword** in the search bar.
2. Click on a **recipe** to view details.
3. **Bookmark** your favorite recipes.
4. **Add your own recipes** (saved locally).

---

## 🌍 Deployment
### **Deploy to Netlify**
1. Build the project: `npm run build`
2. Upload `dist/` folder to [Netlify](https://www.netlify.com/)
3. Done! 🎉

### **Deploy to GitHub Pages**
```bash
git add .
git commit -m "Deploy Forkify"
git push origin main
gh-pages -d dist
```

---

## 📜 License
This project is open-source under the **MIT License**.

---

## 🙌 Acknowledgments
- **Jonas Schmedtmann** for the original course inspiration.
- **Forkify API** for providing recipe data.

---

💡 **Future Enhancements:**
- User authentication for saving personal recipes.
- Dark mode support.
- Advanced filtering options (vegan, gluten-free, etc.).

🚀 **Feel free to contribute or suggest improvements!** 😊
