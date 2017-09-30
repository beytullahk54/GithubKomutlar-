Git oluşturma
--------




Depo Oluşturuyoruz

* Repositories/New

Github depomuzun urlsini kopyalıyoruz

* Clone or Dowload Sssh kodunu kopyalıyoruz Örnek git@github.com:beytullahk54/Uzem.git //Bir yere not alın

Github windows için cmd inidiriyoruz (Git for windows)

* https://git-for-windows.github.io/

Config ayarları

* git config --global user.name “isim,soyisim”

* git config --global user.email “email adresi”

Ssh Oluşturuyoruz

*  ls -al ~/.ssh

* ssh-keygen -t rsa -b 4096 -C "your_email@example.com"  //Enter diyerek devam ediyoruz

Ssh kodumuzu kopyalıyoruz.

* 

Git hesabımıza SSH kodumuzu entegre etme

* Settings/SSH and GPG keys/New SSH key


Yerel klasörümüze depo oluşturma

* git init

Githubtaki depomuzu tanımlama

* git remote add origin <sunucu> //  Örnek git@github.com:beytullahk54/Uzem.git Kopyaladığımız depomuzun urlsi

Yerel klasörde yeni dosya ekleme veya güncelleme 

* git add <dosyaadı> 

* git add * //Tümü

Sunucuya gönderirken bu dosyalar için değişiklik notu,

*git commit -m "Değişiklik Notu"

Sunucuya gönder

*git push -u origin master //Master bizim anadalımız 

Kaynaklar

http://rogerdudler.github.io/git-guide/index.tr.html // Basit ve net

https://github.com/COMU/bohca/wiki/G%C4%B0T-KULLANIM-KLAVUZU

https://aliozgur.gitbooks.io/git101/git_arac_ve_servisleri/kaynakca_ve_referanslar.html

https://aliozgur.gitbooks.io/git101/
