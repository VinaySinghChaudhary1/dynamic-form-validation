# Secure Contact Form Project

This project provides a simple, responsive, and aesthetically pleasing contact form built with plain HTML and styled using Tailwind CSS. It features a modern card-style layout, ensuring a professional user experience across various devices.

## Features

*   **Responsive Design:** Optimized for desktop, tablet, and mobile screens.
*   **Tailwind CSS:** Utilizes the utility-first CSS framework for efficient and customizable styling.
*   **Modern Card UI:** The form is enclosed within a sleek, shadow-effect card.
*   **Required Fields:** Email and Message fields are mandatory to ensure complete submissions.
*   **Company Logo Integration:** Displays a `company_logo.png` above the form title.
*   **Client-Side Validation:** Basic JavaScript handles form submission and provides a feedback message (simulated for demonstration).

## Project Structure

*   `index.html`: The main web page containing the contact form, all styling (Tailwind CDN), and JavaScript logic.
*   `company_logo.png`: An image file for the company logo, expected in the project root.
*   `README.md`: This file, providing an overview and instructions.
*   `LICENSE`: The MIT License text.

## Setup and Usage

To view this project, simply open the `index.html` file in your web browser. No complex build steps or server are required for the front-end functionality.

1.  **Clone the repository (or save the files):**

    ```bash
    git clone <repository-url>
    cd <project-directory>
    ```

2.  **Ensure `company_logo.png` is in the root directory.** If you don't have one, the `img` tag will simply show a broken image icon. You can replace it with your own logo or remove the `img` tag if not needed.

3.  **Open `index.html`** in your favorite web browser.

## Technologies Used

*   HTML5
*   Tailwind CSS (via CDN)
*   JavaScript (Vanilla)

## Customization

*   **Styling:** Modify the Tailwind CSS classes directly within `index.html` to adjust colors, spacing, and other visual properties.
*   **Form Logic:** The JavaScript included provides a basic submission handler. For a real-world application, you would replace the simulated success message with an actual API call to a backend service.
*   **Logo:** Update the `src` attribute of the `<img>` tag if your logo file name or path is different.

## License

This project is open-sourced under the MIT License. See the `LICENSE` file for more details.
