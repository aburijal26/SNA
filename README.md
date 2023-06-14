# Analisis Degree Centrality dan Tweet Terkait dalam Jaringan Retweet (Final Project SNA)
Ini adalah repository yang berisi kode Python untuk melakukan analisis degree centrality pada jaringan retweet dan menampilkan tweet terkait untuk pengguna dengan degree centrality tertinggi. Proyek ini merupakan bagian dari tugas akhir dalam mata kuliah Social Network Analysis (SNA).

# Deskripsi
Kode ini memanfaatkan library NetworkX untuk membangun graf jaringan retweet dari dataset yang diberikan. Kemudian, dilakukan perhitungan degree centrality untuk setiap simpul (pengguna) dalam jaringan retweet. Hasilnya adalah top 5 pengguna dengan degree centrality tertinggi.

Selanjutnya, kode ini mencari tweet terkait untuk setiap pengguna dengan degree centrality tertinggi berdasarkan dataset yang diberikan. Jika tweet tersedia, tweet tersebut ditambahkan ke dalam hasil dataset. Jika tidak tersedia, ditambahkan nilai "No tweet available".
