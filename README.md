<h2 dir="auto">
  <strong>DAFTAR ISI</strong>
</h2>
<p><strong>><a href="#"> Pendahuluan</a></strong></p>
<p><strong>><a href="https://github.com/sikunyuk64/asterisk#--asterisk"> Pengertian Asterisk</a></strong></p>
<p><strong>><a href="https://github.com/sikunyuk64/asterisk#--sejarah-asterisk"> Sejarah Asterisk</a></strong></p>
<p><strong>><a href="https://github.com/sikunyuk64/asterisk#--kelebihan-asterisk"> Kelebihan Asterisk</a></strong></p>
<p><strong>><a href="https://github.com/sikunyuk64/asterisk#--kekurangan-asterisk"> Kekurangan Asterisk</a></strong></p>
<p><strong>><a href="https://github.com/sikunyuk64/asterisk#--cara-menginstall-asterisk"> Cara menginstal Asterisk</a></strong></p>
<h2 dir="auto">
  <strong>Asterisk <a href="https://github.com/sikunyuk64/asterisk#readme">Home</a></strong>
</h2>
<p dir="auto">
<p>Asterisk adalah software IP PBX untuk membuat sistem layanan komunikasi telepon melalui internet atau biasa disebut VoIP (Voice over Internet Protocol). Asterisk adalah software Open Source yang berjalan di linux. Asterisk juga memungkinkan komunikasi antar pengguna telepon regular dengan telepon berbasis sip (sip phones). Asterisk juga sudah dilengkapi banyak fitur baik standard yaitu seperti: Caller ID, Voice Mail, Conference, dan lain-lain.</p>
</p>
<h2 dir="auto">
  <strong>Sejarah Asterisk</strong>
</h2>
<p>Sejarah Perkembangan teknologi VoIP dimulai dari penemuan telepon pada tahun 1876 oleh Alexander Graham Bell. Kemudian dikembangkan lagi teknologi PSTN ( Public Switched Telephone Network ) yang sudah berkembang sampai sekarang. Beberapa tahun kemudian mulai berkembang teknologi yang baru. Pembuatan Personal Computer (PC) secara massal, system komunikasi telepon selular dan terakhir system berdasarkan jaringan internet yang memberikan layanan e-mail, Chat dan lain-lain.Teknologi VoIP diperkenalkan setelah internet mulai berkembang sekitar tahun 1995. Pada mulanya kemampuan mengirimkan suara melalui internet hanya merupakan eksperimen dari beberapa orang atau perusahaan kecil. Ini dimulai dengan perusahaan seperti Vocaltech dan kemudian pada akhirnya diikuti oleh Microsoft dengan program Netmeeting-nya. Pada saat itu jaringan komputer internet masih sangat lambat. Di rumah-rumah (khususnya di Amerika) masih digunakan dial up dengan kecepatan 36,6 Kbyte. Backbone Internet pun masih kecil. Aplikasi yang bersifat menghabiskan bandwith, seperti misalnya suara atau video, masih sangat terbatas penggunaannya di pusat penelitian yang memiliki bandwidth besar.</p>
<h2 dir="auto">
  <strong>Kelebihan Asterisk</strong>
</h2>
<p><strong>></strong> Dapat jalan dibanyak platform OS</p>
<p><strong>></strong> Dapat melakukan koneksi pada semua standar yang berbasis telepon</p>
<p><strong>></strong> menggunakan hardware yang harganya terjangkau</p>
<h2 dir="auto">
  <strong>Kekurangan Asterisk</strong>
</h2>
<p>sangat rentang terhadap aktivitas intruder</p>
<h2 dir="auto">
  <strong>Cara menginstall Asterisk</strong>
</h2>
<p><strong>Kesatu:</strong> untuk menginstall Asterisk ketikan perintah yang ada dibawah ini.</p>
<div class="snippet-clipboard-content position-relative overflow-auto"><pre><code>apt-get install asterisk -y
</code></pre><div class="zeroclipboard-container position-absolute right-0 top-0">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn js-clipboard-copy m-2 p-0 tooltipped-no-delay" data-copy-feedback="Copied!" data-tooltip-direction="w" value="apt-get install astersik -y" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon m-2">
    <path fill-rule="evenodd" d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 010 1.5h-1.5a.25.25 0 00-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 00.25-.25v-1.5a.75.75 0 011.5 0v1.5A1.75 1.75 0 019.25 16h-7.5A1.75 1.75 0 010 14.25v-7.5z"></path><path fill-rule="evenodd" d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0114.25 11h-7.5A1.75 1.75 0 015 9.25v-7.5zm1.75-.25a.25.25 0 00-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 00.25-.25v-7.5a.25.25 0 00-.25-.25h-7.5z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none m-2">
    <path fill-rule="evenodd" d="M13.78 4.22a.75.75 0 010 1.06l-7.25 7.25a.75.75 0 01-1.06 0L2.22 9.28a.75.75 0 011.06-1.06L6 10.94l6.72-6.72a.75.75 0 011.06 0z"></path>
</svg>
    </clipboard-copy>
  </div></div>
 <p>Tunggu beberapa saat sampai proses installasi selesai.</p>
<p><strong>Kedua:</strong> selanjutnya konfigurasikan file sip.conf dengan mengetikan perintah dibawah ini.</p>
<div class="snippet-clipboard-content position-relative overflow-auto"><pre><code>nano /etc/asterisk/sip.conf
</code></pre><div class="zeroclipboard-container position-absolute right-0 top-0">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn js-clipboard-copy m-2 p-0 tooltipped-no-delay" data-copy-feedback="Copied!" data-tooltip-direction="w" value="nano /etc/asterisk/sip.conf" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon m-2">
    <path fill-rule="evenodd" d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 010 1.5h-1.5a.25.25 0 00-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 00.25-.25v-1.5a.75.75 0 011.5 0v1.5A1.75 1.75 0 019.25 16h-7.5A1.75 1.75 0 010 14.25v-7.5z"></path><path fill-rule="evenodd" d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0114.25 11h-7.5A1.75 1.75 0 015 9.25v-7.5zm1.75-.25a.25.25 0 00-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 00.25-.25v-7.5a.25.25 0 00-.25-.25h-7.5z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none m-2">
    <path fill-rule="evenodd" d="M13.78 4.22a.75.75 0 010 1.06l-7.25 7.25a.75.75 0 01-1.06 0L2.22 9.28a.75.75 0 011.06-1.06L6 10.94l6.72-6.72a.75.75 0 011.06 0z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p><strong>Ketiga:</strong> kemudian tambahkan <a href="https://github.com/sikunyuk64/asterisk/blob/main/sip.conf">rules</a> baru di baris paling bawah, kemudian kalian save konfigurasinya dengan menekan tombol <code>ctrl+x</code> kemudian tekan <code>y</code> lalu <code>Enter</code>.</p>
<p><strong>Keempat:</strong> selanjutnya konfigurasikan file extensions.conf dengan mengetikan perintah dibawah ini.</p>
<div class="snippet-clipboard-content position-relative overflow-auto"><pre><code>nano /etc/asterisk/extensions.conf
</code></pre><div class="zeroclipboard-container position-absolute right-0 top-0">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn js-clipboard-copy m-2 p-0 tooltipped-no-delay" data-copy-feedback="Copied!" data-tooltip-direction="w" value="nano /etc/asterisk/extensions.conf" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon m-2">
    <path fill-rule="evenodd" d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 010 1.5h-1.5a.25.25 0 00-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 00.25-.25v-1.5a.75.75 0 011.5 0v1.5A1.75 1.75 0 019.25 16h-7.5A1.75 1.75 0 010 14.25v-7.5z"></path><path fill-rule="evenodd" d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0114.25 11h-7.5A1.75 1.75 0 015 9.25v-7.5zm1.75-.25a.25.25 0 00-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 00.25-.25v-7.5a.25.25 0 00-.25-.25h-7.5z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none m-2">
    <path fill-rule="evenodd" d="M13.78 4.22a.75.75 0 010 1.06l-7.25 7.25a.75.75 0 01-1.06 0L2.22 9.28a.75.75 0 011.06-1.06L6 10.94l6.72-6.72a.75.75 0 011.06 0z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p><strong>Kelima:</strong> kemudian tambahkan <a href="https://github.com/sikunyuk64/asterisk/blob/main/extensions.conf">rules</a> baru di baris paling bawah, kemudian kalian save konfigurasinya dengan menekan tombol <code>ctrl+x</code> kemudian tekan <code>y</code> lalu <code>Enter</code>.</p>
<p><strong>Keenam:</strong> setelah proses instalasi dan konfigurasi selesai, restart Asterisk dengan mengetikan perintah dibawah ini.</p>
<div class="snippet-clipboard-content position-relative overflow-auto"><pre><code>systemctl restart asterisk
</code></pre><div class="zeroclipboard-container position-absolute right-0 top-0">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn js-clipboard-copy m-2 p-0 tooltipped-no-delay" data-copy-feedback="Copied!" data-tooltip-direction="w" value="systemctl restart asterisk" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon m-2">
    <path fill-rule="evenodd" d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 010 1.5h-1.5a.25.25 0 00-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 00.25-.25v-1.5a.75.75 0 011.5 0v1.5A1.75 1.75 0 019.25 16h-7.5A1.75 1.75 0 010 14.25v-7.5z"></path><path fill-rule="evenodd" d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0114.25 11h-7.5A1.75 1.75 0 015 9.25v-7.5zm1.75-.25a.25.25 0 00-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 00.25-.25v-7.5a.25.25 0 00-.25-.25h-7.5z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none m-2">
    <path fill-rule="evenodd" d="M13.78 4.22a.75.75 0 010 1.06l-7.25 7.25a.75.75 0 01-1.06 0L2.22 9.28a.75.75 0 011.06-1.06L6 10.94l6.72-6.72a.75.75 0 011.06 0z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p><strong>Ketujuh:</strong> nah sampai disini tahapan proses instalasi dan konfigurasi Asterisknya sudah selesai.</p>
<br>
<p><strong>Semoga bermanfaat</strong>👍🏻</p>



