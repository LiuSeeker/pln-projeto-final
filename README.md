# Projeto final PLN - Sumarizador de documentos e tradução de sumarização

### Arthur Rizzo e Vitor Liu

Este projeto aborda duas áreas de alta relevância universo de Processamento de Linguagem Natural(PLN). São elas a sumarização e a tradução. Os próximos parágrafos irão resumir como essas áreas se conectam com o PLN e porque são tão estudadas. Também serão tratadas algumas das técnicas utilizadas ao longo do estudo. 

A sumarização automática de documentos é uma técnica muito importante na área de Processamento de Linguagem Natural pois permite gerar uma representação resumida do conteúdo dos documentos. Assim, após a geração de sumários, não é totalmente necessário tratar documentos inteiros, mas apenas um resumo destes.

Tratando-se de textos, existem dois tipos de sumarização: a sumarização extrativa e a sumarização abtrativa. A extrativa seleciona frases ou pequenas partes do documento para ser o sumário; já a abstrativa gera frases baseadas no conteúdo do texto.

Existem diversos métodos para a realização da sumarização. Porém, o método escolhido é baseado no embedding de sentenças e realizando o clustering entre as sentenças.

O embedding é a transformação de algo em vetores. Isso possibilita desde a realização cálculos entre vetores até a utilização de modelos neurais. Na área de PLN, é commum gerar embeddings de palavras, mas não se limita a este.

O clustering é a prática de agrupar objetos baseado em determinadas caracteristicas. Para isso, há vários algoritmos que realizam a clusterização, como o algoritmo baseado em hierarquia e o algoritmo k-means.

A tradução também é uma técnica muito importante na área de PLN pois pode deixar textos mais acessíveis para línguas não tão populares e, do contrário, aproximar e popularizar textos e culturas de línguas menos conhecidas.

Como pode-se notar, por sí só ambas as áreas, sumarização e tradução, são ferramentas poderosas. Curiosamente, somadas, podem propiciar soluções para problemas ainda mais complexos de diversas naturezas e aplicações. Dentre elas, uma forma de categorizar documentos estrangeiros por tópico e seleção de informação em língua estrangeira. Graças aos avanços acadêmicos e práticos nas diversas áreas do PLN, os modelos que estão sendo desenvolvidos estão se tornando cada vez mais certeiros e, isso é bastante motivante.

Esse projeto tem como objetivo realizar melhorias e implementar novos recursos ao [projeto realizado anteriormente](https://docs.google.com/document/d/13gVb1lcceNGXlPpneqkVGrRjgrEUrhPk). Portanto, explicaremos o novo processo de sumarização extrativa por clustering baseado no embedding de sentenças pelo modelo BERT e a implementação da tradução da sumarização. Além disso, explicaremos o funcionamento do modelo de tradução XLM utilizado e o porquê de escolhermos esse modelo.

O resultado da implementação está no arquivo `Projeto Final.ipynb`.