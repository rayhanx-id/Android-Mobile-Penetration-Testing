<h1>Toturial Install Frida in Android</h1>
<ul>
  <li>Cek apakah android telah terhubung, dengan cara <code>adb devices</code></li>
  <li>Masuk ke dalam android mengunalan shell <code>adb shell</code></li>
  <li>Pindahkan file, Firda-Server yang telah di extrak ke Android <code>adb push /data/local/tmp/frida-server</code></li>
  <li>Dalam adb shell <code>chmod +x frida-server</code></li>
  <li>Install Firda in terminal linux<code>pip3 install frida frida-tools objection</code></li>
  <li><code></code></li>
  
  <li><code>frida -U -f com.packageaplikasi.com -l fridascript</code></li>
</ul>
