<!DOCTYPE html>
<html lang="ru">
<head>
  <meta charset="UTF-8" />
  <title>Данные сертификата</title>
  <style>
    * { box-sizing: border-box; font-family: Arial, sans-serif; }
    body { margin: 0; background: #fff; }
    header {
      background: #1f7a8c;
      color: #fff;
      padding: 10px 20px;
      display: flex;
      justify-content: space-between;
      align-items: center;
      font-size: 14px;
    }
    .container { display: flex; padding: 20px; gap: 30px; }
    .left, .middle, .right { border: 1px solid #e0e0e0; padding: 20px; }
    .left { width: 30%; }
    .middle { width: 40%; }
    .right { width: 30%; }
    h2 { margin-top: 0; font-size: 20px; }
    label { display: block; margin-top: 15px; font-size: 14px; }
    input, select {
      width: 100%;
      padding: 8px;
      margin-top: 5px;
      border: 1px solid #ccc;
      border-radius: 4px;
    }
    button {
      margin-top: 20px;
      padding: 10px;
      width: 100%;
      background: #2a7fff;
      color: #fff;
      border: none;
      border-radius: 4px;
      cursor: pointer;
    }
    table { width: 100%; border-collapse: collapse; margin-top: 10px; }
    table, th, td { border: 1px solid #ccc; }
    th, td { padding: 8px; text-align: left; font-size: 14px; }
    .total { font-weight: bold; text-align: right; padding-top: 10px; }
    .download { margin-top: 15px; text-align: right; }
    .download button { width: auto; }
    .row { display: flex; justify-content: space-between; padding: 6px 0; font-size: 14px; }
  </style>
</head>
<body>

<header>
  <div>Национальный центр тестирования</div>
  <div>Тел: 8 (7172) 69-50-69 · uto@testcenter.kz</div>
</header>

<div class="container">

  <div class="left">
    <h2>Поиск по ИКТ</h2>
    <label>Тип тестирования
      <select>
        <option>ЕНТ</option>
      </select>
    </label>
    <label>Год
      <select>
        <option>2026</option>
      </select>
    </label>
    <label>Введите ИИН
      <input value="050224501355" />
    </label>
    <label>Введите ИКТ
      <input value="004010278" />
    </label>
    <button>Поиск</button>
  </div>

  <div class="middle">
    <h2>Данные сертификата</h2>
    <div class="row"><b>ФИО:</b> ОРАЗБЕКУЛЫ МЫРЗАБЕК</div>
    <div class="row"><b>ИИН:</b> 050224501355</div>
    <div class="row"><b>ИКТ:</b> 004010278</div>
    <div class="row"><b>Вид тестирования:</b> ЕНТ</div>
    <div class="row"><b>Год тестирования:</b> 2026 (Январь)</div>
    <div class="row"><b>Язык сдачи:</b> казахский</div>
    <div class="row"><b>Действителен до:</b> 31.12.2026</div>
  </div>

  <div class="right">
    <h2>Предметы тестирования</h2>
    <table>
      <tr><th>№</th><th>Название предмета</th><th>Балл</th></tr>
      <tr><td>1</td><td>История Казахстана</td><td>12</td></tr>
      <tr><td>2</td><td>Грамотность чтения</td><td>9</td></tr>
      <tr><td>3</td><td>Математическая грамотность</td><td>6</td></tr>
      <tr><td>4</td><td>Биология</td><td>26</td></tr>
      <tr><td>5</td><td>Химия</td><td>28</td></tr>
    </table>
    <div class="total">Общий балл: 81</div>
    <div class="download"><button>Скачать документ</button></div>
  </div>

</div>

</body>
</html>
