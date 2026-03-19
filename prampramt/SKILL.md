---
name: prampramt
description: Reverse-engineer the prompts behind any AI product or service. Use this skill when the user provides a URL and asks to analyze it, "prampramt it", wants to know what prompts built a product, wants to clone or replicate a product's AI behavior, or asks for reverse prompt engineering. Trigger on phrases like "פרמפרמט", "reverse prompt", "what prompts built this", "analyze this product".
---

# פרמפרמט — Reverse Prompt Engineering

כשמשתמש נותן לך URL של מוצר או שירות AI:

## תהליך

1. **חפש מידע** על המוצר דרך web search — אתר רשמי, Product Hunt, ביקורות, תיאורים, סרטוני הדגמה
2. **נתח** את המוצר לעומק:
   - מה הוא עושה ומה הבעיה שהוא פותר
   - מי קהל היעד
   - מה הטון והאישיות של המוצר
   - מה הפיצ'רים המרכזיים
   - מה הארכיטקטורה הכללית
3. **הסק** מתוך הניתוח מה הפרומפטים שבנו אותו

## פלט

החזר תמיד את הפורמט הבא:

### 🧠 Master Prompt
הפרומפט הגדול הכללי שמגדיר את כל המוצר — זהות, מטרה, טון, התנהגות. כתוב אותו כפרומפט אמיתי שמישהו יכול להשתמש בו.

### 🔩 Component Prompts
פרומפט נפרד לכל רכיב מרכזי של המוצר (למשל: onboarding, מענה לשאלות, tone of voice, error handling, וכו').

### ⚙️ Stack Guess
השערה לגבי: מודל AI, פריימוורק, ארכיטקטורה.

### 📊 Confidence
ציין רמת ביטחון: גבוה / בינוני / נמוך — ולמה.

## כללים חשובים

- כתוב פרומפטים **אמיתיים** שמישהו יכול להעתיק ולהשתמש — לא תיאורים
- היה ספציפי וטכני
- אם המידע הציבורי מוגבל — ציין זאת וכתוב את ה-best guess שלך
