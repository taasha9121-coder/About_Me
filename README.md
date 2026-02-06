# About_Me
"My personal corner of the internet, showcasing projects and skills."
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>Ansh Tiwari | Profile</title>
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<style>
    * {
        margin: 0;
        padding: 0;
        box-sizing: border-box;
        font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        transition: background 0.5s, color 0.5s;
    }

    body {
        min-height: 100vh;
        display: flex;
        align-items: center;
        justify-content: center;
        background: linear-gradient(135deg, #0f2027, #2c5364); /* Dark mode default */
        color: #f0f0f0;
    }

    .profile-card {
        width: 90%;
        max-width: 900px;
        border-radius: 18px;
        box-shadow: 0 25px 50px rgba(0,0,0,0.25);
        overflow: hidden;
        background: #16222a; /* Dark mode background */
        transition: background 0.5s, color 0.5s;
    }

    .profile-header {
        background: linear-gradient(135deg, #11998e, #38ef7d);
        color: white;
        padding: 35px;
        text-align: center;
        transition: background 0.5s;
    }

    .profile-header img {
        width: 130px;
        height: 130px;
        border-radius: 50%;
        object-fit: cover;
        border: 5px solid rgba(255,255,255,0.9);
        margin-bottom: 15px;
    }

    .profile-header h1 {
        font-size: 32px;
        margin-bottom: 8px;
    }

    .profile-header p {
        font-size: 16px;
        opacity: 0.9;
    }

    .profile-content {
        padding: 30px;
        background: #1f2c34; /* Dark mode content background */
        transition: background 0.5s;
    }

    .section {
        margin-bottom: 25px;
    }

    .section h2 {
        font-size: 22px;
        margin-bottom: 10px;
        color: #ff6b6b;
        border-left: 5px solid #ff6b6b;
        padding-left: 10px;
        transition: color 0.5s, border-color 0.5s;
    }

    .section p {
        font-size: 16px;
        line-height: 1.7;
        color: #dcdcdc;
        transition: color 0.5s;
    }

    .skills {
        display: flex;
        flex-wrap: wrap;
        gap: 10px;
    }

    .skill {
        background: linear-gradient(135deg, #ff6b6b, #4ecdc4);
        padding: 10px 16px;
        border-radius: 20px;
        font-size: 14px;
        color: white;
        font-weight: 500;
        transition: 0.3s;
    }

    .skill:hover {
        background: linear-gradient(135deg, #38ef7d, #11998e);
        transform: scale(1.1);
        box-shadow: 0 8px 20px rgba(255, 75, 43, 0.5);
    }

    .social-links {
        display: flex;
        flex-wrap: wrap;
        gap: 15px;
        margin-top: 10px;
    }

    .social-links a {
        text-decoration: none;
        color: white;
        padding: 12px 22px;
        border-radius: 30px;
        font-size: 15px;
        font-weight: 500;
        display: flex;
        align-items: center;
        gap: 8px;
        transition: 0.3s;
    }

    .youtube {
        background: linear-gradient(135deg, #ff4b2b, #ff416c);
    }

    .instagram {
        background: linear-gradient(45deg, #f7971e, #ffd200, #ff6b6b);
    }

    .social-links a:hover {
        transform: translateY(-4px);
        box-shadow: 0 12px 25px rgba(0,0,0,0.3);
    }

    .profile-footer {
        text-align: center;
        padding: 15px;
        background: #111;
        font-size: 14px;
        color: #bbb;
        transition: background 0.5s, color 0.5s;
    }

    .toggle-btn {
        position: fixed;
        top: 20px;
        right: 20px;
        background: #ff6b6b;
        border: none;
        padding: 10px 15px;
        border-radius: 30px;
        color: white;
        font-weight: bold;
        cursor: pointer;
        transition: 0.3s;
        z-index: 1000;
    }

    .toggle-btn:hover {
        background: #38ef7d;
    }

    /* Light Mode: Mint & Peach */
    body.light-mode {
        background: linear-gradient(135deg, #e0f7fa, #ffe0b2);
        color: #222;
    }

    body.light-mode .profile-card {
        background: #ffffff;
    }

    body.light-mode .profile-header {
        background: linear-gradient(135deg, #ffecd2, #e0f7fa);
        color: #222;
    }

    body.light-mode .profile-content {
        background: #fefefe;
    }

    body.light-mode .section h2 {
        color: #ff6b6b;
        border-left-color: #ff6b6b;
    }

    body.light-mode .section p {
        color: #555;
    }

    body.light-mode .skill {
        background: linear-gradient(135deg, #ffb6b6, #80e0d0);
        color: #222;
    }

    body.light-mode .skill:hover {
        background: linear-gradient(135deg, #ffecd2, #e0f7fa);
        color: #222;
        box-shadow: 0 8px 20px rgba(255, 182, 193, 0.5);
    }

    body.light-mode .profile-footer {
        background: #f9f9f9;
        color: #555;
    }

    @media (max-width: 600px) {
        .profile-header h1 {
            font-size: 26px;
        }
    }
</style>
</head>

<body>

<button class="toggle-btn" onclick="toggleMode()">🌙 / ☀️</button>

<div class="profile-card">

    <div class="profile-header">
        <img src="/storage/emulated/0/MIUI/ShareMe/IMG_20230729_150239.jpg" alt="Profile">
        <h1>Ansh Krishnakant Tiwari</h1>
        <p>Student | Coding Learner | Gamer</p>
    </div>

    <div class="profile-content">

        <div class="section">
            <h2>Introduction</h2>
            <p>
                Hello! My name is <strong>Ansh Krishnakant Tiwari</strong>.
                I am studying in <strong>11th Standard</strong> at
                <strong>RKT College, Ulhasnagar</strong>.
            </p>
        </div>

        <div class="section">
            <h2>Education</h2>
            <p>
                I am focusing on <strong>IT</strong> with practical knowledge
                along with learning modern technical skills.
            </p>
        </div>

        <div class="section">
            <h2>Interests</h2>
            <p>
                I love playing games and learning <strong>coding</strong>.
                I am currently a beginner in web development.
            </p>
        </div>

        <div class="section">
            <h2>Skills & Learning</h2>
            <div class="skills">
                <div class="skill">HTML</div>
                <div class="skill">JavaScript</div>
                <div class="skill">Web Development</div>
            </div>
        </div>

        <div class="section">
            <h2>Social Media</h2>
            <div class="social-links">
                <a href="https://youtube.com/@krishnakanttiwari8040?si=UAzTv18LDU17A7VP" target="_blank" class="youtube">
                    ▶ YouTube Channel
                </a>

                <a href="https://www.instagram.com/isolatedx.soul?igsh=MXRlbnc2MGY5dnFmbg==" target="_blank" class="instagram">
                    📷 Instagram Profile
                </a>
            </div>
        </div>

    </div>

    <div class="profile-footer">
        © 2026 | Created by Ansh Tiwari
    </div>

</div>

<script>
    function toggleMode() {
        document.body.classList.toggle('light-mode');
    }
</script>

</body>
</html>
