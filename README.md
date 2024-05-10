# <img align="center" width="40px" src="https://hermes.digitalinnovation.one/assets/diome/logo-minimized.png"> Orientação a Objetos na Prática com Java
www.dio.me


#### Desenvolvido na linguagem Java por:
- [Marcos Shirafuchi](https://github.com/marcosfshirafuchi)
# Desafio 04 / 05 - Herança Bancária: Entendendo a Herança e Polimorfismo
## Desafio
Após o sucesso no desenvolvimento do sistema básico de abertura de contas bancárias, o banco decidiu expandir seus serviços para oferecer diferentes tipos de contas. Agora, além das contas bancárias comuns, eles também oferecem contas poupança. Sua tarefa é implementar a herança e o polimorfismo no sistema, criando uma classe "ContaPoupanca" que herde da classe "ContaBancaria" anteriormente criada. A classe "ContaPoupanca" deve adicionar um novo atributo, taxa de juros, além dos atributos herdados.
<br><br>
Dica: Utilize a herança para criar a classe "ContaPoupanca" que herde da classe "ContaBancaria" e adicione o atributo "taxaJuros". Implemente o método "exibirInformacoes()" na classe "ContaPoupanca" para exibir as informações adicionais.

## Entrada


O programa deve solicitar ao usuário as informações necessárias para abrir uma conta poupança. A entrada deve ser feita via console (linha de comando) e deve incluir o número da conta (um valor inteiro), o nome do titular (uma sequência de caracteres), o saldo inicial da conta (um valor decimal) e a taxa de juros da conta poupança (um valor decimal).


## Saída

Após receber as informações da conta poupança, o programa deve criar um objeto do tipo "ContaPoupanca" e exibir na tela as informações dessa conta, incluindo o número da conta, o nome do titular, o saldo atual e a taxa de juros. A saída deve ser formatada de forma clara e legível para o usuário.


## Exemplos
A tabela abaixo apresenta exemplos com alguns dados de entrada e suas respectivas saídas esperadas. Certifique-se de testar seu programa com esses exemplos e com outros casos possíveis.
<table>
  <thead>
    <tr align="left">
      <th>Entrada</th>
      <th>Saída</th>
    </tr>
  </thead>
  <tbody align="left">
    <tr>
      <td>Joao<br>
123456<br>
1000.0<br>
1.5<br>
      </td>
      <td>Conta Poupanca:<br>
Joao<br>
123456<br>
Saldo: R$ 1000.0<br>
Taxa de juros: 1.5%<br>
      </td>
    </tr>
    <tr>
      <td>Ana<br>
789012<br>
2500.0<br>
3.0<br>
      </td>
      <td>Conta Poupanca:<br>
Ana<br>
789012<br>
Saldo: R$ 2500.0<br>
Taxa de juros: 3.0%</td>
    </tr>
    <tr>
      <td>Maria<br>
987654<br>
500.0<br>
2.5<br>
</td>
      <td>Conta Poupanca:<br>
Maria<br>
987654<br>
Saldo: R$ 500.0<br>
Taxa de juros: 2.5%<br>
</td>   
    </tr>
  </tbody>
  <tfoot></tfoot>
</table>





