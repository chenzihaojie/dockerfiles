# h5ai-base

[h5ai project](https://larsjung.de/h5ai/)

# Usage

## Common

```
docker container run -d -p 80:80 \
  -v $PWD/share:/share \
  chenzihaojie/h5ai
```

## With custom h5ai options

For overide [options.json](https://raw.githubusercontent.com/lrsjng/h5ai/v0.29.0/src/_h5ai/private/conf/options.json) file is into `/usr/share/h5ai/_h5ai/private/conf/options.json`

```
docker container run -it -p 80:80 \
  -v $PWD/share:/share \
  -v $PWD/options.json:/usr/share/h5ai/_h5ai/private/conf/options.json \
  chenzihaojie/h5ai
```
