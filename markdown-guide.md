# O que é Markdown?
Markdown é uma linguagem de marcação leve que você pode usar para adicionar elementos de formatação a documentos de texto simples. Criado por John Gruber em 2004, Markdown é agora uma das linguagens de marcação mais populares do mundo.

# Headings (Títulos)
Para criar um título, adicione sinais numéricos (#) na frente de uma palavra ou frase. O número de sinais numéricos que você usa deve corresponder ao nível do título.
> # Heading level 1
> ## Heading level 2
> ### Heading level 3
> #### Heading level 4
> ##### Heading level 5
> ###### Heading level 6

# Sintaxe Alternativa
> Heading level 1
> ===============

> Heading level 2
> ---------------

# Parágrafos
Para criar parágrafos, use uma linha em branco para separar uma ou mais linhas de texto.

# Quebras de linha
Para criar uma quebra de linha, termine uma linha com dois ou mais espaços e digite <Enter>.

# Ênfase
Você pode adicionar ênfase colocando o texto em negrito ou itálico.

## Negrito
Para texto em negrito, adicione dois asteriscos ou sublinhados antes e depois de uma palavra ou frase. Para colocar em negrito o meio de uma palavra para dar ênfase, adicione dois asteriscos sem espaços ao redor das letras.

Eu adoro **texto em negrito**.

Eu adoro __texto em negrito__.

Amor **é** negrito.

## Itálico
Para colocar o texto em itálico, adicione um asterisco ou sublinhado antes e depois de uma palavra ou frase. Para colocar em itálico o meio de uma palavra para dar ênfase, adicione um asterisco sem espaços ao redor das letras.

Texto em itálico é o *miado do gato*.

Um *gato* miando

## Negrito e Itálico
Para enfatizar o texto com negrito e itálico ao mesmo tempo, adicione três asteriscos ou sublinhados antes e depois de uma palavra ou frase. Para colocar em negrito e itálico no meio de uma palavra para dar ênfase, adicione três asteriscos sem espaços ao redor das letras.

Este texto é ***realmente importante***.

Este texto é ___realmente importante___.

Este texto é __*realmente importante*__.

Este texto é **_realmente importante_**.

Este texto é __*realmente importante*__.

Este texto é realmente ***muito*** importante.

# Citações em bloco
Para criar um blockquote, adicione um > na frente de um parágrafo.

> Dorothy a seguiu por muitas das belas salas de seu castelo.

## Citações em bloco com vários parágrafos
Citações em bloco podem conter vários parágrafos. Adicione um> nas linhas em branco entre os parágrafos.

> Dorothy a seguiu por muitas das belas salas de seu castelo.
>
> A Bruxa mandou que ela limpasse os potes e chaleiras e varrasse o chão e mantivesse o fogo alimentado com lenha.

## Citações em bloco aninhados
Citações em bloco podem ser aninhados. Adicione um >> na frente do parágrafo que deseja aninhar.

> Dorothy a seguiu por muitas das belas salas de seu castelo.
>
>> A Bruxa mandou que ela limpasse os potes e chaleiras e varrasse o chão e mantivesse o fogo alimentado com lenha.

## Citações em bloco com outros elementos
Citações em bloco podem conter outros elementos formatados em Markdown. Nem todos os elementos podem ser usados - você precisará experimentar para ver quais funcionam.

> #### Os resultados trimestrais estão ótimos!
>
> - A receita estava fora do gráfico.
> - Os lucros foram maiores do que nunca.
>
> *Tudo* está indo de acordo com o **plano**.

# Listas
Você pode organizar itens em listas ordenadas e não ordenadas.

## Listas Ordenadas
Para criar uma lista ordenada, adicione itens de linha com números seguidos de pontos. Os números não precisam estar em ordem numérica, mas a lista deve começar com o número um.

1. Primeiro item
2. Segundo item
3. Terceiro item
     1. Item recuado
     2. Item recuado
4. Quarto item

## Listas não ordenadas
Para criar uma lista não ordenada, adicione travessões (-), asteriscos (*) ou sinais de adição (+) na frente dos itens de linha. Recue um ou mais itens para criar uma lista aninhada.

- Primeiro item
- Segundo item
- Terceiro item
     - Item recuado
     - Item recuado
- Quarto item

## Adicionando Elementos em Listas
Para adicionar outro elemento em uma lista enquanto preserva a continuidade da lista, indente o elemento quatro espaços ou uma tabulação, como mostrado nos exemplos a seguir.

### Parágrafos
* Este é o primeiro item da lista.
* Aqui está o segundo item da lista.

    Preciso adicionar outro parágrafo abaixo do segundo item da lista.

* E aqui está o terceiro item da lista.

### Citações em bloco
* Este é o primeiro item da lista.
* Aqui está o segundo item da lista.

     > Um blockquote ficaria ótimo abaixo do segundo item da lista.

* E aqui está o terceiro item da lista.

### Blocos de Código
Os blocos de código são normalmente recuados quatro espaços ou uma guia. Quando eles estiverem em uma lista, recue oito espaços ou duas tabulações.

1. Abra o arquivo.
2. Encontre o seguinte bloco de código na linha 21:

        <html>
            <head>
                <title> Teste </title>
            </head>

3. Atualize o título para corresponder ao nome do seu site.

### Imagens

1. Abra o arquivo que contém o mascote do Linux.
2. Maravilhe-se com sua beleza.

    ![Tux, o mascote do Linux](/markdown-guide/tux.png)

3. Feche o arquivo. 

### Listas
Você pode aninhar uma lista não ordenada em uma lista ordenada ou vice-versa.

1. Primeiro item
2. Segundo item
3. Terceiro item
    - Item recuado
    - Item recuado
4. Quarto item

# Código
Para denotar uma palavra ou frase como código, coloque-a entre crases (`).

No prompt de comando, digite `nano`.

## Escapando Backticks
Se a palavra ou frase que você deseja denotar como código inclui um ou mais crases, você pode fazer o escape colocando a palavra ou frase entre crases duplos (``).

`` Use `code` em seu arquivo Markdown``

## Blocos de Código
Para criar blocos de código, indente cada linha do bloco em pelo menos quatro espaços ou uma tabulação.

    <html>
        <head>
        </head>
    </html>

# Regras horizontais
Para criar uma régua horizontal, use três ou mais asteriscos (***), travessões (---) ou sublinhados (___) em uma linha.

***
---
___

# Links
Para criar um link, coloque o texto do link entre colchetes (por exemplo, [texto link]) e siga-o imediatamente com o URL entre parênteses (por exemplo, (https://duckduckgo.com)).

Meu mecanismo de pesquisa favorito é [Duck Duck Go] (https://duckduckgo.com).

# Adicionando Títulos
Você pode opcionalmente adicionar um título para um link. Isso aparecerá como uma dica de ferramenta quando o usuário passar o mouse sobre o link. Para adicionar um título, coloque-o entre parênteses após o URL.

Meu mecanismo de pesquisa favorito é [Duck Duck Go](https://duckduckgo.com "O melhor mecanismo de pesquisa para privacidade").

# URLs e endereços de e-mail
Para transformar rapidamente um URL ou endereço de e-mail em um link, coloque-o entre colchetes angulares.

<https://www.markdownguide.org>

<fake@example.com>

# Links de formatação
Para enfatizar os links, adicione asteriscos antes e depois dos colchetes e parênteses. Para denotar links como código, adicione crases entre colchetes.

Eu amo apoiar a **[EFF](https://eff.org)**.

Este é o *[Guia de marcação](https://www.markdownguide.org)*.

Veja a seção em [`código`](#código).

# Links de estilo de referência
Os links de estilo de referência são um tipo especial de link que torna os URLs mais fáceis de exibir e ler no Markdown. Os links de estilo de referência são construídos em duas partes: a parte que você mantém alinhada com o seu texto e a parte que você armazena em algum outro lugar do arquivo para manter o texto fácil de ler.

## Imagens
Para adicionar uma imagem, adicione um ponto de exclamação (!), Seguido pelo texto alternativo entre colchetes e o caminho ou URL para o recurso de imagem entre parênteses. Você pode opcionalmente adicionar um título após o URL entre parênteses.

![Jardins mágicos da Filadélfia. Este lugar era tão legal!](/markdown-guide/philly-magic-garden.jpg "Jardins mágicos da Filadélfia")

## Vinculando Imagens
Para adicionar um link a uma imagem, coloque o Markdown da imagem entre colchetes e, a seguir, adicione o link entre parênteses.

[![Uma velha rocha no deserto](/markdown-guide/shiprock.jpg "Shiprock, Novo México por Beau Rogers")](https://www.flickr.com/photos/beaurogers/31833779864/in/photolist-Qv3rFw-34mt9F-a9Cmfy-5Ha3Zi-9msKdv-o3hgjr-hWpUte-4WMsJ1-KUQ8N-deshUb-vssBD-6CQci6-8AFCiD-zsJWT-nNfsgB-dPDwZJ-bn9JGn-5HtSXY-6CUhAL-a4UTXB-ugPum-KUPSo-fBLNm-6CUmpy-4WMsc9-8a7D3T-83KJev-6CQ2bK-nNusHJ-a78rQH-nw3NvT-7aq2qf-8wwBso-3nNceh-ugSKP-4mh4kh-bbeeqH-a7biME-q3PtTf-brFpgb-cg38zw-bXMZc-nJPELD-f58Lmo-bXMYG-bz8AAi-bxNtNT-bXMYi-bXMY6-bXMYv)

# Personagens em fuga
Para exibir um caractere literal que seria usado para formatar texto em um documento Markdown, adicione uma barra invertida (\) na frente do caractere.

\* Sem a barra invertida, isso seria um marcador em uma lista não ordenada.

# Tabelas
Para adicionar uma tabela, use três ou mais hifens (---) para criar o cabeçalho de cada coluna e use barras verticais (|) para separar cada coluna. Opcionalmente, você pode adicionar tubos em qualquer extremidade da tabela.

| Sintaxe | Descrição |
| ----------- | ----------- |
| Cabeçalho | Título |
| Parágrafo | Texto |

## Alinhamento
Você pode alinhar o texto nas colunas à esquerda, à direita ou ao centro adicionando dois-pontos (:) à esquerda, à direita ou em ambos os lados dos hifens na linha do cabeçalho.

| Sintaxe | Descrição | Texto de teste |
| :--- | :----: | ---: |
| Cabeçalho | Título | Aqui está |
| Parágrafo | Texto | E mais |

# Caracter que você pode escapar
Você pode usar uma barra invertida para escapar dos caracteres a seguir.

| Carater | Nome |
| :-----: | :---- |
| \ | barra invertida |
| ` | crase |
| * | asterisco |
| _ | sublinhado |
| {} | chaves |
| [] | colchetes |
| <> | colchetes angulares |
| () | parênteses |
| # | sinal de libra |
| + | sinal de mais |
| - | sinal de menos (hífen) |
| . | ponto |
| ! | ponto de exclamação |
| \| | tubo (veja também tubo de escape nas tabelas) |


# Comentários
Você pode inserir comentários em seu arquivo, utilizando dos (\<!---) para iniciar o cometário e (--->) no final do comentário.

<!--- Este é um comentário e não deve ser exibido no corpo do arquivo.--->

# Fonte
https://www.markdownguide.org/basic-syntax
