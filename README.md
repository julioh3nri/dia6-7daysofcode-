
---

### **Dia 6 - Remoção de Arrays**

```markdown
# Dia 6 - Remoção de Arrays

No sexto dia, focamos na **remoção de itens** de arrays. Aprendemos métodos como:

- `pop()`
- `shift()`
- `splice()`

Esses métodos são importantes para modificar dinamicamente os arrays durante a execução do programa.

## Objetivos:
- Remover elementos de um array.
- Usar diferentes métodos de remoção de elementos.

## Exemplos:
```js
let lista = ["maçã", "banana", "laranja"];

// Remover o último item
lista.pop();
console.log(lista); // ["maçã", "banana"]

// Remover o primeiro item
lista.shift();
console.log(lista); // ["banana"]

// Remover elementos em posições específicas
lista.splice(0, 1);
console.log(lista); // []
