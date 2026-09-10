# 📱 Projeto Celular - POO

Projeto desenvolvido em **Java** durante a aula de **Programação Orientada a Objetos (POO)**, realizada em **20/08/2026**.

## 📌 Sobre o projeto

Este projeto foi desenvolvido em **Java**, utilizando conceitos de **Programação Orientada a Objetos (POO)**. O objeto escolhido para representar esses conceitos foi um **celular**.

A classe `Celular` representa um aparelho do mundo real e possui características como **marca, modelo, nível de bateria e volume**, além de métodos que permitem alterar o estado do objeto.

## 🏷️ Atributos

A classe `Celular` possui os seguintes atributos:

| Atributo  | Descrição                                        | Exemplo           |
| --------- | ------------------------------------------------ | ----------------- |
| `marca`   | Representa a marca do celular.                   | Apple             |
| `modelo`  | Representa o modelo do celular.                  | iPhone 17 Pro Max |
| `bateria` | Representa a porcentagem de bateria do aparelho. | 50%               |
| `volume`  | Representa o nível de volume do aparelho.        | 40%               |

> 🔒 Os atributos são definidos como `private` para proteger o estado interno do objeto, aplicando o conceito de **encapsulamento**.

## ⚙️ Métodos

### 🔊 `aumentarVolume()`

O método `aumentarVolume(int quantidade)` aumenta o volume do celular de acordo com a quantidade informada.

**Regras de negócio:**

* A quantidade informada deve ser maior que `0`.
* O volume não pode ultrapassar `100`.

**Exemplo:**

```java
celular.aumentarVolume(20);
```

### 🔋 `carregarBateria()`

O método `carregarBateria(int quantidade)` aumenta a porcentagem de bateria do celular de acordo com a quantidade informada.

**Regras de negócio:**

* A quantidade informada deve ser maior que `0`.
* A bateria não pode ultrapassar `100%`.

**Exemplo:**

```java
celular.carregarBateria(30);
```

## 🧪 Testes

O projeto possui testes com **valores válidos e inválidos** para verificar o funcionamento das regras de negócio.

Foram testadas situações como:

* Aumento normal do volume.
* Aumento normal da bateria.
* Tentativa de ultrapassar `100%` de volume.
* Tentativa de ultrapassar `100%` de bateria.
* Entrada de valores inválidos.

Quando um valor inválido é informado, o estado do objeto **não é alterado**, evitando que ele fique inconsistente.

Para controlar essas situações, foi utilizada a estrutura condicional `if`.

## ▶️ Como executar

Para executar o projeto:

1. Clone este repositório.
2. Abra o projeto em uma IDE compatível com Java.
3. Localize o arquivo `Main.java`.
4. Execute o arquivo.

O `Main.java` instancia um objeto da classe `Celular` e realiza os testes dos métodos:

```java
aumentarVolume()
carregarBateria()
```

## 💻 Tecnologias utilizadas

* ☕ **Java**
* 🧩 **Programação Orientada a Objetos (POO)**
* 🔒 **Encapsulamento**
* 🧪 **Testes de regras de negócio**

---

📚 **Projeto desenvolvido para fins acadêmicos durante a aula de Programação Orientada a Objetos.**
