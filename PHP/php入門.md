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
