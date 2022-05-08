Universidade Aberta do Brasil
================
Anderson Fonseca

# Introdução

Universidade Aberta do Brasil (UAB) é um programa para universalizar o
ensino superior no país. Com aulas online é possível levar para um maior
número de cidades e em lugares mais remotos, além de ser mais acessível
para as pessoas que trabalham. Com tamanha importância é de interesse
público ter algumas informações a respeito do programa, como: Quantas
cidades são atendidas? Qual tipo de curso é mais oferecido? Existe
diferença dos tipos de cursos oferecidos em cada região? Quais são os
estados em que mais pessoas se formam? Qual o percentual de desistência?
Entre outras questões. Para tentar responde-las utilizarei uma base de
dados com 6666 observações sobre a UAB nos anos de 2017, 2018, 2019 e
2020, obtido em:
<https://dados.gov.br/dataset/2017-a-2020-programa-universidade-aberta-do-brasil-uab1>

Segundo este conjunto de dados, a UAB atendeu 853 municípios nos 26
estados e o Distrito Federal nos 4 anos citados.

# Resultados

![**Figura 1:** Percentual de estudantes cursando a UAB por
região](UAB_files/figure-gfm/unnamed-chunk-3-1.png)

A região com número de estudante é a Nordeste com praticamente o dobro
da segunda maior, a Sudeste. Seguidas das regiões Sul, Centro-Oeste e
Norte, estas 3 somadas tem menos estudantes na UAB que a região
Nordeste.

![**Figura 2:** Quantidade de municipios com cursos da UAB por
região](UAB_files/figure-gfm/unnamed-chunk-5-1.png)

A região com maior número de municípios atendidos pela UAB é a região
Nordeste, com 264, seguidos da Sudeste, Sul, Centro-oeste e Norte.

![**Figura 3:** Percentual de cursos com oferta ativa na UAB por
região](UAB_files/figure-gfm/unnamed-chunk-6-1.png)

A região nordeste também lidera o ranking de percentual de cursos
ativos, com aproximadamente 40%, mais que as regiões Sul, Centro-oeste e
Norte somadas. E em segundo lugar está a região Sudeste.

![**Figura 4:** Percentual do tipo de curso na
UAB](UAB_files/figure-gfm/unnamed-chunk-7-1.png)

O curso mais comum é de Licenciatura com a aproximadamente 47%, seguido
de Especialização com 42%, portanto 89% dos cursos da UAB são de
Licenciatura ou Especialização. Os menos cursados são os cursos de
Aperfeiçoamento.

![**Figura 5:** Percentual do tipo de curso dividido por
região](UAB_files/figure-gfm/unnamed-chunk-8-1.png)

Na Figura 5 é possível observar que os tipos de cursos apresentam
frequências diferentes a depender da região. Nas regiões Norte e
Nordeste os cursos de licenciaturas são os predominantes, enquanto nas
demais regiões são os cursos de especialização. Os cursos de
aperfeiçoamento só tiveram na região Nordeste.

![**Figura 6:** Proporção de estudantes por tipo de curso em cada
ano](UAB_files/figure-gfm/unnamed-chunk-9-1.png)

Os cursos de Licenciatura e Especialização tinham o mesmo percentual de
estudantes em 2017 (44%), mas o percentual de estudantes nos cursos de
licenciatura aumentou enquanto os de especialização reduziram, tendo a
maior diferença em 2020, com 54% e 39%.

![**Figura 7:** Quantidade de municípios com curso abertos em cada ano
por região](UAB_files/figure-gfm/unnamed-chunk-10-1.png)

Houve uma queda no número de municípios ofertando novos cursos em 2018 e
2019, mas em 2020 voltou a um patamar próximo ao de 2017. A região
Nordeste perdeu o primeiro lugar em 2018 mas retornou em 2020.

![**Figura 8:** Percentual de cursos para formação de professores por
região](UAB_files/figure-gfm/unnamed-chunk-12-1.png)

Os cursos para formação de professores são maiorias em todas as regiões.
A região Norte lidera o ranking, com 83% dos cursos da região sendo para
formar professores. Enquanto na região Sul esse percentual é de 72%.
Mostrando uma diferença entre as regiões.

![**Figura 9:** Percentual de cursos com mais formados do que
desvinculados por região](UAB_files/figure-gfm/unnamed-chunk-14-1.png)

Em 39% dos cursos da região Sul teve mais estudantes se formados do que
desvinculados (desistência oficial do curso), esse é o maior percentual,
seguido da região Centro-Oeste com 33%, em último lugar aparece a região
Norte com 22%. Mais uma evidência da discrepância entre as regiões.

# Conclusão

A Universidade Aberta do Brasil tem papel fundamental na sociedade
brasileira, tornando mais fácil atingir o nível superior. E este
relatório trouxe a luz algumas informações importantes a respeito do
programa, explorando as diferenças entre as regiões e deixa como
trabalho futuro a construção de um *dashboard* com os principais
gráficos e presença de mapas interativos para visualizar o comportamento
de algumas variáveis de acordo com as unidades federativas da união.
