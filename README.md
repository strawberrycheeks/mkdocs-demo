# mkdocs-demo

Простой пример сайта, сгенерированный при помощи MkDocs для курса "Проектирование и развертывание веб-решений в эко-системе Python".

Задание выполнила Катя Абрамушкина, студентка 2 курса магистерской программы "Веб-технологии" НИУ ИТМО.

## Шаги выполнения задания

1. Создала репозиторий на GitHub, склонировала его.
2. Дальше пошла по гайду [Getting Started with MkDocs](https://www.mkdocs.org/getting-started/)**:**

   - Установила MkDocs при помощи команды: `pip install mkdocs`.
   - Создала новый проект с названием `mkdocs-demo` при помощи команды: `mkdocs new mkdocs-demo`.
   - Зашла в созданную директорию, запустила сервер при помощи команды: `mkdocs serve`.
   - Внесла изменения в файл `docs/index.md`, чтобы изменить текст на главной странице.
   - Добавила новую страницу “О сайте” (файл `docs/about.md`).
   - Попробовала другие команды из гайда: добавила `img/favicon.ico`, изменила дефолтную тему сайта на тему **readthedocs**.

3. Для деплоя на GitHub Pages использовала команду `mcdocs gh-deploy`. При использовании этой команды сгенерированные файлы для сайта (то, что складывается в директорию `site` при использовании команды `mkdocs build`) добавляются в ветку **gh-pages**, коммит создается автоматически. Также в настройках репозитория в разделе **Pages** указала, что сайт нужно собирать из корневой папки ветки **gh-pages**.
