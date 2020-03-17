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

As alterações em relação ao comportamento do site devem ser descritas no arquivo [`mkdocs.yml`](./mkdocs.yml), mais configurações como tema e css podem ser encontradas na própria documentação do [MkDocs](https://www.mkdocs.org/user-guide/configuration/#edit_uri):
~~~yml
site_name: WTSS Spec
repo_url: https://github.com/AbnerErnaniADSFatec/mkdocs
nav:
  - Home: index.md
~~~
O `repo_url` referencia um repositório do Github para a edição do documento markdown e para criação de pull requests.

## Execução da versão iterativa
Localizar no endereço `localhost:8000`
~~~shell
$ mkdocs serve
~~~

## Montando o site HTML e CSS
Executar o comando abaixo para a geração do site com documentos HTML e CSS formatados como na versão iterativa.
~~~shell
$ mkdocs build
~~~
