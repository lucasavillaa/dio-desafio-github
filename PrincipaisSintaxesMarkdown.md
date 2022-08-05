# Markdown

## Vantagens do Markdown

Porque utilizar Markdown em vez de um editor WYSIWYG (um editor de textos estilo Microsoft Word ou LibreOffice Writer)? Por que escrever em Markdown em vez de pressionar botões em uma interface para formatar um texto? Existem alguns motivos diferentes para se usar o Markdown em vez de um editor WYSIWYG, na sequência listamos algumas.

- **Markdown pode ser usado para tudo.** Para criar sites, documentos, notas, livros, apresentações, mensagens de e-mail, documentação técnica, documentação acadêmica, etc;

- **Markdown é portátil.** Arquivos de texto escritos em Markdown podem ser abertos com praticamente qualquer aplicativo, o que contrasta fortemente com os aplicativos de processamento de texto do tipo WYSIWYG, que bloqueiam seu conteúdo em um formato de arquivo proprietário;

- **Markdown é independente de plataforma.** Texto formatado em Markdown pode ser criado em qualquer dispositivo que execute qualquer sistema operacional;

- **Markdown é à prova de futuro.** Se o aplicativo que você está usando parar de funcionar em algum momento no futuro, um texto formatado em Markdown ainda poderá ser lido e editado usando qualquer outro aplicativo de edição de texto. Essa é uma consideração importante quando se trata de livros, teses universitárias e outros documentos importantes que precisam ser preservados indefinidamente;

- **Markdown está em toda parte.** Inúmeros sites da Web suportam Markdown, e muitos aplicativos de desktop e baseados na Web o suportam. Existem conversores de Markdown para virtualmente todos os formatos existentes no mundo.

---

## Como o Markdown funciona

Quando escrevemos em Markdown o texto é armazenado em um arquivo de texto simples com extensão .md ou .markdown.

Para que um arquivo Markdown seja convertido em HTML ou em um documento pronto para impressão precisamos de um aplicativo Markdown capaz de processar o arquivo.

Existem inúmeros aplicativos disponíveis - tudo, desde scripts simples de linha de comando até aplicativos de desktop que se parecem com Word, passando por aplicativos baseados na Web. Apesar de diferentes, todos fazem a mesma coisa, convertem texto formatado em Markdown em HTML para que possa ser exibido em navegadores da Web ou convertido em outro formato (o que pode ser feito diretamente também).

Os aplicativos Markdown usam algo chamado de processador Markdown (também chamado de “analisador” - ou parser - ou de “implementação markdown”) para ler o texto Markdown e reescrevê-lo no formato HTML. E então o documento pode ser visualizado em um navegador da Web ou combinado com uma folha de estilos e ser impresso.

Sinteticamente, este é um processo de quatro partes:

1. Criar um arquivo Markdown usando um editor de texto ou um aplicativo Markdown dedicado. O arquivo deve ter uma extensão .md ou .markdown;

2. Abrir o arquivo Markdown em um aplicativo Markdown;

3. Usar o aplicativo Markdown para converter o arquivo Markdown em um documento HTML;

4. Visualizar o arquivo HTML em um navegador da web ou usar o aplicativo Markdown para convertê-lo em outro formato de arquivo, como PDF por exemplo.

O ponto de vista de um usuário sobre processo pode variar conforme a ferramenta utilizada, muitas das quais podem condensar estas etapas em praticamente uma, outras podem adicionar complexidade e funcionalidades extras, tudo conforme o propósito.

---

# Sintaxe básica

## Títulos

O Markdown permite marcar títulos de nível 1 (o título principal) até títulos de nível 6 (o menor nível de subtítulo possível), assim como no HTML. Para marcar um título de nível 1 basta adicionar um # (hash, ou sharp, sustenido, jogo da velha, tralha, cerquilha, como preferir) seguido por um espaço antes texto do título. Para adicionar um título de nível 2 basta adicionar ## (dois hashes) e assim por diante. Desta forma, o seguinte trecho em Markdown:

# Título 1: Cidade

## Título 2: Zona

### Título 3: Bairro

#### Título 4: Logradouro

##### Título 5: Edificação

###### Título 6: Unidade

---

## Listas não ordenadas

A sintaxe para criar uma lista não ordenada em Markdown também é bastante simples e intuitiva, quase como se não estivéssemos fazendo uma “marcação” propriamente. Existem três opções, cada item da lista deve ser precedido por um sinal de - (subtração ou hífen) ou de + (adição) ou um * (asterisco) seguidos de um espaço e o texto do item da lista. Da seguinte forma:

- Primeiro item da lista 
- Segundo item da lista

+ Primeiro item da outra Lista
+ Segundo item da outra Lista

* Primeiro item da terceira Lista
* Segundo item da terceira lista

---


## Listas ordenadas

Para criar uma lista ordenada basta adicionar um número seguido de um ponto e de um espaço antes do texto de cada item da lista. Pode ser qualquer número, em qualquer ordem, ou pode mesmo ser sempre o mesmo número, que o resultado será uma lista ordenada, conforme o seguinte trecho de Markdown:

1. Primeiro item da lista
1. Segundo item da lista
1. Terceiro item da Lista

3. Primeiro item da outra Lista
7. Segundo item da outra Lista
2. Terceiro item da outra lista


