# Sign Up Form

This is a simple, responsive sign-up form created using HTML, CSS, and a custom font. The form includes fields for users to input their personal information, including their first name, last name, email, phone number, and password. It is designed to be visually appealing and user-friendly with clear input validation.

## Features
- **User-friendly design**: The layout is clean and minimalistic with a modern look and feel.
- **Responsive layout**: The form is responsive and will adapt to various screen sizes, ensuring a seamless user experience across devices.
- **Custom logo and image**: The form includes a background image and a custom logo, enhancing the visual appeal of the page.
- **Input validation**: Basic input validation is implemented to ensure users fill out the required fields correctly (e.g., email format, phone number, password).
- **Focused and Invalid Inputs**: The form provides visual feedback with blue borders for focused inputs and red borders for invalid ones.

## File Structure

```
/index.html         - The main HTML file containing the form structure.
styles.css          - The external stylesheet for styling the page.
img/                - Folder containing the images (e.g., logo and background image).
fonts/              - Folder for custom fonts (e.g., Norse-Bold.otf).
```

### HTML (index.html)
This file contains the structure of the form with various fields for user input. The form is wrapped in a `div` container that splits the page into two sections:
- An image container (`#img-container`) with a background image and logo.
- A form container (`#form-container`) where users can input their information.

### CSS (styles.css)
This file contains all the styles for the form, including:
- **Responsive layout**: The page uses `flexbox` and percentage-based widths to make sure the form adapts to different screen sizes.
- **Input styles**: Borders and shadows for focused and invalid inputs to enhance user interaction.
- **Typography**: A custom font is applied for the logo, and basic fonts are used for the form text.

## How to Use
1. Clone or download this repository to your local machine.
2. Open the `index.html` file in your web browser to view the form in action.
3. Customize the form and the styling as needed by editing the `index.html` and `styles.css` files.
4. Replace the images and fonts inside the `img/` and `fonts/` folders to match your branding or requirements.

## Future Improvements
- **Form validation**: Implement JavaScript to add more advanced form validation and provide real-time feedback to users.
- **Backend integration**: Integrate the form with a backend to handle form submissions and store user data.
- **Accessibility**: Improve accessibility by adding ARIA labels and enhancing the tab order.
- **Mobile optimization**: Ensure the layout is fully optimized for mobile devices, with easy-to-use touch interactions.

## License
This project is open source and available under the MIT License. Feel free to use and modify it as per your needs.
