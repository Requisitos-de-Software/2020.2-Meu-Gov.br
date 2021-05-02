# NFR Framework

## Histórico de Versões

| Data       | Versão | Descrição                                             | Autores                         | Revisor       |
| ---------- | ------ | ----------------------------------------------------- | ------------------------------- | ------------- |
| 28/03/2021 | 0.1    | Criação do documento                                  | Luis Marques e Giovana Dionisio | Pedro Haick   |
| 29/03/2021 | 0.2    | Adição de NFR usabilidade,confiabilidade e desempenho | Luis Marques                    | Pedro Haick   |
| 29/03/2021 | 0.3    | Adição da definição e legendas                        | Giovana Dionisio                | Pedro Haick   |
| 29/03/2021 | 0.4    | Adição de NFR geral, portabilidade e disponibilidade  | Giovana Dionisio                | Pedro Haick   |

## Definição
<p align="justify"> O NFR Framework trata de uma abordagem orientada a requisitos não funcionais que auxilia na condução da Engenharia de Requisitos. Esse Framework auxilia os desenvolvedores na implementação de soluções personalizadas para o produto de software, os guiando na escolha dentre as possíveis alternativas de desenvolvimento. </p>
<p align="justify"> A representação dos requisitos dentro no NFR Framework é realizada através de softgoals. Os softgoals caracterizam objetivos em um alto nível de abstração, sem definições ou critérios de satisfação precisos. Eles podem representar requisitos não funcionais (softgoals NFR), funcionalidades (softgoals de operacionalização) ou argumentações sobre a modelagem (softgoals de afirmação). </p>
<p align="justify"> Para a avaliação da satisfação ou não dos softgoals são estudadas suas inter-relações e influências exercidas. Tais relações são classificadas de acordo com a contribuição que os softgoals estabelecem e são divididas em: </p>
 
* <p align="justify"> AND: o softgoal pai só é satisfeito se todos os seus filhos forem satisfeitos; </p>
* <p align="justify"> OR: o softgoal pai é satisfeito quando pelo menos um de seus filhos forem satisfeitos; </p>
* <p align="justify"> MAKE: a satisfação do softgoal filho garante a satisfação do pai; </p>
* <p align="justify"> BREAK: a satisfação do softgoal filho nega a satisfação do pai; </p>
* <p align="justify"> HELP: a satisfação do filho satisfaz parcialmente o softgoal pai; </p>
* <p align="justify"> HURT: a satisfação do filho nega parcialmente a satisfação do pai; </p>
* <p align="justify"> UNKNOWN: a contribuição entre softgoal pai e filho é desconhecida; </p>
* <p align="justify"> EQUALS: a satisfação de um softgoal equivale a satisfação do outro e a sua não satisfação equivale a não satisfação do outro; </p>
* <p align="justify"> SOME +: o softgoal filho contribui positivamente com o pai, mas não se sabe a intensidade; </p>
* <p align="justify"> SOME -: o softgoal filho contribui negativamente com o pai, mas não se sabe a intensidade. </p>
<p align="justify"> Essas relações e contribuições são expressas em um grafo chamado Grafo de Interdependência de Softgoals (SIG). </p>
 
## Legenda
<p align="justify"> No SIG, são utilizadas as seguintes representações: </p>
 
* <p align="justify"> Quanto à classificação do softgoal: </p>
<img alt= "softgoal" src="https://i.ibb.co/ZBm0Qd1/softgoal.png" width = "400"/>

<i>Figura 1: Legenda para a classificação de softgoals. Autor: Giovana Dionisio.</i>  
 
* <p align="justify"> Quanto à contribuição: </p>
<img alt= "contribuicao" src="https://i.ibb.co/X5ZQW2h/contribuicao.png" width = "150"/>

<i>Figura 2: Legenda para a classificação de contribuições. Autor: Giovana Dionisio.</i>
 
* <p align="justify"> Quanto à satisfação do softgoal: </p>
<img alt= "satisfacao" src="https://i.ibb.co/6rcjVxM/satisfacao.png" width = "400"/>

<i>Figura 3: Legenda para a classificação da satisfação dos softgoals. Autor: Giovana Dionisio.</i>  

## NFR Geral
<img alt= "NFRgeral" src="https://i.ibb.co/xSzCvgD/NFRGeral.png" width = "600"/>

<i>Figura 4: NFR Geral. Autor: Giovana Dionisio.</i>

## NFR de Usabilidade
### Sem propagação

<img alt= "caso-de-uso-4" src="../images/NFR/usabili_no_propag.png" width = "900" />

<i>Figura 5: NFR de usabilidade, sem propagação. Autor: Luis Marques.</i>

### Com propagação
<img alt= "caso-de-uso-4" src="../images/NFR/usabili_propag.png" width = "900" />

<i>Figura 6: NFR de usabilidade, com propagação. Autor: Luis Marques.</i>

## NFR de Confiabilidade
### Sem propagação

<img alt= "caso-de-uso-4" src="../images/NFR/confiabilidade_no_propag.png" width = "900" />

<i>Figura 7: NFR de confiabilidade, sem propagação. Autor: Luis Marques.</i>

### Com propagação

<img alt= "caso-de-uso-4" src="../images/NFR/confiabilidade_propag.png" width = "900" />

<i>Figura 8: NFR de confiabilidade, com propagação. Autor: Luis Marques.</i>

## NFR de Desempenho
### Sem propagação

<img alt= "caso-de-uso-4" src="../images/NFR/desempenho_no_propag.png" width = "900" />

<i>Figura 9: NFR de desempenho, sem propagação. Autor: Luis Marques.</i>

### Com propagação

<img alt= "caso-de-uso-4" src="../images/NFR/desempenho_propag.png" width = "900" />

<i>Figura 10: NFR de desempenho, com propagação. Autor: Luis Marques.</i>

## NFR de Disponibilidade
### Sem propagação
<img alt= "NFRdisp" src="https://i.ibb.co/g3J5bzp/NFRDisp.png" width = "400"/>

<i>Figura 11: NFR de disponibilidade, sem propagação. Autor: Giovana Dionisio.</i>

### Com propagação
<img alt= "NFRdispProp" src="https://i.ibb.co/1G3vZSw/NFRDisp-Prop.png" width = "400"/>

<i>Figura 12: NFR de disponibilidade, com propagação. Autor: Giovana Dionisio.</i>

## NFR de Portabilidade
### Sem propagação
<img alt= "NFRport" src="https://i.ibb.co/fGp35gN/NFRPort.png" width = "500"/>

<i>Figura 13: NFR de portabilidade, sem propagação. Autor: Giovana Dionisio.</i>

### Com propagação
<img alt= "NFRportProp" src="https://i.ibb.co/2s3pf5D/NFRPort-Prop.png" width = "500"/>

<i>Figura 14: NFR de portabilidade, com propagação. Autor: Giovana Dionisio.</i>

## Bibliografia
<p align="justify"> PRESSMAN, Roger S.; MAXIM, Bruce R.. <b>Engenharia de software: uma abordagem profissional</b>. 8 ed. Porto Alegre: AMGH, 2016. p 210, 211. </p>
<p align="justify"> DA SILVA, Reinaldo Antônio. <b>NFR4ES</b>: Um Catálogo de Requisitos Não-Funcionais para Sistemas Embarcados. 2019. 155 p. Dissertação (Pós-Graduação em Ciência da Computação)- Centro de Informática, Universidade Federal de Pernambuco, 2019. </p>
<p align="justify"> SERRANO, Milene, SERRANO, Maurício. Requisitos - Aula 13. 40 slides. Disponível em: <a href = "https://aprender3.unb.br/pluginfile.php/693320/mod_resource/content/1/Requisitos%20-%20Aula%20013a.pd">https://aprender3.unb.br/pluginfile.php/693340/mod_resource/content/1/Requisitos%20-%20Aula%20019a.pdf</a>. Acesso em: 29 de março de 2021. </p>