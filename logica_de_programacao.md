## Algoritmos com seleção

#### Seleção simples
~~~
if (<condition = true>) <then> {
    <instructions>
}
~~~

#### Seleção composta ou dupla
~~~
if (<condition = true>) <then> {
    <instructions>
} else <condition = false> {
    <instructions>
}
~~~

#### Seleção concatenada ou aninhada
~~~
if (<condition = true>) <then> {
    if (<condition = true>) <then> {
        <instructions>
    }
}
~~~

#### Seleção múltipla
`switch case`

---
## Algoritmos com repetição

#### Repetição com teste no ínicio
~~~
while (<condition = true>) <do> {
    <instructions>
}
~~~
- Um bloco de código será executado apenas enquanto a condição for **verdadeira**.

#### Repetição com teste no final
~~~
do {
    <instructions>
} while (<condition = false>)
~~~
- Um bloco de código é executado até uma condição enquanto a mesma for **falsa**. O bloco é encerrado quando a condição se torna **verdadeira**.

#### Repetição com variável de controle
~~~
for (<var init>, <var test>, <increment>) <do> {
    <instructions>
}
~~~