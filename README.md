# 🎉 Interactive Birthday Wishing Website

A beautiful, romantic, and interactive **Happy Birthday Wishing Website** featuring custom animations, 3D flip-book cards, interactive floating love letters, and dynamic sound/confetti elements. Designed to create an unforgettable, personalized birthday experience for a loved one.

---

<p align="center">
  <img src="./public/deskBanner.png" alt="Birthday Wishing Website Preview" width="100%" />
</p>

---

## 🌟 Features

- **Cake & Candle Opening Animation:** An animated birthday cake with glowing candle lights, confetti showers, and animated birthday text reveal.
- **Romantic Pink Theme:** Custom HSL rose-pink aesthetic, glassmorphism card overlays, and subtle floating heart animations.
- **Interactive 3D Book Letter:** A 3D flip-book memory card with floating photo frames and customizable heartfelt notes.
- **Envelope & Draggable Love Notes:** Interactive envelope with multiple draggable love letter cards for a surprise note experience.
- **Mini Diary Note:** A subtle bottom letter popup for quick extra wishes.
- **Fully Responsive:** Smooth animations and responsive layout for mobile, tablet, and desktop screens.

---

## 🚀 Getting Started

### 1. Prerequisites
Ensure you have [Node.js](https://nodejs.org/) installed.

### 2. Installation & Setup
```bash
# Install dependencies
npm install

# Start local development server
npm run dev
```

The app will start locally (typically at `http://localhost:5173`).

---

## 🚀 Deploy to GitHub Pages

1. Push this project to a GitHub repository using the `main` branch.
2. In the repository, open **Settings → Pages**.
3. Under **Build and deployment**, select **GitHub Actions** as the source.
4. Push to `main` (or run **Deploy to GitHub Pages** from the Actions tab).

The workflow in `.github/workflows/deploy.yml` builds the app and publishes the `dist` folder automatically. The deployed site will be available at:

`https://<your-username>.github.io/<repository-name>/`

---

## 🛠️ How to Customize

1. **Names & Date:** Update names and birth date in `src/pages/Home.jsx`, `src/pages/LoveLetter.jsx`, `src/components/OpeningAnimation.jsx`, and `src/components/BookCanvas.jsx`.
2. **Messages:** Customize the messages in `lettersData` inside `src/pages/LoveLetter.jsx` and `src/components/BookCanvas.jsx`.
3. **Photos:** Replace `src/assets/orihime.jpg` with your recipient's photo.

---

## 💖 Credits & Acknowledgments

- **Edited by:** **HXNI**
- Built with React, Vite, Tailwind CSS, and CSS3 Animations.

---

*Made with ❤️ to bring smiles and warm birthday wishes.*
