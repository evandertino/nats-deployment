### Steps to follow - [Check](https://docs.nats.io/using-nats/nex/getting-started/building-service)

  1. We need to statically compile our binary before tunning it via NEX
      ```Go
        $ GOOS=linux GOARCH=amd64 CGO_ENABLED=0 go build -tags netgo -ldflags '-extldflags "-static"'
      ```
  2. 
