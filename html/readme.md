## O que é HTML?

HTML (HyperText Markup Language) é a linguagem de marcação utilizada para estruturar páginas na web. Com o HTML, você define títulos, parágrafos, listas, links, imagens e outros elementos que compõem uma página.

https://developer.mozilla.org/pt-BR/docs/Web/HTML

## Tags semânticas em HTML

Tags semânticas são elementos que indicam claramente o significado do conteúdo que envolvem, facilitando a compreensão do código por navegadores, motores de busca e outros desenvolvedores.

### Exemplos de tags semânticas:

- **`<header>`**: Cabeçalho da página ou de uma seção.
- **`<nav>`**: Área de navegação (menus, links).
- **`<main>`**: Conteúdo principal da página.
- **`<section>`**: Seção de conteúdo relacionada.
- **`<article>`**: Conteúdo independente, como posts ou notícias.
- **`<aside>`**: Conteúdo lateral, como barras laterais ou anúncios.
- **`<footer>`**: Rodapé da página ou de uma seção.
- **`<figure>`**: Agrupa uma mídia (imagem, gráfico) e sua legenda.
- **`<figcaption>`**: Legenda de uma mídia dentro do `<figure>`.
- **`<mark>`**: Destaca um texto relevante.
- **`<time>`**: Representa uma data ou hora.
- **`<address>`**: Informações de contato.

## Algumas marcações (tags) usadas em HTML5
-- Artido do Devmedia --
- **`<!--...-->`** Define um comentário; atalho no windows para comentar -> 'ctrl' + ';'
- **`<!DOCTYPE>`** Define o tipo de documento; (No HTML 4 existiam três (3) diferentes tipos de doctype, mas no HTML 5 temos apenas um (1) tipo <!DOCTYPE HTML>. É aqui que o navegador entende o tipo de documento e como ele deve interpretar as tags nele contidas.)
- **`<a>`** Define um hyperlink;
- **`<abbr>`** Define uma abreviação
- **`<address>`** Define um endereço. (Passa a ser tratado como uma seção);
- **`<area>`** Define uma área dentro de um mapa de imagem;
- **`<b>`** Define um texto em negrito; (Possui o mesmo nível semântico que um SPAN, e também o estilo de negrito no texto. Contudo, ele não dá nenhuma importância para o texto marcado com ele.)
- **`<base>`** Define uma base URL para todos os links da página;
- **`<bdo>`** Define a direção do texto apresentado;
- **`<blockquote>`** Define uma citação longa;
- **`<body>`** Define o corpo da página;
- **`<br>`** Insere uma quebra de linha simples;
- **`<button>`** Define um botão de comando;
- **`<caption>`** Define o "caption" de uma tabela;
- **`<cite>`** Define uma citação;
- **`<code>`** Define o código texto do computador;
- **`<col>`** Define os atributos da coluna da tabela;
- **`<colgroup>`** Define um grupo de colunas da tabela;
- **`<dd>`** Define uma descrição de definição;
- **`<del>`** Define um texto deletado;
- **`<dfn>`** Define um termo de definição;
- **`<div>`** Define uma seção no documento;
- **`<dl>`** Define uma lista de definição;
- **`<dt>`** Define um termo de definição;
- **`<em>`** Define um texto em ênfase;
- **`<fieldset>`** Define um conjunto de campos (fieldset);
- **`<form>`** Define um formulário;
- **`<h1>` até `<h6>`** Define do cabeçalho 1 até o cabeçalho 6;
- **`<head>`** Define uma informação sobre o documento. (Não aceita mais elementos Child como filho);
- **`<hr>`** Define uma regra horizontal. (Tem o mesmo nível que um parágrafo, mas também é utilizado para fazer separações e quebras de linha);
- **`<html>`** Define um documento html;
- **`<i>`** Define um texto em itálico; (Possui o mesmo nível semântico que um SPAN. O texto continua sendo itálico e para usuários de leitores de tela, a voz utilizada é modificada para indicar ênfase. É de grande valor e utilidade para marcar, termos técnicos, termos em outras linguagens etc.)
- **`<iframe>`** Define uma linhas sobre a janela (frame);
- **`<img>`** Define uma imagem;
- **`<input>`** Define um campo de inserção;
- **`<ins>`** Define um texto inserido;
- **`<kbd>`** Define um texto do teclado;
- **`<label>`** Define uma "label" para o formulário;
- **`<legend>`** Define um título para os campos (fields);
- **`<link>`** Define uma referência;
- **`<map>`** Define uma imagem de mapa;
- **`<menu>`** Define uma lista de "menus";
- **`<meta>`** Define informações meta;
- **`<noscript>`** Define uma seção noscript;
- **`<object>`** Define um objeto incorporado;
- **`<optgroup>`** Define um grupo de opção;
- **`<option>`** Define uma opção em uma lista suspensa (drop-down list);
- **`<p>`** Define um parágrafo;
- **`<param>`** Define um parâmetro para determinado objeto;
- **`<pre>`** Define um texto pré-formatado;
- **`<q>`** Define uma citação curta;
- **`<s>`** Define um texto que não é mais correto.
- **`<samp>`** Define um código de amostra;
- **`<script>`** Define um script;
- **`<select>`** Define uma lista selecionável;
- **`<small>`** Define um pequeno texto;
- **`<span>`** Container em linha para estilizar partes do texto.
- **`<strong>`** Define um texto forte (similar ao negrito);
- **`<style>`** Define um estilo;
- **`<sub>`** Define um texto subscrito;
- **`<sup>`** Define um texto sobrescrito;
- **`<table>`** Define uma tabela;
- **`<tbody>`** Define o corpo da tabela;
- **`<td>`** Define uma célula da tabela;
- **`<textarea>`** Define um área de texto;
- **`<tfoot>`** Define o rodapé da tabela;
- **`<th>`** Define o cabeçalho da tabela;
- **`<thead>`** Define o cabeçalho da tabela;
- **`<title>`** Define o título do documento;
- **`<tr>`** Define uma linha da tabela;
- **`<ul>`, `<ol>`, `<li>`**: Listas não ordenadas, ordenadas e itens de lista.
- **`<var>`** Define uma variável;

## Atributos em HTML

Atributos são usados para fornecer informações extras aos elementos HTML. Eles sempre aparecem dentro da tag de abertura e geralmente seguem o formato `nome="valor"`.

### Exemplos de atributos comuns:

- **href**  
  Usado em links para definir o destino.
  ```html
  <a href="https://www.exemplo.com">Visite o site</a>
  ```

- **src**  
  Usado em imagens para definir o caminho do arquivo.
  ```html
  <img src="imagem.jpg" alt="Descrição da imagem">
  ```

- **alt**  
  Texto alternativo para imagens.
  ```html
  <img src="logo.png" alt="Logo da empresa">
  ```

- **id**  
  Identificador único para um elemento.
  ```html
  <div id="cabecalho"></div>
  ```

- **class**  
  Define uma ou mais classes para o elemento.
  ```html
  <p class="destaque">Texto em destaque</p>
  ```

- **style**  
  Adiciona estilos CSS diretamente ao elemento.
  ```html
  <h1 style="color: blue;">Título Azul</h1>
  ```

- **title**  
  Mostra um texto ao passar o mouse sobre o elemento.
  ```html
  <button title="Clique aqui">Botão</button>
  ```

- **type**  
  Define o tipo de elemento, muito usado em `<input>`, `<button>`, `<script>`, etc.
  ```html
  <input type="text">
  <button type="submit">Enviar</button>
  ```

- **value**  
  Define o valor inicial de um campo de formulário.
  ```html
  <input type="text" value="Digite aqui">
  ```

- **placeholder**  
  Texto de dica exibido em campos de formulário.
  ```html
  <input type="email" placeholder="seu@email.com">
  ```

- **name**  
  Nome do campo, importante para formulários.
  ```html
  <input type="password" name="senha">
  ```

- **disabled**  
  Desabilita o elemento.
  ```html
  <button disabled>Indisponível</button>
  ```

- **readonly**  
  Torna o campo somente leitura.
  ```html
  <input type="text" value="Apenas leitura" readonly>
  ```

- **maxlength**  
  Limita o número máximo de caracteres.
  ```html
  <input type="text" maxlength="10">
  ```

- **checked**  
  Marca um checkbox ou radio button como selecionado.
  ```html
  <input type="checkbox" checked>
  ```

- **required**  
  Torna o preenchimento obrigatório em formulários.
  ```html
  <input type="text" required>
  ```

- **autocomplete**  
  Controla o preenchimento automático.
  ```html
  <input type="text" autocomplete="off">
  ```

- **min** e **max**  
  Definem valores mínimo e máximo para campos numéricos ou datas.
  ```html
  <input type="number" min="1" max="10">
  <input type="date" min="2025-01-01" max="2025-12-31">
  ```

- **step**  
  Define o intervalo de incremento para campos numéricos.
  ```html
  <input type="number" step="5">
  ```

- **multiple**  
  Permite selecionar múltiplos arquivos ou opções.
  ```html
  <input type="file" multiple>
  <select multiple>
    <option>Opção 1</option>
    <option>Opção 2</option>
  </select>
  ```

- **pattern**  
  Define uma expressão regular para validação de campos.
  ```html
  <input type="text" pattern="[A-Za-z]{3,}">
  ```

- **autofocus**  
  Faz o campo receber foco automaticamente ao carregar a página.
  ```html
  <input type="text" autofocus>
  ```

- **download**  
  Indica que o link fará download do arquivo.
  ```html
  <a href="arquivo.pdf" download>Baixar PDF</a>
  ```

- **rel**  
  Define a relação entre o documento atual e o link.
  ```html
  <a href="https://exemplo.com" rel="noopener noreferrer">Abrir site</a>
  ```

- **target**  
  Define onde abrir o link (ex: nova aba).
  ```html
  <a href="https://exemplo.com" target="_blank">Abrir em nova aba</a>
  ```

Exemplo básico:
```html
<!DOCTYPE html>
<html lang="pt-br">
  <head>
    <meta charset ="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, intial-scale=1.0">
    <title>`**Minha Página</title>
  </head>
  <body>
    <h1>Bem-vindo!</h1>
    <p>Este é um parágrafo.</p>
    <a href="https://www.exemplo.com">`**Visite um site</a>
  </body>
</html>
```