# Sukoon — Hotels Near the Holy Mosques 🕋

Premium curated hotel booking landing page for stays near **Masjid al-Haram** (Makkah) and **Al-Masjid an-Nabawi** (Madinah).

---

## 🚀 Vercel Pe 1-Click Deploy Karne Ke 3 Tareeqay

### Tareeqa 1: Vercel CLI (Sabse Tez - Sirf 10 Seconds)
Is folder me PowerShell / Terminal open karein aur yeh command chalayein:
```bash
npx vercel
```
- Pehli baar puche ga: `Set up and deploy?` -> Type `y` aur Enter karein.
- Account select karein -> Enter.
- Project name: `sukoon-sacred-stays` -> Enter.
- Vercel foran aapko live URL de dega (e.g. `https://sukoon-sacred-stays.vercel.app`)!

---

### Tareeqa 2: GitHub ke Zariye (Automated Deployment)
1. GitHub par ek new repository banayein: `sukoon-hotels`.
2. Is folder me git push karein:
   ```bash
   git init
   git add .
   git commit -m "Initial Sukoon Stays release"
   git branch -M main
   git remote add origin https://github.com/AAPKA_USERNAME/sukoon-hotels.git
   git push -u origin main
   ```
3. [Vercel Dashboard](https://vercel.com/new) par jayein:
   - **Add New Project** par click karein.
   - Apni `sukoon-hotels` repository ko **Import** karein.
   - **Deploy** par click karein.

---

### Tareeqa 3: Vercel Drag & Drop (Zero Code)
1. [Vercel Dashboard](https://vercel.com/new) open karein.
2. Niche **"Deploy a third-party Git repository"** ya direct project folder drop section me is folder ko drag-and-drop karein.
3. 5 seconds me site live ho jayegi!

---

## 📁 Project Structure

```
├── index.html         # Main luxury responsive page (Hero, Stays, Filters, Modals)
├── vercel.json        # Vercel production cache & routing configuration
├── package.json       # Project scripts and metadata
├── .gitignore         # Clean git tracking rules
└── assets/
    ├── styles.css     # Full luxury Tailwind & custom styling
    ├── makkah-hero.jpg
    ├── makkah-destination.jpg
    ├── madinah-destination.jpg
    └── hotel-suite.jpg
```
