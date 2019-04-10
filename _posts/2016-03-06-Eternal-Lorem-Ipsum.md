---
layout: post
title: "Ionic V3"
date:   2019-04-10 02:05:01 +0300
author: Ali Kemal Sahin
---

### NEDEN IONIC?
    •Tamamen ücretsiz ve açık kaynaklıdır.
    •IONIC Framework, yazacağınız tek bir kod ile Android, iOS, Windows Mobile ve BlackBerry gibi tüm platformlarda web sitesi geliştirir gibi uygulama yazmanızı sağlayan bir sistemdir.
    •Ionic AngularJS üzerine inşa edilmiştir.AngularJS, bugün kullanımda olan ve Google tarafından desteklenen en popüler JavaScript çerçevelerinden biridir.
    •Uygulamanızı Chrome tarayıcı üzerinde Android ve iOS platformlarının emülatörleriyle uğraşmaksızın test edip görüntüleyebilirsiniz. LiveReload özelliği ile yaptığınız her değişiklik anında görünür.
    •Özelleştirilmesi kolay, güzel bir varsayılan arayüze sahiptir.
    •Test etmek kolay.
    •Ionic sayesinde native uygulamalar kadar hızlı hybrid mobil uygulamalar geliştirebilirsiniz.

---

### Ionic v3 Kurulum



* **1. Öncelikle yazacağımız kodları derleyebilmemiz için Visual Studio Code kurmamız gerekiyor.**
[Visual Studio Code](https://code.visualstudio.com/Download) buradan indirebilirsiz.

* **2. Ionic Framework ile geliştirmeye başlamadan önce ilk olarak bilgisayarınızda Node.js’in kurulu olması gerekiyor.**
[NodeJS](https://nodejs.org/en/) buradan indirebilirsiz.


* **3. Şimdi Ionic'i yüklemeye başlayacağız.Bunun için konsoldan(cmd) işlemlerimizi gerçekleştiricez.Konsola Bu komut enterlanır.**
```
npm install -g ionic
```

* **4.Kurulumu başarıyla tamamladıktan sonra artık proje oluşturup üzerinde çalışmaya başlayabiliriz.Bunun için tekrardan konsola bu komutlar enterlanır.**
```
ionic start projeAdi templateAdi (Template Adları:blank,tabs,sidemenu,super,tutorial)
```
* **5.Çalıştırmak için son adımdayız.Öncelikle konsoldan proje dosyamızın içine girmemiz gerekiyor.Bunun için projeyi oluşturduğumuz dizinin içine gidilir ve bu komut girilir.**
```
cd projemizinAdi
```
* **6.Son olarak local host'a bağlanılır.Konsola enter lanır.**
```
ionic serve ( Tarayıcınızda görüntülenir --> http://localhost:8100 )
```
