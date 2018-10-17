---
title: Docker build
localeTitle: Docker build
---
## Docker build

`docker build` создала изображение докеров из файла Docker и «контекста». Контекстом может быть URL или местный PATH. Вы можете назвать изображение с помощью дополнительного тега `-t` .

Файл Dockerfile будет устанавливать зависимости во время команды сборки из указанного URL или локального PATH. Любые зависимости, необходимые в ваших контейнерах, должны быть указаны в файле Docker.

Теперь ваше изображение сохраняется в локальном реестре изображений Docker вашего компьютера.

Когда вы создадите контейнеры Docker, вы можете запустить свое приложение с помощью соответствующих команд запуска.

#### Дополнительная информация:

*   [Документы Docker CLI: сборка](https://docs.docker.com/engine/reference/commandline/rm/)
*   [Docker Создание вашего приложения](https://docs.docker.com/get-started/part2/#build-the-app)