# Docker

### 1) Ведение в докер. Что такое докер и из чего состоит.
- [Главная страница](https://www.docker.com/)
- [Что такое и с чем едят](https://eternalhost.net/blog/razrabotka/chto-takoe-docker)
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
### 7) React app с docker 
 - [docker-reactjs](https://github.com/thejungwon/docker-reactjs)


# Jenkins

### 1) Ведение в Jenkins
- [Что такое Jenkins](https://dataenginer.ru/?p=1647)
- [И еще раз что такое Jenkins](https://ru.education-wiki.com/9039545-what-is-jenkins)
- [Видео курсы на русском языке ](https://www.youtube.com/playlist?list=PLg5SS_4L6LYvQbMrSuOjTL1HOiDhUE_5a)
### 2)  Установка Jenkins
 - [Windows](https://ru.education-wiki.com/3736628-how-to-install-jenkins)
 - [Видео установки на Windows](https://www.youtube.com/watch?v=1_Zs0gQq1Yc)
 - [Linux](https://www.jenkins.io/doc/book/installing/linux/)
 - [Видео установки на Linux](https://www.youtube.com/watch?v=Hm6yi7wnp6Y&list=PLg5SS_4L6LYvQbMrSuOjTL1HOiDhUE_5a&index=2)
 - [MacOS](https://coralogix.com/blog/how-to-install-and-configure-jenkins-on-the-mac-os/)
 - [Видео установки на MacOS](https://www.youtube.com/watch?v=GPeSfPjm6L4)

 ### 3) Pipeline
 - [Что такое Pipeline и первый запуск](https://itisgood.ru/2019/11/11/kak-sozdat-svoj-pervyj-pajplajn-ci-cd-v-jenkins/)
 - [Связь Jenkins и GitHub](https://youtu.be/i9KLMQmvZmY)
 - [Генерация ключей для связи с GitHub](https://medium.com/appgambit/ssh-authentication-between-github-and-jenkins-d873dd138db0)

 ### 4) Docker-copmose
 - [Что такое Docker Compose](https://dker.ru/docs/docker-compose/overview-of-docker-compose/)
 - [Docker Compose и React App](https://rsbh.dev/blog/dockerize-react-app)
 - [Репозиторий](https://github.com/rsbh/react-docker)


### 5) Docker-compose for front, back, db
 - [Full-stack app](https://www.section.io/engineering-education/build-and-dockerize-a-full-stack-react-app-with-nodejs-and-nginx/)
 - [Repository](https://github.com/dimanchezzz/node_with_db)



