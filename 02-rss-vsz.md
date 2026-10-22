Таблица rss и vsz процессов:
<img width="1153" height="355" alt="image" src="https://github.com/user-attachments/assets/592cfffe-a103-4209-aa3e-f7f3456a3784" />

Вопрос 1)
~~~
(Первый)
2692
PID  VSZ   RSS  COMMAND
2692 11340 2916 python3
~~~
~~~
(Второй)
2706
PID  VSZ    RSS   COMMAND
2706 526484 20424 python3
~~~
Вопрос 2)
У первого RSS маленький, а VSZ большой потому что RSS отображает объем памяти, который процесс фактически использует в данный момент, когда VSZ показывает общий объем доступной ему памяти.
