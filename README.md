# DRUM-KIT-GAME
This project is a simple drum kit web application. It allows users to play different drum sounds by either clicking on the drum buttons displayed on the webpage or by pressing corresponding keys on the keyboard.

The project utilizes JavaScript to add event listeners to the drum buttons and the document. When a drum button is clicked or a key is pressed, it calls the makesound() function, passing the corresponding key as an argument, to play the associated drum sound. It also calls the buttonAnimation() function to add a temporary "pressed" class to the active button, creating a visual effect.

The makesound() function uses a switch statement to determine which drum sound to play based on the provided key. It creates an Audio object with the corresponding sound file path and plays it.

The buttonAnimation() function adds the "pressed" class to the button element associated with the current key, triggering a CSS animation effect. After a short delay of 100 milliseconds, it removes the "pressed" class to revert the button to its original state.

Overall, this project provides an interactive drum kit experience on the web, allowing users to play drum sounds and see visual feedback when interacting with the drum buttons or keyboard keys.
