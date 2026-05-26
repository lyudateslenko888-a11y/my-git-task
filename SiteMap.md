# Sitemap TELEMART

```mermaid
flowchart LR

%% =========================
%% HOME
%% =========================
Home[Sitemap Telemart.ua]

style Home fill:#1E1E2F,color:#fff,stroke:#6C63FF,stroke-width:3px

%% =========================
%% MAIN NAVIGATION
%% =========================
Home --> Catalog[Каталог]
Home --> Sales[Акції]
Home --> Configurator[Конфігуратор ПК]
Home --> TradeIn[Trade-In]
Home --> Blog[Блог]
Home --> About[Про компанію]
Home --> Contacts[Контакти]

%% =========================
%% COLORS PER MAIN SECTION
%% =========================

%% --- КАТАЛОГ (GREEN)
style Catalog fill:#00B894,color:#fff

Catalog --> B1[Комп'ютери]
Catalog --> B2[Ноутбуки]
Catalog --> B3[Комплектуючі до ПК]
Catalog --> B4[Монітори та телевізори]
Catalog --> B5[Периферія для ПК]
Catalog --> B6[Консольний геймінг]
Catalog --> B7[Мережеве обладнання]
Catalog --> B8[Оргтехніка]
Catalog --> B9[Енергозабезпечення]
Catalog --> B10[Меблі та аксесуари]
Catalog --> B11[Конфігуратор ПК]
Catalog --> B13[Trade in]
Catalog --> B17[Послуги]
Catalog --> B18[Apple]
Catalog --> B19[Акції]
Catalog --> B20[Уцінка/Outlet]

style B1 fill:#00B894,color:#fff
style B2 fill:#6C5CE7,color:#fff
style B3 fill:#E17055,color:#fff
style B4 fill:#0984E3,color:#fff
style B5 fill:#00CEC9,color:#fff
style B6 fill:#D63031,color:#fff
style B7 fill:#6C5CE7,color:#fff
style B8 fill:#FDCB6E,color:#000
style B9 fill:#2D3436,color:#fff
style B10 fill:#E84393,color:#fff
style B11 fill:#00B894,color:#fff
style B13 fill:#636E72,color:#fff
style B17 fill:#FD79A8,color:#fff
style B18 fill:#1E272E,color:#fff
style B19 fill:#FF7675,color:#fff
style B20 fill:#B2BEC3,color:#000

%% --- КОМП'ЮТЕРИ (BLUE)
B1 --> B1A[Швидкий підбір ПК]
B1 --> B1B[Призначення]
B1 --> B1C[Форм-фактор]
B1 --> B1D[По процесору]
B1 --> B1E[За відеокартою]
B1 --> B1F[Послуги для ПК]
B1 --> B1G[Аксесуари для збирання]
B1 --> B1H[Обмін по Trade-in]
B1 --> B1I[Програмне забезпечення]

style B1A fill:#00B894,color:#fff
style B1B fill:#00B894,color:#fff
style B1C fill:#00B894,color:#fff
style B1D fill:#00B894,color:#fff
style B1E fill:#00B894,color:#fff
style B1F fill:#00B894,color:#fff
style B1G fill:#00B894,color:#fff
style B1H fill:#00B894,color:#fff
style B1I fill:#00B894,color:#fff

%% --- НОУТБУКИ (PURPLE)
B2 --> B2A[Призначення]
B2 --> B2B[Форм-фактори]
B2 --> B2C[Ноутбуки по брендам]
B2 --> B2D[Послуги для ноутбуків]
B2 --> B2E[Обмін по Trade-in]
B2 --> B2F[Перифирія для ноутбуків]
B2 --> B2G[Сумки-рюкзаки-чохли]
B2 --> B2H[Програмне забезпечення]

style B2A fill:#6C5CE7,color:#fff
style B2B fill:#6C5CE7,color:#fff
style B2C fill:#6C5CE7,color:#fff
style B2D fill:#6C5CE7,color:#fff
style B2E fill:#6C5CE7,color:#fff
style B2F fill:#6C5CE7,color:#fff
style B2G fill:#6C5CE7,color:#fff
style B2H fill:#6C5CE7,color:#fff

%% --- КОМПЛЕКТУЮЧІ ДО ПК (ORANGE)
B3 --> B3A[Основні компоненти]
B3 --> B3B[Додаткова перифирія для ПК]
B3 --> B3C[Аксесуари для збирання]

style B3A fill:#E17055,color:#fff
style B3B fill:#E17055,color:#fff
style B3C fill:#E17055,color:#fff

%% --- Монітори та телевізори
B4 --> B4A[Монітори по брендам]
B4 --> B4B[Телевізори]
B4 --> B4C[Аксесуари для моніторів]
B4 --> B4D[Добірки моніторів]

style B4A fill:#0984E3,color:#fff
style B4B fill:#0984E3,color:#fff
style B4C fill:#0984E3,color:#fff
style B4D fill:#0984E3,color:#fff

%% --- Перефирія для ПК 
B5 --> B5A[Клавіатури]
B5 --> B5B[Мишки]
B5 --> B5C[Комплекти миша і клавіатура]
B5 --> B5D[Килимки]
B5 --> B5E[Геймпади]
B5 --> B5F[Сімрейсинг та авіасимулятори]
B5 --> B5G[Аудіо]
B5 --> B5H[Відео та стрімінг]
B5 --> B5I[Графічні планшети]

style B5A fill:#00CEC9,color:#fff
style B5B fill:#00CEC9,color:#fff
style B5C fill:#00CEC9,color:#fff
style B5D fill:#00CEC9,color:#fff
style B5E fill:#00CEC9,color:#fff
style B5F fill:#00CEC9,color:#fff
style B5G fill:#00CEC9,color:#fff
style B5H fill:#00CEC9,color:#fff
style B5I fill:#00CEC9,color:#fff

%% --- Консольний геймінг 
B6 --> B6A[Стаціонарні]
B6 --> B6B[Портативні]
B6 --> B6C[Ретроприставки]
B6 --> B6D[Ігри]
B6 --> B6E[Перифирія та аксесуари для консолей]
B6 --> B6F[Телевізори для консолей]

style B6A fill:#D63031,color:#fff
style B6B fill:#D63031,color:#fff
style B6C fill:#D63031,color:#fff
style B6D fill:#D63031,color:#fff
style B6E fill:#D63031,color:#fff
style B6F fill:#D63031,color:#fff

%% --- Мережеве обладнання 
B7 --> B7A[Роутери по брендам]
B7 --> B7B[Роутери за параметрами]
B7 --> B7C[Пасивне]
B7 --> B7D[Активне]

style B7A fill:#6C5CE7,color:#fff
style B7B fill:#6C5CE7,color:#fff
style B7C fill:#6C5CE7,color:#fff
style B7D fill:#6C5CE7,color:#fff

%% --- Оргтехніка 
B8 --> B8A[Пристрої для друку]
B8 --> B8B[Витратні матеріали]
B8 --> B8C[Програмне забезпечення]
B8 --> B8D[Аксесуари для офісу]
B8 --> B8E[Пристрої для робочого місця]

style B8A fill:#FDCB6E,color:#000
style B8B fill:#FDCB6E,color:#000
style B8C fill:#FDCB6E,color:#000
style B8D fill:#FDCB6E,color:#000
style B8E fill:#FDCB6E,color:#000

%% --- Енергозабезпечення 
B9 --> B9A[Все для будинку]
B9 --> B9B[Все для теелфону]
B9 --> B9C[Гібридні інвертори та акумулятори]
B9 --> B9D[Все для ПК]
B9 --> B9E[Все для роутера]

style B9A fill:#2D3436,color:#fff
style B9B fill:#2D3436,color:#fff
style B9C fill:#2D3436,color:#fff
style B9D fill:#2D3436,color:#fff
style B9E fill:#2D3436,color:#fff

%% --- Меблі та аксесуари 
B10 --> B10A[Компютерні столи]
B10 --> B10B[Аксесуари для робочого столу]
B10 --> B10C[Організація та атмосфера робочого місця]
B10 --> B10D[Крісла та стільці]
B10 --> B10E[Аксесуари для крісел]

style B10A fill:#E84393,color:#fff
style B10B fill:#E84393,color:#fff
style B10C fill:#E84393,color:#fff
style B10D fill:#E84393,color:#fff
style B10E fill:#E84393,color:#fff

%% --- ACCOUNT (PINK)
Home --> Account[Особистий кабінет]

Account --> A1[Вхід]
Account --> A2[Реєстрація]
Account --> A3[Мої замовлення]

style Account fill:#FD79A8,color:#fff
style A1 fill:#FD79A8,color:#fff
style A2 fill:#FD79A8,color:#fff
style A3 fill:#FD79A8,color:#fff

%% --- CUSTOMERS (YELLOW)
Home --> Customers[Покупцям]

Customers --> J1[Доставка]
Customers --> J2[Оплата]
Customers --> J3[Гарантія]

style Customers fill:#FDCB6E,color:#000
style J1 fill:#FDCB6E,color:#000
style J2 fill:#FDCB6E,color:#000
style J3 fill:#FDCB6E,color:#000

%% --- STORES (CYAN)
Home --> Stores[Магазини]

Stores --> S1[Київ]
Stores --> S2[Львів]
Stores --> S3[Одеса]

style Stores fill:#00CEC9,color:#fff
style S1 fill:#00CEC9,color:#fff
style S2 fill:#00CEC9,color:#fff
style S3 fill:#00CEC9,color:#fff

%% --- SALES (RED/ORANGE)
Home --> Sales[Акції]

Sales --> C1[Знижки]
Sales --> C2[Black Friday]
Sales --> C3[Розпродаж]

style Sales fill:#FF7675,color:#fff
style C1 fill:#FF7675,color:#fff
style C2 fill:#FF7675,color:#fff
style C3 fill:#FF7675,color:#fff

```
