# JS Cloacking

Project **HTML+Javascript** sederhana untuk mendeteksi apakah user menggunakan Mobile Devices atau Tidak. Project ini digunakan sebagai *Cloacking* untuk ngiklan di Google Ads ataupun Facebook Ads. Project ini menggunakan library dari [UAParser.JS](https://github.com/faisalman/ua-parser-js) untuk mendeteksi Mobile Devices. Project ini sudah dilengkapi **BotDetection (Search Engine Crawler/Spider Bot)** untuk mendeteksi apakah user merupakan bot atau bukan.

## Demo JS Cloacking

Kamu bisa melihat demonya di :
- Asli : [**https://jscloacking.netlify.app**](https://jscloacking.netlify.app)
- Contoh Link Google Ads (Akses Pake HP) : [**https://jscloacking.netlify.app/?gclid=Cj0KCQiA6fafBhC1ARIsAIJjL8l8STD8I7XcEwEFwsOkhxwooUfsknaGJ3IA5aPV6xjL7oak0NIL3s0aAvsrEALw_wcB**](https://jscloacking.netlify.app/?gclid=Cj0KCQiA6fafBhC1ARIsAIJjL8l8STD8I7XcEwEFwsOkhxwooUfsknaGJ3IA5aPV6xjL7oak0NIL3s0aAvsrEALw_wcB)

## Config JS Cloacking

Configuration bisa dilakukan pada file **index.html** pada bagian
```Javascript
    /*  YOU CAN MODIFY THIS  */
    /*  config start  */
    const redirectUrls = [
      'https://google.com',
      'https://github.com'
    ];
    /*  config end  */
```
Penjelasan Config:
- **redirectUrls** = silahkan isi dengan Web Redirect yang kamu inginkan (bisa 1 saja atau beberapa, jika ada lebih dari 1 url maka akan di random). Jika user menggunakan Mobile Devices dan berasal dari Iklan Google Ads ataupun Facebook Ads, maka akan diredirect ke domain yang kamu isi.

## KONTEN

Untuk masalah konten JSCloackingnya, silahkan edit sendiri mulai dari title, sama isi artikelnya. Formatnya HTML sederhana kok.

## Author

Github : [AHMADJN](https://github.com/ahmadjn)
## License

[MIT](https://choosealicense.com/licenses/mit/)
