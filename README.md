<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Perpustakaan Tri Anita Saragih</title>
    <style> 
        body {
            font-family: Arial, sans-serif;
            margin: 20px;
        }
        h1 {
            color: #4CAF50;
        }
        table {
            width: 100%;
            border-collapse: collapse;
            margin-top: 20px;
        }
        th, td {
            border: 1px solid #ddd;
            padding: 8px;
            text-align: left;
        }
        th {
            background-color: #4CAF50;
            color: white;
        }
        tr:nth-child(even) {
            background-color: #f2f2f2;
        }
    </style>
</head>
<body>
    <h1>Selamat Datang Di Perpustakaan Tri Anita Saragih (222201027)!</h1>
    <p>Perkenalkan, nama saya Tri Anita Saragih, NIM: 222201027, Program Studi D3 Perpustakaan, Mata Kuliah Pemrograman Web. Ini merupakan homepage perpustakaan pertama saya.</p>

    <hr/>

    <h2>Berikut ini gambar dari Perpustakaan Untan</h2>
    <img src="https://asset-2.tstatic.net/tribunpontianakwiki/foto/bank/images/perpustakaan-universitas-tanjungpura-pontianak.jpg" alt="Perpustakaan Untan" />

    <h2>Video Profil Perpustakaan Untan</h2>
    <iframe width="560" height="315" src="https://www.youtube.com/embed/Iqhk0z3SIug" frameborder="0" allowfullscreen></iframe>
    <audio controls>
        <source src="" type="audio/mpeg">
        Browsermu tidak mendukung tag audio, upgrade dong!
    </audio>

    <h2>Formulir Perpustakaan Untan</h2>
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

    <h2>Daftar Bahan Buku</h2>
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

    <h2>Formulir Pemesanan Buku</h2>
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

    <h2>Formulir Perpanjangan Peminjaman Buku</h2>
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
</body>
</html>
