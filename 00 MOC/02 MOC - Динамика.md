---
created: <% tp.date.now("YYYY-MM-DD") %>
updated: 2024-12-20T18:42
tags:
  - MOC
  - moc
  - overview
status: 🚧 В разработке
---

#  02 MOC - Динамика

**Описание:** Динамика – раздел механики, который изучает причины движения тел.

## Основные разделы

- [[Архимедова сила (физика)]]
- [[Ускорение (физика)]]
- [[]]

## Отдельные заметки по теме

- [[Ссылка на заметку 1]]
- [[Ссылка на заметку 2]]
- [[Ссылка на заметку 3]]

## См. также

- [[Ссылка на связанную MOC-карточку]]
- [Внешняя ссылка](URL)

%% begin-moc-styles %%

<style>
/* Стили для MOC-карточек */
body {
  --moc-border-color: #287E28; /* Темно-зеленый цвет для рамки */
  --moc-header-color: #FF5733; /* Оранжевый цвет для заголовков */
  --moc-header-border-color: #FF5733; /* Оранжевый цвет для подчеркивания заголовков */
  --moc-link-color: #007acc; /* Синий цвет для ссылок */
  --moc-link-hover-color: #FF5733; /* Оранжевый цвет для ссылок при наведении */
  --moc-background-color: #f8f8f8; /* Светло-серый фон */
}

.moc-styles {
  border: 3px dashed var(--moc-border-color);
  padding: 20px;
  margin-bottom: 30px;
  background-color: var(--moc-background-color);
}

.moc-styles h2 {
  color: var(--moc-header-color);
  border-bottom: 4px solid var(--moc-header-border-color);
  padding-bottom: 8px;
  font-size: 1.4em;
}

.moc-styles a {
  color: var(--moc-link-color);
  text-decoration: none;
}

.moc-styles a:hover {
  text-decoration: underline dotted;
  color: var(--moc-link-hover-color);
}
</style>

<div class="moc-styles"></div>

%% end-moc-styles %%

 %%
 <%*
 // Получаем имя файла
 const fileName = tp.file.title;

 // Проверяем, содержит ли имя файла "MOC"
 if (fileName.includes("MOC")) {
   // Указываем путь к целевой папке, например "MOCs/"
   const targetFolder = "MOC/";

   // Перемещаем файл
   await tp.file.move(targetFolder + fileName);
 }
 %>
 %%