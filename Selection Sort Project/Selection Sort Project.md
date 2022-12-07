1) [22,27,16,2,18,6] -> Insertion Sort
Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

1. aşama [2,27,16,22,18,6] DİZİNİN EN KÜÇÜK ELEMANI BULUNUR VE EN BAŞTAKİ İLE YER DEĞİŞTİRİR. 
2. aşama [2,6,16,22,18,27] 2’NCİ EN KÜÇÜK ELEMAN BULUNUR VE 2’NCİ SIRAYA GETİRİLİR. 
3. aşama [2,6,16,22,18,27] 3’ÜNCÜ EN KÜÇÜK ELEMAN ZATEN SIRASINDA İŞLEM YAPILMAZ. 
4. aşama [2,6,16,18,22,27] 4’ÜNCÜ EN KÜÇÜK ELEMAN ZATEN SIRASINDA İŞLEM YAPILMAZ.
5. aşama [2,6,16,18,22,27] 5’İNCİ EN KÜÇÜK ELEMAN YERİNDE İŞLEM YAPILMAZ.


2) Big-O gösterimini yazınız.
22,27,16,2,18,6] dizisinde 6 tane eleman vardır, yani 6 tane işlem yapılacaktır demektir. 
İlk adımda n-> 6 tane işlem, n + (n-1) + (n-2) + (n-3) .... 1. 
Bu algoritmada n+(n-1)+(n-2)+(n-3)+(n-4)+1 kadar işlem yapılır. 
Bu işlemin formülü: [n(n+1)]/2'dir. 
Bu formül sadeleştirilerek: (n²+n)/2 elde edilir.
Big-O değeri = O(n²)


3) Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız
AVARAGE CASE


4) [7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.
1. aşama [2,3,5,8,7,9,4,15,6] 
2. aşama [2,3,5,8,7,9,4,15,6] 
3. aşama [2,3,4,8,7,9,5,15,6] 
4. aşama [2,3,4,5,7,9,8,15,6]
