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