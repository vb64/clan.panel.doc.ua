Пошук атак УР
=============

Якщо ви витрачаєте багато часу на пошук об'єктів для атаки в УР, вам може допомогти функція "Пошук атак УР" сайту клан-панель. 
Дана функція доступна офіцерам кланів у яких діє <a href="{% url action_doc_page page='pricing' %}">платний режим обслуговування</a> (базовий або преміум).

* авторизуватися через посилання "Увійти" у правому верхньому кутку сторінки
* перейти на вкладку "Укріпрайон"
* натиснути зелену кнопку "Пошук атак УР" (доступна лише офіцерам кланів)

На сторіночці "Пошук атак УР"

* виставити зручний вам часовий пояс, по якому відображуватиметься час боїв
* вибрати із списку рівень, що цікавить вас, УР і година оборони противника
* ввести в поле "Макс.позіция рейтингу" значення позиції рейтингу кланів WG. Клани вище за цю позицію в рейтингу не будуть включені в результати пошуку
* нажать кнопку "Знайти"

Список кланів, які мають УР, що відповідає заданим критеріям пошуку і доступні дні для атак в найближчих 2 тижні, відображється у вигляді таблиці.  
Таблиця має наступні колонки:

* тег клану. при кліці перехід на сторінку із списком дат, коли клан можна атакувати
* позиція клану в рейтингу WG
* к-ть будівель в УР клану, окрім Командного центру
* середній рівень будівель УР
* к-ть дат в розкладі клану, доступних для атак

У результати пошуку не включаються клани:

* з якими у вас вже заплановані бої в майбутньому
* бої з якими були менше 7 днів тому
* що входять у ваш союз УР клан-панелі (якщо ви учасник союзу УР)
* обслуговувані в клан-панелі в преміум-режимі

Нижче розташовується посилання на таблицю кланів, що відповідають заданим критеріям пошуку, на які через вказаний час можна буде поставити нову атаку на 2 тижні вперед.  
На момент цієї нової атаки клани не мають нейтралітету, ця нова атака не потрапляє на їх вихідний, і у вас немає з ними запланованих боїв.

.. note::
   Як це працює

   Раз на добу сторінки УР перших декількох тисяч кланів по рейтингу WG скануються і зберігаються в базі даних.  
   Клани, які мають бої в своєму розкладі, протягом доби додатково скануються ще кілька разів з оновленням їх даних в клан-панелі.
