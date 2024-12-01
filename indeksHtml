<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Perpustakaan Tri Anita Saragih</title>
    <style>
        :root {
            --primary-color: #2c3e50;
            --secondary-color: #3498db;
            --background-color: #f0f2f5;
            --text-color: #333;
            --border-color: #ddd;
            --box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            margin: 0;
            padding: 20px;
            background-color: var(--background-color);
            color: var(--text-color);
            line-height: 1.6;
        }

        .container {
            max-width: 1200px;
            margin: 0 auto;
        }

        /* Box styling untuk semua section */
        .content-box {
            background-color: white;
            border-radius: 10px;
            box-shadow: var(--box-shadow);
            padding: 25px;
            margin-bottom: 30px;
        }

        h1, h2 {
            color: var(--primary-color);
            margin-top: 0;
            margin-bottom: 20px;
            border-bottom: 2px solid var(--secondary-color);
            padding-bottom: 10px;
        }

        /* Image dan Video container */
        .media-box {
            background-color: white;
            border-radius: 10px;
            padding: 15px;
            margin-bottom: 20px;
            box-shadow: var(--box-shadow);
        }

        img, iframe {
            max-width: 100%;
            height: auto;
            border-radius: 8px;
            display: block;
            margin: 0 auto;
        }

        /* Table styling */
        .table-container {
            background-color: white;
            border-radius: 10px;
            padding: 20px;
            margin-bottom: 30px;
            box-shadow: var(--box-shadow);
            overflow-x: auto;
        }

        table {
            width: 100%;
            border-collapse: collapse;
            margin: 0;
        }

        th, td {
            padding: 12px 15px;
            text-align: left;
            border: 1px solid var(--border-color);
        }

        th {
            background-color: var(--primary-color);
            color: white;
            font-weight: 600;
        }

        tr:nth-child(even) {
            background-color: #f8f9fa;
        }

        tr:hover {
            background-color: #f5f5f5;
        }

        /* Form styling */
        .form-container {
            background-color: white;
            border-radius: 10px;
            padding: 25px;
            margin-bottom: 30px;
            box-shadow: var(--box-shadow);
        }

        form table {
            margin: 0;
        }

        input[type="text"],
        input[type="email"],
        input[type="date"],
        textarea {
            width: 100%;
            padding: 8px 12px;
            border: 1px solid var(--border-color);
            border-radius: 4px;
            font-size: 14px;
        }

        input[type="submit"] {
            background-color: var(--secondary-color);
            color: white;
            padding: 12px 24px;
            border: none;
            border-radius: 4px;
            cursor: pointer;
            font-size: 16px;
            transition: background-color 0.3s;
            display: block;
            margin: 20px auto 0;
        }

        input[type="submit"]:hover {
            background-color: #2980b9;
        }

        /* Audio player styling */
        .audio-container {
            background-color: white;
            border-radius: 10px;
            padding: 15px;
            margin-bottom: 20px;
            box-shadow: var(--box-shadow);
        }

        audio {
            width: 100%;
        }

        @media (max-width: 768px) {
            body {
                padding: 10px;
            }
            
            .content-box,
            .media-box,
            .form-container,
            .table-container {
                padding: 15px;
            }
        }

        /* Tambahkan CSS untuk layout 3 kolom */
        .row {
            display: flex;
            gap: 20px;
            margin-bottom: 30px;
        }

        .column {
            flex: 1;
            background-color: white;
            border-radius: 10px;
            padding: 20px;
            box-shadow: var(--box-shadow);
        }

        /* Styling untuk menu dropdown */
        .dropdown {
            position: relative;
            display: inline-block;
            width: 100%;
        }

        .dropdown-btn {
            background-color: var(--primary-color);
            color: white;
            padding: 12px;
            border: none;
            border-radius: 4px;
            cursor: pointer;
            width: 100%;
            text-align: left;
        }

        .dropdown-content {
            display: none;
            position: absolute;
            background-color: white;
            min-width: 100%;
            box-shadow: var(--box-shadow);
            z-index: 1;
            border-radius: 4px;
        }

        .dropdown-content a {
            color: var(--text-color);
            padding: 12px 16px;
            text-decoration: none;
            display: block;
        }

        .dropdown-content a:hover {
            background-color: var(--background-color);
        }

        .dropdown:hover .dropdown-content {
            display: block;
        }

        /* Tambahkan CSS baru */
        .column {
            transition: transform 0.3s ease;
        }

        .column:hover {
            transform: translateY(-5px);
        }

        .welcome-text {
            font-size: 1.8em;
            color: var(--primary-color);
            text-align: center;
            margin-bottom: 20px;
        }

        .highlight {
            color: var(--secondary-color);
            font-weight: bold;
        }

        .stat-number {
            font-size: 2em;
            color: var(--secondary-color);
            text-align: center;
            margin: 10px 0;
        }

        .book-card {
            padding: 10px;
            border-left: 4px solid var(--secondary-color);
            margin-bottom: 10px;
            background-color: #f8f9fa;
            border-radius: 0 4px 4px 0;
        }

        .status-badge {
            padding: 4px 8px;
            border-radius: 12px;
            font-size: 0.8em;
            font-weight: bold;
        }

        .status-tersedia {
            background-color: #28a745;
            color: white;
        }

        .status-dipinjam {
            background-color: #dc3545;
            color: white;
        }

        .status-dipesan {
            background-color: #ffc107;
            color: black;
        }

        .table {
            width: 100%;
            border-collapse: collapse;
            margin-bottom: 1rem;
            background-color: white;
        }

        .table-bordered {
            border: 1px solid var(--border-color);
        }

        .table th,
        .table td {
            padding: 12px;
            vertical-align: middle;
            border: 1px solid var(--border-color);
            text-align: left;
        }

        .table thead th {
            background-color: var(--primary-color);
            color: white;
            font-weight: 600;
            border-bottom: 2px solid var(--border-color);
        }

        .table tbody tr:nth-child(even) {
            background-color: #f8f9fa;
        }

        .table tbody tr:hover {
            background-color: #f2f2f2;
        }

        /* Mempertahankan styling untuk status badge */
        .status-badge {
            padding: 4px 8px;
            border-radius: 12px;
            font-size: 0.8em;
            font-weight: bold;
            display: inline-block;
        }

        .status-tersedia {
            background-color: #28a745;
            color: white;
        }

        .status-dipinjam {
            background-color: #dc3545;
            color: white;
        }

        .status-dipesan {
            background-color: #ffc107;
            color: black;
        }

        .modul-text {
            text-align: center;
            font-size: 1.2em;
            font-weight: bold;
            color: var(--primary-color);
            padding: 15px 0;
            margin: 20px 0;
            border-top: 2px solid var(--secondary-color);
            border-bottom: 2px solid var(--secondary-color);
            text-transform: uppercase;
            letter-spacing: 2px;
            cursor: pointer;
            user-select: none;
        }

        .modul-dropdown {
            position: relative;
            display: inline-block;
            width: 100%;
        }

        .modul-content {
            display: none;
            width: 100%;
            background-color: white;
            border-radius: 10px;
            box-shadow: var(--box-shadow);
            margin-top: 10px;
        }

        .modul-content.active {
            display: block;
        }

        .media-section {
            max-width: 800px;
            margin: 40px auto;
        }

        .media-box {
            background-color: white;
            border-radius: 15px;
            padding: 20px;
            margin-bottom: 30px;
            box-shadow: var(--box-shadow);
            overflow: hidden;
        }

        .media-box img {
            width: 100%;
            height: auto;
            border-radius: 10px;
            transition: transform 0.3s ease;
        }

        .media-box img:hover {
            transform: scale(1.02);
        }

        .media-box iframe {
            width: 100%;
            aspect-ratio: 16/9;
            border-radius: 10px;
            border: none;
        }

        .audio-container {
            background-color: white;
            border-radius: 15px;
            padding: 20px;
            margin-bottom: 30px;
            box-shadow: var(--box-shadow);
        }

        .audio-container audio {
            width: 100%;
            height: 40px;
            margin: 0 auto;
            display: block;
        }

        .media-title {
            color: var(--primary-color);
            font-size: 1.5em;
            margin-bottom: 20px;
            padding-bottom: 10px;
            border-bottom: 2px solid var(--secondary-color);
            text-align: center;
        }
    </style>
</head>
<body>
        <h1>Selamat Datang Di Perpustakaan Tri Anita Saragih (222201027)</h1>
        <p>Perkenalkan, nama saya Tri Anita Saragih, NIM: 222201027, Program Studi D3 Perpustakaan, Mata Kuliah Pemrograman Web. Ini merupakan homepage perpustakaan pertama saya.</p>

        <hr/>

        <div class="media-section">
            <h2 class="media-title">Perpustakaan Untan</h2>
            <div class="media-box">
                <img src="https://asset-2.tstatic.net/tribunpontianakwiki/foto/bank/images/perpustakaan-universitas-tanjungpura-pontianak.jpg" 
                     alt="Perpustakaan Untan" />
            </div>

            <h2 class="media-title">Video Profil Perpustakaan</h2>
            <div class="media-box">
                <iframe src="https://www.youtube.com/embed/Iqhk0z3SIug" 
                        allowfullscreen></iframe>
            </div>

            <h2 class="media-title">Audio Player</h2>
            <div class="audio-container">
                <audio controls>
                    <source src="Gotap ni Rohakki.mp3" type="audio/mpeg">
                    Browsermu tidak mendukung tag audio, upgrade dong!
                </audio>
            </div>
        </div>

        <h2>Formulir Perpustakaan Untan</h2>
        <div class="form-container">
            <form action="#" method="post">
                <table>
                    <tr>
                        <th>Nama</th>
                        <td><input type="text" name="nama" required></td>
                    </tr>
                    <tr>
                        <th>NIM</th>
                        <td><input type="text" name="nim" required></td>
                    </tr>
                    <tr>
                        <th>Alamat</th>
                        <td><textarea name="alamat" rows="3" required></textarea></td>
                    </tr>
                    <tr>
                        <th>Jenis Kelamin</th>
                        <td>
                            <input type="radio" name="jenis_kelamin" value="Laki-laki" required> Laki-laki
                            <input type="radio" name="jenis_kelamin" value="Perempuan" required> Perempuan
                        </td>
                    </tr>
                    <tr>
                        <th>Email</th>
                        <td><input type="email" name="email" required></td>
                    </tr>
                    <tr>
                        <th>No HP</th>
                        <td><input type="text" name="no_hp" required></td>
                    </tr>
                    <tr>
                        <th>Tempat Lahir</th>
                        <td><input type="text" name="tempat_lahir" required></td>
                    </tr>
                    <tr>
                        <th>Tanggal Lahir</th>
                        <td><input type="date" name="tanggal_lahir" required></td>
                    </tr>
                </table>
                <br>
                <input type="submit" value="Submit">
            </form>
        </div>

        <h2>Daftar Bahan Buku</h2>
        <div class="table-container">
            <table>
                <thead>
                    <tr>
                        <th>No</th>
                        <th>Judul Buku</th>
                        <th>Pengarang</th>
                        <th>Penerbit</th>
                        <th>Tahun Terbit</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td>1</td>
                        <td>Pemrograman Web Dasar</td>
                        <td>Andi Saputra</td>
                        <td>Media Press</td>
                        <td>2020</td>
                    </tr>
                    <tr>
                        <td>2</td>
                        <td>Pengenalan HTML dan CSS</td>
                        <td>Budi Santoso</td>
                        <td>Ilmu Komputer</td>
                        <td>2021</td>
                    </tr>
                    <tr>
                        <td>3</td>
                        <td>JavaScript untuk Pemula</td>
                        <td>Siti Rahmawati</td>
                        <td>Edu Books</td>
                        <td>2019</td>
                    </tr>
                    <tr>
                        <td>4</td>
                        <td>Database dan SQL</td>
                        <td>Joko Widodo</td>
                        <td>Tech Press</td>
                        <td>2022</td>
                    </tr>
                </tbody>
            </table>
        </div>

        <h2>Formulir Pemesanan Buku</h2>
        <div class="form-container">
            <form action="#" method="post">
                <table>
                    <tr>
                        <th>Nama</th>
                        <td><input type="text" name="nama" required></td>
                    </tr>
                    <tr>
                        <th>Nomor Anggota Perpustakaan</th>
                        <td><input type="text" name="nomor_anggota" required></td>
                    </tr>
                    <tr>
                        <th>Tanggal Pemesanan</th>
                        <td><input type="date" name="tanggal_pemesanan" required></td>
                    </tr>
                    <tr>
                        <th>Jenis Kelamin</th>
                        <td>
                            <input type="radio" name="jenis_kelamin" value="Laki-laki" required> Laki-laki
                            <input type="radio" name="jenis_kelamin" value="Perempuan" required> Perempuan
                        </td>
                    </tr>
                    <tr>
                        <th>Email</th>
                        <td><input type="email" name="email" required></td>
                    </tr>
                    <tr>
                        <th>No HP</th>
                        <td><input type="text" name="no_hp" required></td>
                    </tr>
                    <tr>
                        <th>Penulis Buku</th>
                        <td><input type="text" name="penulis_buku" required></td>
                    </tr>
                    <tr>
                        <th>No ISBN</th>
                        <td><input type="text" name="no_isbn" required></td>
                    </tr>
                    <tr>
                        <th>Judul Buku Yang Dipesan</th>
                        <td><input type="text" name="judul_buku" required></td>
                    </tr>
                </table>
                <br>
                <input type="submit" value="Submit">
            </form>
        </div>

        <h2>Formulir Perpanjangan Peminjaman Buku</h2>
        <div class="form-container">
            <form action="#" method="post">
                <table>
                    <tr>
                        <th>Nama</th>
                        <td><input type="text" name="nama" required></td>
                    </tr>
                    <tr>
                        <th>Nomor Anggota Perpustakaan</th>
                        <td><input type="text" name="nomor_anggota" required></td>
                    </tr>
                    <tr>
                        <th>Tanggal Peminjaman</th>
                        <td><input type="date" name="tanggal_peminjaman" required></td>
                    </tr>
                    <tr>
                        <th>Email</th>
                        <td><input type="email" name="email" required></td>
                    </tr>
                    <tr>
                        <th>No Telepon</th>
                        <td><input type="text" name="no_telepon" required></td>
                    </tr>
                    <tr>
                        <th>No ISBN</th>
                        <td><input type="text" name="no_isbn" required></td>
                    </tr>
                    <tr>
                        <th>Tanggal Perpanjangan Buku</th>
                        <td><input type="date" name="tanggal_perpanjangan" required></td>
                    </tr>
                </table>
                <br>
                <input type="submit" value="Submit">
            </form>
        </div>
    </div>
    <div class="modul-dropdown">
        <p class="modul-text" onclick="toggleModul()">Modul 5 ▼</p>
        <div class="modul-content" id="modulContent">
            <div class="container">
                <div class="row">
                    <!-- Kolom 1: Statistik Perpustakaan -->
                    <div class="column">
                        <h2>SELAMAT DATANG DI PERPUSTAKAAN SUKA BACA <br> Statistik Perpustakaan</h2>
                        <div class="stat-number">5,000+</div>
                        <p style="text-align: center">Koleksi Buku</p>
                        
                        <div class="stat-number">1,200</div>
                        <p style="text-align: center">Anggota Aktif</p>
                        
                        <div class="stat-number">150</div>
                        <p style="text-align: center">Pengunjung Hari Ini</p>
                        
                        <div class="dropdown" style="margin-top: 20px;">
                            <button class="dropdown-btn">Menu Layanan ▼</button>
                            <div class="dropdown-content">
                                <a href="#"><i class="fas fa-book"></i> Peminjaman Buku</a>
                                <a href="#"><i class="fas fa-clock"></i> Perpanjangan</a>
                                <a href="#"><i class="fas fa-users"></i> Keanggotaan</a>
                                <a href="#"><i class="fas fa-calendar"></i> Event</a>
                                <a href="#"><i class="fas fa-question-circle"></i> Bantuan</a>
                            </div>
                        </div>
                    </div>

                    <!-- Kolom 2: Tabel Buku -->
                    <div class="column">
                        <h2>Daftar Buku Populer</h2>
                        <table class="table table-bordered">
                            <thead>
                                <tr>
                                    <th>No</th>
                                    <th>Judul Buku</th>
                                    <th>Pengarang</th>
                                    <th>Status</th>
                                    <th>Rating</th>
                                </tr>
                            </thead>
                            <tbody>
                                <tr>
                                    <td>1</td>
                                    <td>Filosofi Teras</td>
                                    <td>Henry Manampiring</td>
                                    <td><span class="status-badge status-tersedia">Tersedia</span></td>
                                    <td>⭐⭐⭐⭐⭐</td>
                                </tr>
                                <tr>
                                    <td>2</td>
                                    <td>Laut Bercerita</td>
                                    <td>Leila S. Chudori</td>
                                    <td><span class="status-badge status-dipinjam">Dipinjam</span></td>
                                    <td>⭐⭐⭐⭐½</td>
                                </tr>
                                <tr>
                                    <td>3</td>
                                    <td>Pulang-Pergi</td>
                                    <td>Tere Liye</td>
                                    <td><span class="status-badge status-dipesan">Dipesan</span></td>
                                    <td>⭐⭐⭐⭐</td>
                                </tr>
                                <tr>
                                    <td>4</td>
                                    <td>Atomic Habits</td>
                                    <td>James Clear</td>
                                    <td><span class="status-badge status-tersedia">Tersedia</span></td>
                                    <td>⭐⭐⭐⭐⭐</td>
                                </tr>
                                <tr>
                                    <td>5</td>
                                    <td>Rich Dad Poor Dad</td>
                                    <td>Robert Kiyosaki</td>
                                    <td><span class="status-badge status-dipinjam">Dipinjam</span></td>
                                    <td>⭐⭐⭐⭐</td>
                                </tr>
                            </tbody>
                        </table>
                    </div>

                    <!-- Kolom 3: Pencarian & Filter -->
                    <div class="column">
                        <h2>Pencarian Lanjutan</h2>
                        <form action="#" method="post">
                            <div style="margin-bottom: 15px;">
                                <label for="kategori">Genre:</label>
                                <select name="kategori" id="kategori" style="width: 100%; padding: 8px; margin-top: 5px; border: 1px solid var(--border-color); border-radius: 4px;">
                                    <option value="">Semua Genre</option>
                                    <option value="novel">Novel</option>
                                    <option value="biografi">Biografi</option>
                                    <option value="sejarah">Sejarah</option>
                                    <option value="sains">Sains & Teknologi</option>
                                    <option value="bisnis">Bisnis & Ekonomi</option>
                                </select>
                            </div>
                            
                            <div style="margin-bottom: 15px;">
                                <label for="bahasa">Bahasa:</label>
                                <select name="bahasa" id="bahasa" style="width: 100%; padding: 8px; margin-top: 5px; border: 1px solid var(--border-color); border-radius: 4px;">
                                    <option value="">Semua Bahasa</option>
                                    <option value="indonesia">Indonesia</option>
                                    <option value="inggris">Inggris</option>
                                    <option value="arab">Arab</option>
                                    <option value="mandarin">Mandarin</option>
                                </select>
                            </div>
                            
                            <div style="margin-bottom: 15px;">
                                <label for="cari">Kata Kunci:</label>
                                <input type="text" id="cari" name="cari" 
                                       placeholder="Judul, Pengarang, atau ISBN..." 
                                       style="width: 100%; padding: 8px; margin-top: 5px; border: 1px solid var(--border-color); border-radius: 4px;">
                            </div>

                            <div style="margin-bottom: 15px;">
                                <label>Status Buku:</label>
                                <div style="margin-top: 5px;">
                                    <input type="checkbox" id="tersedia" name="status[]" value="tersedia">
                                    <label for="tersedia">Tersedia</label>
                                    
                                    <input type="checkbox" id="dipinjam" name="status[]" value="dipinjam" style="margin-left: 10px;">
                                    <label for="dipinjam">Dipinjam</label>
                                </div>
                            </div>

                            <button type="submit" style="background-color: var(--secondary-color); color: white; padding: 12px 20px; border: none; border-radius: 4px; cursor: pointer; width: 100%; font-weight: bold; text-transform: uppercase; letter-spacing: 1px;">
                                <i class="fas fa-search"></i> Cari Buku
                            </button>
                        </form>
                    </div>
                </div>
            </div>
        </div>
    </div>

    <script>
        function toggleModul() {
            const content = document.getElementById('modulContent');
            content.classList.toggle('active');
        }
    </script>
</body>
</html>
