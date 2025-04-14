html
<!DOCTYPE html>
<html lang="ru" dir="ltr">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="description" content="Профессиональный ремонт квартир и строительство домов из металлоконструкций. Гарантия качества и сроков.">
  <meta name="keywords" content="ремонт, строительство, металлоконструкции, ремонт квартир">
  <!-- OpenGraph -->
  <meta property="og:title" content="СтройРемГрупп">
  <meta property="og:description" content="Ремонт и строительство под ключ">
  <meta property="og:type" content="website">
  <meta property="og:image" content="https://example.com/path-to-image.jpg">
  <!-- Preconnect -->
  <link rel="preconnect" href="https://cdn.tailwindcss.com">
  <link rel="preconnect" href="https://unpkg.com">
  <title>Ремонт и Строительство | СтройРемГрупп</title>
  <!-- Styles -->
  <script src="https://cdn.tailwindcss.com"></script>
  <script src="https://unpkg.com/aos@2.3.1/dist/aos.js"></script>
  <link href="https://unpkg.com/aos@2.3.1/dist/aos.css" rel="stylesheet">
  <style>
    html {
      scroll-behavior: smooth;
    }
    button, a {
      transition: all 0.3s ease;
    }
  </style>
</head>
<body class="bg-gray-900 text-white font-sans" id="body">
  <!-- Header -->
  <header class="p-6 bg-gray-800 shadow-lg">
    <div class="max-w-7xl mx-auto flex justify-between items-center">
      <div>
        <h1 class="text-2xl font-bold" id="title">СтройРемГрупп</h1>
        <p class="text-sm text-gray-400 mt-1">Строим на совесть, ремонтируем с душой</p>
      </div>
      <nav aria-label="Основное меню" class="space-x-6" id="nav">
        <a href="#about" class="hover:text-yellow-400" id="nav-about">О нас</a>
        <a href="#services" class="hover:text-yellow-400" id="nav-services">Услуги</a>
        <a href="#portfolio" class="hover:text-yellow-400" id="nav-portfolio">Портфолио</a>
        <a href="#contact" class="hover:text-yellow-400" id="nav-contact">Контакты</a>
      </nav>
    </div>
  </header>

  <!-- Hero Section -->
  <section id="about" class="bg-gray-950 py-20 text-center" data-aos="fade-up">
    <h2 class="text-4xl font-bold mb-4" id="hero-title">Ремонт квартир и строительство домов из металлоконструкций</h2>
    <p class="text-gray-400 max-w-xl mx-auto" id="hero-subtitle">Профессионально. Надёжно. В срок.</p>
  </section>

  <!-- Services -->
  <section id="services" class="py-16 px-4 max-w-7xl mx-auto" data-aos="fade-up">
    <h3 class="text-3xl font-bold mb-8 text-center" id="services-title">Наши услуги</h3>
    <div class="grid md:grid-cols-2 gap-10">
      <div class="bg-gray-800 p-6 rounded-xl shadow-md" itemscope itemtype="https://schema.org/Service">
        <h4 class="text-xl font-semibold mb-2" id="service-1-title" itemprop="name">Ремонт квартир</h4>
        <p class="text-gray-400" id="service-1-desc" itemprop="description">Косметический и капитальный ремонт под ключ с гарантией качества.</p>
      </div>
      <div class="bg-gray-800 p-6 rounded-xl shadow-md" itemscope itemtype="https://schema.org/Service">
        <h4 class="text-xl font-semibold mb-2" id="service-2-title" itemprop="name">Строительство домов</h4>
        <p class="text-gray-400" id="service-2-desc" itemprop="description">Современные дома из металлоконструкций — быстро, надёжно, энергоэффективно.</p>
      </div>
    </div>
  </section>

  <!-- Portfolio -->
  <section id="portfolio" class="py-16 bg-gray-950 px-4" data-aos="fade-up">
    <h3 class="text-3xl font-bold mb-8 text-center" id="portfolio-title">Портфолио</h3>
    <div class="grid md:grid-cols-3 gap-6 max-w-7xl mx-auto">
      <figure>
        <img src="https://source.unsplash.com/400x300/?interior" loading="lazy" class="rounded-xl" alt="Интерьер квартиры после ремонта" width="400" height="300">
        <figcaption class="sr-only">Пример ремонта квартиры</figcaption>
      </figure>
      <figure>
        <img src="https://source.unsplash.com/400x300/?construction" loading="lazy" class="rounded-xl" alt="Строительство дома из металлоконструкций" width="400" height="300">
        <figcaption class="sr-only">Строительство дома</figcaption>
      </figure>
      <figure>
        <img src="https://source.unsplash.com/400x300/?architecture" loading="lazy" class="rounded-xl" alt="Готовый проект дома" width="400" height="300">
        <figcaption class="sr-only">Завершенный проект</figcaption>
      </figure>
    </div>
  </section>

  <!-- Contact -->
  <section id="contact" class="py-16 px-4 max-w-2xl mx-auto" data-aos="fade-up">
    <h3 class="text-3xl font-bold mb-6 text-center" id="contact-title">Связаться с нами</h3>
    <form class="space-y-4" aria-label="Форма обратной связи">
      <input type="text" placeholder="Ваше имя" class="w-full p-3 rounded bg-gray-800 text-white placeholder-gray-500" aria-required="true" required>
      <input type="tel" placeholder="Телефон" class="w-full p-3 rounded bg-gray-800 text-white placeholder-gray-500" aria-required="true" required>
      <textarea placeholder="Ваше сообщение" rows="4" class="w-full p-3 rounded bg-gray-800 text-white placeholder-gray-500" aria-required="true" required></textarea>
      <button type="submit" class="bg-yellow-500 hover:bg-yellow-600 text-black font-semibold py-3 px-6 rounded" id="submit-button" data-trans-ru="Отправить" data-trans-he="שלח">Отправить</button>
    </form>
  </section>

  <!-- Map -->
  <section class="py-16 bg-gray-900">
    <h3 class="text-3xl font-bold mb-6 text-center" id="map-title">Где мы находимся</h3>
    <div class="w-full h-96 max-w-4xl mx-auto" loading="lazy">
      <iframe class="w-full h-full rounded-xl" src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d10873.62814648255!2d34.8516125!3d32.1093331!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x151d4c6189f8c0c3%3A0xf84c8e0b40c55de!2z0J_QvtC70YzRidCw0Y8g0J_QvtGB0L_QtdGA0LXQvdC40Y8!5e0!3m2!1sru!2sil!4v1611234567890" frameborder="0" allowfullscreen="" referrerpolicy="no-referrer-when-downgrade" aria-label="Карта расположения офиса"></iframe>
    </div>
  </section>

  <!-- Language Switch -->
  <div class="fixed bottom-4 right-4">
    <button onclick="switchLang()" class="bg-yellow-500 hover:bg-yellow-600 text-black font-semibold py-2 px-4 rounded shadow" id="lang-button" aria-label="Переключить язык" data-trans-ru="Ivrit / Русский" data-trans-he="Русский / Ivrit">Ivrit / Русский</button>
  </div>

  <!-- Footer -->
  <footer class="bg-gray-800 text-center p-4 text-gray-500">
    <p>© <span id="current-year">2025</span> СтройРемГрупп. Все права защищены.</p>
  </footer>

  <script>
    // Инициализация AOS
    AOS.init({
      duration: 800,
      once: true
    });

    // Автоматическое обновление года в футере
    document.getElementById('current-year').textContent = new Date().getFullYear();

    // Оптимизированное переключение языка
    let currentLang = "ru";
    function switchLang() {
      currentLang = currentLang === "ru" ? "he" : "ru";
      document.documentElement.lang = currentLang;
      document.documentElement.dir = currentLang === "he" ? "rtl" : "ltr";
      
      // Обновляем элементы с data-trans
      document.querySelectorAll('[data-trans-' + currentLang + ']').forEach(el => {
        const attr = 'trans-' + currentLang;
        if (el.hasAttribute('data-' + attr)) {
          el.textContent = el.getAttribute('data-' + attr);
        }
      });
    }

    // Валидация формы
    document.querySelector('form').addEventListener('submit', function(e) {
      const telInput = this.querySelector('input[type="tel"]');
      if (!/^[\d\s\+\-\(\)]{10,}$/.test(telInput.value)) {
        e.preventDefault();
        telInput.focus();
        alert('Введите корректный номер телефона');
      }
    });
  </script>

  <!-- Schema.org markup -->
  <script type="application/ld+json">
    {
      "@context": "https://schema.org",
      "@type": "LocalBusiness",
      "name": "СтройРемГрупп",
      "description": "Ремонт квартир и строительство домов из металлоконструкций",
      "address": {
        "@type": "PostalAddress",
        "addressLocality": "Ваш город",
        "streetAddress": "Ваш адрес"
      },
      "telephone": "+XXXXXXXXXXX",
      "openingHours": "Mo-Fr 09:00-18:00"
    }
  </script>
</body>
</html>
