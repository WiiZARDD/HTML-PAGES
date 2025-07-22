# Minimalist Login Page

![Preview](https://i.imgur.com/DInGJjl.jpeg)

A clean and responsive, glass style login page built with HTML & CSS.
<p>Perfect for a sleek authentication UI or as a starter template.</p>

## Features

- Frosted glass backdrop with smooth blur effects  
- Modern “floating” box shadows  
- Fully responsive layout (desktop, tablet & mobile)  
- Accessible form markup with proper `<label>` tags  
- Google‑hosted “Archivo Black” font  
- Vanilla JS form handler stub for easy customization  

## Installation

1. **Clone this repo**  
   ```bash
   git clone https://github.com/WiiZARDD/HTML-PAGES/Minimalist-Glass
   cd Minimalist-Glass
   ```

2. **Open in browser**  
   Simply open `index.html` in your preferred browser, or run a local HTTP server:

   ```bash
   # Using Python 3:
   python -m http.server 8080
   ```

3. **Customize**  
   - Edit `styles.css` to tweak colors, blur strength, shadows, etc.  
   - Swap out the background image URL in your CSS for your own.  
   - Hook into `script.js` for real authentication logic.

## File Structure

```
minimalist-login-page/
├── index.html
├── styles.css
├── script.js
└── README.md
```

## Usage

1. Fill in **Username** and **Password** fields.  
2. Click **Login** to trigger the form’s submit handler in `script.js`.  
3. Click **Sign Up** (button stub) to wire up your registration flow.

## Customization

- **Background**: Change the `background` property on `<body>` in `styles.css`.  
- **Font**: Swap the Google‑Fonts `<link>` in `index.html` for any other typeface.  
- **Form Actions**: Update the `action="#"` attribute on the `<form>` to point at your API endpoint.

## Credits

- Built with ❤️ by [WiiZARDD](https://github.com/WiiZARDD)  
- Frosted glass effect inspired by modern UI design trends  
