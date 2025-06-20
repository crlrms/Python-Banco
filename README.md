# 🏦 Sistema Bancário em Python

Um sistema bancário simples desenvolvido em Python, utilizando Programação Orientada a Objetos (POO) para gerenciar clientes, contas correntes e transações financeiras.

## 📋 Funcionalidades

### 👤 Cadastro de Clientes
- ✔️ Cadastro de pessoas físicas com:
  - Nome completo
  - CPF (único)
  - Data de nascimento
  - Endereço completo
- ✔️ Verificação de CPF já cadastrado

### 💰 Operações Bancárias
| Operação       | Descrição                                  | Limites/Restrições                     |
|----------------|-------------------------------------------|----------------------------------------|
| **Depósito**   | Adicionar fundos à conta                  | Apenas valores positivos               |
| **Saque**      | Retirar dinheiro da conta                 | Limite de R$500 por saque              |
|                |                                           | Máximo 3 saques diários                |
| **Extrato**    | Visualizar histórico de transações        | Mostra todas as movimentações          |
|                |                                           | Exibe saldo atual                      |

### 🏛️ Gerenciamento de Contas
- ✨ Criação de contas correntes vinculadas a clientes
- 📜 Listagem completa de todas as contas
- 🔄 Cada cliente pode ter múltiplas contas
- ⏳ Registro automático de data/hora nas transações

## 🚀 Como Executar

1. Clone o repositório:
   ```bash
   git clone https://github.com/crlrms/Python-Banco
2. Execute o código:
    ```bash
   python banco_python.py

3. Use o menu interativo:
```
================ MENU ================
[d]    Depositar
[s]    Sacar
[e]    Extrato
[nc]   Nova Conta
[lc]   Listar Contas
[nu]   Novo usuário
[q]    Sair
=====================================

⚠️ Limitações Atuais

    🧹 Dados são armazenados apenas em memória (não persistem após fechar o programa)
    💻 Interface apenas via terminal
