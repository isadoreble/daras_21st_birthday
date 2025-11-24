<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Happy 21st Birthday!</title>
    <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@400;500;600&family=Cormorant+Garamond:wght@300;400;500&display=swap" rel="stylesheet">
    <style>
        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
        }
        
        body {
            min-height: 100vh;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            background: linear-gradient(135deg, #fff9c4 0%, #a8dbff 100%);
            font-family: 'Cormorant Garamond', serif;
            padding: 20px;
            position: relative;
        }

        .paper-container {
            position: relative;
            width: 100%;
            max-width: 600px;
            height: auto;
            min-height: 500px;
            perspective: 1500px;
            margin: 20px 0;
        }

        .folded-paper {
            position: relative;
            width: 100%;
            height: 100%;
            min-height: 500px;
            transform-style: preserve-3d;
            transition: transform 2s ease;
            cursor: pointer;
        }

        .folded-paper.open {
            transform: rotateY(-180deg);
        }

        .paper-side {
            position: absolute;
            width: 100%;
            height: 100%;
            backface-visibility: hidden;
            border-radius: 5px;
            box-shadow: 0 10px 30px rgba(0,0,0,0.15);
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            padding: 30px 20px;
            box-sizing: border-box;
            overflow: hidden;
        }

        .front {
            background: linear-gradient(135deg, #ffebee 0%, #fce4ec 100%);
            z-index: 2;
        }

        .back {
            background: #f8f3e9;
            transform: rotateY(180deg);
            z-index: 1;
            justify-content: flex-start;
            padding-top: 30px;
        }

        /* Texture kertas dengan garis-garis */
        .front::before, .back::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            right: 0;
            bottom: 0;
            background-image: 
                linear-gradient(90deg, transparent 98%, rgba(0,0,0,0.03) 100%);
            background-size: 100% 28px;
            pointer-events: none;
            opacity: 0.4;
        }

        .quotes {
            font-family: 'Playfair Display', serif;
            font-size: 20px;
            color: #5d4037;
            line-height: 1.4;
            text-align: center;
            font-style: italic;
            text-shadow: 1px 1px 2px rgba(0,0,0,0.1);
            min-height: 100px;
            margin-bottom: 10px;
        }

        .birthday-21 {
            font-family: 'Playfair Display', serif;
            font-size: 60px;
            color: #ff6b6b;
            margin: 15px 0;
            text-shadow: 2px 2px 4px rgba(0,0,0,0.2);
        }

        .subtitle {
            font-size: 16px;
            color: #5d4037;
            letter-spacing: 2px;
            text-align: center;
        }

        .cursor {
            display: inline-block;
            width: 6px;
            height: 20px;
            background: #5d4037;
            margin-left: 2px;
            animation: blink 1s infinite;
            vertical-align: middle;
        }

        .photo-content {
            width: 100%;
            height: 100%;
            display: flex;
            flex-direction: column;
            overflow-y: auto;
            padding-bottom: 20px;
        }

        .page-title {
            font-family: 'Playfair Display', serif;
            font-size: 22px;
            color: #5d4037;
            text-align: center;
            margin-bottom: 20px;
            border-bottom: 2px solid #e8e0d0;
            padding-bottom: 8px;
        }

        .photo-grid {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 15px;
            margin-bottom: 15px;
        }

        .photo-item {
            display: flex;
            flex-direction: column;
            align-items: center;
            width: 100%;
            max-width: 300px;
        }

        .memory-photo {
            width: 100%;
            height: 180px;
            object-fit: cover;
            border-radius: 5px;
            border: 1px solid #e8e0d0;
            box-shadow: 0 3px 10px rgba(0,0,0,0.1);
        }

        .photo-caption {
            color: #5d4037;
            font-style: italic;
            font-size: 14px;
            text-align: center;
            margin-top: 8px;
            width: 100%;
            line-height: 1.4;
        }

        .footer-caption {
            text-align: center;
            margin-top: 10px;
            color: #5d4037;
            font-style: italic;
            font-size: 14px;
        }

        .love-seal {
            position: absolute;
            bottom: 15px;
            right: 15px;
            color: #ff6b6b;
            font-size: 20px;
        }

        .instruction {
            position: absolute;
            bottom: 15px;
            color: #5d4037;
            font-size: 12px;
            opacity: 0.7;
            animation: pulse 2s infinite;
            text-align: center;
            width: 100%;
        }

        .replay-btn {
            margin-top: 30px;
            padding: 12px 25px;
            background: #ff6b6b;
            color: white;
            border: none;
            border-radius: 50px;
            font-family: 'Cormorant Garamond', serif;
            font-size: 18px;
            font-weight: 500;
            cursor: pointer;
            box-shadow: 0 4px 15px rgba(255, 107, 107, 0.3);
            transition: all 0.3s ease;
            display: flex;
            align-items: center;
            gap: 8px;
            opacity: 0;
            visibility: hidden;
            transition: opacity 0.5s ease, visibility 0.5s ease, transform 0.3s ease;
        }

        .replay-btn.visible {
            opacity: 1;
            visibility: visible;
        }

        .replay-btn:hover {
            background: #ff5252;
            transform: translateY(-2px);
            box-shadow: 0 6px 20px rgba(255, 107, 107, 0.4);
        }

        .replay-btn:active {
            transform: translateY(0);
        }

        .replay-icon {
            font-size: 20px;
        }

        /* Animasi */
        @keyframes blink {
            0%, 50% { opacity: 1; }
            51%, 100% { opacity: 0; }
        }

        @keyframes pulse {
            0%, 100% { opacity: 0.5; }
            50% { opacity: 1; }
        }

        /* Media queries untuk responsivitas */
        @media (min-width: 769px) {
            .paper-container {
                height: 500px;
            }
            
            .folded-paper {
                height: 500px;
            }
            
            .paper-side {
                padding: 40px;
            }
            
            .quotes {
                font-size: 24px;
                min-height: 120px;
                margin-bottom: 20px;
            }
            
            .birthday-21 {
                font-size: 80px;
                margin: 20px 0;
            }
            
            .subtitle {
                font-size: 18px;
            }
            
            .cursor {
                width: 8px;
                height: 24px;
            }
            
            .page-title {
                font-size: 28px;
                margin-bottom: 25px;
                padding-bottom: 10px;
            }
            
            .photo-grid {
                flex-direction: row;
                justify-content: space-between;
            }
            
            .photo-item {
                width: 30%;
            }
            
            .memory-photo {
                height: 150px;
            }
            
            .photo-caption {
                font-size: 14px;
            }
            
            .love-seal {
                bottom: 20px;
                right: 20px;
                font-size: 24px;
            }
            
            .instruction {
                bottom: 20px;
                font-size: 14px;
            }
        }

        /* Untuk tablet */
        @media (max-width: 768px) and (min-width: 481px) {
            .photo-grid {
                gap: 20px;
            }
            
            .photo-item {
                max-width: 45%;
            }
            
            .memory-photo {
                height: 160px;
            }
        }

        /* Untuk HP */
        @media (max-width: 480px) {
            .paper-container {
                width: 100%;
                min-height: 550px;
            }
            
            .folded-paper {
                min-height: 550px;
            }
            
            .quotes {
                font-size: 18px;
                min-height: 90px;
            }
            
            .birthday-21 {
                font-size: 50px;
            }
            
            .subtitle {
                font-size: 14px;
            }
            
            .page-title {
                font-size: 20px;
            }
            
            .photo-item {
                max-width: 100%;
            }
            
            .memory-photo {
                height: 100px;
                width: 90%;
                max-width: 200px;
            }
            
            .photo-caption {
                font-size: 13px;
                width: 90%;
                max-width: 300px;
            }
            
            .replay-btn {
                margin-top: 25px;
                padding: 10px 20px;
                font-size: 16px;
            }
        }

        /* Untuk layar yang sangat kecil */
        @media (max-width: 360px) {
            .quotes {
                font-size: 16px;
            }
            
            .birthday-21 {
                font-size: 45px;
            }
            
            .memory-photo {
                height: 180px;
            }
            
            .photo-caption {
                font-size: 12px;
            }
        }
    </style>
</head>
<body>
    <div class="paper-container">
        <div class="folded-paper" id="foldedPaper">
            <div class="paper-side front">
                <div id="typedQuotes" class="quotes"></div>
                <div class="birthday-21">21</div>
                <div class="subtitle">HAPPY BIRTHDAY</div>
                <div class="love-seal">❤</div>
                <div class="instruction">Tap here</div>
            </div>
            
            <div class="paper-side back">
                <div class="photo-content">
                    <div class="page-title">Our Tahu Bulat Memories</div>
                    <div class="photo-grid">
                        <div class="photo-item">
                            <img src="smile.JPG" alt="Memory 1" class="memory-photo">
                            <div class="photo-caption">I hope that at this legal age you will get a bunch of happiness</div>
                        </div>
                        <div class="photo-item">
                            <img src="21.JPG" alt="Memory 2" class="memory-photo">
                            <div class="photo-caption">and your journal will be approved quickly awkwkwks</div>
                        </div>
                        <div class="photo-item">
                            <img src="gigit.JPG" alt="Memory 3" class="memory-photo">
                            <div class="photo-caption">once again HAPPY 21st BIRTHDAY DARA ZENYA</div>
                        </div>
                    </div>
                    <div class="footer-caption">
                        dikaylno's work • Thank you for being my friend until my oldest age • @dikaylno
                    </div>
                </div>
            </div>
        </div>
    </div>

    <button class="replay-btn" id="replayBtn">
        <span class="replay-icon">↻</span> Putar Ulang
    </button>

    <script>
        const foldedPaper = document.getElementById('foldedPaper');
        const typedQuotesElement = document.getElementById('typedQuotes');
        const replayBtn = document.getElementById('replayBtn');

        // Quotes untuk diketik
        const quotes = [
            "HAPPY BIRTHDAY TO THE MAX DARAYAM BLITZ, btw this is just a temporary gift because you haven't thought about the main gift yet and I hope you like the gift because I made it quite a headache... jkjk. And ALSO ENJOY THE GIFTTT xoxo"
        ];

        let quoteIndex = 0;
        let charIndex = 0;
        let currentLine = '';
        let typingActive = false;

        function typeWriter() {
            if (quoteIndex < quotes.length) {
                const currentQuote = quotes[quoteIndex];
                
                if (charIndex < currentQuote.length) {
                    const currentChar = currentQuote[charIndex];
                    currentLine += currentChar;
                    typedQuotesElement.textContent += currentChar;
                    
                    charIndex++;
                    setTimeout(typeWriter, 80);
                } else {
                    // Pindah ke quotes berikutnya
                    quoteIndex++;
                    charIndex = 0;
                    
                    if (quoteIndex < quotes.length) {
                        typedQuotesElement.innerHTML += '<br>';
                        currentLine = '';
                        setTimeout(typeWriter, 500);
                    } else {
                        // Semua quotes selesai diketik
                        typingActive = false;
                    }
                }
            }
        }

        function resetAnimation() {
            // Reset variabel animasi
            quoteIndex = 0;
            charIndex = 0;
            currentLine = '';
            
            // Reset tampilan
            typedQuotesElement.textContent = '';
            
            // Tutup kertas jika terbuka
            foldedPaper.classList.remove('open');
            
            // Sembunyikan tombol replay
            replayBtn.classList.remove('visible');
            
            // Mulai animasi ketikan
            typingActive = true;
            setTimeout(() => {
                typeWriter();
            }, 800);
        }

        // Buka kertas saat diklik
        foldedPaper.addEventListener('click', function() {
            foldedPaper.classList.add('open');
            // Tampilkan tombol replay setelah kertas terbuka
            setTimeout(() => {
                replayBtn.classList.add('visible');
            }, 1000);
        });

        // Tombol replay
        replayBtn.addEventListener('click', function() {
            // Tambahkan efek animasi sebelum reset
            foldedPaper.style.transition = 'transform 1s ease';
            foldedPaper.classList.remove('open');
            
            // Tunggu animasi selesai sebelum reset
            setTimeout(() => {
                resetAnimation();
                foldedPaper.style.transition = 'transform 2s ease'; // Kembalikan ke durasi normal
            }, 1000);
        });

        // Mulai mengetik setelah halaman dimuat
        window.onload = function() {
            setTimeout(() => {
                typingActive = true;
                typeWriter();
            }, 2000);
        }
    </script>
</body>
</html>