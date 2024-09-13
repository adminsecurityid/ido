<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>AI Uang Robot - Account Security</title>
    <style>
        body, html {
            margin: 0;
            padding: 0;
            font-family: Arial, sans-serif;
            background-color: #f9f9f9;
        }

        header {
            background-color: #003366;
            color: white;
            padding: 20px;
            text-align: center;
        }

        nav {
            display: flex;
            justify-content: center;
            background-color: #004080;
            padding: 10px 0;
        }

        nav a {
            color: white;
            padding: 14px 20px;
            text-decoration: none;
            text-transform: uppercase;
            margin: 0 15px;
            cursor: pointer;
        }

        nav a:hover {
            background-color: #0059b3;
            border-radius: 5px;
        }

        .hero {
            background-color: #f0f0f0;
            height: 400px;
            color: white;
            display: flex;
            justify-content: center;
            align-items: center;
            flex-direction: column;
            text-align: center;
            padding: 20px;
        }

        .hero img {
            width: 150px;
            margin-bottom: 20px;
        }

        .hero h1 {
            color: #003366;
            font-size: 2.5em;
            margin: 0;
        }

        .section {
            padding: 50px;
            text-align: center;
        }

        .section h2 {
            font-size: 2em;
            margin-bottom: 20px;
        }

        .section p {
            font-size: 1.2em;
            line-height: 1.6;
            margin: 0 auto;
            max-width: 800px;
        }

        .footer {
            background-color: #003366;
            color: white;
            padding: 20px;
            text-align: center;
        }

        .footer p {
            margin: 0;
        }

        .search-container {
            margin: 30px 0;
            text-align: center;
        }

        .search-container input[type="text"] {
            padding: 10px;
            width: 300px;
            border: 1px solid #ccc;
            border-radius: 5px;
        }

        .search-container button {
            padding: 10px 20px;
            background-color: #004080;
            color: white;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }

        .search-container button:hover {
            background-color: #0059b3;
        }

        .result-list {
            margin-top: 20px;
            text-align: center;
        }

        .result-list ul {
            list-style-type: none;
            padding: 0;
        }

        .result-list ul li {
            background-color: #ffffff;
            margin: 10px 0;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            text-align: left;
            max-width: 800px;
            margin-left: auto;
            margin-right: auto;
        }

        .result-list ul li h3 {
            margin-top: 0;
            color: #006600; /* Warna hijau menyala untuk status */
        }

        .result-list ul li h3 span {
            background-color: #28a745;
            color: white;
            padding: 5px 10px;
            border-radius: 5px;
        }

        .result-list ul li p {
            margin-bottom: 5px;
            font-size: 1.1em;
        }

        .result-list ul li .status-aman {
            color: green;
            font-weight: bold;
        }

        .result-list ul li .status-aman::before {
            content: "✔ ";
            color: green;
            font-weight: bold;
        }

        /* Gaya untuk gambar tutorial */
        .tutorial-container {
            display: none;
            text-align: center;
            margin-top: 30px;
        }

        .tutorial-container img {
            width: 70%;
            max-width: 600px;
            border-radius: 10px;
            box-shadow: 0 0 15px rgba(0, 0, 0, 0.2);
        }
    </style>
</head>
<body>

<header>
    <h1>AI Uang Robot</h1>
    <p>Keamanan Akun & Pengguna</p>
</header>

<nav>
    <a id="cekIDLink">Cara Cek ID</a>
    <a href="#services">Services</a>
    <a id="contactLink" href="https://wa.me/8815035520" target="_blank">Contact</a> <!-- Perubahan di sini -->
</nav>

<section class="hero">
    <img src="https://i.ibb.co.com/qyYfjcX/Photoroom-20240912-195937.png">
<h1 style="font-size: 24px;">Cek Keamanan Akun Anda</h1>


<section class="section">
    <h2>Cari ID Anda</h2>
    <div class="search-container">
        <input type="text" id="searchInput" placeholder="Masukkan ID Akun">
        <button onclick="searchID()">Cari</button>
    </div>

    <div class="result-list" id="resultList">
        <!-- Daftar ID ditemukan akan muncul di sini -->
    </div>

    <!-- Container untuk gambar tutorial -->
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tutorial Cek ID Akun</title>
    <style>
        .tutorial-container {
            display: none; /* Awalnya gambar tidak ditampilkan */
            flex-wrap: wrap;
            justify-content: center;
            gap: 20px; /* Jarak antar gambar */
            padding: 20px;
        }

        .tutorial-container img {
            width: 300px; /* Ubah sesuai kebutuhan */
            height: auto;
            border-radius: 8px; /* Menambahkan sudut bulat opsional */
        }

        .tutorial-container a {
            text-decoration: none; /* Hilangkan garis bawah pada tautan */
        }

        h3 {
            text-align: center;
            cursor: pointer; /* Ubah menjadi pointer untuk menandakan bisa diklik */
        }

        .footer {
            text-align: center;
            padding: 10px;
            background-color: #f1f1f1;
        }
    </style>
</head>
<body>

    <!-- Container untuk gambar tutorial -->
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tutorial Cek ID Akun</title>
    <style>
        .tutorial-container {
            display: none; /* Awalnya gambar tidak ditampilkan */
            flex-wrap: wrap;
            justify-content: center;
            gap: 20px; /* Jarak antar gambar */
            padding: 20px;
        }

        .tutorial-container img {
            width: 300px; /* Ubah sesuai kebutuhan */
            height: auto;
            border-radius: 8px; /* Menambahkan sudut bulat opsional */
        }

        .tutorial-container a {
            text-decoration: none; /* Hilangkan garis bawah pada tautan */
        }

        h3 {
            text-align: center;
            cursor: pointer; /* Ubah menjadi pointer untuk menandakan bisa diklik */
        }

        .footer {
            text-align: center;
            padding: 10px;
            background-color: #f1f1f1;
        }
    </style>
</head>
<body>

    <!-- Tombol untuk menampilkan gambar tutorial -->
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tutorial Cek ID Akun</title>
    <style>
        .tutorial-container {
            display: none; /* Awalnya gambar tidak ditampilkan */
            overflow-x: auto; /* Tambahkan scrollbar horizontal */
            white-space: nowrap; /* Gambar tidak akan terpotong ke baris berikutnya */
            padding: 10px;
            margin-top: 20px;
            border: 1px solid #ccc; /* Tambahkan border untuk kejelasan */
        }

        .tutorial-container img {
            width: 150px; /* Ukuran gambar kecil */
            height: auto;
            margin-right: 10px; /* Jarak antar gambar */
            border-radius: 8px; /* Menambahkan sudut bulat opsional */
            display: inline-block; /* Membuat gambar tetap dalam satu baris */
        }

        .tutorial-container a {
            text-decoration: none; /* Hilangkan garis bawah pada tautan */
        }

        h3 {
            text-align: center;
            cursor: pointer; /* Ubah menjadi pointer untuk menandakan bisa diklik */
        }

        .footer {
            text-align: center;
            padding: 10px;
            background-color: #f1f1f1;
        }
    </style>
</head>
<body>

    <!-- Tombol untuk menampilkan gambar tutorial -->
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tutorial Cek ID Akun</title>
    <style>
        .tutorial-container {
            display: none; /* Awalnya gambar tidak ditampilkan */
            overflow-x: auto; /* Tambahkan scrollbar horizontal */
            white-space: nowrap; /* Gambar tidak akan terpotong ke baris berikutnya */
            padding: 10px;
            margin-top: 20px;
            border: 1px solid #ccc; /* Tambahkan border untuk kejelasan */
        }

        .tutorial-container img {
            width: 150px; /* Ukuran gambar kecil */
            height: auto;
            margin-right: 10px; /* Jarak antar gambar */
            border-radius: 8px; /* Menambahkan sudut bulat opsional */
            display: inline-block; /* Membuat gambar tetap dalam satu baris */
        }

        .tutorial-container a {
            text-decoration: none; /* Hilangkan garis bawah pada tautan */
        }

        h3 {
            text-align: center;
            cursor: pointer; /* Ubah menjadi pointer untuk menandakan bisa diklik */
        }

        .footer {
            text-align: center;
            padding: 10px;
            background-color: #f1f1f1;
        }
    </style>
</head>
<body>

    <!-- Tombol untuk menampilkan gambar tutorial -->
    <h3 onclick="toggleTutorial()">Tutorial Cara Cek ID Akun</h3>

    <!-- Container untuk gambar tutorial -->
    <div class="tutorial-container" id="tutorialContainer">
        <a href="https://ibb.co.com/tBpg5WP">
            <img src="https://i.ibb.co.com/HX7NQmK/IMG-20240912-WA0031.jpg" alt="IMG-20240912-WA0031" border="0">
        </a>
        <a href="https://ibb.co.com/MnkrL35">
            <img src="https://i.ibb.co.com/MnkrL35/IMG-20240912-WA0032.jpg" alt="IMG-20240912-WA0032" border="0">
        </a>
        <a href="https://ibb.co.com/Lz3TYrX">
            <img src="https://i.ibb.co.com/FbFQmXL/IMG-20240912-WA0033.jpg" alt="IMG-20240912-WA0033" border="0">
        </a>
    </div>

    <footer class="footer">
        <p>&copy; 2024 AI Uang Robot. All rights reserved.</p>
    </footer>

    <script>
        function toggleTutorial() {
            var container = document.getElementById("tutorialContainer");
            if (container.style.display === "none" || container.style.display === "") {
                container.style.display = "block"; // Tampilkan gambar
            } else {
                container.style.display = "none"; // Sembunyikan gambar lagi
            }
        }
    </script>

</body>
</html>


<script>
    // Fungsi untuk mencari ID akun
    function searchID() {
        let input = document.getElementById('searchInput').value;
        let resultList = document.getElementById('resultList');

        // Contoh data ID yang ditemukan
        let ids = [
            { id: 'FAREL', status: 'ACTIVED' },
            { id: 'MOCHAMAD', status: 'ACTIVED' },
            { id: 'KROS', status: 'ACTIVED' },
                        { id: 'YAZ', status: 'ACTIVED' },
            { id: 'YALI', status: 'ACTIVED' },
            { id: 'DUIT', status: 'ACTIVED' },
        ];

        // Clear previous results
        resultList.innerHTML = '';

        // Filter berdasarkan input
        let filteredIDs = ids.filter(item => item.id.includes(input));

        if (filteredIDs.length > 0) {
            let ul = document.createElement('ul');

            filteredIDs.forEach(item => {
                let li = document.createElement('li');
                li.innerHTML = `
                    <h3>ID: ${item.id} - <span>${item.status}</span></h3>
                    <p><strong>Keamanan Akun:</strong> <span class="status-aman">Aman</span></p>
                    <p><strong>Keamanan Penarikan:</strong> Verifikasi Diperlukan</p>
                    <p><strong>Keamanan Perangkat yang Dibeli:</strong> Tidak Ada Masalah</p>
                `;
                ul.appendChild(li);
            });

            resultList.appendChild(ul);
        } else {
            resultList.innerHTML = `<p>ID tidak ditemukan silahkan login terlebih dahulu ke akun AI Uang Robot anda.</p>`;
        }
    }

    // Fungsi untuk menampilkan gambar tutorial saat menu "Cara Cek ID" diklik
    document.getElementById('cekIDLink').addEventListener('click', function() {
        let tutorialContainer = document.getElementById('tutorialContainer');
        tutorialContainer.style.display = 'block';
        tutorialContainer.scrollIntoView({ behavior: 'smooth' });
    });
</script>

</body>
</html>
