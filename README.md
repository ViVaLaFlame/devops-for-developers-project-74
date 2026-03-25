### Hexlet tests and linter status:
[![Actions Status](https://github.com/ViVaLaFlame/devops-for-developers-project-74/actions/workflows/hexlet-check.yml/badge.svg)](https://github.com/ViVaLaFlame/devops-for-developers-project-74/actions)
[![CI/CD](https://github.com/ViVaLaFlame/devops-for-developers-project-74/actions/workflows/push.yml/badge.svg)](https://github.com/ViVaLaFlame/devops-for-developers-project-74/actions)

Проект представляет собой настроенную инфраструктуру для Node.js приложения (блог на Fastify).

## Docker Hub
Образ приложения доступен на Docker Hub:
[elcatze/devops-for-developers-project-74](https://hub.docker.com/r/elcatze/devops-for-developers-project-74)

## Требования к системе
* Docker
* Docker Compose
* Утилита `make`

## Локальная разработка
Для запуска проекта в режиме разработки выполните следующие шаги:

1. Склонируйте репозиторий и перейдите в папку проекта.
2. Создайте файл переменных окружения:
   ```bash
   cp .env.example .env
3. Запустите проект:
   ```bash
   make dev
Приложение будет доступно по адресу: https://localhost

## Для запуска тестов:
  ```bash
  make test