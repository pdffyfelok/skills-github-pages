<!DOCTYPE html>
<html lang="ru">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1" />
<title>HYPOCRITE - Ролевая игра</title>
<style>
  body {
    margin: 0; font-family: Arial, sans-serif;
    background: linear-gradient(135deg, #000000, #1a001a);
    color: #eee;
  }
  header {
    background: linear-gradient(90deg, #ff3399, #33ccff);
    padding: 15px;
    text-align: center;
    font-size: 2em;
    font-weight: bold;
    color: #000;
  }
  nav {
    display: flex;
    justify-content: center;
    background: linear-gradient(90deg, #330033, #003366);
  }
  nav button {
    background: linear-gradient(45deg, #ff3399, #33ccff);
    border: none;
    color: #000;
    padding: 12px 20px;
    margin: 8px;
    font-weight: bold;
    cursor: pointer;
    border-radius: 6px;
    transition: background 0.3s ease;
  }
  nav button:hover {
    background: linear-gradient(45deg, #ff66bb, #66ddff);
  }
  section {
    max-width: 800px;
    margin: 20px auto;
    background: #111;
    padding: 20px;
    border-radius: 10px;
    box-shadow: 0 0 15px #ff3399;
  }
  h2 {
    color: #ff3399;
    border-bottom: 2px solid #33ccff;
    padding-bottom: 5px;
  }
  label {
    display: block;
    margin-top: 10px;
    font-weight: bold;
  }
  input[type="text"], textarea, select {
    width: 100%;
    padding: 8px;
    margin-top: 4px;
    border-radius: 5px;
    border: none;
    background: #222;
    color: #eee;
  }
  textarea {
    resize: vertical;
  }
  .hidden {
    display: none;
  }
</style>
</head>
<body>

<header>HYPOCRITE</header>

<nav>
  <button onclick="showSection('rules')">Правила</button>
  <button onclick="showSection('story')">Сюжет</button>
  <button onclick="showSection('template')">Шаблон анкеты</button>
  <button onclick="showSection('participants')">Анкеты участников</button>
  <button onclick="showSection('roles')">Занятые роли</button>
  <button onclick="showSection('projects')">Другие проекты владельцев</button>
</nav>

<section id="rules" class="content-section">
  <h2>Правила</h2>
  <p>Здесь размещаются правила ролевой игры HYPOCRITE...</p>
</section>

<section id="story" class="content-section hidden">
  <h2>Сюжет</h2>
  <p>Описание сюжета ролевой игры HYPOCRITE...</p>
</section>

<section id="template" class="content-section hidden">
  <h2>Шаблон анкеты</h2>
  <form id="characterForm">
    <label for="name">Имя</label>
    <input type="text" id="name" name="name" required />

    <label for="age">Возраст</label>
    <input type="text" id="age" name="age" required />

    <label for="type">Сталкер / Мутант</label>
    <select id="type" name="type" required>
      <option value="">Выберите</option>
      <option value="сталкер">Сталкер</option>
      <option value="мутант">Мутант</option>
    </select>

    <label for="character">Характер</label>
    <textarea id="character" name="character" rows="3" required></textarea>

    <label for="appearance">Внешность</label>
    <textarea id="appearance" name="appearance" rows="3" required></textarea>

    <label for="background">Предыстория</label>
    <textarea id="background" name="background" rows="4" required></textarea>

    <label for="weapon">Оружие</label>
    <textarea id="weapon" name="weapon" rows="2" required></textarea>

    <label for="headcanons">Хэдканоны</label>
    <textarea id="headcanons" name="headcanons" rows="3"></textarea>

    <button type="submit" style="margin-top: 15px; background: linear-gradient(45deg, #ff3399, #33ccff); color: #000; border: none; padding: 10px 20px; border-radius: 6px; font-weight: bold; cursor: pointer;">Отправить</button>
  </form>
</section>

<section id="participants" class="content-section hidden">
  <h2>Анкеты участников</h2>
  <p>Здесь будут отображаться анкеты участников (пока пусто).</p>
</section>

<section id="roles" class="content-section hidden">
  <h2>Занятые роли</h2>
  <p>Информация о занятых ролях в игре HYPOCRITE...</p>
</section>
<section id="projects" class="content-section hidden">
  <h2>Другие проекты владельцев</h2>
  <p>Список и описание других проектов владельцев сайта...</p>
</section>

<script>
  function showSection(id) {
    document.querySelectorAll('.content-section').forEach(section => {
      section.classList.add('hidden');
    });
    document.getElementById(id).classList.remove('hidden');
  }

  // Обработка формы (пример)
  document.getElementById('characterForm').addEventListener('submit', function(e) {
    e.preventDefault();
    alert('Анкета отправлена! (реализация сохранения данных зависит от бэкенда)');
    this.reset();
  });
</script>

</body>
</html>
