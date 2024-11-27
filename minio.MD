## Setup the minio access

```sh
$> mc alias set myminio http://minio:9000 vgRW4MapAP7TICMnL582 pbjtBqLOFAM7PT6bHjPiEaPAnce9oHh44ZSL33ue
```

## ls
```sh
$> mc ls myminio

[2024-11-27 00:13:22 UTC]     0B landing/
```

## copy data
```sh
$> mc cp ./data/transactions.csv myminio/landing/
```