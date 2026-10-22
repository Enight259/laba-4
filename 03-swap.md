<img width="1139" height="689" alt="image" src="https://github.com/user-attachments/assets/ce3c171a-6062-437d-834c-5bac0b9df26e" />
У меня выдало ошибку swapon --show ( команда не найдена) это скорее всего связна с тем, что утилита swap нету на моей системе. Нашел команду альтернативу cat /proc/swaps, что показывает те же данные(Filename, Type, Size, Used, Priority) что и swap.

Вопрос 1)
~~~
fallocate - выделяет место на диске
mkswap - форматирование под swap
swapon - активирует подкачку
~~~
