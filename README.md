# KamaKama (SplitIt) 🍽️

אפליקציית Web חברתית שנועדה לפתור את “נקודת החיכוך” המביכה של תשלום החשבון במסעדה – עם חוויית שימוש משחקית (Gamification).

## מה יש באפליקציה?
- **Dashboard** להזנת סכום חשבון, אחוז טיפ, וניהול סועדים
- **Equal Split** – חלוקה שווה (כולל טיפ) + כפתור **העתקה/שיתוף**
- **Itemized Split** – חלוקה לפי פריטים (כל אחד מזין כמה אכל) + **בר התקדמות** עד “בול!”
- **Credit Roulette** – גלגל מזל דינמי (SVG) שמגריל מי משלם + קונפטי + ויברציה במובייל
- **Sharing** – שימוש ב‑Web Share API (עם fallback להעתקה)

## טכנולוגיות
- HTML5
- Vanilla JS (ES6+)
- Tailwind CSS (via CDN)
- Lucide Icons
- Google Fonts (Rubik)
- Client‑side only (אין שרת)

## הרצה מקומית
פשוט פתחו את `index.html` בדפדפן.

## העלאה ל‑GitHub Pages (Live Site)
1. צרו ריפו חדש ב‑GitHub (למשל: `kamakama-splitit`)
2. העלו את הקבצים (`index.html`, `README.md`)
3. לכו ל:
   - **Settings → Pages**
   - תחת **Build and deployment** בחרו:
     - **Source**: Deploy from a branch
     - **Branch**: `main` / root
4. אחרי הפרסום, תקבלו לינק לאתר החי.

## התאמות מהירות
- כותרות/צבעים: בתוך `index.html`
- טווח טיפ: רכיב ה‑range (`0–25%`)
- הודעות שיתוף: פונקציות `buildEqualMsg` ו‑`buildWinnerMsg`

---

Made for quick, fun bill-splitting. 🎉
