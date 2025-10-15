This project is a simple web-based CAPTCHA solver interface. It displays a CAPTCHA image and provides an input field for the user to enter the text they see in the image. Upon submission, it checks if the entered text matches the correct CAPTCHA solution.

### Features
- Displays a CAPTCHA image (default: `sample.png` or an image from a URL parameter).
- Input field for users to enter CAPTCHA text.
- "Solve CAPTCHA" button to submit the input.
- Visual feedback (Correct/Incorrect) after submission.
- Loading spinner during CAPTCHA verification.

### How to Use
1.  **Clone the repository** (or download `index.html`, `sample.png`).
2.  **Open `index.html`** in your web browser.
3.  **Enter the text** displayed in the CAPTCHA image into the input field.
4.  **Click "Solve CAPTCHA"**.
5.  The application will indicate whether your entry was correct or incorrect.

### Custom CAPTCHA Image
You can display a custom CAPTCHA image by passing its URL as a query parameter in the URL. For example:
`index.html?url=https://example.com/your-captcha-image.png`

### CAPTCHA Logic
- The correct CAPTCHA text is hardcoded as `ADCR3` (case-insensitive).
- The solution check is client-side for demonstration purposes.
- A 1-second delay simulates network latency or server-side processing.

### Technologies Used
- HTML5
- Tailwind CSS (for styling)
- JavaScript (for logic)

### File Structure
- `index.html`: The main HTML file containing the structure, styling, and JavaScript logic.
- `sample.png`: A sample CAPTCHA image used by default.
