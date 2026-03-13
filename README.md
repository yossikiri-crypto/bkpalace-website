# B.K Palace – Landing Page

דף נחיתה יוקרתי לוילה B.K Palace בחדרה.

## קבצים

| קובץ | תיאור |
|------|-------|
| `index.html` | דף הנחיתה המלא – HTML + CSS + JS בקובץ יחיד |

## הרצה מקומית

פתחו את `index.html` ישירות בדפדפן, או הריצו שרת מקומי:

```bash
# Python 3
python3 -m http.server 8080

# Node (npx)
npx serve .
```

פתחו: `http://localhost:8080`

## אחסון (Hosting)

הדף הוא קובץ HTML סטטי יחיד – ניתן לפרוס בכל שירות:

- **Netlify** – גררו את הקובץ ל-[netlify.com/drop](https://netlify.com/drop)
- **GitHub Pages** – push ל-branch `gh-pages`
- **Vercel** – `vercel deploy`
- **כל שרת רגיל** – העלו את `index.html` לשרת

## סקשנים

1. **Hero** – תמונת רקע מלאת מסך עם כותרת ו-CTA
2. **אודות** – 3 כרטיסי סטטיסטיקה + פסקת תיאור
3. **מה יש** – גריד של 10 מתקנים עם אימוג'י
4. **גלריה** – 6 תמונות ב-masonry + lightbox
5. **צרו קשר** – כפתור WhatsApp + פרטי קשר + טופס
6. **Footer** – הצהרת נגישות + קישורים

## נגישות (SI 5568 / WCAG 2.1 AA)

- `lang="he"` + `dir="rtl"` על תג `<html>`
- קישור "דלג לתוכן" בראש הדף
- Alt text בעברית לכל תמונה
- `aria-label` על כל הכפתורים
- היררכיית כותרות תקנית h1 → h2 → h3
- `:focus-visible` עם מסגרת זהב 3px
- יחס ניגודיות ≥ 4.5:1

## עדכון פרטי קשר

בקובץ `index.html` חפשו:

```
050-6565914          ← מספר טלפון
https://did.li/Bkp-WhatsApp-  ← קישור WhatsApp
info@bkpalace.co.il  ← כתובת מייל (בטופס)
```

## רישיון

© 2025 B.K Palace. כל הזכויות שמורות.
