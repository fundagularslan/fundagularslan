[16,21,11,8,12,22] -> Merge Sort

•	Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
Önce dizini sağ ve soldaki 3 elemean olarak iki gruba böleriz.
Soldaki grup aşağıda gösterilen şekilde işleme tabi tutulur. 
En sonunda da küçükten büyüğe sıralanır.

| 16 | 21 | 11 |  
| -- | -- | -- |  

| 16 | -- | 21 | 11 |  
| -- | -- | -- | -- | 

| 16 | -- | 21 | -- | 11 |  
| -- | -- | -- | -- | -- |

| 16 | -- | 11 | 21 |  
| -- | -- | -- | -- | 

| 11 | 16 | 21 |  
| -- | -- | -- | 

Sağdaki grup için de aynı işlemler tekrarlanır.


| 8  | 12 | 22 |  
| -- | -- | -- |  

| 8 | 12 | -- | 22 |  
| --| -- | -- | -- | 

| 8 | -- | 12 | -- | 22 |  
| --| -- | -- | -- | -- |

| 8 | 12 | -- | 22 |  
| --| -- | -- | -- | 

| 8  | 12 | 22 |  
| -- | -- | -- | 

En son olarak bütün elemanlar küçükten büyüğe sıralanır.

| 8  | 11 | 12 |  16 | 21 | 22 |  
| -- | -- | -- | --  | -- | -- | 

                                      
•	Big-O gösterimini yazınız.

$\ 2^x=nlogn $

$\ O(nlogn) $


