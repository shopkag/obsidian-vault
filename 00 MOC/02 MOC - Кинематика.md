---
tags:
  - MOC
created: 2024-12-18T14:47
updated: 2024-12-19T15:38
---

#  02 MOC - Кинематика

**Описание:** Кинематика – это раздел механики, изучающий состояние различных тел во время движения. При этом кинематика не изучает причины, по которым тела начали двигаться.

## Основные разделы

- [[]]
- [[Ссылка на подраздел 2]]
- [[Ссылка на подраздел 3]]

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