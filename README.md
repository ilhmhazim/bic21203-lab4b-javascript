# bic21203-lab4b-javascript

Project Description

This project demonstrates how to create JSON data, retrieve and display JSON using JavaScript fetch(), and manipulate HTML elements using jQuery.

# Question 1: Create and Structure JSON Data

The books.json file contains two book objects:

- The Great Gatsby by F. Scott Fitzgerald
- To Kill a Mockingbird by Harper Lee

Each book contains a title, author, publication year, and genres. The JSON file uses the correct data types and has no trailing commas.

# Question 2: Retrieve and Display JSON Data

The books.html file uses the JavaScript fetch() API to retrieve information from books.json.

The webpage displays:

The title of the first book.

The author of the second book.

The genres of both books, grouped by book title.

The code uses textContent and createElement() to display text safely. Error handling is included if the JSON file cannot be loaded or the data is invalid.

# Question 3: Compare Native JavaScript and jQuery

The jquery-dom.html file uses jQuery 4.0.0 from the official CDN.

The three operations are:

.text() changes the text to "Modified Text".

.addClass() adds the myStyle class to #myDIV.

.on("click", ...) displays an alert when the button is clicked.

Advantage of native JavaScript: It does not require an external library.

Why an existing project may use jQuery: It may already depend on jQuery for DOM manipulation and event handling, so keeping it can avoid rewriting existing code.

Setup Instructions

Download or clone this repository to your computer.

Open the project folder in Visual Studio Code.

Install the Live Server extension if it is not already installed.

Right-click books.html and select Open with Live Server.

Check that the book information appears correctly.

Open jquery-dom.html with Live Server.

Check that the text changes, the coral background appears, and the button displays the alert.

Important: Run books.html through a local server instead of opening it directly using file://. An internet connection is required to load jQuery from the CDN.

Screenshots

Add your actual screenshots to the screenshots folder.

Question 1: JSON File



Question 2: JSON Output



Question 3: jQuery Output



Question 3: Button Alert



GitHub Repository

Repository URL: Paste your GitHub repository link here.

Conclusion

This project helped me learn how to structure JSON data, retrieve and display JSON using JavaScript, and manipulate webpage elements using jQuery. I also learned how to test HTML files using Live Server and handle errors when loading JSON data.
