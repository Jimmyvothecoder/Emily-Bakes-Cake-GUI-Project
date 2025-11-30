# Emily Bakes Cakes 🎂

A responsive bakery website showcasing delicious cakes and custom cake ordering options.

## Features

- 🏠 Interactive homepage with hero section
- 🍰 Menu showcase with various cake options
- 🎨 Custom cake ordering system
- 🛒 Shopping cart functionality
- 🔍 Search functionality
- 📱 Responsive design for mobile and desktop
- ⭐ Customer reviews section
- 📞 Contact information

## Project Structure

```
CIS_3343_Project/
├── EmilyBC.html          # Main homepage
├── addcakedecor.html     # Cake decorations page
├── order.html            # Order page
├── script.js             # JavaScript functionality
├── style.css             # Main stylesheet
├── style1.css            # Additional styles
├── cakedecor.css         # Cake decoration styles
└── cakepics/             # Image assets
```

## How to Run the Application

### Option 1: Open Directly in Browser (Simplest)

1. **Clone or download this repository:**
   ```bash
   git clone https://github.com/Jimmyvothecoder/CIS-3343-Project.git
   cd CIS-3343-Project
   ```

2. **Open the main HTML file:**
   - **On macOS:** 
     ```bash
     open EmilyBC.html
     ```
   - **On Windows:** 
     ```bash
     start EmilyBC.html
     ```
   - **On Linux:** 
     ```bash
     xdg-open EmilyBC.html
     ```
   
   Or simply double-click `EmilyBC.html` in your file explorer.

### Option 2: Use a Local Development Server (Recommended)

Using a local server prevents CORS issues and provides a better development experience.

#### Using Python (Built-in)

**Python 3.x:**
```bash
python3 -m http.server 8000
```

**Python 2.x:**
```bash
python -m SimpleHTTPServer 8000
```

Then open your browser and navigate to: `http://localhost:8000/EmilyBC.html`

#### Using Node.js (http-server)

1. **Install http-server globally:**
   ```bash
   npm install -g http-server
   ```

2. **Run the server:**
   ```bash
   http-server -p 8000
   ```

3. **Open in browser:** `http://localhost:8000/EmilyBC.html`

#### Using VS Code Live Server Extension

1. Install the "Live Server" extension in VS Code
2. Right-click on `EmilyBC.html`
3. Select "Open with Live Server"

## Technologies Used

- **HTML5** - Semantic markup
- **CSS3** - Styling and responsive design
- **JavaScript** - Interactive functionality
- **Font Awesome** - Icons

## Pages

1. **Home (EmilyBC.html)** - Main landing page with cake menu
2. **Cake Decorations (addcakedecor.html)** - Browse and select decorations
3. **Order (order.html)** - Place your cake order

## Browser Compatibility

- Chrome (recommended)
- Firefox
- Safari
- Edge
- Opera

## Contributing

Feel free to fork this project and submit pull requests for any improvements!

## License

This project is for educational purposes (CIS 3343 Project).

---

**Note:** This is a client-side web application. Do not try to run `script.js` with Node.js as it's designed to run in the browser.