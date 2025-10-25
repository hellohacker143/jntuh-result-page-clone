# JNTU-H Result Page Clone

A clone of the JNTU-H (Jawaharlal Nehru Technological University Hyderabad) result portal interface created for educational purposes.

## Description

This project is a front-end clone of the JNTU-H examination results portal. It replicates the user interface and form structure used by students to check their exam results. This clone is intended for:

- Educational purposes and learning web development
- Understanding form design and validation
- Studying user interface patterns used in educational portals
- Practice with HTML forms and styling

**Note:** This is a non-functional clone for demonstration purposes only. It does not connect to any actual result database or backend system.

## Features

- **Hall Ticket Number Input:** Text field with auto-capitalization
- **Date of Birth Field:** Date picker with format validation (YYYY/MM/DD)
- **CAPTCHA Verification:** Dynamic CAPTCHA generation with refresh functionality
- **Responsive Form Layout:** Clean, centered form design with appropriate styling
- **Form Validation:** Client-side validation for required fields

## Usage Instructions

### Local Setup

1. **Clone the repository:**
   ```bash
   git clone https://github.com/hellohacker143/jntuh-result-page-clone.git
   ```

2. **Navigate to the project directory:**
   ```bash
   cd jntuh-result-page-clone
   ```

3. **Open the HTML file:**
   - Simply open `index.html` in your web browser
   - Or use a local development server:
     ```bash
     # Using Python 3
     python -m http.server 8000
     
     # Using Node.js (with http-server)
     npx http-server
     ```

4. **View in browser:**
   - If using a local server, navigate to `http://localhost:8000`
   - Otherwise, double-click `index.html` to open in your default browser

### Remote Control (Push/Pull)

This repository is configured as a public repository, allowing you to:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/hellohacker143/jntuh-result-page-clone.git
   ```

2. **Make changes locally:**
   - Edit files as needed
   - Test your changes

3. **Commit and push changes:**
   ```bash
   git add .
   git commit -m "Your commit message"
   git push origin main
   ```

4. **Pull latest changes:**
   ```bash
   git pull origin main
   ```

**Note:** You'll need appropriate permissions to push changes. Fork the repository if you want to make your own modifications.

## File Structure

```
jntuh-result-page-clone/
├── index.html          # Main HTML file with form structure
├── README.md           # This documentation file
└── (Additional CSS/JS files to be added as needed)
```

## Technologies Used

- HTML5
- CSS3 (inline styles)
- JavaScript (for form validation and CAPTCHA)
- jQuery UI (for date picker functionality)

## Disclaimer

This project is created purely for educational purposes. It is not affiliated with, endorsed by, or connected to JNTU-H or any official educational institution. The clone does not collect, store, or process any actual student data.

## Contributing

Contributions are welcome! Feel free to:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/improvement`)
3. Commit your changes (`git commit -am 'Add new feature'`)
4. Push to the branch (`git push origin feature/improvement`)
5. Create a Pull Request

## License

This project is open source and available for educational use.

## Contact

For questions or suggestions, please open an issue in this repository.

---

**Educational Use Only** - This is a demonstration project for learning purposes.
