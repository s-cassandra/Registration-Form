# Registration Form

## Overview

This is a simple **Registration Form** built with HTML and styled with CSS. The form collects basic personal information, account type, additional profile details, and requires the user to accept terms and conditions before submission. The form is designed with responsiveness in mind and is styled to fit a dark theme.

## Structure

### HTML File (`index.html`)

- **`<head>` Section:**
  - **Meta tag:** Ensures proper text rendering by setting the character encoding to UTF-8.
  - **Title:** Sets the title of the page to "Registration Form," which appears in the browser tab.
  - **Link to CSS:** The external `styles.css` file is linked for styling.

- **`<body>` Section:**
  - **Main Heading:** A heading (`<h1>`) that introduces the page as a "Registration Form."
  - **Instructional Paragraph:** A brief message guiding users to fill out the form.
  - **Form (`<form>`):**
    - **Method:** POST method, which sends the form data to a URL for processing (`https://register-demo.freecodecamp.org`).
    - **Fieldsets:** Divides the form into logical sections:
      - **Personal Information:** First name, last name, email, and password fields.
      - **Account Type:** A radio button selection for "Personal" or "Business" account type.
      - **Additional Information:** Profile picture upload, age input, how the user heard about the service, and a short bio.
    - **Terms and Conditions:** A checkbox input that the user must check before submitting the form. It also includes a link to the terms and conditions page.
    - **Submit Button:** A button that submits the form.

### CSS File (`styles.css`)

The CSS file provides styles for the form, body, and form elements, ensuring a clean, modern, and readable design.

- **Body:**
  - Full-width and height to fill the viewport with a dark background colour (`#1b1b32`) and light text colour (`#f5f6f7`).
  - Uses Tahoma font-family and a base font size of 16px.

- **Headings and Paragraphs:**
  - Centered text for the main heading (`<h1>`) and paragraph (`<p>`).
  - Margin added to create spacing around these elements.

- **Form Styling:**
  - The form is centered within the page with a flexible width that adjusts to the viewport but is capped between 300px and 500px.
  - Padding is added at the bottom of the form for spacing.

- **Fieldset Styling:**
  - The fieldsets are styled with padding and a bottom border for separation between sections.
  - The last fieldset has no bottom border for a cleaner look.

- **Label and Input Fields:**
  - Labels are displayed as block elements with spacing between them.
  - Input fields, textareas, and selects are styled to take up the full width of their container, with a minimum height set for readability.
  - Input fields have a dark background with white text for contrast.

- **Submit Button:**
  - The submit button is styled to be centered with a background colour matching the theme and a white border.

- **Terms and Conditions Link:**
  - The link colour for the terms and conditions is set to a light gray (`#dfdfe2`) to ensure readability against the dark background.

## Usage Instructions

1. **Clone or Download:** Download or clone the files from this repository to your local machine.
2. **View in Browser:** Open the `index.html` file in your browser to view the registration form.
3. **CSS Customization:** You can modify the `styles.css` file to customise the appearance of the form to fit your needs.
4. **Form Submission:** The form is designed to send POST data to the given URL (`https://register-demo.freecodecamp.org`). Replace this URL with your own server's endpoint if necessary.

## Compatibility

- This form and styling are compatible with modern browsers such as Chrome, Firefox, Safari, and Edge.
- The form is responsive and adjusts to different screen sizes (e.g., mobile, tablet, desktop).

