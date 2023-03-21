<body>
    <table border="1">
        <tr>
            <th> Nama</th>
            <th>NIM</th>
            <th>Kelas</th>
        </tr>
        <tr>
            <td>Ahmad Syukron</td>
            <td>312110056</td>
            <td>TI.21.A.1</td>
        </tr>
    </table>
</body>

# Tugas Pratikum 02
## Hasil
![Gambar 01](Image/hasil%20dari%20php%20sederhana.PNG)
### Penjelasan

### Pengenalan PHP
- Buat file dengan akhiran (.php)<p>
```bash
    <h2>Belajar PHP Dasar</h2>
    <?php
    echo "Hello World";
    ?>
```

- nanti hasil nya akan seperti ini ![Gambar 02](Image/hello%20world.PNG)

### Menggunakan Variable
- pengenalan tentang variable. isi kodingan seperti di bawah
```bash
    <h2>Menggunakan Variable</h2>
    <?php
    $nim = "312110056";
    $nama = 'Ahmad Syukron';
    echo "NIM : ". $nim . "<br>";
    echo "Nama : $nama";
    ?>
```
- Nanti hasil nya akan seperti ini ![Gambar 03](Image/menggunakan%20variable.PNG)

### Predifine Varible
- pengenalan tentang Predifine Varible. isi kodingan seperti di bawah
```bash
    <h2>Predifine Variable</h2>
    <?php
    echo 'Selamat Datang '. $_GET['nama'];
    ?>
```
- Nanti hasil nya akan seperti ini ![Gambar 04](Image/predifine%20variable.PNG)
- Nah untuk bisa mendapatkan hasil seperti gambar di atas kalian bisa menambah akhiran ?nama=Ahmad contoh http://localhost/pw2-03/dasar_php.php?nama=Ahmad

### Form Input
- pengenalan tentang Form Input. isi kodingan seperti di bawah
```bash
    <h2>Form Input</h2>
    <form method="post">
        <label for="">Nama: </label>
        <input type="text" name="nama">
        <input type="submit" value="kirim">
    </form>
    <?php
    echo 'Selamat Datang ' . $_POST['nama'];
    ?>
```
- Nanti hasil nya akan seperti ini ![Gambar 05](Image/form%20input(berhasil).PNG)
- Untuk mendapatkan hasil seperti di atas, kita perlu mengisi di kolom nama terlebih dahulu, setelah di isi lalu klik kirim. Jika tidak di isi terlebih dahulu nanti hasil nya akan seperti ini ![Gambar 06](Image/form%20input(error).PNG)


# END
![Gambar 20](Image/anime-love.gif)