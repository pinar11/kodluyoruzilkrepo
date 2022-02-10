# Merge Sort
### [16,21,11,8,12,22]
Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
- Diziyi ilk aşamada [16,21,11] ve [8,12,22] olarak bölüyoruz.
- İkinci aşamada [16] [21,11] ve [8] [12,22] olarak bölüyoruz
- Üçüncü aşamada [16] [21] [11] ve [8] [12] [22] olarak tek elemanlı kalana kadar böldük.
- Dörüdüncü aşamada kendi aralarında küçükten büyüğe sıralayarak [11,16],[21]  ve [8,12],[22] olacak şekilde birleştiriyoruz. 
- Beşinci aşamada[11,16,21] ve [8,12,22] olarak birleştiriyoruz.
- Altıncı aşamada [8,11,12,16,21,22]  olarak birleştiriyoruz.
---
- Birleştirme ve ayırma işlemleri yaptığımız için O(nlogn).
