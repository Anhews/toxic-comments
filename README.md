# Toxic-comments
Mодель классификации комментариев

Интернет-магазин запускает новый сервис. Теперь пользователи могут редактировать и дополнять описания товаров, как в вики-сообществах. Клиенты предлагают свои правки и комментируют изменения других. 

**Задача:** найти инструмент, который будет искать токсичные комментарии и отправлять их на модерацию.

**Цель:** найти модель классификации комментариев на позитивные и негативные со значением метрики качества F1 >= 0.75.

**План:**

- Обзор данных.
- Подготовка данных.
- Обучение моделей.

**Описание данных**

Файл - `toxic_comments.csv`. 
- Столбец *text* - текст комментария.
- Столбец *toxic* — целевой признак.
