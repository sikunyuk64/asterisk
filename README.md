<img src="https://github.com/sikunyuk64/asterisk/blob/main/Asterisk_Logo-700x438.png" width="350" heiht="150">
<h2 dir="auto">
  <strong>Asterisk</strong>
</h2>
<p>Asterisk adalah implementasi perangkat lunak dari private branch exchange. Sehubungan dengan antarmuka perangkat keras telepon dan aplikasi jaringan yang sesuai, Asterisk digunakan untuk membuat dan mengontrol panggilan telepon antara titik akhir telekomunikasi, seperti perangkat telepon biasa, tujuan dijaringan telepon umum (PSTN), dan perangkat atau layanan pada protokol suara melalui internet.</p>
<h2 dir="auto">
  <strong>Cara menginstall Asterisk</strong>
</h2>
<p>1. Untuk menginstall Asterisk ketikan <code>apt-get install asterisk -y</code> tunggu beberapa saat sampai proses instalasi selesai.</p>
<p>2. Selanjutnya konfigurasikan file sip.conf dengan mengetikan <code>nano /etc/asterisk/sip.conf</code>.</p>
<p>3. Langkah selanjutnya tambahkan rules baru di baris paling bawah.</p>
<p>> <a href="https://github.com/sikunyuk64/asterisk/blob/main/sip.conf">Rules</a></p>
<p>4. Selanjutnya konfigurasikan file extensions.conf dengan mengetikan <code>nano /etc/asterisk/extensions.conf</code>.</p>
<p>5. Langkah selanjutnya tambahkan rules baru di baris paling bawah.</p>
<p>> <a href="https://github.com/sikunyuk64/asterisk/blob/main/extensions.conf">Rules</a></p>
<p>6. Setelah proses instalasi dan konfigurasi selesai, restart Asterisk dengan mengetikan <code>systemctl restart asterisk</code>.</p>
