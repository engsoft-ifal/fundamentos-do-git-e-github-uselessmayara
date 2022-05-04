## Git Clone

Aqui, vamos examinar o comando git clone. O git clone é um comando usado para selecionar um repositório existente e criar um clone ou cópia do repositório de destino. 
 O que é um repositório Git?
Um repositório do Git é um armazenamento virtual para projetos. 
Ele permite que você salve versões do código, que você pode acessar quando precisar. 
Se um projeto já foi configurado em um repositório remoto, o comando git clone cria uma cópia (ou clone) local de um repositório remoto.
Você deve informar uma URL do repositório que deseja clonar. 
Por exemplo:

```
$ git clone https://github.com/engsoft-ifal/github-starter-course.git
```

O Git é compatível com alguns protocolos de rede diferentes e formatos correspondentes de URL. 
Como SSH, HTTPS, e outros (no exemplo acima foi usado HTTPS).

Quando executada, a versão mais recente dos arquivos do repositório remoto vai ser transferida para sua máquina local e adicionada a uma nova pasta. 
A nova pasta vai ser nomeada de acordo com o nome do repositório, neste caso, github-starter-course. 

Após clonar um repositório, você precisa entrar na pasta do projeto para executar os outros comandos do git.
Você pode fazer isso usando cd NOME-DA-PASTA, como no exemplo abaixo:

```
$ cd github-starter-course/
```

Para confirmar que você está em um repositório git, você pode testar os comandos abaixo

```
$ git status
$ git remote -v
```


