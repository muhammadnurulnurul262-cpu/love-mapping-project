# love-mapping-project
A simple mapping project about love — how emotions and logic can connect. I’m still learning, but if you want to add or improve this, thank you for contributing.

<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mind Map Penjelasan Tentang Cinta</title>
    <style>
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background: linear-gradient(135deg, #ff9a9e, #fecfef, #fecfef, #ff9a9e); /* Gradien latar belakang yang menarik */
            margin: 0;
            padding: 20px;
            color: #333;
        }
        h1 {
            text-align: center;
            color: #d63384; /* Warna pink gelap untuk judul */
            text-shadow: 2px 2px 4px rgba(0,0,0,0.1);
        }
        .mindmap {
            display: flex;
            flex-direction: column;
            align-items: center;
        }
        .center {
            background: linear-gradient(45deg, #ff69b4, #ffb6c1); /* Gradien untuk pusat */
            color: white;
            padding: 20px;
            border-radius: 50%;
            text-align: center;
            font-size: 24px;
            font-weight: bold;
            margin-bottom: 20px;
            box-shadow: 0 8px 16px rgba(0,0,0,0.2);
            transition: transform 0.3s ease; /* Animasi hover */
        }
        .center:hover {
            transform: scale(1.1);
        }
        .branch {
            display: flex;
            justify-content: space-around;
            width: 100%;
            max-width: 900px;
            flex-wrap: wrap;
        }
        .node {
            background: linear-gradient(45deg, #ffb6c1, #ffe4e1); /* Gradien untuk node */
            color: #333;
            padding: 15px;
            border-radius: 15px;
            text-align: center;
            width: 180px;
            margin: 10px;
            box-shadow: 0 4px 8px rgba(0,0,0,0.1);
            transition: all 0.3s ease; /* Animasi hover */
        }
        .node:hover {
            background: linear-gradient(45deg, #ff69b4, #ffb6c1);
            transform: translateY(-5px);
            box-shadow: 0 8px 16px rgba(0,0,0,0.2);
        }
        .subnode {
            background-color: rgba(255, 255, 255, 0.8); /* Semi-transparan untuk subnode */
            padding: 10px;
            border-radius: 5px;
            margin: 5px 0;
            font-size: 14px;
            border-left: 4px solid #ff69b4; /* Strip warna untuk penekanan */
        }
        ul {
            list-style-type: none;
            padding: 0;
        }
        li {
            margin: 5px 0;
        }
        .explanation {
            max-width: 800px;
            margin: 40px auto;
            padding: 20px;
            background-color: rgba(255, 255, 255, 0.9);
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0,0,0,0.1);
            text-align: justify;
        }
        .explanation h2 {
            color: #d63384;
        }
    </style>
</head>
<body>
    <h1>Mind Map Penjelasan Tentang Cinta</h1>
    <div class="mindmap">
        <div class="center">Cinta</div>
        <div class="branch">
            <div class="node">
                Definisi Cinta
                <ul>
                    <li class="subnode">Perasaan dalam yang kuat</li>
                    <li class="subnode">Keterikatan emosional</li>
                    <li class="subnode">Dorongan untuk peduli</li>
                </ul>
            </div>
            <div class="node">
                Jenis Cinta
                <ul>
                    <li class="subnode">Romantis (pasangan)</li>
                    <li class="subnode">Platonic (teman)</li>
                    <li class="subnode">Keluarga (orang tua/anak)</li>
                    <li class="subnode">Agape (tak bersyarat)</li>
                </ul>
            </div>
            <div class="node">
                Efek Cinta
                <ul>
                    <li class="subnode">Kebahagiaan & motivasi</li>
                    <li class="subnode">Kesedihan jika hilang</li>
                    <li class="subnode">Pertumbuhan pribadi</li>
                </ul>
            </div>
        </div>
        <div class="branch">
            <div class="node">
                Bagaimana Menunjukkan Cinta
                <ul>
                    <li class="subnode">Dukungan emosional</li>
                    <li class="subnode">Perhatian & perawatan</li>
                    <li class="subnode">Komunikasi terbuka</li>
                </ul>
            </div>
            <div class="node">
                Tantangan Cinta
                <ul>
                    <li class="subnode">Konflik & perbedaan</li>
                    <li class="subnode">Ketergantungan berlebihan</li>
                    <li class="subnode">Kehilangan & patah hati</li>
                </ul>
            </div>
        </div>
    </div>
    <div class="explanation">
        <h2>Penjelasan Mind Map Tentang Cinta</h2>
        <p>Mind map ini menggambarkan konsep cinta secara visual dan terstruktur. Di pusatnya adalah kata "Cinta", yang merupakan inti dari semua aspek yang dibahas. Cabang-cabang utama mencakup definisi, jenis, efek, cara menunjukkan, dan tantangan cinta. Setiap cabang memiliki subnode yang memberikan penjelasan singkat untuk memudahkan pemahaman.</p>
        <p>Cinta adalah emosi kompleks yang memengaruhi kehidupan manusia. Definisi dasarnya melibatkan perasaan dalam dan keterikatan, sementara jenisnya bervariasi dari romantis hingga agape. Efeknya bisa positif seperti kebahagiaan, atau negatif seperti kesedihan. Menunjukkan cinta melalui dukungan dan komunikasi dapat memperkuat hubungan, tetapi tantangan seperti konflik perlu diatasi dengan bijak.</p>
        <p>Modifikasi pada kode ini termasuk penambahan gradien warna yang menarik (seperti pink dan ungu) untuk membuat tampilan lebih hidup dan romantis. Animasi hover ditambahkan pada elemen untuk interaktivitas, seperti efek scale dan translate saat mouse diarahkan ke node. Latar belakang gradien dan shadow memberikan kedalaman visual.</p>
    </div>
    <p><em>Simpan kode ini sebagai file .html dan buka di browser untuk melihat mind map interaktif tentang cinta. Jika perlu penyesuaian lebih lanjut, beri tahu!</em></p>
</body>
</html>
