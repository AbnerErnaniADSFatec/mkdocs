# MkDocs

Testando a geração de documentação para códigos em markdown com o gerador de sites Python [MkDocs](https://www.mkdocs.org/).

## Instalação rápida do MkDocs
~~~shell
# pip install --upgrade pip
~~~
~~~shell
# pip install mkdocs
~~~

## Criando um novo projeto
~~~shell
$ mkdocs new DOCS
~~~

O mkdocs deve criar uma estrutura de pastas simples como descrita abaixo:
```
_ docs
  |_ index.md
|_ mkdocs.yml
```

As alterações em relação ao comportamento do site devem ser descritas no arquivo [`mkdocs.yml`](./mkdocs.yml):
~~~yml
site_name: WTSS Spec

nav:
  - Home: index.md
~~~
