# Somatórios

Uma _soma_ ou _somatório_ é a adição de uma sequência de termos

$$a_1 + a_2 + ... + a_n$$

Que pode ser representada pela notação sigma:

$$\sum_{k=1}^n a_k = a_1 + a_2 + ... + a_n$$

- _n_: limite superior
- _k_: limite inferior
- _a_: termo a ser somado
- $a_k$: índice do termo

# Propriedades

## Limite superior 0

Quando o limite superior for 0, então o resultado do somatório é 0.
$$\sum_{k=1}^0 a_k = 0$$

## Somatório de constante

Quando uma constante há constante não acompanhada de variável, o resultado é o produto da constante com o limite superior.
$$\sum_{k=1}^n c = cn$$

## Distributividade

Quando uma constante é acompanhada de variável, a constante passa para a frente, multiplicando o resto do somatório.

$$\sum_{k=1}^n ca_k = c\sum_{k=1}^n a_k$$

## Associatividade

Quando há soma ou subtração no termo a ser somado, podemos separar cada parte da operação em um somatório próprio.
$$\sum_{k=1}^n (a_k \pm b_k) = \sum_{k=1}^n a_k \pm \sum_{k=1}^n b_k$$

## Somatório de 1

$$\sum_{k=m}^n 1 = n - 1 + m$$

## Somatório de uma progressão aritmética

$$\sum_{k=1}^n k = {n(n + 1)\over 2} $$

## Somatório do índice ao quadrado

$$\sum_{k=0}^n k^2 = {n(n + 1)(2n + 1) \over 6}$$

## Somatório do índice ao cubo

$$\sum_{k=0}^n k^3 = {n^2(n + 1)^2 \over 4}$$

## Somatório de série geométrica

$$\sum_{k=0}^n x^k = {x^{n + 1} - 1 \over x - 1}$$

## Série harmônica

$$\sum_{k=1}^n  {1 \over k} \approx ln + \gamma$$

Onde $\gamma \approx 0.5772$ (constante de Euler)

# Deslocando os limites da soma

$$\sum_{k=1}^n a_k = \sum_{k=0}^{n-1} a_{k+1}$$
