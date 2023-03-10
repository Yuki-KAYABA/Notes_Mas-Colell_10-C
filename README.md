# Notes: Mas-Colell 10.C Partial Equilibrium Competitive Analysis

実証IOは基本的に特定のマーケットにフォーカスした部分均衡分析であるため考え方を整理しておく。

Partial equiliburium analysis is justified by the following reasons:
- When the expenditure on the good under study is a small portion of a counsumer's total expenditure, only a small fraction of any additional doller of wealth will be spent on this good; consequently, we can expect wealth effects for it to be small.
- With similarly dispersed substitution effects, the small size of the market under study shiould lead the prices of other goods to be appoximately unaffected by changes in this market.

→要は他の市場における財との所得効果・代替効果が小さく、他の市場の需要・価格に影響をおよぼさない場合部分均衡分析が正当化される。

## Settings
- Each consumer $i = 1, ..., I$ has a utility function: 
$$u_{i}(m_{i}, x_{i}) = m_{i} + \phi_{i}(x_{i})$$
where $x_{i}$ and $m_{i}$ denote consumer $i$'s consumption of good $l$ and thte numeraire, respectively.
→上記justificationの通り、所得効果のないモデルを考えたいので準線形の効用関数を考える。

- $\phi^{'}_{i}(x_{i}) > 0$ and $\phi^{''}_{i}(x_{i}) < 0$ at all $x_{i} \geq 0$.
- Normalize $\phi_{i}(0) = 0$
