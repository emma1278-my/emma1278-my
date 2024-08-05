## 問題1

変数bottomには底辺の値、変数heightには高さの値が格納されます。
変数を使って、三角形の面積を計算し、数値で返す処理を記述してください。
三角形の面積を求める式は「底辺 × 高さ ÷ 2」です。

```
<?php
function triangle() {
    $bottom = 10;
    $height = 30;
    return $bottom * $height / 2;
}
print triangle()
?>
```

## 問題2

$textには文字列「7」が代入されています。メソッドを用いて文字列「7」を、数値に変換して返す処理を記述してください。
＊コードに全角スペースが含まれているとテストが通らなくなりますのでご注意ください。

```
<?php
function chapter02_03() {
    $text = '7';
    return intval($text);
}

print chapter02_03()
?>
```

※intval

- intval — 変数の整数としての値を取得する

## 問題3

$food変数に文字列「きゅうり」、$price変数に数値「100」が代入されています。
それらの変数を使って「きゅうりは100円です」という文字列を返す処理を記述してください。（ヒント:式展開）

```
<?php
function chapter02_04() {
    $food = 'きゅうり';
    $price = 100;
    return "{$food}は{$price}円です";;
}

print chapter02_04()
?>
```
