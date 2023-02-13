<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <meta http-equiv="X-UA-Compatible" content="ie=edge" />
    <title>Graphic Designer Portfolio</title>
    <style>
      /* Add some basic styling for the page */
      body {
        font-family: Arial, sans-serif;
        margin: 0;
        padding: 0;
      }

      .header {
        background-color: lightgray;
        display: flex;
        justify-content: space-between;
        align-items: center;
        padding: 20px;
      }

      .header h1 {
        margin: 0;
        font-size: 36px;
      }

      .header a {
        text-decoration: none;
        color: black;
        font-size: 18px;
      }

      .container {
        max-width: 800px;
        margin: 40px auto;
        padding: 20px;
      }

      .card {
        background-color: white;
        box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        border-radius: 10px;
        overflow: hidden;
        margin-bottom: 40px;
        display: flex;
        flex-direction: column;
      }

      .card img {
        width: 100%;
        height: 200px;
        object-fit: cover;
      }

      .card h2 {
        font-size: 24px;
        margin: 20px;
      }

      .card p {
        font-size: 18px;
        margin: 20px;
      }
    </style>
  </head>
  <body>
    <header class="header">
      <h1>Graphic Designer Portfolio</h1>
      <nav>
        <a href="#about">About</a>
        <a href="#projects">Projects</a>
        <a href="#certifications">Certifications</a>
      </nav>
    </header>
    <div class="container">
      <section id="about">
        <h2>About Me</h2>
        <p>
          Hi, I'm a graphic designer with a passion for creating beautiful and user-friendly designs.
          I have experience in UX/UI design and HTML/CSS development, which allows me to bring my designs to life.
          I'm constantly learning and staying up-to-date with the latest design trends and techniques.
        </p>
      </section>
      <section id="projects">
        <h2>Projects</h2>
        <div class="card">
          <img src="project1.jpg" alt="Project 1" />
          <h2>Project 1</h2>
          <p>
            
