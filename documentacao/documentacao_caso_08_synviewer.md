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
  - [Caso de uso 08 - Synviewer](#caso-de-uso-08---synviewer)
    - [Descrição Caso de uso 08 - Synviewer](#descrição-caso-de-uso-08---synviewer)
    - [Diagrama do Caso de uso 08- Synviewer](#diagrama-do-caso-de-uso-08--synviewer)
    - [Tutorial:](#tutorial)
      - [**Tutorial: Fluxo normal**](#tutorial-fluxo-normal)

---

## Caso de uso 08 - Synviewer

A plataforma Tycho Brahe oferece uma interface para a geração e visualização de árvores sintáticas, o **Synviewer**. Dentre as funcionalidades, destacam-se a geração de árvores sintáticas com base em parsers baseados em regra desenvolvidos no âmbito do projeto, bem como árvores sintáticas baseadas no banco de Dependências Universais (_Universal Dependencies - UD_). Esta ferramenta facilita o uso dos parser desenvolvidos dentro do projeto, facilitando a visualização, exportação e apresentação dos dados.

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
Diagrama de caso de uso Synviewer

### Tutorial:

**Objetivo:**
Este tutorial tem como objetivo detalhar apresentar as funcionalidades do synviewer
#### **Tutorial: Fluxo normal**

1. Acesse a página inicial da plataforma Tycho Brahe no endereço <https://www.tycho.iel.unicamp.br/home>.

![Acesso Synviewer](../imagens/synviewer/syn_1.png)
Acessando página inicial

2. Clique no "Synviewer" na área de "Ferramentas" para acessar a funcionalidade.

![Geral synviewer](../imagens/synviewer/syn_2.png)
Acessando o "Synviewer"

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
