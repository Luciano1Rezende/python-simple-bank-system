# Simple Bank System 🏦
![Status](https://img.shields.io/badge/status-em%20desenvolvimento-blue?style=for-the-badge)

## 📖 Sobre o Projeto

Este projeto é um sistema bancário simples desenvolvido em Python como um desafio de programação. A aplicação funciona via linha de comando (CLI) e permite ao usuário realizar operações bancárias básicas como depósitos, saques e visualização de extratos. Além disso, o sistema possui funcionalidades para criar novos usuários e contas correntes.

O objetivo principal foi aplicar conceitos fundamentais de Python, como:
- Funções
- Manipulação de strings
- Estruturas de dados (listas e dicionários)
- Lógica de programação

---

## ⚙️ Funcionalidades

O sistema oferece o seguinte menu de operações:

- **[d] Depositar:** Adicionar um valor ao saldo da conta.
- **[s] Sacar:** Retirar um valor do saldo, respeitando um limite por saque e um número máximo de saques diários.
- **[e] Extrato:** Exibir todas as transações realizadas (depósitos e saques) e o saldo atual da conta.
- **[nu] Novo Usuário:** Cadastrar um novo cliente com nome, data de nascimento, CPF e endereço.
- **[nc] Nova Conta:** Criar uma nova conta corrente vinculada a um usuário existente.
- **[lc] Listar Contas:** Exibir a lista de todas as contas cadastradas.
- **[q] Sair:** Encerrar a aplicação.

---

## 🛠️ Tecnologias Utilizadas

O projeto foi desenvolvido inteiramente com:
- **Python 3**

Não há necessidade de instalar bibliotecas externas.

---

## 🚀 Como Executar

Para executar o projeto localmente, siga os passos abaixo:

1.  **Clone o repositório (escolha uma das opções):**
    
    * HTTPS:
        ```bash
        git clone [https://github.com/Luciano1Rezende/python-simple-bank-system.git](https://github.com/Luciano1Rezende/python-simple-bank-system.git)
        ```
    * SSH:
        ```bash
        git clone git@github.com:Luciano1Rezende/python-simple-bank-system.git
        ```

2.  **Navegue até o diretório do projeto:**
    ```bash
    cd python-simple-bank-system
    ```

3.  **Execute o script Python:**
    ```bash
    python main.py
    ```
    *(ou `python3 main.py`, dependendo da sua configuração)*

Pronto! O menu do sistema bancário aparecerá no seu terminal.

---

## 📈 Possíveis Melhorias Futuras

- [ ] Implementar orientação a objetos para modelar `Cliente`, `Conta` e `Transacao`.
- [ ] Adicionar persistência de dados (salvando as informações em arquivos .json ou em um banco de dados como SQLite).
- [ ] Criar validações mais robustas para os dados de entrada (ex: formato de CPF, data de nascimento).
- [ ] Adicionar testes unitários para garantir a qualidade do código.

---

## ✍️ Autor

Feito por **Luciano Rezende**.

[![LinkedIn](https://img.shields.io/badge/linkedin-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/seu-perfil-linkedin/)
[![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Luciano1Rezende)
