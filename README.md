# StentWise v2 — Interventional Cardiology Decision Support

A deployable Progressive Web App (PWA) for interventional cardiologists.
Installs on iPhone/Android home screen. No App Store required.

---

## What's Included (7 Clinical Modules)

| Module | Guideline Source |
|---|---|
| ⚖️ PCI vs Medical Therapy (AUC) | 2021 ACC/AHA/SCAI Revascularization + ISCHEMIA/FAME 2 |
| ⚠️ PCI Risk | 2025 ACC/AHA ACS + 2021 Revascularization |
| 🩸 Bleeding Complications | 2025 ACC/AHA ACS + ARC-HBR 2023 |
| 💊 DAPT Duration | 2025 ACC/AHA ACS (Feb 27, 2025) |
| 🔬 Lipid Management | 2026 ACC/AHA Dyslipidemia (Mar 13, 2026) |
| 🫀 Cardiac Rehab | 2025 ACC/AHA ACS + CR evidence base |
| 🛡️ Secondary Prevention | 2025 ACS + 2026 Lipids + subspecialty guidelines |

Plus: AI Query Bar for any clinical question.

---

## Deploy to Vercel (FREE — 5 minutes)

### Option A: GitHub + Vercel (Recommended)
1. Go to **github.com** → New repository → name it `stentwise`
2. Upload all files from this folder (drag & drop the unzipped folder)
3. Commit
4. Go to **vercel.com** → Sign up with GitHub (free)
5. "Add New Project" → select `stentwise` repo
6. Vite auto-detected → click **Deploy**
7. Your app is live at `https://stentwise.vercel.app` (or custom name)

### Option B: Netlify Drop (Even Faster)
1. Go to **netlify.com** → "Deploy manually"
2. Drag the entire unzipped folder into the browser
3. Done — live URL provided instantly

---

## Add to iPhone Home Screen
1. Open the app URL in **Safari** on iPhone
2. Tap the **Share** button (box with arrow up)
3. Scroll down → tap **"Add to Home Screen"**
4. Name it **StentWise** → tap **Add**
5. App icon now appears on your home screen

---

## Notes
- Requires internet connection (calls Anthropic API for AI content)
- No patient data is ever transmitted or stored — HIPAA safe
- Module content cached within each session
- Works on iOS Safari, Android Chrome, and desktop browsers

---

## Guideline Sources
- 2025 ACC/AHA/ACEP/NAEMSP/SCAI ACS Guideline (JACC + Circulation, Feb 27, 2025)
- 2026 ACC/AHA/Multisociety Dyslipidemia Guideline (JACC + Circulation, Mar 13, 2026)
- 2021 ACC/AHA/SCAI Coronary Artery Revascularization Guideline (Circulation, Dec 2021)
- ARC-HBR Consensus 2020/2023
- ACC/AHA/SCAI Appropriate Use Criteria for Coronary Revascularization
