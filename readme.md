Turkcell Gençlere Yatırım Geleceğe Yazılım 3.0 Frontend Bootcamp'i kapsaminda geliştirmiş olduğum javascript projesi.

## development icin:
### npm i ile gerekli olan paketleri kurun.
#### Hem scss'i hem de json-server'i aynı anda ayağa kaldırmak icin "concurrently" adlı paketi kullandım.
#### Böylece "npm-start" yazıldığı zaman ikisi birden ayağa kalkıyor.

<hr>

#### Sadece json-serveri ayağa kaldırmak icin "npx json-server ../db.json" komutunu kullanabilirsiniz

---

* Canlida vercel kaynakli problemler olabiliyor en iyi deneyim icin **localde** calistirin. 
* Projeyi ``npm start`` ile ayaga kaldirin.
* Daha sonra app.js içerisindeki 
  - `const baseUrl` 
  - `const secondUrl`

  kisimlarindaki localhost olanlari aktif edin.
