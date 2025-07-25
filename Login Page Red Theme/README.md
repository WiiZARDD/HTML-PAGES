# Red Theme Login Page

A sleek modern red themed login/signup page built with HTML and CSS. 

![Preview](https://i.imgur.com/n3oa6xi.png)

---

## Features

- Minimalist centered layout inspired by modern login flows
- Login or Signup flow with custom-styled red buttons
- Custom logo branding centered at the top
- Responsive design optimized for desktop and mobile devices
- Sticky top navigation bar with GitHub-style “Fork Project” button
- Clean input fields with subtle transitions and light shadows
- Forgot password link included for future recovery flow
- Ready for back-end integration (Node.js, Express, sessions, etc.)

## Installation

1. Clone or download this repository:
   ```bash
   git clone https://github.com/WiiZARDD/Login-Page-Red-Theme
   ```
2. Navigate into the project folder:
   ```bash
   cd Login-Page-Red-Theme
   ```
3. Open the `index.html` file in your browser:
   ```bash
   open index.html
   ```

## Usage

- Edit `index.html` to change text, links, or images.
- Modify `./styles/styles.css` to customize colors, spacing, or typography.
- Replace the logo and placeholders with your own assets if needed.

## File Structure

```
Login-Page-Red-Theme/
├── assets/
│   ├── ico.png               # Favicon or branding icon
│   └── logo.png              # Center logo displayed on login page
├── styles/
│   └── styles.css            # All CSS styles for layout and theme
├── js/
│   └── script.js             # (Optional) Future JS interactivity
├── index.html                # Main login page HTML
└── README.md      # Project documentation
```

## Customization

- **Logo**: Replace `logo.png` or `ico.png` in the `./assets/` folder to apply your own brand image.  
  Update `<img src="./assets/logo.png">` in `index.html` to reflect any file name changes.

- **Theme Colors**: Modify red gradient buttons, hover effects, and navigation styling by editing class styles in `./styles/styles.css`.  
  You can also apply your own CSS variables or utility classes if using a framework like Tailwind.

- **Fonts**: Change the `<link>` to your preferred Google Font in the `<head>` of `index.html`, or override the font-family in `styles.css`.

- **Fork Button**: Customize or remove the GitHub fork button at the top-right. Update its link or styling inside `index.html`.

- **Form Labels & Text**: Edit placeholder text, labels, and button text directly inside `index.html` to fit your platform's messaging.

