### SK6093-Independent-Research-in-Computational-Science-3
### SK6094-Independent-Research-in-Computational-Science-4


# Monitoring Penyebaran Covid 19 pada Area Publik dengan Convolution Neural Networks (CNN) 

Pelaksanaan protokol kesehatan harus di sertai dengan pemantauan yang menjadi salah satu upaya adalah dengan melakukan monitoring terhadap pengunjung dalam hal ini berupa objek manusia.
Convolution Neural Networks (CNN)merupakan salah satu  algoritma dari deep learning yang merupakan pengembangan dari Multilayer Percepton (MLP) yang dirancang untuk  mengolah data berupa gambar. 
CNN akan digunakan pada penelitian ini untuk monitoring yaitu berupa objek manusia dengan melakukan deteksi masker dan deteksi jarak ( Social Distancing).


## research 3 : Sistem Deteksi Masker Wajah pada Area Publik Menggunakan Convolution Neural Networks (CNN)
Face Mask Detection  dapat dilakukan dengan memasang kamera di pintu masuk tempat umum seperti stasiun, bandara, tempat wisata, swalayan, dll sebagai bentuk pemantauan.
1. Dapat mengembangkan sistem pendeteksian wajah bermasker atau tidak bermasker dalam bentuk gambar.
2. Mengetahui Optimizer dan fungsi aktivasi yang paling baik dalam sistem pendektesian masker.
3. Mengetahui besar akurasi dari metode Convolution Neural Networks (CNN) dengan beberapa model.

- Face Mask Detection dengan menggunakan model Convolution Neural Networks (CNN)
- Package python yang akan digunakan : OpenCV, Tensorflow dan Keras. 
- Pengujian Variasi  Fungsi Aktivasi dan  Optimizer untuk mendapatkan nilai akurasi tertinggi.

Penelitian model pendeteksi masker dengan Convolutional Neural Network. Adapun tujuan dalam penelitian adalah untuk mengklasifikasikan foto wajah yang akan kita bagi datanya menjadi dua kelas, sehingga kita dapat menjawab pertanyaan berikut.
### Apakah orang itu memakai masker atau tidak?
Sistem deteksi masker (Face mask detection) dengan menggunakan pengolahan citra dilakukan juga untuk mengetahui besar akurasi dari metode Convolution Neural Networks (CNN) yang digunakan.



## research 4 : Deteksi Objek Manusia dan Deteksi Jarak untuk Monitoring Penyebaran Covid-19 pada Area Publik dengan Convolutional Neural Network
Deteksi objek manusia pada video dapat dilakukan secara offline maupun online untuk keperluan analisis. Selain itu, proses deteksi objek manusia juga banyak dilakukan secara real-time, seperti untuk sistem pengamanan berkendara, sistem navigasi di dalam ruangan, sistem pengaturan lalu lintas di persimpangan dan sebagainya .
1. Penelitian akan di lakukan bertujuan untuk merancang suatu program pengolahan citra yang mampu menghitung jumlah obyek manusia dengan metode Convolutional Neural Network .
2. Aplikasi : monitoring terhadap tempat umum yang berpotensi terjadinya kerumunan seperti rumah makan, tempat wisata, gedung pertemuan dan area publik lainnya yang keberadan manusia yang tidak saling mengenal untuk memudahkan tracking penyebaran covid-19.

Dalam studi ini, ide yang diusulkan dikembangkan berdasarkan kerangka kerja Python 3 dan OpenCV. Library OpenCV digunakan untuk memanfaatkan metode pemrosesan gambar yang akan dijelaskan lebih lanjut di bagian ini.
Dataset yang digunakan pada penelitian ini yaitu video OxfordTownCenter. Tujuan utama dari sistem ini adalah untuk memproses rekaman video yang diambil untuk deteksi manusia dan pemrosesan lebih lanjut untuk social distancing.

## Kesimpulan
### research 3
- Model CNN dengan penggunaan Fungsi Aktivasi softmax dan optimasi Adam nenunjukan hasil yang terbaik yaitu memiliki nilai akurasi yang tinggi dan waktu pelatihan yang cepat.
- Model CNN dengan optimasi Adadelta menghasilkan nilai akurasi yang cukup tinggi namun membutuhkan waktu pelatihan dan epoch lebih banyak dibandingkan optimasi Adam. 
- Model ini dapat dikembangkan sebagai face mask detection dengan dataset video maupun secara real time dengan menggunakan kamera.

### research 4
- Deteksi ojek manusia dan deteksi jarak atau social distancing menjadi salah satu kewaspadaan penting dalam mengurangi kontak fisik yang dapat memicu penyebaran virus corona.
- Berdasarkan hasil keseluruhan, penelitian ini dipandang dapat memenuhi semua tujuannya. Namun, ada beberapa batasan untuk hasil yang diperoleh. 
- Berdasarkan pengujian yang dilakukan pada sistem, didapatkan hasil bahwa model deteksi objek yang digunakan untuk mendeteksi manusia mengalami kesulitan dalam mendeteksi manusia dengan posisi saling berhimpitan. 
- Untuk perbaikan lebih lanjut di masa mendatang, model deteksi objek manusia yang lebih baik dapat diterapkan khususnya untuk persoalan mendeteksi manusia dengan posisi saling berhimpitan. 



