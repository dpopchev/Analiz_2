# Анализ 2

Тук се намират материали преподадени в **семинарните занятия** през *летния семестър*
на учебната *2020/2021* на специалност:
- Хидростроителство **Вторник от 8и30 до 11**

## Конспект

1. семинар
    - ОДУ с разделящи се променливи
    - Хомогенни ДУ
    - Уравнения приводими към хомогенни
1. семинар
    - Линейни ДУ от първи ред
    - Уравнения на Бернули и Рикати
1. семинар
    - Точни ДУ
    - Уравнения допускащи интегриращ множител
    - Някои ДУ нерешени спрямо производната
1. семинар
    - Уравнения на Лагранж и Клеро
    - ДУ от по-висок ред, допускащи понижение на реда
1. семинар
    - Линейни хомогенни ДУ от n-ти ред с постоянни коефициенти -- общо решение
    - Нехомогенни уравнения със специална дясна част
1. семинар
    - Нехомогенни линейни ДУ със специална дясна част
    - Метод на Лагранж
1. семинар
    - ДУ на Ойлер
    - Общи задачи
1. семинар
    - Линейни хомогенни системи ДУ с постоянни коефициенти
    - Метод на Лагранж за нехомогенни системи
1. семинар
    - Векторна функция на скаларен аргумент
    - Непрекъснати и гладки криви
    - Кривина и торзия
1. семинар
    - Непрекъсната и гладка повърхнина
1. семинар
    - Пресмятане на кратни интеграли
1. семинар
    - Смяна на променливите в двоен и троен интеграл
1. семинар
    - Несобствени интеграли
1. семинар
    - Криволинеен интеграл от първи и втори тип
1. семинар
    - Приложения на кратни и криволинейни интеграли

# Оценяване

**БЕЗ ЗАДАЧИ И ВЪПРОСИ, КОИТО НЕ СА ПРЕДСТАВЕНИ В ТОВА РЕПО**

**МОЛЯ СЛЕДТЕ ЗА ПРОМЕНИ**

## Типове задачи

| Тип задача | Описание | Очаквано време | Типове точки |
|-|:-:|-|:-:|
| Затворена | Въпрос с предоставени 4 възможни отговора, от които само 1 е верен. | ~1min | A |
| Аналитична | Задача, която изисква прилагане на поредица от аналитични действия за достигане на резултат във вид на формула или заключение. | ~5min | A, M, B |
| Отворена | Многостъпкова задача, в която се изисква цитиране на дефиниция  или записване на обща формула, тълкуването и прилагането ѝ.  | 1+min | A, M, B |

## Типове точки

| Тип точка | Описание | Зависи от |
|-|:-:|-|
| A | Точка за верен и точен отговор или междинна стъпка  (заб: освен ако не е изрично указано,  числените отговори трябва да са до две значещи цифри). Дава се само, когато е присъдена съответна точка тип M. | M |
| M | Точка за правилно приложен метод. Присъжда се само при демонстрирано разбиране на метода, иначе казано не е достатъчно само записване на формула без да се заместят съответните членове.  Точката се дава дори само да е заместено във формулата, без да е изрично записана. Точката не се отнема при числени или алгебрични грешки. |  |
| B | Точка независеща от други точки. |  |

# Генериране на теми

За генериране на определена тема:

```
make ODE_rezdeliashti_promenlivi
```

За генериране на всички теми от семинар:

```
make seminar_1
```

Презентациите ще се намират в `build`.
