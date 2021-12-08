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

## Desenvolvimento

Os microdados do ENEM 2019 são o menor nível de desagregação de dados recolhidos por meio do exame. Eles atendem a demanda por informações específicas ao disponibilizar as provas, os gabaritos, as informações sobre os itens, as notas e o questionário respondido pelos inscritos no ENEM. Eles estão disponíveis na seção Acesso à Informação > Dados Abertos > Microdados > Enem no portal do Instituto Nacional de Estudos e Pesquisas Educacionais (INEP)

### Exploração dos dados

#### Perfil dos inscritos

Em 2019 houveram 91.707 incrições para o ENEM no estado de Alagoas, sendo que 55.255 (60,25%) eram do sexo feminino e 36.452 (39,75%) do sexo masculino. As cidades alagoanas de Maceió e Arapiraca tiveram o maior número de inscritos, respectivamente com 34.635 (37,77%) e 9.738 (10,62%). Apenas 22.289 (24,30%) informaram o tipo de escola do ensino médio. Entre as inscrições femininas 31 (0,06%) eram gestantes. 549 (0,59%) pediram atendimento (DETALHAR!!!). 106 (0,12%) pediram atendimento específico (DETALHAR!!!). 719 (0,78%) pediram recursos especializados e específicos para realização das provas (DETALHAR!!!). A faixa de idade variou em sua maioria dos 18 aos 19 anos (HISTOGRAMA!!!). 8.862 (9,66%) estudantes menores de 18 anos e que ainda não estavam no último ano do ensino médio participaram do exame na condição de treineiros. Isso significa que, mesmo que ele obtenha boas notas no Enem, não poderá se matricular em uma instituição de Ensino Superior ou ter acesso a programas do Governo como SiSu, ProUni ou Fies.

#### Perfil dos que realizaram completamente as provas

Apenas 68.750 (74,97%) do total de inscritos no ENEM 2019 em Alagoas realizaram as provas, sendo que 41.304 (60,08%) eram do sexo feminino e 27.446 (39,92%) do sexo masculino. As cidades alagoanas de Maceió e Arapiraca tiveram o maior número de inscritos, respectivamente com 26.322 (38,29%) e 7.364 (10,71%). Apenas 19.050 (27,71%) informaram o tipo de escola do ensino médio. Entre as inscrições femininas 11 (0.016%) eram gestantes. 422 (0,61%) pediram atendimento especializado (DETALHAR!!!). 42 (0,06%) pediram atendimento específico (DETALHAR!!!). 529 (0,77%) pediram recursos especializados e específicos para realização das provas (DETALHAR!!!). A faixa de idade variou em sua maioria dos 18 aos 19 anos (HISTOGRAMA!!!). 7.588 (11,04%) estudantes menores de 18 anos e que ainda não estavam no último ano do ensino médio participaram do exame na condição de treineiros.

Média das notas(excluindo treineiros):

Segmentar as medianas das notas das provas por pefil socioeconônimo do INSE.

A média é usada para distribuições numéricas normais, que têm uma baixa quantidade de valores discrepantes.

A mediana é geralmente utilizada para retornar a tendência central para distribuições numéricas distorcidas.

O desvio padrão é uma medida que expressa o grau de dispersão de um conjunto de dados. Ou seja, o desvio padrão indica o quanto um conjunto de dados é uniforme. Quanto mais próximo de 0 for o desvio padrão, mais homogêneo são os dados.

Variância é uma medida de dispersão e é usada também para expressar o quanto um conjunto de dados se desvia da média.

O desvio padrão (DP) é definido como a raiz quadrada da variância (V).

A vantagem de usar o desvio padrão ao invés da variância é que o desvio padrão é expresso na mesma unidade dos dados, o que facilita a comparação.


### Métodos estatísticos

Estatística descritiva

### Hipóteses levantadas

Perfil socioeconômico x Rendimento ENEM

## Direções para o órgão público que será dirigido

## Referência:

CARVALHO, Cícero Péricles de. Alagoas 2000-2018. Revista BNB Conjuntura Econômica - Edição Especial 2019, p. 353. Fortaleza: Banco do Nordeste do Brasil, 2019.

INSTITUTO NACIONAL DE ESTUDOS E PESQUISAS EDUCACIONAIS ANÍSIO TEIXEIRA. Resumo Técnico do Estado de Alagoas: Censo da Educação Básica Estadual 2019. Brasília: INEP, 2020.

INSTITUTO DE PESQUISA ECONÔMICA APLICADA. Ipeadata. Rio de Janeiro: IPEA, 2015. Base de dados: Macroeconômico; Regional; Social. Disponível em: www.ipeadata.gov.br/Default.aspx.

PESQUISA NACIONAL POR AMOSTRA DE DOMICÍLIOS CONTÍNUA. Rio de Janeiro: IBGE, 2019. Disponível em: https://www.ibge.gov.br/estatisticas/sociais/trabalho/9173-pesquisa-nacional-por-amostra-de-domicilios-continua-trimestral.html?=&t=o-que-e.

AGÊNCIA NACIONAL DE TELECOMUNICAÇÕES. Dados. 2019. Disponível em: http://www.anatel.gov.br/institucional/.

PROGRAMA DAS NAÇÕES UNIDAS PARA O DESENVOLVIMENTO. Atlas do Desenvolvimento Humano. 2013. Disponível em: http://www.br.undp.org/content/brazil/pt/home/idh0.html.

INSTITUTO BRASILEIRO DE GEOGRAFIA E ESTATÍSTICA. Síntese de Indicadores Sociais: SIS. Rio de Janeiro:IBGE, 2018. Disponível em: https://www.ibge.gov.br/estatisticas/sociais/populacao/9221-sintese-de-indicadores-sociais.html?=&t=sobre.
