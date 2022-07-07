# Correção de algoritmos
 - Classes de problemas que podem ser resolvidos por algoritmos
    - Intratável.
    - Tratável.
    - Decidível.
    - Indecidível. 

--------
# Pertubação da soma

`Links: https://algol.dev/propriedades-dos-somatorios/`

### Propriedades
- Permutativa


  - $\sum_{k=1}^n  (x.n + y.n) = \sum_{k=1}^n x.i + \sum_{k=1}^n y.i$

- Associativa

    - $ \sum_{k=1}^n k.xi = k  . \sum_{k=1}^n xi $

- Comutativa

    - $\sum_{k=1}^p xi + \sum_{k=p+1}^n xi = \sum_{k=1}^n xi  $

-------
### Exemplos

Pertubação da soma

$\sum_{k=1}^n  k^2$

Resolução:

$k_0 + \ \sum_{k=2}^{n+1} k^2 = Sn + k_{n+1}$
$ $

### 

----- 

## Relações de recorrência 

### Definição

$S_5 = \sum_{1<=k<=5} K = 5 + 4 + 3 + 2 + 1$

$S_5 = \sum_{1<=k<=5} K = 5 + 4 + 3 + 2 + (1)_{S_1}$

$S_5 = \sum_{1<=k<=5} K = 5 + 4 + 3 + (2 + (1)_{S_1})_{S_2}$

$S_5 = \sum_{1<=k<=5} K = 5 + 4 + (3 + (2 + (1)_{S_1})_{S_2})_{S_3}$

$S_5 = \sum_{1<=k<=5} K = 5 + (4 + (3 + (2 + (1)_{S_1})_{S_2})_{S_3})_{S_4}$

$S_5 = \sum_{1<=k<=5} K = (5 + (4 + (3 + (2 + (1)_{S_1})_{S_2})_{S_3})_{S_4})_{S_5}$

---
$S_5 = 5 + S_4$

$S_4 = 4 + S_3$

...

$S_1 = 1$


...

------------

$S_1 = a_1,    n = 1 $


$S_n = = a_n + S_{n-1}, n > 1 $ 

### Conjunto de duas equações
-  Equação geral definida em termos de valores anteriores.
- Caso base: equação com valor de parada (Valor de contorno).

$S_1 = a_1 , n = 1$

$ S_n =  a_n + S_{n-1}, n>1$
- É uma outra forma de escrever $\sum$
- Resolvendo-a encontramos como solução sua forma fechada, (Fórmula fechada).

## Forma Fechada
Em geral, uma relação de recorrência reduz-se a um somatório que reduz-se a uma forma fechada.

$S_1 = 1$

$S_n = n + S_{n-1}$

------
$\sum_{1<=k<=n} k$

----
## $\frac{n(n+1)}{2}$

### Técnicas de Resolução 
- **Substituição pra frente**.
- **Substituição pra trás**.
- **Cancelamento algébrico**.
- Adivinhe e prove por indução
- Análise da árvore de recorrência.
- Teorema mestre, etc...



