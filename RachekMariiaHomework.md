## 3. Ветвления.

1. *__Термины__*

    * *git branch* - вывод веток

    * *git branch 'name_of_file'* - создание новой ветки

    * *git checkout 'name_of_branch'* - переключение с одной ветки на другую (указывается имя той ветки, на которую нужно переключиться)

    * *git merge 'name _of_branch'* - слияние веток
    
    * *git -d 'name_of_branch'* - удаление ветки

    * *git log --grapg* - графическое представление ветвления. *Важно!*: левая ветка главнее правой!

2. *__Слияние. Виды слияний.__*

    Существует 3 вида слияний:

    1. *Fast-forward* - дополнительная ветка ушла вперед по кмммитам относительно базовой. При таком слияниее не может быть конфликтов. 

    2. *Ort strategy* - изменение в базовой ветке. Коммит создается автоматически.

    3. Явное слияние - слияние, когда обе ветки содержат изменения, что создает конфликты.

3. *__Конфликты. Разрешение конфликтов.__*

    *Конфликт* - разница при слиянии между одинаковыми строками в ветках, содержащими разную информацию.

    * accept current master - остается информация из базо   вой ветки;

    * accept incoming change - остается информация из   дополнительной ветки;

    * accept both changes - остаются оба варианта;

    * compare changes - сравниваются оба варианта (удобно при большом объеме сравниваемой информации).

## 4.Работа с удаленными депозиториями.

1. Основные команады:
    * git clone - копирование удаленного депозитория на локальный компьютер;
    * cd - смена директории;
    * git remote - новый удаленный депозиторий;
    * git push - отправка с локального компьбтера на удаленный депозиторий;
    * git pull - скачивание с удаленного депозитория на локальный компьютер.

2. Загрузка с локального компьютера на удаленный:
    1) создаем аккаунт на GitHub;
    2) создаем локальный депозиторий;
    3) подгружаем локальный депозиторий к удаленному;
    4) отправляем (push) локальный депозиторий в удаленный, при этом , возможно, придется авторизоваться на удаленном депозитории;
    5) проводим изменения с другого компьютера;
    6) скачиваем (pull) актуальное состояние с удаленного депозитория на локалный компьютер.

3. Работа с чужим депозиторием:
    1) fork интересующего нас депозитория;
    2) git clone для нашей версии депозитория;
    3) создаем ветку, в которую будет вносить предлагаемые изменения;
    4) производим все изменения только в этой ветке;
    5) отправляем (push) эти изменения в свой аккаунт;
    6) Появляется возможность отправить pull request с предлагаемыми изменениями автору.





