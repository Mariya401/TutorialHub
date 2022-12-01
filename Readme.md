# Руководство по использованию git

1. Создать папку (на рабочем столе, например) - Tutorial

2. Открыть VScode

3. Открыть созданную папку через меню в левом верхнем меню

4. Открыть терминал: Меню «Вид» - Терминал

5. Узнать версию установленного приложения: git –version

6. Создание нового репозитория: git init

7. Определение состояния: git status

8. Создать файл с расширением «.md» - Tutorial.md. Сохранить его «Ctrl+S».

9. Снова проверить статус: git status

10. Добавить файл для контроля его версий: git add .\Tutorial.md (можно использовать «Tab» при вводе первых букв имени файла) или git add*.

11. Сделать коммит (примечание – что изменилось в файле): git commit –m”Create file”.

12. Добавить текст в файл. Сохранить.

13. Снова добавить файл к коммиту: git add .\Tutorial.md

14. Сделать коммит: git commit –m”Аdd text”.

15. Преобразовать текст:

* Выделить заголовки: # Заголовок.

* Выделить текст курсивом можно двумя способами: *Текст* или _Текст_.

* Выделить текст полужирным можно двумя способами: **Текст** или __Текст__.

Списки:

1. Создать нумерованный список.

* Создать ненумерованный список*

16. Сохранить.

17. Снова добавить файл к коммиту: git add .\Tutorial.md

18. Сделать коммит: git commit –m”Edit text”.

19. Посмотреть журнал сохранений: git log

20. Вернуться к более ранней версии: git checkout @#$% (ввод хэш-кода коммита)

21. Возврат к последней версии: git checkout master

22. Сравнить изменения в версиях: git diff

23. Узнать перечень веток: git branch

24. Создать новую ветку: git branch имя_ветки

25. Перейти на другую ветку: git checkout имя_ветки

26. Слить ветки: git merge

27. Удалить ветку: git branch -d

28. Вставить картинку: ![Картинка](image.jpg)

29. Конец.

КОНФЛИКТ ИЛИ НЕТ?!?!
