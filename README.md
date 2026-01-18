# Phishing-Emails-in-Action-Email-Phishing-dalam-Aksi

Perkenalan
Setelah kita membahas dasar-dasar mengenai email di Email Phishing 1 , mari kita langsung masuk ke contoh email  phishing yang sebenarnya.

Setiap contoh email yang ditampilkan di ruangan ini akan menunjukkan taktik berbeda yang digunakan untuk membuat email phishing terlihat sah. Semakin meyakinkan email phishing tersebut , semakin tinggi kemungkinan penerima akan mengklik tautan berbahaya, mengunduh dan menjalankan file berbahaya, atau bahkan mengirimkan transfer uang kepada pangeran suatu negara. 

Peringatan : Contoh-contoh di ruangan ini berisi informasi dari email spam dan/atau phishing yang sebenarnya . Berhati-hatilah jika Anda mencoba berinteraksi dengan IP, domain, lampiran, dan lain sebagainya.
# Batalkan pesanan PayPal Anda
Contoh email dalam tugas ini akan menyoroti teknik-teknik berikut:

Alamat email palsu
Layanan pemendekan URL
HTML untuk meniru merek yang sah
Berikut beberapa pengamatan singkat tentang contoh email ini:

Ini adalah alamat penerima email yang tidak biasa. Ini bukan alamat email yang terkait dengan akun Yahoo. 
Ketidaksesuaian ini seharusnya langsung terlihat. Detail pengirim (service@paypal.com) tidak sesuai dengan alamat email pengirim (gibberish@sultanbogor.com). 
Judul email mengisyaratkan bahwa Anda telah melakukan pembelian atau transaksi tertentu. Jika Anda tidak mengingat akun ini, maka email tersebut akan menarik perhatian Anda. Taktik rekayasa sosial ini bertujuan untuk mendorong Anda berinteraksi dengan email tersebut dengan segera. 
<img width="1005" height="155" alt="image" src="https://github.com/user-attachments/assets/ffb735f2-885f-47c4-8f77-dc554db1cd44" />
Sekarang mari kita lihat isi badan email tersebut.

Teks Isi Email (Gambar 1) :
<img width="640" height="685" alt="image" src="https://github.com/user-attachments/assets/50823ae2-207a-449c-9614-55b219eee56e" />
Bagian kedua dari teks isi email yang sama (Gambar 2) :
<img width="494" height="588" alt="image" src="https://github.com/user-attachments/assets/33501a32-bb46-4019-b146-41272c2ac537" />
Isi email melengkapi informasi pengirim dan baris subjek. Email tersebut dirancang agar tampak seperti email resmi dari PayPal. 

Tidak ada lampiran yang terkait dengan email ini. Satu-satunya elemen interaktif dalam email ini adalah tombol/tautan  Batalkan pesanan .

Mari kita selidiki lebih lanjut dengan meninjau kode sumber HTML mentah untuk email tersebut...

Tautan Email :
<img width="783" height="185" alt="image" src="https://github.com/user-attachments/assets/b00bfd4c-8be1-4c76-9796-2ec29e6f3930" />

# Lacak paket Anda
Contoh email ini akan menyoroti teknik-teknik berikut:

Alamat email palsu
Pelacakan piksel
Manipulasi tautan
Berikut beberapa pengamatan singkat tentang contoh email ini:

Email tersebut dirancang sedemikian rupa sehingga tampak seolah-olah dikirim dari pusat distribusi email tertentu. 
Subjek email tersebut menambah kesan pura-pura dengan menyertakan 'nomor pelacakan'. 
Tautan di isi email sesuai dengan baris subjek. 
Catatan : Dalam contoh email ini, Yahoo memblokir gambar agar tidak dimuat secara otomatis. Ada yang bisa menebak alasannya? 

Biasanya kita dapat mengarahkan kursor ke tautan untuk melihat ke mana tautan tersebut mengarah, tetapi dalam contoh ini, teknik tersebut tidak akan berhasil karena Yahoo menonaktifkan tautan di email. Kita dapat melihat kode sumber mentah email tersebut dan mengetahuinya. 

Tautan Email :
<img width="1014" height="376" alt="image" src="https://github.com/user-attachments/assets/f15e8a68-933a-4a25-aeb7-af195ccc2f67" />

Di sini kita melihat sebuah file gambar, dan secara eksplisit disebut Tracking.png . Pelacak ini mengirimkan informasi kembali ke server pengirim spam. 

Ada banyak alasan mengapa pengirim spam menyematkan piksel pelacak (gambar yang sangat kecil) ke dalam email spam mereka. Untuk membaca lebih lanjut tentang konsep ini, lihat postingan di The Verge di sini . 

Sekarang kita bisa memahami mengapa Yahoo secara otomatis memblokir gambar dalam email ini. Banyak penyedia email melakukan hal yang sama. 

Kembali ke hyperlink, tautan tersebut mengarah ke domain yang tampak mencurigakan. Satu-satunya pusat distribusi yang dapat dikaitkan dengan domain ini adalah malware, tetapi analisis lebih lanjut adalah satu-satunya cara untuk memastikan hal itu secara pasti. 

Jawablah pertanyaan-pertanyaan di bawah ini.
Apa domain akar untuk setiap URL? Hilangkan efek fang pada URL tersebut. 
devret[.]xyz

# Pilih penyedia email Anda untuk melihat dokumen.
Contoh email ini akan menyoroti teknik-teknik berikut:
Urgensi
HTML untuk meniru merek yang sah
Manipulasi tautan
Pengumpulan kredensial
Tata bahasa yang buruk dan/atau kesalahan ketik
Mari kita perhatikan lebih detail...

<img width="910" height="584" alt="image" src="https://github.com/user-attachments/assets/fe3c8a9e-52c5-4fd7-83f3-992681eec2de" />
Berikut beberapa pengamatan singkat tentang contoh email ini:

Email tersebut dikirim pada hari Kamis, 15 Juli 2021.  
Email ini menyiratkan rasa urgensi. Perhatikan bahwa tautan untuk mengunduh dokumen faks akan kedaluwarsa pada hari yang sama.
Ada tindakan yang perlu dilakukan. Dalam hal ini, tombol untuk mengunduh faks. 
<img width="911" height="588" alt="image" src="https://github.com/user-attachments/assets/c9b29141-4c8d-4ca7-81e3-92d43e20cb53" />
Gambar di atas menunjukkan korban dialihkan ke halaman yang dibuat agar terlihat seperti OneDrive. Perhatikan bahwa URL tersebut tidak ada hubungannya dengan Microsoft. 

Terdapat dua tautan lagi yang dapat diinteraksi oleh korban. Korban harus mengklik salah satu tombol untuk mendapatkan dokumen faks yang akan segera kedaluwarsa. 

<img width="992" height="573" alt="image" src="https://github.com/user-attachments/assets/75cee52e-d07b-4814-83b8-7f0cd038e3fd" />
Korban diarahkan ke situs lain lagi. Situs ini dirancang agar menyerupai Adobe. Sekali lagi, perhatikan URL-nya. Tampaknya tidak terkait dengan Adobe.

Selain itu, perhatikan judul halaman di tab tersebut. Judulnya adalah "Share Point Online", yang merupakan produk Microsoft. Terdapat beberapa kesalahan tata bahasa juga. 

Korban memiliki pilihan untuk masuk menggunakan penyedia email pilihan mereka. 
Korban kami memilih untuk masuk menggunakan Outlook karena, sesuai petunjuk, " Untuk membaca dokumen, silakan masuk dengan kredensial email yang valid yang digunakan untuk mengirimkan file ini. "; email tersebut kemudian dilihat di Outlook. 
<img width="901" height="573" alt="image" src="https://github.com/user-attachments/assets/52b9f3d6-742d-4508-98ed-5623f65fd60c" />
Dalam contoh ini, kita dapat melihat bahwa kredensial palsu telah dimasukkan, tetapi bahkan jika korban memasukkan kredensial yang valid, pesan kesalahannya akan tetap sama. Skenario ini terjadi karena korban sebenarnya tidak melakukan autentikasi ke penyedia email. Sebaliknya, kredensial yang dimasukkan sekarang berada di server pelaku kejahatan. Tujuan pelaku kejahatan untuk mendapatkan kredensial telah tercapai. 

Terakhir, perhatikan lagi kesalahan tata bahasa. Dengan semua kerja keras yang mereka curahkan, seharusnya mereka juga melakukan pengecekan ejaan. 

Contoh email ini diperoleh dari Any Run. Jika Anda ingin berinteraksi dengan email dan melihat analisis lengkapnya, silakan lihat tautan di bawah ini.

Analisis :  https://app.any.run/tasks/12dcbc54-be0f-4250-b6c1-94d548816e5c/#
Jawablah pertanyaan-pertanyaan di bawah ini.
Contoh email ini menggunakan nama beberapa perusahaan besar, produk mereka, dan logo seperti OneDrive dan Adobe. Nama perusahaan lain apa yang digunakan dalam email phishing ini?
Citrix

# Harap perbarui detail pembayaran Anda.
Contoh email ini akan menyoroti teknik-teknik berikut:

Alamat email palsu
Urgensi
HTML untuk meniru merek yang sah
Tata bahasa yang buruk dan/atau kesalahan ketik
Lampiran
Berikut beberapa pengamatan singkat tentang contoh email ini:

Email ini dibuat agar tampak seolah-olah berasal dari Netflix Billing, tetapi alamat pengirimnya adalah z99@musacombi.online. 
Di sinilah letak urgensinya. Akun tersebut telah ditangguhkan, jadi korban harus bertindak cepat. 
Nuansa urgensi lebih terasa dalam isi email tersebut. 

<img width="1003" height="291" alt="image" src="https://github.com/user-attachments/assets/bfb867d5-4618-4786-b99e-f72a14d5ff27" />
Selain itu, perhatikan juga berbagai kesalahan ejaan kata Netflix. Saya tidak yakin apa tujuan dari hal itu. 

Biasanya, Anda akan melihat teknik ini terkait dengan typosquatting , tetapi bukan itu kasusnya di sini. 



Oke, berikut inti dari email ini. Rupanya, korban perlu membuka lampiran (PDF) untuk memperbarui akun Netflix mereka. 
<img width="850" height="675" alt="image" src="https://github.com/user-attachments/assets/8b3b53f0-7fc0-4987-b91d-d1d6c2f94fc1" />
Perhatikan nomor telepon 'Netflix'. Sekilas, itu adalah nomor telepon yang tidak biasa untuk dikirimkan kepada korban yang berbasis di AS. 
<img width="980" height="550" alt="image" src="https://github.com/user-attachments/assets/20325355-7a66-43bf-8076-3961bd66d35b" />

Lampiran tersebut berisi tautan tersemat berjudul 'Perbarui Akun Pembayaran'. 

Kita akan membahas lampiran email ini secara lebih detail di ruang Phishing Emails 3 mendatang. 

Jawablah pertanyaan-pertanyaan di bawah ini.
Apa yang harus dilakukan pengguna jika menerima email atau pesan teks mencurigakan yang mengaku berasal dari Netflix?
forward the message to phishing@netflix.com

# Pembelian Anda baru-baru ini
Contoh email ini akan menyoroti teknik-teknik berikut:

Alamat email palsu
Penerima di-BCC
Urgensi
Tata bahasa yang buruk dan/atau kesalahan ketik
Lampiran
Berikut beberapa pengamatan singkat tentang contoh email ini:

Email ini dibuat agar tampak seolah-olah berasal dari Dukungan Apple, tetapi alamat pengirimnya adalah gibberish@sumpremed.com. 
Email ini tidak dikirim langsung ke kotak masuk korban, melainkan dikirim melalui BCC ( Blind Carbon Copy ). Alamat email penerima terlihat seperti email palsu lain yang dibuat agar tampak seperti alamat email Apple yang sah. 
Di sinilah letak urgensinya. Tindakan diperlukan demi korban. 
<img width="1006" height="153" alt="image" src="https://github.com/user-attachments/assets/4ee3bd30-73e8-4c10-ad0d-3b2b9eb398ea" />



Terdapat beberapa kesalahan ketik yang cukup mencolok pada alamat email pengirim dan penerima:  donoreply dan  payment .

Email ini tidak memiliki isi email sama sekali. Email ini benar-benar kosong. Email ini hanya berisi lampiran. 

<img width="334" height="161" alt="image" src="https://github.com/user-attachments/assets/fc44e98d-f7e5-4670-9755-a20e5c0b0741" />


Ekstensi file ini mungkin belum Anda kenal. File .DOT adalah file templat tata letak halaman yang terkait dengan Microsoft Word. 
<img width="979" height="552" alt="image" src="https://github.com/user-attachments/assets/81a9e926-6f6d-4c85-87f4-535e8a43a9d5" />



Gambar di atas menunjukkan isi lampiran tersebut. Anda dapat melihat bahwa file tersebut berisi gambar berukuran besar yang menyerupai tanda terima App Store. 

Perhatikan bahwa tautan tersebut berisi kata kunci tertentu yang terkait dengan Apple: aplikasi dan iOS . 

Jawablah pertanyaan-pertanyaan di bawah ini.

Apa arti BCC?
Blind Carbon Copy

Teknik apa yang digunakan untuk membujuk korban agar tidak mengabaikan email tersebut dan bertindak cepat?

Urgency

# Pemberitahuan Pengiriman Kurir DHL Express
Contoh email ini akan menyoroti teknik-teknik berikut:

Alamat email palsu
HTML untuk meniru merek yang sah
Lampiran
Berikut beberapa pengamatan singkat tentang contoh email ini:

Alamat email pengirim tidak sesuai dengan perusahaan yang dipalsukan, yang dalam kasus ini adalah DHL.
Judul email tersebut memberikan kesan bahwa ada paket yang akan dikirim DHL untuk Anda.
Kode HTML di dalam isi email dirancang agar terlihat seperti dikirim dari DHL. 
<img width="971" height="290" alt="image" src="https://github.com/user-attachments/assets/b7c130ae-5e85-472c-9287-b112aed2f449" />

Jika dilihat dari kode sumber email tersebut, tautan untuk melihat email sebagai halaman web tidak berisi URL tujuan yang sebenarnya. 
<img width="607" height="44" alt="image" src="https://github.com/user-attachments/assets/cf88957b-2030-49ef-b5d2-288590633d78" />
<img width="553" height="194" alt="image" src="https://github.com/user-attachments/assets/22df030b-84fa-42f0-9645-e6b04a13389f" />
Satu-satunya elemen yang dapat diinteraksi oleh korban dalam email ini adalah lampiran email, yang dalam hal ini berupa dokumen Excel. 
<img width="796" height="698" alt="image" src="https://github.com/user-attachments/assets/b9a322f7-36c1-4c50-9b8f-5e74f6beb52f" />

Gambar di bawah ini menunjukkan isi lampiran tersebut.
 <img width="980" height="551" alt="image" src="https://github.com/user-attachments/assets/b9a5fb62-4f30-4092-b03c-5c704b81fdb0" />
Lampiran tersebut menjalankan muatan yang menimbulkan kesalahan. 
<img width="978" height="551" alt="image" src="https://github.com/user-attachments/assets/6cf34c9e-03b8-476f-b525-14f9ed05da21" />

Kita akan membahas lampiran email ini secara lebih detail di ruang Phishing Emails 3 mendatang. 

Jawablah pertanyaan-pertanyaan di bawah ini.
Apa nama file yang dapat dieksekusi yang coba dijalankan oleh lampiran Excel tersebut?
regasms.exe

# Kesimpulan
Di ruangan ini, kami melihat berbagai contoh phishing . 

Beberapa contoh menggunakan teknik yang serupa, sementara yang lain memperkenalkan taktik baru yang dapat Anda lihat dan pelajari. 

Memahami cara mendeteksi email phishing membutuhkan pelatihan kesadaran.

Kunjungi sumber daya di bawah ini untuk mempelajari tanda-tanda lain yang perlu diwaspadai dalam email  phishing .

Sumber Daya Tambahan:

https://www.knowbe4.com/ phishing
https://www.itgovernance.co.uk/blog/5-ways-to-detect-a-phishing-email​​
https://cheapsslsecurity.com/blog/10-phishing-email-examples-you-need-to-see/​​
https://phishingquiz.withgoogle.com
Ruangan selanjutnya dalam modul ini: Email Phishing 3




