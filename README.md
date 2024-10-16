# Reinforcement Learning TicTacToe
# Kelompok 6:
1. Mira Juwita Ali (G1A021056)
2. Syakira Az Zahra (G1A021057)
3. Triana Kesumaningrum (G1A021068)

# Permainan TicTacToe
<p align="center">
  <img src="https://mindfulenglish.net/wp-content/uploads/2023/01/tic-tac-toe.jpeg" alt="Deskripsi Gambar" width="400">
</p>

Tic-tac-toe ( Bahasa Inggris Amerika ), noughts and crosses ( Bahasa Inggris Persemakmuran ), atau Xs and Os ( Bahasa Inggris Kanada atau Irlandia ) adalah permainan kertas dan pensil untuk dua pemain yang bergiliran menandai ruang dalam kotak tiga-kali-tiga dengan X atau O. Pemain yang berhasil menempatkan tiga tanda mereka dalam baris horizontal, vertikal, atau diagonal adalah pemenangnya. Ini adalah permainan yang diselesaikan , dengan undian yang dipaksakan dengan asumsi permainan terbaik dari kedua pemain. Tic-tac-toe dimainkan pada kotak berukuran tiga kali tiga oleh dua pemain, yang secara bergantian menempatkan tanda X dan O di salah satu dari sembilan ruang di kotak tersebut.

Repositori ini menjelaskan tentang melatih agen AI untuk bermain Tic-tac-toe dengan reinforcement learning menggunakan algoritma SARSA dan Q-learning RL. Pengguna dapat melatih agen dengan cara bermain melawan agen tersebut atau menggunakan agen pengajar otomatis.

Agen Q-learning dan SARSA diimplementasikan di agent.py. Masing-masing dari dua agen pembelajaran mewarisi dari kelas pembelajar induk. Perbedaan utama antara keduanya adalah fungsi pembaruan nilai Q mereka.

Agen Guru diimplementasikan di teacher.py. Guru mengetahui kebijakan optimal untuk setiap status yang disajikan. Namun, agen ini hanya mengambil pilihan optimal dengan probabilitas yang ditetapkan.

Di game.py, kelas permainan utama ditemukan. Kelas Permainan menyimpan status setiap instans permainan tertentu, dan berisi sebagian besar fungsionalitas permainan utama. Loop permainan utama dapat ditemukan di fungsi kelas playGame().

# Menajalankan program
Untuk memainkan permainan anda dapat menjalankan kode:
python play.py -a q (Q-learner)
python play.py -a s (Sarsa-learner)

Kode ini akan menjalankan permainan dan memungkinkan anda untuk melatih agen secara manual dengan bermain melawan agen itu sendiri.

# Referensi
https://github.com/rfeinman/tictactoe-reinforcement-learning.git
https://github.com/brianspiering/rl-course/tree/main/06_q_learning
