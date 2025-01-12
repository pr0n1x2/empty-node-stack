# TypeScript Backend Starter Template with Docker

Этот проект представляет собой шаблон для создания и разработки backend-приложений на TypeScript с использованием контейнеризации через Docker. Цель проекта — значительно упростить начальную настройку инфраструктуры и обеспечить разработчикам готовую среду для быстрого запуска и дальнейшей работы.

Для корректной работы проекта необходимо предварительно установить и настроить определённое программное обеспечение, которое обеспечит поддержку всех инструментов и зависимостей, используемых в данном шаблоне.

## Volta

Volta — это современный инструмент для управления версиями Node.js, npm, pnpm и других сопряжённых инструментов JavaScript экосистемы. Его основная задача — сделать управление версиями инструментов разработки стабильным, быстрым и удобным.

Перед установкой рекомендуется почитать документацию на официальном сайте https://docs.volta.sh/guide/getting-started

### Unix Installation

```bash
curl https://get.volta.sh | bash
```

### Windows Installation

```bash
winget install Volta.Volta
```

## pnpm

pnpm (Performant NPM) — это высокопроизводительный и эффективный менеджер пакетов для JavaScript и Node.js. Он выступает как альтернатива другим популярным менеджерам пакетов, таким как npm и yarn, но имеет ряд уникальных особенностей, которые делают его более удобным и производительным.

Установите pnpm следуя рекомендациям на официальном сайте https://pnpm.io/installation

## Docker

Docker — это платформа с открытым исходным кодом для создания, развертывания и управления контейнерами. Контейнеры позволяют запускать приложения в изолированной среде, что упрощает переносимость, масштабируемость и управление.

Установите Docker следуя рекомендациям на официальном сайте:

### Unix Installation

Следуйте инструкциям https://docs.docker.com/engine/install/

### Windows Installation

Следуйте инструкциям https://docs.docker.com/desktop/setup/install/windows-install/

### Mac Installation

Следуйте инструкциям https://docs.docker.com/desktop/setup/install/mac-install/

3. Проверить что IDE использует ту же версию TypeScript на которой ведется разработка

для этого открывает настройки Languages & Frameworks > TypeScript и проверяем версию