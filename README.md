# The-Summit

The Summit: Ski Lodge Landing Page
Live Demo: https://macdonald91.github.io/The-Summit/

This project, part of the Codecademy Full-Stack Engineer path, focuses on improving the user experience of a ski lodge landing page. The primary goal was to enhance navigation design by providing clear visual feedback for all clickable elements, making the site more intuitive and engaging for users.

Project Overview
The original landing page lacked clear indications for interactive elements. This project involved applying CSS styling to various links and buttons to demonstrate their clickability through hover and active states, ultimately creating a more user-friendly interface.

Features
Basic Link Styling: All <a> tags have basic color highlighting and hover states for improved visibility.

Navigation Link Styling: The main site navigation (.nav-link) elements are styled to clearly show clickability, with underlines removed for a cleaner look.

Main Button Styling: The "Get on the mountain" button (.btn) features distinct hover and active states, providing clear visual feedback.

Activity Button Styling: The large activity buttons at the bottom of the page (.activity) are styled to indicate their interactive nature, including hover and active effects.

CSS Transitions: Subtle CSS transitions are used on hover and active states to create smooth and seamless visual effects.

Technologies Used
HTML5

CSS3

How to View
Clone the Repository: If this project were in a GitHub repository, you would clone it to your local machine.

Open index.html: Navigate to the project directory and open the index.html file in your web browser.

Code Highlights
style.css
Here are some key CSS styles implemented in this project:

Global Link Styles
CSS

a {
  color: #2176FF;
  text-decoration: underline;
  cursor: pointer;
}

a:hover {
  text-decoration: none;
}
Navigation Link Styles
CSS

.nav-link {
  text-decoration: none;
}

.nav-link:hover {
  color: #5495ff;
}
Main Button (.btn) Styles
CSS

.btn:hover {
  background-color: #fff;
  color: #2176FF;
  transition: color .1s ease-in, background-color .1s ease-in;
}

.btn:active {
  font-size: 18px; /* Slightly smaller on active */
  transition: font-size .1s ease-in-out;
}
Activity Button (.activity) Styles
CSS

.activity {
  border: 1px solid #2176FF;
  cursor: pointer;
  text-decoration: none;
}

.activity:hover {
  background-color: #fff;
  color: #5495ff;
  transition: color .1s ease-in, background-color .1s ease-in;
}

.activity:active {
  font-size: 40px; /* Larger on active for a playful effect */
  transition: font-size .1s;
}
Project Goals Achieved
The project successfully addressed the initial problem of unclear clickable elements. By implementing a combination of color changes, text decorations, and size adjustments on hover and active states, the user experience of "The Summit" landing page has been significantly improved, making interactions more intuitive and visually engaging.

Author
MacDonald Industries
