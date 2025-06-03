
# 🎨 TailwindCSS 3 Days BootCamp by LetsUpgrade 📖 ✒️

<br>

### <p align="center"> **Day 1 Learning** </p>

<br>

## 🧠 Prerequisite

### ✅ Know about these things

- 🟦 Border  
- 🎨 Background  
- 📏 Margin  
- 📦 Padding  
- 📐 Flexbox  

<br>

## 💡 What is Tailwind?

- 🛠️ Utility-first CSS framework — utility classes are basic building blocks like margin, padding, etc.
- 📦 Tailwind only gives you classes to build custom designs.

<br>

## ❓ Why Tailwind?

- 🚀 It’s the **market standard** right now.
- 🌍 A **very large community** supports it.

<br>

## 🧰 How to Use Tailwind? | How to Install?

➡️ Go to [TailwindCSS Website](https://tailwindcss.com) and click on **“Get Started”**.

<br>

### 🛑 We can install TailwindCSS in 3 ways:

---

### 1️⃣ Using CDN *(⚠️ Not Recommended)*

- 🌐 Go to the **Play CDN** tab on the TailwindCSS website.
- 🧩 Copy the script tag and place it in the `<head>` of your `index.html` file.

---

### 2️⃣ **Using Tailwind CLI** 🧑‍💻

- 🧭 Go to the **Using Vite** tab on the website.
- ⚙️ Before running commands, make sure **Node.js** is installed.
- 🔍 Check Node version using:  
  ```bash
  node -v
  ```

#### 📜 Commands to run:

```bash
npm install tailwindcss @tailwindcss/cli
```

1. 📄 Create a CSS file and paste:  
   ```css
   @import "tailwindcss";
   ```
2. ▶️ Run the following command:  
   ```bash
   npx @tailwindcss/cli -i ./src/input.css -o ./src/output.css --watch
   ```

> 💡 **Note:** Tailwind Play is a place where we can experiment with TailwindCSS easily.


## 🧩 Let's Understand Some Utility Classes

- 🅰️ `text`  
- 🅱️ `font`  
- 🎨 `background`  
- 🧱 `border`  
- 📏 `margin`  
- 📦 `padding`  

<br>


## 🔄 TailwindCSS vs Bootstrap

- ⚫ Bootstrap doesn't have **built-in dark/light theme toggle** support.
- 🌗 Tailwind makes it easier to build and toggle **dark/light modes**.

<br>

### <p align='center'>📘 **Day 2 Learning**</p> 

<br>



## 🔧 Crafting Pages and Components

- ✨ `hover:` in Tailwind CSS  
- 🎞️ `transition` in Tailwind CSS  
- ⏱️ `duration` in Tailwind CSS  
- 🧰 `flexbox` in Tailwind CSS  
- 🧮 `grid` in Tailwind CSS  

<br>

### 📱 Responsive Classes in Tailwind CSS

- 🧱 `grid-cols-1 / 2 / 3`  
- 🔁 `flex-wrap`  


> 💡 **Note:**  
> If you apply `dark:bg-white`, the background will change to white **only when the system theme is set to dark**.  

<br>

### 🧵 `@apply`  
Use `@apply` in Tailwind CSS to combine utility classes in your custom CSS for cleaner and more maintainable code.
