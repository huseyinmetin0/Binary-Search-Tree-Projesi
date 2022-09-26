# Binary-Search-Tree-Projesi

Merhaba. [Patika.dev](https://www.patika.dev/tr)'in Veri Yapıları ve Algoritmalar dersinin proje 3 ödevini tamamladım.

####[7,5,1,8,3,6,0,9,4,2] dizisinin Binary-Search-Tree aşamalarını yazınız.
####Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.

Cevap;

                      [root]
                       [7]
                       / \
                      /   \
                    [5]   [8]
                    / \     \
                   /   \     \
                 [1]   [6]   [9]
                 / \
                /   \
              [0]   [3]
                    / \
                   /   \
                 [2]  [4]
                 
####Aşamalar;

1-  Root 7'dir.

2-  5, 7'den küçük olduğu için 7'nin soluna yazılmıştır.

3-  1, 7'den küçük olduğu için 7'nin soluna, 5'ten küçük olduğu için 5'in soluna yazılmıştır.

4-  8, 7'den büyük olduğu için 7'nin sağına yazılmıştır.

5-  3, 7'den küçün olduğu için 7'nin soluna, 5'ten küçük olduğu için 5'in soluna, 1'den büyük olduğu için 1'in sağına yazılmıştır.

6-  6, 7'den küçük olduğu için 7'nin soluna, 5'ten büyük olduğu için 5'in sağına yazılmıştır.

7-  0, 7'den küçük olduğu için 7'nin soluna, 5'ten küçük olduğu için 5'in soluna, 1'den küçük olduğu için 1'in soluna yazılmıştır.

8-  9, 7'den büyük olduğu için 7'nin sağına, 8'den büyük olduğu için 8'in sağına yazılmıştır.

9-  4, 7'den küçük olduğu için 7'nin soluna, 5'ten küçük olduğu için 5'in soluna, 1'den büyük olduğu için 1'in sağına, 3'ten büyük olduğu için 3'ün sağına yazılmıştır.

10- 2, 7'den küçük olduğu için 7'nin soluna, 5'ten küçük olduğu için 5'in soluna, 1'den büyük olduğu için 1'in sağına, 3'ten küçük olduğu için 3'ün soluna yazılmıştır.

