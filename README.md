# Docker

### 1) Ведение в докер. Что такое докер и из чего состоит.
- [Главная страница](https://www.docker.com/)
- [Что такои и с чем едят](https://eternalhost.net/blog/razrabotka/chto-takoe-docker)
- [Описание компонентов Docker](https://selectel.ru/blog/what-is-docker/)
- [Dockerfile](https://habr.com/ru/company/ruvds/blog/439980/)
### 2) Установка Docker 
- [Windows](https://docs.docker.com/desktop/windows/install/)
- [Linux](https://docs.docker.com/engine/install/)
- [MacOS](https://docs.docker.com/desktop/mac/install/)
### 3) Docker hub
- [Что это и как пользоваться](https://ravesli.com/vvedenie-v-docker-hub/)
### 4) Часто используемые команды
-  [docker image ls](https://docs.docker.com/engine/reference/commandline/image_ls/) просмотр существующих образов
    ```sh 
    docker image ls
     ```
- [docker container ls](https://docs.docker.com/engine/reference/commandline/container_ls/) просмотр существующих контейнеров
   ```sh 
    docker container ls
     ```
- [docker container logs](https://docs.docker.com/engine/reference/commandline/container_logs/) просмотр логов контейнера
    ```sh 
    docker container logs vv7f3a968695a3
    (vv7f3a968695a3 - CONTAINER ID)
    ```
- [docker ps -a](https://docs.docker.com/engine/reference/commandline/ps/) просмотр истории контейнеров 
    ```sh 
    docker ps -a
    ```
- [ docker search](https://docs.docker.com/engine/reference/commandline/search/) поиск образов
    ```sh 
    docker search nginx
    ```
- [docker pull](https://docs.docker.com/engine/reference/commandline/pull/) загрузка образа из удаленного репозитория
    ```sh 
    docker pull nginx
    ```
- [docker run](https://docs.docker.com/engine/reference/commandline/run/) запуск образа
    ```sh 
    docker run -it --rm -d -p 8080:80 --name web nginx
    ```
- [docker stop](https://docs.docker.com/engine/reference/commandline/stop/)
    ```sh 
    docker stop 7f3a968695a3
    (7f3a968695a3 - CONTAINER ID)
    ```
- [docker rm](https://docs.docker.com/engine/reference/commandline/rm/) удаление контейнера ( должен быть остановлен)
     ```sh 
    docker rm 5625f52a22f1
    (5625f52a22f1 - CONTAINER ID)
    ```
- [docker rmi](https://docs.docker.com/engine/reference/commandline/rmi/) удаление образа. Просмотр всех образов (docker image ls)
     ```sh 
    docker rmi alpine
    alpine - REPOSITORY)
    ```
### 5) Полезные видеоматериалы
- [Вводное видео в Docker](https://www.youtube.com/watch?v=I18TNwZ2Nqg)
- [Установка Docker Windows 10](https://www.youtube.com/watch?v=n1fiT-zaBmI)
- [Установка Docker Ubuntu](https://www.youtube.com/watch?v=V7lTLVzsK5U)
- [Установка Docker на MacOS](https://www.youtube.com/watch?v=VwZmAgOec1k)
### 6) GitHub
- [Создание репозитория](https://docs.github.com/en/get-started/quickstart/create-a-repo)
- [Добавление ключа доступа к аккаунту (SSH keys)](https://only-to-top.ru/blog/tools/2019-12-08-git-ssh-windows.html)
- [Плейлист который ответит на 98% вопросов](https://youtu.be/DK2PsTcSFFM)


# Jenkins
