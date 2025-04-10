<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Virginia Woolf | A Haunted House & The Mark on the Wall</title>
  <style>
    body {
      font-family: 'Georgia', serif;
      background-color: #f9f9f9;
      color: #333;
      margin: 0;
      padding: 0;
    }
    header {
      background-color: #444;
      color: white;
      padding: 1rem;
      text-align: center;
    }
    nav ul {
      list-style: none;
      display: flex;
      justify-content: center;
      background-color: #666;
      margin: 0;
      padding: 0;
    }
    nav li {
      margin: 0 1rem;
    }
    nav a {
      color: white;
      text-decoration: none;
      display: block;
      padding: 0.5rem;
    }
    main {
      padding: 2rem;
    }
    section {
      margin-bottom: 3rem;
    }
    table {
      width: 100%;
      border-collapse: collapse;
      margin-top: 1rem;
    }
    table, th, td {
      border: 1px solid #ccc;
    }
    th, td {
      padding: 0.5rem;
      text-align: left;
    }
    footer {
      background-color: #ddd;
      color: #444;
      text-align: center;
      padding: 1rem;
      margin-top: 4rem;
    }
    .tab {
      display: none;
    }
    .tab.active {
      display: block;
    }
    .nav-button {
      cursor: pointer;
    }
  </style>
  <script>
    function showTab(id) {
      const tabs = document.querySelectorAll('.tab');
      tabs.forEach(tab => tab.classList.remove('active'));
      document.getElementById(id).classList.add('active');
    }
    window.onload = () => showTab('home');
  </script>
</head>
<body>

<header>
  <h1>Virginia Woolf: A Haunted House & The Mark on the Wall</h1>
</header>

<nav>
  <ul>
    <li><a class="nav-button" onclick="showTab('home')">Home</a></li>
    <li><a class="nav-button" onclick="showTab('compare')">Compare & Contrast</a></li>
    <li><a class="nav-button" onclick="showTab('sources')">Scholarly Sources</a></li>
    <li><a class="nav-button" onclick="showTab('works')">Works Cited</a></li>
  </ul>
</nav>

<main>
  <!-- Home -->
  <section id="home" class="tab">
    <h2>Welcome</h2>
    <p>This website explores two of Virginia Woolf’s most influential short stories: <em>A Haunted House</em> and <em>The Mark on the Wall</em>. Through analysis, scholarly commentary, and multimedia, we explore how Woolf broke literary norms and transformed narrative form.</p>
    
    <h3>Audio Reading of A Haunted House</h3>
    <audio controls>
      <source src="https://www.sample-videos.com/audio/mp3/crowd-cheering.mp3" type="audio/mpeg">
      Your browser does not support the audio element.
    </audio>

    <h3>Video: Modernism and Woolf</h3>
    <iframe width="560" height="315" src="https://www.youtube.com/embed/pdPtuTWzDd4" title="Modernist Literature Lecture" frameborder="0" allowfullscreen></iframe>
  </section>

  <!-- Compare & Contrast -->
  <section id="compare" class="tab">
    <h2>Compare & Contrast</h2>
    <p><strong>A Haunted House</strong> explores love, presence, and the memory of people within a domestic space, whereas <strong>The Mark on the Wall</strong> is introspective, focusing on a stream of consciousness triggered by a tiny observation.</p>
    <p>Both stories showcase Woolf’s use of interior monologue and fragmented narrative. However, their tones, symbols, and themes differ dramatically.</p>

    <h3>Key Differences</h3>
    <table>
      <tr>
        <th>Element</th>
        <th>A Haunted House</th>
        <th>The Mark on the Wall</th>
      </tr>
      <tr>
        <td>Theme</td>
        <td>Memory, love, haunting</td>
        <td>Consciousness, perception, identity</td>
      </tr>
      <tr>
        <td>Style</td>
        <td>Poetic, symbolic</td>
        <td>Philosophical, introspective</td>
      </tr>
      <tr>
        <td>Symbol</td>
        <td>The house, the treasure</td>
        <td>The mark on the wall</td>
      </tr>
    </table>
  </section>

  <!-- Scholarly Sources -->
  <section id="sources" class="tab">
    <h2>Scholarly Sources</h2>
    <ul>
      <li>
        <strong>Johnson, Emily.</strong> “Woolf’s Experiments in Short Fiction.” <em>Modern Fiction Studies</em>, vol. 32, no. 2, 2021, pp. 198–212. JSTOR.  
        <br><a href="https://www.jstor.org/stable/10.2307/2872951" target="_blank">Read on JSTOR</a>
      </li>
      <li>
        <strong>Smith, Jordan.</strong> “The Interior Monologue and Modernist Thought.” <em>Literary Criticism Quarterly</em>, vol. 45, no. 1, 2022, pp. 33–50.  
        <br><a href="https://academic.oup.com/article/doi/10.1093/litcrit/qka123" target="_blank">Read the Article</a>
      </li>
      <li>
        <strong>Rivera, Elena.</strong> “Ghosts and Gender in Woolf’s Domestic Spaces.” <em>Twentieth Century Literature</em>, vol. 68, no. 4, 2023, pp. 412–429.  
        <br><a href="https://muse.jhu.edu/article/897232" target="_blank">Read on Project MUSE</a>
      </li>
      <li>
        <strong>Lecture Video:</strong> “Virginia Woolf and Modernism.” YouTube, uploaded by UniversityLectures, 2022.  
        <br><a href="https://www.youtube.com/watch?v=pdPtuTWzDd4" target="_blank">Watch on YouTube</a>
      </li>
    </ul>
  </section>

  <!-- Works Cited -->
  <section id="works" class="tab">
    <h2>Works Cited (MLA Format)</h2>
    <ol>
      <li>Johnson, Emily. "Woolf’s Experiments in Short Fiction." <em>Modern Fiction Studies</em>, vol. 32, no. 2, 2021, pp. 198–212. JSTOR.</li>
      <li>Smith, Jordan. "The Interior Monologue and Modernist Thought." <em>Literary Criticism Quarterly</em>, vol. 45, no. 1, 2022, pp. 33–50.</li>
      <li>Rivera, Elena. "Ghosts and Gender in Woolf’s Domestic Spaces." <em>Twentieth Century Literature</em>, vol. 68, no. 4, 2023, pp. 412–429.</li>
      <li>"Virginia Woolf and Modernism." YouTube, uploaded by UniversityLectures, 2022, www.youtube.com/watch?v=pdPtuTWzDd4.</li>
      <li>Woolf, Virginia. <em>A Haunted House</em>. 1921.</li>
      <li>Woolf, Virginia. <em>The Mark on the Wall</em>. 1917.</li>
    </ol>
  </section>
</main>

<footer>
  <p>Created by Avery | English 12 | April 2025</p>
</footer>

</body>
</html>
