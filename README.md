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
### Работа с Ошибкой
Во время работы со слиянием веток, вам может показаться такая ошибка:

![](2.png)
Сейчас я вам покажу, как справиться с данной ошибкой.
Пункты
* **_Accept Current Change_** - не будет применять изменения из исходящей ветки, а примет изменения, которые были в ветке, в которой вы находитесь.
* **_Accept Incoming Change_** - примит изменения, которые были из исходящей ветки и удалит конфликт из ветки, в которой вы находитесь 
* **_Accept Both Changes_** - примит изменения из Current и Incoming и объединит их 
* **_Compare Changes_** - сравнит изменения.

Вам всего нужно выбрать нужный вам вариант и всё!
### Работа с удаленным репозиторием 

* **git clone <url-адрес репозитория>** - Эта команда позволяет склонировать внешний репозиторий на наш ПК
* **git pull** - Эта команда позволяет скачать все из текущего репозитория и автоматически сделать merge с нашей версией 
* **git push** - эта команда позволяет отправить нашу версию репозитория на внешний репозиторий. ТРЕБУЕТ АВТОРИЗАЦИИ на внешнем репозитории

_**Как сделать pull request?**_

* Делаем fork репозитория
* Делаем clone СВОЕЙ версии репозитория
* Создаем новую ветку и в НЕЕ вносим свои изменения
* Фиксируем изменения (делаем коммиты)
* Отправляем свою версию в свой GitHub
* На сайте GitHub нажимаем кнопку pull request 

