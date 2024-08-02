整数 N が入力として与えられます。

1からNまでの整数を1から順に表示してください。

ただし、表示しようとしている数値が、
```
・3の倍数かつ5の倍数のときには、"Fizz Buzz"
・3の倍数のときには、"Fizz"
・5の倍数のときには、"Buzz"
```
を数値の代わりに表示してください。


```
# 整数Nを入力として受け取る
n = gets.to_i

# 1からNまでの数をループで処理
(1..n).each do |i|
  if i % 3 == 0 && i % 5 == 0
    puts "Fizz Buzz"
  elsif i % 3 == 0
    puts "Fizz"
  elsif i % 5 == 0
    puts "Buzz"
  else
    puts i
  end
end
```
