# チェックワーク 〜カウントアプリ〜

## Lv. 1 プラスボタンを実装しよう

### アプリのスクショ
https://user-images.githubusercontent.com/49048577/148199977-128a69db-c670-45eb-bb07-6bd618fd8ec7.mp4

### 手順
0. View Binding の設定をしよう
1. `Button` を配置して、idを `plus_button` と設定しよう
1. Int型の変数 `count` を宣言して、初期値として0を代入しよう
1. `plus_button` に `setOnClickListener` メソッドを実装して、 `plus_button` を押すたびに `count` の値を1増やそう

### ソースコードと解説
[Lv. 1 はこちら！](https://github.com/Kaito-Dogi/android-school-checkwork-count-plus-button)

## Lv. 2 マイナスボタンとリセットボタンを実装しよう

### アプリのスクショ
https://user-images.githubusercontent.com/49048577/148207525-0d63ed19-6396-43ea-b6f6-575b87f52060.mp4

### 手順
1. 新たに `Button` を2つ配置して、idを `minus_button` 、 `reset_button` と設定しよう
1. `minus_button` に `setOnClickListener` メソッドを実装して、 `minus_button` を押すたびに `count` の値を1減らそう
1. `reset_button` に `setOnClickListener` メソッドを実装して、 `reset_button` を押すたびに `count` の値を0にしよう

### サンプルコードと解説
[Lv. 2 はこちら！](https://github.com/Kaito-Dogi/android-school-checkwork-count-minus-reset)

## Lv. 3 二つの値をカウントできるようにしよう

### アプリのスクショ
https://user-images.githubusercontent.com/49048577/148212490-d385bb22-5e7d-414a-8a4d-1f9054ec8f9c.mp4

### 手順
1. レイアウトを作成しよう
1. 整数を管理するための整数を宣言しよう
1. ボタンをクリックした時の処理を実装しよう

### サンプルコードと解説
[Lv. 3 はこちら！](https://github.com/Kaito-Dogi/android-school-checkwork-count-multiple)

## Lv. 4 カウントした値に応じて処理を分岐しよう

### アプリのスクショ
https://user-images.githubusercontent.com/49048577/148216535-119af68a-3af1-432f-b77a-2d36d085f67f.mp4

### 手順
1. プラスボタンを実装しよう
1. Int型の変数 `count` が3の倍数の時、数字の代わりに `Fizz` と表示させよう
1. `count` が5の倍数の時、数字の代わりに `Buzz` と表示させよう
1. `count` が15の倍数の時、数字の代わりに `FizzBuzz` と表示させよう

### サンプルコードと解説
[Lv. 4 はこちら！](https://github.com/Kaito-Dogi/android-school-checkwork-count-if)

## Lv. 5 カスタムクラスを作成しよう

### 手順1
1. `Counter`クラスを作成しよう
1. 整数を保持するためのプロパティ`number`を定義して、初期値として0を代入しよう
1. `Counter`クラスをインスタンス化して、変数 `counter` に代入しよう
1. ボタンをクリックした時の処理を実装しよう
1. 手順2に移ろう！

### 手順2
1. `number` の初期値を好きなように代入できるようにしよう
1. `number` の値を更新するメソッドを定義しよう
1. 定義したメソッドを呼び出して、 `number` の値を更新しよう
1. 手順3に移ろう！

### 手順3
1. `companion object` を用いて、生成した `Counter` インスタンスの数を数えよう
1. 手順4に移ろう！

### 手順4
1. `number` 値を直接変更できないようにしよう
    - ヒント `number` のセッターの可視性を `private` にしよう 
1. `MainActivity.kt` で`counter.number += 1`を書いたらどんなエラーが表示されるか確認しよう
1. `private` （可視性修飾子）の意味を調べてみよう
1. エラーの原因を説明してみよう

### サンプルコードと解説
[Lv. 5 はこちら！](https://github.com/Kaito-Dogi/android-school-checkwork-count-custom-class)

## Ex. 1 クロージャを利用してみよう

### アプリのスクショ
スクショ

### 手順
🚨 工事中

### サンプルコードと解説
[Ex. 1 はこちら！]()

## Ex. 2 MVVMを導入してみよう

### アプリのスクショ
スクショ

### 手順
🚨 工事中

### サンプルコードと解説
[Ex. 2 はこちら！]()

## Ex. 3 Jetpack Composeを利用してみよう

### アプリのスクショ
スクショ

### 手順
🚨 工事中

### サンプルコードと解説
[Ex. 3 はこちら！]()
