# DOCUMENTAÇÃO PLATAFORMA TYCHO BRAHE (TYCHO BRAHE PLATAFORM)

<center>
<figure>
<img src="../imagens/logo_tycho1.png" width=220 height=220>
</figure>

<img src = "../imagens/logo_tycho2.png">
</center>

---

SUMÁRIO

- [DOCUMENTAÇÃO PLATAFORMA TYCHO BRAHE (TYCHO BRAHE PLATAFORM)](#documentação-plataforma-tycho-brahe-tycho-brahe-plataform)
  - [Introdução](#introdução)
  - [Caso de Uso 00 - Sign in e acesso à tela inicial de perfil do usuário cadastrado](#caso-de-uso-00---sign-in-e-acesso-à-tela-inicial-de-perfil-do-usuário-cadastrado)
    - [Descrição Caso de uso 00 - Sign in e acesso à tela inicial de perfil do usuário](#descrição-caso-de-uso-00---sign-in-e-acesso-à-tela-inicial-de-perfil-do-usuário)
    - [Diagrama do Caso de uso 00 - Sign in e acesso à tela inicial de perfil do usuário](#diagrama-do-caso-de-uso-00---sign-in-e-acesso-à-tela-inicial-de-perfil-do-usuário)
    - [Tutorial:](#tutorial)
      - [**Tutorial: Fluxo normal**](#tutorial-fluxo-normal)
      - [**Tutorial: Fluxo Alternativo**](#tutorial-fluxo-alternativo)
  - [Caso de uso 01 - Cadastro de novos usuários nos corpora da plataforma](#caso-de-uso-01---cadastro-de-novos-usuários-nos-corpora-da-plataforma)
    - [Descrição Caso de uso 01 - Cadastro de novos usuários nos corpora da plataforma](#descrição-caso-de-uso-01---cadastro-de-novos-usuários-nos-corpora-da-plataforma)
    - [Diagrama do Caso de uso 01 - Cadastro](#diagrama-do-caso-de-uso-01---cadastro)
    - [Tutorial: Cadastro de Novos Usuários - Guia do Administrador](#tutorial-cadastro-de-novos-usuários---guia-do-administrador)
      - [**Tutorial: Fluxo normal**](#tutorial-fluxo-normal-1)
      - [**Tutorial: Fluxo Alternativo 1 - Usuário não presente na Base de Dados**](#tutorial-fluxo-alternativo-1---usuário-não-presente-na-base-de-dados)
      - [**Tutorial: Fluxo Alternativo 2 - Usuário já presente na Base de Dados, vinculado a outro corpus**](#tutorial-fluxo-alternativo-2---usuário-já-presente-na-base-de-dados-vinculado-a-outro-corpus)
    - [Tutorial: Como se cadastrar em um corpus - Guia do usuário final](#tutorial-como-se-cadastrar-em-um-corpus---guia-do-usuário-final)
      - [**Tutorial: Fluxo normal (usuários não cadastrados previamente em nenhum dos corpora)**](#tutorial-fluxo-normal-usuários-não-cadastrados-previamente-em-nenhum-dos-corpora)
      - [**Tutorial: Fluxo alternativo**](#tutorial-fluxo-alternativo-1)
  - [Caso de uso 02 - Solicitar cadastro](#caso-de-uso-02---solicitar-cadastro)
    - [Descrição Caso de uso 02](#descrição-caso-de-uso-02)
    - [Diagramas do Caso de uso 02 - Solicitar cadastro](#diagramas-do-caso-de-uso-02---solicitar-cadastro)
    - [Tutorial: Solicitar cadastro na plataforma](#tutorial-solicitar-cadastro-na-plataforma)
      - [**Tutorial: Fluxo normal**](#tutorial-fluxo-normal-2)
  - [Caso de uso 03 - Criação, configuração e edição dos corpora](#caso-de-uso-03---criação-configuração-e-edição-dos-corpora)
    - [Descrição Subcaso de uso 03.1 - Criação de corpora](#descrição-subcaso-de-uso-031---criação-de-corpora)
    - [Diagrama do Subcaso de uso 03.1 - Criação de corpora](#diagrama-do-subcaso-de-uso-031---criação-de-corpora)
    - [Tutorial: Criação de corpora](#tutorial-criação-de-corpora)
      - [**Tutorial: Fluxo normal**](#tutorial-fluxo-normal-3)
    - [Descrição Subcaso de uso 03.2 - Configuração dos corpora](#descrição-subcaso-de-uso-032---configuração-dos-corpora)
    - [Diagrama do Caso de uso 03.2 - Configuração de corpora](#diagrama-do-caso-de-uso-032---configuração-de-corpora)
    - [Tutorial: Configuração de corpora](#tutorial-configuração-de-corpora)
      - [**Tutorial: Fluxo normal**](#tutorial-fluxo-normal-4)
  - [Caso de uso 04 - Ferramenta **Use eDictor**](#caso-de-uso-04---ferramenta-use-edictor)
    - [Descrição Caso de uso 04](#descrição-caso-de-uso-04)
    - [Diagrama do Caso de uso 04 - **Use eDictor**](#diagrama-do-caso-de-uso-04---use-edictor)
    - [Tutorial:](#tutorial-1)
      - [**Tutorial: Fluxo normal**](#tutorial-fluxo-normal-5)
  - [Caso de uso 05 - Ferramenta **eDictor Translations**](#caso-de-uso-05---ferramenta-edictor-translations)
    - [Descrição Subcaso de uso 05.01 - Edição de corpora (Inserir, editar e remover sentenças) ](#descrição-subcaso-de-uso-0501---edição-de-corpora-inserir-editar-e-remover-sentenças-)
    - [Diagrama do Subcaso de uso 05.01 - **Use eDictor Translations: Edição de corpora**](#diagrama-do-subcaso-de-uso-0501---use-edictor-translations-edição-de-corpora)
    - [Tutorial:](#tutorial-2)
      - [**Tutorial: Fluxo normal**](#tutorial-fluxo-normal-6)
      - [**Tutorial: Fluxo alternativo:**](#tutorial-fluxo-alternativo-2)
  - [Caso de uso 06 - Ferramenta de Pesquisa](#caso-de-uso-06---ferramenta-de-pesquisa)
    - [Descrição Caso de uso 06 - Ferramenta de Pesquisa](#descrição-caso-de-uso-06---ferramenta-de-pesquisa)
    - [Diagrama do Caso de uso 06 - FERRAMENTA DE PESQUISA](#diagrama-do-caso-de-uso-06---ferramenta-de-pesquisa)
    - [Tutorial:](#tutorial-3)
      - [**Tutorial: Fluxo normal**](#tutorial-fluxo-normal-7)
  - [Caso de uso 07 - Visualizador de corpora](#caso-de-uso-07---visualizador-de-corpora)
    - [Descrição Caso de uso 07 - Visualizador de corpora](#descrição-caso-de-uso-07---visualizador-de-corpora)
    - [Diagrama do Caso de uso 07 - Visualizador de corpora](#diagrama-do-caso-de-uso-07---visualizador-de-corpora)
    - [Tutorial:](#tutorial-4)
      - [**Tutorial: Fluxo normal**](#tutorial-fluxo-normal-8)
  - [Caso de uso 08 - Synviewer](#caso-de-uso-08---synviewer)
    - [Descrição Caso de uso 08 - Synviewer](#descrição-caso-de-uso-08---synviewer)
    - [Diagrama do Caso de uso 08- Synviewer](#diagrama-do-caso-de-uso-08--synviewer)
    - [Tutorial:](#tutorial-5)
      - [**Tutorial: Fluxo normal**](#tutorial-fluxo-normal-9)
  - [Caso de uso 09 - Parser ](#caso-de-uso-09---parser-)
    - [Descrição Caso de uso 09](#descrição-caso-de-uso-09)
    - [Diagrama do Caso de uso 09 - Parser](#diagrama-do-caso-de-uso-09---parser)
    - [Tutorial:](#tutorial-6)
      - [**Tutorial: Fluxo normal**](#tutorial-fluxo-normal-10)
      - [\*\*Tutorial: Fluxo Alternativo](#tutorial-fluxo-alternativo-3)
    - [Tutorial: Guia do Usuário Final (SE HOUVER)](#tutorial-guia-do-usuário-final-se-houver)
      - [\*\*Tutorial: Fluxo normal \*\*](#tutorial-fluxo-normal-)
      - [**Tutorial: Fluxo alternativo**](#tutorial-fluxo-alternativo-4)
  - [Caso de uso 10 - IO (Importação e Exportação)](#caso-de-uso-10---io-importação-e-exportação)
    - [Descrição Caso de uso 10 - IO (Importação e Exportação)](#descrição-caso-de-uso-10---io-importação-e-exportação)
    - [Diagrama do Caso de uso 10 - IO (Importação e Exportação)](#diagrama-do-caso-de-uso-10---io-importação-e-exportação)
    - [Tutorial:](#tutorial-7)
      - [**Tutorial: Fluxo normal**](#tutorial-fluxo-normal-11)
      - [\*\*Tutorial: Fluxo Alternativo](#tutorial-fluxo-alternativo-5)
    - [Tutorial: Guia do Usuário Final (SE HOUVER)](#tutorial-guia-do-usuário-final-se-houver-1)
      - [\*\*Tutorial: Fluxo normal \*\*](#tutorial-fluxo-normal--1)
      - [**Tutorial: Fluxo alternativo**](#tutorial-fluxo-alternativo-6)

## Introdução

A Plataforma Tycho Brahe é uma ferramenta avançada para o estudo e análise linguística, oferecendo um ambiente online integrado para a criação, análise e gestão de corpora linguísticos anotados sintaticamente. A plataforma abrange todo o processo de
desenvolvimento de corpora, desde a etapa inicial de transcrição até a aplicação de técnicas avançadas de processamento linguístico, anotação e busca.

Dentre as funcionalidades mais notáveis da Plataforma Tycho Brahe, citam-se:

- Mecanismos de busca sofisticados que permitem explorar dados linguísticos em múltiplos níveis, abrangendo desde unidades lexicais até estruturas sintáticas complexas;
- Recursos para o desenvolvimento de novos corpora, facilitando a colaboração e o compartilhamento de metodologias de anotação entre pesquisadores;
- Ferramentas especializadas para o registro e análise de idiomas ameaçados de extinção, fundamentadas em princípios da gramática gerativa;
- Suporte ao primeiro corpus com anotação sintática de uma língua indígena do Brasil, o kadiwéu, marcando um avanço significativo na documentação linguística;
- Interface intuitiva que permite a participação ativa de falantes nativos na edição e enriquecimento dos corpora, contribuindo para iniciativas educacionais em comunidades indígenas.

A Plataforma Tycho Brahe desempenha um papel crucial na preservação e no estudo de línguas ameaçadas. Sua flexibilidade e abrangência a tornam uma ferramenta valiosa para linguistas, educadores e comunidades linguísticas, promovendo avanços tanto na pesquisa acadêmica quanto na manutenção da diversidade linguística.

Este documento detalha o uso da Plataforma Tycho Brahe. A plataforma oferece uma gama de funcionalidades projetadas para facilitar a pesquisa e o trabalho com corpora linguísticos.

Entre as principais características da Plataforma Tycho Brahe, destacam-se:

- Visualizador de árvores sintáticas: permite a representação gráfica e análise detalhada de estruturas sintáticas;
- Construção de corpus: ferramentas para criar, organizar e gerenciar corpora linguísticos;
- Anotação: recursos para adicionar metadados, tags e anotações aos textos do corpus;
- Busca avançada: mecanismos de pesquisa sofisticados para localizar padrões linguísticos específicos;

Esta documentação fornecerá instruções detalhadas sobre como utilizar cada uma dessas funcionalidades, além de orientações sobre o acesso à plataforma, gerenciamento de usuários e boas práticas para o uso eficiente do sistema.

Nas seções a seguir, serão apresentadas as diversas funcionalidades da plataforma Tycho Brahe. Cada funcionalidade será apresentada com a seguinte estrutura: primeiro, uma pequena introdução; em seguida, são apresentados os casos de uso que representam as funcionalidades no sistema - é apresentada uma descrição de cada, com os atores, pré-requisitos, fluxos normal e alternativos; em seguida, é apresentado um diagrama de Caso de uso da funcionalidade em questão; por fim, um tutorial completo e detalhado de uso da funcionalidade.

---

## Caso de Uso 00 - Sign in e acesso à tela inicial de perfil do usuário cadastrado

O Sign in permite ao usuário acessar a plataforma com segurança.
Este processo envolve somente o usuário previamente cadastrado.
Como será apresentado, o usuário terá acesso à plataforma por meio de um _login_ Google.
A Área Reservada dá acesso ao Catálogo, eDictor, Syntrees, Parser e Centro Administrativo.

A tela inicial de perfil do usuário cadastrado, acessada por meio do link "Área reservada", na página inicial da plataforma, apresenta as seguintes informações.

1. **Meu Perfil**, com Informações do usuário, como e-mail, Nome, Informações acadêmicas e Idioma de preferência.
2. **Meus corpora**, que apresenta os corpora disponíveis associados ao perfil logado.
3. **Minhas Ferrametentas**, que disponibiliza as ferramentas disponíveis para o usuário logado, de acordo com as permissões de acesso configuradas.

### Descrição Caso de uso 00 - Sign in e acesso à tela inicial de perfil do usuário

**Atores primários**:

1. Usuário
2. Administrador

**Pré-requisitos:**

1. Usuário cadastrado deve estar logado; Para uso de algumas ferramentas, usuário deve ter permissão de admin.

**Fluxo normal:**

1. Usuário acessa página _home_ da plataforma no link: <https://www.tycho.iel.unicamp.br/home>.
2. Na área de "Ferramentas", o Usuário acessa "Área reservada" para ser redirecionado ao _login_.
3. Após realizar o _login_ com o Google, o Usuário é redirecionado à página inicial do perfil.

**Fluxo alternativo:**

**A1**

1. Usuário acessa o link <https://www.tycho.iel.unicamp.br/platform> diretamente, sem passar pela página inicial da plataforma e "Área reservada".
2. Retoma a partir do passo 3 do Fluxo normal

### Diagrama do Caso de uso 00 - Sign in e acesso à tela inicial de perfil do usuário

!["Diagrama acesso ao perfil"](../imagens/perfil_usuario.png)
Figura x: Diagrama do Caso de Uso 00 - Sign in e acesso à tela inicial de perfil do usuário.

### Tutorial:

**Objetivo:**
Este tutorial detalha o processo para o usuário realizar o Sign in na plataforma e acessar a tela inicial do perfil do usuário. Em um fluxo normal, o usuário já foi previamente cadastrado com um e-mail Google. Caso contrário, veja Caso de uso 02 - Solicitar cadastro para realizar a solicitação junto aos administradores da plataforma.

#### **Tutorial: Fluxo normal**

1. Acesse a página _home_ da plataforma através do link: <https://www.tycho.iel.unicamp.br/home>.
2. Na área de "Ferramentas", o Usuário acessa "Área reservada" para ser redirecionado ao _login_.

!["Acessando Área reservada"](../imagens/tycho_home_signin.png)
Figura x: Acessando "Área reservada".

3. Realize o _login_ com o Google. Selecione a conta salva no sistema ou preencha os dados da sua conta Google cadastrada na Plataforma Tycho Brahe.

![Login google](../imagens/login_google.png)
Figura x: Seleção de conta Google

Ou

![Tela de login](../imagens/tycho_home_signin2.png)
Figura X: Login in com o Google</figcaption>

4. Após _login_ o Usuário é redirecionado à página inicial do perfil, onde são dispostas as áreas **Meu Perfil**, com Informações do usuário, como e-mail, Nome, Informações acadêmicas e Idioma de preferência, que podem eventualmente ser editadas <!-- REVISAR CRÍTICO: avisar ao Luiz que as edições não são persistidos na base, não ficam salvas-->, **Meus corpora**, que apresenta os corpora disponíveis associados ao perfil logado e **Minhas Ferrametentas**, que disponibiliza as ferramentas disponíveis para o usuário logado, de acordo com as permissões de acesso configuradas.

!["Tela de perfil do usuário"](../imagens/area_reservada_perfil.png)
Figure x: Tela inicial - perfil de usuário

Observe que para cada um dos corpora disponíveis para trabalho pelo usuário, são também disponibilizados botões de acesso rápido:

!["Botões de acesso rápido"](../imagens/botoes_acesso_rapido.png)

#### **Tutorial: Fluxo Alternativo**

1. Acesse o link da plataforma/perfil <https://www.tycho.iel.unicamp.br/platform> diretamente, sem passar pela página inicial da plataforma e acesse a "Área reservada".
2. Retome a partir do passo 3 do Fluxo normal

---

## Caso de uso 01 - Cadastro de novos usuários nos corpora da plataforma

O processo de cadastro na Plataforma Tycho Brahe é um procedimento essencial para garantir o acesso controlado e seguro aos corpora. Este processo envolve tanto administradores quanto usuários finais, cada um com papéis específicos no fluxo de cadastro.

Para os administradores, o processo inclui a criação de convites, configuração de permissões e envio de links de "onboarding" para novos usuários. Já para os usuários finais, o processo consiste em receber o convite, acessar o link de "onboarding" e inserir o código de acesso fornecido.

O sistema oferece flexibilidade para lidar com diferentes cenários, como usuários não presentes na base de dados ou já cadastrados em outros corpora. Além disso, permite a configuração de diferentes níveis de permissão (edição ou admin) e status de usuário (ativo ou inativo).

Nos tópicos a seguir, será detalhado o caso de uso para o cadastro de novos usuários, bem como tutoriais passo a passo tanto para administradores quanto para usuários finais, garantindo uma compreensão completa do processo de cadastro na Plataforma Tycho Brahe.

### Descrição Caso de uso 01 - Cadastro de novos usuários nos corpora da plataforma

**Atores primários**:

1. Usuário (com permissão admin no corpus alvo)
2. Administrador da plataforma (Super-usuário com acesso a todos os corpora);

Note-se a distinção entre Administrador e Usuário com permissão de administrador (admin) em corpora específicos. O Administrador da plataforma tem permissões mais abrangentes de gestão geral na na plataforma, tendo acesso mais irrestrito aos corpora. Do contrário, o Usuário com permissão de admin em um determinado corpus não goza dos mesmos privilégios, tendo permissão de gestão apenas em corpora específicos, aos quais é associado.

**Pré-requisitos:**

1. Para o cadastramento de um usuário em um corpus, é necessário que o corpus tenha sido previamente criado (por um usuário com permissões de administrador ou Adminstrador), ou seja, a permissão de acesso tem de ser necessariamente associada a um corpus já cadastrado no sistema;
2. Configuração de permissões pelo Administrador: necessita permissão de Administrador e acesso ao link de Administrador <!--(VERIFICAR SE POSSO INSERIR link admin NA DOCUMENTAÇÃO)-->;
3. Usuário comum precisa de permissão de admin no corpus específico;
4. Solicitação de cadastro pelo usuário: nenhum (funcional); Solicitações de cadastro passam pela coordenação do projeto.

**Fluxo normal (usuário sem cadastro prévio na plataforma):**

1. O corpus é previamente criado por um Administrador ou Usuário com permissões de admin no corpus (professor, instituição coordenadora do subprojeto/corpus).
2. Usuário não está previamente cadastrado em nenhum corpus (não está na base de dados da plataforma).
3. O Administrador (ou Usuário admin) realiza **login** com a conta Google.
4. O Administrador seleciona um corpus, ou o Usuário admin seleciona "Área reservada" e seleciona a ferramente "Admin" e seleciona um corpus para gerenciar.
5. O Administrador (ou Usuário admin) acessa a aba de “Access control”.
6. O Administrador (ou Usuário admin) acessa botão “Invite” e clica em “+ Add new”.
7. O Administrador (ou Usuário admin) cria um “convite” para associação ao corpus.
8. O Administrador (ou Usuário admin) configura parâmetros de permissão de usuário:
   1. Insere um título “Title”
   2. Seleciona nível da permissão “Role” (edição ou admin)
   3. Seleciona número de convidados (1 - N): no caso de criação de convites N > 1, o contador decresce à medida que usuários se cadastram utilizando o código de acesso;
   4. Seleciona “Status” (active/inactive)
   5. Confirma
9. O sistema cria um link de “onboarding” e um código de acesso.
10. O Administrador (ou Usuário admin) copia o código e o link de onboarding e envia ao potencial usuário;
11. O usuário utiliza o link de “onboading”; clica no botão “Eu possuo um código de acesso”, preenche com o código e confirma, o que resulta em usuário cadastrado.

**Fluxo alternativo:**

**A1** - **Alternativo ao passo 5 do fluxo normal (Usuário não cadastrado previamente e não presente na base de dados)**

1. O Administrador (ou Usuário admin) envia link “/onboarding” para usuário;
2. Usuário entra no link “/onboarding” para automaticamente cadastrar email na base de dados da plataforma (no primeiro acesso, o usuário verifica uma mensagem de acesso negado ao corpus);
3. Na área /admin, o Administrador (ou Usuário admin) acessa o corpus, seleciona o botão “Users”, clica em botão “+ Add new” ;
   1. O Administrador (ou Usuário admin) seleciona email respectivo ao usuário a ser cadastrado (super-usuários e e-mails já cadastrados no corpus não são apresentados como opção);
4. O Administrador (ou Usuário admin) configura parâmetros da permissão de usuário:
   1. Admin seleciona o tipo de permissão (edição ou admin);
   2. Admin seleciona status (active ou inactive);
   3. Admin confirma cadastro do usuário no corpus;

**A2** - **Alternativo ao passo 4 (Usuário já presente na base de dados, vinculado a outro corpus)**

1. Na área /admin, o Administrador (ou Usuário admin) acessa o corpus, seleciona o botão “Users”, clica em botão “+ Add new” ;
   1. Admin seleciona e-mail respectivo ao usuário a ser cadastrado (super-usuários e emails já cadastrados no corpus não são apresentados como opção para seleção);
2. O Administrador (ou Usuário admin) configura parâmetros da permissão de usuário:
   1. Admin seleciona o tipo de permissão (edição ou admin);
   2. Admin seleciona status (active ou inactive);
   3. Admin confirma cadastro do usuário ao corpus;

### Diagrama do Caso de uso 01 - Cadastro

![Caso de uso 01:cadastro](../imagens/caso01_diagrama.png)
Figura x: Caso de uso 01 - Cadastro

### Tutorial: Cadastro de Novos Usuários - Guia do Administrador

**Objetivo:** Este tutorial detalha o processo para o Administrador da plataforma realizar o cadastro de novos usuários em corpora já criados, configurando as permissões necessárias e/ou enviando os convites de acesso. Em um fluxo normal, a coordenação ou professor entra em contato com o Admin previamente avisando a necessidade de cadastrar ou vincular um novo usuário a um determinado corpus (seja via convite para um novo cadastro na plataforma ou associação de um usuário já cadastrado a um novo corpus)

#### **Tutorial: Fluxo normal**

Antes de iniciar o processo de cadastro de um usuário, certifique-se de que o corpus ao qual o usuário será associado já tenha sido criado.

1.  **Acesso ao Sistema**: Há duas maneira de acessar o sistema de gerenciamento dos corpora.

    1. No caso de acesso por um Administrador sem associação a nenhum corpus na plataforma: faça login na plataforma com sua conta de Administrador (_login_ com a conta Google), através do link <!--(REVISAR: VERIFICAR SE POSSO DEIXAR O LINK) --> “/admin”: <https://www.tycho.iel.unicamp.br/admin>. Este link redireciona o Administrador à janela de login com a conta Google.
    2. No caso de acesso por um Usuário com permissão de admin nos corpora alvos: seguir tutorial de Caso de Uso 00 - para acesso à area de perfil do usuário.

2.  **Verificar Corpora**:

    1. **Administrador**: todos os corpora disponíveis para o Administrador aparecem na sua página inicial, através do link <https://www.tycho.iel.unicamp.br/admin> (e devido login), listados com os campos: Nome, Type, Status No. of documents, No. of words, No. of users. Verifique se o corpus que deseja gerenciar está disponível (note que são exibidos 10 resultados por página, e que pode haver várias páginas de corpora - então navegue em todas as páginas para verificar a presença do corpus alvo).<br><br>!["t"](../imagens/corpus_selecionado.png)
       Figura x: Tela inicial Administrador.<br><br>
    2. **Usuário com permissão de admin**: O Usuário admin tem acesso aos corpora aos quais está vínculado após o acesso pela "Área reservada" e o seu login, como no Caso de uso 00 -Tutorial:fluxo normal [2], e acesso à área de gerenciamento do corpus através do botão "Admin" na área "Meus corpora" (em Caso de uso 00 - Tutorial: fluxo normal[4]), como apresentado na Figura x a seguir:<br><br>
       !["Acesso aos corpora por Usuário admin"](../imagens/perfil_plataforma.png)
       Figura x: Tela inicial perfil - Área reservada

    Previamente, o usuário já deve ter realizado contato com a coordenação do projeto solicitando sua associação a determinado corpus. A coordenação então entra em contato com o administrador solicitando associação/cadastro a um determinado corpus. Veja a Figura 2 abaixo:

3.  **Selecionar o Corpus**:

    1. Na interface de Administrador, selecione o corpus ao qual o novo usuário será associado. A Figura x a seguir apresenta o catálogo de corpora disponíveis para acesso. Ao clicar em um dos corpora, o usuário é redirecionado ao corpus específico, como apresentado na Figura x, como apresentado no topo da página “Corpus: Demonstration”.
       !["Acessanco corpus pelo Administrador"](../imagens/selecionando_corpus_demo.png)
       Figura x: Corpus Demonstration selecionado
    1. No caso do Usuário com permissão admin em determinados corpora, há duas maneiras de acessar a área de gerenciamento: na área "Meus corpora" na página incial do perfil, em "Acesso rápido", clique em "Admin"; ou na área "Minhas Ferramentas", selecione "Admin":<br><br>!["Acesso à área de administração corpora"](../imagens/acesso_rapido_admin.png)
       Figura x: Acesso à área de administração dos corpra.<br><br>

4.  **Acessar "Access Control**: Na primeira tela de administração do corpus, são apresentadas informações gerais, como nome, um atalho URL, os parsers etc. No painel do corpus, clique na aba "Access Control" para gerenciar as permissões de acesso.<![](../imagens/corpus_selecionado_access_control.png)
    Figura x: Pagina inicial do corpus selecionado - Controle de acesso<br><br>

    Ao acessar o “Access Control”, a plataforma apresenta uma página com os atuais usuários com permissões no corpus selecionado, como mostra a Figura x a seguir. Com botão “Users” selecionado, é apresentado o usuário com os seguintes campos - “Name”, “status”, “Role”.

!["Área de controle de acesso"](../imagens/access_control_acessado.png)

Figura 5: Área de Controle de acesso

5.  **Criar Convite de acesso**: Na aba "Access Control", clique no botão "Invites" e depois em “ + Add new”.
6.  **Realizar as configurações da permissão:**

    1. **Inserir título:** Escolha um título para o convite no campo “Title”
    2. **Definir Quantidade de Convites**: Escolha se o convite será para um único usuário ou para múltiplos usuários (o contador de convites disponíveis será atualizado conforme os usuários se registrarem).
    3. **Definir o tipo de permissão:** Selecione o tipo de permissão “Role” que o usuário terá:
       - **Edição**: O usuário poderá editar o corpus.
       - **Admin**: O usuário terá permissões de administrador no corpus.
    4. **Status do Usuário**: Selecione o status do usuário:
       - **Active**: O usuário terá acesso ativo ao corpus.
       - **Inactive**: O usuário estará registrado, mas sem acesso ativo.

7.  **Confirmar as Configurações de permissão**: Após configurar as permissões clicar em "Confirmar".

!["Cria a configura convite"](../imagens/invites.png)
Figura x: Criação e configuração de convite de acesso<br><br>

8. **Gerar Link e Código**: O sistema gerará automaticamente um link de "onboarding" e um código de acesso.
9. **Copiar Informações para enviar ao usuário**: Copie o link de onboarding e o código de acesso gerados. O botão “click here to copy to clipboard” copia o código de acesso.

!["Tela de convite gerado"](../imagens/convite_codigo.png)
Figura x: Código de acesso gerado automaticamente

</figure>

10. **Enviar o Convite**: Envie o link de "/onboarding" e o código de acesso ao usuário potencial, via e-mail ou outro meio de comunicação apropriado.
11. Usuário recém cadastrado deve logar-se novamente para verificar se o cadastro foi bem-sucedido.

#### **Tutorial: Fluxo Alternativo 1 - Usuário não presente na Base de Dados**

Se o usuário ainda não estiver na base de dados da plataforma, siga estas etapas alternativas:

1. **Envio do Link de Onboarding**: Envie o link "/onboarding" para o usuário.
2. **Cadastro Inicial do Usuário**: O usuário acessa o link, e ao tentar se cadastrar, o sistema mostrará uma mensagem de acesso negado ao corpus.

<!--REVISAR:INSERIR IMAGEM:NÃO TENHO UMA AINDA COMO USUÁRIO NOVO-->

1. **Adicionar Novo Usuário**: Na tela /admin (<https://www.tycho.iel.unicamp.br/admin>) <!-- REVISAR:MANTER LINK?-->, selecione o corpus ou por meio da "Área reservada"(selecione o "Acesso rápido"-"Admin"). No painel de "Access Control", com o botão “Users” selecionado, clique em "+ Add New" para adicionar o usuário.
2. **Selecionar o E-mail do Usuário**: No campo de busca, preencha o nome ou e-mail do usuário (são apresentados candidatos salvos na base de dados com base no termo de busca preenchido). Escolha o nome/e-mail do usuário que você deseja cadastrar no menu drop down.
   !["Vincular usuário presente na base de dados ao corpus"](../imagens/selecao_usuario_lista.png)
   Figura x: Vincular usuário ao corpus

3. **Configurar Permissões e Confirmar**: Siga o Passos 6 e 7 do fluxo normal para configurar as permissões e confirme o cadastro.
4. Usuário recém cadastrado deve logar-se novamente para verificar sucesso de cadastro.

#### **Tutorial: Fluxo Alternativo 2 - Usuário já presente na Base de Dados, vinculado a outro corpus**

Se o usuário já estiver cadastrado em outro corpus, siga estas etapas:

1. **Adicionar novo usuário**: Acesse o link "admin" <https://www.tycho.iel.unicamp.br/admin> e selecione um corpus, ou por meio da "Área reservada"(selecione o "Acesso rápido"-"Admin"). No painel de "Access Control", com o botão “Users” selecionado, clique em "+ Add New". (Ver Figura x acima)
2. **Selecionar o e-mail do usuário**: Escolha o e-mail do usuário na lista (super-usuários e e-mails já cadastrados no corpus não aparecerão como opção). (Ver Figura x acima)
3. **Configurar Permissões e Confirmar**: Siga o Passo 6 e 7 do fluxo normal para configurar as permissões e confirme o cadastro.

### Tutorial: Como se cadastrar em um corpus - Guia do usuário final

**Objetivo:** Este tutorial detalha o processo para os usuários se cadastrarem em um corpus da plataforma, utilizando o link de "/onboarding" e código de acesso fornecido pelo administrador, ou apenas o link "/onboarding" .

#### **Tutorial: Fluxo normal (usuários não cadastrados previamente em nenhum dos corpora)**

1. **Receber Link onboarding e código de acesso (convite)**: Aguarde o e-mail ou mensagem com o link de "onboarding" e o código de acesso enviados pelo administrador da plataforma.
2. **Acessar o link**: No e-mail ou mensagem recebida, copie o link de "/onboarding" fornecido pelo administrador, insira no navegador.
3. **Acessar Página de perfil**: Você será redirecionado para uma página de perfil na plataforma. Como é o primeiro acesso, não haverá corpora vinculados na área “Meus corpora”
4. **Código de Acesso**: Na página de perfil, clique no botão "Eu possuo um código de acesso".
5. **Preencher o Código**: Insira o código de acesso fornecido no campo correspondente.
6. **Confirmar Cadastro**: Após preencher o código, clique em "Confirmar".
   !["Preenchendo código de acesso"](../imagens/preencher_codigo_acesso.png)
   Figura x: Tela de inserção de código de acesso. <br><br>

7. **Acesso ao Sistema**: O usuário deve tentar realizar o _sign in_ para certificar-se de que o cadastro foi realizado com sucesso. Se o _sign in_ for bem-sucedido, o usuário poderá acessar o corpus com as permissões definidas pelo seu administrador.

#### **Tutorial: Fluxo alternativo**

1. **Receber Link onboarding**: Aguarde o e-mail ou mensagem com o link de "onboarding" enviado pelo administrador da plataforma.
2. **Acessar o link**: No e-mail ou mensagem recebida, copie o link de "/onboarding" fornecido pelo administrador, insira no navegador.
3. **Acessar Página de perfil**: Você será redirecionado para uma página de perfil na plataforma. Como é o primeiro acesso, não haverá corpora vinculados na área “Meus corpora”. Esse acesso salva o seu e-mail na base de dados permitindo que o Admin consiga vincular o seu perfil ao corpus desejado.
4. **Acesso ao Sistema**: O usuário deve tentar realizar o _sign in_ para certificar-se de que o cadastro foi realizado com sucesso. Se o _sign in_ for bem-sucedido, o usuário poderá acessar o corpus com as permissões definidas pelo administrador.

---

## Caso de uso 02 - Solicitar cadastro

O processo de solicitação de cadastro por meio do formulário permite aos usuários iniciar o procedimento de registro na plataforma. Este caso de uso detalha as etapas necessárias para que um novo usuário envie suas informações pessoais, garantindo que os dados sejam avaliados pelos administradores, validados e armazenados corretamente no sistema. Assim, mediante análise, os administradores podem providenciar o processo de cadastramento de novos usuários.

### Descrição Caso de uso 02

**Ator primário**:

1. Usuário
2. Administrador

**Pré-requisitos:** Não há. A solicitação será avaliada pelo Adminstrador/Coordenadores da plataforma.

**Fluxo normal:**

No caso de interesse de participação no projeto, o usuário deve entrar em contato por meio do formulário no fim da página inicial do projeto.

1. Acessar a página inicial da plataforma Tycho Brahe, disponível no link: <https://www.tycho.iel.unicamp.br/home>.
2. Rolar a página até a área do formulário "Entre em contato".
3. Preencher o formulário com seu Nome, E-mail, Assunto, Mensagem (descrevendo seus interesses e motivos para associar-se, por exemplo).
4. Os Administradores devem entrar em contato sobre a solicitação e informar detalhes do procedimento de cadastro (Caso de uso 01)

### Diagramas do Caso de uso 02 - Solicitar cadastro

![Caso de uso 03](../imagens/caso03_diagrama.png)
Figura 13: Diagrama do Caso de uso 02

### Tutorial: Solicitar cadastro na plataforma

#### **Tutorial: Fluxo normal**

1. Acesse a página inicial da plataforma Tycho Brahe, disponível no link: <https://www.tycho.iel.unicamp.br/home>.
2. Role a página até chegar na área "Entre em contato".
3. Preencha o formulário com seu Nome, E-mail, Assunto, Mensagem (descrevendo seus interesses e motivos para associar-se, por exemplo).

![Solicitar cadastro](../imagens/solicitar_cadastro.png)
Figura x: Formulário para solicitar cadastro na plataforma

---

## Caso de uso 03 - Criação, configuração e edição dos corpora

A ferramenta de gestão de corpora é um componente fundamental para a construção e configuração eficiente de coleções de textos destinados a análises linguísticas. Este processo pode ser realizado por Administradores e usuários devidamente cadastrados e com as credenciais corretas (de edição).

Para os administradores, a ferramenta oferece recursos avançados para a criação e configuração dos corpora, atribuição de permissões e gerenciamento etc.

Há três formas para executar a criação de corpora na ferramenta Tycho Brahe:

1. _Translation mode_ (Modo traduções) ou _Translation eDictor_
2. <!-- <-[REVISAR CRÍTICO: INSERIR LISTA DE MANEIRAS DE DEV DE CORPUS]...diz respeito às ferramentas que vou habilitar na configuração dos corpora? Use eDictor, use Transcriber, Use designer ... ?-->

Nos tópicos a seguir, serão abordados os principais fluxos de trabalho para a criação e configuração de novos corpora, além de tutoriais detalhados que guiam administradores e usuários no uso eficiente da ferramenta, garantindo uma experiência fluida e colaborativa na gestão dos catálogos.

### Descrição Subcaso de uso 03.1 - Criação de corpora

**Atores primários**:

1. Administrador
2. Usuário

**Pré-requisitos:**

1. Os usuários devem ser previamente cadastrados e ter permissões de administrador. <!--REVISAR CRÍTICO: SOMENTE ADMINS PODEM CRIAR NOVOS CORPORA?-->

**Fluxo normal:**

1. Acessar a página inicial de /admin na plataforma Tycho Brahe, através do link: <https://www.tycho.iel.unicamp.br/admin> (e realizar o _log in_).<!--REVISAR CRÍTICO: SÓ CONSIGO CRIAR A PARTIR DO LINK ADMIN MESMO? Ou um usuário normal, por meio da área reservada consegue criar um corpus sem ser adminstrador? consegui criar com o perfil alternativo do google que não é adminstrador, mas não consigo acessar a página de gestão pelo perfil-->
2. Na janela que se abre uma lista de corpora disponíveis é apresentada. Clicar em _"+ Create new corpus"_.
3. Adicionar nome ao novo corpus e clicar em "Confirmar": novo corpus criado.

**Nota**: este processo apenas cria o corpus. Sua alimentação pode ser realizada de diferentes formas a depender do tipo de material disponível (textos em papel, áudios, arquivos .txt, arquivos .csv - com ou sem traduções), das configurações estabelecidas (Caso de uso 03.2). É necessário que haja uma interação com a equipe responsável pelo desenvolvimento da plataforma para que a melhor estratégia de importação de dados seja escolhida e aplicada. Cada um dos tipos de importação/transcrição de dados linguísticos será discutido separadamente nesta documentação.

### Diagrama do Subcaso de uso 03.1 - Criação de corpora

![Caso de uso 03.01 - Criação de corpora](../imagens/caso04_01_diagrama.png)
Figura 15: Diagrama caso de uso - Criação de corpora

### Tutorial: Criação de corpora

**Objetivo**: Este tutorial detalha os passos necessários para a criação de novos corpora através através do link de administrador.

#### **Tutorial: Fluxo normal**

1. Acesse a página inicial de administrador da plataforma Tycho Brahe, através do link: <https://www.tycho.iel.unicamp.br/admin> e realize o login com a conta Google (se não estiver logado).

2. Ao acessar a página de adminstrador, uma lista de corpora disponíveis abre. Clique em _"+ Create new corpus"_.

![Criação novo corpus](../imagens/criacao_corpus.png)"
Figura x: Criação de um novo corpus

3. Adicione um nome ao novo corpus e clique em "Confirmar": esta ação finaliza a criação do corpus (Note que estas ações apenas criam o corpus. Para inclusão/edição de documentos, ou seja, alimentar o corpus ver Caso de uso 03.2). Após preencher com o nome desejado, clique em "Confirmar". Esta ação cria um novo corpus, que aparecerá na lista.

![Criação corpus: inserir nome](../imagens/criacao_corpus_nome.png)
Figura x: Criação de corpus: inserção de nome

**Nota**: este processo apenas cria o corpus. Sua alimentação (importação de dados/transcrição de áudios/extração de dados a partir de textos impressos etc.) pode ser realizada de diferentes formas a depender do tipo de material disponível (textos em papel, áudios, arquivos .txt, arquivos .csv - com ou sem traduções), das configurações estabelecidas (Caso de uso 03.2). É necessário que haja uma interação com a equipe responsável pelo desenvolvimento da plataforma para que a melhor estratégia de importação de dados seja escolhida e aplicada. Cada um dos tipos de importação/transcrição de dados linguísticos será discutido separadamente nesta documentação.

### Descrição Subcaso de uso 03.2 - Configuração dos corpora

**Atores primários**:

<!--REVISAR CRÍTICO: VERIFICAR SOBRE AS CREDENCIAIS NECESSÁRIAS SE UM USUÁRIO NORMAL, MAS COM ACESSO ADMIN CONSEGUE REALIZAR CONFIGURAÇÕES-->

1. Administrador
2. Usuário (com permissão de admin no corpus)

**Pré-requisitos:**

1. Os usuários devem ser previamente cadastrados e ter permissões de administrador. Para cadastro, ver Caso de uso 01; para solicitar cadastro, ver Caso de uso 02. Um corpus deve ter sido criado previamente (ver caso de uso 03.1).

**Fluxo normal:**

1. Acessar a página inicial da plataforma Tycho Brahe, através do link: <https://www.tycho.iel.unicamp.br/home>.
2. Na área "Ferramentas", selecionar "Área Reservada".
3. Na página de perfil que se abre, os corpora disponíveis, vinculados ao usuário, são apresentados. O usuário deve selecionar o corpus que deseja configurar e clicar no botão "Admin" na área de "Acesso rápido".
4. Na janela que se abre, selecionar a aba "Parâmetros": abre-se uma caixa com botões de alternância para a realização de configurações de parâmetros do corpus.

**Fluxo alternativo:**

**A1** - **Acesso direto pelo link de administrador**

1. Acessar o link de administrador: <https://www.tycho.iel.unicamp.br/admin>.
2. Navegar até o corpus desejado e selecionar (abre página de gestão do corpus).
3. Retomar a partir do passo 4 do Fluxo normal e realizar as configurações de parâmetros do corpus.

### Diagrama do Caso de uso 03.2 - Configuração de corpora

![Caso de uso 03.02 - Configuração de corpora](../imagens/caso04_02_diagrama.png)
Figura x: Diagrama caso de uso - Configuração de corpora

### Tutorial: Configuração de corpora

**Objetivo:**: Este tutorial detalha os passos necessários para a configuração dos corpora. As configurações são responsáveis por determinar desde o status dos corpora, grau de privacidade, tipo de display do corpus na plataforma, tipos de ferramentas habilitadas para o corpus etc.

#### **Tutorial: Fluxo normal**

1. Acesse a página inicial da plataforma Tycho Brahe, através do link: <https://www.tycho.iel.unicamp.br/home> .

2. Navegue até a área "Ferramentas" e selecione "Área Reservada".

![Acesso área reservada](../imagens/acesso_area_reservada.png)
Figura x: Acessando "Área Reservada"

3. Na página de perfil que se abre, os corpora disponíveis, vinculados ao usuário, são apresentados. Selecione o corpus que deseja configurar e clique no botão "Admin" na área de "Acesso rápido" ou "Admin" na área "Minhas Ferramentas" e selecione o corpus que deseja configurar.

![Acesso rápido](../imagens/acesso_rapido_admin.png)
Figura x: Acesso rápido - botões "Admin"

4. Clique em "Parâmetros": uma caixa se abre, disponibilizando diversos botões de alternância para configuração do corpus.

![Parâmetros do corpus](../imagens/parametros_corpus.png)
Figura x: Acessando área de configuração de corpora

**Tutorial: Fluxo alternativo:**

**A1** - **Acesso direto pelo link de administrador**

1. Acesse o link de administrador: <https://www.tycho.iel.unicamp.br/admin>.
2. Navegue até o corpus desejado e o selecione, clicando sobre ele (isto abre a página de gestão do corpus).

![Acesso config parâmetors fluxo altern](../imagens/configura_parametro_FA1.png)
Figura x: Acesso configuração de parâmetros - Fluxo alternativo 1

3. Retomar a partir do passo 4 do Fluxo normal e realizar as configurações de parâmetros do corpus.<br>
   A seguir são apresentadas descrições de cada um dos botões de configurações disponíveis.<br>

**Public corpus**: seleciona se o corpus é disponível ao público em geral ou se é privado.

**Active**: configura se o corpus está ativo ou inativo;

**Featured Corpus**: Um corpus marcado com esse parâmetro aparece na página principal da plataforma, na área "Corpora em Destaque".

![Corpra em destaque](../imagens/corpora_em_destaque.png)
Figura x: Corpora em corpora_em_destaque

**Use Morphemes**: habilita o uso campos referentes a morfemas, incluindo glossa, nos corpora.
![Configura corpus: Use Morphemes](../imagens/botao_config_corpus_usesplit.png)
Figura X: Configuração de corpora: botão "Use Morphemes"

<br>**Use Sound**: a habilita o uso de áudio no corpus.

- Como podemos observar na Figura x abaixo, a habilitação do botão "Use Sound" habitila uma seção de Áudio, que permite ao analista incluir o áudio a ser transcrito (ou o áudio correspondente à transcrição da sentença selecionada).

  ![Configuração de corpora: botão "Use Sound"](../imagens/botao_config_corpus_usesound.png)
  Figura X: Configuração de corpora: botão "Use Sound"

<br>

- O **"Use Sound"** também habilita, na ferramenta "eDictor", um botão de _play_ para ser tocar os áudios associados às sentenças do documento selecionado, como observamos na Figura x abaixo:
  ![Configuração de corpora: botão "Use Sound" 2](../imagens/botao_config_corpus_usesound2.png)
  Figura X: Configuração de corpora: botão "Use Sound"(no eDictor)

<br>**Use Translations**: o botão "Use Translations" habilita a seção de Traduções no eDictor, como apresentado na Figura x:

![Configura corpus: Use Translations](../imagens/botao_config_corpus_usetranslation.png)
Figura x: Configuração de corpora: botão "Use Translations"

**Use Lexicon**: é utilizado quando há um parser disponível, mas não há um etiquetador automático (que só funciona se houver uma quantidade mínima de palavras para treinamento do etiquetador). No caso de esta condição não estar satisfeita, o analista deve utilizar o léxico para realizar a etiquetagem automática.

**Use Grid**: ao acessar o catálogo, o usuário tem a possibilidade de apresentação de documentos de duas maneiras: lista, ou grid. Ao habilitar o botão "Use Grid", o usuário configura a apresentação em grid como default, como apresentado na Figura x abaixo:

![Configura corpus: Use Grid](../imagens/botao_config_corpus_usegrid.png)
Figura x: Configuração de corpora: botão "Use Grid"

**Use Category**: este botão habilita a possibilidade de categorização e subcategorização dos corpora (por exemplo, categorização com base em parâmetros demográficos etc), como apresentado na Figura x, com o corpus CE-DOHS selecionado no catálogo. Note-se que a criação dos rótulos para as categorias pode ser realizada por um usuário com permissões de adminstrador

![Configuração corpus_ Use Category](../imagens/botao_config_corpus_usecategory.png)
Figura x: Configuração de corpora: botão "Use Category"

**Use Edition Tiers**<!--[REVISAR COM O LUIS]-->: este botão habilita a disponibilização de diversos níveis de edição para garantir a máxima fidelidade filológica do texto. Por exemplo, acessando-se o catálogo, selecione o corpus Tycho Brahe do Português Histórico e selecione o documento "Atas dos Brasileiros - Tomo 02", como apresentado na Figura X:

![Configura corpus: Use edition tiers](../imagens/botao_config_corpus_useeditiontiers1.png)Figura x: Configuração de corpora: botão "Use Edition Tiers"

![Configura corpus: botão Use Edition Tiers 2](../imagens/botao_config_corpus_useeditiontiers2.png)
Figura x: Configuração de corpora: botão "Use Edition Tiers" (abrindo a ferramenta).

![Configura corpus: botao Use Edition Tiers 4](../imagens/botao_config_corpus_useeditiontiers3_4.png)
Figura x: Configuração de corpora botão "Use Edition Tiers"

Esta ação abre um painel com uma matriz para edição dos níveis de edição, como mostra a Figura x. Note-se: na mesma tela que seria análoga à sentença com o "Use Morphemes" selecionado, são apresentadas os níveis de edição.

![Matriz para edição: edition tiers](../imagens/botao_config_corpus_useeditiontiers5.png)
Figura x: Matriz para edição em níveis de edição

Os botões "Use eDictor Translations"/"Use eDictor"/"Use Designer"/"Use Transcriber" não são excludentes, i.e., podem ser habilitados ao mesmo tempo em um determinado corpus. Esta ação disponibiliza todas as ferramentas para utilização no corpus.

**Use eDictor Translations**: Habilita o uso da versão eDictor para apresentação de corpora paralelos, como apresentado na Figura x a seguir:
![Use eDictor Translations](../imagens/botao_config_corpus_useedictortranslations1.png)
Figura x: Configuração de corpora: botão Use eDictor Translations - Corpora paralelos

A configuração do eDictor Tranlations também depende de configurações na aba eDictor na pagina de admin ("Corpora Management"):

- Acesse a página inicial da ferramenta no endereço <https://www.tycho.iel.unicamp.br/home>;
- Acesse "Corpora Management" na área de Ferramentas.
- Selecione o corpus que deseja configurar (ou crie um novo corpus em "+ Create New Corpus").
- Selecione a aba "eDictor" e "Translations" no canto esquerdo.
- Clique em "Create": uma caixa com campos de configurações para entradas de tradução abre:
  - **Order**: aceita números inteiros para configuração da ordem em que as línguas de tradução serão apresentadas;
  - **Symbol**: preencha com o rótulo desejado;
  - **Name**: preencha com o nome desejado;
  - **Reference**: preencha para adicionar uma referência.<!--[REVISAR: ESTA REFERENCIA DIZ RESPEITO A QUE?]-->

<br>

![Apresentação das traduções no eDictor Translations](../imagens/configura_corpus_admin_translations3.png)
Figura x: Configurações de </figcaption>

</figure>
<br>
Estas configurações habilitam a apresentação dos corpora paralelos como em [2] na Figura x abaixo; Em [3], o usuário pode selecionar qual lingua de tradução deseja que seja apresentada; Em [4], após a seleção de uma sentença, é possível verificar as traduções para a sentença selecionada, além de ser possível realizar edições nas traduções.

![Configura corpus:resultadis edictor translations](../imagens/configura_corpus_admin_translations7.png)
Figura x: Resultado configurações de eDictor Translations

**Use eDictor**: o acionamento do botão "Use eDictor" habilita o uso do eDictor tradicional para transcrição e edição.

**Use Designer**: o acionamento deste botão habilita o uso da versão do eDictor para trabalhar com textos de layouts complexos, como jornais.

**Use Transcriber**: este botão habilita o uso da versão do eDictor para trabalhar com transcrição de áudio.

**Allow POS Tag inclusion**: o acionamento deste botão possibilita adicionar novas etiquetas POS à lista enquanto o usuário edita sentenças no eDictor.

**Default for UD**: habilita que o corpus seja configurado para usar Universal Dependencies como o framework padrão para edição de sentenças.

---

## Caso de uso 04 - Ferramenta **Use eDictor**

A ferramenta **Use eDictor** habilita ao usuário o uso do **eDictor** tradicional para realizar transcrições e edições de novos corpora.

### Descrição Caso de uso 04

**Atores primários**:

1. Usuário com permissões de editor no corpus.
2. Administrador (com permissão de editor no corpus alvo)

**Pré-requisitos:**

1. Usuário logado (com permissões de edição no corpus)
2. Corpus previamente criado e o botão de configuração de parâmetros "Use eDictor" habilitado.

**Fluxo normal:**

1. Verificar (ou Habilitar) o **use eDictor** na página de /admin do corpus, na aba de parâmetros.
2. Verificar existência de documento, ou adicionar novo documento para transcrição e edição.
   1. Clicar em "+Adicionar novo documento".
   2. Preencher nome do novo documento.
   3. Selecionar Ferramenta de edição (dentre use eDictor ou eDictor Translation) - Para este caso de uso selecionar a primeira.
3. Realizar o upload de um arquivo de imagem de onde pretende realizar a transcrição: do lado esquerdo da página que abre após a criação do documento, clicar em "clique aqui para realizar o upload. Selecionar imagem e confirmar.
4. Transcrições:
   **Manual**: Clicar o botão "Transcrição" para abrir o campo de preenchimento manual das transcrições do texto da imagem inserida.
   **Automática**: Clicar o botão "extrair texto de imagem" no canto superior direito para realizar a transcrição automática a partir do texto da imagem.
5. Preencher transcrições (ou revisar transcrições extraídas automaticamente de um arquivo de imagem) e salvar.
6. Clicar ícone de "ir para o modo edição" para preparar o texto para receber edições.
7. Etiquetagem e outras edições:
   **Manual**: Clicar sobre palavra que deseja editar e realizar as edições desejadas:

   - Operações: inserir palavras, dividir, juntar com a próxima, spliter, remover.
   - Observações: adicionar observações.
   - Notas de rodapé: adicionar notas de rodapé
   - Edição da palavra original.
   - Etiqueta POS.
   - Flexão
   - Botão de alternância para "Ignorar para análise automática".
   - Botão de alternância para "Marcar esta palavra para ser revisada".
   - Operações de edição: junção e segmentação
   - Níveis de edição: grafia, expansão, correção, pontuação, ilegível, modernização, padronização, flexão.

   **Automática**: há duas maneiras de acessar as orações para realizar o _parser_ e revisar/editar a etiquetagem. Ao acessar o "exibir informações" do documento, selecionar:

   - **Continuar anotação sintática** (Continue a partir da última sentença revisada): Ao acessar esta área, a plataforma apresenta a primeira sentença do documento (e se o parser já tiver sido aplicado previamente, apresenta também a árvore que corresponde à sentença). É possível navegar entre as sentenças através das setas do lado direito superior.
     1. Para rodar o _parser_ na sentença selecionada é necessário que um parser tenha sido associado ao corpus previamente. Em caso afirmativo, clicar em no ícone de "parser" no canto superior direito.
     2. É possível editar os nós da árvore sintática: clicar sobre o nó desejado e selecionar a etiqueta adequada.

   Outras informações a ações são disponibilizadas neste tela: abrir comentários, ver manuais de anotação sintática, salvar, desfazer/refazer, aplicar layout, histórico, juntar à próxima sentença (ação não permitida caso a sentença tenha tradução e/ou áudio correspondentes), debugar _parser_, e por fim, marcar status de revisão de etiquetagem da sentença (a fazer, como pronta, para revisão).<!--REVISAR: EVENTUALMENTE ESTA PARTE DEVE SER MAIS DETALHADA-->

   - **Revisar etiquetas POS**: Ao se acessar esta área, a plataforma apresenta as sentenças do documento para que o usuário possar realizar uma revisão da etiquetagem. Se o _parsing_ já tiver sido previamente realizado na sentença, ela apresenta as etiquetas atribuídas. Do contrário, a camada de etiquetagem POS fica com _vazio_ atribuído a todas os tokens.

     1. Para rodar o parser na sentença desejada (caso a sentença ainda não tenha sido etiquetada), clicar no ícone "▶️" do lado esquerdo da sentença alvo.
     2. É possível também realizar edições manuais em cada uma das etiquetas nas palavras da sentença: clicar sobre a etiqueta (ou "vazio"), selecionar a etiqueta desejada e inflexão e confirmar.
     3. Revisar sentença etiquetada e marcar status (a fazer, como pronta, para revisão.)
        É possível ainda realizar outras ações: desfazer edição, ir para o eDictor, filtrar.

### Diagrama do Caso de uso 04 - **Use eDictor**

<figure>
    <img src=""
         alt="">
    <figcaption>Figura X: CAPTION</figcaption>
</figure>

### Tutorial:

**Objetivo:**

#### **Tutorial: Fluxo normal**

1. Verifique (ou Habilite) o **use eDictor** na página de /admin do corpus, na aba de parâmetros.

![Use eDictor habilitado](../imagens/use_edictor_1.png)
Figura x: Habilitando o use eDictor.

2. Verifique se o documento que deseja editar está no corpus, ou adicione novo documento para transcrição e edição.
   1. Clique em "+Adicionar novo documento".
   2. Preencha o nome do novo documento.
   3. Selecione a Ferramenta de edição desejada para o documento (dentre use eDictor ou eDictor Translation) - Para este caso de uso selecione o use eDictor.

![Adicionar documento](../imagens/use_edictor_2.png)
Figura x: Adicionando documento para use eDictor.

3. Realize o upload de um arquivo de imagem de onde pretende realizar a transcrição: do lado esquerdo da página que abre após a criação do documento, clique em "clique aqui para realizar o upload", selecione imagem e confirme.

![Upload arquivo para transcrição](../imagens/use_edictor_3.png)
Figura x: Upload de documento para eDictor.

![Confirma arquivo](../imagens/use_edictor_4-5.png)
Figura x: Envio do aquivo para eDictor.

4. Transcrições:
   **Manual**: Clique o botão "Transcrição" para abrir o campo de preenchimento manual das transcrições do texto da imagem inserida.

![EDictor transcrição](../imagens/use_edictor_6.png)

**Automática**: Clique o botão "extrair texto de imagem"(T), no canto superior direito, para realizar a transcrição automática a partir da imagem com texto.

![Extração texto de imagem](../imagens/use_edictor_11.png)
Figura x: Transcrição automática - extrair texto da imagem

5. Preenchidas as transcrições, manualmente ou automaticamente, salve as alterações clicando no ícone em [2].

![Salvar transcrição](../imagens/use_edictor_7.png)
Figura x: Salvando uma transcrição .

6. Clique no ícone de "ir para o modo edição" para preparar o texto para receber edições.

![Selecionando edição](../imagens/use_edictor_8.png)
Figura x: Preparando texto para edição

7. Etiquetagem e outras edições:
   **Edições manuais**: Clicar sobre palavra que deseja editar e realizar as edições desejadas:

   **Operações**:
   ![Menu operações](../imagens/use_edictor_24.png)

- **Inserir palavras**: selecionada uma palavra da sentença, no menu "Operações" seleciona "inserir". Uma tela com espaço para preencher palavras a serem inseridas se abre. Preencha as palavras que deseja adicionar e confirme. Note que as palavras preenchidas serão inseridas após a palavra selecionada para edição na sentença;

![Inserir palavras](../imagens/use_edictor_25-26.png)

- **Dividir**: Divida a palavra selecionada em duas ou mais (separadas por espaços). As palavras separadas por espaços serão incluídas como novos _tokens_ na sentença e todas as informações dar parseamento serão redefinidas.

![Dividir tokens](../imagens/use_edictor_27-28.png)
Figura x: Dividindo palavras.

- **Juntar com a próxima**: Com a palavra que será junta e a operação "juntar com a próxima" selecionadas, clique em "Confirmar" para juntar as palavras. Note que a palavra selecionada se juntará à seguinte na sentença e informações de parseamento serão redefinidas.

![Juntar à próxima](../imagens/use_edictor_29-30.png)
Figura x: Juntar com a próxima palavra.

- **Spliter**: é possível adicionar ou remover spliter de um par de palavras. <!--[ REVISAR: VER COM O LUIZ COMO FUNCIONA - NÃO PARECE ESTAR EM FUNCIONAMENTO?]-->
- **Remover** uma palavra: Selecione a palavra que deseja remover, clique em "remover" e confirme.

![Remoção de palavra](../imagens/use_edictor_31.png)
Figura x: Remoção de palavras.

- **Observações**: é possível adicionar observações nas palavras. Clique em "Observações", preencha o campo com as observações desejadas e confirme. As palavras com observações serão grifadas no eDictor e as observações são apresentadas ao usuário passar o cursor sobre a palavra grifada.

![Observações](../imagens/use_edictor_32.png)
Figura x: Incluindo observações.

- **Notas de rodapé**: é possível, também, adicionar notas de rodapé nas palavras. Com a palavra selecionada, clique em "Notas de rodapé". Preencha o campo com as notas desejadas e confirme. O token recebe um índice superior e a nota correspondente aparece no rodapé do eDictor.

![Notas de rodapé](../imagens/use_edictor_33-34.png)
Figura x: Notas de rodapé

- **Edição da palavra original**: é possível realizar uma edição na palavra selecionada. Selecione a palavra desejada; no campo "Palavra original" realize as edições desejadas e clique em "Salvar".

![Editar palavra original](../imagens/use_edictor_36.png)
Figura x: Editando as palavras originais.

- **Etiqueta POS**: selecione a palavra que deseja etiquetar; clique sobre o campo "Etiquetas POS" para abrir um menu suspenso com as opçõs de etiquetas POS; selecione a etiqueta apropriada; clique em "Salvar".

![Etiquetas POS](../imagens/use_edictor_36-37.png)
Figura x: Etiquetando POS.

- **Flexão**: além da etiqueta POS, também é possível marcar etiquetas de flexão (1,2,3S e 1,2,3P). Clique no campo "Flexão" para abrir o menu suspenso; selecione a flexão desejada e clique em "Salvar".

![Flexão](../imagens/use_edictor_38-39.png)
Figura x: Etiquetas de flexão

- **Ignorar para análise automática**: esta botão de alternância marca a palavra selecionada para ser ignorada pela análise automática. Essa operação altera a estrutura sintática e todas as informações de análise são redefinidas. Com a palavra selecionada, clique no botão de alternância "Ignorar para análise automática", leia a mensagem de aviso e clique em "Confirmar".

![Ignorar para análise automática](../imagens/use_edictor_40.png)
Figura X: Ignorar palavra para análise automática.

- "**Marcar esta palavra para ser revisada**": este botão de alternância grifa a palavra, marcando-a como palavra a ser revisada.

![Marcar para revisão](../imagens/use_edictor_41.png)
Figura x: Marcar palavra para revisão

- **Operações de edição**:
  <!--[REVISAR: pedir Luiz exemplos de segmentação e junção para entender melhor o objetivo destas funcionalidades-->
  - junção: é possível inserir junções. Selecione uma palavra, preencha o campo "junção" e clique no botão azul para confirmar.
  - segmentação: é possível incluir segmentações. Selecione a palavra, preencha o campo "segmentação" e clique no botão azul para confirmar.

![Junção e segmentação](../imagens/use_edictor_42.png)
Figura x: Junção e Segmentação.

- **Níveis de edição**: é possível preencher diversos níveis de edição da palavra selecionada.Selecione a palavra desejada, preencha os diversos Níveis de edição: grafia, expansão, correção, pontuação, ilegível, modernização, padronização, flexão. A palavra cujo preenchimento dos níveis de edição for realizado fica grifada, e as informações são apresentadas sob contato do cursor.

![Níveis de edição](../imagens/use_edictor_43-44.png.png)
Figura x: Níveis de edição.

**Edições automáticas**: há duas maneiras de acessar as orações para realizar o _parser_ e revisar/editar a etiquetagem. Ao acessar o "exibir informações" do documento, selecionar:

- **"Continuar anotação sintática"** (Continue a partir da última sentença revisada): Ao acessar esta área, a plataforma apresenta a primeira sentença do documento (e se o parser já tiver sido aplicado previamente, apresenta também a árvore que corresponde à sentença). É possível navegar entre as sentenças através das setas do lado direito superior.
  1. Para rodar o _parser_ na sentença selecionada é necessário que um parser tenha sido associado ao corpus previamente. Em caso afirmativo, clicar em no ícone de "parser" no canto superior direito.
  2. É possível editar os nós da árvore sintática: clicar sobre o nó desejado e selecionar a etiqueta adequada.

Outras informações a ações são disponibilizadas neste tela: abrir comentários, ver manuais de anotação sintática, salvar, desfazer/refazer, aplicar layout, histórico, juntar à próxima sentença (ação não permitida caso a sentença tenha tradução e/ou áudio correspondentes), debugar _parser_, e por fim, marcar status de revisão de etiquetagem da sentença (a fazer, como pronta, para revisão).<!--REVISAR: EVENTUALMENTE ESTA PARTE DEVE SER MAIS DETALHADA-->

- **Revisar etiquetas POS**: Ao se acessar esta área, a plataforma apresenta as sentenças do documento para que o usuário possar realizar uma revisão da etiquetagem. Se o _parsing_ já tiver sido previamente realizado na sentença, ela apresenta as etiquetas atribuídas. Do contrário, a camada de etiquetagem POS fica com a etiqueta "vazio" atribuída a todas os tokens.

  1. Para rodar o parser na sentença desejada (caso a sentença ainda não tenha sido etiquetada), clicar no ícone "▶️" do lado esquerdo da sentença alvo.
  2. É possível também realizar edições manuais em cada uma das etiquetas nas palavras da sentença: clicar sobre a etiqueta (ou "vazio"), selecionar a etiqueta desejada e inflexão e confirmar.
  3. Revisar sentença etiquetada e marcar status (a fazer, como pronta, para revisão.)
     É possível ainda realizar outras ações: desfazer edição, ir para o eDictor, filtrar.

---

## Caso de uso 05 - Ferramenta **eDictor Translations**

A ferramenta **Use eDictor Translations** habilita o uso da versão eDictor para desenvolvimento de corpora com suas traduções nas línguas configuradas e selecionadas pelo usuário. A habilitação desta ferramenta permite, consequentemente, a apresentação dos corpora de forma paralela, ou seja, com originais e traduções de forma paralela e sincronizada.

<!--[REVISAR: AVALIAR SE FUTURAMENTE VOU INSERIR AS OUTRAS FUNCIONALIDADES DE EDIÇÃO DOS CORPORA AQUI: EDITAR ETIQUETAS DAS DIVERSAS CAMADAS ETC]-->

### Descrição Subcaso de uso 05.01 - Edição de corpora (Inserir, editar e remover sentenças) <!--[REVISAR: CONSIDERER SUBDIVIDIR OS CASOS?]-->

**Atores primários**:

1. Usuário (com acesso admin ao corpus)
2. Adminstrador

**Pré-requisitos:**

1. Usuário logado (com permissões de edição no corpus)
2. Corpus previamente criado e o botão de configuração de parâmetros "Use eDictor Translations" habilitado.

**Fluxo normal:**

1. Acessar a página inicial da plataforma Tycho Brahe, através do link: <https://www.tycho.iel.unicamp.br/home>.
2. Na área "Ferramentas", selecionar "Área Reservada" e realizar login com conta Google (se já não estiver logado).
3. Na página de perfil que se abre, os corpora disponíveis, vinculados ao usuário, são apresentados. O usuário deve selecionar o corpus que deseja configurar e clicar no botão "eDictor" na área de "Acesso rápido".
4. Com o catálogo aberto, selecionar o corpus e documento que deseja editar.
5. Acessar "Exibir informações" clicando no ícone com menu no documento do corpus.
6. Na aba de ações que abre à esquerda, no campo "Continuar a edição do documento", clique na seta para abrir o menu de ferramentas de edição: selecionar o "eDictor Translations".

   1. Inserir textos (sentenças):
      1. Selecionar "Inserir texto".
      2. Inserir o texto fonte (original); selecionar o idioma de tradução; inserir texto traduzido. (Nota: sentenças a serem sincronizadas em paralelo podem ser separadas por quebra de linha).
      3. Clicar em "Salvar" para salvar transcrições.
      4. Clicar no botão "Sincronizar", para que as sentenças fonte e alvo sejam apresentados paralelamente.
      5. Clicar em "Inserir sentenças" para inserir sentenças paralelas no documento do corpus.
   2. Apagar textos transcritos (ainda não sincronizados):
      1. Selecionar "Inserir texto"
      2. Clicar em "Apagar" para apagar textos transcritos (Textos já sincronizados são mantidos)
   3. Editar sentenças sincronizadas:

      1. Via botão E - eDictor: 1. Selecionar um par de sentenças. 2. Selecionar botão E (eDictor). 3. Para editar o original: no quadro, clicar no ícone de "lápis" (edição) da palavra que desejar, editar a palavra e confirmar. 4. Para editar a tradução: rolar a página até o campo de "Traduções", editar o campo com o texto e salvar. 5. Para outras edições da palavra: clicar em "...", 1. "Inserir": inserir palavra á direita 2. "Dividir": dividir palavra em duas 3. "Unir": unir palavras 4. "Variações" 5. "Remover": remover palavra 6. Para edições da sentença, clicar em "...":

         1. "Dividir": dividir sentença em duas (após token selecionado)
         2. "Unir": unir com sentença seguinte

         Nota: A função de Dividir e Unir sentenças não funciona se a sentença tiver traduções e áudios associados. Na tentativa, o sistema retorna uma mensagem de erro e a operação é impedida:

         ![Erro união sentença](../imagens/edictor_erro_unir_sentenca.png)

      2. Via botão UD <!--REVISAR CRÍTICO: ACREDITO QUE PARA FAZER EDIÇÕES NO ORIGINAL COM UD SELECIONADO É NECESSÁRIO ANTES TER ASSOCIADO UM PARSER - NO CASO DO NHEENGATU POR EXEMPLO, SÓ CONSIGO EDITAR COM O EDICTOR SELECIONADO-->:
         1. Selecionar um par de sentenças.
         2. Selecionar botão UD (Dependências Universais).
         3. Para editar o original: no quadro, na linha da palavra desejada clicar no ícone de lápis (edição) da palavra que desejar, editar a palavra e confirmar.
         4. Para editar a tradução: não há edição de tradução com o botão UD selecionado.
         5. Para incluir palavra: na linha da palavra selecionada, clicar em "+", editar o campo e confirmar.
         6. Para aplicar informações de um token a todos tokens similares do documento: na linha da palavra objetivo, clicar no ícone de "cópia"
         7. Para deletar: na linha da palavra, clicar no ícone com "lixeira" e confirmar.

   4. Remover sentenças sincronizadas:
      1. Selecionar um par de sentenças.
      2. Clicar em no ícone de "lixeira" (remover) e confirmar.

**Fluxo alternativo:**

**A1**

1. Acessar a página de catálogo através do link: <https://www.tycho.iel.unicamp.br/catalog>
2. Seguir a partir de 3 no Fluxo normal.

**A2** Alternativa para inserção de sentenças

Seguir o fluxo normal de 1 a 5, ou o fluxo A1, para acesso à ferramenta eDictor Translations. Para um fluxo alternativo de inserção de novas sentenças:

1. Selecionar um par de sentenças.
2. Clicar no botão "Adicionar nova".
3. Uma caixa de diaĺogo se abre: clicar em "confirmar".
4. No campo superior "digite a transcrição aqui", preencher.
5. Preencher as traduções e clicar no botão verde para salvar.
6. Clicar em "adicionar nova sentença"

### Diagrama do Subcaso de uso 05.01 - **Use eDictor Translations: Edição de corpora**

![Caso de uso 5.01.](../imagens/caso6.01.1_diagrama.png)
Figura X: Diagrama Caso de uso 5.01 - Edição de corpora (eDictor Translations)

!["Caso de uso 5.01 - Ações no corpus"](../imagens/caso6.01.2_diagrama.png)
Figura x: Cont. Diagrama Caso de uso 5.01 - Ações no corpus <!--REVISAR: VOU TER DE MODIFICAR ESTA FIGURA NÃO SEI SE VALE A PENA-->

### Tutorial:

**Objetivo:** Este tutorial detalha os procedimentos necessários para a edição de corpora usando a ferramenta **"eDictor Translations"**.

#### **Tutorial: Fluxo normal**

1. Acesse a página inicial da plataforma Tycho Brahe, através do link: <https://www.tycho.iel.unicamp.br/home> .

2. Navegue até a área "Ferramentas" e selecione "Área Reservada".
   !["Acessando área reservada"](../imagens/acesso_area_reservada.png)
   Figura x: Acessando "Área Reservada"<br><br>

3. Na página de perfil que se abre, os corpora disponíveis, vinculados ao usuário, são apresentados. Selecione o corpus que deseja configurar e clique no botão "eDictor" na área de "Acesso rápido" ou "eDictor" na área "Minhas Ferramentas" e selecione o corpus que deseja configurar.
   !["Selecionando o eDictor"](../imagens/acesso_rapido_edictor.png)
   Figura x: Selecionando a ferramenta eDictor <br><br>

4. Com o catálogo aberto, clique sobre o nome do corpus e como em [1] para abrir a lista suspensa com os corpora disponíveis e selecione o corpus que deseja editar [2], como na Figura x:
   !["Selecionando um corpus no catálogo"](../imagens/edictor_selecionando_corpus.png)
   Figura x: Selecionando um corpus no catálogo</figcaption><br><br>

5. Após selecionar o corpus que deseja editar, acesse "Exibir informações" clicando no ícone com menu (menu com seis pontos) no documento do corpus.
   !["Acessando "Exibir informações"](../imagens/edict_trans_exibir_info.png)
   Figura x: Acessando "Exibir informações"<br><br>

6. Na aba de "Ações" , na menu que abre à esquerda, no campo "Continuar a edição do documento", clique na seta para abrir o menu de ferramentas de edição: selecionar o "eDictor Translations" (Nota: o botão de configuração de parâmetros "Use eDictor Translations" deve estar habilitado para habilitar a edição através do **eDictor Translations**).
   !["Abrir edição com "eDictor Translations""](../imagens/exib_info_selecionando_ferramentas_edicao.png)
   Figura x: Ações - Abrir edição com "eDictor Translations"<br><br>

   1. Para inserir textos (sentenças):

      1. Selecione o botão "Inserir texto".
      2. Preencha o campo que apresenta "Digite ou cole o texto no idioma original" com o texto fonte (original); selecione o idioma de tradução; preencha o campo "Digite ou cole o texto traduzido em: [idioma selecionado para tradução]" com o texto traduzido.
      3. Clique em "Salvar" para salvar transcrições.
      4. Clique no botão "Sincronizar", para que as sentenças fonte e alvo sejam sincronizadas apresentadas paralelamente.
      5. Clique em "Inserir sentenças" para que as sentenças sincronizadas sejam inseridas no documento do corpus.
         !["Inserir sentenças"](../imagens/edictor_trans_acoes_edicao.png)Figura x: Ações no eDictor Translations

   2. Apagar textos transcritos (ainda não sincronizados):

      1. Selecione "Inserir texto"
      2. Clique em "Apagar" para apagar textos transcritos (Textos já sincronizados são mantidos)
      3. Clique em "voltar" para retornar ao documento com suas sentenças paralelas. !["Apagar sentenças"](../imagens/edict_trans_sentencas_sincronizadas_inseridas.png)Figura x: Sentenças sincronizadas e inseridas no documento

   3. Editar sentenças sincronizadas:
      1. Via botão E - eDictor:
         1. Com o corpus já selecionado, selecione um par de sentenças.!["Seleciona sentença"](../imagens/edictor_edicao_sent_sincronizadas4.png)
         2. Selecione botão E (eDictor).!["seleciona E"](../imagens/edictor_edicao_sent_sincronizadas5.png)
         3. Para editar o texto original do token: no quadro, clique no ícone de "lápis" (edição) da palavra que desejar, edite a palavra e confirme.
         4. Para editar a tradução: role a página até o campo de "Traduções", edite o campo com o texto e salve.!["editando texto"](../imagens/edictor_edicao_sent_sincronizadas6.png)
         5. Para outras edições da palavra: clique em "...":
            1. Clique em "inserir": inserir palavra á direita da palavra selecionada, preencha o campo e confirme!["edições palavra"](../imagens/edictor_edicao_sent_sincronizadas7.png)
            2. Clique em "dividir": dividir palavra em dois tokens distintos![""](../imagens/edictor_edicao_sent_sincronizadas8-9.png)
            3. Clique em "unir" para unir o toke selecionado ao token seguinte na sentença: ![""](../imagens/edictor_edicao_sent_sincronizadas10.png)
            4. Clique em "Variações": o botão de variações apresenta todas as variações de etiquetas e glossas utilizadas para a palavra e salvas no banco de dados. Este botão permite um preenchimento mais rápido das informações sobre a palavra selecionada.
            5. Clique em "remover": remover palavra.![""](../imagens/edictor_edicao_sent_sincronizadas11.png)
         6. Para edições da sentença, clicar em "...":
            1. "Dividir": dividir sentença em duas (após token selecionado)
            2. "Unir": unir com sentença seguinte
      2. Via botão UD:
         1. Com o corpus já selecionado, selecione um par de sentenças.!["Seleciona sentença"](../imagens/edictor_edicao_sent_sincronizadas4.png)
         2. Selecione botão UD (Dependências Universais).![""](../imagens/edictor_edicao_sent_sincronizadas12.png)
         3. Para editar o original: no quadro, na linha da palavra desejada clique no ícone de lápis (edição) da palavra que desejar, edite a palavra e confirma.![""](../imagens/edictor_edicao_sent_sincronizadas13.png)
         4. Não há edição de tradução com o botão UD selecionado
         5. Para incluir palavra: na linha da palavra selecionada, clique em "+", preencha o campo com a palavra a ser adicionada e confirme.![""](../imagens/edictor_edicao_sent_sincronizadas14.png)
         6. Para aplicar informações de um token a todos tokens similares do documento: na linha da palavra selecionada, clique no ícone de "cópia".![""](../imagens/edictor_edicao_sent_sincronizadas15.png)
         7. Para deletar: na linha da palavra, clique no ícone com "lixeira" e confirme.![""](../imagens/edictor_edicao_sent_sincronizadas16.png)
   4. Remover sentenças sincronizadas:
      1. Selecionar um par de sentenças.
      2. Clicar em no ícone de "lixeira" (remover) e confirmar.![""](../imagens/edictor_edicao_sent_sincronizadas17.png)

#### **Tutorial: Fluxo alternativo:**

**A1**

1. Acesse a página de catálogo através do link: <https://www.tycho.iel.unicamp.br/catalog> :

![""](../imagens/edictor_edicao_sent_sincronizadas18.png)
Figura x: Acesso a catálogo

2. Siga a partir do item 3 do Fluxo normal.

**A2** - Alternativa para inserção de sentenças

Siga o fluxo normal de 1 a 5, ou o fluxo A1, para acesso à ferramenta eDictor Translations. Para um fluxo alternativo de inserção de novas sentenças:

1. Selecione um par de sentenças.
2. Clique no botão "Adicionar nova".
3. Uma caixa de diaĺogo se abre: clique em "confirmar".

![""](../imagens/edictor_adicionar_sentença_1.png)

4. No campo superior "digite a transcrição aqui", preencha com o texto desejado.
5. Preencha as traduções e clique no botão verde para salvar.
6. Clique em "adicionar nova sentença".

![""](../imagens/edictor_adicionar_sentença_2.png)

Sentença e tradução adicionadas:
![alt](../imagens/edictor_adicionar_sentença_3.png)

---

## Caso de uso 06 - Ferramenta de Pesquisa

A Ferramenta de Pesquisa possibilita ao usuário realizar pesquisas nos corpora disponíveis na plataforma Tycho Brahe. Há dois tipos de busca disponíveis na plataforma: **Pesquisa simples** e **Pesquisa sintática**. A Pesquisa Simples possibilita que o usuário utilize a sintaxe de expressões regulares (regex) para realizar buscas. Por outro lado, a Pesquisa Sintática disponibiliza dois modos de busca: um modo direto, utilizando os campos com listas suspensas, que apresentam opções para as seleções pertinentes para a pesquisa; ou um modo que possibilita a escrita livre da busca utilizando padrão de sintaxe do _corpus search_, e posterior conversão do texto livre para o modo anterior<!--REVISAR: VER COM O LUIS SE É ISSO MESMO QUE UTILIZA - CORPUS SEARCH?-->

### Descrição Caso de uso 06 - Ferramenta de Pesquisa

**Atores primários**:

1. Usuário (geral). <!--REVISAR: verificar se qualquer pessoa pode realizar busca, sem a necessidade de ser cadastrado na plataforma-->

**Pré-requisitos:**

1. Os corpora devem estar com o status "completed" e serem públicos ("_public_").

**Fluxo normal:**

1. Acessar a página _home_ da plataforma Tycho Brahe através do link: <https://www.tycho.iel.unicamp.br/home>.
2. Na área de "Ferramentas", acessar "Search".
3. Escolher um dos corpora para realizar a pesquisa.
4. Escolher o tipo de busca que será realizada: **Pesquisa simples** ou **Pesquisa sintática**.

   1. **Pesquisa simples**:
      1. Selecionar o botão **Pesquisa simples**
      2. Preencher o campo com a expressão de busca utilizando partes de palavra, palavra completa, palavra + POS, múltiplas palavras, múltiplas palavras em sequência, múltiplas palavras com etiquetas POS, palavra + experssão regular ou múltiplas palavras com expressão regular.
      3. Clicar em "Executar pesquisa"
   2. **Pesquisa sintática** - escolher um dos modos da pesquisa Modo 1- Default: selecionar rótulos nas listas suspensas; Modo 2 - Escreva sua pesquisa: escrever a expressão de busca e converter):
      1. Modo 1 - Default
         1. Selecionar **Pesquisa sintática**.
         2. Selecionar quais padrões serão aplicados na busca pelos colocados:
            1. Nas listas suspensas, escolher entre: Palavra, Categoria sintática, Categoria vazia ou Etiqueta POS.
            2. A depender da seleção anterior, preencher se for "palavra"; ou iniciar o preenchimento e selecionar a partir da lista suspensa se for por categorias sintática, vazia ou Etiqueta POS.
            3. Selecionar qual a relação estabelecida entre os colocados objetos da busca: _dominates, exists hasSister, iDominates, inDominates, iPrecedes, inPrecedes, precedes_.
         3. É possível adicionar mais buscas ao clicar no ícone "+" e deletar padrão de busca ao clicar na "lixeira".
         4. Clicar em "Executar Pesquisa"
      2. Modo 2 - Escreva sua pesquisa. É posível abrir um campo livre para preenchimento para executar busca com padrão de sintaxe do _corpus search_: clicar em "escreva sua pesquisa".
         1. Preencher com o padão de busca (sintaxe _corpus search_).
         2. Clicar em "Converter texto" para converter busca para campos preenchidos na "Pesquisa sintática"<!--REVISAR: AVISAR AO LUIS QUE QUANDO PREENCHO NO CAMPO LIVRE E CONVERTO PARA A BUSCA E REALIZO ESTÁ DANDO ERRO-->

Para qualquer tipo de busca, é possível realizar algumas configurações:

1. Clicar no ícone de "configurações" no canto direito superior.
   1. Metadados <!--REVISAR: encontrei onde se preenche os metadados no admin, configurações (mas não entendi quais os tipos de dados são para serem preenchidos e não sei como isto impacta na hora da pesquisa) -->
   2. Documentos: selecionar um documento para limitar a busca a um documento específico (pode aumentar velocidade de resposta da requisição).
   3. Exportar: selecionar o formato para exportar os resultados da pesquisa.
   4. Consultas: verificar consultas salvas.
   5. Definições <!--REVISAR: VERIFICAR QUAIS SÃO AS DEFINIÇÕES POSSÍVEIS AQUI-->

### Diagrama do Caso de uso 06 - FERRAMENTA DE PESQUISA

![Caso de uso 06](../imagens/caso_ferramenta_pesquisa.png)
Figura x: Diagrama Caso de Uso 06 - Ferramenta de Pesquisa

### Tutorial:

**Objetivo:**
Este tutorial dem o objetivo de detalhar os procedimentos necessários para a realização de pesquisas nos corpora disponíveis na plataforma Tycho Brahe.

#### **Tutorial: Fluxo normal**

1. Acesse a página _home_ da plataforma Tycho Brahe através do link: <https://www.tycho.iel.unicamp.br/home>.
2. Na área de "Ferramentas", acesse a Ferramenta "Search".

![Ferramenta pesquisa](../imagens/busca_01.png)
Figura x: Ferramenta de Pesquisa

3. Escolha um dos corpora para realizar a busca.

![Seleção corpus para pesquisa](../imagens/busca_2.png)
Figura x: Selecionando corpus para realizar uma pesquisa. 4. Escolha o tipo de pesquisa que deseja realizar: **Pesquisa simples** ou **Pesquisa sintática**.

**Pesquisa simples**:

1. Selecione o botão **Pesquisa simples**
2. Preencha o campo com a expressão de busca utilizando partes de palavra, palavra completa, palavra + POS, múltiplas palavras (não necessariamente em sequência), múltiplas palavras em sequência, múltiplas palavras com etiquetas POS (não necessariamente em sequência), palavra + expressão regular ou múltiplas palavras com expressão regular.

| Tipo de consulta                                                    | Exemplo             |
| ------------------------------------------------------------------- | ------------------- |
| Parte de palavra                                                    | ejiwa               |
| Palavra inteira                                                     | "ejiwajegi"         |
| Palavra + etiqueta POS                                              | ejiwajegi/N         |
| Múltiplas palavras (não necessariamente em sequência)               | ica ejiwajegi       |
| Múltiplas palavras em sequência                                     | "ica ejiwajegi"     |
| Múltiplas palavras com etiquetas (não necessariamente em sequência) | ica/D ejiwajegi/N   |
| Múltiplas palavras em sequência com etiquetas                       | "ica/D ejiwajegi/D" |
| Palavra com expressão regular                                       | ica.\*ejiwajegi     |
| Múltiplas palavras com expressão regular                            |                     |

<!--Revisar com o Luiz sobre as expressões regulares, não funciona todos os tipos de buscas-->

3. Clique em "Executar pesquisa"

![Pesquisa simples](../imagens/busca_7.png)
Figura x: Relizando uma Pesquisa Simples.
A pesquisa realizada no exemplo na Figura x acima retorna o seguinte resultado no corpus de Teste.

![Resultado pesquisa](../imagens/busca_9.png)
Figura x: Resultado de uma busca simples.

**Pesquisa sintática** - escolha um dos modos da pesquisa Modo 1- Default: este modo disponibiliza listas suspensas com os tipos de tags/pesquisa pré-determinadas (Palavra, Categoria Sintática, Categoria Vazia, Etiqueta POS), uma lista suspensa com o tipo de relação entre os colocados (_dominates, exists hasSister_ etc); Modo 2 - Escreva sua pesquisa: é possível escrever a expressão de pesquisa e converter para o modo anterior antes de realizar a pesquisa):

**Modo 1 - Default**

1. Selecione **Pesquisa sintática**.
2. Selecione quais padrões serão aplicados na busca pelos colocados:
   1. Nas listas suspensa, escolher entre: Palavra, Categoria sintática, Categoria Vazia ou Etiqueta POS.
   2. A depender da seleção anterior: se selecionar "Palavra", preencha o campo com a palavra desejada a ser pesquisada; Se a pesquisa for por Categorias sintática, Categoria vazia ou Etiqueta POS, inicie o preenchimento da tag desejada e selecione a tag pertinente a partir da lista suspensa.
   3. Selecione qual a relação estabelecida entre os colocados objetos da pesquisa: _dominates, exists hasSister, iDominates, inDominates, iPrecedes, inPrecedes, precedes_.<!--REVISAR: INSERIR DEFINICÃO DE CADA UMA DESSAS PALAVRAS CHAVES COM FIGURAS?-->
3. É possível adicionar mais buscas ao clicar no ícone "+" e deletar padrão de busca ao clicar na "lixeira".
4. Clique em "Executar Pesquisa".

![Pesquisa sintática](../imagens/busca_8.png)
Figura x: Realizando uma Pesquisa Sintática

**Modo 2 - Escreva sua pesquisa**. É posível abrir um campo livre para preenchimento para executar busca com padrão de sintaxe do _corpus search_:

1. Clique em "escreva sua pesquisa".
2. Preencha o campo com o padão de pesquisa desejado (seguindo a sintaxe do _corpus search_).
3. Clique em "Converter texto" para converter busca para campos preenchidos na "Pesquisa sintática" default<!--REVISAR: AVISAR AO LUIS QUE QUANDO PREENCHO NO CAMPO LIVRE E CONVERTO PARA A BUSCA E REALIZO ESTÁ DANDO ERRO-->

Para qualquer tipo de busca, é possível realizar algumas configurações:

1. Clique no ícone de "configurações" no canto direito superior.
   1. Metadados <!--REVISAR: encontrei onde se preenche os metadados no admin, configurações (mas não entendi quais os tipos de dados são para serem preenchidos e não sei como isto impacta na hora da pesquisa) -->
   2. Documentos: selecione um documento para limitar a pesquisa a documentos específicos (pode aumentar velocidade de resposta da requisição).
   3. Exportar: selecione o formato para exportar os resultados da pesquisa.
   4. Consultas: verifique consultas salvas.
   5. Definições <!--REVISAR: VERIFICAR QUAIS SÃO AS DEFINIÇÕES POSSÍVEIS AQUI-->
   <!--REVISAR: aguardar reunião com Luiz para entender melhor esta parte de configurações-->

---

## Caso de uso 07 - Visualizador de corpora

O visualizador de corpora da plataforma Tycho Brahe oferece uma interface acessível e prática para a exploração dos corpora disponíveis. Essa funcionalidade está aberta a todos os usuários, incluindo aqueles que não possuem cadastro na plataforma, promovendo a democratização do acesso aos dados linguísticos desenvolvidos no projeto.

Com o visualizador, é possível:

- Examinar anotações realizadas nos corpora, como etiquetas (POS) e anotações sintáticas.
- Visualizar e exportar representações gráficas, como árvores sintáticas, diretamente a partir da ferramenta, permitindo maior flexibilidade para estudos e apresentações.
- Acessar áudios disponíveis (quando se aplicar).
- Visualizar traduções das sentenças analizadas (quando se aplicar).
  Essas funcionalidades são ideais para pesquisadores, estudantes e interessados em linguística que desejam explorar os corpora de forma detalhada e aproveitar os recursos sem barreiras iniciais de acesso.

### Descrição Caso de uso 07 - Visualizador de corpora

**Atores primários**:

1.Usuários em geral

**Pré-requisitos:**

1.Sem pré-requisitos

**Fluxo normal:**

1. Acessar a página inicial da plataforma Tycho Brahe no endereço <https://www.tycho.iel.unicamp.br/home>.
2. Clicar no "Vizualizador" na área de "Ferramentas".
3. Selecionar um dos corpora disponíveis na lista.
   1. São apresentadas informações como número de documentos e número de palavras nos corpora.
4. Navegar pela lista de documentos. Selecionar um documento.
5. Selecionar a sentença desejada.
   1. São apresentadas informações como etiquetas POS, traduções, áudios disponíveis e árvore/estrutura sintática.

### Diagrama do Caso de uso 07 - Visualizador de corpora

![diagrama caso visualizador](../imagens/caso_visualizador.png)
Figura x: Diagrama caso de uso Visualizador de corpora

### Tutorial:

**Objetivo:**
Este tutorial tem como objetivo guiar os usuários no uso do visualizador de corpora da plataforma Tycho Brahe. Ao final, o usuário será capaz de:

- Acessar o visualizador, mesmo sem cadastro na plataforma.
- Navegar pelas anotações disponíveis nos corpora.
- Visualizar e exportar árvores sintáticas desejadas para uso externo.

#### **Tutorial: Fluxo normal**

1. Acesse a página inicial da plataforma Tycho Brahe no endereço <https://www.tycho.iel.unicamp.br/home>.
2. Clique no "Vizualizador" na área de "Ferramentas".

![Acessando visualizador](../imagens/vizualizador/vizualizador_1.png)
Figura x: Acessando o Visulizador de corpus.

3. Selecione um dos corpora disponíveis na lista.
   1. São apresentadas informações como número de documentos e número de palavras nos corpora.

![Seleção de corpora para visualização](../imagens/vizualizador/visualizador_2.png)

4. Navegue pela lista de documentose e selecione um documento. Há alguma ícones que disponibilizam algumas funcionalidades:

- Filtragem de documentos por palavra ou status:

![Filtragem de docs](../imagens/vizualizador/visualizador_3.png)
Figura x: Filtragem de documentos no Visualizador

- Documentos dispostos em forma de grade ou lista:

![Docs em grade](../imagens/vizualizador/visualizador_4.png)
Figura x: Disposição de documentos em grade.

![Docs em lista](../imagens/vizualizador/visualizador_5.png)
Figura x: Disposição de documentos em lista.

- Botão de compartilhamento de link do corpus:

![Link corpus](../imagens/vizualizador/visualizador_6.png)
Figura x: Compartilhamento do link do corpus.

5. Após a seleção do documento desejado, as sentenças que o corpus contém são apresentadas. Selecione a sentença desejada.
   - Na tela que apresenta as sentenças, são apresentadas: tradução, botão para tocar o áudio original, botão para realizar download do áudio, língua de tradução etc.:

![Apresentação de sentenças](../imagens/vizualizador/visualizador_7.png)
Figura x: Sentenças disponíveis no documento.

- Ao ser selecionada uma sentença, são apresentadas informações como etiquetas POS, traduções, áudios disponíveis e árvore/estrutura sintática.

![Sentença - camadas etiquetas](../imagens/vizualizador/visualizador_8.png)
Figura x: Anotações realizadas na sentença selecionada.

---

## Caso de uso 08 - Synviewer

A plataforma Tycho Brahe oferece uma interface para a geração e visualização de árvores sintáticas, o "Synviewer". Dentre as funcionalidades, destacam-se a geração de árvores sintáticas com base em parsers baseados em regra desenvolvidos no âmbito do projeto, bem como árvores sintáticas baseadas no banco de Dependências Universais (_Universal Dependencies - UD_). Esta ferramenta facilita o uso dos parser desenvolvidos dentro do projeto, facilitando a visualização, exportação e apresentação dos dados.

### Descrição Caso de uso 08 - Synviewer

**Atores primários**:

1. Usuários em geral (inclusive sem cadastro prévio na plataforma)

**Pré-requisitos:**

1. Sem pré-requisitos

**Fluxo normal:**

1. Acessar a página inicial da plataforma Tycho Brahe no endereço <https://www.tycho.iel.unicamp.br/home>.
2. Clicar no "Synviewer" na área de "Ferramentas".

Há duas funcionalidades principais no "Synviewer":

- **Parsers Tycho**: parsers desenvolvidos no âmbito do projeto.

  - **Executar o parser**:
    1. Selecionar a aba "Executar o parser".
    2. Inserir a sentença desejada.
    3. Selecionar o modelo (parser) desejado.
    4. Clicar em "Executar".
  - **Exibir Árvore Sintática**:
    1. Selecionar a aba "Exibir Árvore Sintática".
    2. Inserir expressão em notação de parênteses ou colchetes para geração da árvore.
    3. Converter para notação em colchetes ou parênteses e clicar em "Executar" para gerar a árvore
  - **Exibir Formato Tycho**:
    1. Selecionar a aba "Exibir Formato Tycho".
    2. Inserir os dados.
    3. Clicar em "Executar" <!--REVISAR: ESTA FUNCIONALIDADE NÃO APRESENTA COMPORTAMENTO...TALVEZ TENHA TESTADO A ENTRADA ERRADA-->

- **Dependências Universais**: parsers do banco de dados de Dependências Universais.

  1. Inserir a sentença desejada ou inserir a expressão no modelo CoNLL-U.
  2. Selecionar o modelo (parser) desejado.
  3. Clicar em "Executar".<br><br>

  O usuário pode visualizar e exportar árvores no formato CoNLL-U ou Dependências Universais.<br>
  Nota: se o usuário preferir inserir a sentença e realizar o parser, o sistema retorna tanto as árvores quanto a expressão em notação CoNLL-U. É possível também inserir a expressão em CoNLL-U para geração das árvores diretamente.

### Diagrama do Caso de uso 08- Synviewer

![caso synviewer diagrama](../imagens/synviewer/caso_synviewer_diagram.png)
Figura x: Diagrama de caso de uso Synviewer

### Tutorial:

**Objetivo:**

#### **Tutorial: Fluxo normal**

1. Acesse a página inicial da plataforma Tycho Brahe no endereço <https://www.tycho.iel.unicamp.br/home>.

![Acesso Synviewer](../imagens/synviewer/syn_1.png)
Figura x: Acessando página inicial

2. Clique no "Synviewer" na área de "Ferramentas" para acessar a funcionalidade.
   Figura x: Acessando o "Synviewer"

![Geral synviewer](../imagens/synviewer/syn_2.png)

Há duas funcionalidades principais no "Synviewer":

**Parsers Tycho**: seleciona esta aba com os parsers desenvolvidos no âmbito do projeto.

- **Executar o parser**:
  1. Selecione a aba "Executar o parser".
  2. Insira a sentença desejada.
  3. Selecione o modelo (parser) desejado e clique em "Executar".

![Parsers Tycho](../imagens/synviewer/syn_3.png)

A execução do parser resulta na árvore, como apresentada na Figura a seguir:

![Execução parser de regra](../imagens/synviewer/syn_4.png)

- **Exibir Árvore Sintática**:
  1. Selecione a aba "Exibir Árvore Sintática".
  2. Insira expressão em notação de parênteses ou colchetes para geração da árvore.
  3. Converta para notação em colchetes ou parênteses (se aplicar) e clicar em "Executar" para gerar a árvore. É possível visualizar a árvore em tela cheia e exportar como imagem.

![Exibir Árvore sintática](../imagens/synviewer/syn_5.png)

- **Exibir Formato Tycho**:
  1. Selecionar a aba "Exibir Formato Tycho".
  2. Inserir os dados.
  3. Clicar em "Executar" <!--REVISAR: ESTA FUNCIONALIDADE NÃO APRESENTA COMPORTAMENTO...TALVEZ TENHA TESTADO A ENTRADA ERRADA-->

**Dependências Universais**: parsers do banco de dados de Dependências Universais.

1. Insira a sentença desejada.
2. Selecione o modelo (parser) desejado.
3. Clique em "Executar".

![Dep universais](../imagens/synviewer/syn_6.png)

O usuário pode visualizar e exportar árvores no formato CoNLL-U ou Dependências Universais como imagem.<br>
Nota: se o usuário preferir inserir a sentença e realizar o parser, o sistema retorna tanto as árvores quanto a expressão em notação CoNLL-U. É possível também inserir a expressão em CoNLL-U para geração das árvores diretamente: insira a expressão e clique em Exibir, para gerar as árvores.

![Exibir conllu](../imagens/synviewer/syn_7.png)

<!--A FAZER-->

## Caso de uso 09 - Parser <!--Criação, edição e gerenciamento das regras dos parsers-->

[INTRODUÇÃO]

### Descrição Caso de uso 09

**Atores primários**:
a

1.

**Pré-requisitos:**

1.

**Fluxo normal:**

1.  **Fluxo alternativo:**

**A1**

1.  **A2**

1.

### Diagrama do Caso de uso 09 - Parser

<figure>
    <img src=""
         alt="">
    <figcaption>Figura X: CAPTION</figcaption>
</figure>

### Tutorial:

**Objetivo:**

#### **Tutorial: Fluxo normal**

1.

#### \*\*Tutorial: Fluxo Alternativo

### Tutorial: Guia do Usuário Final (SE HOUVER)

**Objetivo:**

#### **Tutorial: Fluxo normal **

1.

#### **Tutorial: Fluxo alternativo**

1.

---

## Caso de uso 10 - IO (Importação e Exportação)

[INTRODUÇÃO]

### Descrição Caso de uso 10 - IO (Importação e Exportação)

**Atores primários**:

1.

**Pré-requisitos:**

1.

**Fluxo normal:**

1.  **Fluxo alternativo:**

**A1**

1.  **A2**

1.

### Diagrama do Caso de uso 10 - IO (Importação e Exportação)

<figure>
    <img src=""
         alt="">
    <figcaption>Figura X: CAPTION</figcaption>
</figure>

### Tutorial:

**Objetivo:**

#### **Tutorial: Fluxo normal**

1.

#### \*\*Tutorial: Fluxo Alternativo

### Tutorial: Guia do Usuário Final (SE HOUVER)

**Objetivo:**

#### **Tutorial: Fluxo normal **

1.

#### **Tutorial: Fluxo alternativo**

1.  #########################

<!--###########rascunho  ESTRUTURA BÁSICA PARA REUTILIZAÇÃO




## Caso de uso 0X - NOME CASO DE USO

[INTRODUÇÃO]

### Descrição Caso de uso X

**Atores primários**:

1.

**Pré-requisitos:**

1.

**Fluxo normal:**

1.  **Fluxo alternativo:**

**A1**

1.  **A2**

1.

### Diagrama do Caso de uso 0X - NOME CASO

<figure>
    <img src=""
         alt="">
    <figcaption>Figura X: CAPTION</figcaption>
</figure>

### Tutorial:

**Objetivo:**

#### **Tutorial: Fluxo normal**

1.

#### \*\*Tutorial: Fluxo Alternativo

### Tutorial: Guia do Usuário Final (SE HOUVER)

**Objetivo:**

#### **Tutorial: Fluxo normal **

1.

#### **Tutorial: Fluxo alternativo**

1.





    DÚVIDAS A TIRAR COM O LUIZ

COMO DELETAR UM CORPUS? AINDA NÃO IMPLEMENTADO

PERGUNTAR PRO LUIZ, DE MANEIRA GERAL, SOBRE AS CREDENCIAIS NECESSÁRIAS PARA REALIZAR ALGUMAS TAREFAS DE GESTÃO DOS CORPORA
-->
