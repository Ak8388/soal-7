# Jawaban Technical Test

## Bagian 1
```
untuk mengambil data dari api lain kita bisa menggukaan method yang sudah di sediakan oleh package internal golang yaitu http.NewRequest(), lalu menggunakan salah satu method yang ada di dalam sttruct http.Clinet yaitu http.Client.Do() untuk mengirim sebuah request. kita juga bisa set header menggunakan w.Header.Set() untuk set sebuah header jika di perlukan contohnya seperti kita akan mengirimkan sebuah token maka kita gunakan method w.Header.Set() 
```

## Bagian 2
```
Dengan cara melihat code, di dalam sebuah system code merupakan salah satu penentu performa aplikasi/system dengan menggunakan code dengan efisien maka performa pada aplikasi akan semakin baik, begitupun sebaliknya. jadi jika ada masalah berkaitan dengan performa aplikasi kita bisa liat masalahnya pada code yang sudah di buat dan, jika code di rasa tidak efisien atau banyak codingan-codingan yang di rasa tidak perlu maka hapus codingan tersebut, dan lakukan test pada sistem untuk melihat performa system tersebut jika di rasa performa ingin lebih cepat lakukan cara tadi berulang ulang.
```

## Bagian 3
```
langkah pertama untuk membuat sebuah api adalah setup server, kemudian membuat sebuah router dengan menggunakan http.HandleFunc() atau menggunakan r.Get()/r.Post dll sesuai dengan kebutuhan jika menggunakan framework gin,
selanjutnya jika kita ingin membuat sebuah method yang menerima request http maka kita bisa menggunakan request.Body untuk mengambil data dari sebuah body atau request.Header.Get() untuk mengambil data dara sebuah header contohnya seperti token. 
hal yang perlu di perhatikan dalam membuat sebuah api adalah code program karena code dalam program sangat berpengaruh bagi performa aplikasi, mulai dari penggunan method dan pastikan sytax yang di gunakan adalah syntax yang terbaru.
```