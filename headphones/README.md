Responsive Web Page

This project is a simple, responsive webpage designed to switch to a mobile version when the screen width is 480px or less. It incorporates hover and active states for buttons and links to enhance the user experience.

Features

Responsive Design: Automatically adapts to a mobile-friendly layout when the screen width is 480px or less.
Hover/Active States: Links and buttons have hover and active styles to improve interactivity.
Content Max Width: The content is centered on the page with a maximum width of 1000px for readability on larger screens.
Demo

Live Demo Link

Table of Contents

Features
Demo
Installation
Usage
Folder Structure
Interactions
Technologies Used
License
Installation

Clone the repository:
bash
Copy code
git clone https://github.com/Ghost-610/alx_html_css 
Navigate to the project directory:
bash
Copy code
cd responsive-web-page
Open index.html in your preferred browser to view the project.
Usage

To view the desktop version, open the webpage on a device with a screen width greater than 480px.
For the mobile version, resize the browser window or view the webpage on a mobile device with a screen width of 480px or less.
Folder Structure

css
Copy code
responsive-web-page/
│
├── index.html
├── css/
│   └── styles.css
├── img/
│   └── (images used in the project)
└── README.md
Interactions

Mobile Responsiveness:
The web page will switch to the mobile version when the screen width is 480px or less.
Links:
On hover and active states, the links will change color to #FF6565.
css
Copy code
a:hover, a:active {
  color: #FF6565;
}
Buttons:
On hover and active states, the buttons will have reduced opacity for a subtle visual feedback.
css
Copy code
button:hover, button:active {
  opacity: 0.9;
}
Max Content Width:
The content will have a maximum width of 1000px and will be centered within the page for better visual balance on larger screens.
css
Copy code
.content {
  max-width: 1000px;
  margin: 0 auto;
}
Technologies Used

HTML5: For structuring the webpage.
CSS3: For styling, responsive design, and hover/active effects.
Media Queries: To switch between desktop and mobile layouts.
License

This project is licensed under the MIT License. See the LICENSE file for more details.