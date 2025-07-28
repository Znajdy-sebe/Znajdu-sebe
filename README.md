# Znajdu-sebe
<!DOCTYPE html>
<html lang="uk">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Онлайн-курс «Знайди себе»</title>
  <style>
    :root {
      --accent: #e78fb3;
      --mint: #e0f7f1;
      --light: #fce4ec;
      --text: #333;
    }

    * {
      box-sizing: border-box;
    }

    body {
      font-family: 'Segoe UI', sans-serif;
      margin: 0;
      background: #fff;
      color: var(--text);
      line-height: 1.6;
    }

    header, section, footer {
      padding: 60px 20px;
      max-width: 960px;
      margin: auto;
    }

    h1, h2 {
      color: var(--accent);
      margin-top: 0;
    }

    .hero {
      background: var(--mint);
      text-align: center;
      padding-top: 80px;
      padding-bottom: 80px;
    }

    .hero h1 {
      font-size: 2.5em;
    }

    .hero p {
      font-size: 1.2em;
      margin-bottom: 20px;
    }

    .btn {
      background: var(--accent);
      color: white;
      padding: 14px 28px;
      border: none;
      border-radius: 30px;
      font-size: 1em;
      cursor: pointer;
      text-decoration: none;
      display: inline-block;
      transition: 0.3s ease;
    }

    .btn:hover {
      background: #d46c98;
    }

    .benefits ul {
      list-style: none;
      padding: 0;
    }

    .benefits li {
      background: var(--light);
      padding: 10px 20px;
      margin: 10px 0;
      border-radius: 12px;
    }

    .author {
      display: flex;
      gap: 20px;
      align-items: center;
      flex-wrap: wrap;
    }

    .author img {
      width: 100px;
      border-radius: 50%;
    }

    .testimonial {
      background: #f9f9f9;
      padding: 20px;
      margin: 15px 0;
      border-left: 5px solid var(--accent);
      border-radius: 8px;
    }

    footer {
      background: var(--mint);
      text-align: center;
      padding: 40px 20px;
      font-size: 0.9em;
    }

    @media (max-width: 768px) {
      .hero h1 {
        font-size: 2em;
      }
      .hero p {
        font-size: 1em;
      }
      .btn {
        width: 100%;
        font-size: 1.1em;
        padding: 14px;
      }
      .author {
        flex-direction: column;
        text-align: center;
      }
      .author img {
        margin-bottom: 15px;
      }
    }

    @media (max-width: 480px) {
      header, section, footer {
        padding: 40px 15px;
      }

      .hero h1 {
        font-size: 1.8em;
      }

      .hero p {
        font-size: 0.95em;
      }
    }
  </style>
</head>
<body>

  <header class="hero">
    <h1>Знайди себе</h1>
    <p>7-денний онлайн-курс самопізнання. Прості практики — великі зміни.</p>
    <a href="#cta" class="btn">Почати курс</a>
  </header>

  <section class="benefits">
    <h2>Що ти отримаєш?</h2>
    <ul>
      <li>🎯 Чіткість у цілях</li>
      <li>🧘 Впевненість у собі</li>
      <li>✍️ Ефективні практики саморефлексії</li>
      <li>💬 Підтримка на кожному кроці</li>
    </ul>
  </section>

  <section class="about">
    <h2>Хто створив цей курс?</h2>
    <div class="author">
      <img src="https://via.placeholder.com/100" alt="Автор курсу" />
      <div>
        <p><strong>Mari Kozak</strong> — психолог і дизайнер жіночих мотиваційних продуктів. Допомагаю жінкам знайти себе і не боятись почати з нуля.</p>
      </div>
    </div>
  </section>

  <section class="testimonials">
    <h2>Відгуки учасниць</h2>
    <div class="testimonial">
      «Цей курс допоміг мені переосмислити, що я хочу від життя. Простий, щирий, дуже теплий.» — Олена К.
    </div>
    <div class="testimonial">
      «Після вправ я вперше за довгий час зрозуміла свої бажання. Дякую!» — Катерина М.
    </div>
  </section>

  <section id="cta" class="cta">
    <h2>Готова знайти себе?</h2>
    <p>Приєднуйся зараз і розпочни зміни вже сьогодні.</p>
    <a href="#" class="btn">Зареєструватись</a>
  </section>

  <footer>
    © 2025 Mari Kozak. Усі права захищено.
  </footer>

</body>
</html>
