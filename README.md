
# Docker composer PHP7 *all extensions*

## Pull docker image

```
docker pull ivan1993spb/php7-composer
```

## Usage

Installing project:

```
docker run --rm -v $(pwd):/app ivan1993spb/php7-composer install
```

Using local .ssh directory

```
docker run --rm -v $(pwd):/app -v ~/.ssh:/root/.ssh ivan1993spb/php7-composer install
```
