# AutoNova – Multi‑Brand Car Showroom Web App 🚗✨

AutoNova is a **front-end car showroom** that showcases multiple brands through dedicated, media-rich pages, with a simple landing page, navigation, and basic auth flow (login / sign‑up). It’s designed as an educational web project to practice **HTML, CSS, and JavaScript** with clean structure and visually appealing layouts.

---

## 1. AutoNova Overview 🌐

**Root directory:** this repository  
**Entry point:** `index.html`

AutoNova provides:

- A **landing page** with a dropdown menu of car brands.
- **Brand-specific pages** with images, videos, and themed styles.
- A simple **Login** and **Sign Up** experience.
- A consistent visual identity across the project (`AutoNova.css`).

---

## 2. Features ✨

- **Multi-brand navigation**
  - Dropdown menu linking to: Audi, Ferrari, Ford, Honda, Hennessey (HPE), Mazda, Nissan, Pagani, Toyota, and Volvo.

- **Media-rich layouts**
  - High-quality images, background sections, and videos per brand to simulate a car showroom.

- **Auth pages**
  - Dedicated `Login` and `Sign up` pages with their own styling and basic client-side behavior.

- **Static & lightweight**
  - Entirely client-side; no backend or database required.

---

## 3. Tech Stack 🛠️

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

---

## 4. How to Run 🚀

1. Download or clone this repository.  
2. Open `index.html` using any modern web browser:
   - Double-click `index.html`, or  
   - Right-click → **Open with** → choose your browser.
3. Use the navigation bar to explore models and auth pages.

> This is usually enough for local viewing on Windows / desktop browsers.

---

## 5. Project Structure 🗂️

```plaintext
AutoNova/
├── index.html              # Main landing page + navbar + models dropdown
├── AutoNova.css            # Global styling for landing & navigation
│
├── Homepage/               # Extra homepage layout & assets
│   ├── Homepage.html
│   ├── Image1.png
│   └── Image2.png
│
├── Models/                 # Brand-specific experiences
│   ├── Audi/
│   ├── ferrari/
│   ├── ford/
│   ├── Honda/
│   ├── HPE/                # Hennessey Performance
│   ├── Mazda/
│   ├── nissan/
│   ├── Pagani/
│   ├── toyota/
│   └── Volvo/
│
├── Login/                  # Login page + styling
│   ├── index.html
│   └── AutoNova Login.css
│
└── Sign up/                # Sign-up page + styling + JS
    ├── index.html
    ├── AutoNova Sign up.css
    └── AutoNova Sign up.js
```

Each brand folder under `Models/` typically includes:

- A dedicated `index.html` page for that brand.
- One or more CSS files for brand styling.
- Optional JavaScript for interactions.
- Images, videos, and other media assets.

---

## 6. Navigation & Usage 🖱️

1. **Landing Page (`index.html`)**
   - Displays the `AutoNova` logo and a navigation bar.
   - The **Models** dropdown expands to show all available car brands.
   - The main hero section invites users to get “on the road”.
   - A **Login** button takes you to the login page.

2. **Model Pages (`Models/<Brand>/index.html`)**
   - Opened via the **Models** dropdown links (often in a new tab).
   - Showcase brand-specific imagery, styling, and sometimes video backgrounds.

3. **Auth Pages**
   - `Login/index.html`: Simple login form UI with its own stylesheet (`AutoNova Login.css`).
   - `Sign up/index.html`: Registration form, styled via `AutoNova Sign up.css` and enhanced by `AutoNova Sign up.js`.

---

## 7. Ideas for Extensions & Improvements 🔧

You can extend this project in many directions, for learning or portfolio purposes:

- **Feature Enhancements**
  - Add car details (price, performance, specs) as cards per brand.
  - Implement a “Compare Cars” view across multiple brands.

- **Interactivity & Data**
  - Load car data from JSON files instead of hardcoding it into HTML.
  - Add search and filter options (by brand, type, price range, etc.).

- **UI/UX & Responsiveness**
  - Improve layout for tablets and mobile devices.
  - Add a **dark / light mode** toggle and persistent theme preference.

- **Auth Simulation**
  - Simulate login state on the front end (e.g., show a welcome banner after login).
  - Add form validation and better error messages.

---

## 8. Contributing 🤝

Contributions and customizations are welcome. You can:

- Refine styling, typography, and component layouts.
- Add more brands or expand existing brand pages with new sections.
- Improve accessibility (semantic HTML, ARIA roles, keyboard navigation, color contrast).

If you build on top of AutoNova, feel free to share your own fork or deployment.

---

## 9. Connect With Me 🌐

<p align="center">
  <a href="mailto:m.raafatgaber@gmail.com">
    <img src="https://img.shields.io/badge/Email-m.raafatgaber@gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email Badge">
  </a>
  <a href="https://www.linkedin.com/in/mohammed-raafat-swe/">
    <img src="https://img.shields.io/badge/LinkedIn-Mohammed%20Raafat-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn Badge">
  </a>
  <a href="https://github.com/mohammedRaafatt">
    <img src="https://img.shields.io/badge/GitHub-mohammedRaafatt-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub Badge">
  </a>
  <a href="https://www.instagram.com/muhammad_raafat_/">
    <img src="https://img.shields.io/badge/Instagram-muhammad__raafat__-E4405F?style=for-the-badge&logo=instagram&logoColor=white" alt="Instagram Badge">
  </a>
  <a href="https://www.facebook.com/profile.php?id=100004131767214">
    <img src="https://img.shields.io/badge/Facebook-Mohammed%20Raafat-1877F2?style=for-the-badge&logo=facebook&logoColor=white" alt="Facebook Badge">
  </a>
</p>

---

<p align="center">
  🌟 <em>Thanks for checking out AutoNova — enjoy the ride!</em> 🌟
</p>


