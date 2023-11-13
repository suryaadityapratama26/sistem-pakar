<a name="br1"></a> 

ARTIFICIAL INTELLIGENT

Sistem pakar untuk

diagnosa penyakit pasca

melahirkan menggunakan

metode *depth first search*

Kelompok 1 :

Andika Anantyo

(5311421017)

(5311421023)

(5311421026)

Dimas Alfarizky Ilham

Surya Aditya Pratama



<a name="br2"></a> 

Topik pembahasan

Latar Belakang

Pengujian

Sistem Pakar

Kesimpulan



<a name="br3"></a> 

Latar belakang

Sistem Pakar (*expert system*) adalah sistem yang berusaha mengadopsi pengetahuan

manusia ke komputer agar komputer dapat menyelesaikan masalah seperti yang biasa

dilakukan oleh para ahli. Agar sistem dapat menyelesaikan sebuah masalah, diperlukan

sebuah alur sistem yang dapat mencari solusi dari permasalahan dengan pendekatan, yaitu

menggunakan Metode *Depth First Search* (DFS). Salah satu permasalahan yang dapat

diatasi oleh sistem pakar ini yaitu diagnosis penyakit pasca melahirkan.



<a name="br4"></a> 

Metode *depth first search*

Pada algoritma DFS, pencarian dilakukan pada satu node dalam setiap level dari yang

paling kiri. Jika pada level yang paling dalam solusi belum ditemukan, maka pencarian

dilanjutkan pada node sebelah kanan. Node yang di kiri dapat dihapus dari memori. Jika

pada level yang paling dalam belum ditemukan solusi, maka pencarian dilanjutkan ke level

sebelumnya. Demikian seterusnya sampai ditemukannya solusi. Jika solusi ditemukan,

maka tidak diperlukan proses *backtracking* (penelusuran untuk mendapatkan jalur yang

diinginkan).



<a name="br5"></a> 

Dalam pencarian mengguanakan algoritma *Depth*

*First Search* (DFS), simpul-simpul yang paling

dalam pada tree yang akan dicari paling awal.

Sebagai contoh gambar disamping, urutan

pencarian awal (S) sampai keadaan tujuan (G)

adalah dimulai dari node S, kemudian ke node A,

kemudian ke node B, kemudian ke node C,

setelah itu akan menuju node E, selanjutnya akan

menuju node D, setelah itu akan menuju node F

setelah melewati node E, dan yang terakhir akan

menuju node G



<a name="br6"></a> 

Base rule

•Pembuatan tabel keputusan (*decision table*) yang berguna untuk mendokumentasikan

dan mendeskripsikan pengetahuan

•Pembuatan pohon keputusan (*decision tree*) yang berguna untuk menghilangkan

kaidah-kaidah dengan tujuan untuk meniadakan terjadinya perulangan pertanyaan

•Konversi pohon keputusan menjadi kaidah produksi



<a name="br7"></a> 



<a name="br8"></a> 



<a name="br9"></a> 



<a name="br10"></a> 



<a name="br11"></a> 

Interface



<a name="br12"></a> 

Pengujian (Pretest dan Posttest)



<a name="br13"></a> 



<a name="br14"></a> 



<a name="br15"></a> 

Kesimpulan

Penggunaan sistem pakar menggunakan metode DFS dapat berjalan dengan baik.

Terkait dengan hasil pengujian dari aplikasi sistem pakar yang dibangun dengan

menggunakan metode *depth first search* (DFS), dibuktikan dengan hasil uji *pretest* dan

*post test* bahwa dengan jumlah total data uji 50 data menghasilkan 62% data akurasi

*pretest* dan 74% data akurasi *posttest*.

