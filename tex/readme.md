
# codecogs.com
https://www.codecogs.com/latex/eqneditor.php

```html
<img src="https://latex.codecogs.com/gif.latex?\int_a^bf(x)dx" />
```
<img src="https://latex.codecogs.com/gif.latex?\int_a^bf(x)dx" />


## stats

### 一様分布 uniform distribution

離散型、および連続型確率分布の一つで、確率密度関数が常に一定の値をとる分布のこと。期待値と分散は以下の式で表される。


<離散型> 確率変数xが1以上n以下の自然数をとるとき
```tex
E(X) = \frac{n + 1}{2}
```
<img src=https://latex.codecogs.com/gif.latex?E%28X%29%20%3D%20%5Cfrac%7Bn%20&plus;%201%7D%7B2%7D>

```tex
V(X) =  \frac{n^2 - 1}{12}
```
<img src=https://latex.codecogs.com/gif.latex?V%28X%29%20%3D%20%5Cfrac%7Bn%5E2%20-%201%7D%7B12%7D>

<連続型> 確率変数xがa以上b以下の値をとるとき
```tex
E(X) = \frac{a + b}{2}
```
<img src=https://latex.codecogs.com/gif.latex?E%28X%29%20%3D%20%5Cfrac%7Ba%20&plus;%20b%7D%7B2%7D>

```tex
V(X) = \frac{(b - a)^2}{12}
```
<img src=https://latex.codecogs.com/gif.latex?V%28X%29%20%3D%20%5Cfrac%7B%28b%20-%20a%29%5E2%7D%7B12%7D>


### 二項分布 binominal distribution

```tex
1回の試行に対して2種類の結果A、Bが生じ、Aが起こる確率をpとする。
さらに、n回の試行においてAが生じる回数を確率変数Xとする。
このときがある値となる確率は、以下の式で表される。

P(X = x) = {}_n\mathrm{C}_xp^x(1 - p)^{n - x}
```
<img src=https://latex.codecogs.com/gif.latex?P%28X%20%3D%20x%29%20%3D%20%7B%7D_n%5Cmathrm%7BC%7D_xp%5Ex%281%20-%20p%29%5E%7Bn%20-%20x%7D>


```tex
E(X) = np
```
<img src=https://latex.codecogs.com/gif.latex?E%28X%29%20%3D%20np>

```tex
V(X) = np(1 - p)
```
<img src=https://latex.codecogs.com/gif.latex?V%28X%29%20%3D%20np%281%20-%20p%29>
