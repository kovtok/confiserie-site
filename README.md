<!DOCTYPE html>
<html lang="uk">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Confiserie StovbaGalyna</title>
  <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css" rel="stylesheet">
</head>
<body class="bg-pink-50 text-gray-800">
  <!-- Header -->
  <header class="bg-white shadow p-4 flex justify-between items-center">
    <h1 class="text-2xl font-bold text-pink-600">Confiserie StovbaGalyna</h1>
    <a href="https://www.instagram.com/confiserie_stovbagalyna/" target="_blank" class="text-blue-500">Instagram</a>
  </header>

  <!-- Hero -->
  <section class="text-center p-6 bg-pink-100">
    <h2 class="text-3xl font-semibold">Сучасні десерти, торти на замовлення</h2>
    <p class="mt-2">Бронювання і онлайн-оплата • Професійна випічка</p>
    <a href="#catalog" class="mt-4 inline-block px-6 py-2 bg-pink-500 text-white rounded">Переглянути каталог</a>
  </section>

  <!-- Catalog -->
  <section id="catalog" class="p-6">
    <h3 class="text-xl font-semibold mb-4">Каталог солодощів</h3>
    <div class="grid grid-cols-1 md:grid-cols-3 gap-6">
      <div class="bg-white shadow rounded p-4">
        <img src="https://via.placeholder.com/300x200" alt="Бенто торт" class="mb-2">
        <h4 class="font-bold">Бенто торт "Снікерс"</h4>
        <p class="text-sm">Шоколад, арахіс, карамель</p>
        <p class="text-pink-600 font-semibold">200 грн</p>
      </div>
      <div class="bg-white shadow rounded p-4">
        <img src="https://via.placeholder.com/300x200" alt="Макаруни" class="mb-2">
        <h4 class="font-bold">Макаруни "Mix Box"</h4>
        <p class="text-sm">6 штук різних смаків</p>
        <p class="text-pink-600 font-semibold">180 грн</p>
      </div>
      <div class="bg-white shadow rounded p-4">
        <img src="https://via.placeholder.com/300x200" alt="Весільний торт" class="mb-2">
        <h4 class="font-bold">Весільний торт</h4>
        <p class="text-sm">Під замовлення за індивідуальним дизайном</p>
        <p class="text-pink-600 font-semibold">від 500 грн</p>
      </div>
    </div>
  </section>

  <!-- Booking Form -->
  <section class="p-6 bg-pink-100">
    <h3 class="text-xl font-semibold mb-4">Забронювати або замовити</h3>
    <form id="bookingForm" class="grid gap-4 max-w-xl mx-auto">
      <input type="text" placeholder="Ваше ім'я" class="p-2 rounded border" required>
      <input type="tel" placeholder="Телефон/Viber/Telegram" class="p-2 rounded border" required>
      <input type="email" placeholder="Email (необов'язково)" class="p-2 rounded border">
      <select class="p-2 rounded border" required>
        <option disabled selected>Оберіть десерт</option>
        <option>Бенто торт "Снікерс"</option>
        <option>Макаруни "Mix Box"</option>
        <option>Весільний торт</option>
      </select>
      <input type="date" class="p-2 rounded border" required>
      <textarea placeholder="Коментар або побажання" class="p-2 rounded border"></textarea>
      <button type="submit" class="bg-pink-500 text-white p-2 rounded">Забронювати</button>
    </form>
  </section>

  <!-- Payment -->
  <section class="p-6">
    <h3 class="text-xl font-semibold mb-2">Оплата</h3>
    <p class="mb-4">Ви можете оплатити замовлення онлайн:</p>
    <ul class="list-disc list-inside">
      <li><a href="#" class="text-blue-600">LiqPay (ПриватБанк)</a></li>
      <li><a href="#" class="text-blue-600">Monobank</a></li>
      <li>Після підтвердження заявки вам надійде посилання</li>
    </ul>
  </section>

  <!-- Footer -->
  <footer class="bg-white p-4 text-center mt-8 text-sm text-gray-600">
    © 2025 Confiserie StovbaGalyna • Написати: <a href="mailto:galyna@confiserie.com" class="text-blue-600">galyna@confiserie.com</a>
    • Viber/Telegram: +380xx xxx xx xx
  </footer>

  <script>
    document.getElementById('bookingForm').addEventListener('submit', function(e) {
      e.preventDefault();
      alert('Вашу заявку прийнято! З вами зв'яжуться найближчим часом.');
    });
  </script>
</body>
</html>
