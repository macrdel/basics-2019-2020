# Поиск экстремального элемента, удовлетворяющего нескольким условиям
### 8-я лабораторная.
Разработать программу для поиска в одномерном массиве максимального/минимального элемента, удовлетворяющего к тому же нескольким условиям.

В данной задаче необходимо сначала найти номер элемента, удовлетворяющего одному условию, затем номер элемента, удовлетворяющего другому условию, и только затем искать между ними максимальный или минимальный элемент. При поиске элементов, удовлетворяющих условию, необходимо использовать досрочный выход из цикла. Ввод осуществляется из файла, вывод – в файл. Для передачи имён файлов должны использоваться параметры программы. Выходной файл открывать для добавления, вывести в файл результаты нескольких тестов.

Задан целочисленный одномерный массив $ a $ из $ n $ элементов. Найти номер первого минимального элемента среди положительных элементов, расположенных после первого элемента, равного нулю. Если нет нулевых элементов, искать с начала массива.
