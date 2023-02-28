# Итоговая проверочная работа.

## Для выполнения итоговой проверочной работы необходимо:

1. Создать репозиторий на _GitHub_
2. Нарисовать блок-схему алгоритма (можно обойтись блок-схемой основной содержательной части, если вы выделяете ее в отдельный меторд)
3. Снабдить репозиторый оформленым текстовым описанием решения (*файл README.md*)
4. написать программу решающую поставленную задачу
5. Использовать контроль версий в работе над этим небольшим проектом (не должно быть так что все залито одним коммитом, как минимум этапы **2**, **3** и **4** должны быть расположены в разных коммитах)


## Итоговая задача:

Напишите программу, которая из имеющегося массива строк формирует масив из строк, длинна которых меньше либо равна 3 символа. первоначальный массив можно ввести с клавиатуры, либо задать на старте выполнения алгоритма. При решении не рекомендуется пользоваться коллекциями, лучше обойтись массивами.

**Например:**
+ ["hello", "2", "world", ":-)"] -> ["2", ":-)"]
+ ["1234", "1567", "-2", "computer science"] -> ["-2"]
+ ["Russia", "Denmark", "Kazan"] -> []


## Описание алгоритма решения:

1. объявляем два массива: array1 и array2 такой же длинны
2. задаем метод в котором цикл for равный длинне массива, внутри цикла проводим проверку условия (<=3)
    + если да, то заносим элемент из array1 count array2
3. после присвоения переменная count увеличивается на +1
4. происходит возврат к циклу for в котором переменная i увеличивается на +1
5. так проверяется до конца
6. на выходе в консоль выводим array2

