# Veri Yapıları ve Algoritmalar Projeleri

## Insertion Sort Algoritması Projesi

```
[22,27,16,2,18,6] -> Insertion Sort
```

1. Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

> [22, 27, 16, 2, 18, 6] => en küçük eleman bulunur ve en baştaki eleman ile değiştir
> [2, 27, 16, 22, 18, 6] => ikinci en küçük elemanı bul ve en baştan ikinci eleman ile değiştir
> [2, 6, 16, 22, 18, 27] => üçüncü en küçük elemanı bul ve en baştan üçüncü eleman ile değiştir, değiştirilmeye gerek kalmadı
> [2, 6, 16, 22, 18, 27] => dördüncü en küçük elemanı bul ve en baştan dördüncü eleman ile değiştir
> [2, 6, 16, 18, 22, 27] => beşinci en küçük elemanı bul ve en baştan beşinci eleman ile değiştir, değiştirilmeye gerek kalmadı
> [2, 6, 16, 18, 22, 27] => sonuç

2. Big-O gösterimini yazınız.

> O(n^2)

3. Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.

> Worst case: n => O(n) - 6 işlem
> Average case: n/2 => 0(n/2) - 3 işlem
> Best case: 1 => O(1) - 1 işlem 

4. Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.

> Average case kapsamına girer

