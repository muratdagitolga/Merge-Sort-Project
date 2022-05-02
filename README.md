# Merge-Sort-Project
Veri Yapıları ve Algoritmalar dersi merge sort projesi cevapları

SORU-1:
[16,21,11,8,12,22] -- birinci aşama: başlangıç dizisi 3 elemanlı iki alt diziye bölünür:
[16,21,11] - [8,12,22] -- ikinci aşama: oluşturulan diziler 2 ve 1 eleman olacak şekilde iki alt diziye bölünür:
[16] - [21,11] - [8] - [12,22] -- üçüncü aşama: bölünmüş diziler sıralı şekilde 1 elamanlı diziler olacak şekilde bölünür:
[16] - [21] - [11] - [8] - [12] - [22] -- üçüncü aşama: bölünmüş diziler sıralı şekilde aşama aşama birleştirilir:

[16] - [11,21] - [8] - [12,22] -- dördüncü aşama: bölünmüş diziler sıralı şekilde aşama aşama birleştirilir:
[11,16,21] - [8,12,22] -- beşinci aşama: bölünmüş diziler sıralı şekilde aşama aşama birleştirilir:
[8,11,12,16,21,22] -- işlem tamamlanmış olur.

SORU-2:
BIG-O gösterimi: O(nlogn)
