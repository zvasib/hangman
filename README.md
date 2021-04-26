# Игра "Виселица"

Компьютер загадывает слово и показывает, сколько в нём букв. Игрок вводит буквы по одной.
Если буква есть в слове, компьютер показывает, сколько раз она в нем
встречается и на каких местах. Если буквы нет, компьютер засчитывает ошибку.
Если слово отгадано полностью, игрок победил. После каждой ошибки, дорисовывается виселица.
Если виселица нарисована полностью, то игрок проигрывает.
Всего можно сделать 7 ошибок.

Программа написана на языке Ruby.

Для запуска программы необходимо в терминале ввести: 
```
bundle install

bundle exec ruby main.rb
```

Список слов хранится в файле: data/words.txt 

Для добавления новых слов, отредактируйте данный файл.
