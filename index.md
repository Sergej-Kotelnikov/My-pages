---
layout: default
title: Добро пожаловать!
---

# 👋 Привет!

Меня зовут Сергей. Это мой первый сайт на GitHub Pages с темой **Time Machine**.

## 🧠 Навыки
- Git и GitHub
- HTML / CSS / Markdown
- Работа в терминале

---

## ✨ Посты
_Ниже отображаются записи из папки `_posts`_

{% for post in site.posts %}
- [{{ post.title }}]({{ post.url }}) — {{ post.date | date: "%d.%m.%Y" }}
{% endfor %}
