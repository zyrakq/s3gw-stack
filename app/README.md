# Readme

## Using

```sh
sudo pacman -S aws-cli-v2
```

```sh
aws configure
```

```sh
aws configure set endpoint_url https://s3.example.com
```

```sh
aws s3 ls
```

```sh
aws s3 cp <file> s3://<bucket> 
```

```sh
aws s3 mb s3://<new-bucket>
```

```sh
aws s3 rb s3://<remove-bucket>
```
