# Combined Telemart sitemap

```mermaid
flowchart LR
    Home["Sitemap Telemart.ua"]

    Home --> Header["header"]
    Home --> Catalog["Каталог"]
    Home --> Sales["Акції"]
    Home --> Configurator["Конфігуратор ПК"]
    Home --> TradeIn["Trade-In"]
    Home --> Account["Особистий кабінет"]
    Home --> Customers["Покупцям"]
    Home --> Stores["Магазини"]
    Home --> Blog["Блог"]
    Home --> About["Про компанію"]
    Home --> Contacts["Контакти"]
    Home --> Cart["cart"]
    Home --> Footer["footer"]

    Header --> Search["searching field"]
    Header --> Language["language"]
    Header --> Location["Location (choose your location)"]
    Header --> Buyer["buyer"]
    Header --> HeaderStore["store"]
    Header --> Markdown["markdown"]
    Header --> HeaderContact["contact"]

    Search --> PopularCategories["popular categories"]
    Search --> PopularRequests["popular requests"]
    Search --> Product["product"]
    Product --> Buy["buy"]
    Product --> ExchangeTradeIn["exchange trade in"]

    Language --> UA["UA"]
    Language --> RU["RU"]

    Account --> SignIn["sign in"]
    Account --> LogIn["log in"]
    Account --> A1["Вхід"]
    Account --> A2["Реєстрація"]
    Account --> A3["Мої замовлення"]
    Account --> UserMenu["user menu"]
    UserMenu --> MyOrders["my orders"]
    UserMenu --> WishList["wish list"]
    UserMenu --> PCBuilds["PC Builds"]
    UserMenu --> AffiliateProgram["affiliate program"]
    UserMenu --> AdditionalTradeIn["additional trade in"]
    UserMenu --> ViewProduct["View Product"]
    UserMenu --> ServiceReport["Service Report"]

    Buyer --> TrackOrder["track order"]
    Buyer --> Delivery["delivery"]
    Buyer --> Payment["payment"]
    Buyer --> Insurance["insurance"]
    Buyer --> Returns["returns and exchanges"]
    Buyer --> CorporateClients["corporate clients"]
    Buyer --> Feedback["feedback"]
    TrackOrder --> OrderPhone["enter number order and phone number"]
    OrderPhone --> CheckStatus["check status (button)"]
    OrderPhone --> RecallMe["recall me (button)"]

    HeaderStore --> ChooseAddress["choose address(buttons)"]
    Markdown --> ChooseProductCategory["choose product category"]
    Markdown --> ChooseProduct["choose product"]
    HeaderContact --> CreateServiceReport["create Service Report"]

    Customers --> J1["Доставка"]
    Customers --> J2["Оплата"]
    Customers --> J3["Гарантія"]
    Customers --> J4["Відслідкувати замовлення"]
    Customers --> J5["Повернення та обмін товару"]
    Customers --> J6["Корпоративним клієнтам"]
    Customers --> J7["Зворотній зв'язок по роботі сайту"]

    Stores --> StoreKyiv["Київ"]
    Stores --> StoreLviv["Львів"]
    Stores --> StoreOdesa["Одеса"]

    Sales --> SaleDiscounts["Знижки"]
    Sales --> SaleBlackFriday["Black Friday"]
    Sales --> SaleClearance["Розпродаж"]

    Home --> SolutionForGamers["Рішення для геймерів"]
    Home --> SolutionForDesigners["Рішення для дизайнерів"]
    Home --> StreamingSolution["Рішення для стрімінгу"]
    Home --> BusinessSolution["Рішення для бізнесу"]

    Catalog --> B1["Комп'ютери"]
    Catalog --> B2["Ноутбуки"]
    Catalog --> B3["Комплектуючі до ПК"]
    Catalog --> B4["Монітори та телевізори"]
    Catalog --> B5["Периферія для ПК"]
    Catalog --> B6["Консольний геймінг"]
    Catalog --> B7["Мережеве обладнання"]
    Catalog --> B8["Оргтехніка"]
    Catalog --> B9["Енергозабезпечення"]
    Catalog --> B10["Меблі та аксесуари"]
    Catalog --> B11["Конфігуратор ПК"]
    Catalog --> B13["Trade in"]
    Catalog --> B17["Послуги"]
    Catalog --> B18["Apple"]
    Catalog --> B19["Акції"]
    Catalog --> B20["Уцінка/Outlet"]

    B1 --> B1A["Швидкий підбір ПК"]
    B1 --> B1B["Призначення"]
    B1 --> B1C["Форм-фактор"]
    B1 --> B1D["По процесору"]
    B1 --> B1E["За відеокартою"]
    B1 --> B1F["Послуги для ПК"]
    B1 --> B1G["Аксесуари для збирання"]
    B1 --> B1H["Обмін по Trade-in"]
    B1 --> B1I["Програмне забезпечення"]

    B2 --> B2A["Призначення"]
    B2 --> B2B["Форм-фактори"]
    B2 --> B2C["Ноутбуки по брендам"]
    B2 --> B2D["Послуги для ноутбуків"]
    B2 --> B2E["Обмін по Trade-in"]
    B2 --> B2F["Периферія для ноутбуків"]
    B2 --> B2G["Сумки-рюкзаки-чохли"]
    B2 --> B2H["Програмне забезпечення"]

    B3 --> B3A["Основні компоненти"]
    B3 --> B3B["Додаткова периферія для ПК"]
    B3 --> B3C["Аксесуари для збирання"]

    B4 --> B4A["Монітори по брендам"]
    B4 --> B4B["Телевізори"]
    B4 --> B4C["Аксесуари для моніторів"]
    B4 --> B4D["Добірки моніторів"]

    B5 --> B5A["Клавіатури"]
    B5 --> B5B["Мишки"]
    B5 --> B5C["Комплекти миша і клавіатура"]
    B5 --> B5D["Килимки"]
    B5 --> B5E["Геймпади"]
    B5 --> B5F["Сімрейсинг та авіасимулятори"]
    B5 --> B5G["Аудіо"]
    B5 --> B5H["Відео та стрімінг"]
    B5 --> B5I["Графічні планшети"]

    B6 --> B6A["Стаціонарні"]
    B6 --> B6B["Портативні"]
    B6 --> B6C["Ретроприставки"]
    B6 --> B6D["Ігри"]
    B6 --> B6E["Периферія та аксесуари для консолей"]
    B6 --> B6F["Телевізори для консолей"]

    B7 --> B7A["Роутери по брендам"]
    B7 --> B7B["Роутери за параметрами"]
    B7 --> B7C["Пасивне"]
    B7 --> B7D["Активне"]

    B8 --> B8A["Пристрої для друку"]
    B8 --> B8B["Витратні матеріали"]
    B8 --> B8C["Програмне забезпечення"]
    B8 --> B8D["Аксесуари для офісу"]
    B8 --> B8E["Пристрої для робочого місця"]

    B9 --> B9A["Все для будинку"]
    B9 --> B9B["Все для телефону"]
    B9 --> B9C["Гібридні інвертори та акумулятори"]
    B9 --> B9D["Все для ПК"]
    B9 --> B9E["Все для роутера"]

    B10 --> B10A["Комп'ютерні столи"]
    B10 --> B10B["Аксесуари для робочого столу"]
    B10 --> B10C["Організація та атмосфера робочого місця"]
    B10 --> B10D["Крісла та стільці"]
    B10 --> B10E["Аксесуари для крісел"]

    Catalog --> ComputerCategories["computer / product categories"]
    ComputerCategories --> PopularCategories
    ComputerCategories --> Product

    classDef root fill:#1E1E2F,color:#fff,stroke:#6C63FF,stroke-width:3px
    classDef header fill:#1F3A5F,color:#fff,stroke:#1F3A5F
    classDef catalog fill:#00B894,color:#fff,stroke:#008F72
    classDef computer fill:#00B894,color:#fff,stroke:#008F72
    classDef laptop fill:#6C5CE7,color:#fff,stroke:#5141C4
    classDef parts fill:#E17055,color:#fff,stroke:#B94D34
    classDef monitors fill:#0984E3,color:#fff,stroke:#0769B5
    classDef peripherals fill:#00CEC9,color:#fff,stroke:#00A19D
    classDef console fill:#D63031,color:#fff,stroke:#A71F20
    classDef network fill:#6C5CE7,color:#fff,stroke:#5141C4
    classDef office fill:#FDCB6E,color:#000,stroke:#D9A83F
    classDef power fill:#2D3436,color:#fff,stroke:#111
    classDef furniture fill:#E84393,color:#fff,stroke:#B92F72
    classDef account fill:#FD79A8,color:#fff,stroke:#D75C89
    classDef customers fill:#FDCB6E,color:#000,stroke:#D9A83F
    classDef stores fill:#00CEC9,color:#fff,stroke:#00A19D
    classDef sales fill:#FF7675,color:#fff,stroke:#C94D4C
    classDef issue fill:#E15759,color:#111,stroke:#B83A3C
    classDef action fill:#D9EAD3,color:#111,stroke:#93C47D
    classDef navigation fill:#DCE6F1,color:#111,stroke:#9AAFC3

    class Home root
    class Header header
    class Catalog,B11,B13,B17,B18,B19,B20,Configurator,TradeIn catalog
    class B1,B1A,B1B,B1C,B1D,B1E,B1F,B1G,B1H,B1I computer
    class B2,B2A,B2B,B2C,B2D,B2E,B2F,B2G,B2H laptop
    class B3,B3A,B3B,B3C parts
    class B4,B4A,B4B,B4C,B4D monitors
    class B5,B5A,B5B,B5C,B5D,B5E,B5F,B5G,B5H,B5I peripherals
    class B6,B6A,B6B,B6C,B6D,B6E,B6F console
    class B7,B7A,B7B,B7C,B7D network
    class B8,B8A,B8B,B8C,B8D,B8E office
    class B9,B9A,B9B,B9C,B9D,B9E power
    class B10,B10A,B10B,B10C,B10D,B10E furniture
    class Account,SignIn,LogIn,A1,A2,A3,UserMenu,MyOrders,WishList,PCBuilds,AffiliateProgram,AdditionalTradeIn,ViewProduct,ServiceReport account
    class Customers,J1,J2,J3,J4,J5,J6,J7,Buyer,Delivery,Payment,Insurance,Returns,CorporateClients,Feedback customers
    class Stores,StoreKyiv,StoreLviv,StoreOdesa,HeaderStore stores
    class Sales,SaleDiscounts,SaleBlackFriday,SaleClearance sales
    class Location,ChooseAddress,ChooseProductCategory issue
    class Buy,ExchangeTradeIn,OrderPhone,CheckStatus,RecallMe,ChooseProduct,CreateServiceReport,ComputerCategories action
    class Search,PopularCategories,PopularRequests,Product,Language,UA,RU,TrackOrder,Markdown,HeaderContact,Cart,Footer,Blog,About,Contacts,SolutionForGamers,SolutionForDesigners,StreamingSolution,BusinessSolution navigation
```
