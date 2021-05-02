# Histórias de Usuário

## Histórico de Versões

| Data       | Versão | Descrição                                           | Autores                   | Revisor |
| ---------- | ------ | --------------------------------------------------- | ------------------------- | ------- |
| 30/03/2021 | 0.1    | Criação do documento                                | Eduarda Servidio          | Gabriela Pivetta |
| 30/03/2021 | 0.2    | Adição das Metodologias e separação dos tópicos     | Eduarda Servidio          | Gabriela Pivetta |
| 30/03/2021 | 0.3    | Adição das Histórias no Épico Acesso ao Aplicativo  | Eduarda Servidio          | Gabriela Pivetta |
| 30/03/2021 | 0.4    | Adição das Histórias nos Épicos Área do Usuário e Apoio ao Usuário  | Gabriela Pivetta          | Eduarda Servidio |
| 15/04/2021 | 0.5    | Correção Ortográfica  | Eduarda Servidio          | Gabriela Pivetta |

## Metodologia - Histórias de Usuário
<p align="justify">Histórias de Usuário são artefatos de desenvolvimento utilizados em sistemas geridos
segundo metodologias ágeis. São descrições simples que descrevem uma
funcionalidade e é recomendável que sejam escritas segundo o ponto de vista do usuário.
Elas são curtas, simples, claras e focam nos objetivos do usuário e como o sistema alcança esses objetivos.</p>

## Metodologia - Épicos
<p align="justify">Um épico é uma história de usuário que ainda não foi detalhada, é muito grande ou ainda
possui muita incerteza e portanto não pode ser transformada em incremento do produto.
O épico deve ser separado em histórias de usuário menores.</p>

## Épico - Acesso ao aplicativo

### US01 - Realizar Cadastro
Eu, como usuário visitante, desejo poder me cadastrar no aplicativo Meu Gov<span>.</span>br.
#### Critérios de Aceitação
* Deve mostrar as opções de cadastro
* Deve cadastrar somente se o usuário tiver CPF
* Ser possível escolher o modo de como o usuário quer cadastrar
(Existem 6 opções para escolha: Validação Facial, Bancos Credenciados,
Internet Banking, Número do CPF, Certificado digital e Certificado digital em nuvem).

### US02 - Login
Eu, como usuário cadastrado, desejo poder me logar no aplicativo Meu Gov<span>.</span>br.
#### Critérios de Aceitação
* Deve possuir o campo para preencher CPF e Senha.
* Ser possível realizar o login de usuário com CPF cadastrado.
* Validar as credenciais de acesso.
* Realizar a validação facial.
* Disponibilizar acesso ao usuário cadastrado.

### US03 - Logout
Eu, como usuário logado, desejo poder me deslogar do aplicativo Meu Gov<span>.</span>br.
#### Critérios de Aceitação
* Deve haver um botão de logout.
* Retirar as credenciais de acesso do usuário da sessão.
* Retornar a tela de login.
* Não permitir o usuário acessar as funcionalidades do aplicativo deslogado.

### US04 - Recuperar Senha
Eu, como usuário visitante, desejo poder recuperar a minha senha no aplicativo Meu Gov<span>.</span>br.
#### Critérios de Aceitação
* Deve possuir um campo para receber o CPF.
* Verificar se o CPF está cadastrado.
* Deve validar por meio de um CAPTCHA a recuperação da conta.
* Deve ser possível escolher entre 5 opções (validação facial,
bancos credenciados, e-mail, celular e internet banking) a forma
que quer utilizar para recuperar a senha.
* Deve direcionar o usuário para a tela Login depois de recuperar a senha.

### US05 - Leitura QR Code
Eu, como usuário visitante, desejo poder ler o QR Code gerado no computador sem logar no aplicativo Meu Gov<span>.</span>br.
#### Critérios de Aceitação
* Deve haver um botão para leitura de QR Code.
* Deve haver acesso a câmera do dispositivo.
* Deve haver uma validação do QRCode.

## Épico - Área do Usuário

### US06 - Acessar os documentos
Eu, como usuário logado, desejo poder visualizar meus documentos cadastrados no aplicativo Meu Gov<span>.</span>br.
#### Critérios de Aceitação
* Deve haver um botão que direcione o usuário para a área dos documentos.
* Os documentos devem estar disponíveis para visualização.
* Os documentos disponíveis devem ser correspondentes com o usuário.

### US07 - Acessar QR Code referente ao CPF
Eu, como usuário logado, desejo poder acessar o QR Code referente ao meu CPF no aplicativo Meu Gov<span>.</span>br.
#### Critérios de Aceitação
* Deve haver um botão para visualizar o QRCode.
* Deve haver uma validação do QRCode.

## Épico - Apoio ao Usuário

### US08 - Acessar Dúvidas Frequentes
Eu, como usuário visitante, desejo poder visualizar as dúvidas frequentes dos usuários do aplicativo Meu Gov<span>.</span>br.
#### Critérios de Aceitação
* Deve haver um botão que direcione o usuário para a área das dúvidas frequentes.
* Devem ser apresentadas as dúvidas frequentes dos usuários.

### US09 - Rever Instruções do Aplicativo
Eu, como usuário logado, desejo poder visualizar as instruções do aplicativo Meu Gov<span>.</span>br.
#### Critérios de Aceitação
* Deve haver um botão que direcione o usuário para uma aba com as instruções do aplicativo.
* Devem haver as instruções sobre o aplicativo na aba aberta.

### US10 - Rever Política de Privacidade
Eu, como usuário logado, desejo poder visualizar a Política de Privacidade do aplicativo Meu Gov<span>.</span>br.
#### Critérios de Aceitação
* Deve haver um botão que direcione o usuário para uma página com a Política de Privacidade do aplicativo Meu Gov<span>.</span>br.
* Deve haver a Política de Privacidade na página aberta.

## Bibliografia
<p align="justify">SERRANO, Maurício; SERRANO, Milene; Requisitos - Aula 15.</p>
<p align="justify">GLAUCO. User Stories - o que são? como usar?. Disponível em: <a href="https://blog.myscrumhalf.com/user-stories-o-que-sao-como-usar/">https://blog.myscrumhalf.com/user-stories-o-que-sao-como-usar/.</a>Acesso em: 29 de mar. de 2021</p>
<p align="justify">Ferreira,A. Product Backlog: Épico, Histórias de Usuário e Tarefas. Disponível em: <a href="https://k21.global/blog/product-backlog-epico-historia-tarefas#:~:text=%C3%89pico%20%E2%80%93%20Epic,em%20hist%C3%B3rias%20de%20usu%C3%A1rio%20menores.">https://k21.global/blog/product-backlog-epico-historia-tarefas#:~:text=%C3%89pico%20%E2%80%93%20Epic,em%20hist%C3%B3rias%20de%20usu%C3%A1rio%20menores..</a>Acesso em: 29 de mar. de 2021</p>
