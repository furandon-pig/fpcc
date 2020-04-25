# fpcc
chibiccをもとに、自分でCコンパイラを実装してみるためのリポジトリです。

## メモ

### Intel記法でアセンブリ出力する

```sh
$ # gcc,clang共に"-masm=intel"オプションを使用する。
$ clang -masm=intel -S <c_source>
```

## キーワード

 * 再帰下降構文解析(Recursive Descent Parsing)

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

