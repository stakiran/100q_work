# 100q work
「ソフトウェアエンジニアに100の質問」を作ってるところ。

公開用はこっち → [100q](https://github.com/stakiran/100q)

## ビルダーについて

100の質問を作る際、いちいち質問番号を振るのがだるいので、質問一覧から番号付き質問一覧を生成する仕組みを導入しています。

[100q_src.md](100q_src.md) に所定フォーマットで質問を書き、[builder.py](builder.py) に食わせてやると、番号付きの [100q.md](100q.md) が生成されます。Requirement は Windows7+ と Python2.7 です。

## ライセンス

[100q.md](100q.md) と [100q_src.md](100q_src.md) のみ Public Domain です。

残りのファイルは全て [MIT License](LICENSE) です。

