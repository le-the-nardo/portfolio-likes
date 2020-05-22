# Portfolio-likes
> Projeto desenvolvido em javascript, utilizando nodeJs, Express e a biblioteca Jest para testes automatizados. 
Basicamente é uma aplicação onde pode armazenar repositórios, que permite a criação, listagem, atualização e remoção dos repositórios, além disso permite que os repositórios possam receber "likes".

## Instalação dos componentes necessários

Ferramentas que utilizei para implementação e teste da API:

1. [Visual Studio Code](https://code.visualstudio.com/download/)

2. [Insomnia](https://insomnia.rest/download/)


## Requisições suportadas pela API

GET /repositories

```sh
RRota que lista todos os repositórios;
```

Post /repositories

```sh
Rota que recebe um  `title`, `url` e `techs` dentro do corpo da requisição;
```

Put /repositories/:id

```sh
Essa rota altera apenas o `title`, `url` e as `techs` do repositório que possua o `id` igual ao `id` passado pelo parâmetro da rota;
```

Delete /repositories/:id

```sh
A rota deve deleta o repositório com o `id` presente nos parâmetros da rota;
```

Post /repositories/:id/like

```sh
A rota aumenta o número de likes do repositório específico escolhido através do `id` presente nos parâmetros da rota, a cada chamada dessa rota, o número de likes é aumentado em 1;
```

---

## Autor

Feito com muito café e dedicação de Leonardo ☕