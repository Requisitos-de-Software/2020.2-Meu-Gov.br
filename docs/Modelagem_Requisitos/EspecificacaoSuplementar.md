# Especificação Suplementar
## Histórico de Versões

| Data       | Versão | Descrição                        | Autores                   | Revisor |
| ---------- | ------ | -------------------------------- | ------------------------- | ------- |
| 18/03/2021 | 0.1    | Criação do documento             | Giovana Dionisio          | Eduarda Servidio |
| 19/03/2021 | 0.2    | Pequenas correções no texto      | Giovana Dionisio | Eduarda Servidio |

## Introdução
<p align="justify"> A Especificação Suplementar é um artefato documentado em linguagem natural que auxilia o engenheiro de software na listagem e descrição dos requisitos não funcionais de um projeto. Através deste documento, junto às outras técnicas de elicitação e modelagem, é possível obter o conjunto completo dos requisitos do sistema. </p>
<p align="justify"> Muitas vezes, os requisitos não funcionais não são identificados de maneira simples quando são aplicadas técnicas de elicitação voltadas para o usuário e a sua utilização do sistema. Estes requisitos podem estar relacionados: </p>

* Às questões legais e aos padrões do sistema;
* À qualidade do sistema;
* À compatibilidade e às restrições de design do sistema.

<p align="justify"> Por isso, a Especificação Suplementar é orientada pelo método FURPS+, para a simplificação da elicitação destes atributos. </p>

### FURPS+
<p align="justify"> FURPS+ é um método para a classificação dos requisitos relacionados à qualidade do Software. Seu nome consiste em uma silga para <i><b>F</b>uncionality</i>, <i><b>U</b>sability</i>, <i><b>R</b>eliability</i>, <i><b>P</b>erformance</i> e <i><b>S</b>uportability</i>. </p>

* <p align="justify"> Funcionalidade (<i>funcionality</i>): se refere ao conjunto de características e capacidades, funções e segurança de um software; </p>
* <p align="justify"> Usabilidade (<i>usability</i>): está relacionada a fatores humanos do software, como estética, consistência e documentação; </p>
* <p align="justify"> Confiabilidade (<i>reliability</i>): é avaliada através da medição de frequência e severidade das falhas, da precisão dos resultados gerados, do tempo médio entre defeitos, da capacidade do sistema de recuperar-se de uma falha e da previsibilidade do software; </p>
* <p align="justify"> Desempenho (<i>performance</i>): considera a velocidade de processamento, tempo de resposta, consumo de recursos e a eficiência do programa; </p>
* <p align="justify"> Facilidade de suporte (<i>suportability</i>): engloba a extensabilidade, a adaptabilidade e a reparabilidade, entre outras características que envolvem o suporte de um software. </p>

<p align="justify"> O '+' de FURPS+ está relacionado a outros aspectos que podem ser aplicados quando se trata da qualidade de software, mas que não estão descritos na silga. </p>

## Metodologia 
<p align="justify"> A equipe utilizou o método FURPS+ para o levantamento dos requisitos não funcionais relacionados à qualidade do aplicativo Meu gov.br, analisando a aplicação com base nos aspectos descritos no método. Além disso, foram levantados requisitos não funcionais relacionados a questões legais através do estudo da <a href = "https://appgovbr.estaleiro.serpro.gov.br/api/legal">documentação</a> disponibilizada pelos desenvolvedores do aplicativo na sua <a href="https://play.google.com/store/apps/details?id=br.gov.meugovbr&hl=pt_BR&gl=US">página da PlayStore</a>.</p>

## Levantamentos
Aqui são apresentados os requisitos que foram levantados, além de uma breve descrição sobre cada um. 
### Requisitos de qualidade
#### Funcionalidade
<p align="justify"> Os requisitos relacionados às funcionalidade do Meu gov.br foram levantados e descritos anteriormente, com as técnicas de <a href="https://requisitos-de-software.github.io/2020.2-Meu-Gov.br/Elicitacao/introspeccao/">Introspecção</a>, <a href="https://requisitos-de-software.github.io/2020.2-Meu-Gov.br/Elicitacao/questionario/">Questionário</a> e <a href="https://requisitos-de-software.github.io/2020.2-Meu-Gov.br/Elicitacao/introspeccao/">Storyboard</a>. </p>

#### Usabilidade
* <p align="justify"> A interface do aplicativo deve apresentar cores que facilitem o seu uso; </p>

    * <p align="justify"> Para uma melhor usabilidade, o sistema precisa apresentar cores que não confundam o usuário. </p>

* <p align="justify"> As principais funcionalidades devem estar presentes na tela inical do aplicativo; </p>

    * <p align="justify"> O usuário não deve precisar realizar uma busca profunda para encontrar as funcionalidades desejadas. </p>

* <p align="justify"> O sistema deve apresentar ícones intuitivos para os usuários; </p>
    
    * <p align="justify"> O design dos ícones precisa deixar claro qual a sua funcionalidade (ex: sair da aplicação, ver notificações, etc). </p>

* <p align="justify"> O sistema deve apresentar linguagem simples e direta; </p>
    
    * <p align="justify"> Os usuários-alvo do aplicativo englobam pessoas de diferentes idades, diferentes graus de escolaridade, etc., então a linguagem do aplicativo deve ser clara para todos esses grupos. </p> 

* <p align="justify"> O sistema deve apresentar padrões para botões, cores, fontes, espaçamentos e formas; </p>
    
    * <p align="justify"> Ao apresentar uma consistência nos padrões da interface, o usuário que não possui habilidades com a tecnologia ou dificuldades de leitura pode se guiar através da memória visual. </p>

* <p align="justify"> O aplicativo deve possuir uma documentação com instruções  de utilização da plataforma; </p>

    * <p align="justify"> Deve ser elaborado um tutorial de uso para o aplicativo que seja simples e de fácil entendimento para o público em geral. </p>

#### Confiabilidade
* <p align="justify"> As informações apresentadas pelo aplicativo devem ser condizentes com o que consta nos bancos de dado do governo; </p>

    * <p align="justify"> É necessário que haja consistência nas informações e documentos que constam no aplicativo. </p>

* <p align="justify"> O sistema deve estar disponível constantemente; </p>

    * <p align="justify"> Por conter documentos oficiais, o aplicativo deve estar em constante funcionamento, pois o usuário deve poder contar com ele para a sua utilização. </p>

* <p align="justify"> O aplicativo deve dar informações ao usuário sobre os erros que ele cometer durante a sua utilização; </p>

    * <p align="justify"> O usuário deve ser informado quando cometer algum erro e por qual motivo ele é um erro (ex: ao fazer login, se o usuário inserir incorretamente o seu CPF, ele precisa ser informado que ele cometeu o erro de inserir um dado incorreto). </p>

* <p align="justify"> O aplicativo deve oferecer suporte para o usuário se recuperar de seus erros; </p>

    * <p align="justify"> Utilizando o exemplo anterior, o aplicativo precisa permitir que o usuário insira novamente os seus dados, oferecendo assim uma maneira de se recuperar de seu erro. </p>

* <p align="justify"> O aplicativo deve armazenar com segurança os dados dos usuários; </p>

    * <p align="justify"> O aplicativo não pode estar sujeito a falhas que possam, de alguma maneira, afetar os dados sensíves do usuário, como senha ou foto. </p>

#### Desempenho
* <p align="justify"> O sistema deve suportar grandes volumes de usuários na aplicação sem que haja instabilidade; </p>

    * <p align="justify"> Em alguns momentos específicos, pode haver um grande número de acessos simultâneos e o aplicativo precisa ser preparado para este cenário. </p>

* <p align="justify"> A aplicação não deve consumir muitos recursos (memória, processamento, bateria) do dispositivo; </p>

    * <p align="justify"> A aplicação deverá funcionar bem desde os dispositivos mais robustos até os mais simples. </p>

* <p align="justify"> O tempo de resposta ao estímulo ou solicitação do usuário deve ser o mais próximo possível de instantâneo; </p>

    * <p align="justify"> O usuário pode perder a atenção ou a paciência ao ter que lidar com longos períodos de espera, por isso o tempo de reposta do sistema deve ser rápido; </p>

#### Facilidade de suporte:

* <p align="justify"> O aplicativo deve funcionar nos sistemas Android e iOS; </p>

    * <p align="justify"> O aplicativo deve ser disponibilizado tanto para dispositivos que utilizam o sistema Android quanto para os que utilizam o sistema iOS. </p>

* <p align="justify"> O sistema deve se adaptar ao formato de cada dispositivo; </p>

    * <p align="justify"> A interface do aplicativo deve ser otimizada para o dispositivo em que ele está sendo utilizado. </p>

### Requisitos legais
* <p align="justify"> O aplicativo precisa se submeter à Lei Geral de Proteção de Dados (LGPD); </p>

    * <p align="justify"> Essa é a Lei 13.709, de 14 de agosto de 2018, que trata sobre o tratamento de dados pessoais no Brasil e o aplicativo precisa ser fiel a ela. </p>

### Tabela de requisitos levantados

| ID  | Descrição |
| --- | --------- |
|  1  | A interface do aplicativo deve apresentar cores que facilitem o seu uso |
|  2  | As principais funcionalidades devem estar presentes na tela inical do aplicativo |
|  3  | O sistema deve apresentar ícones intuitivos para os usuários |
|  4  | O sistema deve apresentar linguagem simples e direta |
|  5  | O sistema deve apresentar padrões para botões, cores, fontes, espaçamentos e formas |
|  6  | O aplicativo deve possuir uma documentação com instruções de utilização da plataforma |
|  7  | As informações apresentadas pelo aplicativo devem ser condizentes com o que consta nos bancos de dado do governo |
|  8  | O sistema deve estar disponível constantemente |
|  9  | O aplicativo deve dar informações ao usuário sobre os erros que ele cometer durante a sua utilização |
| 10  | O aplicativo deve oferecer suporte para o usuário se recuperar de seus erros |
| 11  | O aplicativo deve armazenar com segurança os dados dos usuários |
| 12  | O sistema deve suportar grandes volumes de usuários na aplicação sem que haja instabilidade |
| 13  | A aplicação não deve consumir muitos recursos (memória, processamento, bateria) do dispositivo |
| 14  | O tempo de resposta ao estímulo ou solicitação do usuário deve ser o mais próximo possível de instantâneo |
| 15  | O aplicativo deve funcionar nos sistemas Android e iOS |
| 16  | O sistema deve se adaptar ao formato de cada dispositivo |
| 17  | O aplicativo precisa se submeter à Lei Geral de Proteção de Dados (LGPD) |

## Bibliografia
<p align="justify"> SERRANO, Milene, SERRANO, Maurício. Requisitos - Aula 13. 40 slides. p 28, 29. Disponível em: <a href = "https://aprender3.unb.br/pluginfile.php/693320/mod_resource/content/1/Requisitos%20-%20Aula%20013a.pd">https://aprender3.unb.br/pluginfile.php/693320/mod_resource/content/1/Requisitos%20-%20Aula%20013a.pdf</a>. Acesso em: 18 de março de 2021. </p>
<p align="justify"> PRESSMAN, Roger S.; MAXIM, Bruce R.. Engenharia de software: uma abordagem profissional. 8 ed. Porto Alegre: AMGH, 2016. p 210, 211. </p>
<p align="justify"> GOIS, Samily, SOBRINHO, Francisco. Projeto de Software Floricultura Beija-Flor, Especificação Suplementar. Versão 101.6. PHP SOFTWARE COMPANY, 2012. </p>
<p align="justify"> Política de Privacidade - Aplicativo Meu gov.br. Disponível em: <a href = "https://appgovbr.estaleiro.serpro.gov.br/api/legal">https://appgovbr.estaleiro.serpro.gov.br/api/legal</a>.</p>
