# ineunuraisyah
membuat ucapan idul fitri untuk sang kakak
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Kartu Ucapan Idul Fitri</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <div class="bintik" style="top: 100px; left: 50px;"></div>
  <div class="bintik" style="top: 200px; left: 150px;"></div>
  <div class="bintik" style="top: 300px; left: 250px;"></div>
  <div class="bintik" style="top: 400px; left: 350px;"></div>
  <div class="bintik" style="top: 500px; left: 450px;"></div>
  <div class="moonstar"></div>
  <div class="moonstar"></div>
    <div class="pesan">
      <h2>Hallo tetehQU</h2>
    </div>

    <div clas="container">
    <div class="card">
    <div class="slide" id="slide1">
      <img src="sticker 1.jpg" alt="sticker">
      <h1>Selamat Hari Raya Idul fitri teteh &#128591;</h1>
      <p>Di hari yang Fitri ini Mari kita saling bermaaf-maafan</p>
      <p>Maaf jika selama ini adik tingkat mu suka membuat kesalahan yang namanya manusia tidak pernah luput dari yang namanya kesalahan</p>
      <P>Taqabalallahu Mina Wamingkum Siyamana siyamakum</P>
      <p>Minal Aidzin Walfaidzin Mohon maaf lahir dan batin</p>
      <button onclick="prevSlide()"Sebelumnya></button>
    </div>
    <div class="slide" id="slide2">
      <img src="gambar 3.jpg" alt="sticker THR" class="gambar-thr">
      <h1>THR dari hati yang tulus untuk teteh yang paling terbaik</h1>
      <p>Semoga lebaran kali ini membawa keberkahan dan bahagiaan bagi kita semua.</p>
      <p>Eeitttsss THR nya nanti ya dikosan wkwkwk</p>
      <p>Jangan diliat dari nilai nya ya tapi liatlah dari ketusannya</p>
      <button onclick="prevSlide()"Sebelumnya></button>
    </div>
    <div class="slide" id="slide3">
      <img src="Aisyah teh raya1 .jpg" alt="Aisyah-teh raya">
      <h1>Teteh, Terimakasih ya</h1>
      <p>teteh selama ini udah jadi temen nonton aisyah, temen nabung aisyah, temen berjuangnya aisyah, sampe menjadi temen umroh aisyah nanti</p>
      <p>Walaupun terkadang suka membuat teteh kesel kecewa dan marah</p>
      <P>Maafin segala kesalahan aisyah yang dulu sekarang dan masa yang akan datang ya teh</P>
      <p>Dari sekian banyak nya kating yang deket sama aisyah, tapi teteh adalah kating yang terbaik aisyah.</p>
      <p>Sehat selalu teteh doa dan harapanku selalu menyertaimu</p>
      <p>#Aisyah Si anak Teknik</p>
      <button onclick="prevSlide()"selanjutnya></button>
    </div>
    </div>
  </div>
  <script src="script.js"></script>
  <script>
    // Ambil elemen pesan
    const pesanElement = document.querySelector('.pesan');

    //Tahbahkan kelas 'show' setelah 1 detik
    setTimeout(() => {
       pesanElement.classList.add('show');
        }, 1000);
  </script>
</body>
</html>
