# Введение в контроль версий
## Комманды git:
- Сделать из папки - репозиторий: git init
- Добавить файл в отслеживание: git add <имя.расширение>
- Сохранить текущее состояние: git commit -m 'описание'
- Вернуть репозиторий к последнему сохранённому состоянию: git checkout master
- Вернуть репозиторий к определённому состоянию: git checkout <версия>
- Показать отличия текущего состояния от сохранённого: git diff
- Показать журнал изменений: git log
- Показать состояние репозитория: git status

## Язык разметки Markdown
- Выделить текст заголовком: h1 - # текст, h2 - ## текст, h3 - ### текст
    # пример h1
    ## пример h2
    ### пример h3
- Перенос строки осуществляется двойным пробелом.
- Символ обратного слэша экранирует соседний символ от выполнения.
- Создание разрыва страницы: --- или *** или ___
___
- Выделение текста курсивом: \*текст*  
*пример*
- Выделение текста полужирным: \*\*текст**  
**пример**
Выделение текста прочерком: \~\~текст\~\~  
~~пример~~
- Создание ненумерованного списка: * или -
    - пример
    - пример
    - пример
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