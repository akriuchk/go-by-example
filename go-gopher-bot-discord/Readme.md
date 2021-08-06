Don't forget pre run gopher provider:

```
git clone https://github.com/gaelleacas/kutego-api.git
cd kutego-api
docker build -t kutego-api .
docker run -it -p 8080:8080 kutego-api:latest
```