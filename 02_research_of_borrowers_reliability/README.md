# Исследование надежности заемщиков

Заказчик — кредитный отдел банка. Нужно разобраться, влияет ли семейное положение и количество детей клиента на факт погашения кредита в срок. Входные данные от банка — статистика о платёжеспособности клиентов.
Результаты исследования будут учтены при построении модели кредитного скоринга — специальной системы, которая оценивает способность потенциального заёмщика вернуть кредит банку.

Необходимо ответить на вопросы:
* Есть ли зависимость между количеством детей и возвратом кредита в срок?
* Есть ли зависимость между семейным положением и возвратом кредита в срок?
* Есть ли зависимость между уровнем дохода и возвратом кредита в срок?
* Как разные цели кредита влияют на его возврат в срок?

# Общий вывод
В результате анализа, клиентов можно описать следующим образом.

Наиболее кредитоспособные клиенты:
* `Без детей` или с `3мя детьми`: **7.54%** и **8.18%** соотвественно.
* `Вдовцы и вдовы`: **6.62%**.
* С доходом `30000–50000р` одни из самых ответственных: **6.02%**

Наименее кредитоспособные клиенты:
* С `4мя  детьми`: **9.76%** (один из самых высоких показателей)
* `Не женаты` или состоят в `гражданском браке`: **9.76%** и **9.31%**. 
* С доходами `200000–1000000р` и `50000–200000р`: **7.06%%** и **8.50%**. 

Так же стоит отметить, что среди клиентов:
* **66%** без детей
* **более половины** `замужем или женаты` 
* У **75%** доход `50000-200000р`, у **99%** доход `50000-1000000р`