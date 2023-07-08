[![Java CI with Maven](https://github.com/av-starodub/java-project-voting-for-restaurants/actions/workflows/javaci.yml/badge.svg)](https://github.com/av-starodub/java-project-voting-for-restaurants/actions/workflows/javaci.yml)
[![Maintainability](https://api.codeclimate.com/v1/badges/2e0eab04395fe72f07b0/maintainability)](https://codeclimate.com/github/av-starodub/java-project-voting-for-restaurants/maintainability)
[![codecov](https://codecov.io/gh/av-starodub/java-project-voting-for-restaurants/branch/master/graph/badge.svg?token=ZJxHJ2IHEK)](https://codecov.io/gh/av-starodub/java-project-voting-for-restaurants)
---------------------------
## Голосование за рестораны
#### Выпускной проект [стажировки TopJava](https://javaops.ru/view/topjava)

----------------------------

Спроектировать и реализовать REST API, используя  Spring-Boot/Spring Data JPA **без пользовательского интерфейса**.

Задача:

Создайте систему голосования, чтобы выбрать ресторан, где пообедать.

* 2 типа пользователей: администратор и обычные пользователи.
* Админ может добавлять рестораны и их меню на день (обычно 2-5 позиции, название блюда и цену).
* Меню меняется каждый день (обновления делают администраторы).
* Пользователи могут проголосовать за ресторан, в котором они хотят сегодня пообедать.
* Учитывается только один голос от пользователя.
* Если пользователь снова проголосует в тот же день:
    - Если до 11:00, мы предполагаем, что он передумал,
    - Если после 11:00, то уже поздно, голосовать нельзя.

Каждый ресторан предлагает новое меню каждый день.

В результате предоставьте ссылку на репозиторий github. Он должен содержать код, README.md с документацией по API и пару команд curl для его тестирования (**лучше — ссылка на Swagger**).

-----------------------------
P.S.: Убедитесь, что все работает с последней версией, которая есть на github :)  
P.P.S.: Имейте в виду, что ваш API будет использоваться frontend-разработчиком для создания пользовательского интерфейса поверх этого.

-----------------------------
