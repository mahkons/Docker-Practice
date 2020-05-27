Нужно выполнить следующие команды:  
docker build . -t "http-server"  
docker run -p 8080:8080 -v "$PWD"/app:/data:z http-server

На localhost:8080 можно полюбоваться на результат  
