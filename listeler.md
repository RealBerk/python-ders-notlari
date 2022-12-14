# Listelerde Method Türleri
* [append](https://github.com/RealBerk/python-ders-notlar-/blob/main/listeler.md#append-kullan%C4%B1m%C4%B1)
* [remove](https://github.com/RealBerk/python-ders-notlar-/blob/main/listeler.md#remove-kullan%C4%B1m%C4%B1)
* [insert](https://github.com/RealBerk/python-ders-notlar-/blob/main/listeler.md#i%CC%87nsert-kullan%C4%B1m%C4%B1)
* [extend](https://github.com/RealBerk/python-ders-notlar-/blob/main/listeler.md#extend-kullan%C4%B1m%C4%B1)
* [pop](https://github.com/RealBerk/python-ders-notlar-/blob/main/listeler.md#pop-kullan%C4%B1m%C4%B1)
* [reverse](https://github.com/RealBerk/python-ders-notlar-/blob/main/listeler.md#reverse-kullan%C4%B1m%C4%B1)
* [sort](https://github.com/RealBerk/python-ders-notlar-/blob/main/listeler.md#sort-kullan%C4%B1m%C4%B1)
* [min,max](https://github.com/RealBerk/python-ders-notlar-/blob/main/listeler.md#min-kullan%C4%B1m%C4%B1)
* [sum](https://github.com/RealBerk/python-ders-notlar-/blob/main/listeler.md#sum-kullan%C4%B1m%C4%B1)
* [enumerate](https://github.com/RealBerk/python-ders-notlar-/blob/main/listeler.md#enumerate-kullan%C4%B1m%C4%B1)
* [join,split](https://github.com/RealBerk/python-ders-notlar-/blob/main/listeler.md#join-kullan%C4%B1m%C4%B1)
* [in](https://github.com/RealBerk/python-ders-notlar-/blob/main/listeler.md#i%CC%87n-kullan%C4%B1m%C4%B1)



### Append Kullanımı ###
+ list = ["Elma","Armut"]   
  +  list.append("Çilek") 

[Output: ["Elma","Armut","Çilek"]]()

> Append Listenin Sonuna Eleman Ekler

### Remove Kullanımı ###
+ list = ["Elma","Armut"]   
  +  list.remove(0) 

[Output: ["Armut"]]()

> Remove Methodu / Fonksiyonu ile Girdiğiniz İndex Numarasındaki Elemanı Listeden Silebilirsiniz


### İnsert Kullanımı ###
+ list = ["Elma","Armut"]   
  +  list.insert(0,"Erik") 

[Output: ["Erik","Elma","Armut"]]()

> İnsert Methodu / Fonksiyonu ile Girdiğiniz İndex Numarasında Eleman Ekler.


### Extend Kullanımı ###
+ list = ["Elma","Armut"]   
  +  list.extend("Şeftali") 

[Output: ["Elma","Armut","Şeftali"]]()

> Extend Methodu / Fonksiyonu ile Listenin Sonuna Bir Eleman Eklersiniz. ( Tek Bir Parametre Alır )

### Pop Kullanımı ###
+ list = ["Elma","Armut"]   
  +  list.pop(0) 

[Output: ["Armut"]]()

> Pop Methodu / Fonksiyonu ile Girdiğiniz İndex Numarasındaki Elemanı Siler.

### Reverse Kullanımı ###
+ list = ["Elma","Armut"]   
  +  list.reverse("Şeftali") 

[Output: ["Armut","Elma"]]()

> Reverse Methodu / Fonksiyonu ile Listedeki Elemanları Tersten Yazdırabilirsiniz.

### Sort Kullanımı ###
+ list = ["Elma","Armut"]   
  +  list.sort(reverse= True) 

[Output: ["Armut","Elma"]]()

> Sort Methodu / Fonksiyonu ile Listedeki Elemanları Alfabetik Olarak Sıralarsınız.


### Min Kullanımı ###
+ list = [1,2,3,4,5,6,7,8,9,10]   
  +  print(min(list)) 

[Output: 1]()

> Min Methodu Listedeki En Küçük Elemanı Seçer.


### Max Kullanımı ###
+ list = [1,2,3,4,5,6,7,8,9,10]   
  +  print(max(list))

[Output: 10]()

> Max Methodu Listedeki En Büyük Elemanı Seçer.

### Sum Kullanımı ###
+ list = [1,2,3,4,5]   
  +  print(sum(list))

[Output: 15]()

> Sum Methodu Listedeki Elemanların Toplamını Alır.


### Enumerate Kullanımı ###
+ list = [1,2,3,4,5]   
  +  print(list(enumerate(a)))

[Output: [(3, 1), (4, 2), (5, 3), (6, 4), (7, 5), (8, 6), (9, 7), (10, 8), (11, 9), (12, 10)]]()

> Enumerate Fonksiyonu Bir Listeyi Numaralandırmaya Yarıyor.

### İn Kullanımı ###
+ list = [1,2,3,4,5]   
  +  print(5 in list)

[Output: True]()

> İn, Bir elemanın listede olup olmadığını kontrol etmenize yarar.

### Join Kullanımı ###
> bir listeyi tek string haline getirmek istiyor isek eğer Join (bağlamak) Method/Fonksiyonunu kullanacağız.
+ list = ["Turuncu","Mor","Mavi"]   
  +  list2 = "".join(list)
> .join'den önceki " tırnaklar arasına ne girerseniz, listedeki elemanların arasına o yazılacaktır!
[Output: TuruncuMorMavi]()

> Join Fonksiyonu, Bir Listedeki Elemanları Tek String Haline Getirmeye Yardımcı Olur.


### Split Kullanımı ###
> Bir stringi listeye dönüştürmek istiyor isek Split Methodunu kullanacağız.
+ list = "Turuncu-Mor-Mavi"  
  +  list2 = list.split("-")
> " arasındaki - sembolü bizim stringimizdeki elemanların arasında o sembol olduğu için yazdık, sizde ney olacaksa veya oysa onu yazın!
[Output: ['Turuncu','Mor','Mavi']]()

