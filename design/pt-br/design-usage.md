# Ferramenta **eDictor Design**

Índice

- [Ferramenta **eDictor Design**](#ferramenta-edictor-design)
  - [Tutorial](#tutorial)
    - [**Fluxo normal**](#fluxo-normal)
      - [Configuração e importação de documento](#configuração-e-importação-de-documento)
      - [Realizar marcações no documento](#realizar-marcações-no-documento)
      - [Transcrições](#transcrições)
        - [**Manual**](#manual)
        - [**Automática**](#automática)
      - [Modo edição](#modo-edição)

---

## Tutorial

Este tutorial apresenta em detalhes o uso da ferramenta **eDictor Design** para edição e revisão de corpora.

### **Fluxo normal**

#### Configuração e importação de documento

1. Verifique (ou Habilite) o **use Designer** na página de /admin do corpus, na aba de parâmetros.

![](./images/du/designer-1.png)

2. Verifique se o documento que deseja editar está no corpus, ou adicione novo documento para transcrição e edição.

   1. Clique em "+Adicionar novo documento".
   2. Preencha o nome do novo documento.
   3. Selecione a Ferramenta de edição desejada para o documento - Para este caso de uso selecione **Design**.
   4. Seleciona a visibilidade do documento (Público ou Privado) e clique em confirmar.
      ![](./images/du/designer-2.png)

Para incluir uma imagem de jornal, por exemplo, para iniciar a marcação, transcrição e edição:

1. Clique sobre o documento.
2. Sobre a coluna que se abre à esquerda, clique em "Ações" e clique em "Continuar a edição do documento" para abrir a ferramenta de Design.

   ![](./images/du/designer-3.png)

3. Realize o upload de um arquivo para realizar as marcações de áreas e a transcrição: do lado esquerdo da página que se abre após a criação do documento, clique em "clique aqui para realizar o upload", selecione imagem (ou arraste a imagem) e confirme .

   ![](./images/du/designer-4.png).

#### Realizar marcações no documento

Após o upload do arquivo, o sistema apresenta o documento e o menu de edições e marcações da imagem (à esquerda):
Na ordem da esquerda para a direita:

![](./images/du/designer-5.png)

1. Mover imagem.
   1. Para mover uma imagem, selecione o ícone "Mover imagem.
   2. Com o cursor, clique e arraste a imagem para a posição desejada.

![](./images/du/designer-6.png)

2. Mover marcações.
   1. Para mover as macações, selecione "Mover marcações"
   2. Com o cursor, clique e arraste a marcação para a posição desejada.

![](./images/du/designer-7.png)

3. Criar marcação na imagem.
   1. Selecione “Criar uma Marcação”
   2. Selecione a área desejada com o cursor e Confirme.
   3. Cada marcação criada na imagem terá uma página correspondente criada (2 marcações e 2 páginas).

![](./images/du/designer-8.png)

1. Redimensionar marcações
   1. Selecione “Redimensionar marcações”.
   2. Com o cursor, clique nas arestas das caixas de marcação e redimensione.

![](./images/du/designer-9.png)

5. Recentralizar imagem: clique para recentralizar a imagem.

6. Exibir ordem das marcações.
   1. Para exibir a ordem de criação das marcações, selecione "Exibir ordem".

![](./images/du/designer-10.png)

7. Excluir imagem: clique sobre o ícone "Excluir imagem" e confirme.

![](./images/du/designer-11.png)

#### Transcrições

Após as marcações serem realizadas em todas as áreas com textos, é possível iniciar a transcrição manual ou automática.

##### **Manual**

1. Selecione a página que deseja transcrever (lembre-se que cada marcação na imagem tem uma contrapartida em página, ou seja, a ordem das páginas segue a ordem das marcações);
2. Clique o botão "Transcrição" para abrir o campo de preenchimento manual do texto na marcação realizada na imagem.
3. Realize a transcrição na área indicada "Digite aqui sua transcrição.
4. Clique no ícone de "Salvar" para salvar as alterações.

![](./images/du/designer-12.png)

Repita para cada página do documento.

##### **Automática**

Para realizar a transcrição automaticamente, extraindo o texto da imagem:

1. Selecione a página que deseja transcrever (lembre-se que cada marcação na imagem tem uma contrapartida em página, ou seja, a ordem das páginas segue a ordem das marcações);
2. Clique o botão "extrair texto de imagem"(T), no canto superior direito, para realizar a transcrição automática a partir da imagem na área da marcação (página selecionada).
3. O texto será extraído para a área de edição da transcrição. A depender da qualidade da imagem, é necessário realizar uma revisão e edição extensiva do texto extraído. Verifique, corrija e edite a transcrição se necessário.
4. Clique no ícone de "Salvar" para salvar as alterações.

![](./images/du/designer-13.png)

#### Modo edição

Após a finalização da transcrição, o texto pode passar para o modo edição, onde passa por tokenização e preparação para receber tratamento computacional (etiquetagem POS, parser etc).

1. Clique no ícone de "ir para o modo edição" para preparar o texto para receber edições.

![](./images/du/designer-14.png)

**Nota:** com o texto em modo de edição, é possível, como apresentado no tutorial do use eDictor, realizar etiquetagem e outras edições (Ver Caso de uso 04 - Ferramenta use eDictor, a partir do item 7 do Fluxo normal).

---
