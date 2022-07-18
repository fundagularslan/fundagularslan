Proje 3
[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.


Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.

Sıranın en başındaki sayı olan root 7’dir. Sağında 7’den büyük sayılar (8,9), solunda 7’den küçük sayılar bulunur (0,1,2,3,4,5,6). 
Dizideki sayılar sıra sıra 7'nin sağına veya soluna eklenir. 
Dizi ilerledikçe 7'ye ek olarak diğer elemanlara görede büyüklük küçünlük kıyaslaması yapmalıyız.
Mesela; 5'ten sonra 1 geleceği için onu 5'in soluna yazmalıyız.
Aynı şekilde 9 da 8'in sağına yazılmalıdır.

	                                                          7
                                                          /       \
                                                         /         \
                                                       5            8
                                                      /              \
                                                     /                \
                                                    1                  9
                                                     \
                                                      \
                                                        3
                                                         \
                                                          \
                                                           6
                                                          /
                                                         /
                                                        0 
                                                         \
                                                          \
                                                           4
                                                          /
                                                         /
                                                        2 
