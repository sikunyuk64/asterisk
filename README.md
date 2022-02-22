# Asterisk
Cara menginstall Asterisk
<h2>Pengertian Asterisk</h2>
<p>Asterisk adalah implementasi perangkat lunak dari private branch exchange. Sehubungan dengan antarmuka perangkat keras telepon dan aplikasi jaringan yang sesuai, Asterisk digunakan untuk membuat dan mengontrol panggilan telepon antara titik akhir telekomunikasi, seperti perangkat telepon biasa, tujuan dijaringan telepon umum (PSTN), dan perangkat atau layanan pada protokol suara melalui internet.</p>
<h2>Cara menginstall Asterisk</h3>
<p>1. Untuk menginstall Asterisk ketikan <code>apt-get install asterisk -y</code> tunggu beberapa saat sampai proses instalasi selesai.</p>
<p>2. Selanjutnya Konfigurasi file sip.conf ketikan <code>nano /etc/asterisk/sip.conf</code><p>
<p>Langkah selanjutnya tambahkan rules baru di baris paling bawah</p>
<p>> <a href="https://github.com/sikunyuk64/asterisk/blob/main/sip.conf">Rules</a></p>
<p>Konfigurasi Asterisk extensions.conf</p>
<p><code>nano /etc/asterisk/extensions.conf</code></p>
<p>Langkah selanjutnya tambahkan rules baru di baris paling bawah</p>
<p>> <a href="https://github.com/sikunyuk64/asterisk/blob/main/extensions.conf">Rules</a></p>
<p>Restart Asterisk</p>
<p><code>systemctl restart asterisk</code></p>
