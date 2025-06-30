<!DOCTYPE html>
<html lang="en">
<head>
  <!-- ========================= META & TITLE ========================= -->
  <meta charset="UTF-8" />
  <meta http-equiv="X-UA-Compatible" content="IE=edge" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Student Portfolio | [Your Name]</title>

  <!-- ========================= FONTS ========================= -->
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600&display=swap" rel="stylesheet" />

  <!-- ========================= STYLES ========================= -->
  <style>
    :root {
      --primary: #4f46e5; /* indigo-600 */
      --bg: #f9fafb;     /* gray-50  */
      --text: #1f2937;   /* gray-800 */
    }

    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
      font-family: "Poppins", sans-serif;
    }

    body {
      background: var(--bg);
      color: var(--text);
      line-height: 1.6;
    }

    /* ---------- Header ---------- */
    header {
      background: var(--primary);
      color: #fff;
      padding: 1rem 2rem;
      position: sticky;
      top: 0;
      z-index: 1000;
    }

    header nav {
      display: flex;
      justify-content: space-between;
      align-items: center;
      max-width: 960px;
      margin: auto;
    }

    header nav a {
      color: #fff;
      text-decoration: none;
      margin-left: 1rem;
      font-weight: 500;
    }

    header nav a:hover {
      opacity: 0.8;
    }

    /* ---------- Layout Sections ---------- */
    section {
      max-width: 960px;
      margin: 3rem auto;
      padding: 0 1rem;
    }

    /* ---------- Hero ---------- */
    #hero {
      display: flex;
      flex-direction: column;
      align-items: center;
      text-align: center;
      padding: 4rem 1rem;
    }

    #hero h1 {
      font-size: 2.5rem;
      margin-bottom: 1rem;
    }

    #hero p {
      font-size: 1.125rem;
      max-width: 600px;
    }

    .btn {
      display: inline-block;
      margin-top: 2rem;
      padding: 0.75rem 1.5rem;
      background: var(--primary);
      color: #fff;
      border-radius: 0.5rem;
      text-decoration: none;
      font-weight: 600;
    }

    .btn:hover {
      filter: brightness(110%);
    }

    h2 {
      font-size: 1.75rem;
      margin-bottom: 1rem;
      color: var(--primary);
    }

    /* ---------- Grid & Cards ---------- */
    .grid {
      display: grid;
      gap: 1.5rem;
    }

    @media (min-width: 640px) {
      .grid {
        grid-template-columns: repeat(2, 1fr);
      }
    }

    .card {
      background: #fff;
      border-radius: 0.75rem;
      padding: 1.5rem;
      box-shadow: 0 4px 20px rgba(0, 0, 0, 0.05);
    }

    .card h3 {
      margin-bottom: 0.5rem;
      color: var(--primary);
    }

    /* ---------- Footer ---------- */
    footer {
      background: #111;
      color: #ddd;
      text-align: center;
      padding: 2rem;
      margin-top: 3rem;
    }

    footer a {
      color: var(--primary);
      text-decoration: none;
    }
  </style>
</head>
<body>
  <!-- ========================= HEADER ========================= -->
  <header>
    <nav>
      <div class="logo"><strong>[Your Name]</strong></div>
      <div class="links">
        <a href="#about">About</a>
        <a href="#education">Education</a>
        <a href="#projects">Projects</a>
        <a href="#contact">Contact</a>
      </div>
    </nav>
  </header>

  <!-- ========================= HERO ========================= -->
  <section id="hero">
    <h1>Hey, I'm <span style="color: var(--primary)">[Your Name]</span></h1>
    <p>
      A passionate <strong>student</strong> exploring software development and design. <br />
      I love turning ideas into digital experiences.
    </p>
    <a href="#projects" class="btn">See My Work</a>
  </section>

  <!-- ========================= ABOUT ========================= -->
  <section id="about">
    <h2>About Me</h2>
    <p>
