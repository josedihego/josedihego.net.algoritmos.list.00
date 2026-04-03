# QUESTÕES

**[jose.dihego@ifba.edu.br](mailto:jose.dihego@ifba.edu.br)**

---

## ⚠️ LEIA ISSO ABAIXO ⚠️

* **EQUIPE: 2 discentes - Envio: Classroom - Somente um membro deve enviar**
* **Nome da equipe deve ser adicionado como comentário nas primeiras linhas do código fonte**
* **Deve ser enviado um único arquivo `.c` por questão. Nenhum outro arquivo deve ser enviado**
* **Não coloque nenhum endereço relativo ao seu computador, pois executarei no meu computador**
* **A interpretação da entrada e saída faz parte das questões**
* **Nenhuma linha da entrada ou saída terá mais que 500 caracteres**

---

## 1)

Considere as seguintes entrada e saída abaixo:

### Entrada (`L0Q1.in`)

```txt
points (-2,-1) (4,2) (4,0) (2,2) (8,6)
points (41,0) (13,0) (-23,-14) (13,44) (46,19) (-22,-7) (-7,41) (-13,35)
```

### Saída (`L0Q1.out`)

```txt
points (-2,-1) (2,2) (4,0) (4,2) (8,6) distance 18.75 shortcut 12.21
points (13,0) (-22,-7) (-23,-14) (-13,35) (41,0) (-7,41) (13,44) (46,19) distance 307.87 shortcut 64.35
```

### Sobre a entrada

A cada linha um `points` marca o início de uma lista de pontos no espaço bidimensional.

### Sobre a saída

1. Ordenar todos os pontos conforme suas **distâncias Euclidianas em relação à origem (0,0)**:

   $$
   d = \sqrt{x^2 + y^2}
   $$

2. Exibir a distância total Euclidiana (`distance`) considerando os pontos na mesma ordem em que aparecem na entrada.

3. Exibir a distância (`shortcut`) entre o **primeiro e o último ponto** da entrada.

---

## 2)

Considere as seguintes entrada e saída abaixo:

### Entrada (`L0Q2.in`)

```txt
maria 3.15 jose 4 8 -1 12.7 (-1,-1) julia (-0.5,-0.5)
74.5 3.15 jose 4 8 -1 12.7 (8,2) carlos (-0.5,-0.5)
LYyEThB ORaS 87 20 -6
```

### Saída (`L0Q2.out`)

```txt
str:jose julia maria int:-1 4 8 float:3.15 12.7 p:(-0.5,-0.5) (-1,-1)
str:carlos jose int:-1 4 8 float:3.15 12.7 74.5 p:(-0.5,-0.5) (8,2)
str:LYyEThB ORaS int:-6 20 87 float: p:
```

### Descrição

Esta questão consiste em:

* Ler uma lista contendo:

  * **strings**
  * **inteiros**
  * **reais**
  * **pontos 2D**

### Saída

Ordenar separadamente:

* `str:` → ordem alfabética
* `int:` → ordem crescente
* `float:` → ordem crescente
* `p:` → ordem crescente pela distância à origem:

$$
d = \sqrt{x^2 + y^2}
$$

---

## ⚠️ REGRAS IMPORTANTES ⚠️

* **Não existem linhas em branco na entrada**
* **Não podem existir espaços em branco no início nem no final**
* **Comparação é feita com `strcmp` (C)**
* **Espaços, maiúsculas, minúsculas e acentos importam**
* **Cada linha é independente**
* **Cada linha de entrada gera exatamente uma linha de saída**
* **Número de linhas de saída = número de linhas de entrada**
* **Dúvidas: atendimento presencial, e-mail ou Classroom**
* **A entrada e saída são a lei**

---
