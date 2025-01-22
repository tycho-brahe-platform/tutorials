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
  - [Caso de uso 02 - Solicitar cadastro](#caso-de-uso-02---solicitar-cadastro)
    - [Descrição Caso de uso 02](#descrição-caso-de-uso-02)
    - [Diagramas do Caso de uso 02 - Solicitar cadastro](#diagramas-do-caso-de-uso-02---solicitar-cadastro)
    - [Tutorial: Solicitar cadastro na plataforma](#tutorial-solicitar-cadastro-na-plataforma)
      - [**Tutorial: Fluxo normal**](#tutorial-fluxo-normal)
  - [Caso de uso 03 - Criação, configuração e edição dos corpora](#caso-de-uso-03---criação-configuração-e-edição-dos-corpora)
    - [Descrição Subcaso de uso 03.1 - Criação de corpora](#descrição-subcaso-de-uso-031---criação-de-corpora)
    - [Diagrama do Subcaso de uso 03.1 - Criação de corpora](#diagrama-do-subcaso-de-uso-031---criação-de-corpora)
    - [Tutorial: Criação de corpora](#tutorial-criação-de-corpora)
      - [**Tutorial: Fluxo normal**](#tutorial-fluxo-normal-1)
    - [Descrição Subcaso de uso 03.2 - Configuração dos corpora](#descrição-subcaso-de-uso-032---configuração-dos-corpora)
    - [Diagrama do Caso de uso 03.2 - Configuração de corpora](#diagrama-do-caso-de-uso-032---configuração-de-corpora)
    - [Tutorial: Configuração de corpora](#tutorial-configuração-de-corpora)
      - [**Tutorial: Fluxo normal**](#tutorial-fluxo-normal-2)
  - [Caso de uso 04 - Ferramenta **Use eDictor**](#caso-de-uso-04---ferramenta-use-edictor)
    - [Descrição Caso de uso 04](#descrição-caso-de-uso-04)
    - [Diagrama do Caso de uso 04 - **Use eDictor**](#diagrama-do-caso-de-uso-04---use-edictor)
    - [Tutorial:](#tutorial)
      - [**Tutorial: Fluxo normal**](#tutorial-fluxo-normal-3)
  - [Caso de uso 05 - Ferramenta **eDictor Translations**](#caso-de-uso-05---ferramenta-edictor-translations)
    - [Descrição Subcaso de uso 05.01 - Edição de corpora (Inserir, editar e remover sentenças) ](#descrição-subcaso-de-uso-0501---edição-de-corpora-inserir-editar-e-remover-sentenças-)
    - [Diagrama do Subcaso de uso 05.01 - **Use eDictor Translations: Edição de corpora**](#diagrama-do-subcaso-de-uso-0501---use-edictor-translations-edição-de-corpora)
    - [Tutorial:](#tutorial-1)
      - [**Tutorial: Fluxo normal**](#tutorial-fluxo-normal-4)
      - [**Tutorial: Fluxo alternativo:**](#tutorial-fluxo-alternativo)
  - [Caso de uso 06 - Ferramenta de Pesquisa](#caso-de-uso-06---ferramenta-de-pesquisa)
    - [Descrição Caso de uso 06 - Ferramenta de Pesquisa](#descrição-caso-de-uso-06---ferramenta-de-pesquisa)
    - [Diagrama do Caso de uso 06 - FERRAMENTA DE PESQUISA](#diagrama-do-caso-de-uso-06---ferramenta-de-pesquisa)
    - [Tutorial:](#tutorial-2)
      - [**Tutorial: Fluxo normal**](#tutorial-fluxo-normal-5)
  - [Caso de uso 07 - Visualizador de corpora](#caso-de-uso-07---visualizador-de-corpora)
    - [Descrição Caso de uso 07 - Visualizador de corpora](#descrição-caso-de-uso-07---visualizador-de-corpora)
    - [Diagrama do Caso de uso 07 - Visualizador de corpora](#diagrama-do-caso-de-uso-07---visualizador-de-corpora)
    - [Tutorial:](#tutorial-3)
      - [**Tutorial: Fluxo normal**](#tutorial-fluxo-normal-6)
  - [Caso de uso 08 - Synviewer](#caso-de-uso-08---synviewer)
    - [Descrição Caso de uso 08 - Synviewer](#descrição-caso-de-uso-08---synviewer)
    - [Diagrama do Caso de uso 08- Synviewer](#diagrama-do-caso-de-uso-08--synviewer)
    - [Tutorial:](#tutorial-4)
      - [**Tutorial: Fluxo normal**](#tutorial-fluxo-normal-7)
  - [Caso de uso 09 - Parser ](#caso-de-uso-09---parser-)
    - [Descrição Caso de uso 09](#descrição-caso-de-uso-09)
    - [Diagrama do Caso de uso 09 - Parser](#diagrama-do-caso-de-uso-09---parser)
    - [Tutorial:](#tutorial-5)
      - [**Tutorial: Fluxo normal**](#tutorial-fluxo-normal-8)
      - [\*\*Tutorial: Fluxo Alternativo](#tutorial-fluxo-alternativo-1)
    - [Tutorial: Guia do Usuário Final (SE HOUVER)](#tutorial-guia-do-usuário-final-se-houver)
      - [\*\*Tutorial: Fluxo normal \*\*](#tutorial-fluxo-normal-)
      - [**Tutorial: Fluxo alternativo**](#tutorial-fluxo-alternativo-2)
  - [Caso de uso 10 - IO (Importação e Exportação)](#caso-de-uso-10---io-importação-e-exportação)
    - [Descrição Caso de uso 10 - IO (Importação e Exportação)](#descrição-caso-de-uso-10---io-importação-e-exportação)
    - [Diagrama do Caso de uso 10 - IO (Importação e Exportação)](#diagrama-do-caso-de-uso-10---io-importação-e-exportação)
    - [Tutorial:](#tutorial-6)
      - [**Tutorial: Fluxo normal**](#tutorial-fluxo-normal-9)
      - [\*\*Tutorial: Fluxo Alternativo](#tutorial-fluxo-alternativo-3)
    - [Tutorial: Guia do Usuário Final (SE HOUVER)](#tutorial-guia-do-usuário-final-se-houver-1)
      - [\*\*Tutorial: Fluxo normal \*\*](#tutorial-fluxo-normal--1)
      - [**Tutorial: Fluxo alternativo**](#tutorial-fluxo-alternativo-4)

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
