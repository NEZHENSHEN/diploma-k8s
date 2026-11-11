---
status: open
priority: normal
dateCreated: 2026-11-02T09:53:59.838+03:00
dateModified: 2026-11-08T15:58:00.025+03:00
tags:
  - PoC
  - task
milestone: "[[Веха 2 - Развернуто тестовое микросервисное приложение в Minikube с Cilium и проверена работа NetworkPolicy]]"
md: 0.75
---

# DoR
- В Minikube с Cilium развернуты три микровервиса: frontend, user-service, order-service
- Ограничивающие NetworkPolicy отсутствуют. 
# DoD
* Подтверждена доступность user-service и order-service из frontend по HTTP через k8s Service
* Результаты зафиксированы в [Эксперименты с NetworkPolicy](<Эксперименты с NetworkPolicy.md>)
# Теория
- [CNI](<CNI.md>)
- [Сетевые политики Kubernetes для изоляции подов и пространства имён](<Сетевые политики Kubernetes для изоляции подов и пространства имён.md>)
# Эксперименты
- [Эксперименты с NetworkPolicy](<Эксперименты с NetworkPolicy.md>)
