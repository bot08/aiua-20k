# [Huggingface](https://huggingface.co/datasets/Kidala/aiua-20k)

# aiua-20k – Інструктивний датасет

**aiua-20k** — це датасет, що містить **20 000 згенерованих інструктивних діалогів**. Діалоги мають складну багатокрокову структуру: окрім базових пар «питання — відповідь», деякі з них продовжуються додатковими уточненнями та репліками, що дозволяє моделі вести розгорнуту розмову.

**Генерація:**  
Всі відповіді та продовження діалогів згенеровані за допомогою сучасних мовних моделей із використанням спеціально розроблених інструкцій. **Вартість генерації цього датасету становить приблизно 300$.**

**Різноманітність тем:**  
У датасеті представлено приблизно **500 різних тем**, що дозволяє охопити широкий спектр запитань та відповідей.

<details>
  <summary>Список тем (тик)</summary>
  ```
  "processed_topics": [
    "Розмова (привітання, прощання, базові речі)",
    "Кухня",
    "Українські телепередачі",
    "Погода і пори року",
    "Сім'я та родинні стосунки",
    "Подорожі Україною",
    "Громадський транспорт",
    "Шопінг",
    "Здоров'я та медицина",
    "Спорт і фізична активність",
    "Навчання та освіта",
    "Робота та кар'єра",
    "Хобі та дозвілля",
    "Національні свята",
    "Домашні тварини",
    "Мистецтво та культура",
    "Музика та концерти",
    "Кіно та театр",
    "Література та книги",
    "Інтернет та технології",
    "Соціальні мережі",
    "Інтернет знаменитості",
    "Екологія та довкілля",
    "Політика та суспільство",
    "Новини та актуальні події",
    "Фінанси та банківські послуги",
    "Житло та нерухомість",
    "Ремонт та облаштування",
    "Мода та стиль",
    "Краса та догляд",
    "Спортивні події",
    "Ресторани та кафе",
    "Дитячий розвиток",
    "Виховання дітей",
    "Університетське життя",
    "Шкільне навчання",
    "Курси та самоосвіта",
    "Іноземні мови",
    "Англійська мова",
    "Французька мова",
    "Японська мова",
    "Подорожі за кордон",
    "Подорожі в США, Японію та Китай. Аеропорт та авіаперельоти",
    "Готелі та проживання",
    "Екскурсії та туризм",
    "Міський транспорт",
    "Таксі та перевезення",
    "Залізничний транспорт",
    "Автобусні перевезення",
    "Продуктові магазини",
    "Торгові центри",
    "Ринки та базари",
    "Аптеки та ліки",
    "Лікарні та клініки",
    "Стоматологія",
    "Шкільні предмети",
    "Вступ до університету",
    "Студентське життя",
    "Гуртожиток",
    "Іспити та заліки",
    "Пошук роботи",
    "Співбесіда",
    "Офісне життя",
    "Професійний розвиток",
    "Бізнес та підприємництво",
    "Малювання",
    "Фотографія",
    "Музичні інструменти",
    "Танці",
    "Рукоділля",
    "Колекціонування",
    "Різдво",
    "Великдень",
    "День Незалежності",
    "Весілля",
    "Хрестини",
    "Поминки",
    "Іменини",
    "День народження",
    "Собаки",
    "Коти",
    "Птахи",
    "Акваріумні рибки",
    "Гризуни",
    "Музеї",
    "Галереї",
    "Виставки",
    "Українська музика",
    "Класична музика",
    "Сучасна музика",
    "Фестивалі",
    "Українське кіно",
    "Зарубіжне кіно",
    "Документальне кіно",
    "Анімація",
    "Аніме",
    "Манга",
    "Манхва та маньхуя",
    "Хентай (визначення)",
    "Опера",
    "Балет",
    "Світова література",
    "Поезія",
    "Дитяча література",
    "Комп'ютери",
    "Смартфони",
    "Планшети",
    "Консолі (PS4, PS5, Xbox, switch) та програмне забезпечення",
    "Інтернет-безпека",
    "Facebook",
    "Instagram",
    "Twitter",
    "TikTok",
    "YouTube",
    "Забруднення довкілля",
    "Переробка відходів",
    "Енергозбереження",
    "Захист тварин",
    "Зміна клімату",
    "Вибори",
    "Місцеве самоврядування",
    "Громадські організації",
    "Волонтерство",
    "Міжнародні відносини",
    "Телевізійні новини",
    "Інтернет-новини",
    "Банківські рахунки",
    "Кредити",
    "Страхування",
    "Інвестиції",
    "Криптовалюти",
    "Оренда житла",
    "Купівля нерухомості",
    "Іпотека",
    "Комунальні послуги",
    "ОСББ",
    "Електрика",
    "Сантехніка",
    "Меблі",
    "Будівельні матеріали",
    "Дизайн інтер'єру",
    "Вирощування овочів",
    "Фруктові дерева",
    "Квіти та рослини",
    "Компостування",
    "Теплиці",
    "Одяг",
    "Взуття",
    "Аксесуари",
    "Ювелірні вироби",
    "Чоловіча мода",
    "Жіноча мода",
    "Дитяча мода",
    "Макіяж",
    "Спа-процедури",
    "Олімпійські ігри",
    "Чемпіонати світу",
    "Місцеві змагання",
    "Спортивні клуби",
    "Українська кухня",
    "Європейська та американська кухня",
    "Азійська кухня",
    "Здорове харчування",
    "Дитячі садки",
    "Школи",
    "Позашкільна освіта",
    "Розвиваючі гуртки",
    "Дитячі табори",
    "Психологія",
    "Самопізнання",
    "Стрес-менеджмент",
    "Особистісний розвиток",
    "Тайм-менеджмент",
    "Медитація",
    "Духовність",
    "Релігія",
    "Філософія",
    "Етика",
    "Історія України",
    "Світова історія",
    "Географія",
    "Фізика",
    "Хімія",
    "Біологія",
    "Математика",
    "Інформатика",
    "Економіка",
    "Соціологія",
    "Педагогіка",
    "Юриспруденція",
    "Медицина",
    "Фармацевтика",
    "Ветеринарія",
    "Архітектура",
    "Інженерія",
    "Авіація",
    "Космонавтика",
    "Військова справа",
    "Поліція",
    "Пожежна безпека",
    "Надзвичайні ситуації",
    "Перша допомога",
    "Безпека життєдіяльності",
    "Правила дорожнього руху",
    "Водіння автомобіля",
    "Велосипедний рух",
    "Пішохідний рух",
    "Правила поведінки в громадських місцях",
    "Етикет",
    "Діловий етикет",
    "Мережевий етикет",
    "Конфліктологія",
    "Переговори",
    "Публічні виступи",
    "Ораторське мистецтво",
    "Акторська майстерність",
    "Сценарна справа",
    "Журналістика",
    "Копірайтинг",
    "Реклама",
    "Маркетинг",
    "Зв'язки з громадськістю",
    "Соціальна робота",
    "Благодійність",
    "Громадянська позиція",
    "Патріотизм",
    "Міжкультурна комунікація",
    "Міграція",
    "Українська діаспора",
    "Національні меншини",
    "Мовна політика",
    "Культурна спадщина",
    "Комп'ютерні ігри",
    "Ігри на телефоні",
    "Гача ігри",
    "Азартні елементи в іграх",
    "Genshin Impact",
    "Персонажі Genshin Impact, Honkai star rail",
    "Ігри серії Souls",
    "Темне фентезі",
    "Жанри комп'ютерних ігор",
    "Смішні моменти в іграхІнтернет меми",
    "Анекдоти",
    "Стрімінг ігор",
    "Кіберспорт",
    "Speedrun (В іграх)",
    "Геймерське обладнання",
    "Українська в іграх",
    "Допомога написати дотепний коментар у Facebook",
    "Редагування caption для Instagram",
    "Перефразування агресивного коментаря",
    "Створення вірусного твіту",
    "Написання привабливого статусу в соцмережі",
    "Переклад молодіжного сленгу літературною мовою",
    "Допомога зробити повідомлення більш зрозумілим",
    "Прибрати з тексту забагато сленгу",
    "Створити жартівливий діалог у месенджері",
    "Пояснити значення складного інтернет-мему",
    "Перетворити SMS-повідомлення на літературний текст",
    "Допомога з правильним використанням emoji",
    "Перевірка правильності інтернет-скорочень",
    "Створення креативного повідомлення з emoji",
    "Пояснення значення незрозумілих скорочень",
    "Редагування тексту для побачення в додатку знайомств",
    "Допомога написати привітне повідомлення",
    "Перевірка тексту на грубощі",
    "Створення цікавої самопрезентації в профілі",
    "Підготовка повідомлення до важливої розмови",
    "Допомога скласти дотепний мем",
    "Переклад гумору з одного інтернет-середовища в інше",
    "Редагування жарту для кращого сприйняття",
    "Створення коміксного діалогу",
    "Пояснення складного інтернет-жарту",
    "Написання привітання в групі",
    "Допомога скласти привітання стріммеру",
    "Редагування тексту для форуму геймерів",
    "Створення дружнього повідомлення в чаті",
    "Підготовка тексту для онлайн-знайомства",
    "Придумати назву для YouTube-каналу",
    "Створити креативний нік для гри",
    "Допомога з написанням опису відео",
    "Редагування біографії в соцмережі",
    "Підбір hashtag для поста",
    "Пояснення складного технічного терміну",
    "Переклад IT-сленгу зрозумілою мовою",
    "Редагування повідомлення в технічній підтримці",
    "Допомога описати технічну проблему",
    "Crear короткий опис додатку",
    "Написання привітання в грі",
    "Допомога скласти дотепне повідомлення в чаті гри",
    "Редагування реплік для рольової гри",
    "Створення презентації геймерського профілю",
    "Пояснення ігрового сленгу",
    "Допомога написати кумедний діалог",
    "Створення короткого оповідання в стилі меседжера",
    "Редагування тексту в стилі інтернет-спілкування",
    "Написання історії через переписку",
    "Трансформація ділового тексту в неформальний",
    "Перевірка граматики та орфографії",
    "Перефразування тексту",
    "Скорочення довгого тексту",
    "Розширення короткого тексту",
    "Покращення стилю письма",
    "Переклад тексту (без Google Translate)",
    "Допомога з написанням офіційного листа",
    "Створення професійного резюме",
    "Редагування супровідного листа",
    "Написання відгуку на товар",
    "Перевірка тексту на плагіат",
    "Написання сценарію для відео",
    "Генерація тексту для сторінки про компанію",
    "Написання посту для Facebook",
    "Допомога скласти опис для Instagram-профілю",
    "Редагування тексту для реклами",
    "Написання опису до відео YouTube",
    "Допомога створити цікавий блоговий пост",
    "Редагування тексту для сторінки сайту",
    "Перефразування складних речень",
    "Допомога скласти текст для оголошення про подію",
    "Написання тексту для email-розсилки",
    "Допомога написати текст для конкурсу",
    "Переписати офіційний текст у дружньому тоні",
    "Редагування тексту для розділу FAQ",
    "Створення опису чайної церемонії (покроковий процес)",
    "Пояснення традиції ханамі (планування пікніку)",
    "Створення привітання з китайським новим роком (традиційні фрази)",
    "Створення плану святкування Дівалі (традиційні елементи)",
    "Допомога з вибором спецій для карі (автентичний смак)",
    "Аналіз мудр в йозі (значення та застосування)",
    "Пояснення символіки мехенді (весільні традиції)",
    "Допомога з базовими кроками сальси (для початківців)",
    "Створення плейлисту латинських ритмів (різні стилі)",
    "Аналіз слов'янських оберегів (значення символів)",
    "Пояснення традицій Івана Купала (обрядові елементи)",
    "Створення весільного короваю (символіка прикрас)",
    "Створення стратегії для покеру (базові принципи для новачка)",
    "Аналіз тактики в Dota 2 (розбір командної гри)",
    "Створення меню на тиждень (швидкі рецепти)",
    "Аналіз помилок у випічці (чому не вдалося)",
    "Створення рецепту смузі (з доступних фруктів)",
    "Створення плану прибирання (щоденні задачі)",
    "Аналіз витрат (оптимізація бюджету)",
    "Написання правил Discord сервера (зробити цікавими та зрозумілими)",
    "Створення welcome message (додати емодзі та теплоти)",
    "Допомога з текстом для bot commands (зробити інтуїтивними)",
    "Написання оголошення для voice channel (коротко та інформативно)",
    "Створення ролей для серверу (креативні назви)",
    "Допомогти переписати з капса на звичайний регістр",
    "Допомога налаштувати новий комп'ютер (перший запуск)",
    "Створення системи папок для організації файлів (зручна структура)",
    "Аналіз роботи антивірусу (які налаштування важливі)",
    "Допомога з очисткою диску С (що можна видалити)",
    "Створення резервної копії важливих файлів (різні методи)",
    "Допомога з налаштуванням батьківського контролю (Windows 11)",
    "Створення різних користувачів на комп'ютері (права доступу)",
    "План оптимізації автозапуску (прискорення роботи)",
    "Аналіз проблем з оновленнями Windows (типові помилки)",
    "Налаштування віддаленого доступу (безпечне підключення)",
    "Допомога перенести дані на новий телефон (різні способи)",
    "Створення системи бекапу для смартфону (автоматизація)",
    "Аналіз батареї телефону (збільшення часу роботи)",
    "План очистки пам'яті телефону (що займає місце)",
    "Налаштування батьківського контролю на планшеті (обмеження)",
    "Допомога підключити новий принтер (налаштування wifi)",
    "Створення інструкції для сканера (всі функції)",
    "Аналіз проблем з мишкою (калібрування та налаштування)",
    "Налаштування веб-камери для стрімінгу (якість картинки)",
    "План вибору та налаштування клавіатури (ергономіка)",
    "Допомога встановити офісні програми (базовий пакет)",
    "Створення інструкції по Paint (базові функції)",
    "Аналіз різних браузерів (який кращий для чого)",
    "План налаштування Zoom (для онлайн навчання)",
    "Допомога з налаштуванням Photoshop (початковий рівень)",
    "Допомога налаштувати домашній wifi (захист та швидкість)",
    "Створення інструкції по VPN (безпечне користування)",
    "Аналіз швидкості інтернету (як покращити)",
    "План налаштування роутера (оптимальні параметри)",
    "Допомога з DNS налаштуваннями (швидший інтернет)",
    "Створення надійних паролів (система запам'ятовування)",
    "Допомога з двофакторною автентифікацією (різні методи)",
    "Аналіз фішингових листів (як розпізнати)",
    "План захисту від вірусів (безкоштовні методи)",
    "Налаштування брандмауера Windows (важливі правила)",
    "Допомога налаштувати розумну лампу (через телефон)",
    "Створення сценаріїв для розумного дому (автоматизація)",
    "Аналіз розумних розеток (економія електрики)",
    "План підключення розумної колонки (голосові команди)",
    "Налаштування розумного термостату (режими роботи)",
    "Допомога налаштувати розумний годинник (всі функції)",
    "Створення інструкції для фітнес-браслету (відстеження сну)",
    "Аналіз роботи AirPods (підключення та функції)",
    "План використання електронної книги (формати файлів)",
    "Налаштування ігрової консолі (перший запуск)",
    "Допомога налаштувати домашній кінотеатр (звук та відео)",
    "Створення інструкції для Smart TV (всі можливості)",
    "Аналіз роботи медіаплеєра (різні формати)",
    "План налаштування караоке системи (підключення)",
    "Допомога з bluetooth колонкою (режими роботи)",
    "Допомога спекти круасани (пошарове тісто, техніка)",
    "Створення ідеального бісквіту (вологий та пухкий)",
    "Аналіз помилок у приготуванні макарунів (температурний режим)",
    "План приготування хліба на заквасці (годування закваски)",
    "Допомога з карамельними прикрасами (робота з цукром)",
    "Створення ідеального стейку (ступені просмаження)",
    "Допомога з приготуванням рамену (бульйон та локшина)",
    "Допомога з приготуванням карі удона (бульйон та локшина)",
    "Аналіз техніки приготування різото (консистенція)",
    "План приготування качки по-пекінськи (хрустка шкірка)",
    "Техніка приготування ідеального суфле (як досягти повітряної текстури)",
    "Створення домашньої пасти (різні форми та соуси)",
    "Допомога розібрати фільм 'Початок' (теорії та символи)",
    "Створення хронології фільмів Marvel (порядок перегляду)",
    "Аналіз символізму у фільмі 'Паразити' (соціальні теми)",
    "План марафону фільмів Тарковського (підготовка до перегляду)",
    "Допомога зрозуміти 'Твін Пікс' (теорії та пояснення)",
    "Створення підбірки серіалів як 'Чорне дзеркало' (технологічні антиутопії)",
    "Допомога вибрати корейську дораму (по жанрах)",
    "Аналіз всесвіту 'Доктора Хто' (з чого почати)",
    "План перегляду 'Картковий будинок' (важливі сюжетні лінії)",
    "Створення списку серіалів для вивчення мови (з субтитрами)",
    "Допомога вибрати перше аніме (для новачків)",
    "Створення підбірки психологічного аніме (глибокий сюжет)",
    "Аналіз символізму в 'Євангеліоні' (філософський підтекст)",
    "План перегляду всесвіту 'Fate' (хронологічний порядок)",
    "Допомога зрозуміти 'Serial Experiments Lain' (теорії)",
    "Створення prompt для ChatGPT (ефективні запити)",
    "Допомога зрозуміти різницю між ШІ моделями (GPT, Claude, Bard)",
    "Аналіз можливостей Midjourney (створення зображень)",
    "План використання ШІ для навчання (корисні інструменти)",
    "Допомога з налаштуванням локального ШІ (установка моделей)",
    "Створення персонального асистента з ШІ (щоденні задачі)",
    "Допомога з використанням ШІ для письма (покращення тексту)",
    "Аналіз ШІ для обробки фото (популярні додатки)",
    "План використання ШІ для бізнесу (автоматизація)",
    "Створення музики за допомогою ШІ (доступні інструменти)",
    "Допомога створити веганський сир (з горіхів)",
    "Створення кето-десертів (без цукру)",
    "Аналіз безглютенової випічки (заміна борошна)",
    "План харчування при діабеті (контроль цукру)",
    "Допомога з raw-десертами (без випічки)",
    "Створення таймлайну 'Темряви' (всі часові лінії)",
    "Допомога розібрати 'Станція Одинадцять' (символізм)",
    "Аналіз всесвіту 'Дюни' (книги та екранізації)",
    "План перегляду Кіновсесвіту DC (включно з серіалами)",
    "Створення теорій про 'Людину-павука 4' (можливі сюжети)",
    "Допомога зрозуміти етичні проблеми ШІ (основні питання)",
    "Створення гайду по безпечному ШІ (правила використання)",
    "Аналіз впливу ШІ на професії (майбутні зміни)",
    "План підготовки до епохи ШІ (необхідні навички)",
    "Допомога відрізнити ШІ контент (характерні ознаки)",
    "Розмова з техпідтримкою (ШІ грає оператора або клієнта, вирішує проблему з пристроєм чи сервісом.)",
    "Поліційний допит (ШІ виступає як слідчий або підозрюваний, моделює розслідування.)",
    "Лікарський прийом (ШІ грає лікаря або пацієнта, обговорює симптоми, діагноз, лікування.)",
    "Знайомство з новими людьми (ШІ допомагає вміло підтримати small talk, розвинути розмову.)",
    "Романтичне побачення (ШІ імітує діалог під час побачення, допомагає знайти тему для розмови.)",
    "Переконання когось у чомусь (ШІ тренує аргументацію та навички впливу на співрозмовника.)",
    "Рольова гра в історичному сетингу (ШІ відтворює діалог у різних історичних епохах.)",
    "Перемовини під час конфлікту (ШІ допомагає знайти рішення в конфліктній ситуації.)",
    "Презентація проєкту (ШІ імітує презентацію перед інвесторами або командою.)",
    "Візит до магазину (ШІ грає продавця або покупця, допомагає вибрати товар.)",
    "Дебати на актуальну тему (ШІ модерує або бере участь у дебатах, висловлює аргументи.)",
    "Розмова з іноземцем (ШІ імітує носія мови, допомагає тренувати комунікаційні навички.)",
    "Рольова гра в жанрі фентезі або sci-fi (ШІ створює унікальний світ, NPC та діалоги.)",
    "Визначення емоційного забарвлення тексту (Аналіз емоцій у тексті – позитивні, негативні, нейтральні, саркастичні, гнівні, сумні тощо.). Ситуація: користувач залишив негативний відгук на службу доставки.",
    "Розпізнавання сарказму в тексті (Визначення, чи містить текст приховану іронію або насмішку.). Ситуація: коментар під відео політика: 'О, так, чудова реформа, тепер ми точно заживемо!'",
    "Аналіз рівня агресії в тексті (Виявлення ознак ворожості, образ чи загроз.). Ситуація: переписка у соціальних мережах між двома конфліктуючими користувачами.",
    "Визначення рівня ентузіазму (Перевірка, наскільки текст звучить натхненно, збуджено або піднесено.). Ситуація: рекламний пост про новий смартфон.",
    "Аналіз емоційного тиску в тексті (Визначення, чи містить текст маніпулятивні фрази, які викликають провину, страх або тривогу.). Ситуація: повідомлення шахраїв про виграш у лотерею.",
    "Перевірка тексту на сум і депресивність (Виявлення ознак песимістичних думок, емоційної втоми або апатії.). Ситуація: пост у блозі про розставання з близькою людиною.",
    "Визначення страху та тривоги (Перевірка тексту на присутність виразів, що свідчать про занепокоєння чи паніку.). Ситуація: новинна стаття про можливу економічну кризу.",
    "Виявлення радості та щастя (Оцінка тексту на наявність позитивних емоцій, таких як радість, вдячність, захоплення.). Ситуація: пост про перемогу у конкурсі.",
    "Аналіз романтичності тексту (Перевірка тексту на наявність романтичного настрою, ніжності, прихильності.). Ситуація: повідомлення у додатку для знайомств.",
    "Виявлення ностальгії (Аналіз тексту на відтінки спогадів, суму за минулим, теплої меланхолії.). Ситуація: історія користувача про шкільні роки.",
    "Перевірка рівня мотивації у тексті (Чи містить текст слова підтримки, натхнення, заклики до дії?). Ситуація: промова тренера перед фінальним матчем.",
    "Аналіз почуття провини у тексті (Визначення, чи викликає текст почуття вини або змушує відчувати відповідальність.). Ситуація: лист-прохання від благодійної організації.",
    "Розпізнавання зневаги та зверхності (Аналіз тексту на ознаки презирливого або зневажливого ставлення до когось.). Ситуація: рецензія на книгу, в якій автор висміює стиль написання.",
    "Виявлення емоційної нестабільності (Аналіз змін настрою в тексті – від радісного до сумного або від спокійного до агресивного.). Ситуація: емоційний допис у соцмережах після сварки.",
    "Перевірка співчуття та емпатії в тексті (Аналіз, наскільки текст виражає розуміння та підтримку почуттів інших людей.). Ситуація: коментар користувача до історії про втрату домашнього улюбленця.",
    "Аналіз розчарування та безнадії (Виявлення ознак зневіри, втрати мотивації, безвиході.). Ситуація: пост про невдалий іспит у студента.",
    "Перевірка гумору та жартівливості (Визначення, чи містить текст комедійні елементи, гру слів або доброзичливий гумор.). Ситуація: стендап-виступ коміка.",
    "Визначення шоку та здивування (Перевірка тексту на вираження несподіваних, шокуючих або вражаючих емоцій.). Ситуація: людина дізналася несподівану новину.",
    "Аналіз вдячності та визнання (Чи містить текст слова подяки та позитивне ставлення до адресата?). Ситуація: подячний лист вчителю від випускника.",
    "Виявлення ревнощів та заздрості (Аналіз тексту на ознаки незадоволеності успіхами інших, прихованого або явного порівняння.). Ситуація: людина коментує пост про чиюсь подорож на Мальдіви.",
    "Написання наукової статті про нейронні мережі",
    "Створення технічного опису інноваційного пристрою",
    "Підготовка опису алгоритму машинного навчання",
    "Розробка технічного завдання для IT-проєкту",
    "Написання експертного висновку з кібербезпеки",
    "Написання репортажу про локальну подію",
    "Створення podcast-сценарію",
    "Розробка структури документального фільму",
    "Написання блог-посту про подорожі",
    "Створення серії інтерв'ю з місцевими експертами",
    "Написання щоденника саморефлексії",
    "Створення плану особистісного коучингу",
    "Розробка стратегії подолання професійного вигорання",
    "Написання автобіографічного есе",
    "Створення персонального маніфесту",
    "Світові епідемії та їхні наслідки",
    "Космічні технології майбутнього (колонізація планет, космічний туризм, терраформування)",
    "Біотехнології та їх вплив на медицину (створення штучних органів, генна терапія, біопринтери)",
    "Штучний інтелект у мистецтві (AI-музика, AI-живопис, AI-література)",
    "Екологічні інновації (відновлювані джерела енергії, біорозкладні матеріали, еко-міста)",
    "Віртуальна реальність у повсякденному житті (VR-навчання, VR-терапія, VR-подорожі)",
    "Квантові комп'ютери та їх застосування (квантові алгоритми, шифрування, моделювання)",
    "Роботи в побуті (домашні роботи, роботи-доглядальники, роботи-кухарі)",
    "Тренди в освіті (онлайн-навчання, гейміфікація, персоналізовані програми)",
    "Майбутнє транспорту (електромобілі, автономні автомобілі, гіперлуп)",
    "Цифрова економіка (криптовалюти, NFT, блокчейн)",
    "Модифікація тіла людини (біонічні протези, імпланти, чипи)",
    "Сучасні методи боротьби зі старінням (біологічні дослідження, антиейджінг-терапії)",
    "Майбутнє харчування (лабораторне м'ясо, вертикальні ферми, їжа з 3D-принтера)",
    "Інтернет речей (розумний дім, розумні міста, IoT-пристрої)",
    "Кібербезпека в епоху цифрових загроз (захист даних, боротьба з кібератаками)",
    "Соціальні мережі нового покоління (децентралізовані платформи, метавсесвіт)",
    "Майбутнє розваг (інтерактивні фільми, віртуальні концерти, AR-ігри)",
    "Відомі блогери про технології (топ-імена, їхні канали, контент-стратегії)",
    "Тренди YouTube у сфері технологій (відеоформати, теми, які зараз на піку)",
    "Популярні відеоблогери про IoT (інтернет речей) та їхні проекти",
    "Як технологічні блогери впливають на ринок (рекомендації, рейтинги)",
    "Які відеоформати зараз на піку популярності на YouTube (2023 рік)",
    "Найпопулярніші TikTok-челленджі 2023 року (як до них приєднатися)",
    "Найвідоміші стрімери Twitch у 2023 році (хто вони і в що грають)",
    "Хто такі вітюбери. Топ-5 вітюберів",
    "Найпопулярніші відео про DIY та рукоділля (2023 рік)",
    "Які блогери зараз лідерять у сфері мотивації та натхнення",
    "Тренди YouTube: який контент про музику зараз популярний",
    "Найвідоміші блогери, які знімають контент про спорт та активний відпочинок",
    "Найпопулярніші блогери, які знімають контент про аніме та мангу",
    "Які відео про подорожі зараз набирають мільйони переглядів",
    "Тренди YouTube: який контент про книги зараз популярний",
    "Знайомство: як представити себе та почати розмову",
    "Подорожі: обговорення планів, маршрутів та вражень",
    "Ресторани: як замовити страву, обговорити меню та дати чайові",
    "Як обговорити плани на майбутнє (особисті цілі, мрії, амбіції)",
    "Обговорення сімейних традицій та звичаїв",
    "Як підтримати розмову про книги та літературу",
    "Обговорення подорожей: улюблені місця, поради, враження",
    "Як обговорити проблеми екології та способи їх вирішення",
    "Обговорення святкування днів народження та інших важливих дат",
    "Обговорення здорового способу життя: дієти, тренування, звички",
    "Як підтримати розмову про події в місті (виставки, концерти, фестивалі)",
    "Як обговорити плани на літо (подорожі, відпочинок, активності)",
    "Обговорення улюблених ігор (настільні, відеоігри, спортивні)",
    "Обговорення найнезвичайніших професій (наприклад, дегустатор морозива)",
    "Якби ви могли жити в будь-якій історичній епосі, яку б ви обрали?",
    "Обговорення найцікавіших міських легенд (наприклад, про привидів у вашому місті)",
    "Якби ви могли створити власну країну, які закони та традиції вона б мала?",
    "Як обрати процесор для ігор та роботи з графікою",
    "Яка відеокарта підійде для 4K-ігор та відеомонтажу",
    "Як вибрати материнську плату під ваші потреби",
    "SSD чи HDD: що обрати для швидкості та обсягу пам'яті",
    "Як обрати компоненти для ПК у 2023 році: актуальні тренди",
    "Як зібрати ПК для монтажу відео: потужність та продуктивність",
    "Як обрати компоненти для ПК під Linux",
    "Як зібрати ПК для штучного інтелекту та машинного навчання",
    "Найкращі місця для подорожей в Україні: куди поїхати?",
    "Як українська мова вплинула на інші слов'янські мови?",
    "Як працює Євросоюз: основні принципи та структура",
    "Найцікавіші європейські міста для подорожей",
    "Як країни ЄС співпрацюють у сфері екології?",
    "Європейська культура: що об'єднує країни ЄС?",
    "Як Євросоюз впливає на економіку країн-членів?",
    "Найвідоміші європейські фестивалі та свята",
    "Як працює Шенгенська зона: переваги та виклики",
    "Україна та Євросоюз",
    "Україномовний датасет назва: aiua-20k (цей датасет один з тих, на яких навчана мережа)"
  ]
  ```
  </details>

**Ліцензія:**  
Датасет надається **лише для некомерційного використання**. Будь-яке комерційне застосування заборонене без спеціального дозволу.

**Джерела:**  
- Синтетично згенеровані діалоги за допомогою сучасних мовних моделей.  

---


# aiua-20k – A Instructive Dataset

**aiua-20k** is a dataset containing **20,000 generated instructive dialogues**. The dialogues feature a complex, multi-turn structure: beyond basic question-answer pairs, some conversations include additional clarifications and follow-up responses, enabling models to engage in extended interactions.

**Generation:**  
All responses and dialogue continuations have been generated using state-of-the-art language models guided by specially designed instructions. The **cost of generating this dataset is approximately $300.**

**Diverse Topics:**  
The dataset covers approximately **500 different topics**, offering a wide range of questions and answers across various subject areas.

**License:**  
This dataset is provided **for non-commercial use only**. Any commercial application is prohibited without explicit permission.

**Sources:**  
- Dialogues generated synthetically using advanced language models.
