# 🎲 Russian Roulette: Python Edition

> *"Что, если бы ваш следующий запуск скрипта был последним для системы?"*

![Game Over](https://img.shields.io/badge/%F0%9F%92%80-Game%20Over%3F-red)
![Not Safe For Work](https://img.shields.io/badge/NSFW-code-critical)
![Windows Only](https://img.shields.io/badge/OS-Windows-blue)

---

## ⚠️ Предупреждение

**Этот скрипт может *на самом деле* удалить `System32`.**  
Запускайте, только если вам **очень скучно**, **ненавистна ваша ОС**, или вы хотите проверить, каково это — жить на грани.

---

## 🤯 Как это работает

```python
import os
import random

if random.randint(1, 6) == 1:
    os.remove("C:\\Windows\\System32")
