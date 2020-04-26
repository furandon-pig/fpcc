# fpcc
chibiccをもとに、自分でCコンパイラを実装してみるためのリポジトリです。

## メモ

### サンプルの作成

 * [ステップ4：エラーメッセージを改良](https://www.sigbus.info/compilerbook#%E3%82%B9%E3%83%86%E3%83%83%E3%83%974%E3%82%A8%E3%83%A9%E3%83%BC%E3%83%A1%E3%83%83%E3%82%BB%E3%83%BC%E3%82%B8%E3%82%92%E6%94%B9%E8%89%AF)から続ける。

### Intel記法でアセンブリ出力する

```sh
$ # gcc,clang共に"-masm=intel"オプションを使用する。
$ clang -masm=intel -S <c_source>
```

## キーワード

 * 再帰下降構文解析(Recursive Descent Parsing)
 * トークン(token)
   * トークナイズする: 文字列をトークン列に分割すること
   * 文字列をトークンに分割すると、トークンを分類して型を付けることができるようになる。

## 参考URL

 * [低レイヤを知りたい人のためのCコンパイラ作成入門](https://www.sigbus.info/compilerbook)
 * [Cコンパイラ作成のオンラインコースを始めます](https://rui314.github.io/course2020)
 * [C-2020](https://c-2020.slack.com)
 * [rui314/chibicc/](https://github.com/rui314/chibicc/)
 * [Compiler Explorer](https://godbolt.org/)(godbolt)
   * コードを入力すると、それに対応するアセンブリ出力をリアルタイムに表示してくれるサイト。
 * [furandon-pig/chibicc](https://github.com/furandon-pig/chibicc)
   * [「低レイヤを知りたい人のためのCコンパイラ作成入門」読書会(6)メモ](https://github.com/furandon-pig/chibicc/issues/3)
   * [「低レイヤを知りたい人のためのCコンパイラ作成入門」読書会(5)メモ](https://github.com/furandon-pig/chibicc/issues/1)
 * [「低レイヤを知りたい人のためのCコンパイラ作成入門」読書会](https://c-compiler.connpass.com/)

