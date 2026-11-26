# KINGS Jerusalem – אתר המשרד

אתר סטטי (HTML/CSS/JS) של KINGS Jerusalem Luxury Real Estate.

- `index.html` – כל האתר (עברית/אנגלית).
- `data/properties.json` – הנכסים. `data/agents.json` – הסוכנים.
- `img/` – תמונות שער (`img/<id>.jpg`), תמונות מהוואטסאפ (`img/w/`), לוגו (`img/brand/`).

תמונות הגלריה של הנכסים הישנים עדיין נטענות מ-Base44 (`CONFIG.IMG_BASE` ב-index.html) ויש להעבירן לפני סגירת החשבון שם.

פריסה: Cloudflare Pages, ללא שלב build (Build command ריק, Output directory: `/`).
