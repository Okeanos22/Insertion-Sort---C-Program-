Insertion Sort - C Programı
Bu proje, Insertion Sort algoritmasını kullanarak bir diziyi sıralayan basit bir C programıdır. Program, diziyi sıralı hale getirmek için her elemanı doğru pozisyona yerleştirir.

İçerik
insertion_sort.c: Insertion Sort algoritmasını içeren C programı.

README.md: Proje hakkında açıklamalar ve kullanım talimatları.

Özellikler
Zaman Karmaşıklığı: O(n^2), burada n dizinin eleman sayısını ifade eder.

Alan Karmaşıklığı: O(1), çünkü algoritma ek bir bellek alanı kullanmaz.

Sıralama Yöntemi: Insertion Sort, her yeni elemanı sıralı alt listeye ekleyerek diziyi sıralar.

Kurulum ve Kullanım
Gerekli Yazılımlar
C derleyicisi (gcc veya herhangi bir C derleyici)

Programı Çalıştırma
Kaynak Kodunu İndir:

bash
Kopyala
Düzenle
git clone https://github.com/kullanici_adi/insertion-sort-c.git
C Kodunu Derle:

Terminal veya komut istemcisinde, projeyi indirdiğiniz dizine gidin ve derleme komutunu çalıştırın:

bash
Kopyala
Düzenle
gcc insertion_sort.c -o insertion_sort
Programı Çalıştır:

Derleme başarılı olduktan sonra, programı çalıştırmak için aşağıdaki komutu kullanabilirsiniz:

bash
Kopyala
Düzenle
./insertion_sort
Çıktı:
Program, sıralanmamış ve sıralanmış diziyi ekrana yazdıracaktır.

Örnek Çıktı:

yaml
Kopyala
Düzenle
Dizi önceki hali: 
12 11 13 5 6
Dizi sıralanmış hali: 
5 6 11 12 13
Algoritma Açıklaması
Insertion Sort, her bir öğeyi doğru pozisyona yerleştiren ve diziyi sırasıyla sıralayan bir sıralama algoritmasıdır. Algoritma, dizinin her elemanını alır ve onu sıralı bir alt listeye ekler. Bu işlem, dizinin sonuna kadar devam eder.

Adımlar:

İkinci elemandan başlayarak, her elemanı alır ve sıralı alt listede uygun pozisyona yerleştirir.

Her yeni eleman, daha önce sıralı olan dizinin bir kısmında doğru pozisyonda yer alacak şekilde yerleştirilir.

Bu işlem tüm diziyi sıralayana kadar devam eder.

Katkıda Bulunma
Eğer projeye katkıda bulunmak isterseniz, lütfen aşağıdaki adımları takip edin:

Bu projeyi çatallayın (fork).

Yeni bir dal (branch) oluşturun.

Değişikliklerinizi yapın ve test edin.

Pull request (PR) gönderin.

Lisans
Bu proje, MIT Lisansı ile lisanslanmıştır.