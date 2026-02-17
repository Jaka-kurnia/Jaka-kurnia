<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Tech Stack Banner</title>

  <!-- Font -->
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600&display=swap" rel="stylesheet">

  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: "Poppins", sans-serif;
    }

    body {
      background: #020617; /* dark navy */
      display: flex;
      justify-content: center;
      align-items: center;
      min-height: 100vh;
    }

    .container {
      text-align: center;
    }

    /* SOCIAL BUTTONS */
    .social {
      margin-bottom: 30px;
    }

    .social a {
      text-decoration: none;
      margin: 0 6px;
    }

    .social img {
      height: 40px;
    }

    /* BADGES AREA */
    .badges {
      display: flex;
      flex-direction: column;
      align-items: center;
      gap: 14px;
    }

    .badge-row img {
      height: 60px;
      margin: 6px;
    }

    .tools-row img {
      height: 50px;
      margin: 6px;
    }

    /* RESPONSIVE */
    @media (max-width: 768px) {
      .badge-row img {
        height: 48px;
      }

      .tools-row img {
        height: 42px;
      }

      .social img {
        height: 34px;
      }
    }
  </style>
</head>
<body>
  <div class="container">

    <!-- SOCIAL -->
    <div class="social">
      <a href="#"><img src="https://img.shields.io/badge/LINKEDIN-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"></a>
      <a href="#"><img src="https://img.shields.io/badge/TELEGRAM-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white"></a>
      <a href="#"><img src="https://img.shields.io/badge/FACEBOOK-1877F2?style=for-the-badge&logo=facebook&logoColor=white"></a>
    </div>

    <!-- TECH STACK -->
    <div class="badges">
      <div class="badge-row">
        <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white"/>
        <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white"/>
        <img src="https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white"/>
        <img src="https://img.shields.io/badge/Bootstrap-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white"/>
        <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black"/>
        <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB"/>
        <img src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=next.js&logoColor=white"/>
        <img src="https://img.shields.io/badge/Laravel-FF2D20?style=for-the-badge&logo=laravel&logoColor=white"/>
        <img src="https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white"/>
        <img src="https://img.shields.io/badge/MariaDB-003545?style=for-the-badge&logo=mariadb&logoColor=white"/>
      </div>

      <!-- TOOLS -->
      <div class="tools-row">
        <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white"/>
        <img src="https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white"/>
        <img src="https://img.shields.io/badge/VS_Code-007ACC?style=for-the-badge&logo=visual-studio-code&logoColor=white"/>
      </div>
    </div>

  </div>
</body>
</html>
