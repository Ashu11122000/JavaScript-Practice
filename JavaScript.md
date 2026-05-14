# 1. Introduction to JavaScript

## What is JavaScript?

JavaScript is a **high-level, dynamic, interpreted programming language** primarily used to make web pages interactive.

- HTML creates structure.
- CSS adds styling.
- JavaScript adds behavior and functionality.

**Example:**

`Without JavaScript:`

- Button appears
- Clicking does nothing

`With JavaScript:`

- Button responds
- Popup appears
- Data changes
- Form validates
- Content updates dynamically

Example:

```javascript
document.getElementById("btn").addEventListener("click", function () {
    alert("Button clicked");
});