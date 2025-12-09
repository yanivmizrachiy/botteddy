# 🔗 קישור קצר מקסימלי

## 🎯 המטרה
ליצור קישור קצר ככל האפשר לאתר בוטדי.

## 💡 אפשרויות:

### 1. **Repository חדש עם שם קצר** ⭐ (מומלץ)
צור repository חדש בשם קצר מאוד, למשל:
- `btd` → `yanivmizrachiy.github.io/btd`
- `bot` → `yanivmizrachiy.github.io/bot`
- `tedi` → `yanivmizrachiy.github.io/tedi`

**איך לעשות:**
```bash
# צור repository חדש
gh repo create btd --public --description "🤖 בוטדי"

# הוסף redirect
echo '<meta http-equiv="refresh" content="0; url=https://yanivmizrachiy.github.io/botteddy/">' > index.html

# Push
git init
git add .
git commit -m "Redirect to botteddy"
git remote add origin https://github.com/yanivmizrachiy/btd.git
git push -u origin main
```

### 2. **שירות קיצור קישורים חיצוני**
- Bitly: `bit.ly/botteddy`
- TinyURL: `tinyurl.com/botteddy`
- Short.io: `short.io/botteddy`

### 3. **Custom Domain** (דורש רכישת domain)
אם יש לך domain, אפשר להשתמש ב:
- `btd.co.il`
- `bot.tedi.co.il`
- וכו'

## 🚀 המלצה
האפשרות הכי טובה היא ליצור repository חדש בשם `btd` - זה יתן קישור קצר מאוד:
**https://yanivmizrachiy.github.io/btd**

---

**נוצר:** 2025-01-05

