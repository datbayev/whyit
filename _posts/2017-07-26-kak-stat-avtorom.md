---
layout: post
date: 2017-05-07
title: "Как стать автором"
categories: general
author_name : Айбол Кусаин
author_url : /author/aibol
author_avatar: aibol.png
show_avatar : true
read_time : 2
feature_image: feature-book
show_related_posts: true
square_related: recommend-woods
---

Привет, читатель! В этом посте я расскажу как стать автором на этом сайте. Сразу скажу, чтобы это сделать
понадобяться навык использования `git` и чуть-чуть сообразительности.

## Шаг 1. Клонировать репозиторий

Для этого нужно ознакомиться с постом [Как вносить изменения][contribute]{:target="_blank"}. Там расписаны шаги,
чтобы начать делать изменения на этом сайте.

## Шаг 2. Создать автора

Для того чтобы создать автора Вам нужно в корневой директории создать файл в формате `author-name.md` и сохранить его.
Внутри должны быть данные в [YML формате][yml]{:target="_blank"} в этом виде:

```
---
layout: author # неизмеяемая часть, указывает на layout который будет использоваться
title: Author
permalink: author/your_username/ # ссылка для страницы автора
feature_image: feature-laptop # рисунок для левой панели
author_avatar: avatar.png # имя рисунка
author_name: Вася Пупкин # имя автора
title: Вася Пупкин # заголовок Вашей страницы
---
```

Далее следует контент Вашей страницы в обычном [Markdown формате][markdown]. Для того, чтобы было понятно кто пишет,
желательно написать откуда Вы и в чем специалист, как например [здесь][german]{:target="_blank"}.

Для того чтобы вставить свой аватар, нужно закинуть рисунок в квадратном формате в папку `img`, после этого как указано
выше, в поле `author_avatar` впишите название файла с форматом.

## Шаг 3. Создать **pull request**

Далее, вы просто добавляете изменения в `git` и делает **pull request**. Если Вы знакомы с `git`-ом, то для Вас это
не должно быть сложно.

Поздравляю! Вы стали автором в [WhyIT.org][whyit]. Теперь пишите посты и делайте свой вклад в развитие IT.

[whyit]: https://whyit.org
[contribute]: https://whyit.org/contribute
[yml]: https://ru.wikipedia.org/wiki/YAML
[markdown]: https://ru.wikipedia.org/wiki/Markdown
[german]: https://whyit.org/german
