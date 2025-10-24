# 🏦 Aplicativo de Controle de Transações Financeiras com POO

Este projeto é uma **aplicação Java orientada a objetos**, desenvolvida com o objetivo de **consolidar conceitos fundamentais da Programação Orientada a Objetos (POO)**, como:

* 🧬 **Herança**
* 🔒 **Encapsulamento**
* 🧠 **Polimorfismo**
* 🧩 **Abstração**
* ♻️ **Reuso de código**

---

## 💡 Sobre o Projeto

A aplicação simula um **sistema bancário básico**, permitindo que o usuário:

* Crie diferentes tipos de contas (corrente, poupança, etc.);
* Realize **depósitos**, **saques** e **transferências via PIX**;
* Crie e gerencie **investimentos**;
* Acompanhe o **histórico de transações** de cada conta.

---

## ⚙️ Tecnologias Utilizadas

* **Java 17+**
* **Paradigma de Programação Orientada a Objetos (POO)**
* **IntelliJ IDEA / Gradle** para gerenciamento do projeto
* (Opcional) **Lombok** para redução de código boilerplate

---

## 🚀 Como Executar o Projeto

1. Clone este repositório:

   ```bash
   git clone https://github.com/DarkGambite/Aplicativo-de-Controle-de-Transacoes-Financeiras-com-POO.git
   ```

2. Abra o projeto no **IntelliJ IDEA** (ou outra IDE compatível).

3. Garanta que o **JDK 17+** esteja configurado corretamente.

4. Execute a classe principal:

   ```
   br.com.dio.Main
   ```

---

## 🧱 Estrutura Básica do Projeto

```
src/
 └── main/
      └── java/
           └── br/com/dio/
                ├── Main.java
                ├── model/
                │    ├── Conta.java
                │    ├── ContaCorrente.java
                │    ├── ContaPoupanca.java
                │    └── Investimento.java
                ├── service/
                │    ├── TransacaoService.java
                │    └── PixService.java
                └── util/
                     └── HistoricoTransacoes.java
```

---

## 📘 Conceitos Aplicados

| Conceito            | Aplicação no Projeto                                                   |
| ------------------- | ---------------------------------------------------------------------- |
| **Herança**         | Classes de conta especializadas derivam de uma classe base `Conta`.    |
| **Encapsulamento**  | Atributos privados com getters/setters controlam o acesso.             |
| **Polimorfismo**    | Métodos sobrescritos permitem comportamentos diferentes em subclasses. |
| **Abstração**       | Classes e métodos abstratos definem estruturas gerais do sistema.      |
| **Reuso de código** | Serviços e utilitários são compartilhados entre múltiplas classes.     |

---

#
