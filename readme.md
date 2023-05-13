# JS Cloacking

Project **HTML+Javascript** sederhana untuk mendeteksi apakah user menggunakan Mobile Devices atau Tidak. Project ini digunakan sebagai *Cloacking* untuk ngiklan di Google Ads ataupun Facebook Ads. Project ini menggunakan library dari [UAParser.JS](https://github.com/faisalman/ua-parser-js) untuk mendeteksi Mobile Devices. Project ini sudah dilengkapi **BotDetection (Search Engine Crawler/Spider Bot)** untuk mendeteksi apakah user merupakan bot atau bukan.

## Demo JS Cloacking

Kamu bisa melihat demonya di : [**https://jscloacking.netlify.app**](https://jscloacking.netlify.app)

## Config JS Cloacking

Configuration bisa dilakukan pada file **index.html** pada bagian
```Javascript
    /*  YOU CAN MODIFY THIS  */
    /*  config start  */
    const redirectUrls = [
      'https://google.com',
      'https://github.com'
    ];
    const delay = 5000;
    /*  config end  */
```
Penjelasan Config:
- **redirectUrls** = silahkan isi dengan Web Redirect yang kamu inginkan (bisa 1 saja atau beberapa, jika ada lebih dari 1 url maka akan di random). Jika user menggunakan Mobile Devices dan berasal dari Iklan Google Ads ataupun Facebook Ads, maka akan diredirect ke domain yang kamu isi.
- **delay** = kamu bisa isi delay dengan nominal (ex. 5000 berarti 5 detik), delay ini berfungsi jika misalnya user tidak dapat dideteksi apakah berasal dari mobile atau tidak, tetapi terdapat parameter dari GAds atau FBAds maka akan teredirect otomatis setelah 5 detik.

## Author

Github : [AHMADJN](https://github.com/ahmadjn)
## License

[MIT](https://choosealicense.com/licenses/mit/)
