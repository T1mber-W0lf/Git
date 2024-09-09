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

8.Далі я добавив до основного файлу деякі HTML теги, перевірив стан репозиторію, зафіксував зміни за допомогою команди git commit -m "Added standard HTML page tags" та видалив файл a.html, після цього я перевірив стан репозиторію

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

[screenshots/photo_55_2024-09-09_12-59-49.jpg](https://github.com/T1mber-W0lf/Git/blob/main/screenshots/photo_55_2024-09-09_12-59-49.jpg)

[screenshots/photo_56_2024-09-09_12-59-49.jpg](https://github.com/T1mber-W0lf/Git/blob/main/screenshots/photo_56_2024-09-09_12-59-49.jpg)

12.Далі я перейшов до main та знову змінив файл,і перевірив його зміни та стан репозиторію

[screenshots/photo_44_2024-09-09_12-59-49.jpg](https://github.com/T1mber-W0lf/Git/blob/main/screenshots/photo_44_2024-09-09_12-59-49.jpg)

13. Наступним кроком я змінив файл добавив в нього коментар, повернувся до main, але я відмінив змінення в гіті та перевірив файл, як ви можете побачити, змінення були відхалені

[screenshots/photo_40_2024-09-09_12-59-49.jpg](https://github.com/T1mber-W0lf/Git/blob/main/screenshots/photo_40_2024-09-09_12-59-49.jpg)

14.Я відмінив непрошуваний комміт, та перевірив логи

[screenshots/photo_45_2024-09-09_12-59-49.jpg](https://github.com/T1mber-W0lf/Git/blob/main/screenshots/photo_45_2024-09-09_12-59-49.jpg)

[screenshots/photo_46_2024-09-09_12-59-49.jpg](https://github.com/T1mber-W0lf/Git/blob/main/screenshots/photo_46_2024-09-09_12-59-49.jpg)

15. Наступним кроком я вирішив видалити комміт з вітки за допомогою команди git reset --hard 

[screenshots/photo_57_2024-09-09_12-59-49.jpg](https://github.com/T1mber-W0lf/Git/blob/main/screenshots/photo_57_2024-09-09_12-59-49.jpg)

16. Добавив в файл автора та емаіл, зафіксував за допомогою commit, також щоб не робити багато коммітів, можна використовувати commit --amend -m, тим самим ми змінюємо останній комміт

[screenshots/photo_9_2024-09-09_12-59-49.jpg](https://github.com/T1mber-W0lf/Git/blob/main/screenshots/photo_9_2024-09-09_12-59-49.jpg)

17.Далі я створив гілку style для того, щоб зробити css файл, після того як створив файл, зафіксував зміни

[screenshots/photo_10_2024-09-09_12-59-49.jpg](https://github.com/T1mber-W0lf/Git/blob/main/screenshots/photo_10_2024-09-09_12-59-49.jpg)

18.Для перевірки файлів та для того щоб переключатися між гілками, можна використовувати команду switch

[screenshots/photo_11_2024-09-09_12-59-49.jpg](https://github.com/T1mber-W0lf/Git/blob/main/screenshots/photo_11_2024-09-09_12-59-49.jpg)

19.Також можна перевіряти логи для окремих файлів, і якщо треба переімінувати файл, то можна використовувати команду mv

[screenshots/photo_13_2024-09-09_12-59-49.jpg](https://github.com/T1mber-W0lf/Git/blob/main/screenshots/photo_13_2024-09-09_12-59-49.jpg)

Якщо вам потрібно перемістити один файл з однієї гілки на іншу, можна використовувати git mv де ви вказуэте файл, та каталог в який ви хочете перемістити файл
В моєму випадку я створив каталог з назвою css та перемістив файл style.css до цього каталогу

[screenshots/photo_14_2024-09-09_12-59-49.jpg](https://github.com/T1mber-W0lf/Git/blob/main/screenshots/photo_14_2024-09-09_12-59-49.jpg)

20.Для більш зручнішого перегляду каталогів, я вирішив створити README.txt файл та додав його до main

[screenshots/photo_1_2024-09-09_12-59-49.jpg](https://github.com/T1mber-W0lf/Git/blob/main/screenshots/photo_1_2024-09-09_12-59-49.jpg)

21. Якщо ви хочете передивитися логи для всії гілкок, ви можете використовувати команду git log --all --graph

[screenshots/photo_3_2024-09-09_12-59-49.jpg](https://github.com/T1mber-W0lf/Git/blob/main/screenshots/photo_3_2024-09-09_12-59-49.jpg) 

22.Якщо вам потрібно обїєднати гілки ви можете використовувати команду merge

[screenshots/photo_2_2024-09-09_12-59-49.jpg](https://github.com/T1mber-W0lf/Git/blob/main/screenshots/photo_2_2024-09-09_12-59-49.jpg)

23.Далі я покажу, як може виглядати конфліктне обїєднання гілок, а саме ми повернулися до main, змінили файл та зафіксували зміни, але ця фіксація не була обїеднана
з style гілкою

[screenshots/photo_4_2024-09-09_12-59-49.jpg](https://github.com/T1mber-W0lf/Git/blob/main/screenshots/photo_4_2024-09-09_12-59-49.jpg)

24. Отже, давайте вирішемо цю проблему, можна її вирішити наступним чином: припинити злиття гілок за допомогою git merge --abort, після цього треба перейти в головну(main) гілку та добавити файл, зафіксувати те що ми вирішили з конфліктом, та перевірити стан
Також будьте дуже уважними, оскільки я забув перейти до гілки, та працював в іншій гілці(помітив це коли пишу цей файл)

[screenshots/photo_6_2024-09-09_12-59-49.jpg](https://github.com/T1mber-W0lf/Git/blob/main/screenshots/photo_6_2024-09-09_12-59-49.jpg)

[screenshots/photo_7_2024-09-09_12-59-49.jpg](https://github.com/T1mber-W0lf/Git/blob/main/screenshots/photo_7_2024-09-09_12-59-49.jpg)

25.Якщо вам потрібно збросити якусь гілку, ви можете використовувати команду git reset --hard

[screenshots/photo_26_2024-09-09_12-59-49.jpg](https://github.com/T1mber-W0lf/Git/blob/main/screenshots/photo_26_2024-09-09_12-59-49.jpg)

26.В git э також команда rebase

[screenshots/photo_20_2024-09-09_12-59-49.jpg](https://github.com/T1mber-W0lf/Git/blob/main/screenshots/photo_20_2024-09-09_12-59-49.jpg)

27.Тепер будемо обїєднувати гілки разом, для цього ми будемо використовувати команду merge 

[screenshots/photo_18_2024-09-09_12-59-49.jpg](https://github.com/T1mber-W0lf/Git/blob/main/screenshots/photo_18_2024-09-09_12-59-49.jpg)

28.Далі я створив ще один репозиторій, щоб працювати з декалькіми репозиторіями
