---
status: open
priority: normal
dateCreated: 2026-11-01T22:37:07.813+03:00
dateModified: 2026-11-02T09:53:32.641+03:00
tags:
  - PoC
  - task
md: 0.75
milestone: "[[Веха 2 - Развернут тестовый кластер с 3 микрсервисами и Cilium]]"
---

# DoR

# DoD
- Написать приложение имитирующее работу интернет-магазина.
- У приложения есть frontend, который отправляет запросы другим сервисам:
	- GET /
	- GET /user/1 - обращается к user-service
	- GET /orders - обращается к order
- user-service
	- GET /users/1 - возвращает информацию о пользователе
- order-service
	- GET /orders - возвращает список заказов
- Готовые образы программ для minikube
# Теория
