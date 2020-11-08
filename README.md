# AtCoder
#AtCoderの問題の回答を保存するリポジトリとなる。

第 3 問: ABC 081 B - Shift Only
【問題概要】
黒板に NN 個の正の整数 A1,…,ANA1,…,AN が書かれています。
すぬけ君は，黒板に書かれている整数がすべて偶数であるとき，次の操作を行うことができます。

黒板に書かれている整数すべてを，22 で割ったものに置き換える。
すぬけ君は最大で何回操作を行うことができるかを求めてください。

【制約】

1≤N≤2001≤N≤200
1≤Ai≤1091≤Ai≤109
【数値例】
1)
　N=3N=3
　A=(16,12,24)A=(16,12,24)
　答え: 22
####################
第 4 問: ABC 087 B - Coins
【問題概要】
500 円玉を AA 枚、100 円玉を BB 枚、50 円玉を CC 枚持っています。これらの硬貨の中から何枚かを選び、合計金額をちょうど XX 円にする方法は何通りあるでしょうか？

【制約】

0≤A,B,C≤500≤A,B,C≤50
A+B+C≥1A+B+C≥1
50≤X≤2000050≤X≤20000
A,B,CA,B,C は整数である
XX は 5050 の倍数である
【数値例】
1)
　A=2A=2
　B=2B=2
　C=2C=2
　X=100X=100
　答え: 22
条件を満たす選び方は以下の 2 通りです。

500 円玉を 0 枚、100 円玉を 1 枚、50 円玉を 0 枚選ぶ
500 円玉を 0 枚、100 円玉を 0 枚、50 円玉を 2 枚選ぶ
