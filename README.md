# go-runtime
Docker image to run common Golang applications

## Usage
```Dockerfile
FROM cedropeople/go-runtime
```

## Content
Image based on alpine with the following additional components:
- ca-certificates - allow SSL-based applications to check for the authenticity of SSL connections
- tzdata - time zone database
- grpc-health-probe - grpc health check tool
