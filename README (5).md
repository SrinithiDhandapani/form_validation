Head Section:
Title and Styles:
The document title is set to "Form Validation".
CSS styles are defined inline within <style> tags to control the appearance of the form elements and error messages.
Body Section:
Form Structure:
The form is centered (max-width: 600px; margin: 0 auto;) on the page for better presentation.
It includes input fields for Name, Address, E-mail Address, Password, Select Your Course, College Name, and a checkbox for agreement.
Validation Logic:
JavaScript Function validateForm():
Retrieves form data such as name, address, email, password, subject, and agree (checkbox).
Initializes variables to store error messages (nameError, addressError, etc.).
Checks each input field against predefined conditions:
Name: Ensures it is at least 6 characters long and starts with an alphabet.
Address: Checks if it is not empty.
E-mail Address: Verifies it contains '@' symbol.
Password: Requires at least 6 characters.
Select Your Course: Ensures an option is selected.
Agreement Checkbox: Ensures it is checked.
Displays specific error messages next to each input field if validation fails.
Returns true if all validations pass, allowing the form to submit; otherwise, returns false to prevent submission until all fields are corrected.
Styling:
The form elements are styled uniformly with padding, margins, borders, and font sizes specified to enhance readability and usability.# Form-validation
