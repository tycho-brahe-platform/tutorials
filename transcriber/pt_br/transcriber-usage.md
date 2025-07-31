## Transcriber

Índice

- [Transcriber](#transcriber)
- [Tutorial](#tutorial)
  - [**Fluxo normal**](#fluxo-normal)
    - [**Adicionar áudio**](#adicionar-áudio)
    - [**Modo Tap**](#modo-tap)
    - [**Transcrição**](#transcrição)
    - [**Editar Informações da transcrição**](#editar-informações-da-transcrição)
    - [**Atalhos**](#atalhos)
    - [**Participantes**](#participantes)

---

## Tutorial

**Objetivo:**
Este tutorial apresenta os passos para utilização do Transcriber, envolvendo a adição de áudio para transcrição, criação de perfil de participantes, associação desses perfis a regiões de áudio (utilizando o Modo Tap), extração de trechos de áudio associados às transcrições etc.

### **Fluxo normal**

Para a edição de uma transcrição no Transcriber, pressupõe-se que o documento tenha sido previamente criado e selecionada a ferramenta Transcriber como ferramenta associada ao documento (para mais detalhes de criação de documentos,ver Caso de uso 03_02 - Criação, configuração e edição de novos documentos).

![](./images/tu/transcriber_1.png)

O primeiro passo a ser adotado para realizar uma trasncrição é a adição de um áudio.
Neste tutorial vamos seguir o exemplo de um áudio em karitiana.

#### **Adicionar áudio**

1. No corpus alvo, clique sobre o documento criado para edição no Transcriber.
2. Clique no ícone para abrir menu de ferramentas de edição.
3. Selecione "Usar o Transcriber".

![](./images/tu/transcriber_2.png)

Esta é a tela inicial do documento no Transcriber

![](./images/tu/transcriber_3.png)

4. Para adicionar um áudio para transcrição clique na área "Áudio não disponível - clique aqui para realizar o upload".
5. Selecione um arquivo de áudio no diretório de sua preferência. São aceitos áudios nos formatos: m4a, mp4 ou mp3 - no caso de outras extensões, realize uma conversão em uma plataforma online para as extensões suportadas no Transcriber. Após upload clique em "Confirmar"

![](./images/tu/transcriber_4.png)

6. Após a adição do áudio, uma barra horizontal apresenta a representação gráfica em forma de onda do áudio. Clique em Reproduzir/pausar para controlar o áudio (Atalho: CTRL + SPACE). Nesta janela, outras informações são apresentadas (ver figura a seguir).

![](./images/tu/transcriber_5.png)

#### **Modo Tap**

Após realizar a adição de um áudio e a criação de participantes (ver abaixo), a ferramenta de "Modo Tap" permite ao usuário tocar o áudio e associar regiões a participantes através das teclas numéricas (a cada participante criado é atribuído um número cardinal do teclado numérico). Para utilizar o "Modo Tap":

1. Clique em “Modo Tap” para abrir a funcionalidade. A tela apresenta as informações como dispostas na imagem:
2. Ulilize o botão Reproduzir/Pausar para dar início ao áudio.

![](./images/tu/transcriber_10.png)

3. Cada participante tem um número associado. Para associar uma região do áudio a um participante, com o áudio em andamento, pressione o respectivo número para marcar o início e pressione o número novamente para marcar o fim. Por exemplo, no áudio, **Participant 1** inicia uma fala - pressione 1 para marcar o início da sentença e 1 novamente para marcar o fim. Isso criará regiões do áudio associadas a cada participante. Os trechos marcados são dispostos com a mesma cor atribuídas aos participantes.

![](./images/tu/transcriber_11.png)

#### **Transcrição**

Para realizar uma transcrição de região marcada:

1. Clique sobre um trecho associado a um participante.
2. Use o botão de play para tocar apenas o trecho de áudio.
3. Realize a Transcrição original do trecho (sentença).
4. Transcrição normalizada: campo com a transcrição que será efetivamente associada ao eDictor e será usada para análise morfossintática. Clique no botão caso queira copiar exatamente o conteúdo da Transcrição original.
5. Clique para inserir camadas.
6. Preencha as traduções (se houver).
7. Abra sentença no eDictor (habilitado quando a Transcrição Normalizada é preenchida).
8. Lembre-se de salvar para não perder seu trabalho (salvamento não é automático).
9. Clique para remover a transcrição.
10. Clique para marcar para revisão
11. Clique para adicionar uma Observação.

![](./images/tu/transcriber_12.png)

A transcrição e a tradução ficam dispostas no trecho associado ao participante:

![](./images/tu/transcriber_13.png)

Para adicionar uma Observação e atribuí-la a um outro usuário:

1. Selecione “Observações”.
2. Clique em “Adicionar comentário”.
3. Preencha o comentário.
4. Dê um título.
5. Selecione um destinatário para o comentário.
6. Clique em “Adicionar comentário” para salvar o comentário.

![](./images/tu/transcriber_14.png)

#### **Editar Informações da transcrição**

Para editar informações da transcrição:

1. Clique sobre o nome do documento para abrir um menu na lateral esquerda.
2. Selecione “Informações”.
3. Os campos são editáveis: clique sobre o campo, preencha as informações e confirme.
<!--REVISAR:VERIFICAR O QUE CADA CAMPO SIGNIFICA CONCEITUALMENTE?-->

![](./images/tu/transcriber_6.png)

**Ações**: a plataforma disponibiliza algumas ações que podem operar para facilitar e acelerar o processo (como "Importar frases") e algumas ações pós transcrição (como "Dividir arquivo de áudio", "Remover sentenças" e "Remover arquivo de áudio".)

![](./images/tu/transcriber_15.png)

- **Dividir arquivo de áudio**: Divida o áudio principal em trechos menores de acordo com os trechos associados aos Participantes no "Modo Tap". Após realizar as transcrições (manualmente ou importando) e salvar.

1. Clique sobre o nome do documento para abrir um menu na lateral esquerda.
2. Selecione “Acões” e “Dividir arquivo de áudio”. Uma mensagem de sucesso é apresentada se não houver problemas. Abre-se uma tela no eDictor apresentando a transcrição original, Tradução da transcrição (importada) e respectivo trecho de áudio dividido e associado à transcrição.

![](./images/tu/transcriber_18.png)

- **Importar frases**: é possível importar frases previamente transcritas (e potenciais traduções), acelerando o processo de transcrição. **Nota**: para que a importação de frases seja bem-sucedida, é necessário que já tenham sido marcadas regiões no áudio (associadas a participantes) no "Modo Tap" e que o número de regiões marcadas seja exatamente o mesmo que o número de frases a serem importadas. Do contrário a plataforma retorna erro.

1. Clique sobre o nome do documento para abrir um menu na lateral esquerda.
2. . Clique em “Ações” e “Importar frases”.
3. Verifique no canto superior direito o número de marcações/transcrições no documento (em [2] na figura a seguir - neste exemplo são 5 transcrições). Lembrando que o número de frases editadas e o número de marcações deve coincidir, do contrário a importação não será bem-sucedida.
4. Selecione o “Tipo de importação”: Apenas texto original, Apenas tradução, Texto e Tradução.
5. Selecione “Traduções”: línguas de tradução que serão apresentadas dependerá das línguas configuradas na página de administração do corpus.
6. Preencha com as sentenças: original e tradução (separado por uma quebra de linha) e separe os pares de sentenças (duas quebras de linha), coincidindo em número com as regiões demarcadas no áudio.
7. Confirme.

![](./images/tu/transcriber_16.png)

Com esta importação das frases (e traduções), as transcrições (original e tradução) ficam preenchidas desta forma:

![](./images/tu/transcriber_17.png)

- **Remover sentenças**:

1. Clique sobre o nome do documento para abrir um menu na lateral esquerda.
2. Clique em “Ações” e em “Remover sentenças”.
3. Leia o aviso e confirme (esta ação não pode ser desfeita).

![](./images/tu/transcriber_19.png)

- **Remover arquivo de áudio**:

1. Clique sobre o nome do documento para abrir um menu na lateral esquerda.
2. Clique em “Ações” e em “Remover arquivo de áudio.
3. Leia o aviso e confirme (esta ação não pode ser desfeita).

![](./images/tu/transcriber_20.png)

#### **Atalhos**

A ferramenta Transcriber disponibiliza alguns atalhos para facilitar a tarefa do transcritor:

![](./images/tu/transcriber_9.png)

#### **Participantes**

Esta funcionalidade permite a gestão de participantes (criação, edição de informações etc.)

1. Clique para abrir um menu na lateral à esquerda.
2. Selecione “Participantes”.
3. Clique “+ Adicionar participante”.
4. Preencha um ID e o Nome do participante e clique em “Confirmar”.

![](./images/tu/transcriber_7.png)

Após a criação do Participante, é possível realizar configurações específicas:

1. Clique para selecionar qual participante vai ser configurado (uma lista suspensa com todos os Participantes previamente criados se apresenta).
2. Clique sobre os campos editáveis, preencha e confirme.
3. Defina a cor que será associada ao perfil do Participante (esta cor fica marcada nos trechos de áudio associados aos participantes no "Modo Tap").
4. Botão pare “Remover” Participante.

![](./images/tu/transcriber_8.png)

Para cada um dos Participantes, é atribuido um número cardinal para uso na associação de trecho de áudio a participante no "Modo Tap".

---
