# Cadastro de Novos Usuários - Guia do Administrador

Índice

- [Cadastro de Novos Usuários - Guia do Administrador](#cadastro-de-novos-usuários---guia-do-administrador)
  - [Tutorial](#tutorial)
    - [**Fluxo normal**](#fluxo-normal)
      - [**Acesso ao Centro Administrativo**](#acesso-ao-centro-administrativo)
        - [**Selecionar o Corpus**](#selecionar-o-corpus)
        - [**Acessar "Controle de Acesso**](#acessar-controle-de-acesso)
        - [**Criar Convite de acesso**](#criar-convite-de-acesso)
    - [**Fluxo Alternativo 1 - Usuário já presente na Base de Dados, vinculado a outro corpus**](#fluxo-alternativo-1---usuário-já-presente-na-base-de-dados-vinculado-a-outro-corpus)

---

Este tutorial detalha o processo para o Administrador da plataforma realizar o cadastro de novos usuários em corpora já criados, configurando as permissões necessárias e/ou enviando os convites de acesso. Em um fluxo normal, a coordenação ou professor entra em contato com o Admin previamente avisando a necessidade de cadastrar ou vincular um novo usuário a um determinado corpus (seja via convite para um novo cadastro na plataforma ou associação de um usuário já cadastrado a um novo corpus)

<!--REVISAR: ver com o Luis se vai haver modificação no processo de solicitação de cadastro-->

## Tutorial

### **Fluxo normal**

Antes de iniciar o processo de cadastro de um usuário, certifique-se de que o corpus ao qual o usuário será associado já tenha sido criado.

#### **Acesso ao Centro Administrativo**

Para acessar o sistema de Gerenciamento dos corpora e realizar o registro de novos usuários, é necessário acessar o Centro Adminstrativo de uma das maneiras descritas no [tutorial: Acessando o Centro administrativo](./accessing-admin-center.md).

Todos os corpora disponíveis para o Administrador e Usuário com permissão de admin aparecem na sua página inicial de admin, listados com os campos: Nome, Tipo, Status, No. de documentos, No. de palavras, No. de usuários. Verifique se o corpus que deseja gerenciar está disponível (note que são exibidos 10 resultados por página, e que pode haver várias páginas de corpora - então navegue em todas as páginas para verificar a presença do corpus alvo).

!["t"](./images/rnu/tycho-admin-50.png)

Nesta tela, o administrador consegue realizar algumas tarefas de gestão, como:

**Restaurar um corpus**:

1. Clique sobre o botão "Restaurar corpus".
2. Arraste e solte um arquivo ou clique e selecione para enviar um arquivo e confirme.

![](./images/rnu/tycho-admin-51.png)

**Gerenciar usuários**: verificar informações de usuários na plataforma.

1. Clique sobre o botão “Manage users”: serão apresentados todos os usuários.
2. Clique sobre um usuário para ver suas informações.
3. Informações do usuário selecionado: Nome, e-mail, UID, Corpora, Parsers e Léxicos aos quais o usuário é associado.
    ![](./images/rnu/tycho-admin-52.png)

**Filtrar corpora**: busca corpora, filtrando com base nas informaçõs fornecidas:

1. Clique sobre o botão "Filtro".
2. Preencha:

    1. **Contendo texto no nome**: retorna os documentos que contenham as palavras informadas no título do documento.
    2. **Corpus Público**: ao clicar, filtrar corpora públicos ou privados.
    3. **Limpar**: limpa o filtro e refaz a busca.
    4. **Buscar**: executa a busca de acordo com os filtros preenchidos.

    ![](./images/rnu/tycho-admin-54.png)

Uma vez na área de Centro Adminstrativo, o admin do corpus consegue seguir com os passos necessários para registrar novos usuários.

##### **Selecionar o Corpus**

1. Na interface de Administrador, selecione o corpus ao qual o novo usuário será associado. A Figura a seguir apresenta o catálogo de corpora disponíveis para acesso. Ao clicar em um dos corpora, o usuário é redirecionado ao corpus específico, como apresentado na Figura, como apresentado no topo da página “Corpus: Demonstration”.<br>
    !["Acessanco corpus pelo Administrador"](./images/rnu/select-demo-corpus.png)

##### **Acessar "Controle de Acesso**

Na primeira tela de administração do corpus, são apresentadas informações gerais, como nome, um atalho URL, os parsers etc. No painel do corpus, clique na aba "Controle de Acesso" para gerenciar as permissões de acesso.

![](./images/rnu/tycho-admin-55.png)

Ao acessar o “Controle de Acesso”, a plataforma apresenta uma página com os atuais usuários com permissões no corpus selecionado, como mostra a Figura a seguir. Com botão “Users” selecionado, é apresentado o usuário com os seguintes campos - “Name”, “status”, “Role”.

!["Área de controle de acesso"](./images/rnu/access-control-accessed.png)

##### **Criar Convite de acesso**

Na aba "Controle de Acesso", clique no botão "Invites" e depois em “ + Add new invite”. Uma nova janela se abre para que o admin possa realizar as configurações da permissão:

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

!["Cria a configura convite"](./images/rnu/invites-2.png)

Após a geração do convite, o admin consegue enviar uma notificação automática com o convite para o e-mail cadastrado, copiar o ID do convite. Além disso, é possível reacessar o convite para verificação das informações, reenvio do e-mail etc.

![](./images/rnu/tycho-admin-56.png)

O usuário recém cadastrado deve receber um email automático neste formato e deve clicar em "Join now" para ser redirecionado à página de adesão ao corpus e inserir o código de acesso constante no email.

![](./images/rnu/invites-4.png)

### **Fluxo Alternativo 1 - Usuário já presente na Base de Dados, vinculado a outro corpus**

Se o usuário já estiver cadastrado em outro corpus, ou seja, já tiver o seu perfil disponível para o Admin na plataforma, siga estas etapas:

1. Acesse o Centro Adminstrativo de uma das maneiras descritas no [tutorial: Acessando o Centro administrativo](./accessing-admin-center.md). No painel de "Controle de Acesso", com o botão “Users” selecionado, clique em "+ Add New".
2. **Selecionar o e-mail do usuário**: Inicie o preenchimento e escolha o e-mail do usuário na lista suspensa (super-usuários e e-mails já cadastrados no corpus não aparecerão como opção).
3. **Configurar Permissões e Confirmar**: Selecione as permissões de "Role" (Adminstrator, Editor, Visitor) e "Status" (Active, Inactive).

![](./images/rnu/register-user-in-base.png)

---
