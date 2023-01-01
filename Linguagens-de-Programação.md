# As linguagens de programação

## Padronizações

### Textuais 

* Lista de instruções (IL)
* Texto estruturado (ST)

### Gráficas

* Diagrama Ladder (LD)
* Diagrama de blocos funcionais (FDB)

### Estruturação de Programas (Textual ou Gráfica)

* Sequênciamento Gráfico de Funções (SFC)

# IL (Instruction List)

* LD -> declarando varíavel
* AND -> Porta lógica E nome da outra variavel
* ST -> Saída que será ativada

```
    LD i00
    AND i01
    ST q00
```
(Se o i00 (1) and i01 (1) -> Saída q00 (1))
(se i00 (0) and i01 (1) -> Saída q00 (0))
(se i00 (1) and i01 (0) -> Saída q00 (0))

# ST (linguagem High-level)

``` q00 := i00 AND i01; ```

q00 é igual a i00 E i01

# FBD (Function block diagram)

* Baseada nos circuitos eletronicos

<img scr="./FBD.png">

# LD (Ladder diagrama eletrico)

<img scr="./LD.png" width="40">

# SFC (Sequenciamento grafico de funções) Fluxograma

# Principais

-Ton -> liga bobina após um tempo 
-Tof -> desliga a bobina após um tempo 
-TS -> deixa a bobina ligada durante um tempo
-Add -> Soma
-Mul -> Multiplicação
-Sub -> Subtração
-Div -> Divisão
-Contato aberto -> passa energia após ser fechado 
-Contato fechado -> corta energia após ser aberto
-Set -> bobina é acionada e mantém 
-Reset -> reseta e desliga a bobina que foi setada