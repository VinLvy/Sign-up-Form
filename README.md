# Sign-up Form
This is a simple Sign-up Form built using HTML and CSS. The form includes fields for first name, last name, email, phone number, password, and password confirmation. It also includes basic styling to create a clean, modern look.

Features
Input Fields:

First Name
Last Name
Email
Phone Number
Password
Confirm Password
Form Validation:

Basic HTML5 validation using attributes like required for required fields and type="email" for email validation.
Invalid inputs are highlighted with a red border.
Styling:

The form is centered on the page using CSS Flexbox.
Background image covers the entire page (background-size: cover).
Smooth transitions for hover and focus effects on input fields and buttons.
The form container has a shadow effect and becomes more prominent when hovered.
How It Works
The form uses HTML5 for input fields and basic validation.
CSS is used to style the form, positioning it at the center of the page, and adding hover and focus effects for better user experience.
CSS Pseudo-classes Used:
:hover and :focus on input fields and buttons to provide visual feedback when users interact with the form.
:invalid to highlight invalid input fields based on basic HTML validation rules (e.g., required fields and email format).
Limitations
Responsiveness
This form is not responsive yet. It is designed for desktop viewports, and when viewed on smaller screens, the layout might not be optimized. To make it responsive:

Add media queries in the CSS file to adjust the layout for different screen sizes.
Stack form inputs vertically for mobile devices to avoid overflowing the page.
JavaScript Validation
This form does not include JavaScript validation. The current validation only uses basic HTML5 features like required and type="email". For better validation and user experience, you can add JavaScript to:

Validate the form in real-time.
Check if the passwords match.
Display more detailed error messages.
Improvements to Consider
Add Responsiveness: Use media queries and make sure the form looks good on all screen sizes (mobile, tablet, and desktop).
JavaScript Validation: Enhance the form validation by adding custom JavaScript for better user feedback, especially to handle password confirmation.
Enhanced Accessibility: Add aria-labels and other accessibility features to ensure a smooth experience for all users, including those using assistive technologies.
Preview

How to Use
Clone this repository or download the files.
Make sure the style.css file and index.html are in the same directory.
Open index.html in a web browser to view the form.
Contributing
Feel free to fork this project and add your improvements! Whether it's making the form responsive or adding custom JavaScript validation, any contributions are welcome.

License
This project is open-source and free to use under the MIT License.
