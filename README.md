# SmartThing
_SmartThing_ - платформа для разработки IOT систем.


_Главная цель SmartThing_ - упростить создание IOT систем за счет реализации основного функционала в виде набора библиотек и шаблонов. 


Для создания IOT устройства разработчику необходимо только указать собственную логику работы устройства и добавить необходимости датчики, а вся логика по сохранению настроек, подключение к WiFi, работа с хуками, REST интерфейса и пользовательского интерфейса уже реализована и готова к использованию.


При необходимости можно запустить маршрутизатор и облачный сервис для удобства взаимодействия с устройствами и доступа из глобальной сети. Маршрутизатор позваоляет находить устройства в локальной сети, управлять найденными устройствами, составлять простой дашборд, собирать логи с устройств по сети, сохранять настройки устройств.

## Архитектура системы
![](https://github.com/PavelProjects/SmartThingProject/blob/main/smt_arch.jpg?raw=true&)

## Проекты платформы
- [SmartThingLib - библиотека для разработки IOT устройств на базе ESP32](https://github.com/PavelProjects/SmartThingLib)
- [SmartThingGateway - приложение локального маршрутизатора](https://github.com/PavelProjects/SmartThingGateway)
- [SmartThingCloud - облачное приложение для доступа к маршрутизатору из глобальной сети](https://github.com/PavelProjects/SmartThingCloud)
- [SmartThingWeb - пользовательский интерфейс маршрутизатора и облака](https://github.com/PavelProjects/SmartThingWeb)
- [SmartThingBuilder - конструктор устройств на базе SmartThingLib](https://github.com/PavelProjects/SmartThingBuilder)
- [SmartThingTest - автоматические тесты для SmartThingLib](https://github.com/PavelProjects/SmartThingTest)
- [SmartThingLibWeb - проект пользовательского интерфейса SmartThingLib](https://github.com/PavelProjects/SmartThingLibWeb)

## Примеры использования
- [Метео станция](https://github.com/PavelProjects/meteo_station)
- [Автоматиечские жалюзи](https://github.com/PavelProjects/SmarThingtLouver)
