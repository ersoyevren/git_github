## Git_Github Kullanımi

## Git nedir?
Git, yazılım sektöründe versiyon kontrolü amacıyla kullanılan en popüler servislerden bir tanesidir. 

## GitHub nedir?

GitHub ise bu servisin bulut versiyonudur, yani kodlarınızı uzak bir sunucuda Git sistemiyle saklamanıza yardımcı olur.

GitHub komut satırını kullanırken kullanabileceğiniz yüzlerce komut vardır. 

## Sık Kullanılan Git&GitHub Terimleri

### `git --version`e
ile gitin yuklu olup olmadigini ve versiyonunu kontrol edebiliriz.

### `git config --global user.name ('kullanici adi')`
kullanici adini belirliyoruz.

### `git config --global email.name('email adresi')`
emailimizi belirliyoruz.

### `git config --global core.editor` 'vim'
default editoru olarak **vim**i belirlemis olduk.

### `git config --list`
yapilandirma ayarlarini gorebiliyoruz.

### `git status` 
dosyalarin hangi asamada oldugunu goruyoruz. ayrica biz hangi branch ta yer almaktayiz. 

### `git help`
gitte calisan komutlarin ne anlama geldiginiz gorebiliyoruz.

### `git revert (commit id)`
istedigimiz committe yapilan degisikligi geriye alma.

### `git commit --help` 
ornegin commit komutunun ne ise yaradigini gorebiliyoruz.

### `git init` 
dosyayi takibe aldiriyoruz.

### `git add (dosya adi)` 
working alanindan dosyayi staging area alanina gonderiyoruz.

### `git add .` 
dosyadaki butun dosyalari stating area ya gonderiyoruz.

### `git commit -m ('aciklama')` 
staging areadaki dosyayi local repository e gonderiyoruz.artik dosya takip edilebilir. buradaki aciklama, versiyonda yaptigimiz degisiklik acisindan onemlidir.

### `git commit -am ('aciklama')` 
degisikligi direk add yapmadan commit yapiyor.

### `git commit --ammend -m 'aciklama'` 
repository de aciklamada kucuk duzenleme yapabiliyoruz.

### `git rm --cached (dosya adi) veya git restore --staged` 
staging areadan working  alanina dosyayi geri gonderiyoruz.

### `git log` 
commiti ekrana yazdiriyoruz. burada kullanici bilgileri ve id gozukecektir.

### `git log oneline` 
sadece ekrana commiti tek satirda yazdiriyoruz.

### `git checkout (branch veya code)` 
gitmek istedigimiz branchin adini yaziyoruz.

### `git log --all` 

### `git branch (branch adi)` 
yeni bir branch olusturuyor.

### `git checkout -b (dosya adi)`
yeni bir branch olusurup ona direk gidebiliriz.

### `git branch -d (dosya adi)`
ismi yazilan dosyayi siliyoruz.

### `git branch -d (dosya adi)`
ismi yazilan dosyayi zorla siliyor.

### `git branch -r` 
localdeki branchleri listeliyor.

### `git branch -a` 
var olan butun branchleri gorebiliyoruz.

### `git -b (yeni branch adi)`
olusturmak istedigimiz branchin adini yazariz.


### `git reset 4r5454 (commit id'si) --hard` 
commite kesin donus yapilir ve sonraki degisiklikler silinmis olur.

### `git reset 4r5454 (commit id'si) --soft` 
dosyalari staging areaya ktasiyor.

### `git merge (branch adi)`
var olan branchin uzerine adi yazilan branchi birlestirir.

### `git log --graph` 

### `git log --all --graph` 

### `git push origin (branch ismi)` 
Bu komut ile, yerelde hazırlanıp kaydedilen değişiklikler, GitHub'daki repository'e gönderilir.

### `git clone adress` 
remote daki dosyayi localdeki dosyaya alir.

### `git push` 
daha onceden eslestirilmis localdeki daki dosyada degisiklik yapilmissa bunu remotaki dosyaya gonderir. 


### `git fetch` 
daha onceden remote da yapilan degisiklikleri gosterir. fakat birlestirmez. birlestirmek icin pull kullanmak gerekiyor.

### `git pull` 
daha onceden eslestirilmis remote daki dosyada degisiklik yapilmissa bunu localdeki dosyaya alir. 

### `git remote add origin repo adress`
uzaktaki repo ile iletisim kurariz.


### `git push -u origin master`
ilk push da gereklidir.

### `git remote rm origin` 
uzaktaki origin i siler.



##ekstra komutlar 
### `mkdir (dosya adi)` 
klasor olustururuz.

### `touch (dosya adi)` 
yeni bir dosya olustururuz.

### `vim (dosya adi)` 
dosyanin icine giris yapabiliyorum. ardindan i tusu yazmaya baslayabilirim. daha sonra esc tusu ve :wq komutu ile cikis yapabilirim.

### `explorer.exe .` 
icinde bulundugumuz dosyayi ayri bir sayfa olarak ekranda acar.

### `rm -rf (dosya adi)` 
dosyayi sileriz.

### `history` 
yazdigim komutlarin gecmisini goruruz.

### `clear veya ctrl+c` 
sayfayi temizliyoruz.

### `cat (dosya adi ve uzantisi)` 
dosyanin icerigini okuruz.

### `code .`


### `pwd` 
hangi dosyanin icindeyiz gorebiliyoruz.

### `ls` 
icinde bulundugumuuz dosyanin icindeki dosya ve dizinleri gorebiliyoruz.

### `ls -a` 
icinde bulundugumuuz dosyanin icindeki gizli dosya ve dizinleri gorebiliyoruz.

### `cd (dosya veya dizin adi)` 
o dosyaya gidebiliyorum.

### `cd ..` 
bir ust dosyaya gidebiliyorum.

### `touch .gitignore`
bu dosyayi olusturduktan sonra icine yazdiklarimizi diger kullanicilar tarafindan gorulemez. bunu git status ile kontrol edebiliriz. 
ornegin: .gitignore dosyasinin icine var olan deneme dosyasini ekledigimizde artik deneme dosyasi gorulmeyecektir. deneme* yaparak butun **deneme** altindaki dosyalarin gorulmesini engelleyebiliriz. Eger deneme dosyasininin altinda bir dosyanin gorulmesini istiyorsak !deneme/ali diyebiliriz. bu durumda sadece ali dosyasi gorulecektir.



## Sık Kullanılan GitHub Terimleri

### Repository

Kelime anlamı: depo, veri deposu, veri havuzu.

Projenin bütün dosya ve klasörlerini içinde tutan veritabanı gibi düşünülebilir. Her bir proje, GitHub'da bir repository olarak tutulabilir. Sadece dosyalar değil, dosyalarda yapılan değişikliklerin geçmişi de burada tutulur.

Bir repository birden fazla kullanıcı arasında paylaşılabilir ve kopyalanabilir (bkz: fork).

### Branch

Kelime anlamı: dal, şube, ayırmak.

Projeye yeni bir özellik eklenmek istendiğinde ya da bir değişiklik yapılacağı zaman, yeni bir branch açılır ve bütün değişiklikler bu branch üzerinde yapıldıktan sonra master branch ile birleştirilir (bkz: merge).

### Fork

Kelime anlamı: çatal, çatallanmak.

Başka birisine ait bir repository üzerinde çalışmak istediğinizde projeyi kendi GitHub hesabınıza kopyalamak için onu fork edebilirsiniz. Fork edilen projeler, projenin aslında bir güncelleme olduğunda bu değişikliklerden etkilenmezler.

Kendi hesabınıza kaydetmek istediğiniz projenin GitHub sayfasında sağ üst köşedeki Fork butonuna basarak fork işlemini gerçekleştirebilirsiniz.

### Clone

Kelime anlamı: kopyalamak, klonlamak.

Bir projeyi bilgisayarınıza indirmek istediğinizde clone komutunu kullanabilirsiniz.

Terminal'e `git clone https://github.com/reactdersleri/github.git` yazıp gönderdiğinizde, `github` isimli proje, o an bulunduğunuz dizinde `github` ismiyle oluşturulan klasörün içine kopyalanacaktır. Bir repository'e ait clone linkine ulaşmak için, projenin GitHub sayfasında sağ taraftaki yeşil `Clone or download` butonuna basarak yahut projenin linkinin sonuna `.git` uzantısını koyarak erişebilirsiniz.


Takım çalışmalarında branch ismi önemlidir. Takımın her bir üyesi, kendi ismiyle yahut üzerinde çalıştığı özelliği açıklayıcı bir branch oluşturmalıdır. Bu branch'a kaydedilen değişiklikler bir `pull request` oluşturularak master branch ile birleştirilmek üzere takım liderinin onayına sunulmalıdır. Böylece hatalı (buggy) kodların gözden geçirilmeden ana ürün olarak sunulmasının önüne geçilecektir.

    NOT: İlk push işlemini gerçekleştirdiğinizde, bir pencere açılacak ve buradan GitHub'a giriş yapmanız istenecektir.

    NOT: Visual Studio Code ile çalışırken, sol alt köşede üzerinde çalıştığınız branch ismini görebilirsiniz.
    
#GIT  README KULLANIMI

[Standart syntax kuralları](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)

[Tablo oluşturmak için syntax kuralları](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/organizing-information-with-tables)

Interview Questions

###What is Git?

Git is a free and open source, distributed version-control system for tracking changes in source code during software development.

###What is the major focus of a Version Control System?

A major focus of version control system (also known as revision control or source control) is to manage the changes to the files, programs, logs, and other information related to code development, code deployment, and code operation.

###What is a Repository?

A repository is a directory or storage space where your projects can live. You can keep code files, text files, image files, etc. inside a repository.

###What are the Git states?

Modified,
Staged,
Committed.

