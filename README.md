<p align="center">
  <img src="https://github.com/Alru33/hangman/blob/main/image/hangman.png" width="250">
</p>

## Компьютерная игра Виселица

Консольный вариант на языке Ruby


### Описание

**Виселица** - увлекательная игра по отгадыванию слов

### История

Хотя происхождение игры неизвестно, вариант упоминается в сборнике детских игр, собранном Алисой Гомм в 1894 году, под названием «Птицы, звери и рыбы». Во Франции вместо виселицы рисуется гильотина с человечком. Если игрок проигрывает, человечку отсекают голову

### Принцип игры

Чтобы победить, игроку за семь попыток нужно угадать слово. Оно представлено рядом черточек, обозначающих каждую букву этого слова. Игроку предлагается ввести в консоли букву. При угадывании, она отображается вместо черточки в слове. Если буква отсутствует, начинает рисоваться виселица с висящим на ней человечком. Игра считается проигранной, если игрок исчерпал все семь попыток и виселица полностью нарисована

*Более подробно можно почитать здесь: [Игра Виселица](https://ru.wikipedia.org/wiki/%D0%92%D0%B8%D1%81%D0%B5%D0%BB%D0%B8%D1%86%D0%B0_(%D0%B8%D0%B3%D1%80%D0%B0))*

### Больше слов

Для того, чтобы было интересней играть, можно увеличить количество отгадываемых слов. Для этого зайдите в папку "data" директории "hangman" и внесите в файл "words.txt" новые слова. Порядок слов не имеет значения. Главное, чтобы все буквы в словах были заглавные и каждое слово начиналось с новой строки. После последнего слова должна быть пустая строка

---

*Путь к файлу для добавления новых слов:* 

```
/hangman/data/words.txt
```
---
Для запуска игры из консоли:

```
ruby main.rb
```
