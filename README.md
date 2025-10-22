<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Follow Us | Skill Development Initiative</title>

<!-- Google Fonts -->
<link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;500;700&display=swap" rel="stylesheet">

<!-- Font Awesome -->
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css">

<style>
    * {
        margin: 0;
        padding: 0;
        box-sizing: border-box;
    }
	

    body {
        font-family: 'Roboto', sans-serif;
        background: linear-gradient(135deg, #1f4037, #99f2c8);
        height: 100vh;
        display: flex;
        justify-content: center;
        align-items: center;
        flex-direction: column;
        color: #fff;
        text-align: center;
        position: relative;
        overflow: hidden;
    }

    .card {
        background: rgba(255, 255, 255, 0.05);
        backdrop-filter: blur(15px);
        border-radius: 20px;
        padding: 40px 30px;
        max-width: 400px;
        width: 90%;
        box-shadow: 0 10px 40px rgba(0,0,0,0.2);
        transition: 0.3s;
    }

    .card:hover {
        transform: translateY(-5px);
        box-shadow: 0 20px 60px rgba(0,0,0,0.3);
    }

    .logo {
        width: 100px;
        height: 100px;
        border-radius: 50%;
        margin-bottom: 20px;
        object-fit: cover;
        border: 3px solid #fff;
    }

    h1 {
        font-size: 28px;
        margin-bottom: 10px;
        font-weight: 700;
    }

    p {
        font-size: 16px;
        margin-bottom: 30px;
        color: #eee;
    }

    .social-links {
        display: flex;
        justify-content: center;
        gap: 25px;
    }

    .social-links a {
        width: 60px;
        height: 60px;
        display: flex;
        align-items: center;
        justify-content: center;
        border-radius: 50%;
        background: rgba(255,255,255,0.2);
        color: #fff;
        font-size: 28px;
        transition: 0.3s;
        text-decoration: none;
        box-shadow: 0 4px 15px rgba(0,0,0,0.2);
    }

    .social-links a:hover {
        background: #fff;
        color: #1f4037;
        transform: scale(1.2);
        box-shadow: 0 6px 20px rgba(0,0,0,0.3);
    }

    footer {
        position: absolute;
        bottom: 20px;
        font-size: 14px;
        color: #f0f0f0;
        font-weight: 400;
    }

    @media(max-width: 480px) {
        .card {
            padding: 30px 20px;
        }

        h1 {
            font-size: 24px;
        }

        .social-links a {
            width: 50px;
            height: 50px;
            font-size: 24px;
        }
    }
</style>
</head>
<body>

<div class="card">

    <h1>Follow Us
<br> Click Icons <color yellow
	</h1>
    <p>Stay connected with us on social media for Upcoming trainings, Job updates.</p>

    <div class="social-links">
        <!-- Replace with your actual links -->
        <a href="https://www.facebook.com/share/19xVVwmsvV/" target="_blank"><i class="fab fa-facebook-f"></i></a>
        <a href="https://www.instagram.com/skill_tripura_official_?igsh=cHd2dGhrZ2Ewcjgw" target="_blank"><i class="fab fa-instagram"></i></a>
        <a href="https://x.com/TSDM_2015" target="_blank"><i class="fab fa-twitter"></i></a>
    </div>
</div>

<footer>© 2025 Skill Development Initiative | All Rights Reserved</footer>

</body>
</html>
