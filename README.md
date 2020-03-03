# Website for Velo Uri


## Installation of dependencies

```
conda env create -f environment.yml
```

## Develop

```
conda activate velo-uri_lektor_env
lektor server
```

[http://127.0.0.1:5000/](http://127.0.0.1:5000/)


## Build

```
activate velo-uri_lektor_env
lektor quickstart
lektor server
lektor build -O temp
```

## Deploy

```
lektor deploy ghpages
```




