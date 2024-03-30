## 概要
下記問題を解く際に、誤差でエラーを吐かれる可能性が非常に高い。<br>
https://yukicoder.me/problems/no/350 <br>
それを防ぐにはDecimalライブラリを使用すると簡潔に解決することができる。

```Python:Decimal.py
# import
from decimal import Decimal
# input
v,t = map(Decimal,input().split())
# calculate
ans = v*t
# output
print(int(ans))
```

実際の提出<br>
https://yukicoder.me/submissions/966086
