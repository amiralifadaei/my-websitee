<!DOCTYPE html>
<html lang="fa" dir="rtl">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>استایلینو 🛍️</title>

  <style>
    * {
      box-sizing: border-box;
    }

    body {
      margin: 0;
      font-family: Tahoma, Arial, sans-serif;
      background: #f5f5f5;
      color: #222;
    }

    header {
      background: linear-gradient(135deg, #111827, #6366f1);
      color: white;
      text-align: center;
      padding: 55px 20px;
    }

    header h1 {
      font-size: 40px;
      margin: 0 0 10px;
    }

    header p {
      font-size: 18px;
      margin: 0;
    }

    .products {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 25px;
      padding: 40px 20px;
    }

    .card {
      background: white;
      width: 280px;
      border-radius: 20px;
      overflow: hidden;
      box-shadow: 0 6px 20px rgba(0,0,0,0.12);
      text-align: center;
      padding-bottom: 20px;
      transition: 0.3s;
    }

    .card:hover {
      transform: translateY(-8px);
    }

    .card img {
      width: 100%;
      height: 240px;
      object-fit: cover;
    }

    .card h2 {
      margin: 15px 10px 8px;
    }

    .price {
      color: #4f46e5;
      font-size: 20px;
      font-weight: bold;
    }

    .card button {
      margin-top: 10px;
      padding: 12px 30px;
      border: none;
      border-radius: 25px;
      background: #4f46e5;
      color: white;
      font-size: 16px;
      cursor: pointer;
    }

    .card button:hover {
      background: #3730a3;
    }

    footer {
      text-align: center;
      padding: 25px;
      background: #111827;
      color: white;
    }
  </style>
</head>

<body>

  <header>
    <h1>استایلینو 🛍️</h1>
    <p>لباس‌های شیک با قیمت مناسب</p>
  </header>

  <section class="products">

    <div class="card">
      <img src="https://images.unsplash.com/photo-1521572163474-6864f9cf17ab" alt="تی شرت">
      <h2>تی‌شرت اسپرت</h2>
      <p class="price">۵۰۰,۰۰۰ تومان</p>
      <button onclick="alert('برای خرید با ما تماس بگیرید 📞')">
        خرید محصول
      </button>
    </div>

    <div class="card">
      <img src="https://images.unsplash.com/photo-1556821840-3a63f95609a7" alt="هودی">
      <h2>هودی مشکی</h2>
      <p class="price">۹۰۰,۰۰۰ تومان</p>
      <button onclick="alert('برای خرید با ما تماس بگیرید 📞')">
        خرید محصول
      </button>
    </div>

    <div class="card">
      <img src="https://images.unsplash.com/photo-1542272604-787c3835535d" alt="شلوار">
      <h2>شلوار جین</h2>
      <p class="price">۷۵۰,۰۰۰ تومان</p>
      <button onclick="alert('برای خرید با ما تماس بگیرید 📞')">
        خرید محصول
      </button>
    </div>

  </section>

  <footer>
    ساخته شده با ❤️
  </footer>

</body>
</html>
