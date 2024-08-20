# פרוצדורות אורתופדיות - מאגר מידע

מאגר מידע זה מספק מידע מקיף על מגוון רחב של פרוצדורות אורתופדיות נפוצות. המידע כולל:

- **הגדרות**: הסברים קצרים על מהות הפרוצדורה
- **תסמינים**: תיאור התסמינים האופייניים לכל בעיה
- **אבחון**: שיטות המשמשות לאבחון הבעיה
- **טיפול**: אפשרויות טיפול שמרניות וניתוחיות
- **החלמה**: מידע על תהליך ההחלמה לאחר ניתוח או טיפול
- **מניעה**: המלצות למניעת בעיות אורתופדיות

## מבנה המאגר

המאגר בנוי בצורה המאפשרת הצגה קלה ונוחה של המידע במכשירים ניידים. הוא כולל את השדות הבאים לכל פרוצדורה:

- `ProcedureHeader`: כותרת הפרוצדורה
- `ProcedureBody`: תוכן הפרוצדורה בפורמט HTML
- `ProcedurePreview`: תקציר קצר של הפרוצדורה

## רשימת פרוצדורות

המאגר כולל מידע על הפרוצדורות הבאות:

1. טראומטולוגיה מוסקולו-סקלטלית
2. דלקות מפרקים ושדרה
3. דלקת מפרקים מסוריאטית
4. דלקת מפרקים שגרונית
5. הארכת גידים בגפיים
6. טיפול בגלי הלם
7. מחלות ופגיעות בכף רגל וקרסול
8. צוואר
9. אורתופד עמוד שדרה
10. אורתופדיה
11. החלפה חלקית של מפרק הברך ("חצי ברך")
12. תיקון פריקת פיקה
13. ארטרוסקופיה
14. אורתופדיית ברכיים
15. אורתופדיית גפיים עליונים
16. אורתופדיה - טיפול בשברים מורכבים

### שימוש במאגר

המאגר מיועד לספק מידע ראשוני בלבד ואינו מהווה תחליף לייעוץ רפואי מקצועי. אם יש לך בעיה אורתופדית, פנה תמיד לרופא.

---

**כתב ויתור**: המידע במאגר זה נועד למטרות אינפורמטיביות בלבד ואינו מהווה ייעוץ רפואי. אין להשתמש במידע זה לאבחון או טיפול בבעיה רפואית כלשהי ללא התייעצות עם רופא מוסמך.

---

# Orthopedic Procedures - Database

This database provides comprehensive information on a wide range of common orthopedic procedures. The information includes:

- **Definitions**: Brief explanations of the nature of the procedure
- **Symptoms**: Description of typical symptoms for each problem
- **Diagnosis**: Methods used to diagnose the problem
- **Treatment**: Conservative and surgical treatment options
- **Recovery**: Information on the recovery process after surgery or treatment
- **Prevention**: Recommendations for preventing orthopedic problems

## Database Structure

The database is built in a way that allows easy and convenient display of information on mobile devices. It includes the following fields for each procedure:

- `ProcedureHeader`: Title of the procedure
- `ProcedureBody`: Content of the procedure in HTML format
- `ProcedurePreview`: Short summary of the procedure

## List of Procedures

The database includes information on the following procedures:

1. Musculoskeletal Traumatology
2. Joint and Spine Inflammations
3. Psoriatic Arthritis
4. Rheumatoid Arthritis
5. Limb Lengthening
6. Shock Wave Therapy
7. Foot and Ankle Diseases and Injuries
8. Neck
9. Spine Orthopedics
10. Orthopedics
11. Partial Knee Replacement ("Half Knee")
12. Patellar Dislocation Repair
13. Arthroscopy
14. Knee Orthopedics
15. Upper Limb Orthopedics
16. Orthopedics - Treatment of Complex Fractures

### Using the Database

This database is intended to provide initial information only and is not a substitute for professional medical advice. If you have an orthopedic problem, always consult a doctor.

---

**Disclaimer**: The information in this database is for informational purposes only and does not constitute medical advice. Do not use this information to diagnose or treat any medical condition without consulting a qualified physician.

---

## Content Generation Prompt

The content for each medical procedure in this database is generated using a specific prompt. This prompt ensures consistency and comprehensiveness across all entries. Here are the key aspects of the content generation process:

### Outputs Generated for Each Procedure

1. **ProcedureBody (HTML)**: The main content of the article in HTML format.
2. **ProcedurePreview**: A brief description of the procedure.
3. **ProcedureHeader**: A short title for the procedure.

### ProcedureBody (HTML) Guidelines

- Content is surrounded by `<div class="procedure-content"></div>`.
- Various HTML structures are used, including:
  - Short paragraphs (`<p class="procedure-para">`)
  - Unordered lists (`<ul class="procedure-ul">` with `<li class="procedure-li">`)
  - Ordered lists (`<ol class="procedure-ol">` with `<li class="procedure-li">`)
  - Subheadings (`<h3 class="procedure-head">`)
- Information covers the procedure's purpose, steps, benefits, risks, and recovery process.
- Maximum length: 500 tokens.

### ProcedurePreview Guidelines

- Concise summary in plain text.
- Highlights key aspects or benefits.
- Maximum length: 140 characters.
- Presents information confidently and factually.

### ProcedureHeader Guidelines

- Exactly matches the name of the procedure.

### Additional Notes

- Hebrew procedure names are not translated to English.
- The content aims to be factually accurate and relevant to general medical practice.
- The prompt ensures a consistent structure across all procedure entries while allowing for detailed and informative content.

This approach to content generation helps maintain the quality and uniformity of the information provided in the database, ensuring it remains a valuable resource for users seeking information on orthopedic procedures.
