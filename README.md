## Tugas Praktikum
1. Silakan selesaikan praktikum tersebut sesuai langkah-langkah sebelumnya, lalu laporkan hasilnya berupa link repository GitHub dengan nama spark-streaming disertai dengan screenshot hasilnya.
2. Jelaskan perbedaan spark streaming dengan metode stateless dan stateful stream processing ?
3. Jelaskan masing-masing maksud kode berikut sesuai nomor kodenya pada laporan praktikum Anda!
## Jawaban
1. Stateless Stream Processing: Stateless stream processing berarti setiap baris data dalam aliran diolah secara independen tanpa mempertahankan atau menggunakan status sebelumnya. 
2.  Stateful Stream Processing: Stateful stream processing berarti status (state) dari aliran data dipertahankan dan digunakan dalam pengolahan berikutnya.
## Tugas Syntax
<img src = 'https://github.com/rijalammar1/Chapter5_BIGDATA/assets/75898886/7a0515f5-234b-45e7-b6a3-776c3895d5c0' width=60% height=50%>

 ```sh
  1. - sys.argv: Variabel yang berisi argumen baris perintah saat menjalankan skrip Python.
     - sys.stderr: Saluran standar untuk output kesalahan.
     - StreamingContext: Konteks inti dalam Spark Streaming untuk pemrosesan streaming.
     - sc: SparkContext untuk berinteraksi dengan kluster Spark.
     - socketTextStream: Membuat DStream dari data yang diterima melalui socket.
     - reduceByKey: Menggabungkan nilai-nilai dengan kunci yang sama dalam RDD menggunakan fungsi pengurangan.
     - lambda line: Fungsi anonim dengan satu parameter line.
     - awaitTermination: Meminta StreamingContext agar tetap berjalan hingga pemrosesan streaming selesai.
  ```
