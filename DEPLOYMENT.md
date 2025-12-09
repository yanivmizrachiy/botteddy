# 🚀 הוראות Deployment

## 🌐 GitHub Pages

הפרויקט מוגדר ל-deployment אוטומטי ל-GitHub Pages.

### 📍 קישור קבוע ויציב:
**https://yanivmizrachiy.github.io/botteddy/**

קישור זה יעבוד מכל מכשיר - מחשב, טלפון, טאבלט - מכל מקום בעולם!

### ⚙️ איך זה עובד?

1. **Deployment אוטומטי**: כל push ל-branch `main` מפעיל את ה-workflow
2. **GitHub Actions**: ה-workflow ב-`.github/workflows/pages.yml` מטפל ב-deployment
3. **זמן בנייה**: בדרך כלל 1-2 דקות לאחר push
4. **עדכון אוטומטי**: כל שינוי בקוד מתעדכן אוטומטית באתר

### 🔍 בדיקת סטטוס

```bash
# בדיקת workflows
gh workflow list

# בדיקת runs אחרונים
gh run list --workflow="Deploy to GitHub Pages"

# צפייה ב-repository
gh repo view --web
```

### 📝 הערות חשובות

- הקישור זמין מיד לאחר ה-deployment הראשון
- אם יש שגיאה, בדוק את ה-Actions tab ב-GitHub
- הנתיבים ב-HTML משתמשים ב-`public/` - זה עובד ב-GitHub Pages
- האתר זמין 24/7 ללא עלות

### 🎯 Custom Domain (אופציונלי)

אם תרצה domain מותאם אישית:
1. הוסף קובץ `CNAME` עם ה-domain שלך
2. הגדר DNS records
3. עדכן את ה-settings ב-GitHub Pages

---

**נוצר:** 2025-01-05  
**עודכן:** אוטומטית עם כל deployment

