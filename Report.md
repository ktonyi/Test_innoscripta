## Тестовое задание для компании 
## Innoscripta
Watch videos: 
- Find as many bugs as u can;
- Record them; 
- Create bug reports in any convenient form; 
- If you have any proposals to enhance the system - feel free to write them.


### Тестирование crm системы по заранее записанным видео с описанием функциональности:

# Баг-1
## Описание: В меню выбора отображена пустая кнопка.
### Шаги воспроизведения:
1. Открыть http://crm.innoscripta.com/login
2. Войти в систему используя валидные данные пользователя.
- Ожидаемый результат: Все кнопки в меню имеют присвоенное значение.
- Фактический результат: В меню отображается пустая кнопка.
![](https://user-images.githubusercontent.com/77203425/142514946-4f1eba58-7122-4740-ab8d-0aee49f3b086.png)
### Окружение:
 Win 7,
Google chrome Версия 96.0.4664.45 
Video 1


# Баг-2
## Описание: Текст выходит за границы после смены вида отображения.
### Предусловие: Необходимо авторизоваться в http://crm.innoscripta.com/login
### Шаги воспроизведения:
1. Перейти по Revenue and Planning в раздел Ideen.
2. Изменить отображение нажав на кнопку под Change View.
- Ожидаемый результат: Текст описания отображается ровно.
- Фактический результат: Текст описания выходит за границы и наслаивается на следующий.
![](https://user-images.githubusercontent.com/77203425/142514947-18b2459e-0aab-4aa9-bd5e-46571a6ab3b9.png) 
### Окружение:
 Win 7,
Google chrome Версия 96.0.4664.45 
Video 2



# Баг-3
## Описание: Языковое несоответствие в разделе RP.
### Предусловие: Необходимо авторизоваться в http://crm.innoscripta.com/login
### Шаги воспроизведения:
1. Перейти по Revenue and Planning
- Ожидаемый результат: Все кнопки меню отображены на Английском языке.
- Фактический результат: Кнопка Ideen – немецкий язык.
![](https://user-images.githubusercontent.com/77203425/142514949-258a4ded-f333-4642-a3ba-8e6548092b4b.png)
### Окружение:
 Win 7,
Google chrome Версия Версия 96.0.4664.45 
Video 2







## Часть 2
### Inspect those sites: 
- http://sff.innoscripta.com/ 
- http://ideas.innoscripta.com/ 
- https://innoscripta.com/ 
#### Find as many bugs as you can and record them, create bug records.


# Баг – 1
### Описание: Поле ввода принимает не валидные значения email.
### Шаги воспроизведения:
1. Перейти на сайт https://sff.innoscripta.com/
2. Пролистать вниз до поля ввода с надписью «Wir stellen mit Ihnen in einem unverbindlichen Termin fest, ob wir zueinander passen»
3. Ввести валидные значения в поле Varname Nachname
4. В поле email ввести «2»
5. Нажать «Absenden»

- Ожидаемый результат: Поле ввода email подчеркнуто красным, появляется сообщение о допустимом вводе.
- Фактический результат: Открывается окно для заполнения данных.

![](https://user-images.githubusercontent.com/77203425/142514937-70dac86f-8ecb-46f3-abfb-27a1e869ab9d.mp4)
### Окружение:
 Win 7,
Google chrome Версия 96.0.4664.45




# Баг – 2
### Описание: Некорректные названия университета в выпадающем списке. 
### Шаги воспроизведения:
1. Перейти на сайт http://ideas.innoscripta.com/
2. Нажать на кнопку «Registrieren»
3. В появившемся окне открыть выпадающий список 


- Ожидаемый результат: Указаны корректные названия университетов.
- Фактический результат: В списке присутствуют некорректные названия.
![](https://user-images.githubusercontent.com/77203425/142514945-3456cba7-13ba-4ed3-98b5-495fe6542bdf.png)
![](https://user-images.githubusercontent.com/77203425/142514943-d2ef9d3e-f25b-488f-8124-0801c824098b.png)
### Окружение:
 Win 7,
Google chrome Версия 96.0.4664.45 



# Баг – 3
### Описание: Некорректные названия университета в выпадающем списке. 
### Шаги воспроизведения:
1. Перейти на сайт http://ideas.innoscripta.com/
2. Нажать на кнопку «Registrieren»
3. В появившемся окне заполнить поля валидными данными
4. В поле «telefon» поставить знак «+».
5. Нажать «Weiter» 


- Ожидаемый результат: Поле телефон подчеркнуто красным появляется сообщение о ошибке.
- Фактический результат: Форма успешно заполняется.

![](https://user-images.githubusercontent.com/77203425/142514921-3a645769-48c2-47e8-8d6b-f14c20140f79.mp4
)
### Окружение:
 Win 7,
Версия 96.0.4664.45 

to be end

