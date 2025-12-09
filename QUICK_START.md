# ⚡ קישור קצר מקסימלי - הוראות מהירות

## 🎯 הקישור הקצר ביותר:

### **https://yanivmizrachiy.github.io/btd/**

(אם ה-repository `btd` קיים)

---

## 📝 איך ליצור קישור קצר:

### אפשרות 1: יצירת Repository חדש עם שם קצר ⭐

1. צור repository חדש ב-GitHub בשם `btd`:
   ```bash
   gh repo create yanivmizrachiy/btd --public --description "🤖 בוטדי - קישור קצר"
   ```

2. צור קובץ `index.html` עם redirect:
   ```html
   <!DOCTYPE html>
   <html>
   <head>
       <meta http-equiv="refresh" content="0; url=https://yanivmizrachiy.github.io/botteddy/">
       <script>window.location.replace("https://yanivmizrachiy.github.io/botteddy/");</script>
   </head>
   <body>מעביר לבוטדי...</body>
   </html>
   ```

3. Push ל-GitHub:
   ```bash
   git init
   git add index.html
   git commit -m "Redirect to botteddy"
   git remote add origin https://github.com/yanivmizrachiy/btd.git
   git push -u origin main
   ```

4. הפעל GitHub Pages ב-Settings → Pages

### אפשרות 2: שירות קיצור קישורים חיצוני

- **Bitly**: https://bitly.com
- **TinyURL**: https://tinyurl.com
- **Short.io**: https://short.io

---

## ✅ התוצאה:

**קישור קצר:** `yanivmizrachiy.github.io/btd`  
**מפנה ל:** `yanivmizrachiy.github.io/botteddy`

---

**נוצר:** 2025-01-05

