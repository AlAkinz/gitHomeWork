# Репозиторий для pull request

* В своём аккаунте на *GitHub* создать копию репозитория **maxim-stoma/gitHomeWork** с помощью кнопки "Fork".
* Клонировать копию репозитория на локальный компьютер.
* **Создать новую ветку.**
* Добавить файл с инструкцией в новую ветку.
* Дополнить инструкцию разделами по работе с удалёнными репозиториями, pull request.
* Зафиксировать изменения (коммиты).
* Отправить изменения на GitHub.
* На сайте GitHub выполнить Pull request.
# Инструкция по Git

## Основные команды

* git init – инициализация локального репозитория
* git commit - создание коммита.
* git status - получить информацию от git о его текущем состоянии
* git add – добавить файл или файлы к следующему коммиту
* git log – вывод на экран истории всех коммитов с их хеш-кодами
* git checkout – переход от одного коммита к другому
* git checkout master – вернуться к актуальному состоянию и продолжить работу
* git diff – увидеть разницу между текущим файлом и закоммиченным файлом
* git branch - показывает все доступные ветки
* git branch branch_name - создает новую именную ветку
* git merge - позволяет слить ветки в одну
* git merge -D branch_name - удаляет не слитую ветку
* git merge -d branch_name - удаляет слитую ветку
* git log --graph - позволяет увидеть лог коммитов с визуализацией
между ними
### Синтаксис языка Markdown
1. "#" Заголовок – выделение заголовков. Количество символов “#” задаёт уровень заголовка
(поддерживается 6 уровней).
2. "=" или "-" – подчёркиванием этими символами (не менее 3 подряд) выделяют заголовки первого
(“=”) и второго (“-”) уровней.
3. ** Полужирное начертание** или __ Полужирное начертание__
4. " * " Курсивное начертание " * " или " _ "Курсивное начертание " _ "
5. " ** " Полужирное курсивное начертание " ** "
6. " ~~ " Зачёркнутый текст " ~~ "
7. " * " Строка – ненумерованные списки, символ “*” в начале строки
8. "1, 2, 3 …" – нумерованные списки
### Работа с изображениями
Чтобы добавить изображение, необходимо воспользоваться следующими символами:
![](), где в "!" обозначает, что мы работаем с изображением, "[]" показывает подпись к изображению, а в "()" мы пишем адрес нашего изображения, например это будет выглядеть вот так: 

![Это ShadowFiend](1.jpg)

А так же, вы можете сделать такое же с GIF изображеиями, например вот так:

![](shadow-fiend-dota2.gif)