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
####################
第 6 問: ABC 088 B - Card Game for Two 
【問題概要】
NN 枚のカードがあり、ii 枚目のカードには aiai という数が書かれています。
Alice と Bob はこれらのカードを使ってゲームを行います。ゲームでは 2 人が交互に 1 枚ずつカードを取っていきます。Alice が先にカードを取ります。
2 人がすべてのカードを取ったときゲームは終了し、取ったカードの数の合計がその人の得点になります。2 人とも自分の得点を最大化するように最適戦略をとったとき、Alice は Bob より何点多くの得点を獲得できるかを求めてください。

【制約】

NN は 11 以上 100100 以下の整数
aiai は 11 以上 100100 以下の整数
【数値例】
1)
　N=3N=3
　a=(2,7,4)a=(2,7,4)
　答え: 55
以下が最適です:

1 ターン目: Alice が 7 を取る
2 ターン目: Bob が 4 を取る
3 ターン目: Alice が 2 を取る
Alice は 7 + 2 = 9 点、Bob は 4 点を獲得するので、その差は 9 - 4 = 5 点です。

