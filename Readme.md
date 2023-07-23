# Chrome Extension: Leads Tracker

## Description
This Chrome extension is designed to track leads by utilizing JavaScript and DOM manipulation. It enables users to save and retrieve leads locally using the browser's local storage. The extension showcases proficiency in handling local storage and demonstrates the ability to enhance browser functionality using JavaScript.

## Skills
- JavaScript Proficiency
- Chrome Extension Development
- Local Storage Handling
- API Integration (Chrome Tabs API)
- Version Control (Git)
- Problem-Solving and Debugging
- User Interface Design
- Project Planning and Execution

## Experience Gained
Through developing the Chrome extension for lead tracking and local storage handling, I gained valuable skills and experiences that have enhanced my capabilities as a developer:

1. **JavaScript Proficiency:** The project deepened my understanding of JavaScript, and I became more adept at using the language to manipulate the Document Object Model (DOM) and create interactive web applications.

2. **Chrome Extension Development:** I gained hands-on experience in building a functional Chrome extension from scratch. I learned how to set up the extension, define the extension's user interface, and handle user interactions effectively.

3. **Local Storage Handling:** The project exposed me to the concept of local storage in web development. I learned how to store data locally within the user's browser, allowing for data persistence and seamless user experiences.

4. **API Integration (Chrome Tabs API):** I acquired knowledge of the Chrome Tabs API and learned how to utilize it to interact with the browser's active tabs. This skill allowed me to save the current tab's URL as a lead, improving the extension's functionality.

5. **Version Control (Git):** Throughout the project, I utilized Git for version control, enabling me to manage code changes effectively, collaborate with others, and track the development progress.

6. **Problem-Solving and Debugging:** I encountered various challenges during the development process, and this project provided ample opportunities to sharpen my problem-solving and debugging skills.

7. **User Interface Design:** While building the extension's user interface, I honed my skills in creating clean and user-friendly designs that enhance the overall user experience.

8. **Project Planning and Execution:** The project required careful planning and execution to ensure that the extension met the intended functionality. This experience enhanced my project management skills and ability to meet deadlines.

## Usage
1. Open the extension popup by clicking on the extension icon in the browser toolbar.
2. Enter a lead URL or any input into the text field.
3. Click the "SAVE INPUT" button to save the entered input as a lead.
4. Click the "SAVE TAB" button to save the current active tab's URL as a lead.
5. All saved leads will be displayed as clickable links in the extension popup.
6. To remove all saved leads, double-click the "DELETE ALL" button.

## Code Files

### `index.css`:
```css
/* CSS styles for the extension popup */

/* ... (CSS styles are defined here) ... */
```

### `index.html`:
```html
<!-- HTML structure for the extension popup -->
<!DOCTYPE html>
<html>
    <head>
        <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/normalize/8.0.1/normalize.css">
        <link rel="stylesheet" href="index.css">
    </head>
    <body>
        <input type="text" id="input-el">
        <button id="input-btn">SAVE INPUT</button>
        <button id="tab-btn">SAVE TAB</button>
        <button id="delete-btn">DELETE ALL</button>
        <ul id="ul-el"></ul>
        <script src="index.js"></script>
    </body>
</html>
```

### `index.js`:
```javascript
// JavaScript logic for the extension popup

// ... (JavaScript code is defined here) ...
```

### `manifest.json`:
```json
{
    "manifest_version": 3,
    "version": "1.0",
    "name": "Leads tracker",
    "action": {
        "default_popup": "index.html",
        "default_icon": "icon.png"
    },
    "permissions": [
        "tabs"
    ]
}
```

## Installation
To use this Chrome extension, follow these steps:

1. Download the code files (`index.css`, `index.html`, `index.js`, and `manifest.json`) to a local directory.

2. Open Google Chrome and navigate to `chrome://extensions`.

3. Enable Developer Mode (usually located in the top right corner).

4. Click on "Load unpacked" and select the directory where you saved the code files.

5. The extension will now be installed and available in the browser toolbar.

## Contributions
Contributions to improve and enhance this extension are welcome. Feel free to fork this repository, make changes, and submit a pull request.

## License
This project is licensed under the [MIT License](LICENSE).