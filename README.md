<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>The Truman Show</title>
    <style>
        body {
            margin: 0;
            font-family: Arial, Helvetica, sans-serif;
            background: linear-gradient(180deg, #111a2d, #1a2f4d);
            color: #eef2f7;
            line-height: 1.6;
        }
        header {
            padding: 24px 20px;
            text-align: center;
            background: rgba(0, 0, 0, 0.35);
            border-bottom: 1px solid rgba(255, 255, 255, 0.12);
        }
        header a {
            color: #a8d8ff;
            text-decoration: none;
            font-weight: bold;
        }
        main {
            max-width: 1000px;
            margin: 0 auto;
            padding: 28px 20px 40px;
        }
        .hero {
            display: grid;
            gap: 24px;
            align-items: center;
        }
        .hero img {
            width: 100%;
            max-width: 420px;
            border-radius: 14px;
            box-shadow: 0 18px 40px rgba(0, 0, 0, 0.55);
        }
        .hero-text {
            background: rgba(255, 255, 255, 0.06);
            border: 1px solid rgba(255, 255, 255, 0.12);
            border-radius: 14px;
            padding: 22px;
        }
        h1 {
            margin: 0 0 12px;
            font-size: 3rem;
            letter-spacing: 1px;
            color: #ffd05b;
        }
        h2, h3 {
            color: #9ddcff;
            margin-top: 0;
        }
        .character-grid {
            display: grid;
            gap: 18px;
            grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
            margin-top: 18px;
        }
        .card {
            background: rgba(255, 255, 255, 0.06);
            border: 1px solid rgba(255, 255, 255, 0.1);
            border-radius: 14px;
            padding: 18px;
        }
        .card strong {
            display: block;
            margin-bottom: 8px;
            color: #ffd05b;
        }
        .section {
            margin-top: 28px;
        }
        img.profile {
            width: 100%;
            height: auto;
            border-radius: 12px;
        }
        footer {
            text-align: center;
            color: #b8c7d5;
            margin-top: 36px;
            padding-top: 18px;
            border-top: 1px solid rgba(255, 255, 255, 0.12);
        }
        @media (min-width: 760px) {
            .hero {
                grid-template-columns: 1fr 1fr;
            }
        }
    </style>
</head>
<body>
    <header>
        <a href="Assign1.html">Assignment 1 - Movies</a>
    </header>
    <main>
        <section class="hero">
            <div class="hero-text">
                    <h1>The Truman Show</h1>
                <p><strong>The Truman Show</strong> is a film about Truman Burbank, whose entire life is secretly filmed and broadcast as a reality TV show. He lives in a carefully controlled town called Seahaven while the world watches, and the story follows his awakening as he begins to sense the truth.</p>
                <p>This movie explores themes of reality, freedom, identity, and the power of media. Jim Carrey delivers a moving performance as Truman, and the film asks whether anyone can escape a world built for them.</p>
            </div>
            <img src="TrumanPoster.png" alt="The Truman Show poster">
        </section>

<section class="section">
            <h2>Main Characters</h2>
            <div class="character-grid">
                <div class="card">
                    <img src="Truman.png" alt="Truman Burbank" class="profile">
                    <strong>Truman Burbank</strong>
                    <p>Truman is the innocent hero of the story. He starts to notice strange things in Seahaven and decides to challenge the limits of his fake world.</p>
                </div>
                <div class="card">
                    <img src="Master mind.png" alt="Christof the director" class="profile">
                    <strong>Christof</strong>
                    <p>Christof is the creator and director of the show. He controls everything behind the scenes and believes he is protecting Truman by keeping him inside Seahaven.</p>
                </div>
                <div class="card">
                    <img src="Wife of truman.png" alt="Meryl Burbank" class="profile">
                    <strong>Meryl Burbank</strong>
                    <p>Meryl is Truman’s wife in the show, but she is really an actress. She follows the script and tries to keep Truman from discovering the truth.</p>
                </div>
                <div class="card">
                    <img src="Twins.png" alt="The twins" class="profile">
                    <strong>The Twins</strong>
                    <p>The twins are part of Seahaven’s cast. Their cheerful presence helps build the illusion of normal life and keeps Truman distracted.</p>
                </div>
            </div>
        </section>
    </main>
    <footer>
        <p>Improved Truman Show page with clearer structure and better styling.</p>
    </footer>
</body>
</html> 
