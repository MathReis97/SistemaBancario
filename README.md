# SistemaBancario
# 💳 Sistema Bancário em Java

Este é um projeto simples de um **sistema bancário orientado a objetos** em Java, com funcionalidades básicas como depósito, saque e aplicação de juros, utilizando os princípios de herança, abstração e interfaces.

---

## 📁 Estrutura do Projeto

├── Cliente.java
├── Conta.java
├── ContaCorrente.java
├── ContaPoupanca.java
├── Main.java
├── OpercaoBancaria


---

## 🚀 Funcionalidades

- Criar contas correntes e poupança
- Realizar depósitos
- Realizar saques
- Aplicar juros (somente na conta poupança)
- Exibir dados das contas

---

## 🧠 Conceitos de Programação Utilizados

- Programação Orientada a Objetos (POO)
  - Abstração (`Conta` como classe abstrata)
  - Herança (`ContaCorrente` e `ContaPoupanca` estendem `Conta`)
  - Polimorfismo (sobrescrita de métodos)
  - Interface (`OpercaoBancarias`)
- Encapsulamento (uso de getters/setters)
- Boa prática de separação de classes

---

## 💻 Como Executar

1. **Clone o repositório:**

```bash
git clone https://github.com/seu-usuario/seu-repositorio.git
cd seu-repositorio
javac br/com/*.java
java br.com.Main



======= Bem vindo ao BANCO =======
Qual Conta deseja ultilizar? 
1 - depositar Conta Corrente
2 - depositar Conta Poupança
3 - para sacar Conta Corrente
4 - para sacar Conta Poupança
5 - para exibir informação
0 - para sair

🧑‍💻 Autor --https://github.com/MathReis97
