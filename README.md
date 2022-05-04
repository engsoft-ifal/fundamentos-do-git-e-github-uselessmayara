# :wave: O básico do Github 

_Este documento é uma versão traduzida para português do documento [original](https://github.com/education/github-starter-course)._

_Este material está em desenvolvimento. Inicialmente estou usando o suporte de um [tradutor automático](https://www.deepl.com/translator) e depois vou corrigindo e contextualizando melhor a tradução. Algumas palavras eu preferi manter o termo em inglês, por entender que ele é mais usado do que a tradução (por ex. commit e push)._

## 🤓 Visão geral do curso e resultados esperados

O objetivo deste material é dar uma breve introdução ao GitHub. Forneceremos também materiais para aprendizagem futura e algumas ideias para você iniciar na nossa plataforma. 🚀

## :octocat: Git e GitHub

Git é um **Sistema de Controlo de Versão (VCS em inglês)**, ou seja, é uma ferramenta útil para rastrear facilmente as alterações ao seu código, colaborar, e partilhar. Com o Git você pode rastrear as alterações feitas no projeto para que tenha sempre um registo daquilo em que trabalhou (ou está trabalhando) e possa facilmente regressar a uma versão mais antiga, se necessário. Também torna mais fácil trabalhar com outras de pessoas (em equipe) para trabalhar em conjunto no mesmo projeto e fundir (fazer merge) das suas alterações num único fonte!

GitHub é uma maneira de usar o mesmo poder de Git tudo online com uma interface fácil de usar. Ele é usado em todo o mundo para colaborar e manter a história dos projetos.

GitHub é o lar de algumas das tecnologias mais avançadas do mundo. Quer você esteja visualizando dados ou construindo um novo jogo, há toda uma comunidade e um conjunto de ferramentas no GitHub que podem levá-lo ao próximo passo. Este curso começa com as noções básicas de GitHub, mas depois vamos investigar o resto.

## :octocat: Entendendo o fluxo do GitHub 

O fluxo GitHub é um fluxo de trabalho leve que lhe permite experimentar e colaborar facilmente em seus projetos, sem o risco de perder seu trabalho anterior.

### Repositórios

Um repositório é onde seu projeto de trabalho acontece - pense nele como sua pasta de projetos. Ele contém todos os arquivos do seu projeto e o histórico de revisão. Você pode trabalhar dentro de um repositório sozinho ou convidar outras pessoas para colaborar com você nesses arquivos.

### Cloning (Clonar)

Quando um repositório é criado com GitHub, ele é armazenado remotamente no site na ☁️. Você pode clonar um repositório para criar uma cópia local em seu computador e depois usar Git para sincronizar os dois. Isso facilita a correção de problemas, a adição ou remoção de arquivos e o envio de commits maiores. Você também pode usar a ferramenta de edição de sua escolha, ao contrário da interface web do GitHub (que é bem limitada para ser usada em projetos reais). Clonar um repositório também baixa (faz download) de todos os dados do repositório que o GitHub tem naquele momento, incluindo todas as versões de cada arquivo e pasta para o projeto! Isto pode ser útil se você experimentar seu projeto e depois perceber que gostou mais de uma versão anterior. 
Para saber mais sobre clonagem, leia ["Clonando um Repositório"](https://docs.github.com/pt/repositories/creating-and-managing-repositories/cloning-a-repository). 

### Committing e pushing (não costuma-se traduzir estas duas palavras)
**Committing** e **pushing** são a forma de adicionar as alterações que fez na sua máquina local ao repositório remoto no GitHub. Desta forma, o seu instrutor e/ou colegas de equipa podem ver o seu último trabalho quando estiver pronto para o compartilhar. Você pode fazer um commit quando tiver feito alterações ao teu projeto que estejam "prontas". Pode também adicionar uma útil **mensagem de compromisso*** para lembrar-se ou lembrar os seus colegas de equipe do trabalho que fez (por exemplo, "Adicionado um README com informações sobre o projeto").

Assim que tiver um commit ou múltiplos commits que esteja pronto a adicionar ao seu repositório, pode usar o comando **push** para adicionar essas alterações ao seu repositório remoto. Commit e push podem parecer novo no início, mas prometemos que te vais habituar a isso 🙂

## 💻 Termos do GitHub

### Repositórios 
Já mencionamos os repositórios, eles são onde seu trabalho acontece, mas vamos falar um pouco mais sobre os detalhes deles! Ao trabalhar mais no GitHub, você terá muitos repositórios que podem parecer confusos no início. Felizmente, seu ["painel do GitHub"](https://docs.github.com/pt/github/setting-up-and-managing-your-github-user-account/about-your-personal-dashboard) ajuda a navegar facilmente até seus repositórios e ver informações úteis sobre eles. Certifique-se de que você esteja logado para vê-la!

Os repositórios também contêm **README**s. Você pode adicionar um arquivo README ao seu repositório para dizer a outras pessoas por que seu projeto é útil, o que eles podem fazer com seu projeto e como eles podem usá-lo. Estamos justamente usando este README para se comunicar com você. 😄 
Para saber mais sobre repositórios leia ["Criando, Clonando e Arquivando Repositórios](https://docs.github.com/pt/github/creating-cloning-and-archiving-repositories/about-repositories) e ["Sobre README's"](https://docs.github.com/pt/github/creating-cloning-and-archiving-repositories/about-readmes). 

### Branches (ou ramos)
Você pode usar branches no GitHub para isolar trabalhos que você não ainda quer misturar em seu projeto final. As branches permitem que você desenvolva recursos, corrija bugs ou experimente com segurança novas idéias em uma área contida do seu repositório. Normalmente, você pode criar uma nova branch a partir da branch padrão (main) de seu repositório. Isto faz uma nova cópia de seu repositório para que você experimente. Uma vez que suas novas mudanças tenham sido revisadas por um colega de equipe, ou você esteja satisfeito com elas, você pode mesclar (ou merge) suas mudanças no branch padrão de seu repositório.
Para saber mais sobre as branches, leia ["Sobre as branches"](https://docs.github.com/pt/github/collaborating-with-issues-and-pull-requests/about-branches).

### Forks
Um fork é outra forma de copiar um repositório, mas geralmente é usado quando se quer contribuir para o projeto de outra pessoa. Criar um repositório permite que você experimente livremente as mudanças sem afetar o projeto original e é muito popular quando você contribui com projetos de software de código aberto (software livre)!
Para saber mais sobre forking, leia ["Fork um repo"](https://docs.github.com/pt/github/getting-started-with-github/fork-a-repo)

### Pull Requests (Solicitação de Mudança)
Ao trabalhar com branches, você pode usar um pull request para informar aos outros sobre as mudanças que deseja fazer e pedir seu feedback. Uma vez aberta uma pull request, você pode discutir e rever as mudanças potenciais com os colaboradores e acrescentar mais mudanças, se necessário. Você pode adicionar pessoas específicas como revisores de sua pull request, o que mostra que você quer o feedback delas sobre suas mudanças! Uma vez que uma pull request estiver pronta, ela pode ser incorporada à sua branch principal.
Para saber mais sobre pull requests, leia ["Sobre pull requests"](https://docs.github.com/pt/github/collaborating-with-issues-and-pull-requests/about-pull-requests). 

### Issues
Issues are a way to track enhancements, tasks, or bugs for your work on GitHub. Issues are a great way to keep track of all the tasks you want to work on for your project and let others know what you plan to work on. You can also use issues to tell a favorite open source project about a bug you found or a feature you think would be great to add!

For larger projects, you can keep track of many issues on a project board. GitHub Projects help you organize and prioritize your work and you can read more about them [in this "About Project boards document](https://docs.github.com/en/github/managing-your-work-on-github/about-project-boards). You likely won’t need a project board for your assignments, but once you move on to even bigger projects, they’re a great way to organize your team’s work!
You can also link together pull requests and issues to show that a fix is in progress and to automatically close the issue when someone merges the pull request.
To learn more about issues and linking them to your pull requests, read ["About Issues"](https://docs.github.com/en/github/managing-your-work-on-github/about-issues). 

### Your user profile

Your profile page tells people the story of your work through the repositories you're interested in, the contributions you've made, and the conversations you've had. You can also give the world a unique view into who you are with your profile README. You can use your profile to let future employers know all about you! 
To learn more about your user profile and adding and updating your profile README, read ["Managing Your Profile README"](https://docs.github.com/en/github/setting-up-and-managing-your-github-profile/managing-your-profile-readme). 

### Using markdown on GitHub 

You might have noticed already, but you can add some fun styling to your issues, pull requests, and files. ["Markdown"](https://guides.github.com/features/mastering-markdown/) is an easy way to style your issues, pull requests, and files with some simple syntax. This can be helpful to organize your information and make it easier for others to read. You can also drop in gifs and images to help convey your point!
To learn more about using GitHub’s flavor of markdown, read ["Basic Writing and Formatting Syntax"](https://docs.github.com/en/github/writing-on-github/basic-writing-and-formatting-syntax). 

### Engaging with the GitHub community

The GitHub community is vast. There are many types of people who use GitHub in their day to day—students like you, professional developers, hobbyists working on open source projects, and explorers who are just jumping into the world of software development on their own. There are many ways you can interact with the larger GitHub community, but here are three places where you can start. 

#### Starring repositories 

If you find a repository interesting or you want to keep track of it, star it! When you star a repository it’s also used as a signal to surface better recommendations on github.com/explore. If you’d like to get back to your starred repositories you can do so via your user profile. 
To learn  more about starring repositories, read ["Saving Repositories with Stars"](https://docs.github.com/en/github/getting-started-with-github/saving-repositories-with-stars). 

#### Following users 

You can follow people on GitHub to receive notifications about their activity and discover projects in their communities. When you follow a user, their public GitHub activity will show up on your dashboard so you can see all the cool things they are working on. 
To learn more about following users, read ["Following People"](https://docs.github.com/en/github/getting-started-with-github/following-people).

#### Browsing GitHub Explore 

GitHub Explore is a great place to do just that … explore :smile: You can find new projects, events, and developers to interact with.

You can check out the GitHub Explore website [at github.com/explore](https://github.com/explore). The more you interact with GitHub the more tailored your Explore view will be. 

## 📝 Optional next steps 

* Open a pull request and let your teacher know that you’ve finished this course.  
* Create a new markdown file in this repository. Let them know what you learned and what you are still confused about! Experiment with different styles!
* Create your profile README. Let the world know a little bit more about you! What are you interested in learning? What are you working on? What's your favorite hobby? Learn more about creating your profile README in the document, ["Managing Your Profile README"](https://docs.github.com/en/github/setting-up-and-managing-your-github-profile/managing-your-profile-readme).
* Go to your user dashboard and create a new repository. Experiment with the features within that repository to familiarize yourself with them. 
* [Let us know what you liked or didn’t like about the content of this course](https://support.github.com/contact/education). What would you like to see more of? What would be interesting or helpful to your learning journey? 

## 📚  Resources 
* [A short video explaining what GitHub is](https://www.youtube.com/watch?v=w3jLJU7DT5E&feature=youtu.be) 
* [Git and GitHub learning resources](https://docs.github.com/en/github/getting-started-with-github/git-and-github-learning-resources) 
* [Understanding the GitHub flow](https://guides.github.com/introduction/flow/)
* [How to use GitHub branches](https://www.youtube.com/watch?v=H5GJfcp3p4Q&feature=youtu.be)
* [Interactive Git training materials](https://githubtraining.github.io/training-manual/#/01_getting_ready_for_class)
* [GitHub's Learning Lab](https://lab.github.com/)
* [Education community forum](https://education.github.community/)
* [GitHub community forum](https://github.community/)
