<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=.50">
<title>Muzamil Portfolio</title>

<!-- Google Fonts -->
<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600;800&display=swap" rel="stylesheet">

<style>
  /* Fullscreen video background */
  #bgVideo {
    position: fixed;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    object-fit: cover;
    z-index: ;
  }

  /* Overlay with blur */
  #overlay {
    position: fixed;
    top:0;
    left:0;
    width:100%;
    height:100%;
    background: rgba(0,0,0,0.5);
    backdrop-filter: (5px);
    z-index: -1;
  }

  body {
    margin: 0;
    font-family: 'Poppins', sans-serif;
    color: yellow;
  }

  /* Content container */
  .content {
    position: relative;
    z-index: -0;
    max-width: 1000px;
    margin: auto;
    padding: 10px;
    text-align: center;
    top: 25%;
  }

  /* Headings */
  h1 {
    font-size: 4rem;
    font-weight: 800;
    margin-bottom: 0.5rem;
    text-transform: uppercase;
    text-shadow: 3px 3px 15px rgba(0,0,0,0.7);
  }

  h3 {
    font-size: 1.8rem;
    font-weight: 600;
    margin-bottom: 2rem;
    text-shadow: 2px 2px 10px rgba(0,0,0,0.6);
    font-style: italic;
  }

  /* Buttons */
  .btn {
    display: inline-block;
    margin: 10px;
    padding: 14px 35px;
    font-size: 1.1rem;
    font-weight: 600;
    text-decoration: none;
    border-radius: 50px;
    background: linear-gradient(135deg, #25D366, #128C7E); /* WhatsApp style */
    color: white;
    border: 2px solid transparent;
    transition: 0.4s;
    box-shadow: 0 8px 15px rgba(0,0,0,0.3);
  }

  .btn.instagram {
    background: linear-gradient(135deg, #E4405F, #C13584);
  }

  .btn:hover {
    transform: translateY(-3px) scale(1.05);
    box-shadow: 0 12px 20px rgba(0,0,0,0.5);
  }

  /* Paragraphs and lists */
  p, li {
    line-height: 1.6;
    text-shadow: 1px 1px 8px rgba(0,0,0,0.6);
    font-weight: 400;
  }

  ul {
    list-style: none;
    padding-left: 0;
  }

  li::before {
    content: "💻 "; /* Emoji bullet */
  }

  /* Center images */
  img {
    display: block;
    margin: 20px auto;
    border-radius: 15px;
  }

  /* Responsive text */
  @media (max-width: 768px) {
    h1 { font-size: 2.5rem; }
    h3 { font-size: 1.2rem; }
    .btn { padding: 12px 28px; font-size: 1rem; }
  }
</style>
</head>
<body>

<!-- Background Video -->
<video autoplay muted loop id="bgVideo">
  <source src="https://res.cloudinary.com/dxjkbpmgm/video/upload/v1773707119/A_smooth_cinematic_3d_transition_0882774980_gq9ke4.mp4" type="video/mp4">
  Your browser does not support HTML5 video.
</video>

<!-- Overlay -->
<div id="overlay"></div>

<!-- Content -->
<div class="content">
  <h1>Hi 👋, I'm Muzamil Meer</h1>
  <h3>💻 aka Muzamil — Developer | Dreamer | Doer ✨</h3>

  <!-- Stylish Buttons -->
  <p>
    <a href="https://wa.me/919103594759?text=i%20hire%20you" target="_blank" class="btn"> Hire Me</a>
    <a href="https://www.instagram.com/software_developer_bandipora" target="_blank" class="btn instagram">Instagram Follow</a>
  </p>

  <p>🌐 <a href="https://muzamilmeerdev.github.io/e-commerce/" class="btn">My Portfolio Website</a></p>

  <p>MEMBER OF ICC INDIA CYBER CLUB</p>
  <ul>
    <li>Currently building:<br>
 Python tools, Termux CLI tools, Web Dev projects</li>
    <li>BCA 3rd Semester student, growing every line of code at a time</li>
    <li>Ask me about GitHub, Python, Termux, Automation & Productivity</li>
    <li>Obsessed with learning, shipping & solving real-world problems</li>
    <li>Life balance = Code + College + Caffeine ☕</li>
    <li>Goal: Work at Google or Microsoft 🔮</li>
  </ul>

  <!-- GIF / Image -->

</div>

</body>
</html>
