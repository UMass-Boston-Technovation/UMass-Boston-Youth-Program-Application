# UMass Boston Youth Program Application Form - 2025

This repository contains the HTML, CSS, and JavaScript for the UMass Boston Youth Program Application Form for the year 2025.

## Features

*   **Multi-Page Layout:** The application (`index.html`) is structured across 7 logical pages for ease of navigation and completion.
*   **Dynamic Summary Page:** Upon submission from `index.html`, user inputs are stored in `localStorage` and displayed on a comprehensive summary page (`summary.html`).
*   **Print Functionality:** Both the application form and the summary page are designed to be printer-friendly.
    *   The summary page is optimized to print the user's responses clearly, aiming for a 7-page output that matches the on-screen sections.
*   **Google Translate Integration:** Users can select their preferred language to translate the form content on both `index.html` and `summary.html`.
    *   Instructions are provided to guide users on translating the form and ensuring the summary is converted to English before printing, as per department requirements.
*   **Data Persistence:** Form data is saved to the browser's `localStorage` upon submission, allowing it to be retrieved by the summary page.
*   **Responsive Design:** Basic responsive considerations are included for viewing on different screen sizes, though primarily designed for desktop use.

## File Structure

*   `index.html`: The main application form that users fill out.
*   `summary.html`: The page that displays the submitted form data for review and printing.
*   `umb.png`: The UMass Boston logo used in the header.
*   `README.md`: This file, providing information about the project.

## Setup and Usage

1.  Clone the repository or download the files.
2.  Open `index.html` in a web browser to fill out the application.
3.  Upon clicking "Submit Application", the data will be saved, and you will be redirected to `summary.html`.
4.  On `summary.html`:
    *   Use the Google Translate widget to convert the page to English if you filled it out in another language.
    *   Click the "Print Summary" button to print the form.
    *   Click "Return to Form" to go back to `index.html` (note: this will not clear previously entered data unless the page is reloaded without submission).

## Notes

*   The translation widget relies on Google Translate and requires an internet connection.
*   Ensure `localStorage` is enabled in your browser for the form data to be passed to the summary page.
*   The print output for `summary.html` has been carefully styled to aim for 7 pages, matching the on-screen logical page breaks.

## Required Documentation
The form includes sections for all required documentation as per 105 CMR 430.000, MA Regulations for Minimum Standards for Recreational Camps for Children, including:
- Staff information forms
- Background review procedures
- Promotional literature
- Child abuse reporting procedures
- Health care policy
- Discipline policy
- Fire evacuation plan
- Disaster/Emergency plan
- Lost camper plan
- Lost swimmer plan (when applicable)
- Traffic control plan
- Field trip documentation

## Contributing
Contributions are welcome! Please feel free to submit a Pull Request.

## License
This project is licensed under the MIT License - see the LICENSE file for details.

## Support
For support or questions, please contact the UMass Boston Technology Innovation team.

This project aims to streamline the registration process for UMass Boston Recreational Programs. 