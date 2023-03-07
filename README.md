# Merge-Sort-Projesi
[16,21,11,8,12,22] -> Merge Sort

a-Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
b-Big-O gösterimini yazınız.

a)
1-[16,21,11,8,12,22]->[16,21,11] [8,21,11]
2-[16,21,11] -> [16], [21,11]
  [8,12,22] -> [8], [12,22]
  
3-[16] -> [16]
  [21,11] -> [11,21]
  [8] -> [8]
  [12,22] -> [12,22]
  
4-[11,21] birleştirilir -> [11, 21]
  [8,12,22] birleştirilir -> [8, 12, 22] 

5-[16], [11,21], [8], [12,22] birleştirilir -> [11,16,21], [8,12,22] 

[8,11,12,16,21,22]

b)Big-O=O(nlog(n))
