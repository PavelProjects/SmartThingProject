# SmartThing
_SmartThing_ - платформа для разработки IOT систем.


_Главная цель SmartThing_ - упростить создание IOT систем за счет реализации основного функционала в виде набора библиотек и шаблонов. 


Для создания IOT устройства разработчику необходимо только указать собственную логику работы устройства и добавить необходимости датчики, а вся логика по сохранению настроек, подключение к WiFi, работа с хуками, REST интерфейса и пользовательского интерфейса уже реализована и готова к использованию.


При необходимости можно запустить маршрутизатор и облачный сервис для удобства взаимодействия с устройствами и доступа из глобальной сети. Маршрутизатор позволяет находить устройства в локальной сети, управлять найденными устройствами, составлять простой дашборд, собирать логи с устройств по сети, сохранять настройки устройств.

## Статусы Github Actions

| Проект             | GithubActions |
|:--------------------:|:---------------:|
| SmartThingLib    |[![Validate](https://github.com/PavelProjects/SmartThingLib/actions/workflows/ci-cd.yml/badge.svg)](https://github.com/PavelProjects/SmartThingLib/actions/workflows/ci-cd.yml)</br>[![Update web header](https://github.com/PavelProjects/SmartThingLib/actions/workflows/update-web.yml/badge.svg)](https://github.com/PavelProjects/SmartThingLib/actions/workflows/update-web.yml)|
|SmartThingGateway|[![Validate](https://github.com/PavelProjects/SmartThingGateway/actions/workflows/maven.yml/badge.svg)](https://github.com/PavelProjects/SmartThingGateway/actions/workflows/maven.yml)|
|SmartThingCloud|[![Validate](https://github.com/PavelProjects/SmartThingCloud/actions/workflows/maven.yml/badge.svg)](https://github.com/PavelProjects/SmartThingCloud/actions/workflows/maven.yml)|
|SmartThingLibWeb|[![Validate](https://github.com/PavelProjects/SmartThingLibWeb/actions/workflows/validate.yml/badge.svg)](https://github.com/PavelProjects/SmartThingLibWeb/actions/workflows/validate.yml)</br>[![Trigger web header update in lib](https://github.com/PavelProjects/SmartThingLibWeb/actions/workflows/dispatch-update.yml/badge.svg)](https://github.com/PavelProjects/SmartThingLibWeb/actions/workflows/dispatch-update.yml)|
|SmartThingWeb|[![Validate](https://github.com/PavelProjects/SmartThingWeb/actions/workflows/node.js.yml/badge.svg)](https://github.com/PavelProjects/SmartThingWeb/actions/workflows/node.js.yml)|
|SmartThingBuilder|[![Validate](https://github.com/PavelProjects/SmartThingBuilder/actions/workflows/node.js.yml/badge.svg)](https://github.com/PavelProjects/SmartThingBuilder/actions/workflows/node.js.yml)|


## Архитектура системы
Крайне поверхностное описание взаимодействия компонентов системы
![](https://github.com/PavelProjects/SmartThingProject/blob/main/smt_arch2.jpg?raw=true)

## Проекты платформы
- [SmartThingLib](https://github.com/PavelProjects/SmartThingLib) - библиотека для разработки IOT устройств на базе ESP32
- [SmartThingGateway](https://github.com/PavelProjects/SmartThingGateway) - приложение локального маршрутизатора
- [SmartThingCloud](https://github.com/PavelProjects/SmartThingCloud) - облачное приложение для доступа к маршрутизатору из глобальной сети
- [SmartThingLibWeb](https://github.com/PavelProjects/SmartThingLibWeb) - проект пользовательского интерфейса SmartThingLib
- [SmartThingWeb](https://github.com/PavelProjects/SmartThingWeb) - пользовательский интерфейс маршрутизатора и облака
- [SmartThingBuilder](https://github.com/PavelProjects/SmartThingBuilder) - конструктор устройств на базе SmartThingLib
- [SmartThingTest](https://github.com/PavelProjects/SmartThingTest) - автоматические тесты для SmartThingLib

## Примеры использования
- [Метео станция](https://github.com/PavelProjects/meteo_station)
- [Автоматиечские жалюзи](https://github.com/PavelProjects/SmarThingtLouver)
