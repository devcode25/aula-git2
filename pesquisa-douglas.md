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







