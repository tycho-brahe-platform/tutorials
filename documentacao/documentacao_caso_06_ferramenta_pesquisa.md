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
  - [Caso de uso 06 - Ferramenta de Pesquisa](#caso-de-uso-06---ferramenta-de-pesquisa)
    - [Descrição Caso de uso 06 - Ferramenta de Pesquisa](#descrição-caso-de-uso-06---ferramenta-de-pesquisa)
    - [Diagrama do Caso de uso 06 - FERRAMENTA DE PESQUISA](#diagrama-do-caso-de-uso-06---ferramenta-de-pesquisa)
    - [Tutorial:](#tutorial)
      - [**Tutorial: Fluxo normal**](#tutorial-fluxo-normal)
  - [](#)

---

## Caso de uso 06 - Ferramenta de Pesquisa

A Ferramenta de Pesquisa possibilita ao usuário realizar pesquisas nos corpora disponíveis na plataforma Tycho Brahe. Há dois tipos de busca disponíveis na plataforma: **Pesquisa simples** e **Pesquisa sintática**. A Pesquisa Simples possibilita que o usuário utilize a sintaxe de expressões regulares (regex) para realizar buscas. Por outro lado, a Pesquisa Sintática disponibiliza dois modos de busca: um modo direto, utilizando os campos com listas suspensas, que apresentam opções para as seleções pertinentes para a pesquisa; ou um modo que possibilita a escrita livre da busca e posterior conversão do texto livre para o modo anterior.<!--REVISAR: VER COM O LUIS SE É ISSO MESMO QUE UTILIZA - CORPUS SEARCH?-->

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
      2. Modo 2 - Escreva sua pesquisa. É posível abrir um campo livre para preenchimento para executar busca com padrão de sintaxe livre: clicar em "escreva sua pesquisa".
         1. Preencher com o padão de busca.
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
Diagrama Caso de Uso 06 - Ferramenta de Pesquisa

### Tutorial:

**Objetivo:**
Este tutorial dem o objetivo de detalhar os procedimentos necessários para a realização de pesquisas nos corpora disponíveis na plataforma Tycho Brahe.

#### **Tutorial: Fluxo normal**

1. Acesse a página _home_ da plataforma Tycho Brahe através do link: <https://www.tycho.iel.unicamp.br/home>.
2. Na área de "Ferramentas", acesse a Ferramenta "Search".

![Ferramenta pesquisa](../imagens/busca_01.png)
Ferramenta de Pesquisa

3. Escolha um dos corpora para realizar a busca.

![Seleção corpus para pesquisa](../imagens/busca_2.png)
Selecionando corpus para realizar uma pesquisa. 4. Escolha o tipo de pesquisa que deseja realizar: **Pesquisa simples** ou **Pesquisa sintática**.

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
Relizando uma Pesquisa Simples.

A pesquisa realizada no exemplo na Figura acima retorna o seguinte resultado no corpus de Teste.

![Resultado pesquisa](../imagens/busca_9.png)
Resultado de uma busca simples.

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
Realizando uma Pesquisa Sintática

**Modo 2 - Escreva sua pesquisa**. É posível abrir um campo livre para preenchimento para executar busca com padrão de sintaxe livre com etiquetas POS:

1. Clique em "escreva sua pesquisa".
2. Preencha o campo com o padão de pesquisa desejado.
3. Clique em "Converter texto" para converter busca para campos preenchidos na "Pesquisa sintática" default<!--REVISAR: AVISAR AO LUIS QUE QUANDO PREENCHO NO CAMPO LIVRE E CONVERTO PARA A BUSCA E REALIZO ESTÁ DANDO ERRO-->

Para qualquer tipo de busca, é possível realizar algumas configurações:

1. Clique no ícone de "configurações" no canto direito superior.
   1. Metadados <!--REVISAR: encontrei onde se preenche os metadados no admin, configurações (mas não entendi quais os tipos de dados são para serem preenchidos e não sei como isto impacta na hora da pesquisa) -->
   2. Documentos: selecione um documento para limitar a pesquisa a documentos específicos (pode aumentar velocidade de resposta da requisição).
   3. Exportar: selecione o formato para exportar os resultados da pesquisa.
   4. Consultas: verifique consultas salvas.
   5. Definições <!--REVISAR: VERIFICAR QUAIS SÃO AS DEFINIÇÕES POSSÍVEIS AQUI-->
   <!--REVISAR: aguardar reunião com Luiz para entender melhor esta parte de configurações-->

## <!-- REVISAR COM LUIZ: O PADRÃO DE BUSCA NA BUSCA SINTÁTICA LIVRE É CORPUS SEARCH?-->
