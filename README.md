# Sistema Bancário em Python 🏦

Este é um script simples em Python que simula operações bancárias básicas. Ele foi criado para fins de prática e aprendizado, utilizando conceitos fundamentais da linguagem como estruturas condicionais, loops e manipulação de strings.

## Funcionalidades ✨

O sistema bancário permite realizar as seguintes operações:

- **Depósito (`d`)**: Adiciona um valor à conta bancária.
- **Saque (`s`)**: Retira um valor da conta, respeitando regras de limite e saldo.
- **Extrato (`e`)**: Exibe o histórico de transações e o saldo atual.
- **Sair (`q`)**: Encerra o programa.

## Regras de Negócio 📝

1. **Depósitos**:
   - Apenas valores positivos são aceitos.

2. **Saques**:
   - O valor do saque não pode exceder o saldo disponível.
   - O valor do saque não pode ultrapassar o limite de R$ 500,00.
   - O número máximo de saques diários é 3.

3. **Extrato**:
   - Exibe todas as transações realizadas (depósitos e saques).
   - Mostra o saldo final da conta.

## Como Usar 🚀

1. Clone o repositório:
   ```bash
   git clone https://github.com/tbarcelar/lab-py-bancario.git


Fluxo do Programa 🔄
Ao executar o script, será exibido o seguinte menu:

[d] Depositar
[s] Sacar
[e] Extrato
[q] Sair


O usuário pode selecionar uma das opções digitando a letra correspondente. Dependendo da escolha, o programa executará a operação solicitada ou exibirá uma mensagem de erro caso algo esteja fora dos critérios definidos.

Exemplo de Uso 📖

Depósito:
plaintext
Copiar
Editar
Informe o valor do depósito: 100
Saque:
plaintext
Copiar
Editar
Informe o valor do saque: 50
Extrato:
plaintext
Copiar
Editar
================ EXTRATO ================
Depósito: R$ 100.00
Saque: R$ 50.00

Saldo: R$ 50.00
=========================================
Estrutura do Código 🛠️
Variáveis Principais:

saldo: Armazena o saldo atual da conta.
limite: Define o valor máximo permitido para um saque.
extrato: Registra o histórico de transações.
numero_saques: Conta o número de saques realizados no dia.
LIMITE_SAQUES: Define o número máximo de saques permitidos por dia.
Menu: Um loop while controla o fluxo do programa, exibindo o menu e processando a entrada do usuário.

Validações: Regras de negócio são verificadas antes de concluir cada operação, garantindo a consistência do sistema.

Contribuições 🤝
Sinta-se à vontade para contribuir com melhorias, novas funcionalidades ou refatorações. Basta abrir um pull request ou relatar um problema na aba de Issues.

Autor: tbarcelar
Licença: MIT 📜