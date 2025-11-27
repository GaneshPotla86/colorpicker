# Color Picker — README

## 📌 Project Overview
Color Picker is a simple and responsive web application that allows users to change the background color of the page by clicking preset color buttons.  
It also displays the selected color’s hex code.  
This project is built using **HTML, CSS, JavaScript**, and **Bootstrap**.

---

## 🎨 Features
- Click any button to change the background color
- Shows the selected background color hex code
- Clean and responsive layout using Bootstrap
- Beginner-friendly and easy to extend

---

## 📁 Project Structure
```
color-picker/
├─ index.html
├─ css/
│  └─ styles.css
├─ js/
│  └─ script.js
└─ README.md
```

---

## 🚀 Installation
1. Clone the repository:
```
git clone https://github.com/<your-username>/color-picker.git
```
2. Navigate to the folder:
```
cd color-picker
```
3. Open the `index.html` file in any browser.

---

## 🧑‍💻 Usage
- Click any color button.
- The entire background changes to that color.
- The selected hex code updates automatically on the screen.

---

## 🔧 How to Add a New Color
### Add button in **index.html**
```html
<button id="button5" class="b5" onclick="button5()">#ffcc00</button>
```

### Add function in **script.js**
```javascript
function button5() {
    const hex = "#ffcc00";
    document.getElementById("colorPickerContainer").style.backgroundColor = hex;
    document.getElementById("selectedColorHexCode").textContent = hex;
    document.getElementById("selectedColorHexCode").style.color = "blue";
}
```

---

## 💡 Future Enhancements
- Add input color picker
- Add copy-to-clipboard button
- Add smooth background fade animation
- Save selected color in localStorage

---

## 📜 License
This project is under the **MIT License**.

