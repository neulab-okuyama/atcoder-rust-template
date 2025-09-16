# AtCoder Rust Template

## 改訂履歴
|日付|更新内容|
|--|--|
|2025.09.16|初版（2023.08 のジャッジアップデート環境）｜

## 前提条件
- 2023.08 のジャッアップデートに合わせた環境
  - [使用できる言語とライブラリの一覧](https://img.atcoder.jp/file/language-update/language-list.html)

## 使い方
### cargo generate のインストール
```
$ cargo install cargo-generate
```

### cargo generate のお気に入りに登録
```
$ vim ~/.cargo/cargo-generate.toml
---
# 以下の様に設定
[favorites.atcoder]
git = "https://github.com/neulab-okuyama/atcoder-rust-template.git"
branch = "main"
```

### コンテストごとのプロジェクト作成 
```
$ cargo generate atcoder
Project Name: abc200 # コンテスト名を入力 
```

### プロジェクト作成後のソースコードの実行例
```
$ cd <Project Name>
$ vim ./src/a.rs
$ cargo run --bin a
Hello, world!
```
