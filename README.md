# Interactive Heart Activity

An educational interactive web application that allows users to explore the different parts of the human heart through clickable SVG elements.

## Features

- **Interactive Heart Parts**: Click on any heart part to see its name displayed
- **Visual Feedback**: Hover effects with glowing outlines and color changes
- **Educational**: Learn the names and locations of heart components
- **Responsive Design**: Works on different screen sizes

## Heart Parts Included

- **Atria**: Left Atrium, Right Atrium
- **Ventricles**: Left Ventricle, Right Ventricle
- **Blood Vessels**: Aorta, Pulmonary Artery, Anterior Vena Cava, Posterior Vena Cava
- **Valves**: Atrioventricular Valve, Semilunar Valve
- **Background Elements**: Ignore parts (non-interactive, for visual context)

## How to Use

1. **Open the Application**: 
   - Visit the live demo (if hosted) or run locally
   - The heart will be displayed with all parts visible

2. **Interact with Heart Parts**:
   - **Hover** over any heart part to see a glowing outline
   - **Click** on a heart part to see its name displayed above the heart
   - **Click** on the background to reset the display

3. **Visual Indicators**:
   - Gray outlines show clickable areas
   - Gold/yellow glow appears on hover
   - Active parts remain highlighted until another is selected

## Running Locally

### Option 1: Python HTTP Server (Recommended)
```bash
# Navigate to the project directory
cd path/to/interactive-heart-activity

# Start a local server
python3 -m http.server 8000

# Open your browser and go to:
# http://localhost:8000
```

### Option 2: Node.js HTTP Server
```bash
# If you have Node.js installed
npx serve .
# or
npx http-server .
```

### Option 3: Direct File Opening
- Simply open `index.html` in your browser
- Note: Some browsers may block SVG loading due to security restrictions

## File Structure

```
interactive-heart-activity/
├── index.html              # Main application file
├── README.md              # This file
├── Anterior Vena Cava.svg
├── Antrioventicular Valve.svg
├── Aorta.svg
├── Ignore-1.svg
├── Ignore-2.svg
├── Ignore.svg
├── Left Atrium.svg
├── Left Ventricle.svg
├── Posterior Vena Cava.svg
├── Pulmonary Artery.svg
├── Pulmonary Veins.svg
├── Right Atrium.svg
├── Right Ventricle.svg
└── Semilunar Valve.svg
```

## Technical Details

- **Frontend**: HTML5, CSS3, JavaScript (Vanilla)
- **Graphics**: SVG (Scalable Vector Graphics)
- **No Dependencies**: Pure web technologies, no frameworks required
- **Browser Support**: Modern browsers with SVG support

## Educational Use

This application is perfect for:
- **Biology Classes**: Teaching heart anatomy
- **Medical Education**: Basic cardiac structure introduction
- **Interactive Learning**: Engaging students with visual and interactive elements
- **Self-Study**: Individual learning of heart components

## Contributing

Feel free to:
- Report bugs or issues
- Suggest improvements
- Add more heart parts or features
- Improve the visual design

## License

This project is open source and available under the [MIT License](LICENSE).

---

**Note**: This is an educational tool and should not be used for medical diagnosis or treatment purposes. 