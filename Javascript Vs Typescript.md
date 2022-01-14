# Javascript Vs Typescript

[![N|Solid](https://cdncontribute.geeksforgeeks.org/wp-content/uploads/Untitled-102-300x216.png)]()

## JavaScript nedir?

JavaScript, etkileşimli web sayfaları oluşturmanıza yardımcı olan bir betik dilidir. İstemci tarafı programlama kurallarına uyarak, web sunucusundan herhangi bir kaynağa ihtiyaç duymadan kullanıcının web tarayıcısında çalışır. Javascript'i REST API'leri, XML ve daha fazlası gibi diğer teknolojilerle de kullanabilirsiniz.

Bu betiği geliştirmenin ardındaki fikir, onu Microsoft'un dil ailelerinde Visual Basic gibi C++ için tamamlayıcı bir betik dili yapmaktır. Ancak JavaScript, büyük karmaşık uygulamalar için tasarlanmamıştır. Birkaç yüz satır kod içeren uygulamalar için geliştirildi.

İlk çıktığı zamanlarda kullanım amacı küçük ölçekli uygulamalar ve tarayıcı içerisinde çalışması planlandığı için bir nesne yönelimli programlama diline göre eksliklikleri vardı.Çıkış planı olarak düşünülen ufak işlerin yanında beklenmedik şekilde popülerliğini hızlıca arttırması sahip olduğu özelliklerin kapsamlı projelerde eksik kalmasına neden oldu. Bu kapsamlar örnek olarak mobil uygulamalar ve büyük çaplı nesne yönelimli projeleri verebiliriz.

Durum böule olunca geliştiriciler bunu javascriptin bir superset'i olan yeni ve jsvascriptte olmayan tip güvenliği ve nesne yönelimli yapısını günümüzde bu ekstraları nedeniyle ciddi şekilde popülerliği artan typescript geliştirildi.

## TypeScript nedir?
TypeScript, modern bir çağda JavaScript geliştirme dilidir. Açık ve basit JavaScript kodu yazmak için statik olarak derlenmiş bir dildir. Node js'de veya ECMAScript 3 veya daha yeni sürümleri destekleyen herhangi bir tarayıcıda çalıştırılabilir.

TypeScript, isteğe bağlı statik yazma, sınıflar ve arabirim sağlar. Büyük bir JavaScript projesi için Typescript'i benimsemek size daha sağlam bir yazılım getirebilir ve normal bir JavaScript uygulamasıyla kolayca dağıtılabilir.

### KEY DIFFERENCE

> - JavaScript, etkileşimli web sayfaları oluşturmanıza yardımcı olan bir komut dosyası dilidir, Typescript ise JavaScript'in bir üst kümesidir.
> - JavaScript kodunun derlenmesi gerekmezken TypeScript kodunun derlenmesi gerekir.
> - TypeScript ve JS'yi karşılaştıran Typescript, bir prototip oluşturma özelliğini desteklerken JavaScript bu özelliği desteklemez.
> - Typescript, kullanılan verileri tanımlamak için türler ve arayüzler gibi kavramları kullanır, oysa JavaScript'in böyle bir konsepti yoktur.
> - Typescript, büyük boyutlu projeler için jenerikler ve JS özelliklerini içeren güçlü bir yazı sistemidir, oysa JavaScript küçük boyutlu projeler için ideal bir seçenektir.

[![N|Solid](https://www.guru99.com/images/1/101218_1344_Typescriptv1.png)]()

#### Neden JavaScript?

- Microsoft'un himayesinde açık kaynak projesi
- Küçük komut dosyaları için özel olarak tasarlanmış araç
- Sınıfları, arayüzleri ve modülleri destekler.
- Derlenmiş JavaScript herhangi bir tarayıcıda çalışır
- Çapraz derlemeye izin verir
- Büyük uygulamalar yazmak için JavaScript'i genişletebilirsiniz
- Sınıflar, arayüzler ve modüller için destek ekler

#### Neden TypeScript?

- TypeScript, JS kitaplıklarını ve API Belgelerini destekler
- JavaScript'in bir üst kümesidir
- İsteğe bağlı olarak yazılan betik dilidir
- TypeScript Kodu, düz JavaScript Koduna dönüştürülebilir
- Daha iyi kod yapılandırması ve nesne yönelimli programlama teknikleri
- Daha iyi geliştirme süresi aracı desteği sağlar
- Dili standart dekoratörlerin ötesine genişletebilir, zaman uyumsuz/bekliyor

[![N|Solid](https://www.guru99.com/images/1/101218_1344_Typescriptv2.png)]()

| Parameter | Javascript | Typescript |
| ------ | ------ | ----- |
| What is |	Lightweight, interpreted, object-oriented language with first-class functions | Powerful type system, including generics & JS features |
| Data Binding | No such concept is available with JavaScript. | TypeScript uses concepts like types and interfaces to describe data being used. |
| Ecosystem | JavaScript offers the option to explore and create code without a build step. | The Ecosystem is quite powerful and intuitive. Thus, it allows you to statically type various type of idiomatic JavaScript features like union types, intersection, discriminated union. |
| Npm package | JavaScript offers the option to explore and create code without a build step. | 	With Typescript, many npm packages either come with static type definitions or have an external one that is easy to install. |
| Learning curve | Flexible and easy to learn, scripting language. | Stiff learning curve. Requires prior scripting knowledge. |
| Prototyping | JavaScript doesn’t have this feature. | Typescript has a feature of prototyping. |
| Community | The JavaScript has a huge community of developers | Typescript does not have a large community of developers. |
| Compilation | No need to compile JavaScript. | TypeScript code needs to be compiled |
| Annotation | No Annotations Required is need for JavaScript. | To get the most out of TypeScript features, developers should constantly annotate their code. |
| Famous Company using the Technology |Airbnb, Codecademy, Instagram | Asana, Clever, Screen award |
| Salary | The average salary for a JavaScript Developer is $110,777 per year in the United States. | The average salary for “Typescript developer” ranges from approximately $148,027 per year in United States |

#### Features of JavaScript
> It’s a cross-platform language
> It’s used for client side and server side
> It’s easy to learn and to start with
> It’s a dynamic language: flexible and powerful
> You have ‘the great freedom’ to do whatever you want with any object
> Strong Testing Workflow
> Added Dependencies
> Framework Unsupported

#### Features of Typescript
> Maintainability
> Offered great productivity for developers
> Code navigation and bug prevention
> Code ‘discoverability’ & refactoring
> Optional Static Type Annotation / Static Typing
> Additional Features for Functions
> Supports ES6
> Supports interfaces, sub-interfaces, classes, and subclasses
> Scalable HTML5 client-side development
> Rich IDE available with autocomplete and code navigation features.
> Class-based object-oriented with the inheritance of private members and interfaces.

[![N|Solid](https://www.guru99.com/images/1/101218_1344_Typescriptv3.png)]()



# Node.js İle Basit Web Server Kurulumu

Javascript'in web tabanlı işlerinin yükünü çeken node.js paketi hakkında biraz bilgi edinelim ardından da node.js ile nasıl web server oluşturacağımıza bakalım.

## Node.js nedir?

- Node.js açık kaynaklı bir sunucu ortamıdır
- Node.js ücretsizdir
- Node.js çeşitli platformlarda çalışır (Windows, Linux, Unix, Mac OS X vb.)
- Node.js, sunucuda JavaScript kullanır

### Neden Node.js?

Node.js asenkron programlama kullanır. Bir web sunucusu için ortak bir görev, sunucuda bir dosya açmak ve içeriği istemciye geri göndermek olabilir.

##### PHP veya ASP bir dosya isteğini şu şekilde işler:

> - Görevi bilgisayarın dosya sistemine gönderir.
> - Dosya sistemi açılıp dosyayı okurken bekler.
> - İçeriği istemciye döndürür.
> - Bir sonraki isteği işlemeye hazır.

##### Node.js bir dosya isteğini şu şekilde ele alır:

> - Görevi bilgisayarın dosya sistemine gönderir.
> - Bir sonraki isteği işlemeye hazır.
> - Dosya sistemi dosyayı açıp okuduğunda, sunucu içeriği istemciye döndürür.
> - Node.js, beklemeyi ortadan kaldırır ve bir sonraki istekle devam eder.

Node.js, bellek açısından oldukça verimli olan tek iş parçacıklı, engellemesiz, eşzamansız programlama çalıştırır.

[![N|Solid](https://kinsta.com/wp-content/uploads/2021/03/Nodejs-Architecture.png)]()

#### Node.js Ne Yapabilir?

 - Node.js dinamik sayfa içeriği oluşturabilir
 - Node.js, sunucuda dosyalar oluşturabilir, açabilir, okuyabilir, yazabilir, silebilir ve kapatabilir
 - Node.js form verilerini toplayabilir
 - Node.js, veritabanınızdaki verileri ekleyebilir, silebilir, değiştirebilir


## En Basit Haliyle Bir Web Sunucusu

```js
 // http modülünü import ederek başlıyoruz.
const http = require('http')
```
```js
// url'mizi oluşturacak kısmı tanımlıyoruz.
const hostname = '127.0.0.1'

// kullanacağımız port numarasını tanımlıyoruz.
const port = 3000
```
```js
// http modülüne ait createServer fonksiyonu ile web sunucumuzu ilgili parametreleri veriyoruz.

const server = http.createServer((req, res) => {
  res.statusCode = 200
  res.setHeader('Content-Type', 'text/plain')
  res.end('Hello World\n')
})
```

```js
// Daha sonra kurduğumuz serverın durumunu konsoldan görmek için listen fonksiyonunu kullanıyoruz.

server.listen(port, hostname, () => {
  console.log(`Server running at http://${hostname}:${port}/`)
})
```



##### Faydalı Linkler (Js Vs Ts)

[(120+ Saat) Komple Uygulamalı Web Geliştirme Eğitimi | Udemy][udemy]
[TypeScript Kursu | Yeni Başlayanlar İçin Typescript - YouTube][youtube1]
[1 VİDEODA TYPESCRIPT - YouTube][youtube2]
[1 Videoda Javascript Temellerini Öğrenin - YouTube][youtube3]

##### Faydalı Linkler (Node.js)
[Node.js Öğrenmek İsteyenler İçin][nodejsdev]
[Node.js Hakkında Detaylı Bilgiler][nodejsorg]
[Kısa kısa node.js kullanım örnekleri][w3]

[udemy]: <https://www.udemy.com/course/komple-web-developer-kursu/>
[youtube1]: <https://www.youtube.com/watch?v=1d92ipW7Mx8>
[youtube2]: <https://www.youtube.com/watch?v=LEKyAW3jPKA&t=2228s>
[youtube3]: <https://www.youtube.com/watch?v=-ei7CLxoOVU&t=647s>

[nodejsdev]: <https://nodejs.dev/learn>
[nodejsorg]: <https://nodejs.org/en/about/>
[w3]: <https://www.w3schools.com/nodejs/nodejs_intro.asp>