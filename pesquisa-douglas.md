# O que é Git?
   Git é um sistema de controle de versão distribuído, gratuito e de código aberto, projetado para lidar com projetos de todos os tamanhos com rapidez e eficiência. Ele é fácil de aprender e tem uma pegada pequena, com desempenho extremamente rápido. O Git supera ferramentas de controle de versão como Subversion, CVS, Perforce e ClearCase com recursos como ramificação local barata, áreas de preparação convenientes e múltiplos fluxos de trabalho.
O Git foi criado por Linus Torvalds, o mesmo desenvolvedor do sistema operacional Linux. Ele concebeu o Git em 2005 como uma ferramenta para o desenvolvimento do kernel Linux, mas, desde então, o Git se tornou essencial para desenvolvedores em todo o mundo 
![image](https://papode.dev/assets/img/comandos-git.png)

# Características do Git

O **Git** possui várias características que o tornam uma ferramenta poderosa para controle de versão e colaboração em projetos de software. Suas principais características são:

* **Distribuído**: O Git é um sistema de controle de versão distribuído, o que significa que cada desenvolvedor tem uma cópia completa do repositório em sua máquina local. Isso permite que você trabalhe offline e mantenha históricos completos.

* **Rápido e Eficiente**: O Git é projetado para ser rápido e eficiente, mesmo em projetos grandes. As operações de **commit, ramificação e mesclagem** são executadas rapidamente.

* **Ramificação Local Barata**: Criar e alternar entre ramos é rápido e não consome muitos recursos. Isso facilita o desenvolvimento paralelo e a experimentação.

* **Área de Preparação (Staging Area)**: O Git possui uma área intermediária chamada "área de preparação" onde você pode selecionar quais alterações deseja incluir no próximo commit. Isso permite uma maior flexibilidade e controle.

* **Histórico Completo e Integridade**: O Git mantém um histórico completo de todas as alterações feitas no projeto. Além disso, ele usa hashes SHA-1 para garantir a integridade dos dados.

* **Suporte a Fluxos de Trabalho Diversos**: O Git suporta vários fluxos de trabalho, como fluxo de trabalho centralizado, fluxo de trabalho de ramificação e mesclagem, e fluxo de trabalho de ramificação e rebase.

* **Compatibilidade com Plataformas**: O Git é multiplataforma e funciona bem em sistemas operacionais como Windows, macOS e Linux.

* **Comunidade Ativa e Ferramentas Integradas**: O Git tem uma comunidade ativa e uma ampla variedade de ferramentas e serviços integrados, como o *GitHub e o GitLab*.

Se você deseja começar a usar o Git, recomendo explorar a documentação oficial e experimentar alguns comandos básicos do Git, <a href="https://git-scm.com/">Clicando aqui</a>

# Configurações
O Git possui várias configurações que permitem personalizar o ambiente e o comportamento do Git, são elas:
1. Identidade
   
   Configure seu nome de usuário e endereço de e-mail, que serão usados em cada commit
   * $ git config --global user.name "Fulano de Tal"
   * $ git config --global user.email fulanodetal@exemplo.br
     
2. Editor de Texto

   Escolha o editor de texto padrão para inserir mensagens de commit
   * $ git config --global core.editor emacs
     Se você não configurar um editor, o Git usará o padrão (geralmente o Vim)

3. Outras Configurações
Existem muitas outras opções de configuração, como:
    * Cores
    * aliases
    * comportamento de merge
    * entre outras.
      
Você pode definir configurações específicas para um repositório local **"(.git/config)"**, para o seu usuário **"(.gitconfig)"**, ou para todo o sistema **"(/etc/gitconfig)"**.

<img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQwCVKzo-ENk_PwpzgM42R79OQRurd-cfrvYHvQVY0J&s">

# O que é GitHub
O GitHub é uma plataforma de desenvolvimento colaborativo que aloja projetos na nuvem utilizando o sistema de controle de versões chamado Git. A plataforma ajuda os desenvolvedores a armazenar e administrar o código e faz o registro de mudanças. Geralmente o código é aberto, o que permite realizar projetos compartilhados e manter o acompanhamento detalhado de seu progresso. A plataforma GitHub também funciona como rede social, conectando os desenvolvedores com os usuários. Como usuário, você pode descarregar programas ou aplicativos, e da mesma maneira, pode colaborar com seu desenvolvimento oferecendo melhorias e discutindo as questões que interessam nos fóruns temáticos.

# Como utilizar o GitHub
1. Crie um repositório no GitHub
O repositório é uma localização onde se armazena toda a informação de um projeto. Ele pode conter um ou vários arquivos de código, imagens, texto, etc. Para criar um, clique no menu extensível com o símbolo + na parte superior direita da página e escolha New repository. Agora você precisa preencher com os dados necessários:

* Atribua um nome curto e claro ao seu repositório;
* Escreva uma breve descrição;
* Selecione o acesso público (para código aberto) ou privado;
* Adicione um arquivo README com comentários sobre o seu projeto;
* Clique em Create repository para confirmar a criação de seu repositório.

2. Crie uma nova ramificação (branch)
A ramificação permite você gerar diferentes versões de um projeto sem afetar o código inicial. O repositório tem um ramo principal chamado Main a partir do qual você pode criar suas próprias ramificações adicionais gerando uma cópia do projeto para adicionar novas características e fazer testes sem receio de se enganar e arruinar o trabalho feito. As mudanças introduzidas nas ramificações se espelharão no ramo principal apenas depois de uma confirmação para uni-los. Para gerar uma nova ramificação:

* Entre em seu repositório e clique na aba Code;
* Aperte o botão Main com uma lista extensível de arquivos;
* Introduza o nome da sua nova ramificação de características;
* Clique em Create branch. Agora você pode começar a fazer mudanças na nova ramificação.
  
3. Faça um commit para salvar mudanças
No GitHub, as mudanças são feitas mediante confirmações ou commits. Para manter as mudanças feitas em uma ramificação e salvá-las em seu repositório, realize os seguintes passos:

* Selecione sua ramificação recém-criada no menu extensível Main;
* Escolha o arquivo que você quer mudar;
* Clique no ícone de lápis para começar a editar;
* Adicione uma breve descrição das mudanças realizadas;
* Pressione o botão Commit changes para subir a nova versão ao repositório.
  
4. Crie uma solicitação de extração (pull request)
Se você quer introduzir ao projeto as mudanças que acaba de fazer ou propor melhorias para outros desenvolvedores, deve criar um pull request ou uma solicitação de extração.
Para aprender o fluxo do GitHub antes de trabalhar em projetos com mais colaboradores, você pode criar um pull request em seu próprio repositório seguindo estes passos:

* Abra a aba Pull requests em seu repositório;
* Clique em New pull request;
* No quadro Compare changes, selecione a ramificação que você criou para compará-la com a ramificação Main;
* Assegure-se de revisar suas mudanças antes de enviar e clique em Create pull request;
* Na nova página, escreva um título de sua solicitação e adicione uma breve descrição das mudanças que oferece;
* Confirme o envio clicando em Create pull request.
  
<img src="https://blog.ebaconline.com.br/blog/wp-content/uploads/2023/04/image4-1.png">

# História do GitHub
Lançado em 2008 e é usado desde então para que desenvolvedores possam hospedar seus projetos. Para controle de versão é usado o Git. O GitHub costuma ser o preferido entre os seus utilizadores por oferecer também alguns recursos de redes sociais, já que é possível seguir projetos de outros desenvolvedores e ainda comentar sobre todos eles. O GitHub, além de tudo, possui um recurso bastante interessante, o Git, sendo possível compartilhar um bloco de código. Além disso, também é possível trocar ideias, comentar os demais projetos e ainda pegar o código de alguém para modificar. Ele está disponível gratuitamente, com limite de armazenamento de 300MB.

Para quem busca mais privacidade, o serviço oferece ainda planos pagos, com isso, os desenvolvedores podem ter um maior controle sobre o código fonte, bem como adicionar desenvolvedores fixos e esconder os códigos dos demais membros. O GitHub funciona basicamente na nuvem, por isso é possível armazenar todo o material. Assim sendo, o projeto pode ser acessado de qualquer local.
<img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTCmeJqWnrvoD_mYtgXUS2X0wWxzuSgNZUM1LI-fnpOKg&s">

# O que é VS Code?

<img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSVxehoM-rU56fgM_FXT64f0icx4NJ7mZPXTQaQ9eG1hg&s">



O Visual Studio Code é um editor de código-fonte desenvolvido pela Microsoft para Windows, Linux e macOS. Ele inclui suporte para depuração, controle de versionamento Git incorporado, realce de sintaxe, complementação inteligente de código, snippets e refatoração de código. Ele é customizável, permitindo que os usuários possam mudar o tema do editor, teclas de atalho e preferências. Ele é um software livre e de código aberto, apesar do download oficial estar sob uma licença proprietária.

O Visual Studio Code é baseado no Electron, um framework que é usado para desenvolver aplicativos Node.js para o desktop rodando no motor de layout Blink. Apesar de usar o Electron como framework,[8] o software não usa o Atom e em seu lugar emprega o mesmo componente editor (apelidado "Monaco") usado no Visual Studio Team Services **(anteriormente chamado de Visual Studio Online)**

# História

Lançado em abril de 2015, o VS Code se tornou rapidamente uma das principais escolhas entre os desenvolvedores, independentemente da plataforma ou linguagem de programação que utilizem.
Em 18 de novembro de 2015, o Visual Studio Code foi lançado sob a licença MIT e o seu código-fonte foi postado no GitHub. O suporte para extensões também foi anunciado.
Em 14 de abril de 2016, o Visual Studio Code concluiu o estágio de previsão pública e foi lançado para a web.

# Recursos
O Visual Studio Code suporta um número de linguagens de programação e um conjunto de recursos que podem ou não estar disponíveis para a dada linguagem, como mostrado na tabela a seguir. Muitos dos recursos do Visual Studio Code features não são expostos através de menus ou da interface de usuário. Ao invés disso, elas estão acessíveis através da paleta de comandos ou por meio de um arquivo JSON (como as preferências do usuário).[12] A paleta de comandos é uma interface de linha de comandos. No entanto, ele desaparece se o usuário clicar em qualquer lugar fora dele ou pressiona uma combinação de teclas no teclado para interagir com algo fora dela. Isso também é válido para comandos de time-taking. Quando isso acontece, o comando em andamento é cancelado.

No papel de um editor de código fonte, o Visual Studio Code permite alterar a página de código na qual o documento atual é salvo, o caractere que identifica quebra de linha (uma escolha entre CR e CRLF), e a linguagem de programação do documento ativo.

<img src="https://miro.medium.com/v2/resize:fit:1400/1*cn_XBD307E3lObHk511Qqg.png">

























