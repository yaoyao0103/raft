## test
```
go test -timeout 60s -race -count 1 ./...
```
I encountered permission denied in my environment, and the path of go could not be found under sudo mode, so I used sudo with absoluate path of go to test my code:
```
sudo /usr/local/go/bin/go test -timeout 60s -race -count 1 ./...
```

## result
![image](https://github.com/yaoyao0103/raft/assets/76504560/5ffebdb1-4f13-4934-9f16-855de2926be5)

