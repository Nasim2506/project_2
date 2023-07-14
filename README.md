# Анализ данных работодателей и вакансий на сайте HH.ru
 
## Краткое описание
 В ходе работы исследовал рынок вакансий в частности на позицию Data-Science 
 ### Для работы были использованы данные базы данных "project_sql",состоящая из 5 таблиц :
 * VACANCIES. Таблица хранит в себе данные по вакансиям
![](https://lms-cdn.skillfactory.ru/assets/courseware/v1/837cf6ff79f483e387a16c993634f3e4/asset-v1:SkillFactory+DST-3.0+28FEB2021+type@asset+block/SQL_pj2_2_2.png)

 * AREAS. Таблица-справочник, которая хранит код города и его название.
![](https://lms-cdn.skillfactory.ru/assets/courseware/v1/682c2306f3d46a25915a89d4ec7e16ed/asset-v1:SkillFactory+DST-3.0+28FEB2021+type@asset+block/SQL_pj2_2_3.png)

* EMPLOYERS. Таблица-справочник со списком работодателей.
![](https://lms-cdn.skillfactory.ru/assets/courseware/v1/d2a26db623c75572c71923b57241e038/asset-v1:SkillFactory+DST-3.0+28FEB2021+type@asset+block/SQL_pj2_2_4.png)

* INDUSTRIES. Таблица-справочник вариантов сфер деятельности работодателей.
![](https://lms-cdn.skillfactory.ru/assets/courseware/v1/2c76bca09937a1a05a9e66d51008e298/asset-v1:SkillFactory+DST-3.0+28FEB2021+type@asset+block/SQL_pj2_2_5.png)

* EMPLOYERS_INDUSTRIES. Дополнительная таблица, которая существует для организации связи между работодателями и сферами их деятельности.
![](https://lms-cdn.skillfactory.ru/assets/courseware/v1/16ff3df0bb0ddecd922562f3c4bdd32c/asset-v1:SkillFactory+DST-3.0+28FEB2021+type@asset+block/SQL_pj2_2_6.png)

## Инстументы использованные в работе

### В процессе работы применил запросы PostgreSQL, а также Python
### Для построения графиков применил библиотеку seaborn


## Результат работы

### В работе были сделаны выводы относительно рынка труда в России в общем, и в частности, касаемо Data-Science 
