# Asterisk
Cara menginstall Asterisk
<h2>Pengertian Asterisk</h2>
<p>Asterisk adalah implementasi perangkat lunak dari private branch exchange. Sehubungan dengan antarmuka perangkat keras telepon dan aplikasi jaringan yang sesuai, Asterisk digunakan untuk membuat dan mengontrol panggilan telepon antara titik akhir telekomunikasi, seperti perangkat telepon biasa, tujuan dijaringan telepon umum (PSTN), dan perangkat atau layanan pada protokol suara melalui internet.</p>
<h2>Cara menginstall Asterisk</h3>
<p><code>apt-get install asterisk -y</code></p>
<h4>Konfigurasi Asterisk sip.conf</h4>
<p><code>nano /etc/asterisk/sip.conf</code></p>
<p>Langkah selanjutnya tambahkan rules baru di baris paling bawah</p>
<p>> <a href="https://github.com/sikunyuk64/asterisk/blob/main/sip.conf">Rules</a></p>
<h4>Konfigurasi Asterisk extensions.conf</h4>
<p><code>nano /etc/asterisk/extensions.conf</code></p>
<p>Langkah selanjutnya tambahkan rules baru di baris paling bawah</p>
<p>> <a href="https://github.com/sikunyuk64/asterisk/blob/main/extensions.conf">Rules</a></p>
<h4>Restart Asterisk</h4>
<p><code>systemctl restart asterisk</code></p>
