# 🎶 Spotify ID Project
🎶What Behind Top Spotify Songs In Indonesia?

Hallo semua!
Kalau kalian mau rilis lagu dan jadi Top 50 Spotify atau pengen iseng aja cari tau karakteristik lagu Top 50 Spotify region Indonesia tuh gimana, monggo bisa disimak, ya!

Project ini merupakan bagian dari Final Project saya di dibimbing.id, dan harapannya karena data ini terus diperbaharui, sehingga dapat menjadi project "bangun tumbuh" bagi saya.

Baik, project ini sederhananya bercerita tentang karakteristik lagu macam apa yang ada di Top 50 Spotify regional Indonesia dari kurun waktu 18 Oktober 2023 - 12 Mei 2025?

Datasetnya sendiri saya dapat dari kaggle disini 👉 https://lnkd.in/gKdEVSaf

Ya, dataset awalnya untuk 73 negara, kemudian saya lakukan filtering untuk mengambil data Indonesia saja. Kemudian, dari banyak pilihan karakteristik musik yang ada, saya memilih 5 karakteristik yang ingin saya liat, karakteristik ini ditentukan dengan melihat korelasi antara target (atau variabel dependen, atau Y) dengan fitur (atau karakteristik, atau variabel independen, atau X).

Tentu saja, saya memilih target popularity untuk menjawab pertanyaan saya di awal. Serta, fitur speechiness, acousticness, loudness, tempo, dan valence (detail deskripsi fitur dapat dibaca pada deskripsi dataset).

Saya jalankan dengan model XG-Boost karena technically lebih "bagus" dibanding Linear Regression atau SVR dilihat dari MAE (Mean Absolute Error), MSE (Mean Squared Error), dan R².

Hasil yang saya dapatkan menunjukan bahwa Top 50 Spotify Songs di Indonesia itu punya karakteristik yang kuat pada acousticness dan valence-nya. Sederhananya lagu-lagu yang kuat dengan instrumen alat musiknya dan bernuansa positif. Supaya mudah bayangin lagu yang seperti apa, contohnya adalah:

1️⃣ TULUS - Interaksi

2️⃣ Sal Priadi - Gala Bunga Matahari

3️⃣ Yung Kai - Blue

4️⃣ MALIQ & D'Essentials - Aduh

Nah, sekarang udah kejawab karakteristiknya apa aja, saya buatkan juga playlist dari kedua fitur tadi di Spotify. Semoga informasi ini bermanfaat!

Ohiya, untuk kalian yang mau coba ngulik lebih lanjut datasetnya, saya juga berikan beberapa evaluasi dan saran untuk project Spotify pertama saya di slide terakhir ya! Terima kasih sudah mau membaca sampai akhir 🙌
