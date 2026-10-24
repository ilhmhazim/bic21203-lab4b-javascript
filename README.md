# bic21203-lab4b-javascript

Project Description

This project demonstrates how to create JSON data, retrieve and display JSON using JavaScript fetch(), and manipulate HTML elements using jQuery.

# Question 1: Create and Structure JSON Data

The books.json file contains two book objects:

- The Great Gatsby by F. Scott Fitzgerald
- To Kill a Mockingbird by Harper Lee

Each book contains a title, author, publication year, and genres. The JSON file uses the correct data types and has no trailing commas.


Output

<img width="702" height="591" alt="image" src="https://github.com/user-attachments/assets/06bf4cd2-4401-4960-878e-cc47517d5ce8" />


# Question 2: Retrieve and Display JSON Data

The books.html file uses the JavaScript fetch() API to retrieve information from books.json.

The webpage displays:

- The title of the first book.
- The author of the second book.
- The genres of both books, grouped by book title.

The code uses textContent and createElement() to display text safely. Error handling is included if the JSON file cannot be loaded or the data is invalid.

Output

<img width="953" height="441" alt="image" src="https://github.com/user-attachments/assets/0bd3bce3-e29b-4651-8622-e51c307f186e" />


# Question 3: Compare Native JavaScript and jQuery

The jquery-dom.html file uses jQuery 4.0.0 from the official CDN.

The three operations are:

1. .text() changes the text to "Modified Text".
2. .addClass() adds the myStyle class to #myDIV.
3. .on("click", ...) displays an alert when the button is clicked.

Advantage of native JavaScript: It does not require an external library.

Why an existing project may use jQuery: It may already use jQuery for DOM manipulation and event handling.

Setup Instructions

1. Open the project folder in Visual Studio Code.
2. Install the Live Server extension.
3. Right-click books.html and select Open with Live Server.
4. Check that the book information appears correctly.
5. Open jquery-dom.html with Live Server and test all three operations.

Native JavaScript does not require an external library. However, an existing project may continue using jQuery if it already depends on it for DOM manipulation and event handling.

Output

The webpage displays "Modified Text", applies a coral background to #myDIV, and shows an alert saying "Button clicked!" when the button is clicked.

output: jQuery Output

<img width="948" height="497" alt="image" src="https://github.com/user-attachments/assets/06e694c2-dc28-40d2-819c-35d0f5f3b28c" />

Output: Button Alert

<img width="947" height="540" alt="image" src="https://github.com/user-attachments/assets/217e2f81-67f4-4dc0-a720-38659f39a8c8" />


This project helped me learn how to structure JSON data, retrieve and display JSON using JavaScript, and manipulate webpage elements using jQuery. I also learned how to test HTML files using Live Server and handle errors when loading JSON data.
