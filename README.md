
# Учебник JavaScript

Этот репозитарий содержит учебник JavaScript, включая все разделы, статьи, задачи.

**Сейчас полностью экспортирован раздел https://github.com/iliakan/javascript-tutorial/tree/master/02-ui/03-event-details, позже будет всё содержимое.**

Он предназначен для отображения движком сайта javascript.ru, при помощи парсера https://github.com/iliakan/simpledownParser.

При этом синтаксис намеренно сделан совместимым с GitHub, чтобы при желании можно было читать текст прямо из репозитария. Конечно, "живые" примеры и другие продвинутые возможности при этом будут не доступны, т.к. парсер GitHub их не умеет.

**Каждому разделу, статье или задаче соответствует директория.**

Эта директория имеет вид NN-url, где NN - это номер для сортировки статей и разделов (они упорядочены), а url - URL-имя, по которому материал будет доступен.

В директории находится один из файлов:

  - `index.md` для раздела
  - `article.md` для статьи
  - `task.md` для условия задачи (+там же `solution.md` с решением)

Каждый из этих файлов начинается с `# Заголовка материала`.

Абсолютный URL для разделов и статей -- это URL-имя без номера и родителей, для задачи -- с префиксом `/task/`.

Например:

  - директория `02-ui/03-event-details` с файлом `index.md` - это раздел сайта "События в деталях", он будет доступен по URL `/event-details`.
  - директория `02-ui/03-event-details/06-drag-and-drop` с файлом `article.md` содержит статью "Мышь: Drag'n'Drop`, доступную по URL `/drag-and-drop`.
  - директория `02-ui/03-event-details/06-drag-and-drop/slider` с файлом `task.md` содержит задачу с названием "Слайдер", доступную по адресу `/task/slider`.

Ресурсы и примеры, необходимые для статьи, раздела или задачи, находятся в её директории. На них можно ссылаться из материала.

**Этот репозитарий пока не публичный, он станет публичным после релиза сайта.**

Это сделано для того, чтобы поисковики (Google, Yandex etc) не проиндексировали его содержимое до того, как оно появится на сайте. А то они подумают, что на сайте копия, а не оригинал материалов и понизят его в ранжировании.



