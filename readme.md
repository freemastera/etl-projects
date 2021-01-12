| Проект      | Краткое описание задачи               | Стэк |
| ------------- |:------------------:| -----:|
| Pentaho ETL    | Создать ежедневно запускаемый ETL, который автоматизирует сведение данных из различных источников и форматов, проверку на возможные ошибки и опечатки, загрузку в DWH (используя dimension modeling).  |**ETL** Pentaho<br>**Планировщик** Cron <br>**Источники данных** - MySQL, Postgres(в облаке), json, xml, csv, xls, zip, google sheets|
| ETL из Яндекс-метрики в Postgres    | Ежедневно выгружать данные, необходимые для маркетинговых отчетов из api яндекс метрики,обрабатывать их и загружать в хранилище на PostgreSQL.<br><br> Должна быть возможность подключаться к хранилищу через любые bi инструменты, используемые в компании: tableau, power bi, excel и др. Написать краткую инструкцию для коллег, как это сделать. |**ETL** - Python с библиотеками request, pandas, sqlalchemy <br>**Планировщик** Cron (bash/bat скрипт) <br>**Источники данных** API яндекс метрики. <br>**БД** Postgres 