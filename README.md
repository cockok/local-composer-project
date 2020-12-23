# local-composer-project

`composer install` でローカルプロジェクトを利用する

## Usage

```sh
docker run --rm --interactive --tty --volume $PWD:/app composer composer install
docker run --rm --volume $PWD:/app composer php main.php
```
