<div align="center">
  <h1>🕵️‍♂️ CrimeHelp</h1>
  <p>Мощный скрипт и веб-платформа для администрации серверов San Andreas Multiplayer (SAMP).</p>
  
  ![Version](https://img.shields.io/badge/version-1.0.3-blue)
  ![License](https://img.shields.io/badge/license-MIT-green)
</div>

---

## 📖 О проекте

**CrimeHelp** — это комплексное решение для администраторов SAMP. Оно включает в себя:
1. **Lua-скрипт (MoonLoader)** — внутриигровое меню с быстрыми командами, логами наказаний и статистикой.
2. **Веб-сайт** — публичная страница с новостями, FAQ, баг-трекером и возможностью скачивания.
3. **Админ-панель** — удобное управление контентом сайта без редактирования кода (через JSONBin API).

## ✨ Возможности

- 🌐 **Все фракции**: Grove, Ballas, Vagos, Aztecas, Rifa, мафии и байкеры.
- 📝 **Логи наказаний**: Полная история с поиском и экспортом.
- 📊 **Статистика**: Отслеживание работы администратора за день и неделю.
- 🗒️ **Заметки**: Встроенный блокнот с автосохранением.
- 🛡️ **Режим стримера**: Скрывает ID и телефоны во время трансляций.
- ⚙️ **Админ-панель**: Управление версиями, новостями, FAQ и баг-трекером.

## 🚀 Установка скрипта

1. Установите [MoonLoader](https://www.blast.hk/threads/13194/) и [SAMPFUNCS](https://www.blast.hk/threads/1753/).
2. Скачайте последний релиз `CrimeHelp-vX.X.X.lua` в разделе **[Releases](../../releases)**.
3. Поместите файл в папку `MoonLoader/moonloader/`.
4. Зайдите в игру. В чате появится сообщение `[CrimeHelp] successfully loaded!`.
5. Нажмите **F8** (или введите `/oc`) для открытия меню.

## 🌐 Настройка сайта (для разработчиков)

Сайт работает на чистом HTML/CSS/JS и использует **JSONBin.io** в качестве базы данных.
1. Зарегистрируйтесь на [JSONBin.io](https://jsonbin.io).
2. Создайте бин с базовой структурой (см. папку `web/`).
3. Замените ключи `binId`, `masterKey` и `accessKey` в файлах `admin.html`, `bugs.html`, `index.html`, `news.html`, `faq.html`.

> ⚠️ **Внимание**: Никогда не выкладывайте ваш `X-Master-Key` в публичный доступ!

## 📞 Контакты

- **Авторы**: Stanislav Ronin, Drakon Drakons
- **VK**: [Stanislav Ronin](https://vk.com/ronin), [Drakon Drakons](https://vk.com/drakon_drakons)

---
<div align="center">
  <i>Сделано с ❤️ для сообщества SAMP</i>
</div>
