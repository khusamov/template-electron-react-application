boilerplate-electron-react
==========================

Шаблон приложения на ElectronJs + ReactJS + Material UI.

Пакеты
------

### electron-wrapper-on-electronforge

Попытка сделать приложение на ElectronJS. Не удачная. JS-вариант не запускается
из-за Лерны. Он что-то ищет в своем локальном node_modules из того, что находится
в node_modules, который на два уровня выше.

TS-вариант не хочет устанавливаться. Не находит шаблон. 
Установка шаблона вручную не помогает. Ничего не работает.

### react-application-example

В этом пакете будет ReactJS-приложение, которое будет подключаться в 
приложении из пакета `electron-wrapper-on-electronforge`.