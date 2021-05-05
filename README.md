# Android-Movie-App


Retrofit API

Retrofit merupakan pustaka type-safe HTTP Client untuk Android, Java, dan Kotlin. Pustaka ini bertujuan untuk merubah bentuk REST API menjadi bentuk interface dalam Java atau Kotlin agar kita dapat lebih mudah dalam mengkonsumsi REST API (berperan sebagai REST client) lewat kode aplikasi untuk kebutuhan transaksi data.

Retrofit menggunakan pustaka OkHTTP sebagai “mesin” untuk dapat berjalan. Jika OkHTTP merupakan pustaka HTTP client biasa maka bisa di katakan lebih “sakti” karena Retrofit memiliki fitur di atas itu. Retrofit memberikan fitur type-safe agar pada saat kita mengkonsumsi REST API di Android menjadi lebih terstruktur dan teratur. Dengan pustaka ini juga, membuat kode yang kita tulis menjadi lebih modular,fleksibel dan mudah untuk di pelihara (maintenance).

Terdapat 3 komponen utama dalam Retrofit, yaitu :

- [x] Database
- [x] Model
- [x] Data Access Object

## Database 
merupakan class object (singleton) yang di gunakan untuk mendaftarkan class Data Access Object dan berfungsi sebagai titik akses utama ke remote database (REST API).

## Model 
merupakan class yang di gunakan untuk menyimpan suatu nilai atau data. Retrofit membutuhkan class model untuk menyimpan data respon yang di dapat dari REST API.

## Data Access Object (DAO) 
merupakan antaramuka (interface) yang di gunakan retrofit untuk akses data dari class client ke remote database (REST API) serta memuat metode yang di gunakan untuk mengakses resourcenya.

Instalasi dan Konfigurasi Retrofit
Untuk dapat menggunakan Retrofit di project yang tengah kita kembangkan hal pertama yang harus di lakukan adalah menambahkan dependency retrofit pada Gradle Scripts, tambahkan kode berikut ini :

    implementation "com.squareup.retrofit2:retrofit: (last version)"
    implementation "com.squareup.retrofit2:converter-gson: (last verion)"
  
 # Project View
 
<a href="https://www.fsf.org">
	<img align="center" src="https://github.com/rendiwibawa/Android-Movie-App/blob/master/ezgif.com-gif-maker%20(4).gif">
</a>
