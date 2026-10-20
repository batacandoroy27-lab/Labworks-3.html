<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
   
    <link rel="stylesheet" href="style.css">
</head>
<body>

  

    <main class="profile-card">

        <div class="badge">✨ MY PROFILE ✨</div>

       
<div class="profile-image">
  


        <h1>Hi, I'm Ryn! 💕</h1>

        <p class="subtitle">
            Student | Future Web Developer
        </p>

        <p class="description">
            Hello! Welcome to my little corner of the internet! 🌷
            I enjoy learning new things, exploring technology,
            expressing my creativity, and creating beautiful
            websites using HTML and CSS.
        </p>

        <div class="divider"></div>

        <h2>🌸 My Skills 🌸</h2>

        <ul class="skills">
            
            <li>🎨 Drawing & Painting</li>
<li>🎤 Singing </li>
<li>🧠 Creative thinking </li>
<li>💭 Analytical Skills </li>
            <li>🧩 Problem Solving</li>
<li>😌 Pattern Recognition </li>

<li>😶‍🌫️ Strategic Thinking </li>
<li>💡 Imagination </li>
            <li>🚀 Creativity</li>
        </ul>

        <div class="divider"></div>

        <h2>💌 Say Hello!</h2>

   

        
        <p id="message" role="status" aria-live="polite"></p>

        <footer>
           💗✨ Never give up. Great things take time, and every small step brings you closer to your dreams. 💗✨
            <br>
            <span>Dream big, stay creative! 🌷</span>
        </footer>

    </main>

    <script>
        const helloBtn = document.getElementById("helloBtn");
        const themeBtn = document.getElementById("themeBtn");
        const nickname = document.getElementById("nickname");
        const message = document.getElementById("message");

        helloBtn.addEventListener("click", function () {
            const name = nickname.value.trim() || "Friend";
            message.textContent =
                "Hello, " + name + "! Welcome to my profile! 🎉💗";
        });

        themeBtn.addEventListener("click", function () {
            document.body.classList.toggle("alternate-theme");
        });
    </script>

</body>
</html><html>

</html>
