<!doctype html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport"
        content="width=device-width, user-scalable=no, initial-scale=1.0, maximum-scale=1.0, minimum-scale=1.0">
  <meta http-equiv="X-UA-Compatible" content="ie=edge">
  <title>Bookshelf Apps</title>
  <link rel="preconnect" href="https://fonts.gstatic.com">
  <link href="https://fonts.googleapis.com/css2?family=Open+Sans:wght@300;400;600;700;800&display=swap"
        rel="stylesheet">
  <link rel="stylesheet" href="style.css">
</head>
<body>
<header class="head_bar">
  <h1 class="head_bar__title">Bookshelf Apps</h1>
</header>
<main>
  <section class="search_section">
    <h2>Cari Buku (Opsional)</h2>
    <form id="searchBook">
      <label for="searchBookTitle">Judul</label>
      <input id="searchBookTitle" type="text">
      <button id="searchSubmit" type="submit">Cari</button>
    </form>
  </section>

  <section class="input_section">
    <h2>Masukkan Buku Baru</h2>
    <form id="inputBook">
      <div class="input">
        <label for="inputBookTitle">Judul</label>
        <input id="inputBookTitle" type="text" required>
      </div>
      <div class="input">
        <label for="inputBookAuthor">Penulis</label>
        <input id="inputBookAuthor" type="text" required>
      </div>
      <div class="input">
        <label for="inputBookYear">Tahun</label>
        <input id="inputBookYear" type="number" required>
      </div>
      <div class="input_inline">
        <label for="inputBookIsComplete">Selesai dibaca</label>
        <input id="inputBookIsComplete" type="checkbox">
      </div>
      <button id="bookSubmit" type="submit">Masukkan Buku ke rak <span>Belum selesai dibaca</span></button>
    </form>
  </section>
  
  
  
  <section class="book_shelf">
    <h2>Belum selesai dibaca</h2>
    
    <div id="incompleteBookshelfList" class="book_list">
<!--    <article class="book_item">-->
<!--      <h3>Book Title</h3>-->
<!--      <p>Penulis: John Doe</p>-->
<!--      <p>Tahun: 2002</p>-->
<!--        -->
<!--      <div class="action">-->
<!--      <button class="green">Selesai dibaca</button>-->
<!--      <button class="red">Hapus buku</button>-->
<!--      </div>-->
<!--   </article>-->
    </div>
  </section>
  
  <section class="book_shelf">
    <h2>Selesai dibaca</h2>
    
    <div id="completeBookshelfList" class="book_list">
<!--      <article class="book_item">-->
<!--        <h3>Book Title</h3>-->
<!--        <p>Penulis: John Doe</p>-->
<!--        <p>Tahun: 2002</p>-->
<!--        -->
<!--        <div class="action">-->
<!--          <button class="green">Belum selesai di Baca</button>-->
<!--          <button class="red">Hapus buku</button>-->
<!--        </div>-->
<!--      </article>-->
    </div>
  </section>
</main>

<script src="script.js" type="text/javascript"></script>

</body>
</html>
