# game_of_life_flask
## Игра "Жизнь" на фреймворке Flask

Игра "Жизнь" придумана математиком Джоном Конвеем в 1970 г. В этой реализации - вариант бесконечной вселенной (правый край поля - продолжение левого)

### Правила
- Каждая клетка может быть:
  - живой (зеленая)
  - пустой (белая),
  - умершей на предыдущем шаге (красная)
- Каждое поколение (кроме первого) строится на основе предыдущего по алгоритму:
  - если у **пустой** клетке **ровно три** живых соседа - в ней зарождается жизнь
  - если у **живой** клетки **два или три** соседа - она остается живой
  - если у **живой** клетки **меньше двух или больше трех** соседей - клетка умирает
- Игра завершается если:
  - нет ни одной живой клетки
  - конфигурация в точности повторяет одно из предыдущих состояний


