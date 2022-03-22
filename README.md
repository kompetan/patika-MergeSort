# patika-MergeSort
patika.dev Veri Yapıları ve Algoritmalar Dersi Merge Sort Projesi

PROJE 2

Soru 1: [16,21,11,8,12,22] -> Merge Sort

a. Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.

       [16,21,11,8,12,22]
                     
   [16,21,11]    |    [8,12,22]
                         
 [16,21]   [11]  |   [8,12]  [22]
                        
 [16] [21]  [11] |  [8] [12]  [22] 
                  
 [16,21]   [11]  |   [8,12]  [22]
     \      /           \     /
    [11,16,21]         [8,12,22]
    
b. Big-O gösterimini yazınız.

O(nlogn)
