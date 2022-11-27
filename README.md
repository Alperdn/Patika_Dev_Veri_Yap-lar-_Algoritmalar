# Proje 1
[22,27,16,2,18,6] -> Insertion Sort
Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
Big-O gösterimini yazınız.
Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız

-> İlk olarak elimizdeki veriyi tarayarak en küçük değeri bulur yani 2'yi, ardından 2 değerini 22'nin yerine yazar, [2,27,16,22,18,6]
-> Bu işlem en başa eklenen element'in sağındakileri kapsayacak şekilde devamlı olarak tekrarlanır;
   -[2,6,16,22,18,27]
   -[2,6,16,18,22,27]
olarak sıralanmış olur

-> Insertion sort'ta lineer bir yapı işlediği için yapacağımız işlem sayısı n (array boyutu) kadardır. Bütün array'in boyutuna göre de n(n+1)/2
 sayısı kadar işlem yapmamız gerekir. Yani sonuç olarak Big O notation = O(n^2)
 
-> 18 sayısı **average case** kapsamına girer
 #
 
 # Proje 2
[16,21,11,8,12,22] -> Merge Sort

Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
Big-O gösterimini yazınız.

-> İlk olarak elimizdeki array'i tek bir eleman kalana kadar ayırırız;
   -[16,21,11] ve [8,12,22]
   -[16,21][11],[8,12],[22]
   -[16],[21],[11],[8],[12],[22]
-> ardından birleştirme işlemine geçip, kendi içlerinde verileri karşılaştırırak array'i sıralarız;
   -16 ile 21 karşılaştırılır 16 başa geçer 11 tek eleman olduğu için bir sonraki aşamayı bekler, 8 ve 12 sıralanır 22 bekler,
   -[16,21] ile 11 karşılaştırılır [11,16,21] olur yine aynı şekilde:[8,12,22]
   -[8,11,12,16,21,22] olarak sıralanır.
-> Big O = O(nlogn)   
#

# Proje 3
[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.

-> rastgele root olarak ben 6'yı seçiyorum;
   -6'nın sağında 7 solunda 5,
   -5'in solunda 1, 7'nin sağında 8,
   -1'in sağında 3, 1'in solunda 0,
   -8'in sağında 9,
   -3'ün sağına 4,
   -3'ün soluna 2 gelir.









