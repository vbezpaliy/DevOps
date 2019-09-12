FROM ubuntu
RUN apt-get update && apt-get install -y cowsay && ln -s /usr/games/cowsay /usr/bin/cowsay

чтобы запустить команду можно прописать инструкцию в докерфайле 
ENTRYPOINT ["cowsay"]

Запустить этот файл в том же каталоге
docker build -t haker/myapp

