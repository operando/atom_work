## Atom

Githubが作ってる


Atom の最大の特長を一言で表すと、Web 技術に よって作られたエディタだという

HTML、 CSS、JavaScript というブラウザ上で動く Web ペー ジ(いわゆるフロントエンド)を構成する技術

Atom は一般的なデスクトップアプリケーションと は異なり、各種 OS の API や UI キットを利用するの ではなく、Chromのオープンソース版である Chromium利用して構築されている

OSS

公式サイト

パッケージ(https://atom.io/packages)

テーマ(https://atom.io/themes)

公式ブログ(http://blog.atom.io/)

## Web 技術によって作られた Atom
Atomは Chromiumをベースとして開発されたAtom Shellと呼ばれる独自のフレームワークによって動作

描画エンジンには Blink
スクリプトエンジ ンには Node.jsを採用

画面の描画はすべて HTML/CSS によって実現され、提供される機能は JavaScript によっ て作られています。

つまり、Web 開発者ならばすでにお気づきのとお り、Atom は Web ページとまったく同じ技術によっ て開発されているのです。

## メリット

* 今までのWeb技術が使える

* Reactを導入していたり、Chromium という最もモダンなブラウザの一つを採 用している

* Web Componentsといった最先端のWeb技術を率先して利用しています。

* 最新ではないブラウザへのサポートが必要なため、こうい った技術を採用できない
 * 開発をより効率的にするエディタ機能の開発を通して最新のWeb技術に触れることができるため、一粒で二度おいしい

* OS のサポートを気にする必要がない
 * HTML と CSS は W3C、JavaScript は Ecma Internationalを中心にオープンスタンダードとして仕様が策定
 * Web の仕様は OS と切り離されている

## デメリット

重い

CSSとHTMLなので、細かい設定ができない可能性もある。Web技術でできる範囲に縛られてる



## apm(Atom Package Manager)



## Update

右下の青いアイコンからUpdateの一覧が見える

AtomのUpdateは、再起動すれば最新バージョンに自動的にアップデートされます。

## Setting

~/.atomディレクトリができる

.gitignoreが配置される

GitHub へ push しておけば、Atom の設定ファイルを バックアップできます


## いいところ

Styleの設定がCSSなので、変更するの楽

Settingがわかりやすいので、目的なことが簡単にできる。あんまり迷わない

複数環境でのPakcageの同期が簡単

packageの有効・無効の操作が楽。アンインストールも楽

各pakcageの設定画面もあるので楽

エラーになった時にissueのリンクが見れる


## 不満

透過できない

## AtomのDOM

Web Componentsが使われてる
 * Custom Elements
 * Shadow DOM

中に含むDOMツリーをカプセル化

UIテーマとシンタックステーマそれぞれのCSSが競合することなく、ShadowRoot内と外でCSSスタイルが完全に分離している

設定ファイルによってスタイルを変更する場合もShadowDOMによるスタイルのスコープは有効

## Key Binding Resolver

キー操作したものに、どんなバインドが設定されてるのか見れるもの

## style

LESSで書ける

Application: Open Your Stylesheet

## スニペット

頻繁に利用されるコードブロックを 登録して自由に呼び出せるようにする機能

スニペット挿入のトリガーとなる文字列 を入力してSnippets: Expan(tab)
code

[Snippets](https://atom.io/docs/latest/using-atom-snippets)


## Github

alt + g g - open Repository

alt + g o - open current file

alt + g b - oepn current file Blame

alt + g h - oepn current file history

alt + g c - copy current file link

alt + g r - open current brunch diff default brunch

## Key Map

cmd + b - 開いてるタブのファイルを切り替える

cmd + p or t - プロジェクト内のファイル検索

cmd + shift + t - 直近に閉じたファイルを開く

cmd + \ - tree viewの表示/非表示

control + 0 - tree viewとbufferのフォーカス切り替え

cmd + alt + i - dev toolを開く

cmd + . - Key Binding Resolverを開く

alt + shift + s - スニペット

cmd + alt + control + l - window reload

cmd + o - open

control + shift + m - preview markdown


## Packages

* Community Packages
 * 自身がインストールしたパッケージ
* Core Packages
 * Atom が標準で内蔵しているパッケージ


* [markdown-preview](https://atom.io/packages/markdown-preview)
* [linter](https://atom.io/packages/linter)
* [sublime-style-column-selection](https://atom.io/packages/Sublime-Style-Column-Selection)
* [git-plus](https://atom.io/packages/git-plus)
* [autocomplete-paths](https://atom.io/packages/autocomplete-paths)
* [autocomplete-emojis](https://atom.io/packages/autocomplete-emojis)
* [autocomplete-snippets](https://atom.io/packages/autocomplete-snippets)
* [git-plus](https://atom.io/packages/git-plus)
* [atomatigit](https://atom.io/packages/atomatigit)
* [atom-html-preview](https://atom.io/packages/atom-html-preview)
* [script](https://atom.io/packages/script)
* [react](https://atom.io/packages/react)

## Ohter

* [Atomのautocomplete-plusパッケージで補完確定をTabキーからEnterキーに変更](http://qiita.com/kanpe777/items/13b363ad9bdadade5d6b)
