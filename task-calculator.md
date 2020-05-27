# Задача: "Калькулятор"

## Описание:
Создайте консольное приложение "Калькулятор".  
Приложение должно читать из консоли введенные пользователем арифметические операции и выводить в консоль результат их выполнения.  

## Требования:

1. Калькулятор умеет выполнять операции сложения, вычитания, умножения и деления с двумя числами:
a + b, a - b, a * b, a / b.  <b> Данные передаются в одну строку (смотрите пример)! Решения, в которых каждое число и арифмитеческая операция передаются с новой строки считаются неверными. </b>
2. Калькулятор умеет работать как с арабскими (1,2,3,4,5...), так и с римскими (I,II,III,IV,V...) числами.
3. Калькулятор должен принимать на вход числа от 1 до 10 включительно, не более. На выходе числа не ограничиваются по величине и могут быть любыми.  
4. Калькулятор умеет работать только с целыми числами.   
5. Калькулятор умеет работать только с арабскими или римскими  цифрами одновременно, при вводе пользователем строки вроде 3 + II калькулятор должен выбросить исключение и прекратить свою работу.   
6. При вводе пользователем неподходящих чисел приложение выбрасывает исключение и завершает свою работу.  
7. При вводе пользователем строки, не соответствующей одной из вышеописанных арифметических операций, приложение выбрасывает исключение и завершает свою работу.

## Пример работы программы:
###### Input:
`1 + 2`  
###### Output:
`3`
###### Input:
`VI / III`  
###### Output:
`II`
 
## Принципы оценки работы:
Обратите внимание на принципы ООП, постарайтесь разбить программу на логические классы. <ins> Решения, в которых весь код программы находится в одном классе будут низко оценены.</ins> Продемонстрируйте своё умение в работе с разными синтаксическими конструкциями, не забудьте про исключительные ситуации, при которых выполнение программы невозможно из-за некорректных входных данных. 

## Как отправить решение?
1. Вам нужно создать собственный репозиторий на Github и добавить туда проект с решением.
2. Ссылку на репозиторий отправьте нам на почту *info@java-mentor.com* с темой **Тестовое задание калькулятор Java**.  

---
# FAQ

### Какую среду разработки мне выбрать?

Мы не ограничиваем вас в выборе, вы можете реализовать свой проект в любой удобной вам среде разработки:
- IntelliJ IDEA - [скачать.](https://www.jetbrains.com/ru-ru/idea/download/)
- Eclipse - [скачать.](https://www.eclipse.org/downloads/)
- NetBeans - [скачать.](https://netbeans.apache.org/download/index.html)

Мы рекомендуем выбрать IntelliJ IDEA. Вот несколько примеров, как быстро начать с ней работу:
- [Установка и запуск первой программы под Intellij IDEA.](https://www.youtube.com/watch?v=tSTvCyqeeYY&list=PL786bPIlqEjRDXpAKYbzpdTaOYsWyjtCX&index=3)
- [Первая программа в IntelliJ IDEA.](https://metanit.com/java/tutorial/1.5.php)

### Я не умею работать с Git и GitHub

- Если вы не знакомы с Git и Github вам нужно ознакомиться с [этой статьей](http://maxsite.org/page/how-to-put-your-project-on-github-com), в ней описаны основы работы с Git.
- [Git: загрузить существующий проект на GitHub.](https://www.youtube.com/watch?v=kO5u0PFdHUQ)
- [Отправка проекта на GitHub из IntelliJ IDEA.](https://www.youtube.com/watch?v=zM6z57OtR2Q)

### Что, если я не знаю Java?

1. Начните с установки JDK c сайта ORACLE - [скачать](https://www.oracle.com/ru/java/technologies/javase-downloads.html). Можете выбрать любую версию, но мы рекомендуем вам 8, либо 11. Для скачивания, необходимо зарегистрироваться на сайте ORACLE - это не займет много времени.
2. Эти материалы помогут вам в установке и настройке JDK:
    - [Видео - Установка Java Development Kit(JDK)](https://www.youtube.com/watch?v=uXMTq81jG7Y&list=PL786bPIlqEjRDXpAKYbzpdTaOYsWyjtCX)
    - [Статья по установке JDK с картинками.](https://www.fandroid.info/ustanovka-jdk-java-development-kit/)
3. Установите среду разработки (мы рекомендуем IntelliJ IDEA) и напишите свою первую маленькую программу на Java - см. вопрос выше.
4. Посмотрите предлагаемый ниже список тем и ресурсов для изучения Java.

##### Вам потребуется изучить некоторый теоретический минимум для решения этой задачи:
1. Основы синтаксиса Java, простые (примитивные) типы данных:
    - [http://developer.alexanderklimov.ru/android/java/basic.php](http://developer.alexanderklimov.ru/android/java/basic.php)
    - [https://metanit.com/java/tutorial/2.12.php](https://metanit.com/java/tutorial/2.12.php)
    - [https://www.youtube.com/watch?v=ZnzIpVWAPv8](https://www.youtube.com/watch?v=ZnzIpVWAPv8)
    - [https://www.youtube.com/watch?v=Y11uOcbJxgQ](https://www.youtube.com/watch?v=Y11uOcbJxgQ)
    
2. Арифметические операции в java:
    - [https://metanit.com/java/tutorial/2.3.php](https://metanit.com/java/tutorial/2.3.php)
    - [https://www.youtube.com/watch?v=zFwDK3BYFcc](https://www.youtube.com/watch?v=zFwDK3BYFcc)
    
3. Методы:
    - [https://metanit.com/java/tutorial/2.7.php](https://metanit.com/java/tutorial/2.7.php)
    - [https://metanit.com/java/tutorial/2.16.php](https://metanit.com/java/tutorial/2.16.php)
    - [https://metanit.com/java/tutorial/2.17.php](https://metanit.com/java/tutorial/2.17.php)
    - [http://developer.alexanderklimov.ru/android/java/methods.php](http://developer.alexanderklimov.ru/android/java/methods.php)
    - [https://youtu.be/yscAqAcB7ok](https://youtu.be/yscAqAcB7ok)
    
4. Преобразование строки в число:
    - [http://study-java.ru/uroki-java/urok-7-preobrazovanie-tipov-v-java/](http://study-java.ru/uroki-java/urok-7-preobrazovanie-tipov-v-java/)
    - [https://youtu.be/P7b_dzMFG7s](https://youtu.be/P7b_dzMFG7s)
    - [https://www.youtube.com/watch?v=iYqpSRq35PA](https://www.youtube.com/watch?v=iYqpSRq35PA)
    
5. Класс String, работа со строками:
    - [https://metanit.com/java/tutorial/7.1.php](https://metanit.com/java/tutorial/7.1.php)
    - [https://metanit.com/java/tutorial/7.2.php](https://metanit.com/java/tutorial/7.2.php)
    - [http://developer.alexanderklimov.ru/android/java/string.php](http://developer.alexanderklimov.ru/android/java/string.php)
    - [https://youtu.be/-YK8B4WO7nI](https://youtu.be/-YK8B4WO7nI)
    
6. Циклы в Java:
    - [https://metanit.com/java/tutorial/2.6.php](https://metanit.com/java/tutorial/2.6.php)
    - [https://youtu.be/Q2DXFrzYWJs](https://youtu.be/Q2DXFrzYWJs)
    - [https://youtu.be/6Vnm9T4NC2k](https://youtu.be/6Vnm9T4NC2k)
    
7. Работа с массивами:
    - [https://metanit.com/java/tutorial/2.4.php](https://metanit.com/java/tutorial/2.4.php)
    - [http://developer.alexanderklimov.ru/android/java/array.php](http://developer.alexanderklimov.ru/android/java/array.php)
    - [https://www.youtube.com/watch?v=i_IiGj65bJM](https://www.youtube.com/watch?v=i_IiGj65bJM)
    - [https://youtu.be/li86TEAEhYM](https://youtu.be/li86TEAEhYM)
    
8. Логические операторы:
    - [http://developer.alexanderklimov.ru/android/java/logic_operators.php](http://developer.alexanderklimov.ru/android/java/logic_operators.php)
    - [https://youtu.be/IbKrOnjHdcE](https://youtu.be/IbKrOnjHdcE)
    
9. Условные операторы, сравнение, switch case:
    - [https://metanit.com/java/tutorial/2.5.php](https://metanit.com/java/tutorial/2.5.php)
    - [http://developer.alexanderklimov.ru/android/java/if.php](http://developer.alexanderklimov.ru/android/java/if.php)
    - [http://developer.alexanderklimov.ru/android/java/comparison.php](http://developer.alexanderklimov.ru/android/java/comparison.php)
    - [http://developer.alexanderklimov.ru/android/java/switch.php](http://developer.alexanderklimov.ru/android/java/switch.php)
    - [https://www.youtube.com/watch?v=AzbyMP6qXo0](https://www.youtube.com/watch?v=AzbyMP6qXo0)
    - [https://youtu.be/QJHcGWbzk3U](https://youtu.be/QJHcGWbzk3U)
    
10. Enum:
    - [https://youtu.be/GOzNp1YAm5w](https://youtu.be/GOzNp1YAm5w)
    - [http://developer.alexanderklimov.ru/android/java/enum.php](http://developer.alexanderklimov.ru/android/java/enum.php)
    
11. Работа с консолью - ввод/вывод, классы Scanner и BufferedReader:
    - [https://metanit.com/java/tutorial/2.9.php](https://metanit.com/java/tutorial/2.9.php)
    - [https://metanit.com/java/tutorial/6.9.php](https://metanit.com/java/tutorial/6.9.php)
    - [https://www.youtube.com/watch?v=Y2iB_DwdyfM](https://www.youtube.com/watch?v=Y2iB_DwdyfM)
    - [https://www.youtube.com/watch?v=8qEvVLr4tg8](https://www.youtube.com/watch?v=8qEvVLr4tg8)
    
12. Java и ООП:
    - [https://metanit.com/java/tutorial/3.1.php](https://metanit.com/java/tutorial/3.1.php)
    - [https://youtu.be/_25bk1zQqyk](https://youtu.be/_25bk1zQqyk)
    - [https://youtu.be/VOUuYiTR8hs](https://youtu.be/VOUuYiTR8hs)
    - [https://youtu.be/yoFRDSh6lWI](https://youtu.be/yoFRDSh6lWI)
    
13. Обработка ошибок и создание своих исключений:
    - [https://metanit.com/java/tutorial/2.10.php](https://metanit.com/java/tutorial/2.10.php)
    - [http://developer.alexanderklimov.ru/android/java/exception.php](http://developer.alexanderklimov.ru/android/java/exception.php)
    - [https://www.youtube.com/watch?v=ZspkReG8L2E](https://www.youtube.com/watch?v=ZspkReG8L2E)

##### Помогут также следующие ресурсы:
1. [Курс CodeBasics](https://ru.code-basics.com/languages/java) - интерактивный курс по основам.  
2. [Курс на Stepic.](https://stepik.org/course/187/syllabus) - большой, но немного сложный курс.
3. [HackerRank](https://www.hackerrank.com/) - много задачек, можно выбрать язык и уровень сложности. На английском, но переводчик вам поможет.
4. [Codewars](https://www.codewars.com/?language=java) - много задачек для практики. На английском, но переводчик вам опять поможет. 
5. [Викиучебник по Java](https://ru.wikibooks.org/wiki/Java) - Справочник по языку.
6. [Руководство по языку программирования Java.](https://metanit.com/java/tutorial/)
7. Отличная бесплатная книга - [Яков Файн "Программирование на Java для детей, родителей, дедушек и бабушек".](https://vk.com/wall-54530371_172885)
8. Много разных плейлистов на YouTube - ищите ["Java для начинающих."](https://www.youtube.com/results?search_query=Java+%D0%B4%D0%BB%D1%8F+%D0%BD%D0%B0%D1%87%D0%B8%D0%BD%D0%B0%D1%8E%D1%89%D0%B8%D1%85)
9. Гугл - основной инструмент для поиска информации.

### Я знаю другой язык программирования, но не знаю Java

1. [Side-by-side code snippets](https://rosetta.alhur.es/) - сравнение примеров кода на разных языках. Выбираем ваш язык и Java - изучаем сходства/различия.
2. [Введение в Java - лекция Тагира Валеева.](https://youtu.be/XC8RmEn5gYA)
3. [Базовый синтаксис Java - лекция Тагира Валеева.](https://vk.com/video-54530371_456248413?list=5042f7c11963fb48e4)
4. [Базовый синтаксис Java - короткая заметка.](https://www.internet-technologies.ru/articles/bazovyy-sintaksis-java-dlya-nachinayuschih.html)

### Я написал код, а мне выдает какую-то ошибку

##### Советы:
1. Если не понимаете английского - пользуйтесь словарем/переводчиком.
2. Не стесняйтесь гуглить текст ошибки.
3. Если не работает большой кусок кода - попробуйте отладить небольшую его часть.

[Хорошее видео про отладку Java-кода в IDEA.](https://www.youtube.com/watch?v=Z1BQsf0A4xY)

### Я не знаю, как подступиться к задаче

Если эта первая программа, которую вы пытаетесь написать - постарайтесь отработать основы на более простых задачах (см материалы выше).  
Постарайтесь разбить большую задачу на маленькие подзадачи и решать их по отдельности - так гораздо проще. Или упростите задачу до варианта, который вы можете решить, а потом дорабатывайте до заданных требований.

### Я не знаю, как работать с римскими числами

Воспользуйтесь преобразованием римских чисел в арабские, например [онлайн тут](https://planetcalc.ru/378/).

Статья о Римских цифрах в [Википедии](https://ru.wikipedia.org/wiki/%D0%A0%D0%B8%D0%BC%D1%81%D0%BA%D0%B8%D0%B5_%D1%86%D0%B8%D1%84%D1%80%D1%8B).

## Успехов!
