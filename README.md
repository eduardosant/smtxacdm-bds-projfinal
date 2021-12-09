# Análise dos microdados do ENEM 2019 em Alagoas

## Introdução

O estado de Alagoas fica na região Nordeste do Brasil. Faz fronteira com os estados de Pernambuco a norte e nordeste, a sul com o estado de Sergipe e a sudoeste, numa pequena área fronteiriça, com o estado da Baía. O rio São Francisco que desagua em Alagoas delimita a zona sul do estado com o Sergipe. A capital do estado de Alagoas é Maceió. Tem uma superfície de 27.830,656 km² de superfície, e é o segundo mais pequeno estado do Brasil só ultrapassado pelo Sergipe. Tem uma população estimada de 3.365.351 habitante em 2021, segundo o  Instituto Brasileiro de Geografia e Estatística e uma densidade demográfica de 112,33 hab/km². Possui o menor índice de desenvolvimento humano do Brasil com 0,6310. O nome do estado deriva das inúmeras lagoas provocadas pelas marés, que podem inundar até 15 km para o interior, a partir da costa perto de Maceió.

### Contextualização histórica, política, social e econômica

Alguns aspectos pertinentes sobre o desenvolvimento do estado de Alagoas são destacados por Carvalho (2019, p. 353), tais como:

- Nos anos 2000-2018, a economia alagoana, cada vez mais integrada à economia brasileira, reafirmou seu caráter urbano, centralizando suas principais atividades econômicas nos setores de comércio, serviços e administração pública. As atividades comerciais e de serviços cresceram pelo consumo popular, estimulado pelas políticas de transferência de renda, principalmente da previdenciária e do programa Bolsa Família. Neste período, a sociedade alagoana, mesmo ocupando uma posição inferior na média nacional, alcançou uma melhoria nos seus indicadores sociais, elevando o nível educacional, a renda média, ampliando o acesso a bens de consumo e reduzindo o grau de pobreza da população que se tornou sua marca histórica mais conhecida.

- Nenhum aspecto das mudanças regionais no período 2001-2014 teve mais destaque, nos meios de comunicação social e na produção acadêmica, do que a queda da pobreza e da miséria no âmbito regional. Neste período, os números foram reduzidos de maneira expressiva: quinze milhões de pobres e dez milhões de extremamente pobres a menos no Nordeste. No caso alagoano, a queda foi relativamente menor que a nordestina, mas, ainda assim, acompanhou a tendência regional (INSTITUTO DE PESQUISA ECONÔMICA APLICADA, 2015).

- Essa tendência é confirmada pelos indicadores da Pesquisa Nacional por Amostra de Domicílios Contínua (2019), revelando como a sociedade e a economia alagoana, na segunda década do século XXI, encontravam-se bem diferentes do ano 2000, com uma população mais urbanizada, menos pobre, com um nível maior de escolaridade e mais conectada, contemplando novas situações, a exemplo do número de residências com energia que saltou de 668 mil, em 2006, para um milhão em 2017. A universalização da energia elétrica, ao mesmo tempo em que permitiu a ampliação do consumo pela sociedade, também possibilitou a esta ficar mais antenada. Em 2016, 61% dos nordestinos e 59% dos alagoanos se conectavam à Internet; o número de celulares cresceu no “boom do consumo” de 700 mil, em 2005, para 4,2 milhões em 2014; e, mesmo caindo para 2,9 milhões em 2019, continuou a fazer parte do cotidiano da maioria das famílias de baixa renda (AGÊNCIA NACIONAL DE TELECOMUNICAÇÕES, 2019).

- A queda da pobreza e a melhoria dos indicadores sociais nas áreas de educação e saúde fizeram com que, em 2010, o IDH-M subisse mais rapidamente em relação ao período 1991-2000. No entanto, Alagoas permaneceu como o mais baixo IDH-M do País, mesmo saindo do nível “baixo” para “médio” de desenvolvimento (PROGRAMA DAS NAÇÕES UNIDAS PARA O DESENVOLVIMENTO, 2013).

- Nos anos pós-Censo de 2010, Alagoas apresentou um processo de evolução positiva de seus indicadores sociais – analfabetismo, mortalidade infantil e expectativa de vida –, estes dois últimos sob a influência da melhoria de renda e da cobertura de 83% da população pelo SUS, apontando para uma possibilidade de convergência com os índices médios nordestinos, o que fazia antever um melhor resultado no IDH-M em 2020. No entanto, a pesquisa “Síntese de Indicadores Sociais 2018”, do IBGE, revelou que, em função da crise econômica do período recente, da deterioração do mercado de trabalho e da queda da renda, mais os cortes orçamentários federais, ocorreu um crescimento nacional da pobreza, entre os anos 2016 e 2017, rompendo com a série dos anos de redução desse fenômeno, fazendo o Nordeste voltar a ter 44,8% pobres e Alagoas alcançar 48,9% de pessoas de sua população vivendo abaixo da linha da pobreza (IBGE, 2018).

### Tema abordado

Ao analisar os microdados do Exame Nacional do Ensino Médio (ENEM) em Alagoas no ano de 2019 vale a pena considerar alguns pontos do Censo da Educação Básica (INSTITUTO NACIONAL DE ESTUDOS E PESQUISAS EDUCACIONAIS ANÍSIO TEIXEIRA, 2020) sobre o nível médio no referido ano:

- Em 2019, foram registradas 116.193 matrículas no ensino médio. Esse valor é 5,7% menor do que o número de matrículas registradas para o ano de 2015. O ensino médio não integrado à educação profissional apresentou uma redução de 10,8% no número de matrículas entre 2015 e 2019 e o ensino médio integrado à educação profissional apresentou um aumento de 67,0% no mesmo período.

- A rede estadual possui a maior participação na matrícula do ensino médio com 79,9% das matrículas, sendo seguida pela rede privada (13,2%). O percentual de matrículas da rede estadual manteve‐se estável entre 2015 e 2019. No mesmo período, a participação das matrículas das escolas da rede privada caiu 1,8 p.p.. Ao avaliar como o número de matrículas do ensino médio está distribuído em relação à localização, observa‐se que a maioria das matrículas (94,8%) do ensino médio está localizada em escolas urbanas e 99,5% das matrículas da zona rural são atendidas pela rede pública.

- As taxas de distorção do ensino médio são mais elevadas na rede pública do que na privada. Na rede pública, a maior distorção foi observada para a primeira série, com taxa de 41,5%. Similarmente ao ensino fundamental, para ambas as redes, os alunos do sexo masculino apresentaram taxas de distorção idade‐série maiores para todas as séries do ensino médio. A maior discrepância na taxa de distorção pode ser observada na primeira série da rede pública, que apresenta uma diferença de 13,1 p.p..

Outro instumento de grande importância é o Indicador de Nível Socioeconômico (Inse) do SAEB 2019 (BRASIL, 2021):

- O Sistema Nacional de Avaliação da Educação Básica (Saeb) é um sistema de avaliação externa em larga escala, composto por um conjunto de instrumentos, realizado periodicamente pelo Instituto Nacional de Estudos e Pesquisas Educacionais Anísio Teixeira (INEP), desde os anos 1990. Dentre os vários indicadores que podem ser produzidos com os dados coletados pelo Saeb, o que mensura as condições socioeconômicas dos estudantes se destaca na literatura educacional devido à sua estreita relação com as medidas de aprendizagem. O indicador de nível socioeconômico auxilia na identificação das desigualdades educacionais e pode orientar futuros investimentos que contribuam para uma sociedade mais igualitária.

- O Indicador de Nível Socioeconômico (Inse), construído pela Diretoria de Avaliação da Educação Básica (Daeb), com base nos resultados do questionário do estudante do Saeb, tem como objetivo contextualizar resultados obtidos em avaliações e exames aplicados por este instituto no âmbito da educação básica. Dessa forma, possibilita-se conhecer a realidade social de escolas e redes de ensino, bem como auxiliar na implementação, no monitoramento e na avaliação de políticas públicas, visando ao aumento da qualidade e da equidade educacional.

## Desenvolvimento

Os microdados do ENEM 2019 são o menor nível de desagregação de dados recolhidos por meio do exame. Eles atendem a demanda por informações específicas ao disponibilizar as provas, os gabaritos, as informações sobre os itens, as notas e o questionário respondido pelos inscritos no ENEM. Eles estão disponíveis na seção Acesso à Informação > Dados Abertos > Microdados > Enem no portal do Instituto Nacional de Estudos e Pesquisas Educacionais (INEP).

Devido à grande população do ENEM 2019, torna-se difícil a observação dos aspectos a serem estudados, de cada um dos elementos. Nessas circunstâncias, fizemos a seleção de uma amostra suficientemente representativa da população referente ao estado de Alagoas e, através da observação dessa amostra, estaremos aptos a analisar os resultados, da mesma forma que se estudássemos toda a população.

Após exploração inicial dos dados de candidatos inscritos para o ENEM 2019 no estado de Alagoas foram elegíveis para o estudo apenas os que realizaram completamente as provas. Excluindo os estudantes menores de 18 anos e que ainda não estavam no último ano do ensino médio, onde participaram do exame na condição de treineiros. Isso significa que, mesmo que ele obtenha boas notas no Enem, não poderá se matricular em uma instituição de Ensino Superior ou ter acesso a programas do Governo como SiSu, ProUni ou Fies.

Através da Estatística Descritiva ou Dedutiva pretendemos descrever e analisar a população determinada, sem pretensão de tirar conclusões de caráter mais genérico.

### Exploração inicial dos dados

#### Perfil dos inscritos

Em 2019 houveram 91.707 incrições para o ENEM no estado de Alagoas, sendo que 55.255 (60,25%) eram do sexo feminino e 36.452 (39,75%) do sexo masculino. As cidades alagoanas de Maceió e Arapiraca tiveram o maior número de inscritos, respectivamente com 34.635 (37,77%) e 9.738 (10,62%). Apenas 22.289 (24,30%) informaram o tipo de escola do ensino médio. Entre as inscrições femininas 31 (0,06%) eram gestantes. 549 (0,59%) pediram atendimento especializado (deficiência física, baixa visão, déficit de atenção, deficiência auditiva, deficiência mental, surdez, visão monocular, dislexia, autismo, cegueira, discalculia e outras deficiências). 106 (0,12%) pediram atendimento específico (lactante, gestante e idoso). 719 (0,78%) pediram recursos especializados e específicos para realização das provas (tempo adicional, sala de fácil acesso, auxílio para transcrição, auxílio para leitura, prova ampliada com fonte tamanho 18, apoio de perna e pé, mesa para cadeira de rodas, mesa e cadeira separada, prova superampliada com fonte tamanho 24, Tradutor-Intérprete Libras, leitura labial, sala especial até 20 participantes, medicamentos, medidor de glicose e/ou aplicação de insulina, atendimento pelo Nome Social, sala especial individual, sala reservada para acompanhantes, máquina Braile e/ou Reglete e Punção, prova em braille, mobiliário adequado para obeso e cadeira acolchoada). A faixa de idade variou em sua maioria dos 18 aos 19 anos (Gráfico 1). 8.862 (9,66%) estudantes participaram do exame na condição de treineiros.

| ![Histograma da idade dos inscritos no ENEM 2019 em Alagoas](https://user-images.githubusercontent.com/1895529/145264849-53b1930d-0849-4209-afe2-b287f3649767.png) |
|:--:|
| Gráfico 1 - Histograma da idade dos inscritos no ENEM 2019 em Alagoas. |


#### Perfil dos que realizaram completamente as provas

Apenas 68.750 (74,97%) do total de inscritos no ENEM 2019 em Alagoas realizaram as provas, sendo que 41.304 (60,08%) eram do sexo feminino e 27.446 (39,92%) do sexo masculino. As cidades alagoanas de Maceió e Arapiraca tiveram o maior número de inscritos, respectivamente com 26.322 (38,29%) e 7.364 (10,71%). Apenas 19.050 (27,71%) informaram o tipo de escola do ensino médio. Entre as inscrições femininas 11 (0.016%) eram gestantes. 422 (0,61%) pediram atendimento especializado (deficiência física, déficit de atenção, baixa visão, deficiência auditiva, deficiência mental, visão monocular, surdez, dislexia, autismo, discalculia, cegueira e outras deficiências). 42 (0,06%) pediram atendimento específico (lactante, gestante e idoso). 529 (0,77%) pediram recursos especializados e específicos para realização das provas (tempo adicional, auxílio para transcrição, auxílio para leitura, sala de fácil acesso, prova ampliada com fonte tamanho 18, apoio de perna e pé, mesa para cadeira de rodas, prova superampliada com fonte tamanho 24, mesa e cadeira separada, leitura labial, sala especial até 20 participantes, atendimento pelo Nome Social, medidor de glicose e/ou aplicação de insulina, medicamentos, Tradutor-Intérprete Libras, sala especial individual, sala reservada para acompanhantes, máquina Braile e/ou Reglete e Punção, prova em braille, mobiliário adequado para obeso e cadeira acolchoada). A faixa de idade variou em sua maioria dos 18 aos 19 anos (Gráfico 2). 7.588 (11,04%) estudantes participaram do exame na condição de treineiros.

| ![image](https://user-images.githubusercontent.com/1895529/145270277-10810f62-51ba-4298-9314-0c5d5f651f11.png) |
|:--:|
| Gráfico 2 - Histograma da idade dos inscritos no ENEM 2019 em Alagoas que realizaram completamente as provas. |

Média das notas(excluindo treineiros):

Segmentar as medianas das notas das provas por pefil socioeconônimo do INSE.

A média é usada para distribuições numéricas normais, que têm uma baixa quantidade de valores discrepantes.

A mediana é geralmente utilizada para retornar a tendência central para distribuições numéricas distorcidas.

O desvio padrão é uma medida que expressa o grau de dispersão de um conjunto de dados. Ou seja, o desvio padrão indica o quanto um conjunto de dados é uniforme. Quanto mais próximo de 0 for o desvio padrão, mais homogêneo são os dados.

Variância é uma medida de dispersão e é usada também para expressar o quanto um conjunto de dados se desvia da média.

O desvio padrão (DP) é definido como a raiz quadrada da variância (V).

A vantagem de usar o desvio padrão ao invés da variância é que o desvio padrão é expresso na mesma unidade dos dados, o que facilita a comparação.


### Notas das provas realizadas e o Inse

Organizamos as notas de 61.162 (66,69%) não inscritos como treineiros no ENEM 2019 em Alagoas por muncípio e que realizaram completamente as provas, relacionando com os níveis do Inse para análise.

#### Simetria das notas

As notas das provas de Ciências da Natureza, Ciências Humanas, Linguagens e Códigos, e Redação tiveram uma distribuição simétrica, a linha da mediana no centro do retângulo. As notas da prova de Matemátiva tiveram uma distribuição assimétrica positiva, a linha da mediana está próxima ao primeiro quartil. (Gráfico 3) A mediana é a medida de tendência central mais indicada quando os dados possuem distribuição assimétrica, uma vez que a média aritmética é influenciada pelos valores extremos.

|![image](https://user-images.githubusercontent.com/1895529/145284869-88120375-23d6-4d2a-999b-e488590c776e.png) ![image](https://user-images.githubusercontent.com/1895529/145285466-7051b4a8-2168-4e62-af31-e62f2d749f30.png) ![image](https://user-images.githubusercontent.com/1895529/145285947-806ff6ae-b2e1-447f-812d-79013315e7b0.png) ![image](https://user-images.githubusercontent.com/1895529/145286074-2ca47d12-8f46-4e78-abe5-8957be9130cc.png) ![image](https://user-images.githubusercontent.com/1895529/145287218-66300274-5449-44f9-a4ce-6dc6d83b7dda.png)|
|:--:|
|Gráfico 3 - Boxplot das notas nas provas (Ciências da Natureza, Ciências Humanas, Linguagens e Códigos, Matemática e Redação) do ENEM 2019 em Alagoas.|

#### Níveis socioeconômicos

##### Nível I

Temos 6.894 (11,27%) dos não inscritos como treineiros no ENEM 2019 em Alagoas e que realizaram completamente as provas enquadrados no Nível I do Inse. Este é o nível inferior da escala, no qual os estudantes têm dois ou mais desvios-padrão abaixo da média nacional do Inse. Considerando a maioria dos estudantes, o pai/responsável não completou o 5º ano do ensino fundamental e a mãe/responsável tem o 5º ano do ensino fundamental incompleto ou completo. A maioria dos estudantes deste nível possui uma geladeira, um ou dois quartos, uma televisão e um banheiro. Mas não possui muitos dos bens e serviços pesquisados (i.e., computador, carro, wi-fi, mesa para estudar, garagem, microondas, aspirador de pó, máquina de lavar roupa e freezer).

O Gráfico 4 apresenta as medidas de tendência central para as notas das provas do ENEM 2019 no Nível I do Inse em Alagoas.:
- A média aritmética de 437,32 para Ciências da Natureza, com uma distribuição simétrica;
- A média aritmética de 464,19 para Ciências Humanas, com uma distribuição simétrica;
- A média aritmética de 482,75 para Linguagens e Códigos, com uma distribuição simétrica;
- A mediana de 449,90 para Matemática, com uma distribuição assimétrica;
- A média aritmética de 517,38 para Redação, com uma distribuição simétrica.

|![image](https://user-images.githubusercontent.com/1895529/145312339-7c911eb0-61d4-4eef-a8c9-bf6b7279bd83.png)|
|:--:|
|Gráfico 4 - Notas das provas do ENEM 2019 no Nível I do Inse em Alagoas.|

##### Nível II

Temos 9.106 (14,89%) dos não inscritos como treineiros no ENEM 2019 em Alagoas e que realizaram completamente as provas enquadrados no Nível II do Inse. Neste nível, os estudantes estão entre um e dois desvios-padrão abaixo da média nacional do Inse. Considerando a maioria dos estudantes, a mãe/responsável e/ou o pai/responsável tem o 5º ano do ensino fundamental incompleto ou completo. A maioria possui uma geladeira, um ou dois quartos, uma televisão e um banheiro. Mas não possui muitos dos bens e serviços pesquisados, exceto uma parte dos estudantes deste nível passa a ter freezer, máquina de lavar roupa e três ou mais quartos para dormir em sua casa.

O Gráfico 5 apresenta as medidas de tendência central para as notas das provas do ENEM 2019 no Nível II do Inse em Alagoas.:
- A média aritmética de 437,80 para Ciências da Natureza, com uma distribuição simétrica;
- A média aritmética de 465,01 para Ciências Humanas, com uma distribuição simétrica;
- A média aritmética de 484,05 para Linguagens e Códigos, com uma distribuição simétrica;
- A mediana de 450,40 para Matemática, com uma distribuição assimétrica;
- A média aritmética de 520,39 para Redação, com uma distribuição simétrica.

|![image](https://user-images.githubusercontent.com/1895529/145315313-7510478e-1d0b-4ad8-8ab3-0fd5a9638216.png)|
|:--:|
|Gráfico 5 - Notas das provas do ENEM 2019 no Nível II do Inse em Alagoas.|

##### Nível III

Temos 375 (0,61%) dos não inscritos como treineiros no ENEM 2019 em Alagoas e que realizaram completamente as provas enquadrados no Nível III do Inse. Neste nível, os estudantes estão entre meio e um desvio-padrão abaixo da média nacional do Inse. Considerando a maioria dos estudantes, a mãe/responsável e o pai/responsável têm o ensino fundamental incompleto ou completo e/ou ensino médio completo. A maioria possui uma geladeira, um ou dois quartos, uma televisão, um banheiro, wi-fi e máquina de lavar roupas, mas não possui computador, carro, garagem e aspirador de pó. Parte dos estudantes passa a ter também freezer e forno de micro-ondas.

O Gráfico 6 apresenta as medidas de tendência central para as notas das provas do ENEM 2019 no Nível III do Inse em Alagoas.:
- A média aritmética de 450,70 para Ciências da Natureza, com uma distribuição simétrica;
- A média aritmética de 479,57 para Ciências Humanas, com uma distribuição simétrica;
- A média aritmética de 505,48 para Linguagens e Códigos, com uma distribuição simétrica;
- A mediana de 465,70 para Matemática, com uma distribuição assimétrica;
- A média aritmética de 555,31 para Redação, com uma distribuição simétrica.

|![image](https://user-images.githubusercontent.com/1895529/145316841-52320cea-6670-47ae-9aa0-80fa05c57cc2.png)|
|:--:|
|Gráfico 6 - Notas das provas do ENEM 2019 no Nível III do Inse em Alagoas.|

##### Nível IV

Temos 423 (0,69%) dos não inscritos como treineiros no ENEM 2019 em Alagoas e que realizaram completamente as provas enquadrados no Nível IV do Inse. Neste nível, os estudantes estão até meio desvio-padrão abaixo da média nacional do Inse. Considerando a maioria dos estudantes, a mãe/responsável e o pai/responsável têm o ensino fundamental incompleto ou completo e/ou ensino médio completo. A maioria possui uma geladeira, um ou dois quartos, um banheiro, wi-fi, máquina de lavar roupas e freezer, mas não possui aspirador de pó. Parte dos estudantes deste nível passa a ter também computador, carro, mesa de estudos, garagem, forno de micro-ondas e uma ou duas televisões.

O Gráfico 7 apresenta as medidas de tendência central para as notas das provas do ENEM 2019 no Nível IV do Inse em Alagoas.:
- A média aritmética de 479,74 para Ciências da Natureza, com uma distribuição simétrica;
- A média aritmética de 506,29 para Ciências Humanas, com uma distribuição simétrica;
- A média aritmética de 527,18 para Linguagens e Códigos, com uma distribuição simétrica;
- A mediana de 517,60 para Matemática, com uma distribuição assimétrica;
- A média aritmética de 608,94 para Redação, com uma distribuição simétrica.

|![image](https://user-images.githubusercontent.com/1895529/145318682-ef595dc4-119f-43c1-ba2e-848a7583e84e.png)|
|:--:|
|Gráfico 7 - Notas das provas do ENEM 2019 no Nível IV do Inse em Alagoas.|

##### Nível V

Temos XXXXXXXXXXX dos não inscritos como treineiros no ENEM 2019 em Alagoas e que realizaram completamente as provas enquadrados no Nível V do Inse. Neste nível, os estudantes estão até meio desvio-padrão acima da média nacional do Inse. Considerando a maioria dos estudantes, a mãe/responsável tem o ensino médio completo
ou ensino superior completo, o pai/responsável tem do ensino fundamental completo até o ensino superior completo. A maioria possui uma geladeira, um ou dois quartos, um banheiro, wi-fi, máquina de lavar roupas, freezer, um carro, garagem, forno de micro-ondas. Parte dos estudantes deste nível passa a ter também dois banheiros.

O Gráfico 8 apresenta as medidas de tendência central para as notas das provas do ENEM 2019 no Nível V do Inse em Alagoas.:
- A média aritmética de 479,74 para Ciências da Natureza, com uma distribuição simétrica;
- A média aritmética de 506,29 para Ciências Humanas, com uma distribuição simétrica;
- A média aritmética de 527,18 para Linguagens e Códigos, com uma distribuição simétrica;
- A mediana de 517,60 para Matemática, com uma distribuição assimétrica;
- A média aritmética de 608,94 para Redação, com uma distribuição simétrica.

||
|:--:|
|Gráfico 8 - Notas das provas do ENEM 2019 no Nível IV do Inse em Alagoas.|

## Discussão

### Hipóteses levantadas

Perfil socioeconômico x Rendimento ENEM

### Direções para o órgão público que será dirigido

## Referências bibliográficas:

CARVALHO, Cícero Péricles de. Alagoas 2000-2018. Revista BNB Conjuntura Econômica - Edição Especial 2019, p. 353. Fortaleza: Banco do Nordeste do Brasil, 2019.

INSTITUTO DE PESQUISA ECONÔMICA APLICADA. Ipeadata. Rio de Janeiro: IPEA, 2015. Base de dados: Macroeconômico; Regional; Social. Disponível em: www.ipeadata.gov.br/Default.aspx.

PESQUISA NACIONAL POR AMOSTRA DE DOMICÍLIOS CONTÍNUA. Rio de Janeiro: IBGE, 2019. Disponível em: https://www.ibge.gov.br/estatisticas/sociais/trabalho/9173-pesquisa-nacional-por-amostra-de-domicilios-continua-trimestral.html?=&t=o-que-e.

AGÊNCIA NACIONAL DE TELECOMUNICAÇÕES. Dados. 2019. Disponível em: http://www.anatel.gov.br/institucional/.

PROGRAMA DAS NAÇÕES UNIDAS PARA O DESENVOLVIMENTO. Atlas do Desenvolvimento Humano. 2013. Disponível em: http://www.br.undp.org/content/brazil/pt/home/idh0.html.

INSTITUTO BRASILEIRO DE GEOGRAFIA E ESTATÍSTICA. Síntese de Indicadores Sociais: SIS. Rio de Janeiro:IBGE, 2018. Disponível em: https://www.ibge.gov.br/estatisticas/sociais/populacao/9221-sintese-de-indicadores-sociais.html?=&t=sobre.

INSTITUTO NACIONAL DE ESTUDOS E PESQUISAS EDUCACIONAIS ANÍSIO TEIXEIRA. Resumo Técnico do Estado de Alagoas: Censo da Educação Básica Estadual 2019. Brasília: INEP, 2020.

BRASIL. INSTITUTO NACIONAL DE ESTUDOS E PESQUISAS EDUCACIONAIS ANÍSIO TEIXEIRA. Saeb 2019: indicador de nível socioeconômico do Saeb 2019: nota técnica. Brasília, DF: Inep, 2021.
