# Задача: "Калькулятор"

## Описание:
Создай консольное приложение "Калькулятор".
Приложение должно читать из консоли введенные пользователем арифметические операции и выводить в консоль результат их выполнения.

## Требования:

1. Калькулятор умеет выполнять операции сложения, вычитания, умножения и деления с двумя числами:
a + b, a - b, a * b, a / b.  <b> Данные передаются в одну строку (смотри пример)! Решения, в которых каждое число и арифмитеческая операция передаются с новой строки считаются неверными. </b>
2. Калькулятор умеет работать как с арабскими (1,2,3,4,5...), так и с римскими (I,II,III,IV,V...) числами.
3. Калькулятор должен принимать на вход числа от 1 до 10 включительно, не более. На выходе числа не ограничиваются по величине и могут быть любыми.
4. Калькулятор умеет работать только с целыми числами.   
5. Калькулятор умеет работать только с арабскими или римскими  цифрами одновременно, при вводе пользователем строки вроде 3 + II калькулятор должен выбросить исключение и прекратить свою работу.
6. При вводе римских чисел, ответ должен быть выведен римскими цифрами, соответственно, при вводе арабских - ответ ожидается арабскими.
7. При вводе пользователем неподходящих чисел приложение выбрасывает исключение и завершает свою работу.
8. При вводе пользователем строки, не соответствующей одной из вышеописанных арифметических операций, приложение выбрасывает исключение и завершает свою работу.
9. Результатом операции деления является целое число, остаток отбрасывается. 
10. Результатом работы калькулятора с арабскими числами могут быть отрицательные числа и ноль. Результатом работы калькулятора с римскими числами могут быть только положительные числа, если результат работы меньше единицы, выбрасывается исключение

## Пример работы программы:
###### Input:
`1 + 2`
###### Output:
`3`
###### Input:
`VI / III`
###### Output:
`II`
###### Input:
`I - II`
###### Output:
`throws Exception //т.к. в римской системе нет отрицательных чисел`
###### Input:
`I + 1`
###### Output:
`throws Exception //т.к. используются одновременно разные системы счисления `
###### Input:
`1`
###### Output:
`throws Exception //т.к. строка не является математической операцией `
###### Input:
`1 + 2 + 3`
###### Output:
`throws Exception //т.к. формат математической операции не удовлетворяет заданию - два операнда и один оператор (+, -, /, *) `
 
## Принципы оценки работы:
Обрати внимание на принципы ООП, постарайся разбить программу на логические классы. <ins> Решения, в которых весь код программы находится в одном классе будут низко оценены.</ins> Продемонстрируй своё умение в работе с разными синтаксическими конструкциями, не забудь про исключительные ситуации, при которых выполнение программы невозможно из-за некорректных входных данных. 

## Как отправить решение?
1. Тебе нужно создать собственный репозиторий на Github и добавить туда проект с решением.
2. Ссылку на репозиторий отправь нам на почту *info@java-mentor.com* с темой **Тестовое задание калькулятор Java**.  

---
# FAQ

### Что, если я не знаю Java?

1. Начни с установки JDK c сайта ORACLE - [скачать](https://www.oracle.com/ru/java/technologies/javase-downloads.html). Подойдет любая версия выше 8-й включительно. Обрати внимание, после выбора версии ОС перед началом загрузки необходимо создать учетную запись на сайте ORACLE.
2. Эти материалы помогут вам в установке и настройке JDK:
    - [Установка и настройка JDK ](https://www.youtube.com/watch?v=0OrVOHB42C4) (Перед просмотром видео не забудь, пожалуйста, включить русские субтитры :)
)
    - [Установка JDK и IntelliJ Idea:]( https://www.youtube.com/watch?v=xvUFqDKIKJE)
3. Установи среду разработки (мы рекомендуем IntelliJ IDEA) и напиши свою первую маленькую программу на Java.

### Какую среду разработки мне выбрать?

Мы не ограничиваем тебя в выборе, ты можешь реализовать свой проект в любой удобной среде разработки:
- IntelliJ IDEA - [скачать.](https://www.jetbrains.com/ru-ru/idea/download/)
- Eclipse - [скачать.](https://www.eclipse.org/downloads/)
- NetBeans - [скачать.](https://netbeans.apache.org/download/index.html)

Мы рекомендуем выбрать IntelliJ IDEA. Вот видео, показывающее как быстро начать с ней работу: 
- [Установка и запуск первой программы под Intellij IDEA.](https://www.youtube.com/watch?v=YCnd0IAJHd4)

### Я не умею работать с Git и GitHub

- Если ты не знаком с Git и Github, то тебе нужно ознакомиться с [этой статьей](http://maxsite.org/page/how-to-put-your-project-on-github-com), в ней описаны основы работы с Git.
- [Git: загрузить существующий проект на GitHub.](https://www.youtube.com/watch?v=kO5u0PFdHUQ)
- [Отправка проекта на GitHub из IntelliJ IDEA.](https://www.youtube.com/watch?v=zM6z57OtR2Q)

### Тебе потребуется изучить некоторый теоретический минимум для решения этой задачи:
1. Основы синтаксиса Java, простые (примитивные) типы данных
2. Арифметические операции в java    
3. Методы    
4. Преобразование строки в число    
5. Класс String, работа со строками    
6. Циклы в Java    
7. Работа с массивами    
8. Логические операторы    
9. Условные операторы, сравнение, switch case    
10. Enum    
11. Работа с консолью - ввод/вывод, классы Scanner и BufferedReader    
12. Java и ООП    
13. Обработка ошибок и создание своих исключений

### Помогут также следующие ресурсы:

**ВНИМАНИЕ!** Не нужно смотреть все видео из плейлиста, не нужно проходить курс до конца и читать всю книгу! У тебя 7 дней на решение задачи, поэтому не трать время. Сверься со списком тем выше и посмотри выборочно материалы только по этим темам! Для того, чтобы сэкономить свое время, выбери один источник из предложенных и используй его для решения ТЗ. 

1. [Трегулов, Програмания](https://www.youtube.com/watch?v=TQ_vwm4h0ro&list=PLqj7-hRTFl_rqruGcnd2V8SPbY0j9DzT5) 
2. [Канал Алишева](https://www.youtube.com/watch?v=ziOQ8wkmnSE&list=PLAma_mKffTOSUkXp26rgdnC0PicnmnDak)
3. [Metanit. Руководство по языку программирования Java.](https://metanit.com/java/tutorial/) 
4. [Java для начинающих. Курс](https://ru.code-basics.com/languages/java) 
9. Гугл - основной инструмент для поиска информации.

### Я написал код, а мне выдает какую-то ошибку
Часто написанный с ошибками код компилируется и при запуске может выбрасывать исключения, стектрейс которых выводится в консоль. Это нормально.
##### Советы:
1. Для понимания природы этого исключения можно прочитать java doc этого исключения, либо просто загуглив исключение по названию первого исключения и тексту ошибки. 
2. Если по поиску теста ошибки ничего не находится, попробуй сократить текст ошибки, удалив из него текст, относящийся к конкретно к твоему приложению (например там могут быть указаны название написанных тобой методов или переменных).
3. Если не понимаешь английского - пользуйся словарем/переводчиком.
4. Не стесняйся гуглить текст ошибки.
5. Если не работает большой кусок кода - попробуй отладить небольшую его часть.
6. Мысленно пройдись последовательно по коду, записывая значения переменных и результат работы.

Так же для отладки приложения и нахождения проблемный мест в среде разработки предсмотрен режим debug. Видео, показывающее основы использования debug режима в IntelliJ Idea [смотреть](https://www.youtube.com/watch?v=nIABqX19qFM)

### Я не знаю, как подступиться к задаче

Если эта первая программа, которую ты пытаешься написать - постарайся отработать основы на более простых задачах (см материалы выше).  
Постарайся разбить большую задачу на маленькие подзадачи и решать их по отдельности - так гораздо проще. Или упрости задачу до варианта, который ты можешь решить, а потом дорабатывай до заданных требований.

### Я не знаю, как работать с римскими числами

Воспользуйся преобразованием римских чисел в арабские, например [онлайн тут](https://planetcalc.ru/378/).

Статья о Римских цифрах в [Википедии](https://ru.wikipedia.org/wiki/%D0%A0%D0%B8%D0%BC%D1%81%D0%BA%D0%B8%D0%B5_%D1%86%D0%B8%D1%84%D1%80%D1%8B).

## Успехов!
