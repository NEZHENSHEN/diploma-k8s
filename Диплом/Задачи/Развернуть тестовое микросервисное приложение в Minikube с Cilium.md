---
status: open
priority: normal
dateCreated: 2026-11-01T22:33:37.652+03:00
dateModified: 2026-11-08T15:52:38.985+03:00
tags:
  - PoC
  - task
milestone: "[[Веха 2 - Развернуто тестовое микросервисное приложение в Minikube с Cilium и проверена работа NetworkPolicy]]"
md: 0.25
---

# DoR
- Собраны образы трёх микросервисов, доступные в Minikube
- Подготовлено окружение Minikube для использования Cilium
# DoD
* В Minikube установлен и функционирует Cilium 
* Созданы манифесты Deployment и Service для трёх микросервисов
* Все три микросервиса успешно развернуты в кластере
* Проверена доступность микросервисов и их взаимодействие через Service
# Теория
- [[Cilium]]
- [[Deployment]]
- [[Service]]
