# Проекты в Яндекс.Практикум
В данном репозитории представлены проекты, которые я выполнил в рамках курса "Специалист по Data Science" в Яндекс.Практикуме.

| № | Название | Описание | Используемые инструменты |
| :---: | :---: | --- | :---: |
| 1 | Яндекс.Музыка | Цель исследования — проверить три гипотезы: <br /> 1. Активность пользователей зависит от дня недели. Причём в Москве и Петербурге это проявляется по-разному. <br /> 2. В понедельник утром в Москве преобладают одни жанры, а в Петербурге — другие. Так же и вечером пятницы преобладают разные жанры — в зависимости от города. <br /> 3. Москва и Петербург предпочитают разные жанры музыки. В Москве чаще слушают поп-музыку, в Петербурге — русский рэп. | `Python`, `Pandas` |
| 2 | Исследование надёжности заёмщиков | Заказчик — кредитный отдел банка. Нужно разобраться, влияет ли семейное положение и количество детей клиента на факт погашения кредита в срок. Входные данные от банка — статистика о платёжеспособности клиентов. <br /> Результаты исследования будут учтены при построении модели кредитного скоринга — специальной системы, которая оценивает способность потенциального заёмщика вернуть кредит банку. <br /> Заказчику необходимы ответы на следующие вопросы: <br /> 1. Есть ли зависимость между наличием детей и возвратом кредита в срок? <br />2. Есть ли зависимость между семейным положением и возвратом кредита в срок? <br /> 3. Есть ли зависимость между уровнем дохода и возвратом кредита в срок? <br /> 4. Как разные цели кредита влияют на его возврат в срок? | `Предобработка данных`, `Python`, `Pandas` |
| 3 | Исследование объявлений о продаже квартир | В нашем распоряжении данные сервиса Яндекс.Недвижимость — архив объявлений о продаже квартир в Санкт-Петербурге и соседних населённых пунктах за несколько лет. Нужно научиться определять рыночную стоимость объектов недвижимости. Наша задача — установить параметры. Это позволит построить автоматизированную систему: она отследит аномалии и мошенническую деятельность. <br /> По каждой квартире на продажу доступны два вида данных. Первые вписаны пользователем, вторые получены автоматически на основе картографических данных. Например, расстояние до центра, аэропорта, ближайшего парка и водоёма. | `Предобработка данных`, `Исследовательский анализ данных`, `Визуализация данных`, `Python`, `Pandas`, `Matplotlib` |
| 4 | Определение перспективного тарифа для телеком-компании | Я - аналитик компании «Мегалайн» — федерального оператора сотовой связи. Клиентам предлагают два тарифных плана: «Смарт» и «Ультра». Чтобы скорректировать рекламный бюджет, коммерческий департамент хочет понять, какой тариф приносит больше денег. <br /> Для этого мне предоставили данные 500 пользователей «Мегалайна»: кто они, откуда, каким тарифом пользуются, сколько звонков и сообщений каждый отправил за 2018 год. Нужно проанализировать поведение клиентов и сделать вывод — какой тариф лучше. | `Описательная статистика`, `Проверка статистических гипотез`, `Python`, `Pandas`, `Matplotlib`, `NumPy`, `SciPy` |
| 5 | Планирование рекламных кампаний в игровой индустрии для интернет-магазина "Стримчик" | Мы работаем в интернет-магазине «Стримчик», который продаёт по всему миру компьютерные игры. Из открытых источников доступны исторические данные о продажах игр, оценки пользователей и экспертов, жанры и платформы (например, Xbox или PlayStation). Перед нами данные до 2016 года. Представим, что сейчас декабрь 2016 г., и мы планируем кампанию на 2017-й. Нам нужно выявить определяющие успешность игры закономерности. Это позволит сделать ставку на потенциально популярный продукт и спланировать рекламные кампании. |
| 6 | Рекомендация тарифов мобильной связи | Оператор мобильной связи «Мегалайн» выяснил: многие клиенты пользуются архивными тарифами. Они хотят построить систему, способную проанализировать поведение клиентов и предложить пользователям новый тариф: «Смарт» или «Ультра». <br /> В нашем распоряжении данные о поведении клиентов, которые уже перешли на тарифы, которые мы исследовали в одном из прошлых проектов. <br /> Теперь нам необходимо построить модель для задачи классификации, которая выберет подходящий новый тариф для пользователей, которые в настоящее время пользуются архивными тарифами. | `Python`, `Pandas`, `Matplotlib`, `Scikit-learn` |
| 7 | Отток клиентов | Из «Бета-Банка» стали уходить клиенты. Каждый месяц. Немного, но заметно. Банковские маркетологи посчитали: сохранять текущих клиентов дешевле, чем привлекать новых. <br /> Нужно спрогнозировать, уйдёт клиент из банка в ближайшее время или нет. Нам предоставлены исторические данные о поведении клиентов и расторжении договоров с банком. |
| 8 | Выбор локации для скважины | Мы работаем в добывающей компании «ГлавРосГосНефть». Нам поставили задачу - решить, где бурить новую скважину. <br /> Для решения задачи нам были предоставлены пробы нефти в трёх регионах: в каждом 10 000 месторождений, где измерили качество нефти и объём её запасов. По этим данным мы построим модель машинного обучения, которая поможет определить регион, где добыча принесёт наибольшую прибыль. Далее мы проанализируем возможную прибыль и риски, используя технику Bootstrap. |
| 9 | Восстановление золота из руды | Нам необходимо подготовить прототип модели машинного обучения для «Цифры». Компания разрабатывает решения для эффективной работы промышленных предприятий. <br /> Модель должна предсказать коэффициент восстановления золота из золотосодержащей руды. Для работы используем данные с параметрами добычи и очистки. <br /> Модель поможет оптимизировать производство, чтобы не запускать предприятие с убыточными характеристиками. |
| 10 | Защита персональных данных клиентов | Нам нужно защитить данные клиентов страховой компании «Хоть потоп». Разработаем такой метод преобразования данных, чтобы по ним было сложно восстановить персональную информацию. Нужно защитить данные, чтобы при преобразовании качество моделей машинного обучения не ухудшилось. |
| 11 | Определение стоимости автомобилей | Сервис по продаже автомобилей с пробегом «Не бит, не крашен» разрабатывает приложение для привлечения новых клиентов. В нём можно быстро узнать рыночную стоимость своего автомобиля. В моем распоряжении исторические данные: технические характеристики, комплектации и цены автомобилей. Мне нужно построить модель для определения стоимости. |
| 12 | Прогнозирование заказов такси | Компания «Чётенькое такси» собрала исторические данные о заказах такси в аэропортах. Чтобы привлекать больше водителей в период пиковой нагрузки, нужно спрогнозировать количество заказов такси на следующий час. Построим модель для такого предсказания. |
| 13 | Проект для «Викишоп» | Интернет-магазин «Викишоп» запускает новый сервис. Теперь пользователи могут редактировать и дополнять описания товаров, как в вики-сообществах. То есть клиенты предлагают свои правки и комментируют изменения других. Магазину нужен инструмент, который будет искать токсичные комментарии и отправлять их на модерацию. Меобходимо обучить модель классифицировать комментарии на позитивные и негативные. В нашем распоряжении набор данных с разметкой о токсичности правок. |
| 15 | Определение возраста покупателей | Сетевой супермаркет «Хлеб-Соль» внедряет систему компьютерного зрения для обработки фотографий покупателей. Фотофиксация в прикассовой зоне поможет определять возраст клиентов, чтобы: <br /> 1. Анализировать покупки и предлагать товары, которые могут заинтересовать покупателей этой возрастной группы; <br /> 2. Контролировать добросовестность кассиров при продаже алкоголя.<br />Постройте модель, которая по фотографии определит приблизительный возраст человека. В вашем распоряжении набор фотографий людей с указанием возраста. |
| 16 | Промышленность | Чтобы оптимизировать производственные расходы, металлургический комбинат ООО «Так закаляем сталь» решил уменьшить потребление электроэнергии на этапе обработки стали. Нам предстоит построить модель, которая предскажет температуру стали. |
