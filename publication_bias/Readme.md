# 概要

# 個人的なモチベ
この章はサーベイなしで書きます。エッセイはサーベイ後に書き始めます。下記についてはおそらく専門家から見たらめちゃくちゃだと思いますが、フィードバック受けながら洗練させていきます・・・。
- 修士の研究で仮説検定を取り扱っていたのですが、修了して社会人になった今もどうもしっくり来ません
- 「有意差がある」と言われたものだけ論文として出版されて、論文全体で間違いがどれくらいの割合になるのか疑問のまま過ごしていました([出版バイアス](https://www.jspt.or.jp/ebpt_glossary/publicationbias.html)のことを深く知りたいということです)。
  - 有意水準5%だから5%というわけじゃなくて、「帰無仮説が正しい」実験と「帰無仮説が誤っている」実験の割合も関係するのでもっと複雑な感じです
    - 実際「[再現性の危機](https://www.jstage.jst.go.jp/article/sjpr/59/1/59_3/_pdf)」があったとき再現しない実験は5%じゃなかったですし。
      - 大規模な追試プロジェクトの結果，社会心理で 25%，認知心理で 50% ほどしか結果の再現ができないことが報告された（Open Science Collaboration, 2015）。([心理学における再現可能性危機：問題の構造と解決策](https://www.jstage.jst.go.jp/article/sjpr/59/1/59_3/_pdf)より引用)
  - 単純なベイズの問題にも見えますが、「尤度」と「棄却域」は似て非なるものなのでよく考えたいです
- p-hackingとかHARKINGとかやってるのも考慮できるかもしれませんが最初はシンプルに考えます
- 素人っぽい構想
  - 統計的仮説検定をホーア論理で形式化を行っている論文がある([Kawamoto, Y., Sato, T., & Suenaga, K. (2021, September). Formalizing Statistical Beliefs in Hypothesis Testing Using Program Logic. In KR (pp. 411-421).](https://staff.aist.go.jp/yusuke.kawamoto/papers/KR2021long.pdf)。これを拡張したら出版バイアスの仕組みがわかるかも？
    - マルチエージェントといって複数人の相互作用を形式的に記述する方法があるらしい([参考](https://www.jstage.jst.go.jp/article/jjsai/25/3/25_429/_pdf))。もしかしたら関係ある？
  - こんなことするより素朴に計算した方がいいかも。やってみたら大した話でもない気がする。 
  - 基本的には定量的な出版バイアスの理論がほしいです。サーベイの結果定量的な解析をやっている人がいるまたは難しいとわかったら、論理としての形式化に重点をおいて考えます
    - 2025/02/22時点で[Kawamoto, Y., Sato, T., & Suenaga, K. (2021, September). Formalizing Statistical Beliefs in Hypothesis Testing Using Program Logic. In KR (pp. 411-421).](https://staff.aist.go.jp/yusuke.kawamoto/papers/KR2021long.pdf)の引用3件を見た結果まだ出版バイアスを論理として形式化してる人はいないと思われる。
- 上記の話はベイズ検定だとどうなるんだろう
