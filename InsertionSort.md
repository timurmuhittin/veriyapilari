# Odev 1

[22,27,16,2,18,6] -> Insertion Sort

Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
Big-O gösterimini yazınız.
Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız

## Odev 1 Cozum

Önce en büyük sayı ile en küçük sayı yer değiştirir.
1-[2,27,16,22,18,6]
Sonra sırayla her sayıya bakılır ve bu sayılar kendinden sonraki en küçük sayı ile yer değiştirir.
2-[2,6,16,22,18,27]
3-[2,6,16,18,22,27]

Big-O : O(n^2),
Time Complexity:18 sayısının ortada olmasından dolayı:Avarage Case


# Odev 2

[7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.

## Odev 2 Cozum

Adım:1 2-7 yer değiştirir:
[2,3,5,8,7,9,4,15,6]

Adım:2 ikinci en küçük 3 olduğu için aynı kalır:
[2,3,5,8,7,9,4,15,6]

Adım:3 üçüncü en küçük 4 olduğu için 4-5 yer değiştirir:
[2,3,4,8,7,9,5,15,6]

Adım:4 dördüncü en küçük 5 olduğu için 5-8 yer değiştirir:
[2,3,4,5,7,9,8,15,6]