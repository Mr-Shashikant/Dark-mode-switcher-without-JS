# Dark Mode Switcher Without JavaScript

A pure CSS solution for implementing a dark mode toggle on your website, eliminating the need for JavaScript.

## Features

- **Dark Mode Toggle**: Switch between light and dark themes using only CSS.
- **No JavaScript Required**: Achieve theme switching without any JavaScript dependencies.
- **Responsive Design**: Ensures compatibility across various devices and screen sizes.

## Demo

Experience the live demo here: [Dark Mode Switcher Without JavaScript](https://mr-shashikant.github.io/Dark-mode-switcher-without-JS/)

## Installation

To integrate this dark mode switcher into your project:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/Mr-Shashikant/Dark-mode-switcher-without-JS.git
   cd Dark-mode-switcher-without-JS
   ```

2. **Include the CSS**:
   Link the `style.css` file in your HTML:
   ```html
   <link rel="stylesheet" href="style.css">
   ```

3. **Add the Toggle Switch**:
   In your HTML, include the following toggle switch:
   ```html
   <input type="checkbox" id="theme-toggle">
   <label for="theme-toggle" class="theme-toggle-label">Toggle Theme</label>
   ```

4. **Structure Your HTML**:
   Ensure your content is wrapped appropriately:
   ```html
   <div class="container">
       <!-- Your content here -->
   </div>
   ```

## Usage

- **Toggling Themes**: Click the "Toggle Theme" switch to switch between light and dark modes.
- **Default Theme**: The default theme is light mode. Users can switch to dark mode using the toggle.

## How It Works

This implementation utilizes the CSS `:checked` pseudo-class in combination with the `prefers-color-scheme` media query to detect the user's system theme preference. When the checkbox is toggled, CSS variables are used to switch between light and dark themes.

## Contributing

Contributions are welcome! If you have suggestions or improvements, feel free to submit a pull request or open an issue.

## License

This project is open-source and available under the [MIT License](LICENSE).