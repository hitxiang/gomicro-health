# gomicro-health

## Get code from https://github.com/micro/kubernetes/blob/master/cmd/health/main.go

```
GOOS=linux GOARCH=amd64 go build -o health
docker build -t hitxiang/micro-health:0.0.7 .
docker run -it hitxiang/micro-health:0.0.7
docker push hitxiang/micro-health:0.0.7
```