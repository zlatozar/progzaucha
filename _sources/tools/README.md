## Създаване на речник с българските думи

```shell
$ aspell --lang bg dump master | aspell --lang bg expand | tr ' ' '\n' > bulgarian.dic
```

## Инсталиране на jupyter-book

```shell
$ python3 -m pip install -U jupyter-book
```

## За локално тестване

```shell
$ cd progzaucha
$ jupyter-book create book/
$ jupyter book build book/
$ open book/_build/html/index.html 
```