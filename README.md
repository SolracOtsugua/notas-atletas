# 🏅 Projeto: Cálculo de Média dos Atletas

## 🧩 Descrição
Este projeto foi desenvolvido como parte de um exercício de lógica de programação utilizando **JavaScript**.  
O objetivo é criar uma aplicação capaz de **calcular a média das notas** de atletas em uma competição de ginástica artística.

A média é calculada **com base nas três notas centrais**, ou seja, **desconsiderando a maior e a menor nota** de cada atleta.

---

## 📊 Regras da competição
- Cada atleta recebe **5 notas** (entre 1 e 10).
- As notas são fornecidas por 5 jurados.
- A **média válida** é calculada após remover a **maior** e a **menor** nota.
- O resultado final exibe:
  - Nome do atleta
  - Notas obtidas
  - Média válida

---

## 🧮 Exemplo de entrada

```js
let atletas = [
  { nome: "Cesar Abascal", notas: [10, 9.34, 8.42, 10, 7.88] },
  { nome: "Fernando Puntel", notas: [8, 10, 10, 7, 9.33] },
  { nome: "Daiane Jelinsky", notas: [7, 10, 9.5, 9.5, 8] },
  { nome: "Bruno Castro", notas: [10, 10, 10, 9, 9.5] }
];
