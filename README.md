# Merge-Sorting

[16,21,11,8,12,22] -> Merge Sort algoritması ile nasıl çalıştığını yazınız.

Tek eleman kalana kadar yarıya bölünerek devam eder. Tek kaldıktan sonra istenilen sırada diziye yerleştirerek sonucu yazdırır.

1.-> [16,21,11,8,12,22]
2.-> [16,21,11] [8,12,22]
3.-> [16,21] [11] [8,12] [22]
4.-> [16] [21] [11] [8] [12] [22]
5.-> [16,21] [8,11] [12,22]
6.-> [8,11,16,21] [12,22]
7.-> [8,11,12,16,21,22]

Big-O österimi: 2^x = n ==> O(nlogn)
