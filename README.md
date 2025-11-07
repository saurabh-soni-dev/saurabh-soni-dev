<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Saurabh Soni | GitHub Profile</title>

  <style>
    body {
      margin: 0;
      font-family: 'Poppins', sans-serif;
      background-color: #0d1117;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
    }

    .profile-container {
      background-color: #0d1117;
      text-align: center;
      padding: 40px 20px;
      border-radius: 16px;
      box-shadow: 0 0 25px rgba(0, 120, 255, 0.1);
      width: 90%;
      max-width: 450px;
    }

    .profile-container img.profile-pic {
      border-radius: 50%;
      border: 3px solid #0078ff;
      width: 120px;
      height: 120px;
      margin-bottom: 15px;
      transition: transform 0.3s ease;
    }

    .profile-container img.profile-pic:hover {
      transform: scale(1.05);
    }

    .profile-container h1 {
      color: #ffffff;
      margin: 8px 0;
      font-size: 26px;
    }

    .profile-container p.role {
      color: #c9d1d9;
      font-size: 15px;
      margin-bottom: 20px;
    }

    .social-icons {
      display: flex;
      justify-content: center;
      gap: 15px;
      margin-bottom: 15px;
    }

    .social-icons a img {
      width: 30px;
      height: 30px;
      border: 1.5px solid #0078ff;
      border-radius: 50%;
      padding: 5px;
      background-color: #ffffff10;
      transition: all 0.3s ease;
    }

    .social-icons a img:hover {
      transform: scale(1.1);
      background-color: #0078ff33;
    }

    .location {
      color: #c9d1d9;
      font-size: 14px;
      display: flex;
      align-items: center;
      justify-content: center;
      gap: 6px;
    }

    .location img {
      width: 16px;
      height: 16px;
      vertical-align: middle;
    }

    @media (max-width: 480px) {
      .profile-container {
        padding: 30px 15px;
      }

      .profile-container h1 {
        font-size: 22px;
      }

      .profile-container p.role {
        font-size: 13px;
      }

      .social-icons a img {
        width: 26px;
        height: 26px;
      }
    }
  </style>
</head>

<body>
  <div class="profile-container">
    <!-- 👤 Profile Image -->
    <img src="https://avatars.githubusercontent.com/u/00000000?v=4" 
         alt="Saurabh Soni" 
         class="profile-pic" />

    <!-- 💬 Name -->
    <h1>Saurabh Soni</h1>

    <!-- 💻 Role and Tech -->
    <p class="role">
      💼 Software Engineer | ⚛️ React Native | ⚛️ React.js | 🌿 Node.js
    </p>

    <!-- 🌐 Social Icons -->
    <div class="social-icons">
      <a href="https://www.linkedin.com/in/saurabhsoni11" target="_blank">
        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/linkedin/linkedin-original.svg" alt="LinkedIn" />
      </a>
      <a href="https://github.com/saurabh-soni-dev" target="_blank">
        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/github/github-original.svg" alt="GitHub" />
      </a>
      <a href="mailto:saurabhsoni1101@gmail.com">
        <img src="https://cdn-icons-png.flaticon.com/512/732/732200.png" alt="Email" />
      </a>
    </div>

    <!-- 📍 Location -->
    <div class="location">
      <img src="https://cdn-icons-png.flaticon.com/512/535/535239.png" alt="Location" />
      <span>Pune, India</span>
    </div>
  </div>
</body>
</html>
