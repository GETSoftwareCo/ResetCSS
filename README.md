# GET Software - ResetCSS

![Version](https://img.shields.io/badge/version-0.0.1-blue.svg)
![License](https://img.shields.io/badge/license-MIT-green.svg)
![Size](https://img.shields.io/github/size/GETSoftwareCo/ResetCSS/reset.min.css)
[![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](https://github.com/GETSoftwareCo/ResetCSS/graphs/commit-activity)

**ResetCSS** is a modern, lightweight, and opinionated CSS reset and starter kit maintained by [GETSoftware Co.](https://getsoft.com.tr) It ensures consistent styling across different browsers and provides a solid foundation for your web projects with essential defaults and accessibility improvements.

## 🚀 Features

- **Consistent Box Model:** Applies `box-sizing: border-box` globally.
- **Modern Font Stack:** Uses system UI fonts for the best performance and native feel.
- **Accessibility Ready:** Improved focus states for keyboard navigation.
- **Form Controls:** Normalized styling for inputs, buttons, and textareas.
- **Responsive:** Basic responsive adjustments for mobile devices.
- **Customizable:** Built with CSS Variables for easy theming.

---

## 📦 Installation

### Option 1: CDN (Recommended)
You can use **jsDelivr** to include ResetCSS directly in your project without downloading anything.

Add this line to the `<head>` section of your HTML file **before** your own stylesheets:

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/GETSoftwareCo/ResetCSS@main/reset.min.css">
```


## Option 2: NPM
Install via npm for modern frontend workflows:

```Bash
npm install @getsoftwareco/resetcss
```

Then import it in your JavaScript or CSS entry point:

```JavaScript
import '@getsoftwareco/resetcss/reset.min.css';
```

## Option 3: Direct Download
Simply download the reset.min.css file from this repository and link it:

```Html
<link rel="stylesheet" href="path/to/reset.min.css">
```

## 🎨 Customization
ResetCSS uses CSS Custom Properties (Variables). You can easily override the default colors and settings in your own CSS file:

```CSS
:root {
    /* Override these variables in your main CSS file */
    --color-primary: #ff5722;       /* Change primary color */
    --color-link: #1e90ff;          /* Change link color */
    --color-background: #ffffff;    /* Change body background */
    --color-text: #212121;          /* Change text color */
}
```



## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request or open an issue for bugs and feature requests.

1. Fork the repository  
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)  
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)  
4. Push to the branch (`git push origin feature/AmazingFeature`)  
5. Open a Pull Request  

---

## 📄 License

This project is licensed under the MIT License – see the LICENSE file for details.

---

<p align="center">
Made with ❤️ by <a href="https://getsoft.com.tr">GETSoftware Co.</a>
</p>
