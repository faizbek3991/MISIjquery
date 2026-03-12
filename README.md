# MISIjquery - jQuery Basics Exercise

A simple web application demonstrating basic jQuery DOM manipulation techniques.

## 📋 Overview

This project is a beginner-friendly exercise that showcases how to use jQuery to interact with and modify the DOM (Document Object Model). It includes a button that, when clicked, changes the text of a paragraph element using jQuery.

## 🚀 Features

- **DOM Manipulation**: Change text content of HTML elements dynamically
- **Event Handling**: Respond to user click events
- **Clean UI**: Simple and responsive design with CSS styling

## 📁 Project Structure

```
/workspace
├── index.html          # Main HTML file
├── script.js           # jQuery functionality
├── style.css           # Custom styles
├── jquery-4.0.0.min.js # jQuery library (v4.0.0)
└── README.md           # This file
```

## 🛠️ Technologies Used

- **HTML5** - Structure of the page
- **CSS3** - Styling and layout
- **jQuery 4.0.0** - JavaScript library for DOM manipulation

## 📖 How It Works

1. The page loads with an original text in a paragraph element
2. When the "Change Text" button is clicked, jQuery intercepts the event
3. The text content of the paragraph is updated to: "This text has been changed with jQuery!"

### Code Explanation

**script.js**:
```javascript
$(document).ready(function() {
    // Wait for document to be fully loaded
    $("#change-text").click(function() {
        // On button click, change the text of the paragraph
        $("#text-to-change").text("This text has been changed with jQuery!");
    });
});
```

## 🎯 Usage

1. Open `index.html` in any modern web browser
2. Click the "Change Text" button
3. Observe the text change dynamically

No build process or server required - just open the HTML file directly!

## 🤝 Learning Objectives

This exercise helps you learn:
- How to include jQuery in your project
- Using `$(document).ready()` to ensure DOM is loaded
- Selecting elements with jQuery selectors
- Handling click events
- Modifying text content with `.text()`

## 📄 License

This project is open source and available for educational purposes.
