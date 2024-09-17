
## 4. Caso de uso 04 - Criação, configuração e edição dos corpora

A ferramenta de criação de corpora é um componente fundamental para a construção e gestão eficiente de coleções de textos destinados a análises linguísticas. Este processo pode ser realizado por Administradores e usuários devidamente cadastrados e com as credenciais corretas (de edição).

Para os administradores, a ferramenta oferece recursos avançados para a criação e configuração dos corpora, atribuição de permissões e gerenciamento etc.

Há três formas [REVISAR] para executar a criação de corpora na ferramenta Tycho Brahe:

1. *Translation mode* (Modo traduções) ou *Translation edictor*
2. [REVISAR: INSERIR LISTA DE MANEIRAS DE DEV DE CORPUS]
Antes de ver em detalhe cada uma das meneiras de criação de corpora, é necessário apresentar quais são as opções disponíveis para configuração dos corpra.

A seguir, é apresentada uma descrição dos botões de configuração dos corpora (acesso pela ferramenta "Corpora Management"). O acesso à área de configuração dos corpora pode ser realizada a partir da pagina inicial da plataforma em https://www.tycho.iel.unicamp.br/home , acessando-se a ferramenta "Corpora Management", como apresentado na Figura x, a seguir:

<figure> 
    <img src = "../imagens/botoes_configuracao_corpora2.png" alt = "Processo de configuração dos corpora: acessando a área de config">
    <figcaption>Figura x: Acessando área de configuração de corpora </figcaption>

</figure>


- Public corpus: seleciona se o corpus é disponível ao público em geral ou se é privado.
- Active: configura se o corpus está ativo;
- Featured corpus: atualmente não está sendo utilizado [REVISAR QUAL A FUNCIONALIDADE]
- Use split: habilita o uso campos referentes morfemas, incluindo glossa, nos corpora.

<figure>
    <img src="../imagens/botao_config_corpus_usesplit.png"
         alt="Configura corpus: Use Split">
    <figcaption>Figura X: Configuração de corpora: botão "use split"</figcaption>
</figure>

- Use Sound: a habilita o uso de áudio no corpus.
  
  - Como podemos observar na Figura x abaixo, a habilitação do botão "Use Sound" habitila uma seção de Áudio, que permite ao analista incluir o áudio a ser transcrito.
  
<figure>
    <img src="../imagens/botao_config_corpus_usesound.png"
         alt="Configura corpus: use sound 1">
    <figcaption>Figura X: Configuração de corpora: botão "Use Sound"</figcaption>
</figure>

  - O "Use Sound" também habilita, na ferramenta "edictor", um botão para dar play nos áudios associados às sentenças do documento selecionado, como observamos na Figura x abaixo:
  
<figure>
    <img src="../imagens/botao_config_corpus_usesound2.png"
         alt="Configura corpus: Use Sound 2">
    <figcaption>Figura X: Configuração de corpora: botão "Use Sound"(no edictor)</figcaption>
</figure>

- Use translations: o botão "use translations" habilita a seção de Traduções no edictor, como apresentado na Figura x:

<figure>
    <img src = "../imagens/botao_config_corpus_usetranslation.png" alt = "Configura corpus: use translations">
    <figcaption> Figura x: Configuração de corpora: botão "use translations"  </figcaption>
</figure>

- Use Lexicon: é utilizado quando há um parser disponível, mas não há um etiquetador automático (que só funciona se houver uma quantidade mínima de palavras para treinamento do etiquetador). No caso de esta condição não estar satisfeita, o analista deve utilizar o léxico para realizar a etiquetagem automática.

- Use Grid: ao acessar o catálogo, o usuário tem a possibilidade de apresentação de documentos de duas maneiras: lista, ou grid. Ao habilitar o botão "Use Grid", o usuário configura a apresentação em grid como default, como apresentado na Figura x abaixo:

<figure>
<img  src = "../imagens/botao_config_corpus_usegrid.png" alt = "Configura corpus: Use Grid">

<figcaption> Figura x: Configuração de corpora: botão "Use Grid"</figcaption>

</figure>

- Use Parser: [REVISAR: O Luiz mencionou que iria revisar se este botão está sendo utilizado..a mesma funcionalidade está presente na aba à esquerda]. Este botão habilita a utilização de parser.

- Use Category: o botão "Use Category" habilita a possibilidade de categorização e subcategorização dos corpora (por exemplo, categorização com base em parâmetros demográficos etc), como apresentado na Figura x, com o corpus CE-DOHS selecionado no catálogo. Note-se que a criação dos rótulos para as categorias pode ser realizada por um usuário com permissões de adminstrador 

<figure>
    <img src = "../imagens/botao_config_corpus_usecategory.png" alt = "Configuração corpus_ Use Category">
    <figcaption>Figura x: Configuração de corpora: botão "Use Category"</figcaption>
</figure>

- Use Edition Tiers: o botão "Use Edition Tiers", contrapondo-se ao "use split", habilita a disponibilização de diversos campos para edição, incluindo POS, spelling etc. Por exemplo, acessando-se o catálogo, selecione o corpus Tycho Brahe do Português Histórico e selecione o documento "Atas dos Brasileiros - Tomo 02", como apresentado na Figura X:

<figure>
    <img src = "../imagens/botao_config_corpus_useeditiontiers1.png" alt = "Configura corpus: botão Use Edition Tiers">
    <figcaption>Figura x: Configuração de corpora: botão "Use Edition Tiers"
</figure>


<figure>
    <img src = "../imagens/botao_config_corpus_useeditiontiers2.png" alt = "Configura corpus: botão Use Edition Tiers 2">
    <figcaption>Figura x: Configuração de corpora: botão "Use Edition Tiers (abrindo a )."</figcaption>

</figure>

<figure>
    <img src = "../imagens/botao_config_corpus_useeditiontiers3_4.png" alt = "Configura corpus: botao Use Edition Tiers 4">
    <figcaption>Figura x: Configuração de corpora  botão "Use Edition Tiers: "</figcaption>
</figure>

Esta ação abre um painel com uma matriz para edição das camadas de edição, como mostra a Figura x. Note-se: na mesma tela que seria análoga à sentença com o "use split" selecionado, são apresentadas as camadas de edição.

<figure>
    <img src = "../imagens/botao_config_corpus_useeditiontiers5.png">
    <figcaption>Figura x: Matriz para edição em camadas </figcaption>
</figure>

- Use Translations/Use Edictor/Use Designer/Use Transcriber/Use Syntrees/: Estes cinco botões não são excludentes, i.e., podem ser habilitados todos ao mesmo tempo em um determinado corpus. Esta ação disponibiliza todas as ferramentas para utilização no corpus. (Haeverá seções específicas para cada um dos botões) 

Nos tópicos a seguir, serão abordados os principais fluxos de trabalho para a criação de novos corpora, além de tutoriais detalhados que guiam administradores e usuários no uso eficiente da ferramenta, garantindo uma experiência fluida e colaborativa na gestão dos catálogos.

