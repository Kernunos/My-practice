# Tests

API тесты.
test_api_graphql запускает проверку по всем микросервисам.
stores_api_test проверяет stores
users_api_test проверяет users

Скрипты нацеленные на проверку конкретного микросервиса создают меньше сущностей в базе данных, но все равно затрагивают другие микросервисы, так как работать полноценно по одиночке они не могут.
По умолчанию запускается на Nightly для запуска на другом сервере нужно запустить скрипт задав при запуске переменную url из переменной окружения 'GRAPHQL_URL'
