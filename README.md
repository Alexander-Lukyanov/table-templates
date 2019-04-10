# ФОРМАТОРИ
<p align="justify">Цей документ містить шаблони таблиць (так звані форматори), котрі полегшують роботу розпорядників інформації щодо формування та подальшого оприлюднення їх даних, як на Єдиному державному порталі (https://data.gov.ua), так і на інших централізованих та регіональних порталах відкритих даних. Форматори розроблені в загальнодоступних електронних Google таблицях, котрі розпорядники інформації можуть перезберегти на своїх особистих Google дисках.</p>
<p align="justify"><b>Примітка:</b> <i>Більш детальну інформацію про алгоритм збереження форматорів на особистих Google дисках розпорядників інформації, а також опис основних принципів оприлюднення відкритих даних Ви можете знайти в «Пам'ятці щодо оприлюднення відкритих даних на Єдиному державному порталі та на інших відповідних порталах органів влади центрального і регіонального рівня» за адресою:</i> http://bit.ly/2EZ9GYt.</p>
<p align="justify">Форматори розроблені під конкретні таблиці, що входять до складу того чи іншого набору даних. Таких таблиць в наборі зазвичай налічується від однієї до декількох десятків (у випадку з регламентованими звітами). Зокрема, на кінець 2018 року вже було розроблено 36-ть форматорів для 10 наборів даних і, цей список форматорів постійно поповнюється. Таким чином, з часом число форматорів для таблиць в наборах даних може скласти кілька сотень і, для того, щоб розібратися та знайти потрібний форматор, всі вони оформлені у вигляді наведених нижче таблиць, які відповідають тому чи іншому набору даних. У цих же таблицях також наведені CSV файли зі структурою всіх ресурсів (таблиць), що належать відповідному набору даних. Разом з тим, всі форматори містять докладний опис того, як ними користуватися.</p>
<p align="justify">Слід зазначити, що присутні в назвах вищезгаданих таблиць позначення наборів даних формуються у вигляді сукупності, як скорочених найменувань груп (розпорядників) наборів даних, задекларованих у Постанові КМУ № 835, так і порядкових номерів цих наборів даних у відповідних групах. Наприклад, набору даних <i>«Інформація про організаційну структуру розпорядника інформації»</i> буде відповідати підпапка <i><b>«all-002»</b></i>, так як цей набір даних належить до групи <i>«Всі розпорядники інформації»</i>, і знаходиться в ній під <i>2-м</i> порядковим номером. Далі наводяться розшифровки до позначень для тих груп (розпорядників), по наборах даних яких на сьогоднішній момент вже розроблені форматори:</p>

▪ <b>all</b> - Все розпорядники інформації<br>
▪ <b>mun</b> - Органи місцевого самоврядування

## ЗМІСТ

<p align="center"><i><b>Все розпорядники інформації</b></i></p>

- [<b>all-001</b> - Набір данних: «Довідник підприємств, установ (закладів) та організацій розпорядника інформації та підпорядкованих йому організацій»](#Набір-данних-all-001)<br>
- [<b>all-002</b> - Набір данних: «Інформація про організаційну структуру розпорядника інформації»](#Набір-данних-all-002)<br>
- [<b>all-010</b> - Набір данних: «Фінансова звітність суб’єктів господарювання державного сектору економіки»](#Набір-данних-all-010)<br>
- [<b>all-011</b> - Набір данних: «Переліки регуляторних актів із зазначенням дати набрання чинності, строку проведення базового, повторного та періодичного їх відстеження»](#Набір-данних-all-011)<br>

<p align="center"><i><b>Органи місцевого самоврядування</b></i></p>

- [<b>mun-002</b> - Набір данних: «Перелік об’єктів комунальної власності»](#Набір-данних-mun-002)
- [<b>mun-003</b> - Набір данних: «Перелік об’єктів комунальної власності, що передані в оренду чи інше право користування»](#Набір-данних-mun-003)
- [<b>mun-004</b> - Набір данних: «Перелік незадіяних земельних ділянок і майнових об’єктів комунальної власності, які можуть бути передані в користування»](#Набір-данних-mun-004)
- [<b>mun-012</b> - Набір данних: «Титульні списки на проведення капітального та поточного ремонту, будівництва, реконструкції та благоустрою»](#Набір-данних-mun-012)
- [<b>mun-016</b> - Набір данних: «Дані про об'єкти та засоби торгівлі»](#Набір-данних-mun-016)
- [<b>mun-018</b> - Набір данних: «Відомості щодо ярмарків, їх організаторів, а також укладених з ними договорів»](#Набір-данних-mun-018)
- [<b>mun-021</b> - Набір данних: «Перелік перевізників, що надають послуги пасажирського автомобільного транспорту, та маршрути перевезення»](#Набір-данних-mun-021)
- [<b>mun-022</b> - Набір данних: «Відомості щодо транспортних засобів, які обслуговують пасажирські автобусні, тролейбусні та трамвайні маршрути перевезення»](#Набір-данних-mun-022)
- [<b>mun-023</b> - Набір данних: «Розклад руху громадського транспорту»](#Набір-данних-mun-023)
- [<b>mun-024</b> - Набір данних: «Дані про місце розміщення зупинок міського електро- та автомобільного транспорту»](#Набір-данних-mun-024)
- [<b>mun-026</b> - Набір данних: «Перелік земельних ділянок, що пропонуються для здійснення забудови»](#Набір-данних-mun-026)
- [<b>mun-027</b> - Набір данних: «Перелік укладених договорів, укладені договори, інші правочини, додатки, додаткові угоди та інші матеріали до них»](#Набір-данних-mun-027)
- [<b>mun-028</b> - Набір данних: «Актуальні списки власників та орендарів місцевих земельних ділянок»](#Набір-данних-mun-028)

## Набір данних: all-001

<p align="center"><i>Довідник підприємств, установ (закладів) та організацій розпорядника інформації та підпорядкованих йому організацій</i></p>

| Посилання на файли<br>форматорів та структур | Короткий опис таблиць форматорів або файлів структур |
| ------ | ------ |
| [referenceBookFormatter.xls](https://docs.google.com/spreadsheets/d/1eAh-_koPnNYcVyWxoHeREJ2RriofUHrei-H5EnkQ82Q/edit?usp=sharing) | Відомості про підприємства, установи (заклади), організації або структурні підрозділи розпорядника інформації |
| [allStructure-001.csv](https://drive.google.com/file/d/1Ed_nrsFjcmQ8Lx2Epkm9WKpQ9Su4yKbP/view?usp=sharing) | Описання структури для таблиці referenceBook |

## Набір данних: all-002

<p align="center"><i>Інформація про організаційну структуру розпорядника інформації</i></p>

| Посилання на файли<br>форматорів та структур | Короткий опис таблиць форматорів або файлів структур |
| ------ | ------ |
| [organizationsFormatter.xls](https://docs.google.com/spreadsheets/d/1gMwDp1IuBFrxizrxYSfxI8q9lEhO8HudPm4PkWBr76M/edit?usp=sharing) | Перелік юридичних осіб, що підпорядковані розпоряднику та/або входять в його структуру |
| [organizationalUnitsFormatter.xls](https://docs.google.com/spreadsheets/d/1B4OT9PL7tQm4TWHleg6Mfvf5ITcKL_eOE4IES9VvF88/edit?usp=sharing) | Перелік структурних підрозділів усіх рівнів, що входять до юридичної особи, якою є розпорядник |
| [postsFormatter.xls](https://docs.google.com/spreadsheets/d/1H1NpucGuMyPPtgZhZndWtwug0kCENeY4P_j1pNCTs48/edit?usp=sharing) | Перелік посад та працівників юридичної особи, якою є розпорядник |
| [allStructure-002.csv](https://drive.google.com/file/d/111HFYLXHRNdUDnJ0ho_2SWHVsCXC-IfW/view?usp=sharing) | Описання структур для таблиць organizations, organizationalUnits та posts |

## Набір данних: all-010

<p align="center"><i> Фінансова звітність суб’єктів господарювання державного сектору економіки </i></p>

| Посилання на файли<br>форматорів та структур | Короткий опис таблиць форматорів або файлів структур |
| ------ | ------ |
| [forma2dFormatter.xls](https://docs.google.com/spreadsheets/d/1vcN7F6VqipykL1Cp4KeILJ-HZqUr10QbLfK4WpnsegA/edit?usp=sharing) | Форма № 2д - Звіт про надходження та використання коштів загального фонду (державний бюджет) |
| [forma2mFormatter.xls](https://docs.google.com/spreadsheets/d/1HQxY67qZDSfrEIGBwBDdZeNHW1v9cRXpRGsbBHGCxO8/edit?usp=sharing) | Форма № 2м - Звіт про надходження та використання коштів загального фонду (місцевий бюджет) |
| [forma4_1dFormatter.xls](https://docs.google.com/spreadsheets/d/1x2BuOGFRWpB6qZohMCu5UZqrYPyyYM_xcA-C37xI8c4/edit?usp=sharing) | Форма № 4-1д - Звіт про надходження і використання коштів, отриманих як плата за послуги  (державний бюджет) |
| [forma4_1mFormatter.xls](https://docs.google.com/spreadsheets/d/1oIKRRP56X65C2XzXg6KbdOA6AiivcNCgd1Q9-7HqJys/edit?usp=sharing) | Форма № 4-1м - Звіт про надходження і використання коштів, отриманих як плата за послуги  (місцевий бюджет) |
| [forma4_2dFormatter.xls](https://docs.google.com/spreadsheets/d/1xIZFtWqZ57sAWj-dJoSKyXIK-BKN8A6-77gkwUSunfM/edit?usp=sharing) | Форма № 4-2д - Звіт про надходження і використання коштів, отриманих за іншими джерелами власних надходжень (державний бюджет) |
| [forma4_2mFormatter.xls](https://docs.google.com/spreadsheets/d/1VYmXVLkupQnjOM-76Fji8HvFfm72IVfNmJcBay03dQo/edit?usp=sharing) | Форма № 4-2м - Звіт про надходження і використання коштів, отриманих за іншими джерелами власних надходжень (місцевий бюджет) |
| [forma4_3dFormatter.xls](https://docs.google.com/spreadsheets/d/17t7r3ewlwnPCD3OdqC1ZcTH01IZ4Zq7Vt2jZNL7r1Uw/edit?usp=sharing) | Форма № 4-3д - Звіт про надходження і використання інших надходжень спеціального фонду (державний бюджет) |
| [forma4_3mFormatter.xls](https://docs.google.com/spreadsheets/d/140NuJfTI6-_l3qe14ZYAI8auQTLf8jFqqCW-ATZPIFw/edit?usp=sharing) | Форма № 4-3м - Звіт про надходження і використання інших надходжень спеціального фонду (місцевий бюджет) |
| [forma4_3_1dFormatter.xls](https://docs.google.com/spreadsheets/d/1IqNXW5Si1jtLvKGQ9RkOaujXve0Y_4jgWxwBN97COjo/edit?usp=sharing) | Форма № 4-3д.1 - Звіт про надходження і використання інших надходжень спеціального фонду (позики міжнародних фінансових організацій) (державний бюджет) |
| [forma4_3_1mFormatter.xls](https://docs.google.com/spreadsheets/d/1_oBzTg4XL43cGhwaaoG5qA-XqFI8AvR_A6xGjIJ_-0U/edit?usp=sharing) | Форма № 4-3м.1 - Звіт про надходження і використання інших надходжень спеціального фонду (позики міжнародних фінансових організацій) (місцевий бюджет) |
| [forma4_4dFormatter.xls](https://docs.google.com/spreadsheets/d/1cdV2Ql8uPy32X9x3wjPtVnSLeud2bycD3fMuovYXsgc/edit?usp=sharing) | Форма № 4-4д - Звіт про надходження і використання коштів, отриманих на виконання програм соціально-економічного та культурного розвитку регіонів (державний бюджет) |
| [forma7dFormatter.xls](https://docs.google.com/spreadsheets/d/1_yAbwyFBur7yXn0iUWs3c9PY3k2LaVZ1ysiP0VkcPyk/edit?usp=sharing) | Форма № 7д - Звіт про заборгованість за бюджетними коштами (державний бюджет) |
| [forma7mFormatter.xls](https://docs.google.com/spreadsheets/d/1atqU9XhO0Ve8AavbD90ZwuJfJ-pK-0jWPuSd11lDIAY/edit?usp=sharing) | Форма № 7м - Звіт про заборгованість за бюджетними коштами (місцевий бюджет) |
| [forma7_1dFormatter.xls](https://docs.google.com/spreadsheets/d/1jMXNSIpoEdtLSewalk_6jBebTKsk0pPvJjGklZKP4L4/edit?usp=sharing) | Форма № 7д.1 - Звіт про заборгованість за окремими програмами (державний бюджет) |
| [forma7_1mFormatter.xls](https://docs.google.com/spreadsheets/d/1wrNBy0hX0pBllnsfqDG6-8w-WIxLZ8GtN-UpOf6gSqI/edit?usp=sharing) | Форма № 7м.1 - Звіт про заборгованість за окремими програмами (державний бюджет) |
| [allStructureStateBudget-010.csv](https://drive.google.com/file/d/1w6lC3deC0cfwq1F-hzaoXn1ZJxQNbEsl/view?usp=sharing) | <b>Описання структур для таблиць:</b> forma2dFormatter.xls, forma4_2dFormatter.xls, forma4_2dFormatter.xls, forma4_3dFormatter.xls, forma4_3_1dFormatter.xls, forma4_4dFormatter.xls, forma7dFormatter.xls, forma7_1dFormatter.xls |
| [allStructureLocalBudget-010.csv](https://drive.google.com/file/d/1piRVc2gUMjopVW0fpmL0k46NQkPZUnED/view?usp=sharing) | <b>Описання структур для таблиць:</b> forma2mFormatter.xls, forma4_2mFormatter.xls, forma4_2mFormatter.xls, forma4_3mFormatter.xls, forma4_3_1mFormatter.xls, forma7mFormatter.xls, forma7_1mFormatter.xls |

## Набір данних: all-011

<p align="center"><i> Переліки регуляторних актів із зазначенням дати набрання чинності, строку проведення базового, повторного та періодичного їх відстеження </i></p>

| Посилання на файли<br>форматорів та структур | Короткий опис таблиць форматорів або файлів структур |
| ------ | ------ |
| [listOfRegulatoryActsFormatter.xls]( https://docs.google.com/spreadsheets/d/1yGniQiJhagiOCI2WfspLF_rPW_Zys2hZSq6PaYnNl-Q/edit?usp=sharing) | Таблиця, що містить перелік діючих регуляторних актів розпорядника із зазначенням інформації про нормативно-правові акти, якими вони були введені в дію, а також інформації про базові, повторні та періодичні відстеження |
| [allStructure-011.csv]( https://drive.google.com/file/d/1GbxCsfr95WymJeEByhbtKo3PXIRY59Xx/view?usp=sharing) | Описання структури для таблиці listOfRegulatoryActs |

## Набір данних: mun-002

<p align="center"><i>Перелік об’єктів комунальної власності</i></p>

| Посилання на файли<br>форматорів та структур | Короткий опис таблиць форматорів або файлів структур |
| ------ | ------ |
| [referenceBookFormatter.xls](https://docs.google.com/spreadsheets/d/1Wo6MJVPfcHdkHWbFfbTGAA3gfS2NeUxRnlJY289qcXw/edit?usp=sharing) | Довідник власників, балансоутримувачів та користувачів об’єктів комунальної власності |
| [registerFormatter.xls](https://docs.google.com/spreadsheets/d/1pEWPtdU9nPKYETPC-g1p5IwS4pmKefmSMSMu3afN1FE/edit?usp=sharing) | Перелік об’єктів комунальної власності |
| [munStructure-002.csv]( https://drive.google.com/file/d/1W2x9vx0nz_tBQmoh5SZNnQYVab2auk8O/view?usp=sharing) | Описання структур для таблиць referenceBook і register |

## Набір данних: mun-003

<p align="center"><i> Перелік об’єктів комунальної власності, що передані в оренду чи інше право користування </i></p>

| Посилання на файли<br>форматорів та структур | Короткий опис таблиць форматорів або файлів структур |
| ------ | ------ |
| RentedPropertyFormatter.xls | Таблиця, що містить перелік об’єктів комунальної власності, котрі передані в оренду чи інше право користування |
| munStructure-003.csv | Описання структури для таблиці RentedProperty |

## Набір данних: mun-004

<p align="center"><i>Перелік незадіяних земельних ділянок і майнових об’єктів комунальної власності, які можуть бути передані в користування</i></p>

| Посилання на файли<br>форматорів та структур | Короткий опис таблиць форматорів або файлів структур |
| ------ | ------ |
| ItemsFormatter.xls | Перелік незадіяних земельних ділянок і майнових об’єктів комунальної власності, які можуть бути передані в користування |
| AuctionsFormatter.xls | Інформація про умови передачі об’єктів комунальної власності у користування за прямими договорами або на аукціонах |
| munStructure-004.csv | Описання структур для таблиць Items і Auctions |

## Набір данних: mun-012

<p align="center"><i>Титульні списки на проведення капітального та поточного ремонту, будівництва, реконструкції та благоустрою</i></p>

| Посилання на файли форматорів та структур | Короткий опис таблиць форматорів або файлів структур |
| ------ | ------ |
| [titleListsFormatter.xls](https://docs.google.com/spreadsheets/d/1VaZO2EspsO7I6839Gleid4pcwXrvZHCjzkx-0HtVEfI/edit?usp=sharing) | Титульні списки на проведення капітального та поточного ремонту, будівництва, реконструкції та благоустрою |
| [munStructure-012.csv](https://drive.google.com/file/d/1Si3z5XjdbhZr4_di2TPhMPzHBe9KzF6T/view?usp=sharing) | Описання структури для таблиці TitleLists |

## Набір данних: mun-016

<p align="center"><i>Дані про об'єкти та засоби торгівлі</i></p>

| Посилання на файли форматорів та структур | Короткий опис таблиць форматорів або файлів структур |
| ------ | ------ |
| [storesFormatter.xls](https://docs.google.com/spreadsheets/d/1Olt21KInuQAZaRVUC87Siwi1vz2NCuQTj96ZikjMIF8/edit?usp=sharing) | Дані про об'єкти та засоби торгівлі |
| [munStructure-016.csv](https://drive.google.com/file/d/1zFlgDn3Z-CDKxPyaWzVLGrexnsxrOEYl/view?usp=sharing) | Описання структури для таблиці Stores |

## Набір данних: mun-018

<p align="center"><i>Відомості щодо ярмарків, їх організаторів, а також укладених з ними договорів</i></p>

| Посилання на файли форматорів та структур | Короткий опис таблиць форматорів або файлів структур |
| ------ | ------ |
| [fairsFormatter.xls](https://docs.google.com/spreadsheets/d/1eJBHRL6u46GMHDXieZXYhb06ktUQgXcjhyt1DSZhyvc/edit?usp=sharing) | Відомості про проведені на території регіону ярмарки. Зокрема відомості щодо організаторів ярмарків, укладених для їх проведення договорів, кількості і вартості місць на них, тощо. |
| [munStructure-018.csv](https://drive.google.com/file/d/1dvhYTzy6CjmIReOa78hU--Vgp9Ah57_q/view?usp=sharing) | Описання структури для таблиці Fairs |

## Набір данних: mun-021

<p align="center"><i> Перелік перевізників, що надають послуги пасажирського автомобільного транспорту, та маршрути перевезення </i></p>

| Посилання на файли<br>форматорів та структур | Короткий опис таблиць форматорів або файлів структур |
| ------ | ------ |
| [agencyFormatter.xls](https://docs.google.com/spreadsheets/d/1H5h4hzSARBfwYNClDSIeEdjfV2eoS5T0SJ5zEfeT_uI/edit?usp=sharing) | Перелік суб’єктів господарювання, що надають послуги громадського транспорту |
| [routesFormatter.xls](https://docs.google.com/spreadsheets/d/1hbo97mP3JP1WGRC98dvMiTJ7dpXpee-Z4yNu8ChuEk8/edit?usp=sharing) | Перелік маршрутів громадського транспорту |
| [munStructure-021.csv](https://drive.google.com/file/d/1cBFOu-6_erTJlB8p4JGBVChJMO5e__0-/view?usp=sharing) | Описання структур для таблиць agency і routes |

## Набір данних: mun-022

<p align="center"><i>Відомості щодо транспортних засобів, які обслуговують пасажирські автобусні, тролейбусні та трамвайні маршрути перевезення</i></p>

| Посилання на файли форматорів та структур | Короткий опис таблиць форматорів або файлів структур |
| ------ | ------ |
| [vehiclesFormatter.xls](https://docs.google.com/spreadsheets/d/1t4HHtCDtaB0Cy8Of8-AqyPWAYm4SMXDx6A9yC-FkDhk/edit?usp=sharing) | Відомості щодо транспортних засобів, які обслуговують пасажирські автобусні, тролейбусні та трамвайні маршрути перевезення |
| [munStructure-022.csv](https://drive.google.com/file/d/1gZyzVDyV4WXSk70StyBHU0iFljuqWBL1/view?usp=sharing) | Описання структури для таблиці vehicles |

## Набір данних: mun-023

<p align="center"><i>Розклад руху громадського транспорту</i></p>

| Посилання на файли<br>форматорів та структур | Короткий опис таблиць форматорів або файлів структур |
| ------ | ------ |
| [agencyFormatter.xls](https://docs.google.com/spreadsheets/d/1fDfFhvbAbf4nBkoyLnHf9rGi2jCHsLxCwgvDaA_-ano/edit?usp=sharing) | Дані про суб’єктів господарювання, що надають послуги громадського транспорту |
| [stopsFormatter.xls](https://docs.google.com/spreadsheets/d/1AP5OIuOp0sLMiEiKzrB6qDllM0Yif05Xzti7Mj7W20w/edit?usp=sharing) | Дані про зупинки громадського транспорту |
| [routesFormatter.xls](https://docs.google.com/spreadsheets/d/1d_GKRYCcNF1ygUj_oP8EMvWBUb9D2mxBbMgxTSdDn3Y/edit?usp=sharing) | Дані про маршрути громадського транспорту |
| [tripsFormatter.xls](https://docs.google.com/spreadsheets/d/19lWQKBWrHjfJK2VMJF473eZ-wMzl7UL1KOOWN1B7_as/edit?usp=sharing) | Дані про рейси громадського транспорту |
| [stop_timesFormatter.xls](https://docs.google.com/spreadsheets/d/1f4z-BhG6ns8tR6Ie_jCzUZom0lJs7aVSvAZqoTdAgrY/edit?usp=sharing) | Графік відбуття та прибуття транспорту до та від зупинок |
| [calendarFormatter.xls](https://docs.google.com/spreadsheets/d/1fEv76gw4FQX1HN8YUAq4oBn5wlpmeXmHbGBPXUIEQYI/edit?usp=sharing) | Варіанти тижневих графіків роботи громадського транспорту |
| [calendar_datesFormatter.xls](https://docs.google.com/spreadsheets/d/15BBo8yhzembOCSb9YQHviPP_sNxmNxeTyS8Qkmd4gtA/edit?usp=sharing) | Перелік винятків до тижневих графіків |
| [munStructure-023.csv](https://drive.google.com/file/d/1eZc433pQnkBt_tESaTFSQFB4k_9UtfAj/view?usp=sharing) | Описання структур для таблиць agency, stops, routes, trips, stop_times, calendar, та calendar_dates |

## Набір данних: mun-024

<p align="center"><i> Дані про місце розміщення зупинок міського електро- та автомобільного транспорту </i></p>

| Посилання на файли<br>форматорів та структур | Короткий опис таблиць форматорів або файлів структур |
| ------ | ------ |
| [stopsFormatter.xls](https://docs.google.com/spreadsheets/d/16wQxmSHN05Sl53aRW6rdYocrRKta-kIlCyIhbNSL76w/edit?usp=sharing) | Дані про місце розміщення зупинок міського електро- та автомобільного транспорту |
| [munStructure-024.csv](https://drive.google.com/file/d/1QemIe8Try4A3WZAd8epSxHvhwliraVph/view?usp=sharing) | Описання структури для таблиці stops |

## Набір данних: mun-026

<p align="center"><i>Перелік земельних ділянок, що пропонуються для здійснення забудови</i></p>

| Посилання на файли<br>форматорів та структур | Короткий опис таблиць форматорів або файлів структур |
| ------ | ------ |
| landLotsFormatter.xls | Перелік земельних ділянок, що пропонуються для здійснення забудови |
| auctionsFormatter.xls | Перелік земельних аукціонів |
| munStructure-026.csv | Описання структур для таблиць landLots та auctions |

## Набір данних: mun-027

<p align="center"><i>Перелік укладених договорів, укладені договори, інші правочини, додатки, додаткові угоди та інші матеріали до них</i></p>

| Посилання на файли<br>форматорів та структур | Короткий опис таблиць форматорів або файлів структур |
| ------ | ------ |
| [contractsFormatter.xls](https://docs.google.com/spreadsheets/d/1NnTYus27Kq5P-TfZO86fdjU-Se2OTJnEA9xC4u0vbv0/edit?usp=sharing) | Відомості щодо договорів, які були укладені розпорядниками даних |
| [addendumsFormatter.xls](https://docs.google.com/spreadsheets/d/1XgHtCL_UpMEIZ4I3Fi826XOG4yhTYM-RqBmrvHnVa-0/edit?usp=sharing) | Відомості щодо додаткових угод до договорів, які були укладені розпорядниками даних |
| [actsFormatter.xls](https://docs.google.com/spreadsheets/d/10JtkEIpfjbEWxZxeS_CwKeBAYyNLR4irHtMlytAMeQ4/edit?usp=sharing) | Відомості щодо актів та накладних до договорів, які були укладені розпорядниками даних |
| [penyFormatter.xls](https://docs.google.com/spreadsheets/d/1dKzqVXA_tJ7FCI0Hex-55mFkwXtyE9sL8aDn6dye5a4/edit?usp=sharing) | Відомості по штрафних санкціях щодо договорів, які були укладені розпорядниками даних |
| [paymentsFormatter.xls](https://docs.google.com/spreadsheets/d/1m0cQM6yq2hqn6JVMOtm0wVJGsA7LHIIRrjpofLM2yXE/edit?usp=sharing) | Таблиця, що містить відомості про планові і фактичні надходження за договорами оренди комунального майна |
| [specificationFormatter.xls](https://docs.google.com/spreadsheets/d/14RdSI6w8DW-uz5pgD5azC6db-vMpSFzt4v6KnjthYoY/edit?usp=sharing) | Відомості по специфікаціям до договорів, які були укладені розпорядниками даних (використовуються тільки для пакетного (багаточисельного) завантаження специфікацій на портал spending.gov.ua |
| [munStructure-027.csv](https://drive.google.com/file/d/1GqnxJ-bUVEpMj1a-8DNGjXEABYLXqOHG/view?usp=sharing) | Описання структур для таблиць contracts, addendums, acts, peny та payments |

## Набір данних: mun-028

<p align="center"><i>Актуальні списки власників та орендарів місцевих земельних ділянок</i></p>

| Посилання на файли<br>форматорів та структур | Короткий опис таблиць форматорів або файлів структур |
| ------ | ------ |
| landLotsFormatter.xls | Таблиця, що містить актуальні списки власників та орендарів місцевих земельних ділянок |
| munStructure-028.csv | Описання структури для таблиці landLots |

