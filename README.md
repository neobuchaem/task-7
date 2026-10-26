# task-7
Тема 1. Числовые типы: int, double, num и математические операции
1.Конвертер валют: Напишите функцию, принимающую сумму в рублях (int) и курс доллара (double), возвращающую строку с результатом, отформатированным строго до 2 знаков после запятой.
<img width="1422" height="266" alt="1 1" src="https://github.com/user-attachments/assets/3c00e4b4-ea9d-49e6-b29a-70d97cd10a07" />
2.Безопасный калькулятор возраста: Примите ввод пользователя в виде String. Используя int.tryParse(), верните возраст или -1, если пользователь ввел некорректный текст.
<img width="1386" height="330" alt="1 2" src="https://github.com/user-attachments/assets/830e9ab8-bd4f-48e9-a76d-b5d09548a2f4" />
3.Расчет плотности пикселей (DP): Реализуйте формулу dp = px / density с использованием оператора целочисленного или дробного деления.
<img width="1487" height="236" alt="1 3" src="https://github.com/user-attachments/assets/3119462c-d960-4420-9f56-3d700b650a6b" />
4.Побитовые флаги сенсоров: Используя побитовые операторы &, | и <<, закодируйте состояние трех мобильных датчиков в одну переменную int.
<img width="1438" height="413" alt="1 4" src="https://github.com/user-attachments/assets/c19cb1fd-b21c-4b14-bca3-90f77b205db5" />
5.Проверка четности без остатка от деления: Проверьте, является ли целое число четным, используя побитовое умножение (number & 1) == 0.
<img width="1381" height="286" alt="1 5" src="https://github.com/user-attachments/assets/fa3c7796-2c8e-4287-be6f-229b10af2a7b" />
Тема 2. Строки (String), интерполяция и кодовые точки (Runes)
1.Маскирование email: Напишите функцию, преобразующую ivanov.flutter@gmail.com в i************r@gmail.com.
<img width="1528" height="297" alt="2 1" src="https://github.com/user-attachments/assets/b0165b7b-eb98-4251-86b4-b3949d1cb2bc" />
2.Валидатор префикса ссылки: Проверьте, начинается ли переданная строка с безопасного протокола https:// с помощью метода .startsWith().
<img width="1386" height="225" alt="2 2" src="https://github.com/user-attachments/assets/3e18ff5f-d776-4c2a-8aaa-9c2731aff03a" />
3.Генератор инициалов (Monogram): Примите строку из двух слов («Александр Пушкин») и верните заглавные буквы «АП».
<img width="1367" height="237" alt="2 3" src="https://github.com/user-attachments/assets/90cf64d7-a967-48b3-95f5-aeaf2114fca8" />
4.Разбор CSV-строки корзины: Разбейте строку вида "Яблоко,3,150.5" методом .split(',') и извлеките наименование, количество и стоимость.
<img width="1431" height="305" alt="2 4" src="https://github.com/user-attachments/assets/f4f0743e-c1f2-422d-9253-60d939747ec6" />
5.Подсчет реальной длины строки с эмодзи: Напишите утилиту, которая считает точное количество символов в тексте с комбинированными эмодзи (через .runes).
<img width="1415" height="207" alt="2 5" src="https://github.com/user-attachments/assets/32244ae1-6f17-4d1f-981d-c7515b3fad12" />
Тема 3. Логический тип (bool) и строгость условий
1.Проверка права доступа к экрану: Сформируйте булево выражение: пользователь авторизован, подтвердил email и не находится в списке заблокированных.
<img width="1356" height="330" alt="3 1" src="https://github.com/user-attachments/assets/5af69ddb-de99-434f-854e-1b7ebaaff04b" />
2.Определитель пустоты строки: Напишите функцию bool isBlank(String? input), возвращающую true, если строка равна null, пуста или состоит только из пробелов.
<img width="1412" height="333" alt="3 2" src="https://github.com/user-attachments/assets/b4d9e477-e0c7-4c6e-9c0d-5bb271b40d91" />
3.Тоггл состояния (Инвертор): Напишите функцию, переключающую флаг темной темы isDarkMode на противоположное значение.
<img width="1391" height="303" alt="3 3" src="https://github.com/user-attachments/assets/22976bbf-e2d2-493a-96fa-cecc5b0a7612" />
4.Валидатор возраста для аренды авто: Проверьте совокупность условий: возраст (\ge 21) года И стаж вождения (\ge 2) лет.
<img width="1351" height="294" alt="3 4" src="https://github.com/user-attachments/assets/811e84e4-ad09-4bae-8765-4916874742ed" />
5.Строгая фильтрация коллекций: Напишите проверку, что баланс пользователя строго положителен, избегая неявных сравнений.
<img width="1357" height="282" alt="3 5" src="https://github.com/user-attachments/assets/5d913511-ab6c-4574-8365-724d3df2db24" />
Тема 4. Списки (List): списковые включения и spread-операторы
1.Удаление дубликатов с сохранением порядка: Дан список List<int> с повторами. Верните список уникальных элементов через .toSet().toList().
<img width="1417" height="194" alt="4 1" src="https://github.com/user-attachments/assets/3607f619-7378-4b50-9198-a15a4b2079fd" />
2.Пагинация среза (Slice): Реализуйте метод getPage(List<T> list, int page, int pageSize), возвращающий соответствующий подсписок с помощью .sublist().
<img width="1383" height="323" alt="4 2" src="https://github.com/user-attachments/assets/eeeb73be-b4f8-44b1-9202-e148e437168b" />
3.Сортировка товаров по цене: Дан список цен List<double>. Отсортируйте его по убыванию с помощью метода .sort().
<img width="1501" height="226" alt="4 3" src="https://github.com/user-attachments/assets/058f4057-1b1d-437f-961e-e6372649bdee" />
4.Поиск первого подходящего элемента: Найдите в списке строк первое слово длиннее 8 символов с помощью .firstWhere(), обработав случай отсутствия через orElse.
<img width="1456" height="371" alt="4 4" src="https://github.com/user-attachments/assets/af824684-48f1-4794-9ad4-647d71ae82ae" />
5.Генератор виджетов через List.generate: Создайте список строк вида ["Слот 1", "Слот 2", ... "Слот 10"] с помощью конструктора List.generate().
<img width="2016" height="178" alt="4 5" src="https://github.com/user-attachments/assets/e25adeaf-e200-44c1-8c04-f55eecc2b097" />
Тема 5. Множества (Set) и Словари (Map): парсинг JSON-структур
1.Подсчет частоты слов: Дана строка текста. С помощью Map<String, int> подсчитайте, сколько раз каждое слово встречается в тексте.
<img width="1575" height="364" alt="5 1" src="https://github.com/user-attachments/assets/3ac58e07-6bab-48eb-9747-591cc2d27ff6" />
2.Симметрическая разность тегов: Найдите теги, которые присутствуют только в одном из двух множеств Set<String>, но не в обоих одновременно.
<img width="1560" height="296" alt="5 2" src="https://github.com/user-attachments/assets/c5832af2-084b-4417-95f8-ccbe977315f7" />
3.Безопасное извлечение настроек: Напишите функцию, извлекающую значение String из вложенной Map<String, dynamic> с гарантированным возвратом дефолтного значения при отсутствии ключа.
<img width="1355" height="308" alt="5 3" src="https://github.com/user-attachments/assets/2ef83187-6a0e-40af-9854-6ba08525a2f6" />
4.Трансформация карты (Map Entries): Преобразуйте Map<String, double> с ценами в рублях в карту с ценами в долларах с помощью .map().
<img width="1641" height="358" alt="5 4" src="https://github.com/user-attachments/assets/680da3f1-3d5c-4348-a099-5454823a8074" />
5.Группировка пользователей по городу: Дан список карт пользователей. Сгруппируйте их в структуру Map<String, List<Map<String, dynamic>>>.
<img width="2154" height="425" alt="5 5" src="https://github.com/user-attachments/assets/b9c335f1-ddbb-45cc-b0d4-c39a3534880f" />
Тема 6. Null Safety, Records (кортежи) и Pattern Matching
1.Координаты экрана через Record: Напишите функцию, возвращающую кортеж (double x, double y) центра экрана смартфона.
<img width="1410" height="224" alt="6 1" src="https://github.com/user-attachments/assets/e07372cf-f36c-44f4-a06f-bbf2734e63f5" />
2.Безопасная распаковка профиля: Дана переменная String? bio. Если она null, запишите в переменную displayBio текст «Информация отсутствует».
<img width="1504" height="263" alt="6 2" src="https://github.com/user-attachments/assets/5d8f28da-5025-463b-9240-b8bfefdbe708" />
3.Pattern Matching над JSON: Используя конструкцию switch (json), проверьте формат входящего пакета: валидный объект с id или объект с полем ошибки.
<img width="1432" height="558" alt="6 3" src="https://github.com/user-attachments/assets/a0d35a32-5797-47c1-b6ef-dde8b05da74d" />
4.Служебная переменная с late: Объявите переменную late final double expensiveCalculation, которая вычисляется только при первом реальном обращении.
<img width="1429" height="284" alt="6 4" src="https://github.com/user-attachments/assets/f4495daf-f830-4958-950f-ace8cfdc91ce" />
5.Безопасный поиск в списке: Извлеките первый элемент списка List<int>? numbers через операторы ?.[0] и ?? -1.
<img width="1342" height="308" alt="6 5" src="https://github.com/user-attachments/assets/04cd9403-670c-49e8-bf81-1ffe37041ccd" />
50 Смешанных заданий по обработке данных
Блок 1: Числа, финансы и расчеты корзины (1–10)
1.Калькулятор скидки с промокодом: Рассчитайте итоговую стоимость заказа при условии: скидка 15%, но не более 500 рублей.
<img width="1409" height="277" alt="1" src="https://github.com/user-attachments/assets/67837763-eb52-4f81-ab93-c9d8e8c89904" />
2.Форматирование цены по стандарту валют: Преобразуйте число 15400900.5 в строку "15 400 900.50 ₽".
<img width="1432" height="419" alt="2" src="https://github.com/user-attachments/assets/9cb03cb5-928b-4595-9e64-0c4856a7c572" />
3.Расчет кешбэка баллами: Начислите 1 балл за каждые полные 100 рублей чека, используя оператор целочисленного деления ~/.
<img width="1387" height="189" alt="3" src="https://github.com/user-attachments/assets/da90721a-eda2-4436-9794-13331eda91d7" />
4.Ограничитель диапазона (Clamp): Напишите функцию, ограничивающую уровень громкости динамика в диапазоне от 0.0 до 1.0.
<img width="1333" height="297" alt="4" src="https://github.com/user-attachments/assets/096f0fcc-3213-4978-87b8-0c026d04d637" />
5.Конвертер байтов в мегабайты: Преобразуйте размер файла из байтов в МБ с округлением до одного знака после запятой.
<img width="1340" height="188" alt="5" src="https://github.com/user-attachments/assets/5a7aeaab-264b-4349-9eff-2ed2e50a7032" />
6.Вычисление процентного прогресса: По текущему шагу current и общему числу шагов total верните double от 0.0 до 1.0.
<img width="1328" height="211" alt="6" src="https://github.com/user-attachments/assets/d6aa05a8-eae6-400c-a847-738a112ae1c7" />
7.Округление до ближайшего десятка: Округлите переданное число вверх до ближайшего числа, кратного 10 (например, 43 -> 50).
<img width="1334" height="194" alt="7" src="https://github.com/user-attachments/assets/62be9471-24ee-44f6-90a6-b868f8f33b9d" />
8.Калькулятор стоимости доставки: Базовая ставка 200 руб. + 30 руб. за каждый километр свыше 5 км.
<img width="1320" height="241" alt="8" src="https://github.com/user-attachments/assets/dc620a3f-1939-4bdb-adc6-5392b6701447" />
9.Проверка делимости без остатка: Определите, делится ли размер скачиваемого пакета ровно на блоки по 1024 байта.
<img width="1340" height="260" alt="9" src="https://github.com/user-attachments/assets/446c70c8-e71a-443f-add1-640a8cac1a66" />
10.Парсер диапазона цен: Извлеките минимальную и максимальную цену из строки "1500 - 4500 руб".
<img width="1446" height="222" alt="10" src="https://github.com/user-attachments/assets/5b8b438c-4c44-4c03-84e9-499520d2aab5" />
11.Валидатор пароля на регулярных выражениях: Проверьте пароль на наличие минимум 8 символов, одной цифры и одной заглавной буквы.
<img width="1339" height="373" alt="11" src="https://github.com/user-attachments/assets/864d848d-5a8f-430a-b1e8-91b5116260a5" />
12.Очистка поискового ввода: Удалите из поискового запроса двойные пробелы, спецсимволы #, $, % и приведите к нижнему регистру.
<img width="1395" height="212" alt="12" src="https://github.com/user-attachments/assets/aea0925c-5d86-41c8-8d47-8f36da1a164a" />
13.Генератор сокращенного имени автора: Преобразуйте "Иванов Иван Иванович" в "Иванов И. И.".
<img width="1400" height="203" alt="13" src="https://github.com/user-attachments/assets/bf90a54e-906c-4480-976e-f3e876c35db0" />
14.Парсинг HEX-цвета для Flutter: Преобразуйте строку вида "#FF5722" в целочисленное значение цвета int (0xFFFF5722).
<img width="1388" height="218" alt="14" src="https://github.com/user-attachments/assets/821cb73c-188f-4027-b6a6-4d1625d6f874" />
15.Форматирование таймера звонка: Переведите количество секунд int seconds = 125 в строку вида "02:05".
<img width="1336" height="248" alt="15" src="https://github.com/user-attachments/assets/9fa4c916-9887-400f-8ecb-66d2c07278a2" />
16.Скрытие номера телефона: Преобразуйте "+79991234567" в "+7 (999) ***-**-67".
<img width="1455" height="187" alt="16" src="https://github.com/user-attachments/assets/2f0c3e40-5d75-438c-95da-a8774c6bbd81" />
17.Определитель языка текста (Кириллица/Латиница): Определите, содержит ли строка символы русского алфавита с помощью проверки диапазонов кодовых точек.
<img width="1330" height="290" alt="17" src="https://github.com/user-attachments/assets/4934428f-45e1-4ea3-b01b-e152aae0e191" />
18.Генератор слага (Slugify): Преобразуйте заголовок статьи "Быстрый старт во Flutter!" в "bystryi-start-vo-flutter".
<img width="1506" height="283" alt="18" src="https://github.com/user-attachments/assets/b0a1ea49-4032-46bc-a26f-9516b9ffc14c" />
19.Подсчет слов в заметке: Подсчитайте количество слов в тексте заметки, разделенных пробелами и переносами строк.
<img width="1317" height="200" alt="19" src="https://github.com/user-attachments/assets/75e9b90d-ab85-4ed3-b2f4-6cbe2092c6ea" />
20.Выделение тегов из текста: Извлеките все хештеги из сообщения блога (слова, начинающиеся с #).
<img width="1512" height="295" alt="20" src="https://github.com/user-attachments/assets/6ccaf3dd-eef3-4e8c-9427-669877a616a7" />
21.Фильтр каталога по диапазону цен: Из списка карточек товаров отберите только те, у которых цена находится в заданном диапазоне.
<img width="1491" height="337" alt="21" src="https://github.com/user-attachments/assets/19a2fd9b-4fd4-48dd-a84a-1ac6f24a6f36" />
22.Удаление завершенных задач из To-Do списка: Отфильтруйте список задач, оставив только элементы со статусом isCompleted == false.
<img width="1990" height="297" alt="22" src="https://github.com/user-attachments/assets/980dbfd6-b115-4364-bc84-6df559a66e7d" />
23.Инверсия порядка чатов: Разверните список сообщений без создания промежуточных копий в памяти.
<img width="1457" height="175" alt="23" src="https://github.com/user-attachments/assets/5074d9f4-c250-4323-b099-6dfb7e9279c5" />
24.Склейка двух списков баннеров: Объедините системные промо-акции и персональные предложения с помощью spread-оператора ....
<img width="1523" height="204" alt="24" src="https://github.com/user-attachments/assets/b5faf2d0-76be-48bd-b877-7a0705254bae" />
25.Поиск максимального элемента без библиотек: Найдите товар с наивысшим рейтингом в списке с помощью метода .reduce().
<img width="1308" height="183" alt="25" src="https://github.com/user-attachments/assets/faae3030-a902-4072-ba3a-4b75b464e9a5" />
26.Чередование элементов списка: Вставьте рекламный баннер после каждого 5-го элемента ленты новостей.
<img width="2298" height="307" alt="26" src="https://github.com/user-attachments/assets/ec33db32-8845-4b82-91ba-b3e6309e3aff" />
27.Проверка идентичности двух списков: Напишите функцию, проверяющую, содержат ли два списка одинаковые элементы на тех же позициях.
<img width="1340" height="482" alt="27" src="https://github.com/user-attachments/assets/8591427c-99ca-4447-900a-6d166390938c" />
28.Извлечение уникальных категорий: Из списка всех товаров магазина сформируйте List<String> уникальных названий категорий.
<img width="1408" height="261" alt="28" src="https://github.com/user-attachments/assets/614c0520-adee-4c1b-99ae-6a7216a48e34" />
29.Сортировка списка по нескольким полям: Отсортируйте список товаров сначала по доступности на складе, а затем по возрастанию цены.
<img width="2288" height="350" alt="29" src="https://github.com/user-attachments/assets/9bbc4976-ad96-40b9-b01a-2ab5687c0e76" />
30.Постраничная группировка (Chunking): Разбейте длинный список из 100 элементов на пачки (страницы) по 10 элементов.
<img width="2125" height="293" alt="30" src="https://github.com/user-attachments/assets/79c4bbc2-b0a5-4a1c-b895-95f52f35382d" />
31.Десериализация профиля: Напишите парсер словаря Map<String, dynamic> в безопасные локальные переменные с дефолтными значениями.
<img width="1570" height="300" alt="31" src="https://github.com/user-attachments/assets/a0e1e095-a44c-4b73-a260-33b916a6b9e3" />
32.Конвертация списка в ассоциативную карту: Преобразуйте List<User> в Map<int, User>, где ключом выступает уникальный id.
<img width="1687" height="294" alt="32" src="https://github.com/user-attachments/assets/210054d2-ad81-4d3c-9be8-7c8a56c1e367" />
33.Слияние локального и серверного профиля: Объедините настройки приложения из кэша и свежие настройки с бэкенда с приоритетом сервера.
<img width="1667" height="205" alt="33" src="https://github.com/user-attachments/assets/02205480-82a4-452f-be53-50bfbc004c87" />
34.Удаление ключей с null-значениями: Очистите словарь от всех пар, где значение равно null, перед отправкой POST-запроса.
<img width="1463" height="259" alt="34" src="https://github.com/user-attachments/assets/360cf8a7-663b-4581-9601-c80cc536d979" />
35.Кэш экранов (LRU-концепт): Реализуйте простейшую карту последних 5 открытых страниц, удаляя самый старый элемент при переполнении.
<img width="1647" height="433" alt="35" src="https://github.com/user-attachments/assets/0909dd74-9bc3-4d57-8a52-a8f66cf65800" />
36.Инверсия карты (Значения становятся ключами): Поменяйте местами ключи и значения в словаре Map<String, String> (гарантируя уникальность).
<img width="1438" height="238" alt="36" src="https://github.com/user-attachments/assets/e314a709-f694-41df-8818-6b0c586a14b6" />
37.Подсчет суммы товаров по категориям: На основе списка покупок верните Map<String, double>, где ключ — категория, а значение — общая сумма затрат.
<img width="1486" height="355" alt="37" src="https://github.com/user-attachments/assets/05f89ff6-eae2-45d0-9893-04aa4b4ff0e4" />
38.Валидация обязательных JSON-полей: Проверьте, содержит ли карта ответа сервера ключи "status", "data" и "timestamp".
<img width="1332" height="296" alt="38" src="https://github.com/user-attachments/assets/1ab76788-b625-4204-bb0d-a1e81793ce30" />
39.Построение дерева категорий: Преобразуйте плоский список категорий с parentId в иерархическую карту подкатегорий.
<img width="2357" height="351" alt="39" src="https://github.com/user-attachments/assets/29244636-e467-4ab7-b474-2e98857cb05c" />
40.Сериализация параметров фильтра в URL: Соберите из словаря {"brand": "Apple", "minPrice": 50000} строку параметров brand=Apple&minPrice=50000.
<img width="1516" height="260" alt="40" src="https://github.com/user-attachments/assets/2f35ec07-bccb-48e6-b761-a736f17b8cbd" />
41.Парсер геолокации через Record: Напишите функцию, принимающую строку "54.01, 38.29" и возвращающую кортеж (double lat, double lon)?.
<img width="1403" height="330" alt="41" src="https://github.com/user-attachments/assets/f7d67d79-9ecb-4d04-9fb7-acc58c3361df" />
42.Резолвер состояний загрузки (Pattern Matching): С помощью switch верните текст сообщения для состояний (isLoading: true, hasError: false), (isLoading: false, hasError: true) и (isLoading: false, hasError: false).
<img width="1387" height="385" alt="42" src="https://github.com/user-attachments/assets/6ecfa582-e8ff-401c-b60c-8fb7b0a0d709" />
43.Безопасная цепочка вызовов (Deep Null Traversal): Считайте улицу из вложенного объекта компании: user?.company?.address?.street ?? "Адрес не указан".
<img width="1430" height="356" alt="43" src="https://github.com/user-attachments/assets/1f81d9c5-a709-4c92-892b-cc672a5b0441" />
44.Сопоставление типа ответа API: Напишите функцию обработки ответа через сопоставление типов: case int code, case String error, case Map data.
<img width="1458" height="390" alt="44" src="https://github.com/user-attachments/assets/ca8f49eb-72ad-4165-8c1c-12c5df06f460" />
45.Деструктуризация координат точки в цикле: Пройдитесь по списку кортежей List<(int x, int y)> с прямой деструктуризацией for (var (x, y) in points).
<img width="1354" height="212" alt="45" src="https://github.com/user-attachments/assets/3699472b-0640-4081-80ba-fa645b2af907" />
46.Обмен значений двух переменных без третьей: Поменяйте местами значения переменных a и b с помощью синтаксиса кортежей: (a, b) = (b, a).
<img width="1424" height="213" alt="46" src="https://github.com/user-attachments/assets/8edb193f-d957-487e-b23c-e05624da681f" />
47.Валидатор комплексной формы регистрации: Функция возвращает Record ({bool isValid, List<String> errors}) с перечнем всех найденных ошибок формы.
<img width="1776" height="298" alt="47" src="https://github.com/user-attachments/assets/ec6af1bd-673e-43fa-a255-4e25de5779c6" />
48.Обработка диапазона громкости через Switch Guard: Используйте паттерн с условием when: case int v when v > 80 => "Слишком громко!".
<img width="1420" height="262" alt="48" src="https://github.com/user-attachments/assets/ee5ea7f4-eacd-4475-841e-b52be7995f62" />
49.Пайплайн очистки телефонной книги: Дан список List<String?> с поврежденными записями. Очистите его от null, пустых строк и верните Set<String> уникальных нормализованных номеров.
<img width="1415" height="277" alt="49" src="https://github.com/user-attachments/assets/3d9163c6-1e49-40d4-8b6e-3ca7e28ab6ae" />
50.Итоговый аналитический модуль корзины:
Примите корзину покупок в виде List<Map<String, dynamic>>.
Рассчитайте общую стоимость позиций с учетом индивидуальных скидок.
Выделите категории товаров и проверьте бесплатность доставки (от 2000 руб.).
Верните результат в виде именованного кортежа ({double total, double discountAmount, bool isFreeDelivery}).
<img width="1781" height="561" alt="50" src="https://github.com/user-attachments/assets/b93cdbd0-a188-4a18-8b09-ef9a325d5f60" />



