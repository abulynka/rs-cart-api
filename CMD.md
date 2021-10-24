## Init project

```bash
# eb init --profile personalAccount -r eu-west-1
eb init -r eu-west-1
```

## Docker build

```bash
docker build -f ./Dockerfiles/Dockerfile -t cart-api:latest .
```

## Deploy

```bash
eb create --single
```
