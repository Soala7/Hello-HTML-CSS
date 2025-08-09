# 🎨 Hello HTML & CSS

![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white&style=for-the-badge)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white&style=for-the-badge)
![VS Code](https://img.shields.io/badge/VS%20Code-007ACC?logo=visualstudiocode&logoColor=white&style=for-the-badge)

Welcome to the **Hello HTML & CSS** repository!  
This repo will help you set up your environment and start creating beautiful web pages from scratch. Perfect for beginners! 🚀

---

## 🧰 What You’ll Need
- **VS Code** (Text editor) → [Download Here](https://code.visualstudio.com/)
- A web browser (e.g. Chrome, Firefox, Edge)

---

## 🛠 Installation & Setup

### 1️⃣ Install VS Code
- Go to [VS Code website](https://code.visualstudio.com/).
- Download for your operating system.
- Install using the default settings.

---

### 2️⃣ Create Your First HTML & CSS Project
1. Open **VS Code**.
2. Create a new folder for your project (e.g. `hello-html-css`).
3. Create two files:
   - `index.html`
   - `style.css`

---

### 3️⃣ Add HTML Code
Inside `index.html`:
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Hello HTML & CSS</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <h1>Hello, World!</h1>
    <p>Welcome to HTML & CSS learning.</p>
</body>
</html>
body {
    font-family: Arial, sans-serif;
    text-align: center;
    margin-top: 50px;
    background-color: #f0f0f0;
}

h1 {
    color: #e34f26;
}

p {
    color: #1572b6;
}
