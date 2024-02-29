## labka1-2.2-
# Варіант 2
Масив вважається монотонним, якщо всі його елементи розташовані в зростаючому або спадаючому порядку.

Завдання: Напишіть функцію, яка перевіряє, чи є заданий масив монотонним. Функція повинна повертати логічне значення True, якщо масив є монотонним, і False, якщо масив не є монотонним.

Приклад вхідних даних і результатів:

Для масиву [1, 2, 3, 4, 5] функція повертає True, оскільки всі елементи зростають монотонно.
Для масиву [5, 4, 3, 2, 1] функція повертає True, оскільки всі елементи спадають монотонно.
Для масиву [1, 2, 2, 3, 2, 4] функція повертає False, оскільки масив не є строго монотонним.
Зверніть увагу, що масив із однаковими значеннями наступного елемента вважається монотонним.

Для перевірки виконання роботи реалізованого алгоритму слід використати бібліотеку unittest .

