# Dasar Menggunakan Bahasa Program HTML<hr>


![perintah](image/2022-03-10.png)
### Perbedaan tag `<p>` dan `<br>`?

Fungsi dari tag `<p>` membuat paragraf baru, sedangkan `<br>` membuat paragraf baru dan memberikan jarak pada paragraf pertama yang telah dibuat dengan menggunakan tag`<p>`.
![penjelasan <p> dan <br>](image/non%20align1.png)
```html
    <!--ini adalah paragraf pertama-->
    <p> 
        Kami sedang belajar HTML dasar, pada matakuliah Pemrograman Web di Prodi Teknik Informatika 
        Universitas Pelita Bangsa. Pelajaran pertama yang kami dapat adalah membuat tampilan web 
        sederhana dalam rangka mengenal tag-tag dasar HTML.
    </p>
```

```html
    <br> <!--ini adalah paragraf kedua-->
    <p>
        Ini merupakan sebuah paragraf yang terdiri dari beberapa kalimat yang saling
        mendukung sehingga menjadi satu kesatuan. Paragraf dibuat dengan menggunakan
        tag dasar html.
    </p>
```

### Perbedaan atriburt dari tag `title` dan `alt` pada tag `<img>`

Jika menggunakan atribut `title` maka saat crusor berada tepat digambar akan muncul title dari gambar tersebut

![title](image/title.png)
```html
<img src="LOGO UPB.png" width="200" title="Logo Universitas Pelita Bangsa">
```
Jika menggunakan atribut `alt` tidak bisa menampilkan title dari gambar tersebut
```html
<img src="LOGO UPB.png" width="200" alt="Logo Universitas Pelita Bangsa">
```
![alt](image/alt.png)