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
  - [Caso de uso 01 - Cadastro de novos usuários nos corpora da plataforma e controle de acesso](#caso-de-uso-01---cadastro-de-novos-usuários-nos-corpora-da-plataforma-e-controle-de-acesso)
    - [Caso 01.1 Cadastro de Novos Usuários - Guia do Administrador](#caso-011-cadastro-de-novos-usuários---guia-do-administrador)
      - [**Fluxo normal**](#fluxo-normal)
      - [**Fluxo Alternativo 1 - Usuário já presente na Base de Dados, vinculado a outro corpus**](#fluxo-alternativo-1---usuário-já-presente-na-base-de-dados-vinculado-a-outro-corpus)
    - [Caso 01.2 Controle de acesso - Guia do Administrador](#caso-012-controle-de-acesso---guia-do-administrador)
      - [**Fluxo normal**](#fluxo-normal-1)

---

## Caso de uso 01 - Cadastro de novos usuários nos corpora da plataforma e controle de acesso

O processo de cadastro na Plataforma Tycho Brahe é um procedimento essencial para garantir o acesso controlado e seguro aos corpora. Este processo envolve tanto administradores quanto usuários finais, cada um com papéis específicos no fluxo de cadastro.

Para os administradores, o processo inclui a criação de convites, configuração de permissões e envio de links de "onboarding" para novos usuários. Já para os usuários finais, o processo consiste em receber o convite, acessar o link de "onboarding" e inserir o código de acesso fornecido.

O sistema oferece flexibilidade para lidar com diferentes cenários, como usuários não presentes na base de dados ou já cadastrados em outros corpora. Além disso, permite a configuração de diferentes níveis de permissão (edição ou admin) e status de usuário (ativo ou inativo).

Nos tópicos a seguir, será detalhado o caso de uso para o cadastro de novos usuários, bem como tutoriais passo a passo tanto para administradores quanto para usuários finais, garantindo uma compreensão completa do processo de cadastro na Plataforma Tycho Brahe.

### Caso 01.1 Cadastro de Novos Usuários - Guia do Administrador

**Objetivo:** Este tutorial detalha o processo para o Administrador da plataforma realizar o cadastro de novos usuários em corpora já criados, configurando as permissões necessárias e/ou enviando os convites de acesso. Em um fluxo normal, a coordenação ou professor entra em contato com o Admin previamente avisando a necessidade de cadastrar ou vincular um novo usuário a um determinado corpus (seja via convite para um novo cadastro na plataforma ou associação de um usuário já cadastrado a um novo corpus)

**Atores primários**:

1. Usuário (com permissão admin no corpus alvo)
2. Administrador da plataforma (Super-usuário com acesso a todos os corpora);

Note-se a distinção entre Administrador e Usuário com permissão de administrador (admin) em corpora específicos. O Administrador da plataforma tem permissões mais abrangentes de gestão geral na na plataforma, tendo acesso mais irrestrito aos corpora. Do contrário, o Usuário com permissão de admin em um determinado corpus não goza dos mesmos privilégios, tendo permissão de gestão apenas em corpora específicos, aos quais é associado.

**Pré-requisitos:**

1. Para o cadastramento de um usuário em um corpus, é necessário que o corpus tenha sido previamente criado (por um usuário com permissões de administrador ou Adminstrador), ou seja, a permissão de acesso tem de ser necessariamente associada a um corpus já cadastrado no sistema;
2. Configuração de permissões pelo Administrador: necessita permissão de Administrador e acesso ao link de Administrador <!--(VERIFICAR SE POSSO INSERIR link admin NA DOCUMENTAÇÃO)-->;
3. Usuário comum precisa de permissão de admin no corpus específico;
4. Solicitação de cadastro pelo usuário: nenhum (funcional); Solicitações de cadastro passam pela coordenação do projeto.

#### **Fluxo normal**

Antes de iniciar o processo de cadastro de um usuário, certifique-se de que o corpus ao qual o usuário será associado já tenha sido criado.

**Acesso ao Sistema**: Há duas maneira de acessar o sistema de gerenciamento dos corpora.

   1. No caso de acesso por um Administrador sem associação a nenhum corpus na plataforma: faça login na plataforma com sua conta de Administrador (_login_ com a conta Google), através do link “/admin”: <https://www.tycho.iel.unicamp.br/admin>. Este link redireciona o Administrador à janela de login com a conta Google ou com as credenciais (email e senha) cadastradas.
   2. No caso de acesso por um Usuário com permissão de admin nos corpora alvos: seguir tutorial de Caso de Uso 00 - para acesso à area de perfil do usuário.

**Verificar Corpora**:

**Administrador**: todos os corpora disponíveis para o Administrador aparecem na sua página inicial, através do link <https://www.tycho.iel.unicamp.br/admin> (e devido login), listados com os campos: Nome, Type, Status No. of documents, No. of words, No. of users. Verifique se o corpus que deseja gerenciar está disponível (note que são exibidos 10 resultados por página, e que pode haver várias páginas de corpora - então navegue em todas as páginas para verificar a presença do corpus alvo).

!["t"](../imagens/admin/tycho_admin_50.png)

Nesta tela, o administrador consegue realizar algumas tarefas de gestão, como: 

**Restaurar um corpus**:

   1. Clique sobre o botão “Restore corpus”.
   2. Arraste e solte um arquivo ou clique e selecione para enviar um arquivo e confirme.

![](../imagens/admin/tycho_admin_51.png)

**Gerenciar usuários**: verificar informações de usuários na plataforma.

   1. Clique sobre o botão “Manage users”: serão apresentados todos os usuários.
   2. . Clique sobre um usuário para ver suas informações.
   3. Informações do usuário selecionado: Nome, e-mail, UID, Corpora aos quais o usuário é associado.
   ![](../imagens/admin/tycho_admin_52.png)

**Filtrar corpora**: busca corpora, filtrando com base nas informaçõs fornecidas:

   1. Clique sobre o botão “Filter”.
   2. Preencha:
      1. **Containing text on name**: retorna os documentos que contenham as palavras informadas no título do documento.
      2. **Public corpus**: ao clicar,  filtrar corpora públicos ou privados.
      3. **Clear**: limpa o filtro e refaz a busca.
      4. **Search**: executa a busca de acordo com os filtros preenchidos.

      ![](../imagens/admin/tycho_admin_54.png)

**Usuário com permissão de admin**: O Usuário admin tem acesso aos corpora aos quais está vínculado após o acesso pela "Área reservada" e o seu login, como no Caso de uso 00 -Tutorial:fluxo normal [2], e acesso à área de gerenciamento do corpus através do botão "Admin" na área "Meus corpora" (em Caso de uso 00 - Tutorial: fluxo normal[4]), como apresentado na Figura a seguir:<br>
      !["Acesso aos corpora por Usuário admin"](../imagens/perfil_plataforma.png)
      Tela inicial perfil - Área reservada<br><br>

Previamente, o usuário já deve ter realizado contato com a coordenação do projeto solicitando sua associação a determinado corpus. A coordenação então entra em contato com o administrador solicitando associação/cadastro a um determinado corpus. Veja a Figura abaixo:

**Selecionar o Corpus**:

   1. Na interface de Administrador, selecione o corpus ao qual o novo usuário será associado. A Figura a seguir apresenta o catálogo de corpora disponíveis para acesso. Ao clicar em um dos corpora, o usuário é redirecionado ao corpus específico, como apresentado na Figura, como apresentado no topo da página “Corpus: Demonstration”.<br>
      !["Acessanco corpus pelo Administrador"](../imagens/selecionando_corpus_demo.png)
      Corpus Demonstration selecionado<br><br>
   2. No caso do Usuário com permissão admin em determinados corpora, há duas maneiras de acessar a área de gerenciamento: na área "Meus corpora" na página incial do perfil, em "Acesso rápido", clique em "Admin"; ou na área "Minhas Ferramentas", selecione "Admin":<br><br>!["Acesso à área de administração corpora"](../imagens/acesso_rapido_admin.png)
      Acesso à área de administração dos corpra.<br><br>

**Acessar "Access Control**: Na primeira tela de administração do corpus, são apresentadas informações gerais, como nome, um atalho URL, os parsers etc. No painel do corpus, clique na aba "Access Control" para gerenciar as permissões de acesso.

   ![](../imagens/admin/tycho_admin_55.png)
  
Ao acessar o “Access Control”, a plataforma apresenta uma página com os atuais usuários com permissões no corpus selecionado, como mostra a Figura a seguir. Com botão “Users” selecionado, é apresentado o usuário com os seguintes campos - “Name”, “status”, “Role”.

!["Área de controle de acesso"](../imagens/access_control_acessado.png)

**Criar Convite de acesso**: Na aba "Access Control", clique no botão "Invites" e depois em “ + Add new”. Uma nova janela se abre para que o admin possa realizar as configurações da permissão:

   1. **Inserir título:** Escolha um título para o convite no campo “Title”
   2. **Definir Quantidade de Convites**: Escolha se o convite será para um único usuário ou para múltiplos usuários (o contador de convites disponíveis será atualizado conforme os usuários se registrarem).
   3. **Definir o tipo de permissão:** Selecione o tipo de permissão “Role” que o usuário terá:
      - **Edição**: O usuário poderá editar o corpus.
      - **Admin**: O usuário terá permissões de administrador no corpus.
   4. **Email**: Preencha o email do usuário a ser adicionado ao corpus.
   5. **Status do Usuário**: Selecione o status do usuário:
      - **Active**: O usuário terá acesso ativo ao corpus.
      - **Inactive**: O usuário estará registrado, mas sem acesso ativo.
   6. Após configurar as permissões clicar em "Confirmar".

   !["Cria a configura convite"](../imagens/invites_2.png)

Após a geração do convite, o admin consegue enviar uma notificação automática com o convite para o e-mail cadastrado, copiar o ID do convite. Além disso, é possível reacessar o convite para verificação das informações, reenvio do e-mail etc. 

   ![](../imagens/admin/tycho_admin_56.png)

O usuário recém cadastrado deve receber um email automático neste formato e deve clicar em "Join now" para ser redirecionado à página de adesão ao corpus e inserir o código de acesso constante no email.
   ![](../imagens/invites_4.png)

#### **Fluxo Alternativo 1 - Usuário já presente na Base de Dados, vinculado a outro corpus**

Se o usuário já estiver cadastrado em outro corpus, siga estas etapas:

1. **Adicionar novo usuário**: Acesse o link "admin" <https://www.tycho.iel.unicamp.br/admin> e selecione um corpus, ou por meio da "Área reservada"(selecione o "Acesso rápido"-"Admin"). No painel de "Access Control", com o botão “Users” selecionado, clique em "+ Add New". (Ver Figura acima)
2. **Selecionar o e-mail do usuário**: Escolha o e-mail do usuário na lista (super-usuários e e-mails já cadastrados no corpus não aparecerão como opção). (Ver Figura acima)
3. **Configurar Permissões e Confirmar**: Siga o Passo 6 e 7 do fluxo normal para configurar as permissões e confirme o cadastro.

<!--### Como se cadastrar em um corpus - Guia do usuário final

**Objetivo:** Este tutorial detalha o processo para os usuários se cadastrarem em um corpus da plataforma, utilizando o link de "/onboarding" e código de acesso fornecido pelo administrador, ou apenas o link "/onboarding" .

#### **Fluxo normal (usuários não cadastrados previamente em nenhum dos corpora)**

1. **Receber Link onboarding e código de acesso (convite)**: Aguarde o e-mail ou mensagem com o link de "onboarding" e o código de acesso enviados pelo administrador da plataforma.
2. **Acessar o link**: No e-mail ou mensagem recebida, copie o link de "/onboarding" fornecido pelo administrador, insira no navegador.
3. **Acessar Página de perfil**: Você será redirecionado para uma página de perfil na plataforma. Como é o primeiro acesso, não haverá corpora vinculados na área “Meus corpora”
4. **Código de Acesso**: Na página de perfil, clique no botão "Eu possuo um código de acesso".
5. **Preencher o Código**: Insira o código de acesso fornecido no campo correspondente.
6. **Confirmar Cadastro**: Após preencher o código, clique em "Confirmar".
   !["Preenchendo código de acesso"](../imagens/preencher_codigo_acesso.png)
   Tela de inserção de código de acesso. <br><br>

7. **Acesso ao Sistema**: O usuário deve tentar realizar o _sign in_ para certificar-se de que o cadastro foi realizado com sucesso. Se o _sign in_ for bem-sucedido, o usuário poderá acessar o corpus com as permissões definidas pelo seu administrador.

#### **Fluxo alternativo**

1. **Receber Link onboarding**: Aguarde o e-mail ou mensagem com o link de "onboarding" enviado pelo administrador da plataforma.
2. **Acessar o link**: No e-mail ou mensagem recebida, copie o link de "/onboarding" fornecido pelo administrador, insira no navegador.
3. **Acessar Página de perfil**: Você será redirecionado para uma página de perfil na plataforma. Como é o primeiro acesso, não haverá corpora vinculados na área “Meus corpora”. Esse acesso salva o seu e-mail na base de dados permitindo que o Admin consiga vincular o seu perfil ao corpus desejado.
4. **Acesso ao Sistema**: O usuário deve tentar realizar o _sign in_ para certificar-se de que o cadastro foi realizado com sucesso. Se o _sign in_ for bem-sucedido, o usuário poderá acessar o corpus com as permissões definidas pelo administrador.-->

### Caso 01.2 Controle de acesso - Guia do Administrador 

Além do cadastro de novos usuários, a plataforma também oferece funcionalidades de controle de acesso de usuários já cadastrados. 

#### **Fluxo normal**

1. Com a aba "Access control" selecionada, são apresentados os usuários que estão atualmente associados ao corpus e os convites gerados para associação ao corpus.
   
![](../imagens/admin/tycho_admin_22.png)

2. Para realizar alterações de controle de acesso do usuário, selecione um usuário, clicando sobre o perfil. Uma caixa com as informações do perfil do usuário se abre, com três colunas: 
**Profile**: foto, nome e email associado; Botão para revogar acesso do usuário: para revogar, clique sobre o botão "Revoke access" (o acesso do usuário é revogado imediatamente).

   **Access**: nesta coluna, o adminstrador consegue configurar o "Role"(papel) do usuário; o status; Display in Viwer:

   1. Role
      1. Clique sobre o "papel"
      2. Selecione entre: Admnistrator, Editor e Visitor.
      3. Clique em "aplicar" para salvar a seleção.
  
   2. Status
      1. Clique sobre o Status.
      2. Selecione entre Active e Inactive.
      3. Clique em "aplicar" para salvar a seleção.

   3. Display in Viwer
      1. Alterne para apresentar ou não o perfil do usuário na página do corpus, no viewer e na página principal.

   **Other Corpora**: apresenta os outros corpora aos quais o usuário é associado.

![](../imagens/admin/tycho_admin_23.png)

---
