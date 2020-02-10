# ФОРМАТОРИ

<p align="center"><b>Нижченаведена інструкція щодо використання розпорядниками інформації Форматорів, викладена на підставі <i><a href="https://data.gov.ua/pages/835-rec-index" target="_blank"> Рекомендацій для оприлюднення наборів відкритих даних</a></i>, розроблених <a href="https://thedigital.gov.ua/" target="_blank"> Міністерством цифрової трансформації України</a> за підтримки проекту <a href="http://tapas.org.ua" target="_blank">«Прозорість та підзвітність у державному управлінні та послугах»</a> виходячи з переліку наборів даних, затвердженого <a href="https://zakon0.rada.gov.ua/laws/show/835-2015-п" target="_blank"> Постановою КМУ № 835</a> щодо «Всіх розпорядників» та щодо «Органів місцевого самоврядування».</b></p>

---

<p align="center"><b>ЗМІСТ</b></p>

* [1. ВВЕДЕННЯ](#1-ВВЕДЕННЯ)
* [2. Стандартна методика використання Форматорів](#2-Стандартна-методика-використання-Форматорів)
* [2.1. Розміщення Форматорів](#21-Розміщення-Форматорів)
* [2.2. Копіювання існуючих заготовок Форматорів на індивідуальні Google диски розпорядників інформації](#22-Копіювання-існуючих-заготовок-Форматорів-на-індивідуальні-Google-диски-розпорядників-інформації)
* [2.3. Розшифровки змісту загальнодоступних архівів (папок) з шаблонами Форматорів](#23-Розшифровки-змісту-загальнодоступних-архівів-папок-з-шаблонами-Форматорів)
* [2.4. Заповнення файлу «IdentificationData» ідентифікаційними даними розпорядника інформації](#24-Заповнення-файлу-IdentificationData-ідентифікаційними-даними-розпорядника-інформації)
* [2.5. Заповнення файлів заготовок Форматорів даними розпорядників інформації](#25-Заповнення-файлів-заготовок-Форматорів-даними-розпорядників-інформації)
* [2.6. Специфічні Форматори](#26-Специфічні-Форматори)
* [2.7. Конвертація даних з листа Форматору «Результуюча таблиця» в окремий CSV або XLSX файл](#27-Конвертація-даних-з-листа-Форматору-Результуюча-таблиця-в-окремий-CSV-або-XLSX-файл)
* [2.8. Файли, що описують табличну структуру ресурсів наборів даних](#28-Файли-що-описують-табличну-структуру-ресурсів-наборів-даних)
* [3. Публікація на порталі data.gov.ua CSV або XLSX файлів, сформованих на основі «Результуючих таблиць» відповідних Форматорів](#3-Публікація-на-порталі-datagovua-CSV-або-XLSX-файлів-сформованих-на-основі-Результуючих-таблиць-відповідних-Форматорів)
* [4. Контакти для технічної підтримки щодо впровадження та функціонування Форматорів](#4-Контакти-для-технічної-підтримки-щодо-впровадження-та-функціонування-Форматорів)
---
## 1. ВВЕДЕННЯ
<p align="justify">Як правило, оприлюднення центральними структурами влади та органами місцевого самоврядування (далі - розпорядниками інформації) потрібних за законодавством відкритих даних пов'язано зі значними трудовитратами, викликаними необхідністю:</p>

* Попереднього формування табличних структур відкритих даних для законодавчо задекларованих або суспільно затребуваних наборів даних.
* Виправлення помилок в даних з подальшим їх занесенням в сформовані табличні структури відповідних наборів даних.
* Оприлюднення вже підготовлених наборів даних, як на Єдиному державному порталі [(data.gov.ua)](https://data.gov.ua), так і на інших централізованих та регіональних порталах відкритих даних.
* Системного поновлення наборів даних на відповідних порталах відкритих даних.

<p align="justify">Тому, для зниження цих трудовитрат необхідна хоча б часткова автоматизація всіх перерахованих вище процесів, яка зокрема може бути здійснена за рахунок використання Форматорів. Форматори представляють собою стандартизовані під ті чи інші набори даних, табличні структури у вигляді Google таблиць, які з одного боку приводять внесені в них дані до однакового виду (усувають типові помилки), а з іншого боку доповнюють ці самі внесені дані заздалегідь асоційованої або один раз введеної інформацією. Таким чином, за рахунок використання Форматорів для тих чи інших наборів даних:</p>

* Виключається необхідність формування табличних структур.
* Приблизно на 80 - 70 відсотків знижується обсяг інформації, що вводиться для первісного оприлюднення, а також для подальшого доповнення та оновлення наборів даних.
* Забезпечується усунення типових помилок, пов'язаних з різним поданням одних і тих же значень (м., місто), зі змішуванням різних форматів (временних, географічних і т.п.), використанням різних розмірностей і т.д.
* Спрощується процес конвертації таблиць наборів даних в формат CSV та XLSX з метою їх подальшого оприлюднення на відповідних всеукраїнських і регіональних порталах відкритих даних.
---
## 2. Стандартна методика використання Форматорів

### 2.1. Розміщення Форматорів

<p align="justify">Як уже згадувалося вище, Форматори є Google таблицями і, отже, повинні зберігатися на індивідуальному Google диску, який може бути автоматично наданий кожному розпоряднику інформації після створення їм відповідного <a href="https://myaccount.google.com/intro" target="_blank">Google аккаунта</a>.</p>
<p align="justify">Всі існуючі Форматори на Google диску за структурою свого розміщення можуть бути зібрані в однойменну папку <b><i>«Форматори»</i></b> і систематизовані в ній по підпапках, асоційованих з відповідними, задекларованими <i>Постановою КМУ № 835</i>, наборами даних. Назви вищеназваних підпапок представляють собою сукупність скорочених найменувань груп (категорій або назв розпорядників) та порядкових номерів тих наборів даних, які входять в ці групи. Наприклад, набору даних <i>«Інформація про організаційну структуру розпорядника інформації»</i> повинна бути зіставлена підпапка <b>«all-002»</b>, так як цей набір відноситься до групи <i>«Всі розпорядники інформації»</i> і знаходиться в ній під <i>2-м</i> порядковим номером. На даний момент Форматори розроблені лише для двох наступних груп (категорій розпорядників):</p>
  
* **all** - Все розпорядники інформації<br>
* **mun** - Органи місцевого самоврядування<br>

Кожна підпапка, асоційована з відповідним набором даних, в залежності від його специфіки, може містити в собі:

1. Від одного до декількох десятків файлів Форматорів, кожен з яких відповідає однієї таблиці набору даних. Наприклад, для такого набору даних, як *«Регламентовані звіти»* число файлів Форматорів буде відповідати числу систематично надаваних розпорядниками інформації стандартних форм звітності.
2. Файл, що описує структуру всіх таблиць (Форматорів), властивих для того чи іншого набору даних, асоційованого з відповідною підпапкою.
3. Файл паспорта відповідного набору даних з усією необхідною інформацією (метаданими) щодо його змісту, юридичних підстав для його формування, властивих йому ключівих слів та контактних даних тих осіб хто за нього несе відповідальність.
4. Від одного до декількох десятків файлів паспортів ресурсів, кожен з яких описує той чи інший ресурс, що входить до складу відповідного набору даних. Зокрема, кожен з цих паспортів ресурсів визначає зміст властивого йому ресурсу та формат файлу (джерела), у вигляді якого даний ресурс представлений у відповідному наборі даних.

<p align="justify">Потрібно відзначити, що паспорт набору даних та паспорта його ресурсів не входять в стандартний комплект Форматорів, а включені лише в їх повний комплект. Це пояснюється тим, що автоматизації вищеназваних паспортів в комплекті з Форматорами не суттєва, і їх можна заповнювати безпосередньо на порталах відкритих даних при створенні або оновленні відповідних наборів даних. Разом з тим дані паспорта в складі повного комплекту Форматорів будуть дуже корисні при їх використанні зі спеціальним (планованим в перспективі) програмним забезпеченням, яке буде служити своєрідним менеджером по оприлюдненню та обслуговуванню наборів даних шляхом автоматизації всіх дій, що цього стосуються.</p>

<p align="justify">У загальній папці, де розміщуються всі інші папки, асоційовані з відповідними наборами даних, також розміщується файл <b><i>«IdentificationData»</i></b>, призначений для введення в нього ідентифікаційних даних того розпорядника інформації, який в подальшому має намір користуватися Форматорами. Надалі за рахунок заповнення даного файлу відповідними відомостями буде забезпечуватися істотне зниження обсягу введення типових (властивих тільки для конкретного розпорядника) даних, а отже, і виключатися можливість помилок в цих даних.</p>

---

### 2.2. Копіювання існуючих заготовок Форматорів на індивідуальні Google диски розпорядників інформації

<p align="justify">Для того, щоб здійснити копіювання вже існуючих заготовок Форматорів на свій Google диск необхідно послідовно виконати ряд наступних дій:</p>

* Відкрити загальнодоступну папку з архівом усіх заготовок Форматорів перейшовши за посиланням: [«Архів Форматорів»](http://bit.ly/2N0OMKg).
* Перейти в цій папці на необхідну папку зі стандартним або з повним комплектом архівів та завантажити в ній собі на локальний комп'ютер архів з потрібним набором даних (наприклад, файл з ім'ям *mun-042.zip* який відповідає набору даних *«Адресный реестр»*)
* Клацнути на завантаженому архіві правою кнопкою мишки та розпакувати його в поточну папку вашого комп'ютера.
* Зайти в новій вкладці свого браузера (браузера, де був зареєстрований аккаунт Google) на свій [Google диск](https://drive.google.com/drive/my-drive).

<p align="center"><b>Увага:</b> наступні дві дії достатньо виконати лише при завантаженні першого архіву. При завантаженні наступних архівів з шаблонами форматорів, ці дії можна пропустити</p>

* Відкрити в правому верхньому куті вашого Google диску меню, позначене символом *«шестерінки»* та виконати команду *«Налаштування»*.
* У відкритому модальному вікні поставити галочку навпроти позиції *«Конвертувати завантажені файли»* і натиснути кнопку *«Готово»*.

<p align="center"><i>І нарешті:</i></p>
  
* Виконати команду *«Завантажити папку»* клацнувши правою кнопкою мишки в порожньому місці на вашому Google диску, а потім завантажити вже існуючу у вас на локальному комп'ютері папку з відповідним архівом.

<p align="justify">Після виконання всіх вище перерахованих дій ви, як розпорядник інформації, на своєму особистому Google диску отримаєте папку з шаблонами Форматорів для заповнення та обслуговування потрібного Вам набору даних. Слід зазначити, що для чіткої систематизації наборів даних, цю папку бажано було б розмістити (перемістити) в загальну папку з назвою <i>«Форматори»</i>.

<p style="text-align:center"><img alt="" src="https://github.com/Alexander-Lukyanov/table-templates/raw/master/ris2.jpg" style="height:344px; width:800px" /></p>
<p align="center"><b>Малюнок 1.</b> <i>Попереднє налаштування особистих Google дисків розпорядників інформації</i></p>

<p align="justify"><b>Примітка:</b> Може скластися враження, що XLS файли, які з загального архіву повинні бути розархівовані у відповідну папку на локальному комп'ютері, можна без проблем відкрити і почати заповнювати за допомогою всім знайомої програми <i>Excel</i>. Отже, тоді відпаде необхідність в завантаження цієї папки на власний Google диск, де потрібно буде використовувати мало кому відому серед пересічних користувачів програму <i>Google sheets</i>. Проте, справа в тому, що в <i>Excel</i> не передбачено застосування формул в сфері регулярних виразів, а отже в ньому буде відсутня автоматична перевірка коректності введених даних, що за сучасними стандартами є неприйнятним для оприлюднення відкритих даних. Разом з тим, пересічним користувачам не слід боятися програми <i>Google sheets</i>, так як вона за алгоритмом роботи в ній повністю ідентична програмі <i>Excel</i>. Тому, всі, хто знайомий з <i>Excel</i> з легкістю освоять <i>Google sheets</i> за пару хвилин.</p>

---

### 2.3. Розшифровки змісту загальнодоступних архівів (папок) з шаблонами Форматорів

<p align="justify">Для завантаження потрібних архівів, розпорядникам інформації необхідно, перш за все, з орієнтуватися, в яких архівах (папках) лежать шаблони форматорів для необхідних їм наборів даних. З цією метою, на окремій сторінці даної інструкції наводяться <a href="https://github.com/Alexander-Lukyanov/table-templates/blob/master/Subfolders-formatters.md" target="_blank">«Розшифровки змісту загальнодоступних архівів (папок) з шаблонами Форматорів, притаманними тому чи іншому набору даних»</a> які містять імена та призначення всіх файлів, включених, як в стандартний, так і в повний набір Форматорів.</p>
<p align="justify">На сьогоднішній момент всього вже підготовлено</p>

* **Для повного комплекту форматорів** - ***70*** архівів (папок з 70-ю відповідними наборами даних) в яких розміщується ***95*** файлів з безпосередніми Форматорами, ***55*** файлів, що описують табличну структуру ресурсів відповідних наборів даних, ***70*** файлів паспортів для відповідних наборів даних та ***124*** файла паспорта для ресурсів цих наборів даних.
* **Для стандартного комплекту форматорів** - ***55*** архівів (папок з 55-ю відповідними наборами даних) в яких розміщується ***95*** файлів з безпосередніми Форматорами та ***55*** файлів, що описують табличну структуру ресурсів відповідних наборів даних.

---

### 2.4. Заповнення файлу «IdentificationData» ідентифікаційними даними розпорядника інформації

<p align="justify">Попередньо, перед тим як приступати до безпосереднього заповнення Форматорів, кожному розпоряднику інформації слід в файлі <b><i>«IdentificationData»</i></b> вказати свої ідентифікаційні дані. Це повинно забезпечити для цих розпорядників істотне зниження обсягу введення типових (властивих тільки їм) даних, а отже, і виключити можливість помилок в таких даних при подальшому заповненні Форматорів.</p>

<p align="justify">Але, перш ніж заповнювати вищезгаданий файл, розпорядникам інформації необхідно спочатку скопіювати його на свій власний Google диск в загальну папку під рекомендованої і далі використовуваної назвою <i>Форматори</i>, де розміщені відповідні підпапки, що асоціюються з необхідними цим розпорядникам наборами даних. Це можна здійснити за допомогою виконання наступних дій:</p>

* Пройти по посиланню [***«IdentificationData»***](https://docs.google.com/spreadsheets/d/1vRN0NH61zjtPBszDeWGVNhUIh_kFfZe4JQ8ZOyNB5Ek/edit?usp=sharing), відкривши таким чином загальнодоступний файл з відповідною заготовкою (шаблоном) для введення ідентифікаційних даних в програмі *Google sheets*.
* Відкрити в вищеназваний програми меню *«Файл»* та виконати команду *«Копіювати»*.
* Коли відкриється нове модальнє вікно слід спочатку відкоригувати назву файлу (видалити текст: *«- копія»*), потім вибрати *«Мій диск» -> «Форматори»*, після цього відзначити галочкою пункт *«Копіювати коментарі»*, але категорично не відзначати пункт *«Надати доступ тим самим людям»* і, нарешті, натиснути кнопку *«ОК»*.
* Після цього у вашому браузері відкриється нова вкладка з уже збереженої на вашому Google диску заготовкою файлу *«IdentificationData»*, яку ви можете починати заповнювати.

Даний файл має лише дві такі колонки:

* Найменування показників, що ідентифікують розпорядника інформації
* Значення відповідних показників

<p align="justify">Перша колонка даного файлу містить спливаючі (при наведенні мишки) підказки, які роз'яснюють значення і формат того чи іншого показника, ідентифікуючого розпорядника інформації.</p>
<p align="justify">Друга ж колонка файлу призначена безпосередньо для введення відповідних значень у визначеному (описуваному регулярними виразами та притаманному тільки для них) форматі. Всі порожні комірки цієї (другої) колонки спочатку зафарбовуються в салатовий колір. Коли ж в якусь комірку вноситься значення, то при збігу умов щодо коректного його введення, комірка забарвлюється в білий колір, при некоректному ж введенні даних, ця комірку забарвлюється червоним кольором.</p>
<p style="text-align:center"><img alt="" src="https://github.com/Alexander-Lukyanov/table-templates/raw/master/ris1.jpg" style="height:558px; width:800px" /></p>
<p align="center"><b>Малюнок 2.</b> <i>Приклад заповнення файлу <b>«IdentificationData»</b></i></p>

<p align="justify"><b>Примітка:</b> З метою автоматичного внесення ідентифікаційних даних з файлу <i>«IdentificationData»</i> в усі відповідні файли Форматорів, розпорядникам інформації потрібно спочатку зв'язати ці файли між собою. Для цього в кожному файлі Форматорі, на окремому листку <i>«Прив'язка до даних розпорядника»</i> в комірки <b>B1</b> розпорядникам інформації слід вказати URL адресу свого індивідуального файлу <i>«IdentificationData»</i>. Цю URL адресу можна скопіювати у верхньому адресному рядку браузера після відкриття файлу </i>«IdentificationData»</i> в програмі <i>Google sheets</i> на індивідуальному Google диску конкретного розпорядника інформації в відповідний папці <i>«Форматори»</i>.</p>
<p align="justify"><b>Примітка:</b> Як правило, в усі Форматори з файлу <i>«IdentificationData»</i> в обов'язковому порядку автоматично вносяться лише дані <i>за кодом ЄДРПОУ</i> та <i>за кодом КОАТУУ</i>. Внесення всіх інших даних з файлу <i>«IdentificationData»</i> зазвичай визначається виходячи з вимог щодо змісту відповідних Форматорів.</p>
<p align="justify"><b>Примітка:</b> Після заповнення всіх даних на листку <i>«Ідентифікаційні дані розпорядника»</i> кожен розпорядник інформації повинен:</p>
  
1. Стандартним чином пере конвертувати лист *«IdentificationData»* поточного файлу в CSV формат.
2. Перейменувати отриманий файл в *«dentificationdata.csv»*.
3. Опублікувати отриманий файл *«dentificationdata.csv»* на *Єдиному державному порталі відкритих даних (data.gov.ua)* в складі файлів стандартного набору даних *«Реєстр наборів даних, що знаходяться у володінні розпорядника інформації»*.

<p align="justify">Це, в свою чергу дозволить активізувати створення найрізноманітніших сервісних додатків у сфері аналітики, отримання довідкової інформації та надання електронних послуг.</p>

<p style="text-align:center"><img alt="" src="https://github.com/Alexander-Lukyanov/table-templates/raw/master/ris5.jpg" style="height:146px; width:800px" /></p>
<p align="center"><b>Малюнок 3.</b> <i>Остаточне прив'язування файлу Форматору до файлу <b>«IdentificationData»</b></i></p>

<p align="justify"><b>Примітка:</b> При подальшому заповненні того чи іншого файлу Форматору на комірках його листа з <i>«Результуючою таблицею»</i>, в місці де передбачається автоматичне введення даних з файлу <i>«IdentificationData»</i> спочатку завжди виникають повідомлення <b>«#REF!»</b>. Тому, розпорядникам інформації в обов'язковому порядку слід позбутися цього повідомлення. Це можна зробити просто клацнувши мишкою на будь-який комірки з повідомленням та натиснувши в ній на синю кнопку <i>«Дозволити доступ»</i>.</p>

---

### 2.5. Заповнення файлів заготовок Форматорів даними розпорядників інформації

<p align="justify">Як ви, напевно, вже здогадалися, кожен файл Форматору забезпечує попереднє коригування даних відповідно до заданих в ньому регулярних виразів, а також мінімізує введення цих даних для конкретної таблиці в тому чи іншому наборі даних. З цією метою файли Форматорів представлені у вигляді електронних таблиць (файлів з розширенням XLS), котрі, як правило складаються з наступних листів:</p>

* **Введення даних** - цей лист в файлах Форматорів є основним місцем роботи розпорядників інформації по формуванню відповідних таблиць для того чи іншого набору даних. Спочатку порожні комірки цього листа все пофарбовані в салатовий колір. Коли ж в якусь комірку вноситься значення, то при збігу умов щодо коректності цього значення, комірка забарвлюється в білий колір, при некоректному ж введенні даних, комірка забарвлюється червоним кольором.
* **Результуюча таблиця** - лист являє собою таблицю, придатну для оприлюднення в складі того чи іншого набору даних і сформовану на основі оброблених (доповнених та скоригованих) значень з попереднього листа Форматору *«Введення даних»*. Цей лист формується в Форматорах автоматично, тому розпорядники інформації повинні лише просто періодично публікувати новосформовані або оновлені версії даного листа у вигляді CSV файлів на відповідних централізованих та регіональних порталах відкритих даних. Назва даного листа в складі конкретного Форматору, як правило, ідентична назві файлу самого Форматору. Наприклад, якщо файл Форматору називається *«postsFormatter»*, то відповідний лист з результуючої таблиці в складі цього файлу буде називатися *«Posts»*.
* **Довідники** - даний лист існує не у всіх файлах Форматорів, але якщо цей лист є, то він містить переліки стандартних варіантів заповнення тих чи інших колонок в таблиці на аркуші *«Введення даних»*. Наприклад, якщо в складі вищеназваної таблиці є колонка, кожна комірка якої повинна містити назву того чи іншого адміністративно-територіального регіону, то при натисканні мишкою на комірках цієї колонки повинен випадати список, де можна буде вибрати потрібний вам регіон. Таким чином, застосування довідників, так само як і файл *«IdentificationData»* мінімізує час і знижує кількість можливих помилок при введенні даних в Форматори.
* **Прив'язка до даних розпорядника** - цей лист призначений для зв'язування файлу *«IdentificationData»*, де повинні знаходитися ідентифікаційні дані розпорядників інформації з файлами Форматорів, куди ці дані мають бути автоматично внесені. Даний лист існує не в кожному файлі Форматорі, але при його наявності розпорядникам інформації необхідно буде лише ввести в комірку **B1** URL адресу свого індивідуального файлу *«IdentificationData»*. Цю URL адресу можна скопіювати в верхньому адресному рядку браузера після відкриття файлу *"IdentificationData»*в програмі *oogle sheets* на індивідуальному Google диску конкретного розпорядника інформації в відповідний папці *«Форматори»*.

<p style="text-align:center"><img alt="" src="https://github.com/Alexander-Lukyanov/table-templates/raw/master/ris3.jpg" style="height:219px; width:800px" /></p>
<p align="center"><b>Малюнок 4.</b> <i>Приклад заповнення файлу одного з Форматорів</i></p>

<p align="justify">З метою максимального роз'яснення розпорядникам інформації специфіки заповнення таблиць листів <i>«Введення даних»</i> і <i>«Результуюча таблиця»</i> в усіх файлах Форматорів існують спливаючі (при наведенні мишки) підказки, які роз'яснюють призначення кожної колонки в цих листах і то, як ці колонки потрібно заповнювати.</p>
<p align="justify"><b>Примітка:</b> При необхідності копіювання на лист <i>«Введення даних»</i> масиву з уже існуючими даними з <i>Google таблиць, Excel</i> або <i>Libre Office Calc</i>, область всього цього масиву необхідно спочатку перевести в текстовій формат. Це дозволить при подальшій вставці цього скопійованого масиву значень на лист <i>«Введення даних»</i> відразу ж виявити помилкові дані, комірки з якими будуть виділені червоним кольором.</p>

---

### 2.6. Специфічні Форматори

<p align="justify">Крім стандартних Форматорів, структура яких була описана вище, є ще ряд специфічних Форматорів, які були розроблені для двох наступних наборів даних:</p>

* *«Фінансова звітність суб’єктів господарювання державного сектору економіки»*
* *«Дані про зовнішню доступність інфраструктурних об'єктів для маломобільних груп населення»*

<p align="justify">Опис специфічних Форматорів, розроблених для <i>«Фінансової звітності суб'єктів господарювання»</i> наведений за посиланням: <a href="https://github.com/Alexander-Lukyanov/table-templates/blob/master/Specific-Formatters-1.md" target="_blank">Особливості Форматорів, розроблених з урахуванням публікації їх Результуючих таблиць на Єдиному порталі використання публічних коштів (spending.gov.ua)</a>.</p>
<p align="justify">Що ж стосується другого набору даних, то тут потрібно просто мати на увазі, що для коректного заповнення такого файлу Форматору в цьому наборі, як <i>«accessibilityToolsFormatter»</i> слід використовувати <a href="https://drive.google.com/file/d/1b9xZiiLV1u8FxONzbjlIZvsKBCE_qlOt/view" target="_blank">Короткий довідник державних норм і стандартів щодо забезпечення зовнішньої доступності інфраструктурних об&#39;єктів для маломобільних груп населення</a>. Цей довідник, зокрема, полегшить оцінювання відповідності обстежуваного засобу доступності (елементу інфраструктурного об'єкта) існуючим державним нормативам.

---

### 2.7. Конвертація даних з листа Форматору «Результуюча таблиця» в окремий CSV або XLSX файл

<p align="justify">Незалежно від того чи іншого Форматора, для конвертації даних його листа <i>«Результуюча таблиця»</i> в окремий CSV файл, кожному розпоряднику інформації слід виконати ряд наступних дій:</p>

1. Перейти на лист Форматору з *«Результуючою таблицею»*, а потім зберегти його на своєму локальному комп'ютері за допомогою команди *«Файл» -> «Завантажити як» -> «CSV файл (поточний лист)»*.
2. Перейменувати збережений на локальному комп'ютері CSV файл в файл з ім'ям ідентичним назві листа, дані якого були збережені. Наприклад, якщо лист з *«Результуючою таблицею»* в Форматори називався *«Posts»*, то розпорядник інформації повинен буде перейменувати свій збережений на локальному комп'ютері CSV файл в файл з назвою *posts.csv*.

<p align="justify">У разі необхідності з тих чи інших причин, або ж просто для зручності використання даних, розпорядники інформації можуть пере конвертувати вже наявний у них відповідний CSV файл в формат XLSX. Для цього слід виконати ряд наступних дій:
  
1. Імпортувати вже збережений і перейменований раннє CSV файл за допомогою виконання в програмі *Excel* команди *«Дані» -> «Отримання зовнішніх даних» -> «З тексту»*, або просто відкрити даний файл в програмі *Libre Office Calc*.
2. Пере зберегти, імпортований в *Excel* або відкритий в *Libre Office Calc*, CSV файл в файл XLSX формату.

---

### 2.8. Файли, що описують табличну структуру ресурсів наборів даних

<p align="justify">У кожній підпапки з Форматорами обов'язково має бути розміщений один спеціальний XLSX файл, котрий служить для опису табличних структур ресурсів того набору даних, який асоціюється з відповідною підпапкою, де він знаходиться. Цей спеціальний файл завжди містить у своєму найменуванні слово <i>«Structure»</i> та <i>код набору даних</i> для якого він був сформований. Наприклад, файл <i>«allStructure-005»</i> описує табличні структури ресурсів для такого набору даних, як <i>«Звіти, в тому числі щодо задоволення запитів на інформацію»</i> з кодом <b>«all-005»</b>.</p>
<p align="justify">Всі вищеназвані файли зі структурами розпорядники інформації в обов'язковому порядку повинні публікувати на відповідних порталах відкритих даних разом з пере конвертованими в CSV (XLSX) формати <i>«Результуючими таблицями»</i> Форматорів. Це, в свою чергу, дозволить об'єднувати набори даних за різними критеріями, а отже і активізувати розробку нових найрізноманітніших програмних сервісів на основі відкритих даних в сфері аналітики, отримання довідкової інформації та надання електронних послуг.</p>


## 3. Публікація на порталі data.gov.ua CSV або XLSX файлів, сформованих на основі «Результуючих таблиць» відповідних Форматорів

<p align="justify">Отримані за даними <i>«Результуючих таблиць»</i> Форматорів відповідні файли з CSV або XLSX форматами повинні публікуватися розпорядниками інформації у вигляді <i>Ресурсів</i> на <i>Єдиному державному порталі відкритих даних (data.gov.ua)</i>. Для здійснення такої публікації файлів розпорядники повинні виконати ряд наступних кроків:</p>
<p align="justify"><b>Крок 1:</b> В особистому кабінеті зайти в розділ <i>«Мої розпорядники»</i> та вибрати потрібного розпорядника.</p>
<p align="justify"><b>Крок 2:</b> На екрані з'явиться список наборів даних розпорядника, з якого необхідно вибрати потрібний набір, натиснувши на відповідне посилання.</p>
<p align="justify"><b>Крок 3:</b> На екрані з'явиться список документів обраного набору даних і кнопка <i>«Управління»</i>, яку потрібно буде натиснути.</p>
<p align="justify"><b>Крок 4:</b> Натиснути на кнопку <i>«Ресурси»</i>.</p>
<p align="justify"><b>Крок 5:</b> Натиснути на кнопку <i>«Додати новий ресурс»</i>.</p>
<p align="justify"><b>Крок 6:</b> Відкриється форма для додавання нового Ресурсу, де потрібно буде завантажити безпосередньо сам файл, що публікується натиснувши на кнопку <i>«Завантажити»</i>, а потім заповнити наступні поля:</p>
  
* **Назва** - містить назву файлу, що публікується
* **Опис** - являє собою опис того, що міститься в опублікованому файлі
* **Формат** - містить формат файлу, що публікується.

<p align="justify"><b>Крок 7:</b> Натиснути на кнопку <i>«Додати»</i>.</p>

<p style="text-align:center"><img alt="" src="https://github.com/Alexander-Lukyanov/table-templates/raw/master/ris4.jpg" style="height:219px; width:800px" /></p>
<p align="center"><b>Малюнок 5.</b> <i>Особистий кабінет розпорядника інформації на Єдиному державному порталі відкритих даних (data.gov.ua)</i></p>

---

## 4. Контакти для технічної підтримки щодо впровадження та функціонування Форматорів

<p align="justify">У разі виникнення будь-яких проблем при перенесенні заготовок Форматорів на Google диски відповідних структур або ж при подальшому використанні цих Форматорів, розпорядники інформації можуть звернутися онлайн за необхідною технічною консультацією за наступними контактами:</p>

* **E-mail** – *lykich@te.net.ua*
* **Skype** – *lykich68*
* **Viber** - *0965926998*
