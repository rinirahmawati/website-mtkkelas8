<!doctype html>
<html lang="en">
<head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>Kelas 8 - Pola Bilangan</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH" crossorigin="anonymous">
    <style>
        body {
            background: linear-gradient(to bottom right, #ffffff, #e0f7fa);
            font-family: Arial, sans-serif;
        }
        h1 {
            color: #0f6460;
            margin-top: 20px;
        }
        h2 {
            color: #00796b;
            margin-top: 20px;
        }
        h3 {
            color: #004d40;
        }
        .example {
            background-color: #f0f8ff;
            border-left: 5px solid #00796b;
            padding: 10px;
            margin: 20px 0;
        }
        .footer {
            text-align: center;
            margin-top: 30px;
            color: #555;
            font-size: 1.1em;
        }
        .card {
            margin-bottom: 20px;
            border: none;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0,0,0,0.1);
        }
        .btn-custom {
            background-color: #45b867;
            color: white;
        }
        .video-frame {
            width: 100%;
            height: 400px; /* Ubah tinggi sesuai kebutuhan */
            border: none;
        }
        .img-fluid {
            max-height: 300px;
        }
    </style>
</head>
<body>
    
    <nav class="navbar navbar-expand-lg navbar-light bg-primary">
        <div class="container-fluid">
            <a class="navbar-brand" href="home.html">Home</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav">
                    <li class="nav-item">
                        <a class="nav-link active" aria-current="page" href="materi.pdf">Materi</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="Lembarkerjapolabilangan.pdf">Lembar Kerja</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#">Lembar Latihan</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link disabled" aria-disabled="true">Tugas</a>
                    </li>
                </ul>
            </div>
        </div>
    </nav>

    <div class="container">
        <h1 class="text-center">Materi Pola Bilangan</h1>

        <div class="container my-4">
            <h2 class="text mb-4">Indeks Materi</h2>
            <div class="list-group">
                <a href="#video" class="list-group-item list-group-item-action">
                    Sebelum itu yuk nonton dulu!
                </a>
                <a href="#geoGebra" class="list-group-item list-group-item-action">
                    Yuk dicoba lagi!
                </a>
                <a href="#apa-itu" class="list-group-item list-group-item-action">
                    Apa itu Pola Bilangan?
                </a>
                <a href="#jenis-jenis" class="list-group-item list-group-item-action">
                    Jenis-Jenis Pola Bilangan
                </a>
                <a href="#latihan" class="list-group-item list-group-item-action">
                    Latihan
                </a>
            </div>
        </div>
        

        <div class="row my-4" id="video">
            <div class="col-md-6">
                <div class="card">
                    <div class="card-body">
                        <h2>Sebelum itu yuk nonton dulu!</h2>
                        <iframe class="video-frame" src="https://www.youtube.com/embed/lkvoQNWmlQQ?si=dhWDv6LDxIN0WjaS" title="YouTube video player" allowfullscreen></iframe>
                    </div>
                </div>
            </div>
            <div class="col-md-6" id="geoGebra">
                <div class="card">
                    <div class="card-body">
                        <h2>Yuk dicoba lagi!</h2>
                        <iframe class="video-frame" title="Number Pattern Game" src="https://www.geogebra.org/material/iframe/id/xpntmj8z/width/1366/height/643/border/888888/sfsb/true/smb/false/stb/false/stbh/false/ai/false/asb/false/sri/false/rc/false/ld/false/sdz/false/ctl/false" style="border:0;"></iframe>
                    </div>
                </div>
            </div>
        </div>

        <h2 id="apa-itu">Apa itu Pola Bilangan?</h2>
        <div class="card mb-4">
            <div class="card-body">
                <p>
                    Pola bilangan adalah urutan angka yang mengikuti suatu aturan tertentu. Pola ini dapat berupa 
                    penjumlahan, pengurangan, perkalian, atau pembagian. Memahami pola bilangan membantu kita 
                    mengenali keteraturan dan memprediksi angka berikutnya dalam suatu urutan.
                </p>
            </div>
        </div>

        <h2 id="jenis-jenis">Jenis-Jenis Pola Bilangan</h2>

        <h3>Pola Aritmetika</h3>
        <div class="card mb-4">
            <div class="card-body">
                <p>
                    Dalam pola aritmetika, selisih antara dua suku berturut-turut adalah konstan. 
                    Rumus umum pola aritmetika adalah:
                </p>
                <p class="text-center">
                    a<sub>n</sub> = a<sub>1</sub> + (n - 1)d
                </p>
                <p>
                    Di mana:
                    <ul>
                        <li><strong>a<sub>n</sub></strong> = suku ke-n</li>
                        <li><strong>a<sub>1</sub></strong> = suku pertama</li>
                        <li><strong>d</strong> = selisih antar suku</li>
                        <li><strong>n</strong> = nomor suku</li>
                    </ul>
                </p>
                <div class="example">
                    Contoh: 2, 5, 8, 11, 14, ...<br>
                    Selisihnya adalah 3. Suku ke-5: a<sub>5</sub> = 2 + (5 - 1) × 3 = 14.
                </div>
            </div>
        </div>

        <h3>Pola Geometri</h3>
        <div class="card mb-4">
            <div class="card-body">
                <p>
                    Dalam pola geometri, rasio antara dua suku berturut-turut adalah konstan. 
                    Rumus umum pola geometri adalah:
                </p>
                <p class="text-center">
                    a<sub>n</sub> = a<sub>1</sub> × r<sup>(n - 1)</sup>
                </p>
                <p>
                    Di mana:
                    <ul>
                        <li><strong>a<sub>n</sub></strong> = suku ke-n</li>
                        <li><strong>a<sub>1</sub></strong> = suku pertama</li>
                        <li><strong>r</strong> = rasio antar suku</li>
                        <li><strong>n</strong> = nomor suku</li>
                    </ul>
                </p>
                <div class="example">
                    Contoh: 3, 6, 12, 24, 48, ...<br>
                    Rasio adalah 2. Suku ke-5: a<sub>5</sub> = 3 × 2<sup>(5 - 1)</sup> = 48.
                </div>
            </div>
        </div>

        <h3>Pola Bilangan Fibonacci</h3>
        <div class="card mb-4">
            <div class="card-body">
                <p>
                    Pola Fibonacci adalah urutan di mana setiap suku adalah jumlah dari dua suku sebelumnya.
                    Urutan dimulai dengan 0 dan 1.
                </p>
                <p class="text-center">
                    0, 1, 1, 2, 3, 5, 8, 13, 21, ...
                </p>
                <p>
                    Contoh: Suku ke-7 adalah 13 (5 + 8).
                </p>
            </div>
        </div>

        <h2 id="latihan">Latihan</h2>
        <div class="card mb-4">
            <div class="card-body">
                <p>
                    1. Tentukan suku berikutnya dalam pola berikut: 4, 7, 10, 13, ...<br>
                    2. Jika suku pertama adalah 5 dan selisihnya adalah 4, tentukan 5 suku pertama dari pola aritmetika tersebut.<br>
                    3. Tentukan suku berikutnya dalam pola berikut: 2, 4, 8, 16, ...<br>
                    4. Hitung suku ke-10 dalam urutan Fibonacci.
                </p>
            </div>
        </div>

        <div class="text-center">
            <img src="rektorat.jpg" class="img-fluid rounded-circle border my-4" alt="Rektorat">
        </div>

        <footer class="text-center my-4">
            <p>&copy; 2024 Sekolah Menengah Pertama Kelas 8</p>
        </footer>
        
        <div class="card text-center mb-4">
            <h5 class="card-header">Pendidikan Matematika</h5>
            <div class="card-body">
                <h5 class="card-title">Universitas Mataram</h5>
                <p class="card-text">Kami Akan Memberikan Yang Terbaik Untuk Anda</p>
                <a href="#" class="btn btn-custom">Kunjungi kami di sini</a>
            </div>
        </div>
    </div>

    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-b2a0w5C2G1frSOTJtFkvN/N2OMf8rY1brMOC/aRh9XUQk+H0ZDLrD3M4X2aRYL" crossorigin="anonymous"></script>
</body>

</html> 
