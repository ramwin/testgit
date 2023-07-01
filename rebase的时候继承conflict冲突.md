目前在基础分支(rebase_base)

1. A
2. B
3. C
4. D
5. E

之后
(rebase_a)A分支: 第一行变成A, 第三行变成3
(rebase_b)B分支: 把第五行变成E, 第三行变成c

然后合并A, B分支. 冲突修复时, 把第三行变成了C

最后rebase. 希望同时保留第一, 三, 五行的变更
