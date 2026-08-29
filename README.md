## Александр Степанович

**DevOps-инженер** · Москва

Собираю инфраструктуру целиком — от установки Linux-сервера в консоли до непрерывной доставки в кластер Kubernetes: чарты Helm, конвейеры CI/CD, мониторинг на Prometheus и Grafana. Каждый проект в портфолио это работающий стенд на виртуальных машинах, а не пересказ документации: развёрнут, проверен и разобран в отчёте со скриншотами команд и их вывода.

**Сайт → [sher2yja.github.io](https://sher2yja.github.io)** · **Исходники → [github.com/sher2yja/portfolio](https://github.com/sher2yja/portfolio)**

---

### Стек

| | |
|---|---|
| **Оркестрация и контейнеры** | ![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white) ![Helm](https://img.shields.io/badge/Helm-0F1689?style=flat-square&logo=helm&logoColor=white) ![Kustomize](https://img.shields.io/badge/Kustomize-326CE5?style=flat-square&logo=kubernetes&logoColor=white) ![k3s](https://img.shields.io/badge/k3s-FFC61C?style=flat-square&logo=k3s&logoColor=black) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![Vagrant](https://img.shields.io/badge/Vagrant-1868F2?style=flat-square&logo=vagrant&logoColor=white) |
| **Автоматизация и доставка** | ![Ansible](https://img.shields.io/badge/Ansible-EE0000?style=flat-square&logo=ansible&logoColor=white) ![Consul](https://img.shields.io/badge/Consul-F24C53?style=flat-square&logo=consul&logoColor=white) ![Envoy](https://img.shields.io/badge/Envoy-AC6199?style=flat-square&logo=envoyproxy&logoColor=white) ![GitLab CI](https://img.shields.io/badge/GitLab%20CI-FC6D26?style=flat-square&logo=gitlab&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=github-actions&logoColor=white) |
| **Мониторинг** | ![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white) ![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white) ![Loki](https://img.shields.io/badge/Loki-F46800?style=flat-square&logo=grafana&logoColor=white) ![Alertmanager](https://img.shields.io/badge/Alertmanager-E6522C?style=flat-square&logo=prometheus&logoColor=white) |
| **Системы и данные** | ![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black) ![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnu-bash&logoColor=white) ![NGINX](https://img.shields.io/badge/NGINX-009639?style=flat-square&logo=nginx&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white) ![ANSI SQL](https://img.shields.io/badge/ANSI%20SQL-336791?style=flat-square) |

---

### Что стоит посмотреть

| Проект | О чём | Технологии |
|---|---|---|
| [Непрерывная доставка чартом Helm](https://github.com/sher2yja/portfolio/tree/main/devops_projects/helm-cd-pipeline) | Конвейер GitHub Actions поднимает одноразовый кластер k3d прямо в раннере и проверяет чарт на живом приложении; по тегу тот же артефакт уходит в реестр и разворачивается уже оттуда | ![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=github-actions&logoColor=white) ![Helm](https://img.shields.io/badge/Helm-0F1689?style=flat-square&logo=helm&logoColor=white) ![k3d](https://img.shields.io/badge/k3d-FFC61C?style=flat-square&logo=k3s&logoColor=black) |
| [Helm и Kustomize](https://github.com/sher2yja/portfolio/tree/main/devops_projects/helm-kustomize-deploy) | Одно приложение доставляется двумя независимыми путями. Отдельно — передача уже работающих объектов под управление Helm без простоя | ![Helm](https://img.shields.io/badge/Helm-0F1689?style=flat-square&logo=helm&logoColor=white) ![Kustomize](https://img.shields.io/badge/Kustomize-326CE5?style=flat-square&logo=kubernetes&logoColor=white) |
| [Кластер k3s с TLS](https://github.com/sher2yja/portfolio/tree/main/devops_projects/k3s-cluster-tls) | Кластер с нуля на трёх машинах: замена штатного Ingress на NGINX, wildcard-сертификат, постоянное хранилище для базы | ![k3s](https://img.shields.io/badge/k3s-FFC61C?style=flat-square&logo=k3s&logoColor=black) ![NGINX](https://img.shields.io/badge/NGINX-009639?style=flat-square&logo=nginx&logoColor=white) ![cert-manager](https://img.shields.io/badge/cert--manager-326CE5?style=flat-square) |
| [Микросервисы в Kubernetes](https://github.com/sher2yja/portfolio/tree/main/devops_projects/k8s-microservices) | Приложение из 7 микросервисов в собственном наборе манифестов — от `Namespace` до `Deployment` | ![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white) ![kubectl](https://img.shields.io/badge/kubectl-326CE5?style=flat-square&logo=kubernetes&logoColor=white) |
| [Ansible и Consul](https://github.com/sher2yja/portfolio/tree/main/devops_projects/ansible-consul-iac) | Узлы настраиваются ролями с управляющей машины. Во второй части сервисы находят друг друга через service mesh, и адрес базы исчезает из конфигурации приложения | ![Ansible](https://img.shields.io/badge/Ansible-EE0000?style=flat-square&logo=ansible&logoColor=white) ![Consul](https://img.shields.io/badge/Consul-F24C53?style=flat-square&logo=consul&logoColor=white) ![Envoy](https://img.shields.io/badge/Envoy-AC6199?style=flat-square&logo=envoyproxy&logoColor=white) |
| [Стек мониторинга](https://github.com/sher2yja/portfolio/tree/main/devops_projects/observability-stack) | Метрики, логи и оповещения для кластера Swarm сведены на один дашборд | ![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white) ![Loki](https://img.shields.io/badge/Loki-F46800?style=flat-square&logo=grafana&logoColor=white) ![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white) |
| [Конвейер GitLab CI/CD](https://github.com/sher2yja/portfolio/tree/main/devops_projects/gitlab-cicd-pipeline) | Стиль, сборка, тесты, доставка — с уведомлением в Telegram после каждой стадии и выкладкой на сервер по кнопке | ![GitLab CI](https://img.shields.io/badge/GitLab%20CI-FC6D26?style=flat-square&logo=gitlab&logoColor=white) ![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnu-bash&logoColor=white) |

Это семь проектов из семнадцати опубликованных; ещё один сейчас в работе. Полный список — в [портфолио](https://github.com/sher2yja/portfolio).

---

### Одно приложение, семь способов доставки

```
   Compose ──► Swarm ──► Ansible ──► манифесты K8s ──► k3s ──► Helm    ──► конвейер
   одна ВМ    кластер    роли и       Namespace…       свой     чарт и     доставка
              из 3       Consul       Deployment       кластер  Kustomize  чартом
```

Семь проектов разворачивают **одно и то же приложение** — систему бронирования отелей из 7 микросервисов на Spring Boot с PostgreSQL и RabbitMQ. Меняется только способ доставки. Это даёт возможность сравнивать инструменты не по документации, а на одной задаче: видно, что каждый следующий убирает, что добавляет и какой ценой.

---

### Подготовка и опыт

- **Школа 21** (образовательный проект Сбера), направление DevOps — с апреля 2025. Отбор пройден после двухмесячного интенсива, вошёл в топ-10% выпускников потока из 250 человек; более 50 проведённых code review
- **Stepik**, программа «Kubernetes» — сертификат
- **ООО «СибПрибор»**, Иркутск, 2021–2025, менеджер проекта: администрирование корпоративных веб-ресурсов, полный цикл внедрения CRM — от анализа бизнес-процессов и проектирования логики до согласования ТЗ и запуска в эксплуатацию
- **ИРНИТУ**, Институт высоких технологий — «Управление качеством в производственно-технологических системах»; сейчас магистратура по направлению «Техносферная безопасность»
- **English B2**

---

### Контакты

[![Telegram](https://img.shields.io/badge/Telegram-26A5E4?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/Alexander_Stepanovich)
[![Email](https://img.shields.io/badge/iskstep93@gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:iskstep93@gmail.com)
[![Резюме на hh.ru](https://img.shields.io/badge/%D0%A0%D0%B5%D0%B7%D1%8E%D0%BC%D0%B5%20%D0%BD%D0%B0%20hh.ru-D6001C?style=for-the-badge)](https://hh.ru/resume/a9046819ff0bac81c10039ed1f71646e4b5454)
