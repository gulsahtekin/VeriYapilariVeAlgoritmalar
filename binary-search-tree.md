# Proje 3
---

## [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamaları:
 
### Root = 7 olarak başlarsak,

İlk olarak 7'nin solunda 5 yer alır. Sırasıyla, 1, 5'in solunda; 8 ise 7'nin sağında konumlanır. 


                              7
                         5        8
                    1      

Ardından, aynı kurala göre devam edilince, sırasıyla 3, 6 ve 0 aşağıdaki gibi eklenir.

                              7
                         5        8
                    1       6         
                0      3


Son olarak, 9, 4 ve 2 aşağıdaki konumlarda eklenerek, verilen dizi için şu binary-search-tree diagram elde edilir:

                              7
                         5        8
                    1      6          9
                0     3
                    2   4
