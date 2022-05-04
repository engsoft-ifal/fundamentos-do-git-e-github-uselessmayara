# :wave: Configuraçao Inicial

## Instalação

Para realizar a instalação do Git no seu computador use [este guia](https://www.atlassian.com/br/git/tutorials/install-git)

## 🤓 Configurando a sua identidade

A primeira coisa que você deve fazer ao instalar Git é configurar seu nome de usuário e endereço de e-mail. Isto é importante porque cada commit usa esta informação, e ela é carimbada de forma imutável nos commits que você começa a criar:

```shell
$ git config --global user.name "Fulano de Tal"
$ git config --global user.email fulanodetal@exemplo.br
```

Você precisará fazer isso somente uma vez se tiver usado a opção --global, porque então o Git usará esta informação para qualquer coisa que você fizer naquele sistema. Se você quiser substituir essa informação com nome diferente para um projeto específico, você pode rodar o comando *sem* a opção --global dentro daquele projeto.

