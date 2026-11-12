# סטטוס מקורות חסומים

ריצה: חמישי 12.11.2026, 11:42–12:00 (שעון ישראל). ריצה ראשונה – לא היה blocked_sources.csv קודם.
סה"כ: 16 שורות "מועמד" (11 חדשות + 5 שכבר בבורד הלידים) · 6 שורות "מכרז פתוח". ~35 דפים בדפדפן, 5 חיפושי רשת.

## לפי מקור

### עיריית ירושלים – נפתח
- https://www.jerusalem.muni.il/he/city/tenders/contractorstenders/decisions/ → מפנה לדף ועדת המכרזים: https://www.jerusalem.muni.il/he/city/council/committees/Committee?id=30a0e81f-30e4-ee11-904c-000d3ab1f351
- נקראו דוחות ישיבות 46 (03.11.2026) ו-45 (20.10.2026). כל דוח הוא PDF ב-jerintsvcblob.blob.core.windows.net (חסום מהענן); נקרא בדפדפן: ניווט לכתובת ה-PDF ואז pdf.js (cdn.jsdelivr.net, pdfjs-dist@4.0.379) בתוך הדף.
- מועמדים: 3 (זוכי מכרז ניקיון מבני חינוך 40.2026). בישיבה 46 – מילגם (כבר בלידים), השאר נסחרות או קטנות.
- singleproviders/ – נפתח, "לא נמצאו מכרזים".
- ישיבה הבאה: 47 ב-17.11.2026 (הדוח עולה בדרך כלל כשבוע-שבועיים אחרי).

### gov.il – נפתח חלקית
- רשות החשמל – החלטות: https://www.gov.il/he/collectors/policies?officeId=c1d2ec1c-7f78-4d96-a739-1ed90f9e2b4b&limit=10&Type=2c0063a0-b17b-4979-83e9-ace8454572ec (עמוד 2: &skip=10). ה-PDF של כל החלטה: https://www.gov.il/BlobFolder/policy/<מספר>/he/Files_Hachlatot_<מספר>.pdf – לקרוא בניווט ישיר ל-PDF + pdf.js (בדף ה-HTML של gov.il ה-CSP חוסם את pdf.js). מועמדים: 2.
- רשות התחרות – לא נמצאה רשימה עדכנית של הודעות/החלטות מיזוג. הקולקטור https://www.gov.il/he/collectors/legalinfo?officeId=51752c15-473a-4c15-959f-e719cb113529&TopicId=8868151f-d968-4931-b4fd-1c9ea0feeb4e מציג רק "אישור בתנאים" ישנים. הכתובת dynamiccollectors/merger_notices מחזירה 404. 0 מועמדים.
- הרשות להתחדשות עירונית – חדשות: https://www.gov.il/he/collectors/news/?officeId=03919f7f-55f3-4846-a50b-4079735bf569 – אין פרסום רלוונטי מאז 1.9.2026. 0 מועמדים.
- רשות ההשקעות, המשרד להגנת הסביבה – לא הספקתי.

### מגדילים – נפתח
- https://magdilim.co.il/ ; כתבות נקראות ב-fetch בתוך הדף (פסקאות p).
- מועמדים: 8 (מכרז יקנעם מבואות מערביים – 6 זוכים; בית רומנו ת"א; פרץ בוני הנגב בחדרה). דולגו: ארי נדל"ן ותדהר (נסחרות), אקרו, מטרופוליס (קשורה לאלייד).

### news1 – נפתח (RSS חסום)
- https://www.news1.co.il/indexRSS.aspx נפתח, אבל פידי ה-RSS (‎/Rss/?area=…) מחזירים בדיקת Cloudflare.
- עובד: מדור כלכלה https://www.news1.co.il/Home/L02-S-003-00.html וכתבות Archive/001-D-<id>-00.html.
- מועמדים: 3 (סטרפלאסט, סי.אם. קומפוזיט, מחצבות כפר גלעדי).

### המכרזייה – נפתח
- https://michraziya.co.il/browse/publishers ; דפי גוף: /browse/by/<שם>; חיפוש: /search?q=<מילה>.
- נקראו: רכבת ישראל, חברת החשמל, מקורות, נמל אשדוד; חיפוש "אגירה", "סולארי", "פוטו-וולטאי".
- מכרזים פתוחים שנרשמו: 6.

### רכבת ישראל ונת"ע – חסום
- https://www.rail.co.il/tenders ו-https://www.nta.co.il/ – בדיקת "אני לא רובוט" (Cloudflare). נשלחה התראה לאביב, נוסה שוב אחרי ~10 דקות – עדיין חסום. דולג – אביב לא זמין.

## כתובות טובות לשבוע הבא
- https://www.jerusalem.muni.il/he/city/council/committees/Committee?id=30a0e81f-30e4-ee11-904c-000d3ab1f351
- https://www.gov.il/he/collectors/policies?officeId=c1d2ec1c-7f78-4d96-a739-1ed90f9e2b4b&limit=10&Type=2c0063a0-b17b-4979-83e9-ace8454572ec
- https://magdilim.co.il/
- https://www.news1.co.il/Home/L02-S-003-00.html
- https://michraziya.co.il/search?q=%D7%90%D7%92%D7%99%D7%A8%D7%94
- https://michraziya.co.il/browse/by/%D7%A8%D7%9B%D7%91%D7%AA%20%D7%99%D7%A9%D7%A8%D7%90%D7%9C

## מה לא הספקתי
- רשות התחרות (צריך למצוא את דף הודעות המיזוג העדכני), רשות ההשקעות, היתרי פליטה.
- סכומים לזוכה במכרז הניקיון בירושלים (יש רק מסגרת כוללת).
- בדיקת "נסחרת?" עבור: א.י. אמריקה ישראל, YBOX, ריינדיר אנרגיה.
