<!DOCTYPE html>
<html lang="he" dir="rtl">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>תכנית פסגות - תכנית מצויינות טכנולוגית | Psagot</title>
  <meta name="description" content="מידע לא-רשמי על פסגות — תוכנית מצוינות טכנולוגית תחת משרד הביטחון, מפא״ת חטיבת תלפיות–פסגות. תהליך מיון תובעני, הכשרה מעמיקה ותרומה למחקר ופיתוח הביטחוני." />
  <meta property="og:title" content="פסגות — תוכנית מצוינות טכנולוגית" />
  <meta property="og:description" content="תחת משרד הביטחון, מפא״ת חטיבת תלפיות–פסגות. קבלה תחרותית במיוחד ותהליך מיון רב-שלבי." />
  <meta property="og:type" content="website" />
  <meta property="og:locale" content="he_IL" />
  <style>
    :root{
      --bg:#0f172a;          /* slate-900 */
      --card:#0b1226;        /* deep card */
      --muted:#94a3b8;       /* slate-400 */
      --text:#e2e8f0;        /* slate-200 */
      --accent:#7c3aed;      /* violet-600 */
      --accent-2:#a78bfa;    /* violet-300 */
      --ok:#10b981;          /* emerald-500 */
      --warn:#f59e0b;        /* amber-500 */
      --danger:#ef4444;      /* red-500 */
    }
    *{box-sizing:border-box}
    body{
      margin:0;
      font-family: system-ui, -apple-system, Segoe UI, Roboto, Helvetica, Arial, "Noto Sans", "Apple Color Emoji","Segoe UI Emoji";
      background: radial-gradient(1200px 800px at 80% -10%, rgba(124,58,237,.25), transparent 70%), var(--bg);
      color:var(--text);
      line-height:1.65;
    }
    a{color:var(--accent-2); text-decoration:none}
    a:hover{text-decoration:underline}
    header{
      position:sticky; top:0; backdrop-filter:saturate(180%) blur(8px);
      background:linear-gradient(to left, rgba(15,23,42,.8), rgba(15,23,42,.6));
      border-bottom:1px solid rgba(148,163,184,.15);
      z-index:50;
    }
    .container{max-width:1050px;margin:0 auto;padding:0 18px}
    .nav{
      display:flex; align-items:center; justify-content:space-between;
      height:64px;
    }
    .brand{display:flex; gap:10px; align-items:center}
    .logo{
      width:36px;height:36px;border-radius:10px;
      background:linear-gradient(135deg, var(--accent), #4c1d95);
      display:inline-grid; place-items:center; font-weight:700;
      box-shadow:0 6px 20px rgba(124,58,237,.35);
    }
    .logo span{font-size:18px}
    .nav a{margin-inline:10px; color:var(--text); opacity:.9}
    .btn{
      display:inline-block; padding:10px 16px; border-radius:12px;
      background:var(--accent); color:white; font-weight:600; border:none;
      box-shadow:0 8px 22px rgba(124,58,237,.35); cursor:pointer;
    }
    .btn:hover{filter:brightness(1.08)}
    .hero{ padding:72px 0 36px; }
    .hero h1{ font-size:clamp(28px, 5vw, 46px); line-height:1.15; margin:0 0 10px; letter-spacing:.3px; }
    .hero p{ font-size:clamp(16px, 2.2vw, 20px); color:var(--muted); margin:0 0 18px }
    .hero .badges{display:flex; gap:10px; flex-wrap:wrap; margin-top:12px}
    .badge{ border:1px solid rgba(167,139,250,.35); color:var(--accent-2); padding:6px 10px; border-radius:999px; font-size:13px; }
    .grid{ display:grid; gap:18px; grid-template-columns: repeat(auto-fit, minmax(260px,1fr)); }
    section{padding:28px 0}
    .card{ background:linear-gradient(180deg, rgba(167,139,250,.06), rgba(124,58,237,.03) 40%, rgba(2,6,23,.6)); border:1px solid rgba(148,163,184,.14); border-radius:18px; padding:18px 18px 16px; }
    h2{font-size:clamp(22px, 3.2vw, 28px); margin:0 0 10px}
    h3{font-size:20px; margin:8px 0}
    ul{margin:0; padding-inline-start:18px}
    .pill{ display:inline-block; padding:6px 10px; border-radius:999px; background:rgba(16,185,129,.12); color:#c8ffe4; font-size:13px; border:1px solid rgba(16,185,129,.25); }
    footer{ border-top:1px solid rgba(148,163,184,.15); color:var(--muted); padding:24px 0 48px; margin-top:22px; }
    .cta{ text-align:center; padding:26px; border-radius:18px; margin-top:10px; background:linear-gradient(180deg, rgba(16,185,129,.08), rgba(16,185,129,.05)); border:1px solid rgba(16,185,129,.25); }
    .faq dt{font-weight:700; margin-top:10px}
    .faq dd{margin:0 0 8px; color:var(--muted)}
    .tiny{font-size:12px; color:var(--muted)}
    .divider{height:1px;background:linear-gradient(to left, rgba(124,58,237,.2), rgba(124,58,237,.05)); margin:18px 0}
  </style>
</head>
<body>
  <header>
    <div class="container nav">
      <div class="brand">
        <div class="logo" aria-hidden="true"><span>פ</span></div>
        <strong>פסגות | Psagot</strong>
      </div>
      <nav>
        <a href="#about">על התוכנית</a>
        <a href="#selection">מיונים</a>
        <a href="#tracks">תחומי עשייה</a>
        <a href="#faq">שאלות נפוצות</a>
        <a href="#apply" class="btn">איך ניגשים</a>
      </nav>
    </div>
  </header>

  <main class="container">
    <section class="hero">
      <h1>פסגות — תוכנית מצוינות טכנולוגית</h1>
      <p>
        פסגות היא תוכנית עילית להכשרת מובילי מחקר, טכנולוגיה וחדשנות ביטחונית. התוכנית פועלת
        <b>תחת משרד הביטחון — מפא״ת, חטיבת תלפיות–פסגות</b> בשיתוף גורמי צה״ל ואקדמיה, ומיועדת למועמדים בעלי
        סקרנות מדעית, יכולות אנליטיות גבוהות ואחריות לאומית.
      </p>
      <div class="badges">
        <span class="badge">תהליך מיון רב‑שלבי ותובעני</span>
        <span class="badge">מסלול מצוינות מחקרי‑יישומי</span>
        <span class="badge">השפעה ישירה על ביטחון ישראל</span>
      </div>
    </section>

    <section id="about" class="grid">
      <article class="card">
        <h2>מה מייחד את פסגות?</h2>
        <p>
          פסגות מטפחת דור מובילים טכנולוגיים המסוגלים לגשר בין מחקר יסודי לבין יישום מבצעי.
          ההכשרה משלבת למידה מעשית, עבודה צוותית וחניכה צמודה ביחידות מחקר ופיתוח. בוגרי ובוגרות התוכנית
          משתלבים בפרויקטים מסווגים בתחומים חיוניים וממשיכים להוביל גם בתעשייה ובאקדמיה.
        </p>
        <div class="divider"></div>
        <p><span class="pill">חשוב לדעת</span> התוכנית אינה מוגדרת כ״עתודה אקדמית״. היא מופעלת תחת משרד הביטחון — מפא״ת, חטיבת תלפיות–פסגות.</p>
      </article>

      <article class="card">
        <h2>למי זה מתאים?</h2>
        <ul>
          <li>יכולות אנליטיות גבוהות לצד כישורים חברתיים מעולים.</li>
          <li>מצטיינים/ות במדעים והנדסה, בעלי חשיבה עצמאית ויצירתית.</li>
          <li>מסוגלות/ות לעבודה אינטנסיבית לאורך זמן ובהובלת צוותים.</li>
          <li>הרגלי למידה גבוהים, משמעת עצמית ויכולת עמידה בלחצים.</li>
          <li>מוטיבציה להשפעה מערכתית ובינתחומית.</li>
        </ul>
        <p class="tiny">* התאמה רפואית וביטחונית נדרשת על פי נהלי משרד הביטחון וצה״ל.</p>
      </article>

      <article class="card">
        <h2>עד כמה קשה להתקבל?</h2>
        <p>
          הקבלה לפסגות <b>תחרותית במיוחד</b>. תהליך המיון כולל מספר שלבים מצטברים שמטרתם להבטיח התאמה יוצאת דופן —
          ידע מדעי, יכולת פתרון בעיות, עבודת צוות, עמידות, אחריות ויכולות מנהיגות.
        </p>
        <h3>שלבי המיון</h3>
        <ul>
          <li>מבחני חשיבה מתקדמים במתמטיקה, פיזיקה ואלגוריתמיקה.</li>
          <li>משימות אישיות וצוותיות תחת אילוצי זמן ומשאבים.</li>
          <li>ריאיונות עומק עם מומחים/ות ומנהלים/ות מקצועיים.</li>
          <li>בדיקות התאמה ביטחונית ומבחני אמינות.</li>
          <li>ועדת קבלה בכירה — הערכה הוליסטית של המסוגלות והפוטנציאל.</li>
        </ul>
        <p class="tiny">* התהליך עשוי להשתנות מעת לעת; המידע כאן כללי ולא‑רשמי.</p>
      </article>
    </section>

    <section id="tracks" class="grid">
      <article class="card">
        <h2>תחומי עשייה</h2>
        <ul>
          <li>אלגוריתמיקה, למידת מכונה ועיבוד אות/תמונה.</li>
          <li>אלקטרו‑אופטיקה, חיישנים ומערכות חלל.</li>
          <li>תקשורת מתקדמת, ניווט ומערכות אוטונומיות.</li>
          <li>סייבר הגנתי והבטחת מידע.</li>
          <li>מערכות משולבות חומרה‑תוכנה ו‑R&amp;D בין‑תחומי.</li>
        </ul>
      </article>

      <article class="card">
        <h2>אופי ההכשרה</h2>
        <p>
          המסלול בפסגות כולל לימודי <b>תואר בהנדסת חשמל</b> ותואר נוסף ב<b>פיזיקה</b>, בנוסף להכשרות, סדרות, "פסגותיקס" וימי עיון שמועברים על‑ידי בוגרי המסלול המשרתים בכל רחבי צה"ל ומשרד הביטחון.
        </p>
        <ul>
          <li>לימוד מואץ של תשתיות מדעיות והנדסיות חיוניות.</li>
          <li>סדנאות פתרון בעיות וחשיבה מערכתית.</li>
          <li>חניכה על ידי חוקרים/מפתחים בכירים במפא״ת ובגופים שותפים.</li>
          <li>פרויקטים מעשיים עם תוצרים מבצעיים.</li>
        </ul>
      </article>

      <article class="card">
        <h2>הטבות ותמיכה לחניכים</h2>
        <ul>
          <li>אופציה למגורים במעונות האוניברסיטה.</li>
          <li>מענקי עידוד ממפא״ת וגם מעתודה אקדמית, בסך <b>עשרות אלפי שקלים בשנה</b> <span class="tiny">(בכפוף להנחיות וגובה עדכני של הגופים המממנים)</span>.</li>
        </ul>
      </article>

      <article class="card">
        <h2>שיבוצים</h2>
        <p>
          שיבוצי בוגרות ובוגרי פסגות מצויים <b>בליבת המחקר והפיתוח של מערכת הביטחון</b> —
          החל מיחידות הטכנולוגיה והמודיעין המתקדמות של צה״ל <span class="tiny">(לרבות יחידות כמו 8200)</span>,
          דרך מרכזי מו״פ בין‑זרועיים, ועד לארגוני הביטחון הלאומי ובהם <b>השב״כ</b> ו<b>המוסד</b>.
          מרבית התפקידים הם בתפקידי R&D, אלגוריתמיקה והנדסה יישומית בעלי השפעה ישירה על המערכה המבצעית.
        </p>
      </article>

      <article class="card" id="apply">
        <h2>איך ניגשים?</h2>
        <p>
          פרטי המיונים מתפרסמים על ידי הגורמים המוסמכים של משרד הביטחון וצה״ל.
          ההרשמה ויצירת הקשר מתבצעות בהתאם להנחיות הרשמיות. מומלץ להיערך מראש בלימוד עצמי, חיזוק מתמטי‑פיזיקלי,
          עבודה על פרויקטים טכנולוגיים והעמקה בתחומי עניין מחקריים.
        </p>
        <div class="cta">
          <h3>טיפ למועמדים/ות</h3>
          <p>התמקדו בפתרון בעיות קשות, בניית סקרנות אמיתית ויכולת הסבר ברורה. הראו למידה עצמאית ועומק — זה בולט.</p>
          <a class="btn" href="#selection">לקריאה על המיונים</a>
        </div>
      </article>
    </section>

    <section id="selection" class="card">
      <h2>מבנה מיון</h2>
      <div class="grid">
        <div>
          <h3>שלב 1 — סינון ראשוני</h3>
          <ul>
            <li>בדיקת נתונים לימודיים/ממליצים ופתרון משימות כתובות.</li>
            <li>מבחני חשיבה ואנליזה; נדרשת שליטה חזקה בבסיס מדעי.</li>
          </ul>
        </div>
        <div>
          <h3>שלב 2 — הערכה מעשית</h3>
          <ul>
            <li>סדנאות צוות, פתרון בעיות פתוחות והצגה מול פאנל.</li>
            <li>בדיקות עמידות, ניהול זמן ותקשורת בין‑אישית.</li>
          </ul>
        </div>
        <div>
          <h3>שלב 3 — ריאיונות ווועדה</h3>
          <ul>
            <li>דיון מקצועי מעמיק, אינטגריטי ומוטיבציה לשירות משמעותי.</li>
            <li>ועדת קבלה מסכמת — הקבלה מוגבלת ומדודה.</li>
          </ul>
        </div>
      </div>
      <p class="tiny">המידע כאן תיאורי וכללי בלבד ואינו מחליף פרסום רשמי.</p>
    </section>

    <section id="faq" class="card">
      <h2>שאלות נפוצות</h2>
      <dl class="faq">
        <dt>האם פסגות היא עתודה אקדמית?</dt>
        <dd>לא. פסגות פועלת תחת משרד הביטחון — מפא״ת, חטיבת תלפיות–פסגות. הדגש הוא הכשרה מחקרית‑יישומית במסגרת ביטחונית.</dd>

        <dt>האם יש התחייבות לשירות?</dt>
        <dd>כן. מדובר בתוכנית ביטחונית תובענית עם מחויבות לשירות משמעותי, בהתאם לנהלים.</dd>

        <dt>מה עוזר להתקבל?</dt>
        <dd>מצוינות מתמשכת במדעים, פרויקטים עצמאיים, חשיבה מערכתית, כישורי תקשורת חזקים ויכולת הובלה בצוות.</dd>
      </dl>
    </section>

    <footer>
      <p><strong>ויתור</strong>: אתר מידע לא‑רשמי שנועד להנגשת מידע כללי על פסגות. אין באתר זה פרטים מסווגים, והוא אינו מייצג גורם רשמי כלשהו.</p>
      <p class="tiny">© Psagot — Information site (unofficial). Built for demonstration and personal use.</p>
    </footer>
  </main>
</body>
</html>
