<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Follow Me</title>
<link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css" rel="stylesheet">
<style>
  * { margin: 0; padding: 0; box-sizing: border-box; }
  body {
    font-family: 'Arial', sans-serif;
    background-color: #0d0d0d;
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
    color: #fff;
  }

  .container {
    text-align: center;
    background: #1a1a1a;
    padding: 40px 30px;
    border-radius: 20px;
    box-shadow: 0 0 25px rgba(255,0,0,0.4);
    transition: transform 0.3s;
  }

  .container:hover { transform: scale(1.02); }

  .profile-pic {
    width: 150px;
    height: 150px;
    border-radius: 50%;
    border: 4px solid #ff0000;
    cursor: pointer;
    transition: transform 0.3s, border-color 0.3s;
  }

  .profile-pic:hover {
    transform: scale(1.1);
    border-color: #ff4d4d;
  }

  .links {
    margin-top: 25px;
    display: none;
    flex-direction: column;
    gap: 15px;
    animation: fadeIn 0.5s forwards;
  }

  @keyframes fadeIn { from { opacity: 0; transform: translateY(20px); } to { opacity: 1; transform: translateY(0); } }

  .link-card {
    display: flex;
    align-items: center;
    justify-content: flex-start;
    gap: 15px;
    padding: 12px 20px;
    border-radius: 12px;
    text-decoration: none;
    color: #fff;
    background: #ff0000;
    font-weight: bold;
    transition: background 0.3s, transform 0.2s, box-shadow 0.3s;
  }

  .link-card i {
    font-size: 1.5rem;
    width: 25px;
  }

  .link-card:hover {
    background: #ff4d4d;
    transform: scale(1.05);
    box-shadow: 0 4px 15px rgba(255, 0, 0, 0.5);
  }

  @media(max-width: 500px) {
    .container { padding: 30px 20px; }
    .profile-pic { width: 120px; height: 120px; }
    .link-card { padding: 10px 15px; font-size: 14px; }
  }
</style>
</head>
<body>

<div class="container">
  <img src="your-pfp.jpg" alt="Profile Picture" class="profile-pic" id="pfp">
  <div class="links" id="links">
    <a href="https://twitter.com/yourusername" target="_blank" class="link-card">
      <i class="fab fa-twitter"></i> Twitter
    </a>
    <a href="https://instagram.com/yourusername" target="_blank" class="link-card">
      <i class="fab fa-instagram"></i> Instagram
    </a>
    <a href="https://twitch.tv/yourusername" target="_blank" class="link-card">
      <i class="fab fa-twitch"></i> Twitch
    </a>
    <a href="https://youtube.com/yourusername" target="_blank" class="link-card">
      <i class="fab fa-youtube"></i> YouTube
    </a>
    <a href="https://discord.com/invite/yourserver" target="_blank" class="link-card">
      <i class="fab fa-discord"></i> Discord
    </a>
  </div>
</div>

<script>
  const pfp = document.getElementById('pfp');
  const links = document.getElementById('links');

  pfp.addEventListener('click', () => {
    links.style.display = links.style.display === 'flex' ? 'none' : 'flex';
  });
</script>
