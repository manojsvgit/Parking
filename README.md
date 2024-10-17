# Parking System Web Application

A simple parking system web interface allowing users to sign in or sign up using vehicle information. It also supports login via social media platforms.

## Features

- **Sign In:** Users can sign in using their vehicle number and password.
- **Sign Up:** New users can create an account by signing up with their vehicle number, email, and password.
- **Social Media Login:** Users can choose to log in via popular social media platforms like Facebook, Twitter, Google, and LinkedIn.
- **Responsive Design:** The layout is designed to be mobile-friendly and responsive across different devices.
- **Animations:** Smooth transitions between the sign-in and sign-up panels.

## Technologies Used

- **HTML5:** Structure of the application.
- **CSS3:** For styling and responsiveness (styles provided in `style.css`).
- **JavaScript:** For handling UI interactions (such as switching between sign-in and sign-up forms) (script provided in `script.js`).
- **FontAwesome:** For adding icons (car, lock, email, etc.).
- **Social Media Integration:** Buttons linking to social media login.

## How to Use

1. **Sign In:**  
   - Enter your vehicle number and password.
   - Click the "Login" button to access the parking services.
   
2. **Sign Up:**  
   - Enter your vehicle number, email, and password.
   - Click "Sign up" to create an account.

3. **Social Media Login:**  
   - Click on any social media icon (Facebook, Twitter, Google, LinkedIn) to sign in with your social media account.

4. **Switch Forms:**  
   - New users can switch to the sign-up form by clicking the "Sign up" button on the left panel.
   - Existing users can switch to the sign-in form by clicking the "Sign in" button on the right panel.

## Project Structure

```bash
.
├── index.html         # Main HTML file for the web application
├── style.css          # CSS file for styling
├── script.js          # JavaScript file for form handling and panel switching
├── img/               # Directory for images (e.g., log.svg, register.svg)
├── README.md          # This file
```

## How to Run

1. **Clone the repository:**
  ```bash
    git clone https://github.com/yourusername/parking-system.git
  ```
2. **Navigate into the project directory:**
```bash
  cd parking-system
  ```
3. **Open index.html in your preferred web browser to view and interact with the parking system UI.**

## Future Enhancements
- Integration with a backend for user authentication and vehicle tracking.
- Database setup (MongoDB) to store user and vehicle data.
- Timer functionality to track parking duration.
- Payment gateway integration for parking fees.
- Improved UI/UX based on feedback.

## License
This project is licensed under the MIT License - see the LICENSE file for details.
