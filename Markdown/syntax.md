# **Markdown** 
É uma linguagem de marcação que converte o texto em sintonia ao 'HTML' válido. É frequentemente utilizado para confeccionar arquivos README e documentar informações importantes. A documentação da linguagem pode ser acessada [aqui](https://www.markdownguide.org/basic-syntax/), ao passo que o tutorial para utilização no *GitHub* está disponível [neste repositório](https://docs.github.com/en/get-started/writing-on-github).

## Headings
```md
(MD)
# Heading
## Heading 2
### Heading 3
#### Heading 4
##### Heading 5
###### Heading 6

(HTML)
<h1> Heading </h1>
<h2> Heading 2 </h2>
```
## Emphasis
```md
Itálico: *asterisks* ou _underscores_.

Negrito: **asterisks** ou __underscores__.

Combinação: **asterisks e _underscores_**.

Riscar: ~~scratch~~.
```
## Paragraph and Line Breaks
```md
(MD)
Para criar um parágrafo, deve-se utilizar uma linha vazia 
para separar as linhas de texto. 
Por outro lado, para criar uma quebra de linha, 
basta finalizar a linha com um ou mais espaços e apertar enter.

(HTML) 
<p> Paragraph </p>
<br>
```
## Blockquote
```md
>
> -
>>
```
## Lists
```md
• Ordenada 
(MD)
1.
2.
3.

(HTML)
<ol>
	<li> Item 1<li>
	<li> Item 2 <li>
	<li> Item 3 <li>
</ol>

• Não Ordenada
(MD)
- Item
- Item 2
- Item 3

(HTML)
<ul>
	<li> Item 1 <li>
	<li> Item 2 <li>
	<li> Item 3 <li>
</ul>

Para iniciar com um número, use "\".
- 1968\.
```
## Images
```md
(MD)
![Nome alternativo](imagelink.com)
```
## Links, Email Adresses and URLs
```md
(MD)
[Nome do Link](link.com)

<fake@example.com>

<https://www.markdownguide.org>

(HTML)
<a href="https://www.example.com"> Nome do Link </a>
```
## Tables
```md
| Heading 1 | Heading 2 | Heading 3 |
|---|---|---|
| col1 | col2 | col3 |
| col1 | col2 | col3 |
```
## Task List
```md
[x] Write the post
[ ] Update the website
[ ] Contact the user
```
