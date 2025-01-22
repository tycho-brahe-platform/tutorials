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
