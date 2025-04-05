<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Melancholic</title>
    <style>
        body {
            margin: 0;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            
            background-image: url('./green.png');
        }

        nav {
            background-color: rgb(2, 48, 0);
            height: 100px;
            color: #faf9f9;
            display: flex;
            align-items: center;
            justify-content: center;
        }

        nav h1 {
            font-size: 48px;
            margin: 0;
            font-family: 'Times New Roman', Times, serif;
        }


        .card-container {
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
            gap: 30px;
            padding: 20px;
        }

        .card {
            margin-top: 20px;
            background-color: #fff;
            width: 300px;
            border-radius: 16px;
            box-shadow: 0 8px 20px rgba(0, 0, 0, 0.1);
            overflow: hidden;
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }

        .card:hover {
            transform: translateY(-5px);
            box-shadow: 0 12px 24px rgba(0, 0, 0, 0.2);
        }

        .card img {
            width: 100%;
            height: 400px;
            object-fit: cover;
        }

        .card-body {
            padding: 20px;
        }

        .card-title {
            font-size: 22px;
            margin-bottom: 10px;
            color: rgb(2,48,40);
        }

        .card-text {
            font-size: 14px;
            color: #333;
        }

        .list-group {
            list-style: none;
            padding: 0;
            margin: 0;
            border-top: 1px solid #eee;
        }

        .list-group-item {
            padding: 12px 20px;
            border-bottom: 1px solid #eee;
            font-size: 14px;
            background-color: #fff;
        }

        .card-body a {
            text-decoration: none;
            color: rgb(2,48,40);
            margin-right: 10px;
            font-weight: bold;
        }

        .card-body a:hover {
            text-decoration: underline;
        }
    </style>
</head>
<body>
    <nav style="background-color: rgb(2,48,40); height: 150px; color: #faf9f9; display: flex; flex-direction: column; align-items: center; justify-content: center; font-family: 'Times New Roman', Times, serif;">
        <h1 style="font-size: 54px; margin: 10px 0 12px 0;">Passionate & Intense</h1>
        <p style="font-size: 22px; font-style: italic; color: #f0e6e6; margin-top: 10px;">Would a dramatic violin solo suffice today?</p>
    </nav>
    
    
    

<div class="card-container">

   <!-- 1. The Bell Jar -->
<div class="card">
    <img src="C:\Users\vaish\Downloads\bell jar.png" alt="The Bell Jar">
    <div class="card-body">
        <h2 class="card-title">The Bell Jar</h2>
        <p class="card-text">A young woman's descent into mental illness echoes the suffocating pressure of identity, womanhood, and society.</p>
    </div>
    <ul class="list-group">
        <li class="list-group-item"><strong>Author:</strong> Sylvia Plath</li>
        <li class="list-group-item"><strong>Publishing Year:</strong> 1963</li>
        <li class="list-group-item"><strong>Goodreads Rating:</strong> 4.02</li>
        <li class="list-group-item"><strong>Themes:</strong> Depression, Identity, Isolation</li>
    </ul>
</div>

<!-- 2. Norwegian Wood -->
<div class="card">
    <img src="C:\Users\vaish\Downloads\Screenshot 2025-04-05 112925.png" alt="Norwegian Wood">
    <div class="card-body">
        <h2 class="card-title">Norwegian Wood</h2>
        <p class="card-text">Toru’s memories of young love, grief, and solitude paint a hauntingly beautiful picture of loss and longing.</p>
    </div>
    <ul class="list-group">
        <li class="list-group-item"><strong>Author:</strong> Haruki Murakami</li>
        <li class="list-group-item"><strong>Publishing Year:</strong> 1987</li>
        <li class="list-group-item"><strong>Goodreads Rating:</strong> 4.00</li>
        <li class="list-group-item"><strong>Themes:</strong> Melancholy, Death, Love</li>
    </ul>
</div>

<!-- 3. On Earth We're Briefly Gorgeous -->
<div class="card">
    <img src="C:\Users\vaish\Downloads\Screenshot 2025-04-05 112957.png" alt="On Earth We're Briefly Gorgeous">
    <div class="card-body">
        <h2 class="card-title">On Earth We're Briefly Gorgeous</h2>
        <p class="card-text">A poetic letter from a son to his illiterate mother, unraveling trauma, love, and queerness in a fractured world.</p>
    </div>
    <ul class="list-group">
        <li class="list-group-item"><strong>Author:</strong> Ocean Vuong</li>
        <li class="list-group-item"><strong>Publishing Year:</strong> 2019</li>
        <li class="list-group-item"><strong>Goodreads Rating:</strong> 4.15</li>
        <li class="list-group-item"><strong>Themes:</strong> Identity, War, Queerness</li>
    </ul>
</div>

<!-- 4. Never Let Me Go -->
<div class="card">
    <img src="C:\Users\vaish\Downloads\Screenshot 2025-04-05 113104.png" alt="Never Let Me Go">
    <div class="card-body">
        <h2 class="card-title">Never Let Me Go</h2>
        <p class="card-text">A haunting tale of students at a mysterious school who slowly uncover the tragic purpose of their existence.</p>
    </div>
    <ul class="list-group">
        <li class="list-group-item"><strong>Author:</strong> Kazuo Ishiguro</li>
        <li class="list-group-item"><strong>Publishing Year:</strong> 2005</li>
        <li class="list-group-item"><strong>Goodreads Rating:</strong> 3.85</li>
        <li class="list-group-item"><strong>Themes:</strong> Memory, Fate, Loss</li>
    </ul>
</div>

<!-- 5. A Little Life -->
<div class="card">
    <img src="C:\Users\vaish\Downloads\Screenshot 2025-04-05 113234.png" alt="A Little Life">
    <div class="card-body">
        <h2 class="card-title">A Little Life</h2>
        <p class="card-text">Four friends navigate decades in New York, anchored by one man's deeply buried trauma and enduring pain.</p>
    </div>
    <ul class="list-group">
        <li class="list-group-item"><strong>Author:</strong> Hanya Yanagihara</li>
        <li class="list-group-item"><strong>Publishing Year:</strong> 2015</li>
        <li class="list-group-item"><strong>Goodreads Rating:</strong> 4.33</li>
        <li class="list-group-item"><strong>Themes:</strong> Trauma, Friendship, Survival</li>
    </ul>
</div>

<!-- 6. The Remains of the Day -->
<div class="card">
    <img src="C:\Users\vaish\Downloads\Screenshot 2025-04-05 113320.png" alt="The Remains of the Day">
    <div class="card-body">
        <h2 class="card-title">The Remains of the Day</h2>
        <p class="card-text">An aging butler reflects on his life of service and the chances at love he quietly let slip away.</p>
    </div>
    <ul class="list-group">
        <li class="list-group-item"><strong>Author:</strong> Kazuo Ishiguro</li>
        <li class="list-group-item"><strong>Publishing Year:</strong> 1989</li>
        <li class="list-group-item"><strong>Goodreads Rating:</strong> 4.13</li>
        <li class="list-group-item"><strong>Themes:</strong> Regret, Duty, Lost Love</li>
    </ul>
</div>

<!-- 7. The God of Small Things -->
<div class="card">
    <img src="C:\Users\vaish\Downloads\Screenshot 2025-04-05 113415.png" alt="The God of Small Things">
    <div class="card-body">
        <h2 class="card-title">The God of Small Things</h2>
        <p class="card-text">Set in India, this tale of twins explores forbidden love, broken family, and the lasting echo of childhood trauma.</p>
    </div>
    <ul class="list-group">
        <li class="list-group-item"><strong>Author:</strong> Arundhati Roy</li>
        <li class="list-group-item"><strong>Publishing Year:</strong> 1997</li>
        <li class="list-group-item"><strong>Goodreads Rating:</strong> 4.09</li>
        <li class="list-group-item"><strong>Themes:</strong> Love, Caste, Memory</li>
    </ul>
</div>

<!-- 8. The Shadow of the Wind -->
<div class="card">
    <img src="C:\Users\vaish\Downloads\Screenshot 2025-04-05 113544.png" alt="The Shadow of the Wind">
    <div class="card-body">
        <h2 class="card-title">The Shadow of the Wind</h2>
        <p class="card-text">In post-war Barcelona, a boy discovers a forgotten book—and a buried past full of sorrow, secrets, and obsession.</p>
    </div>
    <ul class="list-group">
        <li class="list-group-item"><strong>Author:</strong> Carlos Ruiz Zafón</li>
        <li class="list-group-item"><strong>Publishing Year:</strong> 2001</li>
        <li class="list-group-item"><strong>Goodreads Rating:</strong> 4.26</li>
        <li class="list-group-item"><strong>Themes:</strong> Memory, Literature, Tragedy</li>
    </ul>
</div>



</div>

</body>
</html>
