<p align="center">
  <img src="/imagem2.png" alt="Banner - Sistema Bancário em Python" width="800">
</p>

<h1 align="center">💰 Sistema Bancário em Python</h1>


# 🏦 Otimizando o Sistema Bancário com Funções em Python

Este projeto apresenta a evolução de um sistema bancário simples desenvolvido em Python. A primeira versão foi criada utilizando estruturas básicas, como condicionais e variáveis globais. A versão otimizada aprimora a organização do código utilizando **funções**, parâmetros posicionais e nomeados, além de incorporar manipulação de **usuários e contas bancárias**.

---

## ✨ Melhorias Implementadas

| Versão Antiga | Versão Otimizada |
|--------------|-----------------|
| Uso de variáveis globais | Separação de responsabilidades com funções |
| Funções limitadas ao depósito, saque e extrato | Agora inclui criação de usuário e conta bancária |
| Código menos modular e difícil de manter | Código organizado e reutilizável |
| Menu simples | Menu expandido com novas operações |

---

## 🧰 Funcionalidades

- **Depositar** valores em conta
- **Sacar** com limite por operação e quantidade máxima por dia
- **Exibir extrato** das movimentações
- **Criar novo usuário**
- **Criar nova conta bancária**
- **Listar contas cadastradas**

---

## 🧑‍💻 Tecnologias Utilizadas

- Linguagem: **Python 3**
- Biblioteca auxiliar: `textwrap` (para formatação)

---

## 📂 Estrutura do Código

```python
def menu()
def depositar(saldo, valor, extrato, /)
def sacar(*, saldo, valor, extrato, limite, numero_saques, limite_saques)
def exibir_extrato(saldo, /, *, extrato)
def criar_usuario(usuarios)
def filtrar_usuario(cpf, usuarios)
def criar_conta(agencia, numero_conta, usuarios)
def listar_contas(contas)
def main()
Cada função é responsável por uma tarefa específica, tornando o código mais legível, limpo e escalável.

▶️ Como Executar
Certifique-se de ter o Python 3 instalado.

Salve o código otimizado em um arquivo, por exemplo:

Copiar código
desafio1.py
Execute no terminal:

bash
python desafio1.py.py
📝 Exemplo de Uso
Ao rodar o programa, será exibido o menu:

csharp

=============== MENU ================
[d]  Depositar
[s]  Sacar
[e]  Extrato
[nc] Nova conta
[lc] Listar contas
[nu] Novo usuário
[q]  Sair
=>
Basta digitar a letra correspondente à operação desejada.

🎯 Objetivo do Projeto
Este projeto foi desenvolvido para praticar:

Modularização em Python

Manipulação de listas e dicionários

Regras de negócio e validação

Organização de código seguindo boas práticas

👨‍🏫 Autor: Vandilma Cândido
Projeto desenvolvido para fins de estudo e aperfeiçoamento em lógica de programação e boas práticas com Python.

