## Тест-кейс №1. Ввод значений для переменных int_balace и int_transfer в код файла Main.java для проверки отображения итоговой суммы в переменной int_remainder

При вводе различных данных для переменных int_balace и int_transfer в код файла Main.java в результате вычисления отображается правильная сумма согласно правилам сложения

1. Клонируем репозиторий по ссылке https://github.com/DinaFatkh/javalesson2.1.git на локальный компьютер;
2. Открываем файл Main.java (путь javalesson2.1/src/Main.java) в IntelliJ IDEA;
3. Вводим значение в переменную int_balace для текущего баланса (см. столбец "Текущий баланс" в таблице Ожидаемый результат);
4. Вводим значение для перевода в переменную int_transfer (см. столбец "Перевод на счет" в таблице  Ожидаемый результат);
5. Нажимаем Shift+F10 для запуска кода или кнопку Run на консоли.

Ожидаемый результат: в консоль выводится значение для int_remainder (см. столбец "Итоговый баланс")

| текущий баланс | перевод на счет | итоговый баланс |
| :------------- | --------------- | ---------------:|
| 2_000_000_000  | 100_000_000     | 2100000000      |
| 1_647_483_648  | 500_000_000     | 2147483648      |
| 500_000_000    | 651_584_984     | 1151584984      |
| 0              | 2_147_483_647   | 2147483647      |
| 2_000_000_000  | 500_000_000     | 2500000000      |
| 258_483_648    | 0               | 258483648       |