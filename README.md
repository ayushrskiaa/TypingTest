# ⌨️ Typing Test

Welcome to the Typing Test project! This application helps you practice and improve your typing skills by providing randomly selected paragraphs to type. It tracks your typing speed (WPM - Words Per Minute), the number of mistakes, and the number of characters typed correctly (CPM - Characters Per Minute).

## 📁 Project Structure

- `index.html`: The main HTML file that contains the structure of the typing test application.
- `script.js`: The JavaScript file that contains the logic for the typing test, including loading paragraphs, tracking typing progress, and calculating WPM and CPM.
- `style.css`: The CSS file that contains the styles for the typing test application.

## ✨ Features

- 📝 Randomly selects a paragraph for the user to type.
- ⏱️ Tracks the time left, mistakes, WPM, and CPM.
- ✅ Highlights correct and incorrect characters as the user types.
- 🔄 Allows the user to reset the test and try again.

## 🚀 Usage

1. Clone the repository or download the project files.
2. Open `index.html` in a web browser.
3. Start typing the displayed paragraph in the input field.
4. The application will track your progress and display your typing speed, mistakes, and characters typed correctly.
5. Click the "Try Again" button to reset the test and load a new paragraph.

## 🛠️ Code Overview

### HTML

The HTML file (`index.html`) contains the structure of the typing test application, including the input field, the paragraph to type, and the result details.

### CSS

The CSS file (`style.css`) contains the styles for the typing test application, including the layout, colors, and animations.

### JavaScript

The JavaScript file (`script.js`) contains the logic for the typing test application. Key functions include:

- `loadParagraph()`: Loads a random paragraph from the `paragraphs` array and displays it.
- `initTyping()`: Handles the typing logic, including tracking the typed characters, mistakes, and updating the WPM and CPM.
- `initTimer()`: Handles the countdown timer for the typing test.
- `resetGame()`: Resets the typing test and loads a new paragraph.

## 📄 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgements

- The paragraphs used in this project are fictional and created for the purpose of this typing test application.

Enjoy improving your typing skills! 🚀
