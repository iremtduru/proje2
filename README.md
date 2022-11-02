# proje2
Merge Sort 
[16,21,11,8,12,22] -> Merge Sort
Merge sort sıralama sırasında bir diziyi parçalayarak sıralayan bir algoritmadır.Bu parçalama işlemi tek eleman kalıncaya
kadar sürer.
Parçalayarak ayrılan diziler daha sonrasında birbiri ile birleştirilip sıralama aşamasında daha verimli performans sağlar.

İlk olarak dizi ortadan ikiye ayrılarak parçalanır.
 [16,21,11] [8,12,22]
İkinci olarak ikiye ayrılan diziye tekrardan parçalama işlemi yapılır.
 [16] [21,11] , [8] [12,22]
Tek eleman kalıncaya kadar bu işlem devam eder.
[16] [21] [11] , [8] [12] [22]
Parçaladığımız bu dizileri sıralama işlemi yaparız.
[16] [11,21] , [8] [12,22]
Daha sonra ikili olarak küçükten büyüğe sıralama yaparız.
[11,16,21] , [8,12,22]
Dzileri birleştirken küçükten büyüğe sıralama işlemi yaparız.Böylece Merge Sort algoritmasını kullanmış oluruz.
[8,11,12,16,21,22]

Şema olarak göstermek istersek;
                                [16,21,11,8,12,22]
                     [16,21,11]                    [8,12,22]
                 [16]          [21,11]          [8]        [12,22]
                 [16]        [21] [11]          [8]      [12] [22]
                 [16]          [11,21]          [8]        [12,22]
                     [11,16,21]                    [8,12,22]
                                 [8,11,12,16,21,22]

www.patikadev.com
