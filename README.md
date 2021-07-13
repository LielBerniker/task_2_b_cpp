לוח מודעות דו ממדי
בלוח המודעות השכונתי, אנשים מדביקים מודעות אחת על השניה, והמודעות מתערבבות (כמו בסרטון הזה). במטלה זו נכתוב מחלקה לניהול לוח המודעות. המחלקה צריכה לתמוך בפונקציות הבאות:

post - מקבלת מיקום (שורה וטור), כיוון (אופקי או אנכי), ומחרוזת המייצגת מודעה, ומדביקה את המחרוזת על הלוח במקום המתאים.
read - מקבלת מיקום (שורה וטור), כיוון (אופקי או אנכי), ומספר תוים, קוראת את מה שכתוב על הלוח במיקום הנתון ובאורך הנתון, ומחזירה מחרוזת. האות הנמצאת בכל משבצת על הלוח היא האות האחרונה שהודבקה שם.
show - מציגה את לוח-המודעות הנוכחי בצורה נוחה לקריאה, בפורמט כלשהו לפי בחירתכם.
דוגמאות לפעולת המחלקה ניתן למצוא ב-Demo.cpp.

פרטים:

מספרי השורות והטורים ומספר התוים הם מספרים שלמים אי-שליליים (unsigned int).
השורה העליונה היא 0 והטור השמאלי הוא 0.
בכל משבצת שלא הודבק עליה כלום, יש קו תחתי
גודל הלוח אינו מוגבל מראש, אבל אפשר להניח שכל המודעות יהיו מרוכזות באותו איזור -- המרחקים בין מודעה למודעה לא יהיו גדולים מאד.

