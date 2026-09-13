# Glass LoginPage

A responsive login/registration popup UI built with **HTML, CSS, and vanilla JavaScript**. Features a glassmorphism-style card that slides between Login and Registration forms, triggered by a navbar button.

<img width="1920" height="1080" alt="Image" src="https://github.com/user-attachments/assets/48085898-a4b8-4981-bfc4-4edde3df9187" />

## ✨ Features

- 🔐 Toggle between **Login** and **Registration** forms with smooth slide animation
- 🪟 Glassmorphism design (frosted glass effect via `backdrop-filter`)
- 📱 Popup opens/closes via navbar button and close icon
- 🎨 Floating label inputs for Email, Password, and Username
- ✅ "Remember me" and "Terms & Conditions" checkboxes
- 🖼️ Full-screen background image with gradient overlay
- ⚡ No dependencies except [Ionicons](https://ionic.io/ionicons) for icons

## 📁 Project Structure

```
├── index.html       # Markup for navbar, login form, and registration form
├── style.css        # Styling, layout, animations, and glassmorphism effects
├── script.js        # Toggle logic for popup and form switching
└── Background.jpg   # Background image
```

## 🚀 Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/<your-username>/<repo-name>.git
   ```
2. Navigate into the project folder:
   ```bash
   cd <repo-name>
   ```
3. Open `index.html` in your browser — no build step or server required.

## 🛠️ How It Works

- Clicking the **Login** button in the navbar adds the `active-popup` class to the `.wrapper`, revealing the popup.
- Clicking the **close icon** removes `active-popup`, hiding the popup.
- Clicking **Register** inside the login form adds the `active` class, sliding the registration form into view.
- Clicking **Login** inside the registration form removes `active`, sliding back to the login form.

## 🎨 Customization

- Change the background image by replacing `Background.jpg` and updating the path in `style.css`.
- Adjust the primary color theme by updating the `#162938` hex values throughout `style.css`.
- Update the popup size via `.wrapper` width/height in `style.css`.

## 📄 License

This project is open source and available under the [MIT License](LICENSE).
