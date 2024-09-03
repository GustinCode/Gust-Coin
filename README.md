# 📖Criação de uma moeda em uma rede Etherium: 🪙Gust-Coin

Um projeto da DIO para criar uma contrato segundo o padrão ERC-20 para criação de um token fundivel, na criação do projeto foi criado uma moeda simples e alguns sistemas

## 💻 Tecnologias utilizadas no projeto

- [Ganache CLI](https://archive.trufflesuite.com/ganache/) 
- [Etherium](https://ethereum.org/pt-br/)

## ✨ Features


|   Evento   | retorno |
| :------: | :------: |
|  totalSuppy  | retorna a quantidade total de moedas disponíveis do contrato |
| balanceOf | retorna a quantidade total de moedas disponíveis no endereço enviado |
| allowance | retorna um valor boleano, se está permitido o envio do endereço **delegate** para ser transacionado do endereço **Owner** |
| tranfer | retorna um valor boleano, se o saldo do endereço **spender** é valido para encaminhar a quantidade de moedas pertimidas em **amount** |
| transferFrom | retorna um valor boleano, se o saldo do endereço **spender** possuí a quantidade de moedas estabelecidas em **amount** para ser encaminhadoao endereço de **recipient** em caso da transação ser valida e realiza a transação posteriormente emite o evento **Transfer**|



|   Evento   | retorno |
| :------: | :------: |
| Transfer | Event que realiza a notificação no contrato da transferencia das moeda GST de um endereço **receiver** para outro endereço|
| Approval | Event que realiza a notificação na contrato da transferencia da quantidade permitida **amount** de moeda GST do endereço **spender** pela conta **Owner** |

  

# ✍️ Leia o contrato

se você quiser ler um pouco sobre o contrato e dar alguma melhoria as funções, por favor deixe uma mensagem na aba de edições, para eu atualizá-lo e torná-lo ainda melhor.

[Click aqui para ver o código](https://github.com/GustinCode/Gust-Coin/blob/master/GustCoin.sol)
