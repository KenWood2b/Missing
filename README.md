# Инструмент для поиска недействительных ссылок в проектах Unity
Инструмент позволяет находить недействительные ссылки, которые мешают запуску проекта
Выбран самый простой спобоб найти и проверить каждую ссылку в искомой облости

## Для использования:
1)	Открыть меню инструмента
2)	Выбрать в какой части проекта нужно искать недействительные ссылки (Текущая сцена, все сцены из сборки, все ассеты, весь проект)
3)	Недействительные ссылку будут отображены как ошибки, при нажатии на которые вы будете направлены к соответствующей точке проекта

### Как работает:
Сканирует всю сцену (или другую часть проекта, которая выбрана пользователем) и проверяет каждую ссылку - куда она ведет и существует ли объект, на который она направлена

#### Пример:
1. В проекте есть неработающая ссылка:

![image](https://github.com/KenWood2b/Missing/assets/146090806/5547350c-d6ec-4151-b2e4-030411daf363)


2. Открываем иструмент и выбираем нужную нам опцию:

![image](https://github.com/KenWood2b/Missing/assets/146090806/f0122977-067f-44de-8382-b1ae73ec2809)


3. Скрипт показывает ошибку с недействительной ссылкой и указывает тип ошибки:

![image](https://github.com/KenWood2b/Missing/assets/146090806/456c74da-3f72-4630-a290-3830205fc2cf)


4. При клике по ошибке объект подсвечиваеться:

![image](https://github.com/KenWood2b/Missing/assets/146090806/75503eda-2aca-48f0-a307-27bbd44a7df4)




