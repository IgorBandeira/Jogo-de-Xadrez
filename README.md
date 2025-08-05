# 🧩 Jogo de Xadrez no terminal

Uma implementação de um **jogo de xadrez via console**, desenvolvida em **C#**, ideal para praticar programação orientada a objetos (POO) e lógica de jogo.

---

## 🧠 Sobre o Projeto

Este projeto foi criado como parte do curso de C#, com foco em aplicar conceitos de POO como herança, encapsulamento, polimorfismo e exceções em um cenário real de jogo de xadrez.

Você terá um tabuleiro exibido no terminal, entrada de jogadas em notação tradicional (ex: `e2 e4`), validações de movimento, tratamento de exceções e regras especiais como roque, en passant e promoção.

---

## 🎯 Funcionalidades

- Impressão dinâmica do tabuleiro no console com distinção entre peças brancas e pretas.
- Movimentação das peças: torre, cavalo, bispo, rainha, rei e peão.
- Validações reforçadas:
  - Origem válida
  - Destino permitido
  - Movimentos possíveis
- **Tratamento de erros** personalizado com exceções.
- Regras especiais:
  - **Roque** (pequeno e grande)
  - **En passant**
  - **Promoção de peão**

---

## 🚀 Começando

### Executando o projeto

1. Compile e execute:

   ```bash
   cd xadrez-console
   dotnet run --project xadrez-console/xadrez-console.csproj
   ```

2. Digite suas jogadas em notação padrão, por exemplo:

   ```
   e2 e4
   g8 f6
   ```

3. Jogue até o **checkmate** ou até desistir.

---

## 📚 Conceitos de POO aplicados

- **Encapsulamento:** controle de acesso aos dados e regras internas do jogo
- **Herança:** peças compartilham uma estrutura comum
- **Polimorfismo:** cada peça executa suas próprias regras de movimento
- **Exceções personalizadas:** tratamento claro de erros durante a partida
- **Abstração:** divisão entre lógica do jogo e apresentação no console

---
