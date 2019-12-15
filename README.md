# GolangCWB

Repositório do blog GolangCWB, grupo local sobre a linguagem de programação Go da cidade de Curitiba e região.

## Como contribuir

Para gerar esse blog é necessário ter instalado as ferramentas `git` e `hugo`.

As alterações no site devem sempre ser feitas pela branch `source`. A branch `master` armazena o site já gerado.

## Adicionando um novo post

Na branch `source`.

```
> hugo new post-title.md
```

E edite o arquivo criado.

Para testar locamente use:

```
> hugo server -D
```

## Atualizando o site

Na branch `source`, faça o commit das alterações e rode:

```
> sh deploy.sh
```
