# Pesquisa Git, Github, Vscode.

## Git

Acesso ao [Git](https://git-scm.com/)

O Git é um sistema de controle de versão distribuído amplamente utilizado para o desenvolvimento de software. Ele foi criado por Linus Torvalds em 2005, inicialmente para o desenvolvimento do kernel do Linux. O Git permite que os desenvolvedores acompanhem as mudanças no código-fonte de seus projetos ao longo do tempo. Ele é especialmente útil em colaborações, pois permite que várias pessoas trabalhem no mesmo código de forma simultânea e coordenada.

![imagem 1](https://media.licdn.com/dms/image/D4D12AQFuCKCScEbmig/article-cover_image-shrink_720_1280/0/1681135229721?e=2147483647&v=beta&t=5frFPpiL6iZ24UN3EfWOkmWA-_1ONxN7RKNeVH-5Efc)

Principais características do Git:

1. **Controle de Versão Distribuído**: Cada usuário tem uma cópia completa do repositório, o que permite que trabalhem offline e realizem operações localmente sem depender de um servidor central.

2. **Rápido e Eficiente**: O Git é projetado para ser rápido, mesmo em projetos grandes, e é eficiente em termos de uso de espaço em disco.

3. **Ramo (Branch) e Fusão (Merge)**: Os ramos permitem que os desenvolvedores trabalhem em funcionalidades ou correções de bugs separadamente, sem interferir no código principal. A fusão permite combinar as alterações de diferentes ramos de volta ao ramo principal (geralmente chamado de 'master' ou 'main').

4. **Seguro e Integridade dos Dados**: Todas as alterações no Git são rastreadas por um sistema de hash SHA-1, garantindo a integridade dos dados.

5. **Suporte a Projetos de Qualquer Tamanho**: Desde pequenos scripts até grandes projetos de software, o Git é capaz de lidar com uma variedade de casos de uso.

6. **Ferramentas e Serviços Integrados**: Existem várias ferramentas e serviços que se integram ao Git para melhorar o fluxo de trabalho de desenvolvimento, como GitHub, GitLab e Bitbucket.

O Git se tornou uma peça fundamental no desenvolvimento de software moderno devido à sua eficiência, flexibilidade e escalabilidade. Ele é amplamente adotado por desenvolvedores individuais, equipes e grandes corporações em todo o mundo.

**Link para estudo**  [clique aqui](https://www.atlassian.com/br/git/tutorials/what-is-git) ou [aqui](https://blog.betrybe.com/git/)

**Comparação**

Git em comparação ao SVN.

| Característica      | Git                                              | SVN (Apache Subversion)                          |
|---------------------|--------------------------------------------------|--------------------------------------------------|
| Tipo de sistema     | Distribuído                                      | Centralizado                                     |
| Repositório         | Cada cópia é um repositório completo com histórico completo | Repositório central contém histórico completo, cópias locais são apenas instantâneos |
| Branching e Merging | Ramificação e mesclagem são rápidas e leves     | Ramificação e mesclagem podem ser mais lentas e pesadas |
| Desconexão          | Funciona offline sem problemas                    | Geralmente requer conexão com o servidor central |
| História            | Cada cópia do repositório tem histórico completo | O histórico completo reside no servidor central   |
| Desempenho          | Geralmente rápido, especialmente para operações locais | Pode ser mais lento, especialmente para operações remotas |
| Uso de Espaço       | Pode ocupar mais espaço devido ao histórico completo em cada cópia | Requer menos espaço devido ao histórico centralizado |
| Flexibilidade       | Mais flexível devido à natureza distribuída      | Menos flexível em comparação com a centralização  |
| Popularidade        | Extremamente popular, especialmente para projetos de código aberto | Popular, mas perdendo terreno para sistemas distribuídos como o Git |



## GitHub

Acesso ao [GitHub](https://github.com/)

O GitHub é uma plataforma de hospedagem de código-fonte baseada em nuvem que utiliza o sistema de controle de versão Git. Ele foi lançado em 2008 e desde então se tornou uma das maiores comunidades de desenvolvedores e repositórios de código do mundo.

![imagem2](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQwJo5M-5n9zg1x_i99RAIi_oFfqek8hTCETnsGwF3gVQ&s)

Principais características do GitHub:

1. **Hospedagem de Repositórios**: O GitHub permite que os desenvolvedores hospedem seus projetos de software e compartilhem código com outras pessoas. Os repositórios podem ser públicos, acessíveis a todos, ou privados, acessíveis apenas para colaboradores autorizados.

2. **Controle de Versão com Git**: O GitHub utiliza o Git como sistema de controle de versão para rastrear alterações no código-fonte ao longo do tempo. Isso inclui recursos como ramos (branches), fusões (merges) e histórico de commits.

3. **Colaboração**: O GitHub facilita a colaboração entre desenvolvedores, permitindo que eles contribuam com projetos abertos por meio de solicitações de pull (pull requests) e revisões de código. Essas funcionalidades são fundamentais para projetos de código aberto e trabalho em equipe.

4. **Gestão de Problemas e Projetos**: O GitHub oferece ferramentas para gestão de problemas (issues) e projetos, permitindo que os desenvolvedores rastreiem bugs, solicitem novos recursos e organizem o trabalho em sprints e milestones.

5. **Integração com Serviços de CI/CD**: O GitHub integra-se facilmente com serviços de integração contínua (CI) e entrega contínua (CD), permitindo automatizar a construção, teste e implantação de software diretamente a partir dos repositórios.

6. **API e Extensibilidade**: O GitHub fornece uma API robusta que permite aos desenvolvedores criar integrações personalizadas e automatizar tarefas específicas relacionadas aos repositórios e à colaboração.

O GitHub é amplamente utilizado por desenvolvedores individuais, equipes de desenvolvimento e empresas de todos os tamanhos como uma plataforma central para hospedar, colaborar e gerenciar o desenvolvimento de software. Ele desempenha um papel crucial no ecossistema de desenvolvimento moderno e é uma ferramenta essencial para a comunidade de código aberto.

**Link para estudo** [clique aqui](https://www.hostinger.com.br/tutoriais/o-que-github) ou [aqui](https://ebaconline.com.br/blog/o-que-e-github)

**Tabela Comparativa**

GitHub sendo comparado ao LinkedIn 

| Recurso         | GitHub                                   | LinkedIn                                 |
|-----------------|------------------------------------------|------------------------------------------|
| Propósito       | Plataforma de hospedagem de código-fonte | Rede social profissional e de negócios  |
| Foco Principal  | Desenvolvedores e colaboração em código | Profissionais, recrutamento e networking|
| Tipo de Conteúdo| Código-fonte, problemas, wikis, etc.    | Perfis de usuários, publicações, vagas  |
| Interação       | Colaboração em projetos, revisões de código | Conexões, mensagens, compartilhamento de postagens |
| Recrutamento    | Pode ser usado para exibir projetos e habilidades | Recrutamento ativo e passivo, exibição de experiência e habilidades |
| Público-Alvo    | Desenvolvedores, equipes de tecnologia   | Profissionais de todos os setores, recrutadores |
| Formato de Conteúdo | Texto, código, documentação         | Texto, imagens, links, documentos       |
| Monetização     | Planos pagos para empresas, hospedagem pública gratuita | Planos pagos para recrutadores e empresas, anúncios, subsídios premium |
| Usuários Ativos | Mais voltado para usuários técnicos    | Maior variedade de profissionais        |


## Vscode

Acesso ao [Vscode](https://code.visualstudio.com/)

O Visual Studio Code (VSCode) é um editor de código-fonte desenvolvido pela Microsoft. Ele é uma ferramenta de código aberto e multiplataforma (disponível para Windows, macOS e Linux) projetada para atender às necessidades dos desenvolvedores em uma variedade de linguagens de programação.

![imagem 3](https://miro.medium.com/v2/resize:fit:1400/0*ydOn9T3LuyMcTOwO)

Principais características do Visual Studio Code:

1. **Editor de Texto Avançado**: O VSCode oferece recursos avançados de edição de texto, como realce de sintaxe, formatação de código, auto-completar, refatoração, navegação de código e muito mais.

2. **Extensibilidade**: Uma das características mais poderosas do VSCode é sua extensibilidade. Ele suporta uma ampla variedade de extensões desenvolvidas pela comunidade, que adicionam novos recursos, linguagens de programação, integrações com serviços e ferramentas adicionais diretamente ao editor.

3. **Integração com Git**: O VSCode possui integração nativa com o Git, o que facilita a gestão de repositórios Git diretamente do editor. Os desenvolvedores podem visualizar o status dos arquivos, realizar commits, push/pull e muito mais, sem sair do ambiente de desenvolvimento.

4. **Depuração Integrada**: O VSCode oferece suporte integrado para depuração de código em uma variedade de linguagens de programação. Ele permite configurar pontos de interrupção, inspecionar variáveis, acompanhar o fluxo de execução e diagnosticar problemas diretamente no editor.

5. **Terminal Integrado**: O editor inclui um terminal integrado que permite aos desenvolvedores executar comandos diretamente dentro do VSCode, sem a necessidade de alternar entre o editor e uma janela de terminal separada.

6. **Gestão de Tarefas e Workspaces**: O VSCode oferece recursos para gerenciar tarefas, projetos e workspaces de forma eficiente. Ele permite abrir vários diretórios em uma única instância, organizar configurações de projeto e executar tarefas personalizadas através de scripts.

O Visual Studio Code tornou-se uma escolha popular entre os desenvolvedores devido à sua leveza, velocidade, extensibilidade e a vasta gama de recursos que oferece. É amplamente utilizado em diversos ambientes de desenvolvimento, desde projetos pessoais até grandes equipes de software.

**Link para estudo** [clique aqui](https://www.treinaweb.com.br/blog/vs-code-o-que-e-e-por-que-voce-deve-usar) ou [aqui](https://www.remessaonline.com.br/blog/visual-studio-code-confira-as-principais-funcoes-da-ferramenta/)

**Tabela Comparativa**

VScode sendo comparado ao Sublime Text.

| Recurso           | Visual Studio Code (VSCode)      | Sublime Text                     |
|-------------------|----------------------------------|----------------------------------|
| Licença           | Software Livre (MIT License)     | Proprietária (Licença comercial) |
| Extensibilidade   | Altamente extensível com uma vasta gama de extensões disponíveis na Visual Studio Marketplace | Extensível através de plugins, mas em menor quantidade comparado ao VSCode |
| Multiplataforma   | Disponível para Windows, macOS e Linux | Disponível para Windows, macOS e Linux |
| Interface         | Interface de usuário moderna e altamente customizável | Interface limpa e minimalista, com opções de personalização limitadas |
| Desempenho        | Mais pesado em termos de uso de recursos do sistema, especialmente com várias extensões ativas | Leve e rápido, mesmo com muitos arquivos abertos |
| Suporte a idiomas | Suporta uma ampla variedade de idiomas através de extensões | Suporta diversos idiomas de programação com destaque de sintaxe |
| Customização      | Configurações personalizáveis através de arquivos JSON e extensões | Customização através de configurações e plugins, mas com menos opções de personalização |
| Integração        | Integração nativa com Git e outros sistemas de controle de versão | Integração com Git e outros sistemas de controle de versão através de plugins |
| Comunidade        | Comunidade ativa de desenvolvedores contribuindo com extensões e suporte | Comunidade ativa, mas em menor escala comparado ao VSCode |
