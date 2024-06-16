# usuario-telefone-verificacao-saldo
Criar uma classe UsuarioTelefone e uma classe PlanoTelefone para representar um usuário e seu plano de telefone, respectivamente. Adicione funcionalidades para verificar o saldo do plano e retornar uma mensagem personalizada com base em condições específicas de saldo.

# Desafio: Verificação de Saldo em Planos de Telefone

## Descrição
Neste desafio, você irá adicionar uma funcionalidade à classe `UsuarioTelefone` para que possa ser verificado o saldo disponível em seu plano. Para essa solução, você deve criar uma classe `PlanoTelefone`, seu método de inicialização e encapsular os atributos, `nome` e `saldo` dentro da classe. Adicione também um método `verificar_saldo` para verificar o saldo do plano e uma `mensagem_personalizada` para gerar uma mensagem personalizada.

### Condições da verificação do saldo:
- Caso o saldo seja menor do que 10, retorne: "Seu saldo está baixo. Recarregue e use os serviços do seu plano."
- Caso o saldo seja maior ou igual a 50, retorne: "Parabéns! Continue aproveitando seu plano sem preocupações."
- Caso contrário, retorne: "Seu saldo está razoável. Aproveite o uso moderado do seu plano."

## Entrada
Como entrada, será solicitado o nome, plano (Essencial, Prata, Premium) e saldo atual do cliente.

## Saída
Mensagem personalizada de acordo o saldo do cliente.

## Exemplos
A tabela abaixo apresenta exemplos com alguns dados de entrada e suas respectivas saídas esperadas. Certifique-se de testar seu programa com esses exemplos e com outros casos possíveis.

| Entrada       | Saída |
| ------------- | ----- |
| João          | Seu saldo está baixo. Recarregue e use os serviços do seu plano. |
| Essencial     | 
| 9             |       |
| Debora        | Seu saldo está razoável. Aproveite o uso moderado do seu plano. |
| Prata         |       |
| 11            |       |
| Catarina      | Parabéns! Continue aproveitando seu plano sem preocupações. |
| Premium       |       |
| 50            |       |
