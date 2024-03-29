# Отчёт по итогам автоматизации

## Что было запланировано и что было сделано

- проведено исследовательское тестирование функционала веб-сервиса покупки тура "Путешествие дня".
- настроен удобный запуск SUT с быстрым подключением к необходимой БД.
- запущена и настроена CI, запускающая тесты на обеих заявленных БД: MySQL и PostgreSQL.
- составлен план автоматизации.
- автоматизированы все 56 заявленных в плане тестовых сценария. Помимо заявленных было добавлено ещё 8 дополнительных
  сценария тестирования UI.
- созданы issue по найденным дефектам.

## Сработавшие риски

- отсутствие технической документации не позволяло четко определить ожидаемый результат в тестах
- требование поддержки двух СУБД добавило сложности в настройках запуска SUT и CI.
- отсутствие у веб-элементов приложения атрибута test-id создало сложности с локаторами элеметов при составление page objects.
