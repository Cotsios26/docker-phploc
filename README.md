# gruen/PHPLOC
PHPLOC in a docker container.

For more information please check out the [phploc github page](https://github.com/sebastianbergmann/phploc)

## Usage
Quite simple. This assumes you are in the code directory
```shell
docker run --rm -it \
    --name phploc$(date +%s) \
    -v $(pwd):/app \
    gruen/phploc \
    [options]
```

## Tags
-   `3.0.1`, `3`, `latest`
