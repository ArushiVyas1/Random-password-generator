# Random-password-generator
A lightweight and user-friendly web application that generates secure, random passwords containing a mix of uppercase letters, lowercase letters, numbers, and special symbols. The app features a simple interface with the ability to generate passwords and quickly copy them to the clipboard.

# Features
Secure Passwords: Generates 12-character passwords ensuring inclusion of uppercase, lowercase, digits, and special characters.

Copy to Clipboard: Easily copy generated passwords with a single click.

Read-only Display: Passwords are shown in a readonly input field to prevent accidental editing.

Visual Enhancements: Utilizes Font Awesome icons for intuitive user experience.

Responsive Design: Built with modern HTML and CSS for compatibility across devices.

# Technologies Used
HTML5 for structure and semantic markup.

CSS (via external stylesheet sheet.css) for styling and layout.

JavaScript for password generation logic and clipboard interaction.

Font Awesome 5.15.4 for iconography.

# How It Works
1. Generate Password:
When the "Generate Password" button is clicked, a function creates a random password by:

Selecting at least one character from uppercase letters, lowercase letters, numbers, and symbols.

Filling the remaining password length with random characters from all character sets.

Displaying the password in a readonly input field.

2. Copy Password:
Clicking the copy icon triggers the Clipboard API to copy the password. Success or failure is communicated via alert messages.
