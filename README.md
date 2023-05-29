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
  1. - sys.argv: Adalah sebuah list dalam modul sys pada bahasa pemrograman Python. List ini berisi argumen baris perintah yang diberikan saat menjalankan skrip Python dari baris perintah atau terminal.
     - sys.stderr: Adalah objek file standar error dalam modul sys pada bahasa pemrograman Python.
     - StreamingContext: Adalah entitas utama yang digunakan untuk mengonfigurasi dan mengendalikan proses streaming data dalam Spark Streaming.
     - sc: SparkContext Untuk berinteraksi dengan kluster Spark.
     - socketTextStream: Adalah sebuah metode dalam modul pyspark.streaming di Apache Spark yang digunakan untuk membuat DStream (Distributed Stream) yang membaca data dari socket TCP.
     - reduceByKey: adalah sebuah operasi pada DStream (Distributed Stream) dalam modul pyspark.streaming di Apache Spark yang digunakan untuk menggabungkan nilai-nilai yang memiliki kunci yang sama dalam setiap batch dari DStream.
     - lambda line: Fungsi anonim dengan satu parameter line.
     - awaitTermination: Adalah metode dalam StreamingContext di Apache Spark yang digunakan untuk menunggu hingga streaming job selesai atau dihentikan secara manual.
  ```
 ```sh
  2. - nc, lk: Utilitas netcat untuk membuka koneksi dan mengirim/menerima data melalui jaringan.
  ```
```sh
  3. - spark-submit: Adalah sebuah perintah yang digunakan untuk menyerahkan (submit) aplikasi Spark untuk dieksekusi di dalam cluster Spark. Ini adalah utilitas baris perintah yang disediakan oleh Apache Spark.
     - master: Argumen untuk menentukan alamat URL atau mode eksekusi kluster Spark.
     - local[*]: Adalah mode lokal dalam Apache Spark yang digunakan untuk menjalankan aplikasi Spark di dalam satu mesin secara lokal, menggunakan semua core yang tersedia.
  ```
   ```sh
  4. - ssc.checkpoint: Adalah metode dalam StreamingContext di Apache Spark yang digunakan untuk mengatur titik kontrol (checkpoint) untuk aplikasi streaming.
      - parallelize: Digunakan untuk membuat RDD (Resilient Distributed Dataset) dari koleksi data yang ada dalam bahasa pemrograman Python. 
      - updateStateByKey: adalah sebuah operasi pada DStream (Distributed Stream) dalam modul pyspark.streaming di Apache Spark yang digunakan untuk menggabungkan nilai baru dengan status yang ada dalam setiap batch dari DStream.
      - flatMap: Membagi setiap elemen dalam RDD menjadi beberapa elemen dalam bentuk yang berbeda.
  ```
