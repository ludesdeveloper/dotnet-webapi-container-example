```
dotnet new webapi
docker build -t aspnetapp .
docker run -d -p 8081:80 --name myapp aspnetapp
```
