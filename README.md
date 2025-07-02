# HTML basics

Project Readme
This project consists of several HTML and CSS files, demonstrating various web development concepts, including basic HTML structure, forms, animations, and layout techniques using CSS.

Files Overview
Here's a detailed description of each file:

anima1.html
Description: This HTML file demonstrates a CSS animation on a div element. The animation, named moveAndColor, moves the box horizontally, translates it, changes its background color, applies a box-shadow, and changes its border-radius over a 5-second infinite loop.

Key Features:

CSS @keyframes rule for defining animation steps.

animation-name, animation-duration, and animation-iteration-count properties.

transform property for translateX and translateY.

Dynamic styling of background-color, box-shadow, and border-radius during animation.

animations.html
Description: This HTML file showcases another CSS animation (myAnimation) applied to a div element. The animation runs for 10 seconds, infinitely, and alternates between keyframes, changing the element's position, background color, border-radius, and rotation.

Key Features:

Defines keyframes for 0%, 50%, and 100% animation states.

Uses position: absolute and left for horizontal movement.

Applies transform: translateX and transform: rotate for advanced animations.

Changes background-color and border-radius at different animation stages.

car.css
Description: This CSS file provides styling for the car.html file, defining the visual presentation of a "Favourite Cars" webpage. It includes styles for the body, header, car list, and individual car sections with background images and text boxes.

Key Features:

Global body styling (font, background, color).

Styling for headers, lists, and buttons.

Responsive button styling with hover effects.

container and textbox classes for laying out car information with background images, using position: relative and position: absolute for precise placement of text boxes over images.

Includes a variety of image URLs for different car backgrounds.

car.html
Description: This HTML file structures a webpage titled "Favourite Cars," listing several car brands (BMW, Mercedes, Audi, Lamborghini, Porsche, Rolls Royce) and providing a brief description for each, along with a "Know more" button linking to their respective official websites. It links to car.css for its styling.

Key Features:

Includes a header and a list of top car picks.

Sections for each car brand with descriptions.

Uses div containers and textboxes for content organization.

External links to official car manufacturer websites.

claculator.html
Description: This HTML file creates a basic calculator interface. It features a display area and a grid of buttons for numbers and potential operations. The name contains a typo, it is claculator.html instead of calculator.html.

Key Features:

Centered h1 title "Calculator".

A display area (A1 class) for showing input/results.

A flex container using CSS Grid to arrange calculator buttons in a 4-column layout.

Styling for buttons (f class) with hover effects.

demo.html
Description: This comprehensive HTML file serves as a demonstration of various fundamental HTML elements and concepts. It covers text formatting, tables, lists, forms, and includes examples of input types, radio buttons, checkboxes, dropdowns, and buttons with JavaScript onclick events.

Key Features:

Examples of <b>, <q>, <pre>, <abbr>, <address>, <kbd> tags.

HTML Tables with <caption>, <thead>, <tbody>, <tr>, <td> for structured data.

Different types of HTML lists: unordered (<ul>), ordered (<ol>), and description lists (<dl>, <dt>, <dd>).

HTML Forms with various input types (text, password, radio, checkbox, date), select dropdowns, and textarea.

Demonstrates submit, reset, and button types, including an alert function on button click.

Links to an external CSS file named style.css (not provided in the current set).

flex.html
Description: This HTML file demonstrates the use of CSS Flexbox and Grid for layout. It features a main flex container that uses a CSS Grid layout for its children, showcasing how elements can be arranged with gaps and alignment.

Key Features:

A div with class flex acting as a grid container with 4 auto-sized columns.

gap property for spacing between grid items.

justify-content and align-items for centering content.

Nested flex1 and f classes demonstrating flex properties within grid items.

form.css
Description: This CSS file provides styling for an HTML form, likely associated with form.html. It defines the appearance of the body, headings, form elements like fieldset, legend, label, input, textarea, and button.

Key Features:

General body and heading styles.

Styles for form container, including max-width, margin: auto for centering, border-radius, and box-shadow.

Styling for fieldset and legend for grouping form elements.

Full-width styling for input and textarea fields with padding and margin.

Styling for the button with a green background and white text.

form.html
Description: This HTML file presents a user detail entry form with fields for personal information such as name, password, email ID, phone number, DOB, and address. It links to form.css for its visual styling. The form also includes examples of embedding a local video and a YouTube video using <iframe>.

Key Features:

A form structured with a fieldset and legend for "personal information".

Various input types: text, password, number, date.

A textarea for the address.

A submit button.

Demonstrates embedding a local video (abc.mp4/Screen Recording 2025-06-20 105038.mp4) and a YouTube video.

header&footer.html
Description: This HTML file demonstrates a webpage with a sticky header and a sticky footer. The main content section provides information about Hyderabad.

Key Features:

A header with a navigation menu, styled to be position: sticky at the top of the viewport.

A footer also styled to be position: sticky.

A main content area with padding and a minimum height to avoid overlap.

Includes a brief informational text about Hyderabad.

Technologies Used
HTML5

CSS3

How to Use
To view these files, simply open any of the .html files in a web browser. Ensure that the corresponding .css files (e.g., car.css for car.html, form.css for form.html) are in the same directory as their respective HTML files for the styling to be applied correctly.

For form.html, the local video file (abc.mp4/Screen Recording 2025-06-20 105038.mp4) needs to be present at the specified path for it to play.
