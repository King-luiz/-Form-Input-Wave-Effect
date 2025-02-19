

# 🌊 Form Input Wave Effect

This project demonstrates a visually appealing wave effect on form input labels using HTML, CSS, and JavaScript.  It provides a modern and interactive user experience for login forms.


## 🛠️ Technologies Used

*   **HTML:**  Structure and content of the web page.
*   **CSS:** Styling and visual presentation, including the wave effect.
*   **JavaScript:**  Enhancing interactivity and dynamic label animation.

## 💡 Project Overview

This project focuses on creating a smooth and engaging animation for form input labels. When an input field is focused, the label appears to "wave" or rise up from the input field. This effect enhances the user experience by providing clear visual cues and a touch of modern design.

## ⚙️ How to Use

1.  **Clone the Repository:**
    ```bash
    git clone [https://github.com/King-luiz/-Form-Input-Wave-Effect].git
    ```
2.  **Open `index.html`:** Open the `index.html` file in your web browser.

## 🧰 Project Structure

form-input-wave/
├── index.html      // Main HTML file (contains the form structure)
├── style.css       // CSS stylesheet (styles the form and implements the wave effect)
└── script.js      // JavaScript file (currently for sound effects, can be used for other dynamic behavior

## ✨ Features

*   **Wave Effect:**  Animated label movement on input focus.
*   **Clean Design:**  Simple and modern user interface.
*   **Easy Customization:**  Easily adaptable CSS for styling.
*   **Responsive Design:** Works well on different screen sizes.

## 🎨 Customization

The `style.css` file controls the visual appearance of the form. You can modify colors, fonts, animations, and other styles to match your preferences.

## 📜 Code Explanation

### HTML (`index.html`)

The HTML file sets up the basic structure of the login form, including input fields for email and password, a login button, and a link to a registration page (which is currently a placeholder).  Each input field is wrapped in a `form-control` div, which is crucial for the wave effect.

### CSS (`style.css`)

The CSS file styles the form elements and implements the wave animation.  Key aspects include:

*   `@import url(...)`: Imports the Poppins font from Google Fonts.
*   `form-control`:  Styles the container for the input and label.
*   `label`: Styles the label and its positioning.  The `transition` property is key for the smooth animation.
*   `input:focus + label`, `input:valid + label`: Styles the label when the input is focused or has valid input, triggering the wave animation by transforming and positioning the label.

### JavaScript (`script.js`)

The JavaScript file adds dynamic behavior to the form.  It listens for focus events on the input fields and adds or removes classes to trigger the CSS animation.

## 📚 Further Improvements

*   **Form Validation:** Implement client-side and server-side form validation.
*   **Accessibility:** Improve accessibility for users with disabilities.
*   **Error Handling:**  Provide user-friendly error messages.
*   **Backend Integration:** Connect the form to a backend for data processing and authentication.

## 📄 License

[MIT License](LICENSE) *(Add a LICENSE file if you want to specify licensing terms)*

## 🤝 Contributing

Contributions are welcome! Please open an issue or submit a pull request.
