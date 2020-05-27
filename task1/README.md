Нужно запустить следующие команды  
docker build . -t "my-hello-world"  
docker run -v "$PWD"/app:/data:z my-hello-world  

