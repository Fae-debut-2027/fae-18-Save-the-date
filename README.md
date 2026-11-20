<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Darlin Fae @ 18 | Save the Date</title>
    <!-- Google Fonts for Gothic Elegance -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Cinzel:wght@400;600;700&family=Cormorant+Garamond:ital,wght@0,400;0,600;1,400&display=swap" rel="stylesheet">
    
    <style>
        :root {
            --bg-black: #0b0b0c;
            --card-burgundy: #2b080d;
            --accent-burgundy: #7a1c28;
            --deep-red: #4a0e17;
            --gold-accent: #d4af37;
            --text-light: #f5f0eb;
            --text-muted: #b8a99a;
        }

        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
        }

        body {
            background-color: var(--bg-black);
            color: var(--text-light);
            font-family: 'Cormorant Garamond', serif;
            min-height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            padding: 20px;
            background-image: 
                radial-gradient(circle at center, rgba(122, 28, 40, 0.25) 0%, rgba(11, 11, 12, 0.95) 70%);
            background-attachment: fixed;
        }

        .container {
            max-width: 650px;
            width: 100%;
            background: linear-gradient(145deg, rgba(43, 8, 13, 0.85), rgba(11, 11, 12, 0.95));
            border: 1px solid rgba(212, 175, 55, 0.3);
            border-radius: 12px;
            padding: 40px 30px;
            text-align: center;
            box-shadow: 0 15px 35px rgba(0, 0, 0, 0.8), 0 0 20px rgba(122, 28, 40, 0.3);
            position: relative;
            backdrop-filter: blur(5px);
        }

        .container::before {
            content: '';
            position: absolute;
            top: 10px; left: 10px; right: 10px; bottom: 10px;
            border: 1px dashed rgba(212, 175, 55, 0.2);
            border-radius: 8px;
            pointer-events: none;
        }

        .subtitle {
            font-family: 'Cinzel', serif;
            font-size: 0.9rem;
            letter-spacing: 4px;
            color: var(--gold-accent);
            text-transform: uppercase;
            margin-bottom: 12px;
        }

        h1 {
            font-family: 'Cinzel', serif;
            font-size: 2.5rem;
            font-weight: 700;
            color: var(--text-light);
            text-shadow: 0 0 10px rgba(122, 28, 40, 0.7);
            margin-bottom: 5px;
            line-height: 1.2;
        }

        .tagline {
            font-style: italic;
            font-size: 1.2rem;
            color: var(--text-muted);
            margin-bottom: 30px;
        }

        .divider {
            width: 80px;
            height: 2px;
            background: linear-gradient(90deg, transparent, var(--gold-accent), transparent);
            margin: 20px auto;
        }

        .details-box {
            margin: 25px 0;
            padding: 20px;
            background: rgba(11, 11, 12, 0.5);
            border-left: 2px solid var(--accent-burgundy);
            border-right: 2px solid var(--accent-burgundy);
            border-radius: 6px;
        }

        .detail-item {
            margin: 12px 0;
        }

        .detail-label {
            font-family: 'Cinzel', serif;
            font-size: 0.85rem;
            color: var(--gold-accent);
            letter-spacing: 2px;
            display: block;
            margin-bottom: 3px;
        }

        .detail-value {
            font-size: 1.25rem;
            color: var(--text-light);
        }

        .dress-code {
            font-size: 1.05rem;
            color: var(--text-muted);
            margin-top: 15px;
            font-style: italic;
        }

        .btn-rsvp {
            display: inline-block;
            margin-top: 25px;
            padding: 14px 36px;
            font-family: 'Cinzel', serif;
            font-size: 1rem;
            font-weight: 600;
            letter-spacing: 2px;
            color: var(--text-light);
            background: linear-gradient(135deg, var(--deep-red), var(--accent-burgundy));
            border: 1px solid var(--gold-accent);
            border-radius: 30px;
            text-decoration: none;
            transition: all 0.3s ease;
            box-shadow: 0 4px 15px rgba(0, 0, 0, 0.5);
        }

        .btn-rsvp:hover {
            background: linear-gradient(135deg, var(--accent-burgundy), #9e2434);
            box-shadow: 0 0 20px rgba(212, 175, 55, 0.5);
            transform: translateY(-2px);
        }

        /* Floating Music Button */
        .music-control {
            position: fixed;
            bottom: 25px;
            right: 25px;
            background: rgba(43, 8, 13, 0.9);
            border: 1px solid var(--gold-accent);
            color: var(--gold-accent);
            width: 50px;
            height: 50px;
            border-radius: 50%;
            display: flex;
            justify-content: center;
            align-items: center;
            cursor: pointer;
            box-shadow: 0 4px 12px rgba(0,0,0,0.6);
            z-index: 1000;
            transition: transform 0.2s;
        }

        .music-control:hover {
            transform: scale(1.1);
        }

        .music-icon {
            font-size: 1.2rem;
        }
    </style>
</head>
<body>

    <div class="container">
        <div class="subtitle">Save The Date</div>
        <h1>Darlin Fae</h1>
        <div class="tagline">Is Turning 18</div>

        <div class="divider"></div>

        <p style="font-size: 1.1rem; color: var(--text-muted);">
            Join us for an evening of dark romance, elegance, and magic.
        </p>

        <div class="details-box">
            <div class="detail-item">
                <span class="detail-label">Date & Time</span>
                <span class="detail-value">December 19, 2027 | 5:00 PM</span>
            </div>
            
            <div class="divider" style="width: 40px; margin: 10px auto;"></div>

            <div class="detail-item">
                <span class="detail-label">Venue</span>
                <span class="detail-value">Chalie's Restaurant & D'Jocos Resort</span>
                <div style="font-size: 0.95rem; color: var(--text-muted); margin-top: 2px;">
                    Muzon, Naic, Cavite
                </div>
            </div>

            <div class="dress-code">
                <strong>Dress Code:</strong> Deep Burgundy & Black (Gothic Elegance)<br>
                <small style="font-size: 0.85rem; color: #a09080;">*Strictly for guests ages 13 years old and above.</small>
            </div>
        </div>

        <!-- Integrated Shortened Google Form Link -->
        <a href="https://forms.gle/g9BE5XhNpbMPETYw7" target="_blank" class="btn-rsvp">
            CONFIRM RSVP
        </a>
    </div>

    <!-- Background Audio Element -->
    <audio id="bg-music" loop>
        <source src="https://cdn.pixabay.com/download/audio/2022/05/27/audio_1808fbf07a.mp3?filename=waltz-of-the-flowers-115340.mp3" type="audio/mpeg">
        Your browser does not support the audio element.
    </audio>

    <!-- Floating Audio Toggle Button -->
    <div class="music-control" id="music-btn" title="Toggle Music">
        <span class="music-icon" id="music-icon">🎵</span>
    </div>

    <script>
        const audio = document.getElementById('bg-music');
        const musicBtn = document.getElementById('music-btn');
        const musicIcon = document.getElementById('music-icon');
        let isPlaying = false;

        musicBtn.addEventListener('click', () => {
            if (isPlaying) {
                audio.pause();
                musicIcon.textContent = '🎵';
                musicBtn.style.borderColor = 'var(--gold-accent)';
            } else {
                audio.play();
                musicIcon.textContent = '⏸️';
                musicBtn.style.borderColor = '#ff4d4d';
            }
            isPlaying = !isPlaying;
        });
    </script>
</body>
</html>
