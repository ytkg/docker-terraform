# docker-terraform

## Install
```sh
$ git clone https://github.com/ytkg/docker-terraform.git
$ cp .env.sample .env
$ vim .env
```
```sh
# vim .env
AWS_ACCESS_KEY_ID={AWS_ACCESS_KEY_ID}
AWS_SECRET_ACCESS_KEY={AWS_SECRET_ACCESS_KEY}
AWS_REGION={AWS_REGION}
```

## Usage
```sh
$ docker-compose run --rm terraform plan
$ docker-compose run --rm terraform apply
$ docker-compose run --rm terraform destroy
```
