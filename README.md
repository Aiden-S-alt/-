<!DOCTYPE html>
<html lang="he" dir="rtl">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1" />
<title>חדשות - העבדות חוזרת להיות חוקית</title>
<style>
  /* Reset & basics */
  * {
    box-sizing: border-box;
  }
  body {
    margin: 0;
    font-family: Arial, sans-serif;
    background: #fff;
    color: #222;
  }

  /* Top red header bar */
  header {
    background: #bb1919;
    color: white;
    padding: 10px 20px;
    font-weight: bold;
    font-size: 1.2rem;
    display: flex;
    justify-content: space-between;
    align-items: center;
    /* מחזירים לכיוון RTL כי התפריט בעברית */
    direction: rtl;
  }
  header .logo {
    font-size: 1.4rem;
    font-weight: 900;
  }
  header nav a {
    color: white;
    text-decoration: none;
    margin-left: 20px;
    font-weight: normal;
  }
  header nav a:hover {
    text-decoration: underline;
  }

  /* Main container */
  .container {
    max-width: 1080px;
    margin: 30px auto;
    padding: 0 15px;
    direction: rtl;
  }

  /* Main featured article */
  .featured {
    display: flex;
    flex-wrap: wrap;
    gap: 20px;
    margin-bottom: 40px;
  }
  .featured-image {
    flex: 1 1 45%;
    min-width: 280px;
  }
  .featured-image img {
    width: 100%;
    height: auto;
    border-radius: 4px;
  }
  .featured-text {
    flex: 1 1 50%;
    display: flex;
    flex-direction: column;
    justify-content: center;
  }
  .featured-text h1 {
    font-size: 2.8rem;
    margin: 0 0 10px 0;
    color: #bb1919;
    font-weight: 900;
  }
  .featured-text p {
    font-size: 1.2rem;
    line-height: 1.5;
    color: #444;
  }

  /* Smaller articles grid */
  .articles-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
    gap: 25px;
  }
  .article {
    border-bottom: 1px solid #ddd;
    padding-bottom: 15px;
    transition: background-color 0.2s ease;
  }
  .article:hover {
    background-color: #f7f7f7;
  }
  .article h2 {
    font-size: 1.3rem;
    margin: 0 0 10px 0; /* הוספתי ריווח מתחת לכותרות */
    font-weight: 700;
    color: #bb1919; /* צבע אדום לכותרות המשנה */
  }
  .article p {
    font-size: 0.95rem;
    color: #666;
    margin: 0;
  }

</style>
</head>
<body>

<header>
  <div class="logo">חדשות</div>
  <nav>
    <a href="#">בית</a>
    <a href="#">עולם</a>
    <a href="#">עסקים</a>
    <a href="#">תרבות</a>
    <a href="#">ספורט</a>
  </nav>
</header>

<div class="container">

  <!-- Featured Big Article -->
  <section class="featured">
    <div class="featured-image">
      <img src="https://images.unsplash.com/photo-1506744038136-46273834b3fb?auto=format&fit=crop&w=600&q=80" alt="תמונה הממחישה את נושא העבדות" />
    </div>
    <div class="featured-text">
      <h1>העבדות חוזרת להיות חוקית</h1>
      <p>הנושא שהכי מעורר סערה היום - האם העבדות תחזור להיות חוקית? העולם מחולק בדעותיו ונמשך דיון סוער.</p>
    </div>
  </section>

  <!-- Smaller articles -->
  <section class="articles-grid">
    <article class="article">
      <h2>העולם בסערה אחרי שהג'ינג'ים ומנעיגם ברנר החריזו על מלחמה</h2>
      <p>התגובות לא איחרו להגיע אחרי ההכרזה הדרמטית מהצדדים המעורבים.</p>
    </article>
    <article class="article">
      <h2>מסעדת כלבים נפתחה עם השף האיכרי ג'ימי</h2>
      <p>אוכל חדש ומיוחד בשוק — מסעדת כלבים עם טעם שלא הכרתם.</p>
    </article>
    <article class="article">
      <h2>בשר הר ציון - הבשר הכי טעים בעולם? אנחנו כרגע ברעיון עם רבית הגמלה של גילעד</h2>
      <p>ביקורת על בשר הר ציון, האם הוא אכן הטעים ביותר? המומחים אומרים שכן.</p>
    </article>
    <article class="article">
      <h2>חנות צברים - רק היום הנחה לג'ינג'ים וצברים</h2>
      <p>מבצעים מיוחדים לצברים בלבד, רק היום בחנות המרכזית.</p>
    </article>
  </section>

</div>

</body>
</html>
