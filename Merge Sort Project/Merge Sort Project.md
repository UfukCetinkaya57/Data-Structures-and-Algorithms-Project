[16,21,11,8,12,22] -> Merge Sort


1) Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.

1. aşama [16,21,11,8,12,22] 
2. aşama [16,21,11]  [8,12,22] 
3. aşama [16,21] [11]  [8,12][22] 
4. aşama [16] [21] [11]  [8][12]  [22] 
5. aşama [16,21] [8,11]       [12,22] 
6. aşama [8,11,16,21]   [12,22] 
7. aşama [8,11,12,16,21,22]


2) Big-O gösterimini yazınız

2^x=n -> logn=x Big O Notation : O(nlogn)
