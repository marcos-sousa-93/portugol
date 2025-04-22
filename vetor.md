# Declaração de VETOR
```Portugol
  inteiro vetor1[5]
```
### Vetor1 inteiro de 5 espaços
|   0   |   1   |   2   |   3   |   4   |
|-------|-------|-------|-------|-------|
| vazio | vazio | vazio | vazio | vazio |

***

```Portugol
  caracter vetor2[10]
```

### Vetor2 caracter de 10 espaços
|   0   |   1   |   2   |   3   |   4   |   5   |   6   |   7   |   8   |   9   |
|-------|-------|-------|-------|-------|-------|-------|-------|-------|-------|
| vazio | vazio | vazio | vazio | vazio | vazio | vazio | vazio | vazio | vazio |

***

 ### Vetores iniciados

 ```Portugol
  real vetor3[2] = {1.4, 2.5}
```
### Vetor3 real de 2 espaços preenchidos
|   0   |   1   |
|-------|-------|
|  1.4  |  2.5  |

***

```Portugol
  logico vetor4[4] = {verdadeiro, falso, verdadeiro, verdadeiro}
```

### Vetor4 lógico de 4 espaços preenchidos
|   0   |   1   |   2   |   3   |
|-------|-------|-------|-------|
| verdadeiro | falso | verdadeiro | verdadeiro |

***

```Portugol
  cadeia vetor5[ ] = {"Questão", "fundamental"}
```

### Vetor5 cadeia com espaços não definido preenchidos
|   0   |   1   |
|-------|-------|
| "Questão" | "Fundamental" |

***

```Portugol
  // Mudando o valor do vetor5 na posição 0 de "Questão" para "Pergunta".
  vetor5[0] = "Pergunta"
```

### Vetor5 mudando o valor na posição 0 para "Pergunta"
|   0   |   1   |
|-------|-------|
| "Pergunta" | "Fundamental" |
