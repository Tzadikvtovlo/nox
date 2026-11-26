<div dir="rtl">

# nox

כלי Python להמרת קובץ תרגום בפורמט JSON (`multiplayer_ar.json`) לקובץ תרגום של **Qt Linguist** בפורמט XML (`multiplayer.ts`) המוגדר לשפה העברית (`language="he_IL"`).

## קבצים במאגר
- **`nox.py`** — סקריפט Python הקורא את רשימת ההודעות (`context`, `source`, `translation`) מ-`multiplayer_ar.json` ומייצר את הקובץ `multiplayer.ts`.
- **`multiplayer_ar.json`** / **`nox_ar.json`** — קובצי הנתונים והמחרוזות לתרגום.

## הפעלה
```bash
python nox.py
```

## רישיון
מפורט בקובץ `License.txt`.

</div>
