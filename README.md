# 🍽️ Foodpanda Style Responsive Navbar

This project is a **Foodpanda-inspired responsive navbar** built using **Bootstrap 5.3**, **Font Awesome**, and **custom CSS**. It mimics the clean, modern look of Foodpanda's top navigation bar with fully responsive behavior for both desktop and mobile devices.

---

## ✨ Features

### ✅ Desktop View (`≥ 1200px`)
- Left: **Logo**
- Right:
  - `Log in` button
  - `Signup for free delivery` button
  - Language selector with dropdown (`EN`)
  - Cart icon

### ✅ Mobile View (`< 1200px`)
- Left: **User icon**
- Center: **Logo**
- Right: **Cart icon**
- No toggle menu — clean and simple layout

---

## 🧱 Technologies Used

- [Bootstrap 5.3](https://getbootstrap.com/)
- [Font Awesome 6](https://fontawesome.com/)
- Custom CSS

---

## 📁 File Structure

```
/project-folder
├── index.html           # Navbar HTML file
├── style.css            # Custom button styling
├── foodpanda-logo.png   # Logo image
└── README.md            # Project description
```

---

## 🔧 How to Use

1. Clone or download this repository
2. Open `index.html` in your browser
3. Customize logo, links, or styling as needed

---

## 🔍 Example Snippet (Mobile Header)

```html
<!-- Mobile header -->
<div class="d-flex justify-content-between align-items-center px-3 py-2 shadow-sm d-xl-none">
  <a href="#"><i class="fa-solid fa-user fs-4 text-dark"></i></a>
  <a href="#"><img src="./foodpanda-logo.png" style="height: 35px;" /></a>
  <a href="#"><i class="fa-solid fa-bag-shopping fs-4 text-secondary"></i></a>
</div>
```



## 📜 License

This project is open-source and free to use under the [MIT License](https://opensource.org/licenses/MIT).

---

## 👨‍💻 Credits

Created by [Abdul Hadi]  
Inspired by [foodpanda.com](https://www.foodpanda.com/)
