МИНИСТЕРСТВО НАУКИ  И ВЫСШЕГО ОБРАЗОВАНИЯ РОССИЙСКОЙ ФЕДЕРАЦИИ  
Федеральное государственное автономное образовательное учреждение высшего образования  
"КРЫМСКИЙ ФЕДЕРАЛЬНЫЙ УНИВЕРСИТЕТ им. В. И. ВЕРНАДСКОГО"  
ФИЗИКО-ТЕХНИЧЕСКИЙ ИНСТИТУТ  
Кафедра компьютерной инженерии и моделирования
<br/><br/>
​
### Отчёт по лабораторной работе № XX<br/> по дисциплине "Программирование"
<br/>
​
студента 1 курса группы ХХХХХХХХ  
Фамилия Имя Отчество  
направления подготовки 09.03.0Х "ХХХХХХХХХХХХХХХХХХХХХ"  
<br/>
​
<table>
<tr><td>Научный руководитель<br/> старший преподаватель кафедры<br/> компьютерной инженерии и моделирования</td>
<td>(оценка)</td>
<td>Чабанов В.В.</td>
</tr>
</table>
<br/><br/>
​
Симферополь, 2019
# Laboratory-work-1
Изучение базовых возможностей MS Visual Studio.
## **Цель:** изучить основные возможности создания и отладки программ в IDE MS Visual Studio.
## **Ход работы**
### 1.Как создать консольное приложение С++?
#### * В Visual Studio откройте  **файл**  меню и выберите  **New**  >  **проекта**  открыть  **создайте новый проект**  диалоговое окно.  Выберите  **консольное приложение**  шаблона, а затем выберите  **Далее**.
![](https://docs.microsoft.com/ru-ru/cpp/build/media/vs2019-choose-console-app.png?view=vs-2019)
#### * В  **настроить новый проект**  диалоговом окне введите  название проекта.  Выберите  **создать**  для создания проекта.
![](https://docs.microsoft.com/ru-ru/cpp/build/media/vs2019-configure-new-project-hello-world.png?view=vs-2019)
### 2.Как изменить цветовую схему (оформление) среды?
#### * Для того, чтобы изменить фон в Visual Studio, необходимо в строке меню нажать кнопку “Средства”, затем выбрать пункт “Параметры”.
![](https://sun9-28.userapi.com/c855128/v855128310/f423b/2FYB_GwEUYY.jpg)
#### * В появившемся окне “Параметры” нажать на группу “Общие” (слева) и в выпадающем списке “Цветовая тема” (справа) выбрать нужную тему: “Светлую”, “Синюю” или “Темную”.
![](https://vscode.ru/wp-content/uploads/2016/08/changeThemeInVisualStudio2.png)
#### * Для завершения нажмите кнопку “ОК”. Готово!
### 3.Как закомментировать/раскомментировать блок кода средствами VS?
#### * Выберите строки, которые вы хотите комментировать/раскомментировать.
#### * Выполните команду  `editor.action.commentLine`  (ярлык по умолчанию в Windows:  `CTRL + /`)

**или**

выполните команду  `editor.action.addCommentLine`  (ярлык по умолчанию в Windows:  `ctrl+k ctrl+c`) соответственно  `editor.action.removeCommentLine`  (ярлык по умолчанию в Windows:  `ctrl+k ctrl+u`)
![](https://sun9-62.userapi.com/c855128/v855128310/f42c5/e0eggVLz8UM.jpg)
### 4.Как открыть в проводнике Windows папку с проектом средствами VS?
#### * Для того,чтобы открыть папку в проводнике,нужно открыть проект и в правом верхнем углу нажать правой кнопкой мыши **Решение (название проекта)**.
![](https://sun9-60.userapi.com/c855128/v855128945/f96e2/Gq0QO1-zX44.jpg)
#### * Нажимаем **открыть папку в проводнике** и готово!
### 5.Какое расширение файла-проекта используется в VS?
### 6.Как запустить код без отладки?
#### * Из **конфигурации** раскрывающегося списка на **стандартный** панели инструментов, выберите **Запуск без отладки**.
#### * Также это можно сделать сочетанием клавиш **Ctrl+F5**.
![](https://sun9-25.userapi.com/c855128/v855128427/f932d/8_69gYFqi3Q.jpg)
### 7.Как запустить код в режиме отладки?
#### * Из **конфигурации** раскрывающегося списка на **стандартный** панели инструментов, выберите **Отладка**.
#### * Чтобы начать отладку, щелкните зеленый **запустить** стрелку на панели инструментов или выберите **Отладка** > **начать отладку**, или нажмите клавишу **F5**.
![](https://sun9-25.userapi.com/c855128/v855128427/f932d/8_69gYFqi3Q.jpg)
### 8.Как установить/убрать точку останова (breakpoint)?
#### * Чтобы установить точку останова в исходном коде, щелкните в крайнем левом поле рядом со строкой кода.  Можно также выбрать строку и нажать клавишу  **F9**  или выберите  **Отладка**  >  **точка останова**и щелкните правой кнопкой мыши и выберите  **точки останова**  >  **Вставить точку останова**.  Точка останова отображается в виде красной точки в левом поле.
![](https://sun9-49.userapi.com/c853624/v853624427/1008b4/sCqye8D4wm4.jpg)
#### * Чтобы отключить точку останова, не удаляя его, наведите указатель мыши или щелкните его правой кнопкой мыши и выберите  **отключить точку останова**.  Отключенные точки останова отображаются как пустые точки в левом поле или  **точки останова**  окна.  Чтобы снова включить точку останова, наведите указатель мыши или щелкните его правой кнопкой мыши и выберите  **Включить точку останова**.
### 9.Создал программу со следующим кодом:
![](https://sun9-5.userapi.com/c851032/v851032427/1c7bdb/4nwb1lY3oEc.jpg)
#### * Переключился в конфигурацию сборки **Debug**;
#### * Установил breakpoint на 5 и 6 строках;
![](https://sun9-9.userapi.com/c851220/v851220098/1d4d9e/rzGhOzOwfbs.jpg)
#### * Запустил приложение в режиме отладки. Использовал Кнопку **Продолжить** или **Шаг с обходом** для перемещения к следующей точке останова;
![](https://sun9-5.userapi.com/c851032/v851032098/1c50a9/rdWaaQkhmW8.jpg)
#### * В пятой строчке кода i принимает значение 5.
#### * В шестой строчке кода i принимает значение 5.
![](https://sun9-44.userapi.com/c851032/v851032098/1c50d5/0aiuK5EWGa0.jpg)
### 10.Создал программу со следующим кодом:
![](https://sun9-67.userapi.com/c851032/v851032098/1c5103/S6y0R1pR3ic.jpg)
#### * Переключился в конфигурацию сборки **Debug**;
#### * Установил breakpoint на 5 и 6 строках;
![](https://sun9-39.userapi.com/c851220/v851220098/1d4ce7/0Iiz7RKjABI.jpg)
#### * Запустил приложение в режиме отладки. Используйте Кнопку **Продолжить** или **Шаг с обходом** для перемещения к следующей точке останова;
![](https://sun9-30.userapi.com/c851032/v851032098/1c5147/0YMQFoUplmY.jpg)
#### * В пятой строчке кода i принимает значение 5.
#### * В шестой строчке кода i принимает значение 5.0000000000000000.
![](https://sun9-31.userapi.com/c851220/v851220098/1d4d70/FcO2QVKG0nE.jpg)
### Вывод:изучил основные возможности создания и отладки программ в IDE MS Visual Studio.
