1. Удалить все пустые строки. Использовав регулярное выражение ^\s+ и оставив графу replace with пустой, я удалила все пустые строки.
![alt-текст](https://raw.githubusercontent.com/linapilipchuk/result.txt/master/пункт%201.1.png)

2. Найти всех князей и города, имя и название которых оканчивается на "слав". Использованное регулярное выражение: [А-ЯѢ]+[а-яѣ]+(слав)[а-яѣ]+, выдало мне 564 вхождения.
![alt-текст](https://raw.githubusercontent.com/linapilipchuk/result.txt/master/кньзья%202.png)

3. Найти все упоминания Новгорода. (Нов)+.(город)[^W], данное регулярное выражение позволило мне найти 58 упоминаний о Новгороде.
![alt-текст](https://raw.githubusercontent.com/linapilipchuk/result.txt/master/Новгород%201.png)
