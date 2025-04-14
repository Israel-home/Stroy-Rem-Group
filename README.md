<!-- Вставьте этот код вместо предыдущего -->
<!DOCTYPE html>
<html lang="ru" dir="ltr">
<head>
  <!-- ... (метатеги, preconnect, стили остаются как в оптимизированной версии выше) ... -->
</head>
<body class="bg-gray-900 text-white font-sans">
  <!-- ... (все секции: header, hero, services, portfolio, contact, map) ... -->

  <!-- Language Switch -->
  <div class="fixed bottom-4 right-4">
    <button onclick="switchLang()" class="bg-yellow-500 hover:bg-yellow-600 text-black font-semibold py-2 px-4 rounded shadow" 
            aria-label="Переключить язык" 
            data-trans-ru="Ivrit / Русский" 
            data-trans-he="Русский / Ivrit">
      Ivrit / Русский
    </button>
  </div>

  <!-- Footer -->
  <footer class="bg-gray-800 text-center p-4 text-gray-500">
    <p>© <span id="current-year">2025</span> СтройРемГрупп. Все права защищены.</p>
  </footer>

  <script>
    // Инициализация AOS (только один раз!)
    if (typeof AOS !== 'undefined') {
      AOS.init({ duration: 800, once: true });
    }

    // Автоматическое обновление года
    document.getElementById('current-year').textContent = new Date().getFullYear();

    // Переключение языка (оптимизированная версия)
    let currentLang = "ru";
    function switchLang() {
      currentLang = currentLang === "ru" ? "he" : "ru";
      document.documentElement.lang = currentLang;
      document.documentElement.dir = currentLang === "he" ? "rtl" : "ltr";
      
      // Обновляем только элементы с data-trans-атрибутами
      document.querySelectorAll('[data-trans-' + currentLang + ']').forEach(el => {
        el.textContent = el.getAttribute('data-trans-' + currentLang);
      });
    }

    // Валидация формы
    const form = document.querySelector('form');
    if (form) {
      form.addEventListener('submit', function(e) {
        const telInput = this.querySelector('input[type="tel"]');
        if (telInput && !/^[\d\s\+\-\(\)]{10,}$/.test(telInput.value)) {
          e.preventDefault();
          telInput.focus();
          alert('Введите корректный номер телефона');
        }
      });
    }
  </script>
</body>
</html>
