# hw9
## Ход работы

### 1
После открытия файла для удаления пустых строк использовала регулярное выражение: ^\s*$ заменил все вхождения на \0

![](https://github.com/polinakozh/hw9/blob/master/%D0%91%D0%B5%D0%B7%D1%8B%D0%BC%D1%8F%D0%BD%D0%BD%D1%8B%D0%B9.png)

### 2
Для нахождения и посчета всех князей и города, имя и название которых оканчивается на "слав", использовал регулярное выражение:[А-Я][а-я]*(слав)
Всего упоминаний нашел: (592)

![](https://github.com/polinakozh/hw9/blob/master/%D0%91%D0%B5%D0%B7%D1%8B%D0%BC%D1%8F%D0%BD%D0%BD%D1%8B%D0%B9%201.png)

### 3
Для нахождения всех упоминаний о Новгороде в летописи использовал регулярное выражение: Нов(ѣ|ъ|а|у)город(ѣ|ъ|цю|а|ю)?
Всего упоминаний Новгорода нашел: (58)
![]()
