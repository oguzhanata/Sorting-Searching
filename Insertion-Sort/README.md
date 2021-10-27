#### [22,27,16,2,18,6] -> Insertion Sort

1. Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

[22,27,16,2,18,6] -> 22 sayısı tek tek sayıları dolaşır ve en küçük değer 2 ile yer değiştirir.

[2,27,16,22,18,6] ->27 sayısı sağında kalan sayıları tek tek dolaşır ve en küçük sayı 6 ile yer değiştirir.

[2,6,16,22,18,27] ->16 sayısı sağında kalan sayıları tek tek dolaşır ve en küçük değer olduğu için yerinde kalır.

[2,6,16,22,18,27] ->22 sayısı sağında kalan sayıları tek tek dolaşır ve en küçük sayı 27 ile yer değiştirir.

[2,6,16,18,22,27] ->18 sayısı sağında kalan sayıları tek tek dolaşır ve en küçük sayı olduğu için yerinde kalır.

[2,6,16,18,22,27] ->22 sayısı sağında kalan 27 sayısından küçük değer olduğu için yerinde kalır.

2. Big-O gösterimini yazınız.

n + (n-1) + (n-2) + ...... + 1  bu da -> (n.(n+1))/2 -> (n²+n)/2 -> burada en büyük domine eden fonksiyonus alırız o da n²'dir. 

O(n2)'dir.

3. Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.

4. Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.

[2,6,16,18,22,27] Dizi sıralandıktan sonra 18 sayısı ortada yer aldığı için Average Case girer.


- [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

[7,3,5,8,2,9,4,15,6] -> 7 sayısı tek tek sayıları dolaşır ve en küçük değer 2 ile yer değiştirir.

[2,3,5,8,7,9,4,15,6] -> 3 sayısı tek tek sayıları dolaşır ve en küçük değer olduğu için yerinde kalır.

[2,3,5,8,7,9,4,15,6] -> 5 sayısı tek tek sayıları dolaşır ve en küçük değer 4 ile yer değiştirir.

[2,3,4,8,7,9,5,15,6] -> 8 sayısı tek tek sayıları dolaşır ve en küçük değer 5 ile yer değiştirir.