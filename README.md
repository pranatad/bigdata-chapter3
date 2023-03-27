## Nama      : Pranata Dito Fitriyansyah
## Kelas     : TI - 3C
## No. Absen : 16

BIG DATA - Chapter 3

## Hasil

## Accumulator

![Screenshot](image/Accumulator.png)

sc: singkatan dari SparkContext, ini adalah objek utama dalam pemrograman dengan Apache Spark. Ini digunakan untuk menginisialisasi aplikasi Spark dan membuat RDD (Resilient Distributed Datasets) yang mendukung komputasi paralel.

accumulator: objek shared variable yang digunakan dalam Apache Spark untuk agregasi asinkron nilai dari beberapa executor (pekerja) di sepanjang sebuah job (tugas). Biasanya digunakan untuk menghitung statistik yang kompleks atau mengakumulasikan hasil dalam loop.

parallelize: method yang digunakan pada objek SparkContext untuk membuat RDD dari koleksi data yang ada dalam program. RDD ini nantinya akan didistribusikan secara paralel pada executor (pekerja) yang tersedia.

lambda: fungsi anonim yang sering digunakan dalam pemrograman fungsional dan pemrograman paralel. Biasanya digunakan untuk melakukan operasi yang sederhana dan terbatas pada sebuah data, sehingga sangat cocok untuk dijalankan di dalam RDD.

value: tipe data dasar dalam Spark. Ini mewakili nilai tunggal dan dapat berupa tipe data apapun seperti integer, float, string, boolean, atau objek Python. Ini sering digunakan sebagai argument dalam method yang membutuhkan input data seperti map atau reduceByKey.

## Broadcast

![Screenshot](image/Broadcast.png)

## Kode 3
![Screenshot](image/Kode3.png)

## PairRDD

![Screenshot](image/PairRDD.png)

## SystemCommandsOutput

![Screenshot](image/SystemCommandsOutput.png)

## SystemCommandsReturnCode

![Screenshot](image/SystemCommandsReturnCode.png)

## UnderstandingRDDs

![Screenshot](image/UnderstandingRDDs.png)

## WordCount

![Screenshot](image/WordCount.png)

