# Git
В цьому репозиторії я показую як ознайомлювався з Git

1.Отже, розпочнемо з налаштування Git

[screenshots/photo_31_2024-09-09_12-59-49.jpg](https://github.com/T1mber-W0lf/Git/blob/main/screenshots/photo_31_2024-09-09_12-59-49.jpg)

на цьому скрішоті я налаштував Git 

2.Наступним кроком ми створемо папку work та добавимо файл hello.html та впишемо в нього будь-який текст

[screenshots/photo_32_2024-09-09_12-59-49.jpg](https://github.com/T1mber-W0lf/Git/blob/main/screenshots/photo_32_2024-09-09_12-59-49.jpg)

3.Після того як ми створили файл, треба створити репозиторій та добавити файл в репозиторій

[screenshots/photo_33_2024-09-09_12-59-49.jpg](https://github.com/T1mber-W0lf/Git/blob/main/screenshots/photo_33_2024-09-09_12-59-49.jpg)

4.Для того щоб перевірити що файл дійсно в репозиторії, я перейшов до папки work

[screenshots/photo_34_2024-09-09_12-59-49.jpg](https://github.com/T1mber-W0lf/Git/blob/main/screenshots/photo_34_2024-09-09_12-59-49.jpg)

як ви можете побачити, файл дійсно створився та знаходится в репозиторії

5.Наступним кроком ми перевіримо стан самого репозиторія,якщо є якісь не збережені дії, то нам буде показано повідомлення про не збережені дії

[screenshots/photo_35_2024-09-09_12-59-49.jpg](https://github.com/T1mber-W0lf/Git/blob/main/screenshots/photo_35_2024-09-09_12-59-49.jpg)

у моєму випадку все добре, та ніяких не збережених дій немає

6.Я внес деякі зміни в файл,та перевірив стан репозиторію

[screenshots/photo_36_2024-09-09_12-59-49.jpg](https://github.com/T1mber-W0lf/Git/blob/main/screenshots/photo_36_2024-09-09_12-59-49.jpg)

Як ви можете побачити, мені гіт показав, що файл було змінено, для того щоб зберегти зміни, я знову добавив файл до репозиторію

7.Наступним кроком я зробив фіксацію деяких файлів, перед цим я добавив файл a.html до репозиторію, але мені показало повідомлення про те, що інших файлів не існує(а саме файли b.html та c.html), та зафіксував зміни в репозиторії за допомогою комманди git commit

[screenshots/photo_37_2024-09-09_12-59-49.jpg](https://github.com/T1mber-W0lf/Git/blob/main/screenshots/photo_37_2024-09-09_12-59-49.jpg)

8. Далі я добавив до основного файлу деякі HTML теги, перевірив стан репозиторію, зафіксував зміни за допомогою команди git commit -m "Added standard HTML page tags" та видалив файл a.html, після цього я перевірив стан репозиторію

8.1 Збереження змін в файлі:
[screenshots/photo_47_2024-09-09_12-59-49.jpg](https://github.com/T1mber-W0lf/Git/blob/main/screenshots/photo_47_2024-09-09_12-59-49.jpg)

8.2 Перевірка стану репозиторію:
[screenshots/photo_48_2024-09-09_12-59-49.jpg](https://github.com/T1mber-W0lf/Git/blob/main/screenshots/photo_48_2024-09-09_12-59-49.jpg)

8.3 Фіксація змін в репозиторії:
[screenshots/photo_49_2024-09-09_12-59-49.jpg](https://github.com/T1mber-W0lf/Git/blob/main/screenshots/photo_49_2024-09-09_12-59-49.jpg)

8.4 Повторна перевірка стану репозиторію після фіксації:
[screenshots/photo_50_2024-09-09_12-59-49.jpg](https://github.com/T1mber-W0lf/Git/blob/main/screenshots/photo_50_2024-09-09_12-59-49.jpg)

9.Перевірка логів в гіті, виконується за допомогою команди git log, що я і зробив
[screenshots/photo_38_2024-09-09_12-59-49.jpg](https://github.com/T1mber-W0lf/Git/blob/main/screenshots/photo_38_2024-09-09_12-59-49.jpg)
Далі я налаштував логи так, щоб можна було більш комфортніше перевіряти логи

[screenshots/photo_39_2024-09-09_12-59-49.jpg](https://github.com/T1mber-W0lf/Git/blob/main/screenshots/photo_39_2024-09-09_12-59-49.jpg)
[screenshots/photo_43_2024-09-09_12-59-49.jpg](https://github.com/T1mber-W0lf/Git/blob/main/screenshots/photo_43_2024-09-09_12-59-49.jpg)
[screenshots/photo_51_2024-09-09_12-59-49.jpg](https://github.com/T1mber-W0lf/Git/blob/main/screenshots/photo_51_2024-09-09_12-59-49.jpg)

10. Наступним кроком я перевірив старі версії файлів в репозиторії за допомогою команди checkout, та повернувся до main за допомогою команди switch

[screenshots/photo_52_2024-09-09_12-59-49.jpg](https://github.com/T1mber-W0lf/Git/blob/main/screenshots/photo_52_2024-09-09_12-59-49.jpg)

11.Далі я створив теги для версій за домогою tag та перевірив за допомогою команди checkout
Також можна переходити між тегами та так само перевіряти їх

[screenshots/photo_53_2024-09-09_12-59-49.jpg](https://github.com/T1mber-W0lf/Git/blob/main/screenshots/photo_53_2024-09-09_12-59-49.jpg)
[screenshots/photo_54_2024-09-09_12-59-49.jpg](https://github.com/T1mber-W0lf/Git/blob/main/screenshots/photo_54_2024-09-09_12-59-49.jpg)
[screenshots/photo_50_2024-09-09_12-59-49.jpg](https://github.com/T1mber-W0lf/Git/blob/main/screenshots/photo_50_2024-09-09_12-59-49.jpg)

12. Далі я перейшов до main та знову змінив файл,і перевірив його зміни та стан репозиторію

[screenshots/photo_44_2024-09-09_12-59-49.jpg](https://github.com/T1mber-W0lf/Git/blob/main/screenshots/photo_44_2024-09-09_12-59-49.jpg)
