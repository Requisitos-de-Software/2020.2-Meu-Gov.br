# Matriz Backward From

## Histórico de Versões

| Data       | Versão | Descrição                        | Autores               | Revisor          |
| ---------- | ------ | -------------------------------- | --------------------- | ---------------- |
| 01/05/2021 | 0.1    | Criação do Documento             | Gabriela Pivetta     | --- |

## Introdução

<p text-align='justify'>A rastreabilidade de requisitos é uma característica de sistemas ondese pode ligar requisitos às suas fontes e aos artefatos criados a partir deles durante o ciclo de vida de desenvolvimento do sistema baseado nesses requisitos. Rastreabilidade de requisitos estabelece um elo entre mudanças das necessidades dos usuários e evolução dos sistemas de computação, sendo uma base para o gerenciamento do conhecimento organizacional.</p>

## Metodologia

### Meta-Modelo de Toranzo

<p text-align='justify'>Para classificar as informações a serem rastreadas na nossa matriz backward-from, nós utilizamos o meta-modelo de Toranzo para classicá-las em quatro níveis:

• Ambiental: informações oriundas do contexto no qual a organização está inserida;
• Organizacional: informações pertencentes à organização (missão, objetivos e estratégias);
• Gerencial: informações que auxiliam a gerência do projeto.
• Desenvolvimento: informações associadas aos diversos artefatos gerados ao longo do processo de desenvolvimento (artefatos de requisitos, diagramas, códigos, casos de teste e outros).

Já os principais elos definidos por Toranzo são:

• Satisfação: classe origem tem dependência de satisfação com a classe destino.
• Recurso: classe origem tem dependência de recurso com a classe destino.
• Responsabilidade: registra a participação, responsabilidade e ação de pessoas sobre artefatos.
• Representação: captura a representação ou modelagem dos requisitos em outras linguagens.
• Alocado: classe origem está relacionada à classe destino, que representa um subsistema.
• Agregação: indica “composição” de elementos.</p>


## Matriz Backward From

| Origem | ID  | Requisito | Categoria da meta-modelo | Tipo de elo |
| ------ | --- | --------- | ------------------------ | ----------- |
| Introspecção | R01 | O sistema deve ter uma tela agradável, limpa e intuitiva com as opções de cadastro e login | Organizacional | Representação |
| Introspecção | R02 | O usuário deve poder alterar sua senha caso necessário | Ambiental; Desenvolvimento | Representação |
| Introspecção e Storyboard | R03 | O sistema deve realizar a validação facial para usuários novos | Ambiental; Organizacional; Desenvolvimento | Representação |
| Introspecção e Storyboard | R04 | O sistema deve apresentar uma tela principal com as funcionalidades e informações disponíveis de forma clara | Organizacional; Desenvolvimento | Representação |
| Introspecção, Questionário e Storyboard | R05 | O sistema deve disponibilizar documentos oficiais, além do CPF e CNH (ex. CRV, Passaporte, Identidade, Certidão de Nascimento, Título de Eleitor, Carteira de Trabalho, Carteira de Vacinação, Certidão de Casamento) | Organizacional; Desenvolvimento | Representação |
| Introspecção | R06 | O usuário deve ter a possibilidade de revisar como é feita a proteção dos seus dados | Ambiental; Desenvolvimento | Representação |
| Introspecção | R07 | O usuário deve ter a possibilidade de ver e rever as instruções sobre o aplicativo | Ambiental; Desenvolvimento | Representação |
| Introspecção e Storyboard | R08 | O usuário deve ter a possibilidade de ver e rever a política de privacidade | Ambiental; Desenvolvimento | Representação |
| Introspecção | R09 | O sistema deve disponibilizar um QR Code único para cada usuário para a recuperação de senha | Organizacional; Desenvolvimento | Representação |
| Introspecção | R10 | O usuário deve ser capaz de sair do aplicativo | Ambiental; Desenvolvimento | Representação |
| Introspecção | R11 | O sistema deve disponibilizar uma aba de Dúvidas Frequentes | Organizacional; Desenvolvimento | Representação |
| Questionário | R12 | O login do usuário deve ser armazenado, de forma que ele não precise fazer login a cada entrada no aplicativo | Ambiental; Organizacional; Desenvolvimento | Representação |
| Questionário | R13 | O sistema deve disponibilizar em formato digital o Certificado de Dispensa de incorporação/certificado de reservista | Organizacional; Desenvolvimento | Representação |
| Storyboard | R14 | O sistema deve atualizar os documentos oficiais do usuário sempre que ocorrer alterações ou disponibilidade de novos documentos | Ambiental; Organizacional; Desenvolvimento | Representação |

## Bibliografia

<p text-align='justify'><a href="https://www.youtube.com/watch?v=2vokkbYeX8U&ab_channel=Andr%C3%A9BarrosdeSales">Aula 25 - Apoio: Pós-Rastreabilidade - Gerência II. </a>Acesso em: 01/05/2021 </p>