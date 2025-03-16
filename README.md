# Desafio: Simulação de Conta Bancária em Java

Este repositório contém um programa simples em Java que simula uma conta bancária, permitindo ao usuário consultar saldo, transferir valores e receber depósitos.

## Funcionalidades
- Exibir informações do cliente e saldo inicial.
- Consultar saldo atualizado.
- Transferir um valor, verificando se há saldo suficiente.
- Receber valores e atualizar o saldo.
- Interface interativa via terminal.

## Tecnologias Utilizadas
- Java
- Scanner (para entrada de dados do usuário)

## Como Executar o Programa
1. Certifique-se de ter o Java instalado em seu sistema.
2. Clone este repositório:
   ```bash
   git clone https://github.com/Lelibi/aplicacao_java.git
   ```
3. Compile o programa:
   ```bash
   javac Desafio.java
   ```
4. Execute o programa:
   ```bash
   java Desafio
   ```

## Estrutura do Código
O programa inicia exibindo o nome do cliente, o tipo de conta e o saldo inicial. Em seguida, apresenta um menu interativo onde o usuário pode escolher entre:
- **Consultar saldo**: Exibe o saldo atual.
- **Transferir valor**: Solicita um valor a ser transferido e verifica se há saldo suficiente.
- **Receber valor**: Permite adicionar um valor ao saldo.
- **Sair**: Encerra o programa.

O loop continua executando até que o usuário escolha a opção de sair.

## Exemplo de Uso
```
***********************

Nome do cliente: Clark Kent
Tipo conta: Corrente
Saldo atual: 1599.99

***********************
Digite sua opção
1 - Consultar saldo
2 - Transferir valor
3 - Receber valor
4 - Sair
```

## Melhorias Futuras
- Implementar autenticação de usuário.
- Criar uma interface gráfica para interação mais intuitiva.
- Adicionar persistência de dados para armazenar informações das transações.

---
Desenvolvido por [Lelibi](https://github.com/Lelibi).

