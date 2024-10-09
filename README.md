# Boston
Overview
This project is a simple web application that displays the top earners from a dataset, specifically focusing on individuals with salaries below $20,000,000. Using HTML, CSS, and JavaScript, it retrieves and processes data from an external module (boston.js) and presents the results in a styled format.

Features
Dynamic Data Display: Extracts the top earners based on salary from the dataset and displays them in the browser.
Styled Presentation: Utilizes CSS to style the output for better visibility and aesthetics.
Modular JavaScript: Uses ES6 module import to bring in data from an external file.
Prerequisites
A modern web browser (e.g., Chrome, Firefox) to view the application.
A server environment (like Live Server in VS Code) to run ES6 modules properly, as some browsers restrict module loading from local files.
How to Use
Clone the Repository: Download or clone this repository to your local machine.
Create boston.js: Ensure you have a boston.js file in the same directory that exports the boston object with the necessary data structure.
Open the HTML File: Open index.html (or whatever you've named it) in a web browser using a server environment.
View Results: The application will display the top earners with their names and salaries.
Code Structure
HTML:

Contains a <div> with the ID app for dynamically displaying the top earners.
CSS:

Inline styles applied to the #app element to set text color and border.
JavaScript:

The script retrieves the data from boston.js, processes it to filter top earners, and sorts them by salary. The results are then dynamically inserted into the HTML.
Customization
Data Source: Modify the boston.js file to update or change the dataset.
Salary Threshold: Adjust the salary limit in the if condition to include or exclude different earning thresholds.
Styling: Change the CSS in the <style> section to customize the look and feel of the application.
License
This project is open-source and available for personal or educational use. Feel free to modify and expand upon it!

Acknowledgments
This application serves as a practical example of working with data in web development, showcasing the use of JavaScript modules and dynamic content rendering.
