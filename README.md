# Proje 1: 
## Sorular 1
### Soru --> [22,27,16,2,18,6] -> Insertion Sort Verilen dizinin sort türüne göre aşamalarını yazınız.

```
[22,27,16,2,18,6] --> O(n) //input n tane
[2,27,16,22,18,6] --> O(n)
[2,6,16,22,18,27] --> O(n-1)
[2,6,16,22,18,27] --> O(n-2) //16 için arama yaptık ama değisiklik olmadı
[2,6,16,18,22,27] --> O(n-3)
[2,6,16,18,22,27] --> O(n-4) //22 için arama yaptık ama değişiklik olmadı
```

### Soru --> Big-O gösterimini yazınız.
```
Bütün adımlardaki --> "O(n) + O(n-1) + O(n-2) + O(n-3) ... O(n-(n-1))" ifadesiyle girilen input değeri kadar ilerlediği için *O((n(n-1))/2)  => complexity ile O(n²) dir.
```
[* Gauss Yöntemi](https://www.matematikdunyasi.org/1992/03/gauss-formulunun-genellestirilmesi/#:~:text='den%20'ye%20kadar%20tamsay%C4%B1lar%C4%B1n%20toplam%C4%B1n%C4%B1,form%C3%BCl%C3%BCne%20genellikle%20Gauss%20form%C3%BCl%C3%BC%20denir.)

### Soru --> Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız

Average case: Aradığımız sayının ortada olması
Worst case: Aradığımız sayının sonda olması
Best case: Aradığımız sayının dizinin en başında olması.

```
Dizi sıralandıktan sonra [2,6,16,18,22,27] --> 18 sayısı ortada bulunduğundan Avarage Case'ine girer
```

## Sorular 2
### Soru --> [7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.
```
[7,3,5,8,2,9,4,15,6] --> Input
[2,3,5,8,7,9,4,15,6] --> 1. Adım
[2,3,5,8,7,9,4,15,6] --> 2. Adım
[2,3,4,8,7,9,5,15,6] --> 3. Adım
[2,3,4,5,7,9,8,15,6] --> 4. Adım
.
.
.
```
