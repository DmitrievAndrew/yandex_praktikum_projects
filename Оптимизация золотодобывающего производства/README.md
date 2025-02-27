﻿**Цель**: подготовка прототипа модели машинного обучения, которая должна предсказать коэффициент восстановления золота из золотосодержащей руды.

**Результаты**:
В результате обучения моделей выяснилось:
- размеры гранул сырья незначительно влияют на качество линейной регрессии, но не влияют на качество остальных моделей;
- предсказание эффективности восстановления чернового концентрата необходимо делать на признаках, относящихся к этапу флотации;
- для предсказания эффективности восстановления финального концентрата признаки, относящиеся к этапу флотации, необходимо:
  - в случае линейной регрессии исключить;
  - для остальных моделей оставить.

Лучшей моделью оказался случайный лес, она подходит на роль прототипа модели машинного обучения, которая должна предсказать коэффициент восстановления золота из золотосодержащей руды.

Дополнительно ноутбук доступен по [ссылке.](https://nbviewer.jupyter.org/github/DmitrievAndrew/yandex_praktikum_projects/blob/master/%D0%9E%D0%BF%D1%82%D0%B8%D0%BC%D0%B8%D0%B7%D0%B0%D1%86%D0%B8%D1%8F%20%D0%B7%D0%BE%D0%BB%D0%BE%D1%82%D0%BE%D0%B4%D0%BE%D0%B1%D1%8B%D0%B2%D0%B0%D1%8E%D1%89%D0%B5%D0%B3%D0%BE%20%D0%BF%D1%80%D0%BE%D0%B8%D0%B7%D0%B2%D0%BE%D0%B4%D1%81%D1%82%D0%B2%D0%B0/gold.ipynb)
