# patika_veri_algoritma_odevi

[22,27,16,2,18,6] -> Insertion Sort
Cevap : [22,27,16,2,18,6]  
sırası ile en küçük elemanı bulup en başa yazacagız ve her seferinde bulduğumuz en küçükten sonrakini bir yanına yazacağız. (n-1)

[22,27,16,2,18,6] inceleme yaptığımızda 2 en küçük olduğu görülmüş ve 22 ile yer değiştirilmiştir [2,27,16,22,18,6]  şeklinde olmuştur.
[2,27,16,22,18,6] 6 ile 27 yer değişikliği yapacaktır>> [2,6,16,22,18,27] ve son olarak 22 ve 18 yer değiştirecektir>> [2,6,16,18,22,27] 

Big o notation : O(2ⁿ)

Son hali [2,6,16,18,22,27]  olan durumda 18 sayısı AvarageCase kapsamında olur en başta ve en sonda değil ortada bulunduğu için.
[7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk dört adımını yazınız.
1-)[2,3,5,8,7,9,4,15,6]
2-)[2,3,4,8,7,9,5,15,6]
3-)[2,3,4,5,7,9,8,15,6]
4-)[2,3,4,5,6,9,8,15,7]
