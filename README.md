# 🖥️ **Electron Templates**

Welcome to **Electron Templates**! 🚀 This repository contains a collection of templates to quickly start projects with **Electron**. Each template is preconfigured to simplify development and reduce initial setup time. These templates are inspired by [Electron⚡️Vite](https://electron-vite.github.io/) and optimized to offer a smoother, modern development experience.

---

## 📂 **Available Templates**

The repository includes the following templates:

| 🌟 Template                 | 📄 Description                                                                         |
| --------------------------- | -------------------------------------------------------------------------------------- |
| **React + TypeScript**      | Template for building an Electron app with React and TypeScript.                       |
| **React**                   | Template for building an Electron app with React and JavaScript.                       |
| **JavaScript + TypeScript** | Template for building an Electron app with a combination of JavaScript and TypeScript. |
| **JavaScript**              | Basic template for building an Electron app with JavaScript only.                      |

---

## 🚀 **Installation and Usage**

### 1. **Clone the Repository**

```bash
git clone git@github.com:n3bulat3ch/electron-templates.git
```

### 2. **Navigate to the Folder**

```bash
cd electron-templates
```

### 3. **Select a Template**

Copy the template you want to use into a new project folder:

```bash
cp -r templates/electron-react-ts/ ../my-new-project
```

### 4. **Install Dependencies**

```bash
cd ../my-new-project
npm install
```

### 5. **Start the Project**

```bash
npm start
```

> **Troubleshooting:**  
> If you encounter the following error when running `npm run dev` or `pnpm dev`:
>
> ```
> Error: Electron failed to install correctly, please delete node_modules/electron and try installing again
> ```
>
> You can resolve the issue by running:
>
> ```bash
> node node_modules/electron/install.js
> ```

---

## 🛠️ **Project Structure**

```bash
electron-templates/
├── templates/
│   ├── electron-react/           # React + JS template
│   ├── electron-react-ts/        # React + TypeScript template
│   ├── electron-vanilla-ts/      # JS + TypeScript template
│   └── electron-vanilla/         # JS template
├── README.md
└── .gitignore
```

---

## 🌐 **Technologies Used**

-   [Electron](https://www.electronjs.org/)
-   [React](https://react.dev/)
-   [TypeScript](https://www.typescriptlang.org/)
-   [JavaScript](https://developer.mozilla.org/)

---

## 📌 **Inspiration**

This repository is inspired by [Electron⚡️Vite](https://electron-vite.github.io/) and adapted to simplify development with different tech stacks.

---

## 🤝 **Contributions**

Contributions are welcome! If you have an improvement or want to add a new template, feel free to open a **Pull Request**.

---

## 📝 **License**

This project is licensed under the **MIT** license.

---

💡 **Start building with Electron today!** 😎
