
# Sinif, obyekt və referans/istinad dəyişəni anlayışları (JAVA class, object, reference variable)

Siniflər və Obyektlər Obyektyönümlü Proqramlaşdırmanın əsas anlayışlarıdır.

![Uygulama Ekran Görüntüsü](https://www.atnyla.com/library/images-tutorials/class-and-object-in-java-3.PNG)

## Siniflər

Hər bir ***sinif*** ümumi xassələri olan ***obyektlərin toplusudur.*** 
Java-da siniflərinin atributları ***dəyişənlərlə***, davranışları isə ***metodlarla*** müəyyən edilir. 
Hər bir sinifdəki metodlarla həmin sinfin dəyişənlərindən istifadə edə bildiyimiz kimi müxtəlif siniflərə qoşularaq onların dəyişən və metodlarından da istifadə edə bilərik.

### Sinifin yaradılması 

![Uygulama Ekran Görüntüsü](https://i2.paste.pics/bffa72fda3dfa7c092ea81a19f29f16b.png)


## Obyekt
Obyekt yönümlü proqramlaşdırmada obyektlər siniflərdən yaradılır. 
Siniflərdən fərqli olaraq, obyektlər canlıdır və eyniliklərə malikdir. 
Eyni sinifdən yaradılan iki obyektin xüsusiyyətləri oxşar və fərqli ola bilər. 
İfadənin obyekt olması üçün o, ***yaddaşda yerini*** göstərməlidir. 
Obyekt özü haqqında, yerinə yetirə biləcəyi əməliyyatlar haqqında məlumatları saxlayır. 
Proqrama lazım olan bütün məlumatlar obyektlər tərəfindən saxlanılır. 
Görülən əməliyyatın növündən asılı olaraq obyektlər müxtəlif məlumatlardan ibarətdir.

![Uygulama Ekran Görüntüsü](https://i2.paste.pics/e736c028f6f8cc29e983353caf1fdbe7.png)

Yuxarıda obyektin yaradılması prosesi öz əksini tapıb. 
**new** açar sözü və **konstruktor** anlayışları verilib. 
Bunlar haqqında ətraflı şəkildə metod və konstruktor mövzusunda danışacağıq.

## Referans/istinad Dəyişəni

İstinad dəyişənini başa düşmək üçün bəzi məqamları gözdən keçirək:

- İstinad dəyişəni obyekti/qiymətləri təmsil etmək üçün istifadə olunur.

![Uygulama Ekran Görüntüsü](https://1.bp.blogspot.com/-gKWUcwIKWWU/VvPtKUAIFjI/AAAAAAAAFRc/WLCqWfSxlZ4ioocmBuFS3KaRhzs0I13OA/w1200-h630-p-k-no-nu/Difference%2Bbetween%2Bstack%2Band%2Bheap%2Bmemory%2Bin%2BJava.gif)

- Siniflər, interfeyslər, massivlər, siyahılar və annotasiyalar Java-da istinad növləridir. İstinad dəyişənləri Java-da istinad növlərinin obyektlərini/dəyərlərini saxlayır.
- İstinad dəyişəni də null dəyəri saxlaya bilər. Varsayılan olaraq, heç bir obyekt istinad dəyişəninə ötürülmürsə, o, null dəyərini saxlayacaq.

![Uygulama Ekran Görüntüsü](https://i2.paste.pics/1d8922b94eb2f2f9c56f953e49d35a58.png)

- Nöqtə sintaksisindən istifadə edərək istinad dəyişənindən istifadə edərək obyekt üzvlərinə daxil ola bilərsiniz.

![Uygulama Ekran Görüntüsü](https://i2.paste.pics/f3cff5cd153da600d36bb75f8867e890.png)

### Çoxlu obyektlər (Multiple Objects)

Xatırlatmaq istərəm ki bir sinfə aid birdən çox obyekt yaradıla bilər :

![Uygulama Ekran Görüntüsü](https://i2.paste.pics/3cf0ebd14559954d8e9605eab94674fd.png)

## İstinadlar

Bu yazı aşağıdaki mənbələrdən yararlanılaraq hazırlanmışdır:

- https://www.geeksforgeeks.org/classes-objects-java/
- https://www.geeksforgeeks.org/reference-variable-in-java/
- https://www.w3schools.com/java/java_classes.asp#:~:text=Previous%20Next%20%E2%9D%AF-,Java%20Classes%2FObjects,such%20as%20drive%20and%20brake.
- https://www.upwork.com/resources/what-is-null-in-java#:~:text=Null%20is%20a%20reserved%20keyword,any%20other%20keyword%20in%20Java.



