# Simple Cursor — דף ההורדה

דף ההורדה הציבורי של Simple Cursor, תוסף ל-AutoCAD ול-Revit. האתר מוגש ב-GitHub Pages מהתיקייה הראשית של המאגר.
קוד המקור של התוסף נמצא במאגר נפרד ופרטי.

- `index.html`: הדף כולו, בלי שלב בנייה.
- קובץ ההתקנה לא נשמר במאגר. הוא מצורף ל-Release, וכפתורי ההורדה מצביעים תמיד על הגרסה האחרונה:
  `releases/latest/download/SimpleCursor-Setup.exe`

## פרסום גרסה

בונים את קובץ ההתקנה במאגר המקור (`install\build-installer.ps1`) ומריצים משם:

```bash
gh release create v1.0.1 dist\SimpleCursor-Setup.exe --repo fleet-360/simplecursor-download --title "Simple Cursor 1.0.1"
```

שם הקובץ חייב להישאר `SimpleCursor-Setup.exe`. אחרי הפרסום מעדכנים את מספר הגרסה שמופיע ב-`index.html`.
