<!DOCTYPE html>
<html lang="ar">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Joo Smile Store</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      text-align: center;
      background-color: #f0f8ff;
      margin: 0;
      padding: 0;
      direction: rtl;
    }
    header {
      background-color: #00aaff;
      color: black;
      padding: 20px 0;
    }
    img {
      max-width: 200px;
      margin: 10px;
    }
    button {
      background-color: #00aaff;
      color: black;
      padding: 10px 20px;
      border: none;
      border-radius: 10px;
      cursor: pointer;
      margin: 10px;
    }
    footer {
      margin-top: 30px;
      padding: 20px;
      background-color: #eee;
    }
    .social a {
      margin: 0 10px;
      text-decoration: none;
      color: #00aaff;
    }
    form {
      margin-top: 30px;
    }
    input, textarea {
      padding: 10px;
      width: 80%;
      margin: 10px 0;
    }
  </style>
</head>
<body>
  <header>
    <h1>Joo Smile Store</h1>
    <p>كل أدوات الأسنان اللي تحتاجها - للطلبة والدكاترة</p>
  </header>

  <section>
    <h2>بعض المنتجات</h2>
    <img src="https://via.placeholder.com/200x150?text=Dental+Tool+1" alt="منتج 1" />
    <img src="https://via.placeholder.com/200x150?text=Dental+Tool+2" alt="منتج 2" />
    <img src="https://via.placeholder.com/200x150?text=Dental+Tool+3" alt="منتج 3" />
    
    <button onclick="alert('شكراً لاهتمامك! تواصل معنا للطلب 📞')">اطلب الآن</button>
  </section>

  <section>
    <h2>تواصل معنا</h2>
    <form>
      <input type="text" placeholder="الاسم" required><br>
      <input type="email" placeholder="البريد الإلكتروني" required><br>
      <textarea placeholder="اكتب رسالتك هنا..." rows="5"></textarea><br>
      <button type="submit">إرسال</button>
    </form>
  </section>

  <footer>
    <div class="social">
      <h3>تابعنا على</h3>
      <a href="https://facebook.com">فيسبوك</a> |
      <a href="https://instagram.com">إنستجرام</a> |
      <a href="https://wa.me/201234567890">واتساب</a>
    </div>
    <p>© 2025 Joo Smile Store</p>
  </footer>
</body>
</html>
