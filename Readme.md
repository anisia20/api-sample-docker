- docker build -t api-sample .
- docker tag api-sample:latest 192.168.59.102:35000/api-sample:latest
- docker push 192.168.59.102:35000/api-sample:latest

