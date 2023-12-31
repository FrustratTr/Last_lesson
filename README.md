# Внедрение автоматизации. 
## Виды тестирования:
* Дымовое тестирование - проверяем, что работает вкладка «Каталог курсов» и путь к ней;
* Функциональное тестирование - проверяем функциональность на соответствие требованиям;
## Перечень автоматизируемых сценариев:
### Переход на страницу профессии:
* Переход на страницу профессии с главной страницы сайта;
1. Переход на страницу профессии через иконку "программирование" в разделе "направления обучения" без фильтрации курсов:
1. Кликнуть на иконку "программирование" в разделе "направления обучение";
1. После перехода на страницу с курсами кликнуть на профессию "Тестировщик ПО";
1. Дождаться перехода на страницу профессии;
* Переход на страницу профессии через иконку "программирование" в разделе "направления обучения" с фильтрацией курсов:
1. Кликнуть на иконку "программирование" в разделе "направления обучение"
1. После перехода на страницу с курсами в фильтрах "уровень" задать "новичкам", в фильтре "стоимость" - "платное"
1. После фильтрации курсов кликнуть на профессию "Тестировщик ПО"
1. Дождаться перехода на страницу профессии;
* Переход на страницу профессии через иконку "Полный каталог" в разделе "направления обучения" без фильтрации курсов:
1. Кликнуть на иконку "Полный каталог" в разделе "направления обучения"
1. После перехода на страницу с курсами кликнуть на профессию "Тестировщик ПО"
1. Дождаться перехода на страницу профессии;
* Переход на страницу профессии через иконку "Полный каталог" в разделе "направления обучения" с фильтрацией курсов:
1. Кликнуть на иконку "Полный каталог" в разделе "направления обучения"
1. После перехода на страницу с курсами в фильтре "направление" задать "программирование", в фильтре "уровень" - "новичкам", в фильтре "стоимость" - "платное"
1. После фильтрации курсов по заданным параметрам кликнуть на профессию "Тестировщик ПО"
1. Дождаться перехода на страницу профессии;
* Переход на страницу профессии напрямую из каталога курсов:
1. Кликнуть на кнопку "каталог курсов"
1. Навести мышку на строку "программирование" 
1. Скрольнуть мышку и в предложенном списке в разделе "для начинающих" кликнуть на профессию "Тестировщик ПО" 
1. Дождаться перехода на страницу профессии;
* Переход на страницу профессии через "каталог курсов" и "страницу курсов" без фильтрации курсов:
1. Кликнуть на "каталог курсов"
1. Навести мышку на строку "программирование" и кликнуть
1. После перехода на страницу с курсами выбрать профессию "Тестировщик ПО" и кликнуть
1. Дождаться перехода на страницу профессии;
* Переход на страницу профессии через "каталог курсов" и "страницу курсов" с фильтрацией курсов:
1. Кликнуть на "каталог курсов"
1. Навести мышку на строку "программирование" и кликнуть
1. После перехода на страницу с курсами задать в фильтре "уровень" параметр "новчикам", в фильтре "стоимость" - "платное"
1. После фильтрации курсов по заданным параметрам кликнуть на профессию "Тестировщик ПО"
1. Дождаться перехода на страницу профессии;
* Переход на страницу профессии через "полный каталог" курсов без фильтрации курсов:
1. Кликнуть на "каталог курсов"
1. Кликнуть на строку "полный каталог"
1. После перехода на страницу с курсами кликнуть на профессию "Тестировщик ПО"
1. Дождаться перехода на страницу профессии;
* Переход на страницу профессии через "полный каталог" курсов с фильтрацией курсов:
1. Кликнуть на "каталог курсов"
1. Кликнуть на строку "полный каталог"
1. После перехода на страницу с курсами в фильтре "направление" задать "программирование", в фильтре "уровень" - "новичкам", в фильтре "стоимость" - "платное"
1. После фильтрации курсов кликнуть на профессию "Тестировщик ПО"
1. Дождаться перехода на страницу профессии;
   
### Переход на форму записи:
* Переход нажатием на кнопку "записаться" в превью курса:
1. Со страницы профессии в превью курса нажать на кнопку "записаться"
1. Дождаться, пока страница пролистается до формы записи;
   
* Переход нажатием кнопки "записаться" в заголовке сайта при просмотре информации о курсе:
1. Нажать на кнопку "посмотреть программу" в привью курса
1. После пролистывания страницы нажать на кнопку "записаться" в заголовке сайта;

* Переход на форму записи пролистыванием страницы:
1. Пролистать страницу до формы записи на курс;

### Заполнение формы записи:
* Позитивные сценарии:
1. Проверяем что будет, если правильно заполнить форму валидными значениями (Имя создать с помощью фейкера на русском, номер и почту также с помощью фейкера, нажать кнопку "Записаться");
1. Проверяем что будет, если правильно заполнить форму валидными значениями (Имя сделать двойное, с дефисом, номер и почту с помощью фейкера, нажать кнопку "Записаться");

**_Ожидаемые результаты:_**
1. Появится надпись "Спасибо, мы с вами свяжемся" и произойдет перехода на главную страницу.
1. Появится надпись "Спасибо, мы с вами свяжемся" и произойдет перехода на главную страницу.

* Негативные сценарии:
1. Проверяем что будет, если заполнить все поля, кроме имени;
1. Проверяем что будет, если заполнить все поля, кроме номера;
1. Проверяем что будет, если заполнить все поля, кроме почты;
1. Проверяем на некорректность заполнения формы, ставим на поле имя значение из фейкера, но на английском языке;
1. Проверяем на некорректность заполнения формы, ставим на поле имя значение в один символ русской буквы;
1. Проверяем на некорректность заполнения формы, ставим на поле номер значение, на единицу меньше правильного числа цифр в номере;
1. Проверяем на некорректность заполнения формы, ставим на поле номер значение, на единицу больше правильного числа цифр в номере;
1. Проверяем поле Имя граничными значениями.

**_Ожидаемые результаты:_**
1. Появится надпись, что поле обязательно для заполнения;
1. Появится надпись, что поле обязательно для заполнения;
1. Появится надпись, что поле обязательно для заполнения;
1. Появится надпись, что неправильно введено значение;
1. Появится надпись, что неправильно введено значение;
1. Появится надпись, что неправильно введено значение;
1. Появится надпись, что неправильно введено значение или номер должен состоять из 10 цифр;
1. Появится надпись, что неправильно введено значение;

### Перечень используемых инструментов:
* Java - язык, на котором будем писать код;
* Selenide для взаимодействия со страницей в браузере;
* JUnit 5 - библиотека для тестирования;
* Faker - генерация пользовательских данных (имени, телефона и почты);
* IntelliJ IDEA - программа, для написания кода;
* Gradle - система автоматической сборки;
* Allure - для анализа отчетов.

### Перечень необходимых разрешений, данных и доступов:
1. Разрешение на доступ к базе данных сервера;
1. Предоставление тестовых аккаунтов для записи на курс.
1. Разрешение на тестирование страниц сайта с помощью автоматизированного ПО;

### Перечень и описание возможных рисков при автоматизации:
1. Селекторы могут измениться, из-за этого придется править код.
1. Форма записи может видоизменяться через какое-то время и обновления.
3. Долгое открытие страницы сайта, либо вкладки.
4. Результаты теста могут несколько искажаться, в связи с тем, что отсутствует доступ к реальной БД пользователей.
   
### Перечень необходимых специалистов для автоматизации:
* специалист по ручному тестированию
* специалист автоматизированного тестирования

### Интервальная оценка с учётом рисков (в часах):
* Время, необходимое на тестирование, составляет 8 часов.
* С учетом рисков состалвяет 11 часов.  
    
