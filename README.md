このREADMEファイルはMarkdown記法の説明をしています。
Markdown記法で書いた文章の改行はHTML同様にファイル内の改行コードを認識して入るわけではありません。意図して改行したい場合には、行末に半角スペースを2つ連続して入力しておくと  
このように改行できます。ただし、半角スペースを2つ連続して挿入されていることがエディタによっては分かりづらいので、エディタ上の設定で編集中に表示して分かるようにする工夫は必要な気がする。すぐ下に何らかの要素が来る場合には自動で改行することになるため、意図して改行するという使い方がなかなか難しいところ。

# 箇条書きについて
以下で箇条書きをしています。
* これはGitHubを使う実験のプロジェクトです
* Markdown記法を使ってREADME.mdを書いています

罫線も引くことができます。罫線を引くと自動的に「その罫線の前にある文章」の文字サイズが変更されます。段落を分けておけば、文字サイズ変更の影響を避けることができます。

以下はその例です。-を連続して罫線をこの下に挿入しています。
-------------------------
上記の方法で罫線を引いた場合には、その罫線の前にある文章が2番目に大きい見出しと同じ文字サイズになります。

=を連続して罫線をこの下に挿入しています。この場合には文字サイズが大きくなります。
=========================
上記の方法で罫線を引いた場合にはその前にある文章が1番目に大きい見出しと同じ文字サイズになります。「罫線の前」にある文字サイズが自動的に変更されてしまうので、罫線を挿入する場合には注意する必要があります。
Markdownはとっても便利な記法です。HTMLは文章の構造を記述する言語であり、CSSは文章の見え方を記述する言語です。構造(意味)と見え方が区別されていないという意味では初期のHTMLに近い感覚かもしれません。

改行文字を連続すると、段落を分けることができます。この辺りはHTMLに近い感覚です。

もちろん見出しを作って、文字の大きさを変更することもできます。
# 1番大きい見出し#
見出しのタイトルを書くには良い大きさです。とりあえず見出しとして使いたい文字の大きさになるので、見出しを作る際にはあまり深く考えずに使い、必要に応じて見出しの大きさを細かく分けていくというのが良いかもしれません。
## 2番目に大きい見出し##
少し小さい見出しには良い大きさだけど3番目との使い分けが難しいかも
### 3番目に大きい見出し###
ちょっとした見出しには良い大きさ
#### 4番目に大きい見出し####
通常の文字と同じ大きさ。文字がボールドになるので、その部分で区別できるのなら有用かも。4番目の大きさでも可読性としてはギリギリな気もしたり。
##### 5番目に大きい見出し#####
表示できるサイズとしては一番小さい。通常の文字サイズよりもさらに小さい。
###### 6番目に大きい見出し######
表示できる文字サイズで色を少し薄くしたもの。  

1番目と2番目の見出しでは見出しの後に罫線が入る。3〜6番目の大きさでは見出し文字のサイズや色が変更されるだけで、罫線は入らない。

**ボールド**にしたい場合には、ボールドにしたい文字をアスタリスク2つで入れ子にする。そうすると、**このようにボールドにすることができる**。でもボールドにしてもあんまり太くなるわけではないので、使い方が難しい。

_italic_ にすることもできる。半角英数字じゃないと効かないので注意する。文字の前後を「半角スペース+アンダースコア」で入れ子にする。

リンクを貼ることもできる。リンク対象文字を[]で囲み、続いて()でURIを囲む。そうすると[GitHub Desktop](https://desktop.github.com)のようにリンクを生成できる。リンクを自由に貼れるとHTMLと同じでやれることはかなり広がる。

引用をすることができる。この場合には、>に続いて半角スペースを挿入すると
> このように引用ができる
>を連続させることで多重引用も可能
