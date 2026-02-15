This HTML document brings to life an interactive, floating-keyboard-like interface for the “RTP Hackathon 2025” event. Let’s dive into what each part does:

### 1. **HTML Structure**
* **Text Box**: Imagine an input box (<input>) where you can type using buttons that pop up on the screen. This box shows you exactly what you’re typing.
* **Buttons**: Picture a bunch of buttons representing letters (A-Z) and special keys like “Space” and “Backspace.” They sport a light blue background with white text, and they change appearance when you hover over them.
* 
### 2. **CSS Styles**

* **Body & Background**: The background is a sleek black, making the text and buttons really pop.
* **Text Box**: The input box is big and has a white border, making it easy to read.
* **Buttons**: These buttons have a cool shadow effect and rounded corners. They turn light green when you hover over them, adding a nice touch to the interface.
* **Positioning**: The buttons are positioned absolutely, so they float around freely in the window.
* 
### 3. **JavaScript Functionality**

* **Typing Simulation**: Click a button, and the letter appears in the text box. Hit “Backspace,” and it deletes the last letter. As you type, a dynamic text (preText) updates to show what’s left of “RTP HACKATHON 2025.”
* **Text Handling**: The preText (“RTP HACKATHON 2025”) is your guide. As you type, it updates to reveal the part you haven’t typed yet.
* **Button Movement**: The buttons aren’t just sitting there; they move around! Each button has a speed for both X and Y directions, and their positions update regularly. When they hit the screen’s edge, they bounce off, creating a fun, dynamic effect.
* **Button Speed Increase**: Every time you click a button, its speed boosts by 1.5 times. So, the more you click, the faster they go.
* 
### 4. **Additional Details**
* **Random Initial Positioning**: When you load the page, the buttons start off at random spots on the screen.
* **Button Speed Update**: Each key press updates the button speed, making them move faster as you interact with them.

In a nutshell, this page offers a playful typing experience where buttons dance around, and your typing is tied to the reference text (“RTP HACKATHON 2025”). The whole interaction is visually captivating thanks to the lively button movements and the text box updates.

