slidenumbers: true

# iOS Dev Workflow with Vim

---

# 自己紹介
* GMOペパボでminneというiOSアプリの開発をしている
* Vim歴１年くらい
* github.com/yhkaplan
	* [gfontenot/vim-xcode](https://github.com/gfontenot/vim-xcode)
	* [sbdchd/neoformat](https://github.com/sbdchd/neoformat)

---

# Remap Tip
* Remap `J` to `gJ` to eliminate space

```vim
nnoremap J gJ
```

---

# Intro to Swift
* Fast
* Nice looking/readable syntax
* Safe (memory safety, optionals)

---

# Why Vim
* ほかの言語で使える
* キーバインドが指に優しい
* 軽い
* プログラマブル

---

# Xvim 2
* [XVim2](https://github.com/XVimProject/XVim2)
* 実装できたのはすごい
	* が、不安定
	* アップデートにすぐ対応できない可能性がある
	* セキュリティの懸念あり

---

# AppCode
* 重い
* インライン警告・エラーがない
* 有料なのに補完以外はあまりAtom/VSCodeと変わらない
* 補完がいい

---

# 環境
* Neovim

---

# 一般的なプラグイン
* Deoplete
* ALE
* vim-gutentags
* vim-tmux-navigator
* FZF

---

# iOS関連
* xcode-vim
* keith/swift.vim

---

# Vimでしないこと
* LLDBデバッグ
	* （だが、する予定）
* ビルド（Xcodeの修正提案（fixit）が便利すぎる）
* 複数ファイルの置き換え
	* （Xcodeの正規表現がわかりやすい）
	* だが、awk, sedの使い方をちゃんと覚える予定

---

# Future
* LSP（Language Server Protocol）
* Xcodeのプラグイン機能が強化される？
