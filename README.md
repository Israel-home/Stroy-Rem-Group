<html lang="ru" dir="ltr">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="description" content="Профессиональный ремонт квартир и строительство домов из металлоконструкций. Гарантия качества и сроков.">
  <meta name="keywords" content="ремонт, строительство, металлоконструкции">
  <meta name="robots" content="index, follow">
  <!-- OpenGraph -->
  <meta property="og:title" content="СтройРемГрупп">
  <meta property="og:description" content="Ремонт и строительство под ключ">
  <meta property="og:type" content="website">
  <meta property="og:image" content="https://israel-home.github.io/Stroy-Rem-Group/images/og-image.jpg">
  <link rel="canonical" href="https://israel-home.github.io/Stroy-Rem-Group/">
  <title>Ремонт и Строительство | СтройРемГрупп</title>
  <!-- Preconnect -->
  <link rel="preconnect" href="https://cdn.tailwindcss.com">
  <link rel="preconnect" href="https://unpkg.com">
  <!-- Favicon -->
  <link rel="icon" href="images/favicon.ico" type="image/x-icon">
  <!-- Styles -->
  <script src="https://cdn.tailwindcss.com"></script>
  <script src="https://unpkg.com/aos@2.3.1/dist/aos.js"></script>
  <link href="https://unpkg.com/aos@2.3.1/dist/aos.css" rel="stylesheet">
  <style>
    html { scroll-behavior: smooth; }
    button, a { transition: all 0.3s ease; }
    .text-gold { color: rgba(234, 179, 8, 0.8); }
    #mobile-menu {
      max-height: 0;
      overflow: hidden;
      transition: max-height 0.3s ease-out;
    }
    #mobile-menu.active {
      max-height: 500px;
    }
  </style>
</head>
<body class="bg-gray-900 text-white font-sans">
  <!-- Header -->
  <header class="p-6 bg-gray-800 shadow-lg sticky top-0 z-50">
    <div class="max-w-7xl mx-auto flex justify-between items-center">
      <div>
        <h1 class="text-2xl font-bold">СтройРемГрупп</h1>
        <p class="text-sm text-gray-400 mt-1">
          <span class="text-gold">Строим на совесть</span>, 
          <span class="text-gold">ремонтируем с душой</span>
        </p>
      </div>
      <nav aria-label="Основное меню" class="hidden md:flex space-x-6">
        <a href="#about" class="hover:text-yellow-400">О нас</a>
        <a href="#services" class="hover:text-yellow-400">Услуги</a>
        <a href="#portfolio" class="hover:text-yellow-400">Портфолио</a>
        <a href="#contact" class="hover:text-yellow-400">Контакты</a>
      </nav>
      <button class="md:hidden text-yellow-400" id="mobile-menu-button" aria-label="Меню">☰</button>
    </div>
    <!-- Мобильное меню -->
    <div class="md:hidden" id="mobile-menu">
      <a href="#about" class="block py-2 hover:text-yellow-400">О нас</a>
      <a href="#services" class="block py-2 hover:text-yellow-400">Услуги</a>
      <a href="#portfolio" class="block py-2 hover:text-yellow-400">Портфолио</a>
      <a href="#contact" class="block py-2 hover:text-yellow-400">Контакты</a>
    </div>
  </header>

  <!-- Hero Section -->
  <section id="about" class="min-h-[60vh] bg-gray-950 flex items-center justify-center text-center px-4" data-aos="fade-up">
    <div>
      <h2 class="text-4xl font-bold mb-4">Ремонт квартир и строительство домов из металлоконструкций</h2>
      <p class="text-gray-400 max-w-xl mx-auto text-lg">Профессионально. Надёжно. В срок.</p>
      <a href="#contact" class="inline-block mt-8 bg-yellow-500 hover:bg-yellow-600 text-black font-semibold py-3 px-8 rounded">
        Бесплатная консультация
      </a>
    </div>
  </section>

  <!-- Services -->
  <section id="services" class="py-16 px-4 max-w-7xl mx-auto" data-aos="fade-up">
    <h3 class="text-3xl font-bold mb-12 text-center">Наши услуги</h3>
    <div class="grid md:grid-cols-3 gap-8">
      <div class="bg-gray-800 p-8 rounded-xl shadow-lg hover:shadow-yellow-500/10 transition-all">
        <div class="text-yellow-400 text-4xl mb-4">🏠</div>
        <h4 class="text-xl font-semibold mb-3">Ремонт квартир</h4>
        <p class="text-gray-400">Косметический и капитальный ремонт под ключ с гарантией качества.</p>
      </div>
      <div class="bg-gray-800 p-8 rounded-xl shadow-lg hover:shadow-yellow-500/10 transition-all">
        <div class="text-yellow-400 text-4xl mb-4">🏗️</div>
        <h4 class="text-xl font-semibold mb-3">Строительство домов</h4>
        <p class="text-gray-400">Дома из металлоконструкций — быстро, надёжно, энергоэффективно.</p>
      </div>
      <div class="bg-gray-800 p-8 rounded-xl shadow-lg hover:shadow-yellow-500/10 transition-all">
        <div class="text-yellow-400 text-4xl mb-4">🛠️</div>
        <h4 class="text-xl font-semibold mb-3">Дизайн-проекты</h4>
        <p class="text-gray-400">Индивидуальные решения для вашего интерьера.</p>
      </div>
    </div>
  </section>

  <!-- Portfolio -->
  <section id="portfolio" class="py-16 bg-gray-950 px-4" data-aos="fade-up">
    <div class="max-w-7xl mx-auto">
      <h3 class="text-3xl font-bold mb-12 text-center">Наши работы</h3>
      <div class="grid md:grid-cols-2 lg:grid-cols-3 gap-6">
        <div class="group relative overflow-hidden rounded-xl">
          <img src="images/project1.jpg" loading="lazy" class="w-full h-64 object-cover transition-transform duration-500 group-hover:scale-110" alt="">
          <div class="absolute inset-0 bg-gradient-to-t from-black/80 to-transparent flex items-end p-6 opacity-0 group-hover:opacity-100 transition-opacity">
            <div>
              <h4 class="text-xl font-bold">Дом в кибуце</h4>
              <p class="text-gray-300">Капитальный ремонт, 85 м²</p>
            </div>
          </div>
        </div>
        <div class="group relative overflow-hidden rounded-xl">
          <img src="images/project2.jpg" loading="lazy" class="w-full h-64 object-cover transition-transform duration-500 group-hover:scale-110" alt="Загородный дом из металлоконструкций">
          <div class="absolute inset-0 bg-gradient-to-t from-black/80 to-transparent flex items-end p-6 opacity-0 group-hover:opacity-100 transition-opacity">
            <div>
              <h4 class="text-xl font-bold">Загородный дом</h4>
              <p class="text-gray-300">150 м², металлоконструкции</p>
            </div>
          </div>
        </div>
        <div class="group relative overflow-hidden rounded-xl">
          <img src="images/project3.jpg" loading="lazy" class="w-full h-64 object-cover transition-transform duration-500 group-hover:scale-110" alt="Офисный ремонт">
          <div class="absolute inset-0 bg-gradient-to-t from-black/80 to-transparent flex items-end p-6 opacity-0 group-hover:opacity-100 transition-opacity">
            <div>
              <h4 class="text-xl font-bold">Офис в бизнес-центре</h4>
              <p class="text-gray-300">Ремонт офиса, 120 м²</p>
            </div>
          </div>
        </div>
      </div>
      <div class="text-center mt-12">
        <button class="border-2 border-yellow-400 text-yellow-400 hover:bg-yellow-400 hover:text-black font-semibold py-2 px-6 rounded-full transition-all">
          Показать все работы
        </button>
      </div>
    </div>
  </section>

  <!-- Contact -->
  <section id="contact" class="py-16 px-4 max-w-2xl mx-auto" data-aos="fade-up">
    <h3 class="text-3xl font-bold mb-8 text-center">Свяжитесь с нами</h3>
    <form id="contact-form" class="space-y-5">
      <input type="text" name="name" placeholder="Ваше имя" class="w-full p-4 rounded-lg bg-gray-800 text-white placeholder-gray-500 border border-gray-700 focus:border-yellow-400 focus:outline-none" required>
      <input type="tel" name="phone" placeholder="Телефон" class="w-full p-4 rounded-lg bg-gray-800 text-white placeholder-gray-500 border border-gray-700 focus:border-yellow-400 focus:outline-none" required>
      <textarea name="message" placeholder="Ваше сообщение" rows="5" class="w-full p-4 rounded-lg bg-gray-800 text-white placeholder-gray-500 border border-gray-700 focus:border-yellow-400 focus:outline-none"></textarea>
      <button type="submit" class="w-full bg-yellow-500 hover:bg-yellow-600 text-black font-semibold py-3 px-6 rounded-lg transition-all">
        Отправить заявку
      </button>
    </form>
    <div id="form-success" class="hidden mt-4 p-4 bg-green-500/20 text-green-400 rounded-lg">
      Заявка отправлена! Мы свяжемся с вами в ближайшее время.
    </div>
    <div id="form-error" class="hidden mt-4 p-4 bg-red-500/20 text-red-400 rounded-lg">
      Ошибка отправки. Пожалуйста, попробуйте позже или свяжитесь другим способом.
    </div>
  </section>

  <!-- Map -->
  <div class="w-full h-96 bg-gray-800 overflow-hidden">
    <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d2245.372951144276!2d37.618423315930474!3d55.75367628055255!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x46b54a5a738fa419%3A0x7c347d506f52311f!2z0JzQvtGB0LrQvtCy0YHQutC40Lkg0JrRgNC10LzQu9GM!5e0!3m2!1sru!2sru!4v1623753287124!5m2!1sru!2sru" 
            width="100%" 
            height="100%" 
            style="border:0;" 
            allowfullscreen="" 
            loading="lazy"
            referrerpolicy="no-referrer-when-downgrade"
            aria-label="Карта с нашим местоположением">
    </iframe>
  </div>

  <!-- Footer -->
  <footer class="bg-gray-800 py-12 px-4">
    <div class="max-w-7xl mx-auto grid md:grid-cols-4 gap-8">
      <div>
        <h4 class="text-xl font-bold mb-4">СтройРемГрупп</h4>
        <p class="text-gray-400">
          <span class="text-gold">Строим на совесть</span>, 
          <span class="text-gold">ремонтируем с душой</span>
        </p>
      </div>
      <div>
        <h5 class="font-semibold mb-4">Контакты</h5>
        <p class="text-gray-400 mb-2"></p>
        <p class="text-gray-400 mb-2">0557734071</p>
        <p class="text-gray-400">info@stroirem.ru</p>
      </div>
      <div>
        <h5 class="font-semibold mb-4">Услуги</h5>
        <a href="#services" class="block text-gray-400 hover:text-yellow-400 mb-2">Ремонт квартир</a>
        <a href="#services" class="block text-gray-400 hover:text-yellow-400 mb-2">Строительство домов</a>
        <a href="#services" class="block text-gray-400 hover:text-yellow-400">Дизайн-проекты</a>
      </div>
      <div>
        <h5 class="font-semibold mb-4">Соцсети</h5>
        <div class="flex space-x-4">
          <a href="https://vk.com/stroiremgroup" class="text-gray-400 hover:text-yellow-400 text-xl" aria-label="ВКонтакте">VK</a>
          <a href="https://t.me/stroiremgroup" class="text-gray-400 hover:text-yellow-400 text-xl" aria-label="Telegram">TG</a>
          <a href="https://wa.me/79991234567" class="text-gray-400 hover:text-yellow-400 text-xl" aria-label="WhatsApp">WA</a>
        </div>
      </div>
    </div>
    <div class="border-t border-gray-700 mt-12 pt-6 text-center text-gray-500">
      © <span id="current-year">2025</span> СтройРемГрупп. Все права защищены.
    </div>
  </footer>

  <script>
    // Инициализация анимаций
    AOS.init({
      duration: 800,
      once: true,
      offset: 100
    });

    // Мобильное меню
    const mobileMenuButton = document.getElementById('mobile-menu-button');
    const mobileMenu = document.getElementById('mobile-menu');
    if (mobileMenuButton && mobileMenu) {
      mobileMenuButton.addEventListener('click', () => {
        mobileMenu.classList.toggle('active');
        mobileMenuButton.textContent = mobileMenu.classList.contains('active') ? '✕' : '☰';
      });
    }

    // Автоматическое обновление года
    document.getElementById('current-year').textContent = new Date().getFullYear();

    // Плавный скролл для якорных ссылок
    document.querySelectorAll('a[href^="#"]').forEach(anchor => {
      anchor.addEventListener('click', function(e) {
        e.preventDefault();
        const target = document.querySelector(this.getAttribute('href'));
        if (target) {
          target.scrollIntoView({
            behavior: 'smooth'
          });
          // Закрываем мобильное меню после клика
          if (mobileMenu.classList.contains('active')) {
            mobileMenu.classList.remove('active');
            mobileMenuButton.textContent = '☰';
          }
        }
      });
    });

    // Обработка формы
    const contactForm = document.getElementById('contact-form');
    const formSuccess = document.getElementById('form-success');
    const formError = document.getElementById('form-error');
    
    if (contactForm) {
      contactForm.addEventListener('submit', async (e) => {
        e.preventDefault();
        
        const formData = new FormData(contactForm);
        const response = await fetch('https://api.telegram.org/botВАШ_BOT_API/sendMessage', {
          method: 'POST',
          body: new URLSearchParams({
            chat_id: 'ВАШ_CHAT_ID',
            text: `Новая заявка:\nИмя: ${formData.get('name')}\nТелефон: ${formData.get('phone')}\nСообщение: ${formData.get('message')}`
          })
        });
        
        if (response.ok) {
          contactForm.reset();
          formSuccess.classList.remove('hidden');
          formError.classList.add('hidden');
        } else {
          formError.classList.remove('hidden');
          formSuccess.classList.add('hidden');
        }
      });
    }
  </script>
</body>
</html>
