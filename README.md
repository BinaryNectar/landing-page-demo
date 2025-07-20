# Landing Page Demo

A fully-featured, modern landing page template showcasing advanced web design techniques using **HTML5**, **Bootstrap 5**, **AOS (Animate On Scroll)**, and vanilla **JavaScript**. It includes theming, a loader, parallax hero, animations, responsive layout, interactive components, and a newsletter form.

---

## 🔧 Features

- **Page Loader**: Full-screen spinner overlay until all assets load.
- **Dark/Light Mode Toggle**: Switch between light and dark themes with smooth CSS class rotation.
- **Parallax Hero Section**: Full-height background image with centered dynamic text and AOS fade-down animation.
- **Dynamic Hero Text**: Rotating keywords (`Innovation`, `Creativity`, `Excellence`) via JavaScript.
- **Modal Popup**: Bootstrap modal triggered from the hero `Learn More` button.
- **Features Grid**: Three-card responsive section with flip animations on scroll.
- **Image Carousel**: Bootstrap carousel with uniform-height images using `object-fit: cover`.
- **Newsletter Form**: Centered email subscription form.
- **Custom Buttons**: Globally styled black buttons overriding Bootstrap defaults.
- **Responsive Design**: Built on Bootstrap’s grid and utility classes for mobile-first layouts.

---

## 🗂️ File Structure

```
├── index.html       # Main landing page
├── style.css        # Custom styles and theme variables
└── assets/          # (Optional) Local images for hero & carousel backgrounds
    ├── ales-nesetril-Im7lZjxeLhg-unsplash.jpg
    ├── luca-dugaro-tuueCVnYN0s-unsplash.jpg
    ├── max-petrunin-dPzF4JbtxC8-unsplash.jpg
    └── mike-kononov-lFv0V3_2H6s-unsplash.jpg
```

---

## ⚙️ Installation & Usage

1. **Clone or Download** this repository:

   ```bash
   git clone https://github.com/binarynectar/landing-page-demo.git
   cd limitless-web-design
   ```

2. **Host Locally**

   - Simply open `index.html` in your browser, or
   - Serve via a simple HTTP server (recommended for AOS animations):
     ```bash
     npx http-server .
     # or
     python3 -m http.server 8000
     ```

3. **Ensure Internet Access** for CDN assets (Bootstrap & AOS). To use locally, download and link those libraries instead.

---

## 🎨 Customization

- **Theme Colors**: Tweak CSS variables in `:root` of **style.css**:
  ```css
  --bg-light: #f8f9fa;
  --bg-dark: #212529;
  --text-light: #212529;
  --text-dark: #f8f9fa;
  ```
- **Hero Images**: Replace the URL in the inline `style` of the `.parallax` section or point to local assets.
- **Carousel Slides**: Edit the `<img>` `src` attributes within the `#demoCarousel` container.
- **Loader Spinner Color**: Change `.spinner-border` class to desired utility (e.g., `text-primary`).
- **Toggle Label Text**: Adjust the logic in the `<script>` for `modeLabel.textContent` and the checkbox state.
- **Animation Settings**: Modify `AOS.init` parameters (e.g., `duration`, `delay`, `easing`) or per-element `data-aos-*` attributes.
- **Custom Buttons**: The `.btn` override in **style.css** can be removed or altered if using default Bootstrap styles.

---

## 📚 Dependencies

- [Bootstrap 5.3.0](https://getbootstrap.com/)
- [AOS 2.3.4](https://michalsnik.github.io/aos/)

All other functionality is implemented with vanilla JavaScript and CSS.

---

## 🤝 Credits

- **Bootstrap Components & Grid** — Bootstrap contributors
- **Animations** — AOS (Animate On Scroll)
- **Loader Spinner** — Bootstrap utility classes

### Image Credits

Photo by <a href="https://unsplash.com/@alesnesetril?utm_content=creditCopyText&utm_medium=referral&utm_source=unsplash">Ales Nesetril</a> on <a href="https://unsplash.com/photos/gray-and-black-laptop-computer-on-surface-Im7lZjxeLhg?utm_content=creditCopyText&utm_medium=referral&utm_source=unsplash">Unsplash</a>

Photo by <a href="https://unsplash.com/@mikofilm?utm_content=creditCopyText&utm_medium=referral&utm_source=unsplash">Mike Kononov</a> on <a href="https://unsplash.com/photos/architectural-photography-of-building-with-people-in-it-during-nighttime-lFv0V3_2H6s?utm_content=creditCopyText&utm_medium=referral&utm_source=unsplash">Unsplash</a>

Photo by <a href="https://unsplash.com/@mvogulov?utm_content=creditCopyText&utm_medium=referral&utm_source=unsplash">Max Petrunin</a> on <a href="https://unsplash.com/photos/a-holographic-dome-with-circular-openings-dPzF4JbtxC8?utm_content=creditCopyText&utm_medium=referral&utm_source=unsplash">Unsplash</a>

Photo by <a href="https://unsplash.com/@lucadgr?utm_content=creditCopyText&utm_medium=referral&utm_source=unsplash">Luca Dugaro</a> on <a href="https://unsplash.com/photos/photo-of-clouds-tuueCVnYN0s?utm_content=creditCopyText&utm_medium=referral&utm_source=unsplash">Unsplash</a>

---

## 📜 License

This project is open source and available under the [MIT License](LICENSE).
