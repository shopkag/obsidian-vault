---
title: "{{title}}"
aliases: []
tags: []
author: "{{authorString}}"
date:
  "{ year }": 
citekey:
  "{ citekey }": 
zotero_link: zotero://select/library/items/{{key}}
type: "{{itemType}}"
source: "{{publicationTitle}}"
source-link: "{{url}}"
status: ""
date-accessed: <% tp.date.now("YYYY-MM-DD") %>
created: 2025-01-05T21:41
updated: 2025-01-12T22:41
---

# 📚 {{title}}

## ℹ️ Основная информация

*   **Название:** {{title}}
*   **Автор/Создатель:** [[{{authorString}}]]
*   **Тип:** {{type}}
*   **Источник:** {{source}}
*  **🔗 Ссылка:** {{source-link}}
*   **Статус:** {{status}}
*   **🗓️ Дата ознакомления:** {{date-accessed}}

## ✨ Основные тезисы

> Здесь запишите все ваши мысли, идеи, впечатления, цитаты и связи относительно этого произведения.

{%- for annotation in annotations -%}
- *{{annotation.text}}*
   {%- if annotation.comment -%}
     -  {{annotation.comment}}
   {%- endif -%}
{%- endfor -%}

## Заметки:
{{notes}}

---