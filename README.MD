Отчет о выполнении ДЗ№1:

1) Установка на ОС Ubuntu 22.04:
- Развернул ОС Ubuntu 22.04
- Установил ClickHouse используя инструкцию с ресурса https://clickhouse.com/docs/ru/getting-started/install
- Включил доступ к СУБД из сети
- Включил access_management
- Подключился к СУБД посредством DBEvear
- Увеличил таймауты на запрос в свойствах драйвера в DBEvear
- Создал таблицу trips
- Загрузил в нее датасет https://datasets-documentation.s3.eu-west-3.amazonaws.com/nyc-taxi/trips_{0..2}.gz
- Общее количество записей 3 000 317, количество записей с признаком payment_type - 1 850 287 (скриншот прилагаю CH_Lab01_Install_on_Ubuntu)

1) Установка на ОС Ubuntu 22.04 в Docker:
- Развернул ОС Ubuntu 22.04
- Установил Docker и Docker Compose
- Создал файл docker-comose.yml (файл прилагаю), в качестве образа использовал clickhouse/clickhouse-server
- Пробросил порты 9100 и 8123 на материнскую ОС
- Подключился к СУБД посредством DBEvear
- Увеличил таймауты на запрос в свойствах драйвера в DBEvear
- Создал таблицу trips
- Загрузил в нее датасет https://datasets-documentation.s3.eu-west-3.amazonaws.com/nyc-taxi/trips_{0..2}.gz
- Общее количество записей 3 000 317, количество записей с признаком payment_type - 1 850 287 (скриншот прилагаю CH_Lab01_Install_on_Docker)