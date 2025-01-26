![OSE Logo](OSE.Logo.Black.png)

---

# מאורגן מחדש. פורסם מחדש. משוחזר מחדש!

### מהו OSE SRD משוחזר מחדש?

זוהי התאמה "אמריקאית" של ה-Old-School Essentials (OSE) SRD שעוצבה מחדש ב-Markdown (.MD) לייצוא קל לפורמטים אחרים של פרסום. אנא דווחו על כל בעיה או אי-התאמה בחומר עצמו; ראו דיונים ונושאים למטה.

החומר הכלול כאן שוחזר מחדש שורה אחר שורה לפורמט Markdown לשימוש בפרויקטים שלכם של OSE. אני המרה בקפידה את ה-[OSE SRD](https://oldschoolessentials.necroticgnome.com/srd/index.php/Main_Page) המקורי ל-Markdown, כולל כל התיקונים הנוכחיים. בנוסף, המרה את כל האיות הבריטי לאיות אמריקאי. לדוגמה, armour ל-armor, colour ל-color, וכו'. כמו כן, לקחתי את החירות לבדוק את הדקדוק של כל החומר ולנסח מחדש כמה משפטים לשם בהירות. למידע נוסף, בקרו ב-[SRD Wiki](https://srd.wiki).

**מסמך ההתייחסות למערכות (SRD)** מכיל הנחיות לפרסום תוכן תחת רישיון המשחק הפתוח [OGL](https://oldschoolessentials.necroticgnome.com/srd/index.php/Open_Game_License) או [רישיון Creative Commons Attribution 4.0 International License](https://creativecommons.org/licenses/by/4.0/legalcode) (“CC-BY-4.0”).

<details>
 <summary>למה פורמט Markdown?</summary>

Markdown היא שפת סימון קלה עם תחביר עיצוב טקסט פשוט שנוצרה על ידי [John Gruber](https://daringfireball.net). מטבעה, כקובץ טקסט פשוט, היא נועדה להוסיף עמידות לעתיד לכל סט של מסמכים תוך שמירה על אפשרויות עיצוב טקסט וטבלה בסיסיות. בנוסף, Markdown ניתן לייצוא ל-HTML ולפורמטים רבים אחרים באמצעות מספר עורכי Markdown שונים. Markdown משמשת לעיתים קרובות לעיצוב קבצי readme, לכתיבת ספרים, בלוגים והודעות, או פשוט ליצירת טקסט עשיר באמצעות טקסט פשוט בעורך Markdown.

</details>

<details>
 <summary>אפשרויות ייצוא</summary>

אני ממליץ להשתמש ביישומי Markdown הבאים לעריכת החומר:

* [Typora](https://typora.io): $15 (תשלום חד פעמי)
* [Visual Studio Code](https://code.visualstudio.com/Download): חינם!

לייצוא Markdown לפורמטים שונים של פרסום, אני ממליץ להשתמש ב-Typora (המוזכר לעיל), שכן יש לו אפשרויות ייצוא רבות וטובות שיספקו את רוב המשתמשים. רוב עורכי Markdown הטובים יציעו ייצוא בסיסי. עם זאת, אם אתם רוצים יותר אפשרויות, [PanWriter](https://panwriter.com) הוא הפתרון הטוב ביותר. עם זאת, כדי ש-PanWriter יפעל כראוי, יש להתקין גם את היישומים הבאים כדי למקסם את אפשרויות הייצוא שלכם:

* [הורד PanDoc](https://github.com/jgm/pandoc/releases/download/2.19.2/pandoc-2.19.2-macOS.pkg)

לחילופין, תוכלו להתקין pandoc באמצעות Homebrew:

`brew install pandoc`

Homebrew יכול גם להתקין תוכנה אחרת שמשתלבת עם Pandoc. לדוגמה, כדי להתקין librsvg (ה-rsvg-convert שלו מכסה פורמטים ללא תמיכה ב-SVG), Python (לשימוש במסנני Pandoc), ו-BasicTeX (לסידור PDF עם LaTeX):

`brew install librsvg python homebrew/cask/basictex`

הערה: בגרסאות לא נתמכות של macOS (יותר משלוש גרסאות ישנות), Homebrew מתקין מהמקור, מה שלוקח זמן נוסף ומקום בדיסק עבור המהדר ghc וספריות Haskell התלויות.

יש קובץ zip המכיל את הבינאריים ודפי המדריך, למי שמעדיף לא להשתמש במתקין. פשוט חלצו את הקובץ והעבירו את הבינאריים ודפי המדריך לכל ספרייה שתרצו.

כברירת מחדל, Pandoc יוצר PDF באמצעות LaTeX. מכיוון שהתקנה מלאה של MacTeX משתמשת בארבעה ג'יגה-בייט של מקום בדיסק, אנו ממליצים על BasicTeX או TinyTeX ושימוש בכלי tlmgr להתקנת חבילות נוספות לפי הצורך. אם אתם מקבלים אזהרות שגיאה של גופנים שלא נמצאו:

`tlmgr install collection-fontsrecommended`

</details>

<details>
 <summary>ידידותי ל-Obsidian</summary>

ההתאמה הזו של ה-OSE SRD מיועדת במיוחד ליישומי PKM כמו Obsidian. [Obsidian.md](https://obsidian.md) היא בסיס ידע חזק על גבי תיקיית קבצי טקסט פשוטים Markdown מקומית. ההגדרה הזו נשמעת פשוטה; עם זאת, Obsidian היא הרבה, הרבה יותר. בקרו בערוץ היוטיוב של [Josh Plunkett](https://www.youtube.com/c/JoshPlunkett/videos) כדי ללמוד עוד על שימוש ב-Obsidian לניהול קמפיין משחק התפקידים שלכם.

</details>

<details>
 <summary>דיונים ונושאים</summary>

אל תהססו לבקר בפורום ה-[דיון](https://github.com/OldManUmby/OSE.SRD.Wiki/discussions) שלנו כדי לבחון רעיונות לפרסום בנוגע ל-D&D SRD. אנא **דווחו** על כל [נושא](https://github.com/OldManUmby/OSE.SRD.Wiki/issues) שתמצאו דרך Github. כחלופה, תוכלו **לשכפל מחדש ולהשתמש מחדש** בפרויקט זה דרך [בקשת משיכה](https://github.com/OldManUmby/OSE.SRD.Wiki/pulls) ב-GitHub.

</details>

<details>
 <summary>קבלו הורדות</summary>

* הורידו את ה-[גרסה האחרונה](https://github.com/OldManUmby/OSE.SRD.Wiki/releases).
* הורידו את ה-[חוקים בסיסיים](https://necroticgnome.com/products/old-school-essentials-basic-rules) הרשמיים של OSE.
* הורידו את ה-[תיקונים](https://docs.google.com/document/d/1dzQnig4CNET8-1yLJgOfYdssc70oUp5rGfGUZuBZBQE/edit#heading=h.8u1si328qbpn) הרשמיים של OSE.
* הורידו את ה-[גיליונות דמויות](https://necroticgnome.com/collections/free-downloads) הרשמיים של OSE.

</details>

---

**הצהרת אחריות:** Old-School Essentials הוא סימן מסחרי של Necrotic Gnome. הסימן המסחרי ולוגו Old-School Essentials משמשים באישור של Necrotic Gnome, תחת רישיון. למידע נוסף על Old-School Essentials או על קניין רוחני אחר, אנא בקרו באתר האינטרנט שלהם ב-[www.necroticgnome.com](http://www.necroticgnome.com).

אתר אינטרנט, המרת Markdown, ופורמטים מורחבים על ידי [Old Man Umby](http://www.oldmanumby.com).