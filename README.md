# Máquina de Turing - Conversor de Número por Extenso

Este repositório contém uma **Máquina de Turing** criada no programa **JFLAP**. A máquina é capaz de converter um número inteiro para sua forma por extenso.

## 🛠️ Funcionalidades

- Aceita como entrada um número inteiro entre `0` e `999999`.
- Gera como saída o número por extenso em português, sem uso de acentos e todo em minúsculas.
  - Exemplo: Entrada: `123` → Saída: `cento e vinte e tres`

## 🚀 Como Usar

1. Abra o arquivo `numero_extenso.jff` no **JFLAP**.
2. Escolha o modo **Input**.
3. Insira um número inteiro entre `0` e `999999` na fita.
4. Clique em **Run** para executar a máquina.
5. O número será exibido por extenso na fita como saída.

## 📝 Exemplos de Entrada e Saída

| Entrada | Saída                  |
|---------|------------------------|
| `0`     | zero                  |
| `15`    | quinze                |
| `123`   | cento e vinte e tres  |
| `1001`  | mil e um              |
| `999999`| novecentos e noventa e nove mil novecentos e noventa e nove |

## ⚠️ Limitações

- A máquina aceita apenas números inteiros entre `0` e `999999`.
- A saída não inclui acentuação gráfica (ex.: "três" será exibido como "tres").
