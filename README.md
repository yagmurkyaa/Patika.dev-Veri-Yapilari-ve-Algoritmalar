# Patika.dev-Veri-Yapilari-ve-Algoritmalar
Insertion Sort Proje
Proje 1
[22,27,16,2,18,6] -> Insertion Sort

Soru 1 :
Yukarıda verilen dizinin sort türüne göre aşamalarını yazınız.
Cevap 1 :
İlk adımda, dizinin ikinci elemanı olan 27'yi seçiyoruz. Bu elemanı, dizinin ilk elemanı olan 22 ile karşılaştırıyoruz. 27, 22'den büyük olduğu için yer değiştirmemiz gerekmeyecek. Dizi şu şekilde görünüyor: [22, 27, 16, 2, 18, 6]

Şimdi 27'yi sabit olarak kabul ediyoruz ve üçüncü elemanı olan 16 ile karşılaştırıyoruz. 16, 27'den küçük olduğu için 27'yi kaydırarak 16'yı doğru konuma yerleştiriyoruz. Dizi şu şekilde görünüyor: [22, 16, 27, 2, 18, 6]

Şimdi 16'yı da sabit olarak kabul ediyoruz ve dördüncü eleman olan 2 ile karşılaştırıyoruz. 2, 16'dan küçük olduğu için 16'yı kaydırarak 2'yi doğru konuma yerleştiriyoruz. Dizi şu şekilde görünüyor: [2, 22, 16, 27, 18, 6]

Şimdi 2'yi de sabit olarak kabul ediyoruz ve beşinci eleman olan 18 ile karşılaştırıyoruz. 18, 2'den büyük olduğu için yer değiştirmemiz gerekmeyecek. Dizi şu şekilde görünüyor: [2, 22, 16, 27, 18, 6]

Şimdi 18'i de sabit olarak kabul ediyoruz ve altıncı eleman olan 6 ile karşılaştırıyoruz. 6, 18'den küçük olduğu için 18'i kaydırarak 6'yı doğru konuma yerleştiriyoruz. Dizi şu şekilde görünüyor: [2, 6, 22, 16, 27, 18]

Son adımda, diziyi bir kez daha gözden geçiriyoruz. Sıralama tamamlanmıştır ve dizi artık tamamen sıralıdır. Son hali şu şekildedir: [2, 6, 16, 18, 22, 27]

Soru 2 : Big-O gösterimini yazınız.
Cevap 2 : Insertion Sort'un Big-O gösterimi O(n^2) şeklindedir. Bu, dizinin eleman sayısının karesi kadar işlem gerektiği anlamına gelir. Yani, dizi eleman sayısı (n) arttıkça algoritmanın çalışma süresi karesel olarak artar. Bu nedenle büyük veri setleri üzerinde kullanıldığında performans sorunlarına neden olabilir ve tercih edilmeyebilir.

Soru 3 : Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız

Average case: Aradığımız sayının ortada olması
Worst case: Aradığımız sayının sonda olması
Best case: Aradığımız sayının dizinin en başında olması.
Cevap 3 : Insertion Sort'un Big-O gösterimi O(n^2) şeklindedir. Bu, dizinin eleman sayısının karesi kadar işlem gerektiği anlamına gelir. Yani, dizi eleman sayısı (n) arttıkça algoritmanın çalışma süresi karesel olarak artar. Bu nedenle büyük veri setleri üzerinde kullanıldığında performans sorunlarına neden olabilir ve tercih edilmeyebilir.

Soru 4: 

[7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.

Cevap 4 : 

Merge Sort Projesi
Proje 2
[16,21,11,8,12,22] -> Merge Sort

Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
Big-O gösterimini yazınız.

Cevap:
İlk adım olarak, diziyi iki eşit parçaya bölüyoruz:
[16, 21, 11] ve [8, 12, 22]

Her iki parçayı da aynı Merge Sort algoritmasıyla sıralamaya devam ediyoruz:

İlk parça olan [16, 21, 11] için sıralama adımları:

[16, 21, 11] -> [16, 11, 21]
[16, 11, 21] -> [11, 16, 21]
İkinci parça olan [8, 12, 22] için sıralama adımları:

[8, 12, 22] -> [8, 12, 22]
Şimdi, sıralanmış bu iki parçayı birleştiriyoruz:

[11, 16, 21] ve [8, 12, 22] -> [8, 11, 12, 16, 21, 22]
Merge Sort'un Big-O gösterimi O(n log n) şeklindedir. Bu, Merge Sort'un n elemanlı bir diziyi sıralamak için en kötü durumda O(n log n) karşılaştırma ve yer değiştirme işlemi gerçekleştireceği anlamına gelir. Bu algoritma, büyük veri setlerini sıralamak için etkili bir seçenektir.
