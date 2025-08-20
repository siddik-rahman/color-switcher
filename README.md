# 🎨 Color Switcher

A simple JavaScript project that changes the background color randomly with a single click.  

---

## 📌 Features  
- Generates **random RGB color** using JavaScript  
- Updates the background color dynamically  
- Easy to use and beginner-friendly project  

---

## 🛠️ Technologies Used  
- HTML5  
- CSS3  
- JavaScript  

---

## 📂 Project Structure  
color-switcher/
│── index.html
│── style.css
│── script.js
│── README.md



---

## ▶️ How to Run  
1. Clone this repository  
   ```bash
   git clone https://github.com/siddik-rahman/color-switcher.git
2. Open index.html in your browser

3. Click the button to see the background color change 🎉  
---  


📖 How It Works
 - JavaScript function generates 3 random numbers (0–255) for Red, Green, and Blue

- Combines them into an rgb(r, g, b) color format

- Applies the color to the background of the page  
---  

```JavaCript  
let r = Math.floor(Math.random() * 256);
let g = Math.floor(Math.random() * 256);
let b = Math.floor(Math.random() * 256);

let color = `rgb(${r}, ${g}, ${b})`;
document.body.style.backgroundColor = color;

```


## 🚀 Live Demo  
🔗 [View Live](https://siddik-rahman.github.io/color-switcher/)

## 🧑‍💻 Author
 Siddikur Rahman  
## 🌐 GitHub: [siddik-rahman](https://github.com/siddik-rahman)

## 📧 Email: siddik8976@gmail.com


📜 License
This project is free to use and modify.