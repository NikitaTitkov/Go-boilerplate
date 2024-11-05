<h1 align="center">Go-boilerplate</h1>

## Table of Contents

- [About](#about)
- [Getting Started](#getting_started)
- [Testing](#testing)

## About <a name="about"></a>

Go-boilerplate — это базовая структура для разработки проектов на Go, включающая CI/CD инструменты для проверки качества кода, тестирования и автоматизации. Проект нацелен на стандартизацию рабочего процесса, позволяя разработчикам быстро запускать проекты и соблюдать лучшие практики.

## Getting Started <a name="getting_started"></a>

Приведенные ниже шаги помогут вам настроить проект и подготовить рабочую среду.

### Установка линтера

Для установки golangci-lint, используемого в проекте для автоматического анализа кода, выполните команду:
```bash
make install-golangci-lint
```
## Testing <a name="testing"></a>
Для проверки стиля и качества кода используйте линтер:

```bash
make lint
```