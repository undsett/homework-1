1.Напишите программу, которая заменяет символы в почтовом адресе пользователя:

@ заменяется на [ at ]<br/>
. заменяется на [ dot ]

Пример ввода:<br/>
person@gmail.com<br/>
Результат:<br/>
person[ at ]gmail[ dot ]com<br/>

2.i18n используется для обозначения слова internationalization, где 18 означает количество букв между первой и последней в этом слове, такое можно встретить в среде разработчиков. Например, для слова localization используется сокращение l10n.
Напишите функцию, которая преобразует слова введенные из консоли через пробел в сокращенную форму. Слова длиной меньше 4х оставить без изменений.

Пример ввода:<br/>
internationalization localization cat elephant monitor<br/>
Результат:<br/>
i18n l10n cat e6t m5r<br/>

PS: напишите функцию, которая сокращает слово, в основной функции используйте метод сплит, который поместит слова в массив и для каждого из них вызовет вашу функцию

3.Определить является ли слово палиндромом, т.е. читается одинаково, слева направо и справа налево.
Определить количество таких слов в тексте, в котором все слова введены через запятую.<br/>

Пример ввода:<br/>
deleveled, evitative, cat, dog, deified<br/>
Результат:<br/>
There are 3 palindromes in the text<br/>

PS: используйте метод split c параметром "," и потом метод trim, чтобы удалить лишние пробелы слева и справа<br/>

4.Напишите перевод из 2ной системы счисления в 10ную.<br/>

Пример ввода:<br/>
1100<br/>
Результат:<br/>
12<br/>

5.Напишите функцию нахождения числа в массиве, элементы которого упорядочены по возрастанию.
Если число есть в массиве функция должна возвращать **true**, иначе - **false**<br/>

Первые 4 задачи должны находиться в пакете **com.hillel.tasks** в классе **StringTasks**<br/>
5ая задача должна находиться в пакете **com.hillel.tasks** в классе **BinarySearch**<br/>

Пример оформления можно посмотреть в папке **john.doe**
