---
position: 102
title: 手順2. フォークとクローン
---

# 2. フォークとクローン

プロジェクトのデータを準備します。  
最初は **fork(フォーク)** から始めましょう。

![gif](/tutorial/eye-fork.gif)

<br />

## fork

GitHub の画面からハニープロジェクトをフォークします。  
この操作はプロジェクトに参加する はじめの一度だけで充分です。  
`Owner` が自分のアカウントになっていることを確認してください。

![image](/tutorial/fork.png)  
<a href="https://github.com/rubydog-jp/hunny/fork" class='linkbutton'>フォークの画面 (GitHub) へ</a>

<br />

<br />

## Clone

フォークが完了したら、自分のパソコンまでデータを持ってくるために **clone(クローン)** をしましょう。  
この操作はパソコンの中身を捨てない限り、はじめの一度だけで充分です。

```
$ git clone https://<アクセストークン>@github.com/<ユーザーID>/hunny.git
```

例

```
$ git clone https://ghp_Xxxx1122Yyyy3344Zzzz5566AaaaBbbbCccc@github.com/rbdog/hunny.git
```

<br />

<br />

## upstreamを設定

ハニープロジェクト本体のURLを`upstream` として Git に登録しておきます

```
$ cd hunny
$ git remote add upstream https://github.com/rubydog-jp/hunny.git
```

例

```
$ cd hunny
$ git remote add upstream https://github.com/rubydog-jp/hunny.git
```

<br />

## 準備OK

これで活動の準備ができました。
