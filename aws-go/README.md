# Serverless

## Init
```
    go mod init github.com/yogparra/go-serverless/aws-go
```

## Credenciales

```
    serverless config credentials --provider aws --key xxx --secret xxx
```

## Templates
```
    serverless create -template aws-go -name curso-sls-hola-mundo
    sls create -t aws-go -n curso-sls-hola-mundo
```

## Paquetes
```
    github.com/aws/aws-lambda-go/events
	github.com/aws/aws-lambda-go/lambda
```

