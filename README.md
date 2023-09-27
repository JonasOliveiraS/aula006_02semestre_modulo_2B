# aula006_02semestre_modulo_2B
Atividade Prática 6 - Fundamentos sobre estilos.

Atividade Prática
Atividade Prática 6 - Fundamentos sobre estilos.

Título da Prática: Manipulando o arquivo CSS.

Objetivos: Compreender a utilização do arquivo CSS.

MATERIAIS, MÉTODOS E FERRAMENTAS: Visual Studio Code ou Bloco de notas do Windows.

Atividade Prática

1º Passo: Leia atentamente o texto abaixo:

O CSS pode ser aplicado nos elementos HTML do site de quatro maneiras:

1. Um arquivo CSS externo é incluído no HEAD do arquivo HTML usando uma tag de link.

2. Tag de estilo no HEAD do documento HTML, especialmente no caso de soluções especiais para páginas individuais.

3. Importar um arquivo CSS externo dentro da tag de estilo ou em outro arquivo CSS.

4. CSS embutido: atributo de estilo em tag HTML.


Integrar CSS com arquivo externo

Esta é provavelmente a melhor maneira de incluir CSS em HTML. Um site geralmente consiste em muitas páginas. Por isso, faz sentido salvar as instruções de design em um arquivo separado.

Isso permite uma separação clara entre conteúdo e design e facilita a manutenção. O arquivo exportado é simplesmente vinculado ao documento HTML.

Salve a folha de estilo externa com uma extensão .css e use uma tag de link para incluí-la em seu arquivo HTML. No exemplo, o arquivo CSS é denominado estilo.css.


O atributo rel define o tipo de relacionamento lógico e href refere-se ao arquivo CSS a ser incorporado. Observe que o elemento link também pode ter outros atributos. Por exemplo, com a propriedade media=“print” você especifica que a folha de estilo é usada apenas na visualização de impressão. A folha de estilo externa não contém nenhuma tag HTML, apenas o respectivo seletor e chaves com as declarações, conforme o exemplo a seguir:


2º Passo:

O HTML estrutura sites e mostra uma representação significativa - nem mais nem menos. CSS - Cascading Style Sheets - “embeleza” o HTML com regras para fonte, cor e layout e substitui a aparência simples do HTML.

O CSS não é apenas responsável por páginas da web, mas também funciona em outras linguagens de marcação, como XML, SVG e RSS, além de descrever saída de impressão e fala.

No passado, o navegador enviava uma solicitação HTTP (Hypertext Transfer Protocol) para o servidor web para cada recurso externo – sejam imagens, arquivos CSS ou Javascript. Cada solicitação tinha uma pequena sobrecarga e atrasava a construção da página.

Daí o conselho de combinar arquivos CSS individuais em um arquivo CSS. Caso contrário, cada arquivo CSS individual se tornaria uma solicitação HTTP.

Hoje, os servidores e navegadores modernos usam o protocolo HTTP/2 mais recente, no qual o servidor envia vários arquivos ao mesmo tempo em uma conexão. Se os sites forem servidos com o protocolo HTTP 2, vários arquivos CSS individuais fornecem uma visão geral melhor, as alterações são mais fáceis e as fontes de erro se abrem melhor.

3º Passo:

Utilize o código de HTML de referência abaixo para aplicar os estilos de acordo com as recomendações a seguir:


Implemente o arquivo CSS, para manipular as seguintes tags <body>, <h1> e <p>. Segue abaixo uma imagem de referência para que você consiga visualizar como o seu projeto poderá ficar.


Observe que você tem autonomia para formatar o texto (fonte, tamanho, cor, etc.) da maneira que você achar melhor. Nessa atividade você será avaliado justamente sobre a aplicação dos princípios de CSS que foram abordados ao longo da aula. Nessa tarefa, você deverá construir e enviar APENAS o arquivo de CSS ou até mesmo o print do código.



Comentários e conclusões:

1. O que aprendeu com esta atividade?

2. Tudo funcionou como o esperado?

3. Quais foram as principais dificuldades?
