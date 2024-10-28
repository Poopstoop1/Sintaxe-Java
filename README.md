# DIO - Trilha Java Básico

Vamos exercitar todo o conteúdo apresentado no módulo de Sintaxe codificando o seguinte cenário.

1. Crie o projeto `ContaBanco` que receberá dados via terminal.
2. Dentro do projeto, crie a classe `ContaTerminal.java` para realizar toda a codificação do nosso programa.
3. Dentro do projeto, crie uma classe `Conta` para armazenar todos os atributos abaixo:

###### Revise sobre regras de declaração de variáveis

| Atributo     | Tipo    | Exemplo       |
| ------------ | ------- | ------------- |
| Numero       | Inteiro | 1021          |
| Agencia      | Texto   | 067-8         |
| Nome Cliente | Texto   | MARIO ANDRADE |
| Saldo        | Decimal | 237.48        |

###### Revise sobre terminal, main args e a classe Scanner

2. Faça uma lista de contas cadastrando 3 contas e permita que os dados sejam inseridos via terminal sendo que o usuário receberá a mensagem de qual informação será solicitada, exemplo:

- Programa: "Por favor, digite o número da Agência !"
- Usuário: 1021 _(depois ENTER para o próximo campo)_

###### Revise sobre concatenação e classe String com método concat

3. Depois de todas as informações terem sido inseridas, o sistema deverá exibir a seguinte mensagem:

_"Olá [Nome Cliente], obrigado por criar uma conta em nosso banco, sua agência é [Agencia], conta [Numero] e seu saldo [Saldo] já está disponível para saque"._

Os campos em [ ] devem ser alterados pelas informações que forem inseridas pelos usuários.