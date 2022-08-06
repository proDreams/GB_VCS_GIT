# Введение в контроль версий
## Комманды git:
- Сделать из папки - репозиторий: git init
- Добавить файл в отслеживание: git add <имя.расширение>
- Сохранить текущее состояние: git commit -m 'описание'
- Вывести список веток: git branch
- Создать новую ветку: git branch <название>
- Вернуть репозиторий к последнему сохранённому состоянию: git checkout master
- Вернуть репозиторий к определённому состоянию: git checkout <версия>
- Перейти на другую ветку репозитория: git checkout <название ветки>
- Показать отличия текущего состояния от сохранённого: git diff
- Показать журнал изменений: git log - клавиша q выход из журнала
- Показать состояние репозитория: git status
- Выполнить слияние двух веток: git merge <ветка>
- Удалить ветку: git branch -d <ветка>
- Для игнорирования git'ом определённых файлов из папки репозитория, необходимо создать файл .gitignore и прописать в нём названия игнорируемых файлов.

## Язык разметки Markdown
- Выделить текст заголовком: h1 - # текст, h2 - ## текст, h3 - ### текст
    # пример h1
    ## пример h2
    ### пример h3
    #### привер h4
    ##### пример h5
    ###### пример h6
- Перенос строки осуществляется двойным пробелом.
- Символ обратного слэша экранирует соседний символ от выполнения.
- Создание разрыва страницы: --- или *** или ___
___
- Выделение текста курсивом: \*текст* или \_текст_  
*пример*
- Выделение текста полужирным: \*\*текст** или \_\_текст__  
**пример**  
- Выделение текста и курсивом и полужирным: \*\*пример \_текста_**  
**пример _текста_**  
Выделение текста прочерком: \~\~текст\~\~  
~~пример~~
- Создание ненумерованного списка: * или - или +
    - пример
    + пример
    * пример
- Создание пронумерованного списка: 1. 2. 3. ... n.
    1. пример
    2. пример
    3. пример
- Выделение текста кодом: \`код`
- Создание блока с кодом: \```<название языка> текст с новой строки```
    ```python
    text = 'пример'
    print(text)
    ```
- Создание блока цитат: > текст
    > пример  
    пример  
    пример  
- Создание ссылки: [текст ссылки]\(адрес ссылки)  
    [GeekBrains](https://gb.ru)
- Прикрепление изображения: ![alt-текст](адрес изображения)  
    ![alt-текст](./markdown.png)