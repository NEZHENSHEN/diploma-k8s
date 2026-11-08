---
status: open
priority: normal
dateCreated: 2026-11-01T22:37:07.813+03:00
dateModified: 2026-11-08T14:40:26.648+03:00
tags:
  - PoC
  - task
md: 0.75
milestone: "[[Веха 2 - Развернуто тестовое микросервисное приложение в Minikube с Cilium и проверена работа NetworkPolicy]]"
---

# DoR
- Достугнута веха 1
# DoD
- Написано тестовое приложение интернет-магазина из 3-х микросервисов
	- У приложения есть frontend, который отправляет запросы другим сервисам:
		- GET /
		- GET /user/1 - обращается к user-service
		- GET /orders - обращается к order
	- user-service
		- GET /users/1 - возвращает информацию о пользователе
	- order-service
		- GET /orders - возвращает список заказов
- Созданы Dockerfile и собраны контейнерные образы всех трёх микросервисов
# Теория
