<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Ellen Noda | Data Analysis Portfolio</title>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;800&display=swap" rel="stylesheet" />
  <style>
    body {
      font-family: 'Inter', sans-serif;
      background: #fffafc;
      color: #333;
      margin: 0;
      padding: 0;
    }
    header {
      background-color: #f9dee4;
      padding: 2rem;
      text-align: center;
    }
    header h1 {
      margin: 0;
      font-size: 2.5rem;
      color: #d75c8c;
      display: flex;
      justify-content: center;
      align-items: center;
      gap: 1rem;
    }
    .puzzle-large {
      width: 220px;
      height: auto;
    }
    .section {
      padding: 2rem;
      max-width: 900px;
      margin: auto;
    }
    .section h2 {
      color: #d75c8c;
      font-size: 1.8rem;
      display: flex;
      align-items: center;
      gap: 0.5rem;
    }
    .project h3 {
      color: #d75c8c;
      font-size: 1.4rem;
      margin-top: 2rem;
    }
    iframe {
      width: 100%;
      height: 400px;
      border: none;
      border-radius: 12px;
      box-shadow: 0 4px 16px rgba(0,0,0,0.1);
    }
    .dashboard-img {
      width: 100%;
      border-radius: 12px;
      box-shadow: 0 4px 16px rgba(0,0,0,0.1);
      margin-bottom: 0.5rem;
    }
    .contact {
      background: #d8b6c3;
      text-align: center;
      padding: 2rem;
    }
    .contact a {
      display: inline-block;
      margin: 0.5rem;
      color: #d75c8c;
      text-decoration: none;
      font-weight: 600;
    }
    .intro {
      font-size: 1rem;
      margin-top: 1rem;
      color: #444;
    }
    .background-anim {
      position: fixed;
      top: 0;
      left: 0;
      z-index: -1;
      width: 100vw;
      height: 100vh;
      opacity: 0.2;
    }
    .project p {
      font-size: 1rem;
    }
    .icon {
      height: 64px;
    }
    .coming-soon {
      text-align: center;
      margin-top: 4rem;
    }
    .coming-soon img {
      width: 80px;
      height: auto;
      margin-bottom: 1rem;
    }
    .coming-soon h3 {
      font-size: 1.5rem;
      color: #d75c8c;
      margin-bottom: 0.5rem;
    }
    .coming-soon p {
      font-size: 1rem;
      color: #666;
    }
  </style>
</head>
<body>
  <img class="background-anim" src="https://github.com/ellenoda/data-analysis-portfolio/blob/65853f933598785bf4dae2dc4c5601034ed86538/background.gif?raw=true" alt="Background animation" />

  <header>
    <h1>
      <img class="puzzle-large" src="https://github.com/ellenoda/data-analysis-portfolio/blob/d6940618be42a7f0ad5da9d142f78e65a4d11c38/puzzle-unscreen.gif?raw=true" alt="Puzzle animation" />
      Ellen Noda | Data Analysis Portfolio
    </h1>
  </header>
  <div class="section">
    <h2>🪪 About Me</h2>
    <div class="project">
      <iframe 
        src="https://www.figma.com/embed?embed_host=ellenoda.github.io&url=https://www.figma.com/proto/F79Ln3iR1qJavrQSxtlDKt/Ellen?node-id=13-233&p=f&t=urgp79XY8OasFgw2-1&scaling=contain&content-scaling=fixed&page-id=6%3A2" 
        allowfullscreen
        style="width:100%; height:500px; border:1px solid #ccc; border-radius: 12px;">
      </iframe>
    </div>
  </div>

  <div class="section">
    <h2>🎬 Portfolio Overview</h2>
    <div class="project">
      <iframe src="https://www.youtube.com/embed/NnvfWpUnvJo" title="Portfolio Overview" allowfullscreen></iframe>
      <p class="intro">
        Welcome to my Data Analyst Portfolio! This is a showcase about my journey in data analysis and visualization.<br><br>
        ✅ Data analysis projects using Power BI, Looker Studio, SQL, and Python<br>
        ✅ ETL processes for data transformation and automation<br>
        ✅ Business case studies demonstrating data-driven decision-making
      </p>
    </div>
  </div>

  <div class="section">
    <h2>🧩 Projects</h2>

    <div class="project">
      <h3>💼 Finance Dashboard</h3>
      <img class="dashboard-img" src="https://github.com/ellenoda/data-analysis-portfolio/blob/c7903a7285a7cbfb255ce0643de80ba85454e099/finance-ANIMATION.gif?raw=true" alt="Finance Dashboard" />
      <p><strong>🧠 What I did:</strong> I created a financial dashboard analyzing revenue, expenses, and net profit using Power BI.<br>
         <strong>📈 Outcome:</strong> Clear visualizations to support financial decision-making based on real-time data.<br>
         <a href="https://drive.google.com/file/d/1Me4aUDwu_-nYrVtvWHkeQtvmo7tdczNm/view">📊 Download PBIX</a></p>
    </div>

    <div class="project">
      <h3>🍇 AgroFruits Analytics</h3>
      <img class="dashboard-img" src="https://github.com/ellenoda/data-analysis-portfolio/blob/08dec2367d11025c32241f3fd32fa0ee306b5bd9/agrofruit-ANIMATION.gif?raw=true" alt="Agro Dashboard" />
      <p><strong>🧠 What I did:</strong> I analyzed sales data by harvest, fruit type, and region.<br>
         <strong>📈 Outcome:</strong> Identified the most profitable products and suggested inventory optimizations.<br>
         <a href="https://drive.google.com/file/d/1EXaC9Om9Nypj_OOYdaySfdpfCq33KEeU/view">📊 Download PBIX</a></p>
    </div>

    <div class="project">
      <h3>👥 Employee Turnover (Power BI)</h3>
      <img class="dashboard-img" src="https://github.com/ellenoda/data-analysis-portfolio/blob/bcf5e9e334a891fbf2c5756fa20309704bad6caf/turnover_powerbi-ANIMATION.gif?raw=true" alt="Turnover Dashboard" />
      <p><strong>🧠 What I did:</strong> I modeled employee data to identify turnover rates by department, age group, and tenure.<br>
         <strong>📈 Outcome:</strong> Key insights to reduce resignations and enhance employee retention.<br>
         <a href="https://drive.google.com/file/d/1qDPURrwNEkrySyMPUXCx95eWOA0jZsn3/view">📊 Download PBIX</a></p>
    </div>

    <div class="project">
      <h3>🧭 Candidates Journey (Looker Studio)</h3>
      <img class="dashboard-img" src="https://github.com/ellenoda/data-analysis-portfolio/blob/f10e9a284317fa86251827e1c2093ca5c0533440/soulcode-ANIMATION.gif?raw=true" alt="Candidates Journey" />
      <p><strong>🧠 What I did:</strong> I visualized the complete journey of SoulCode applicants, from application to approval.<br>
         <strong>📈 Outcome:</strong> Full overview with detailed stages to understand process bottlenecks and improve candidate experience.<br>
         <a href="https://lookerstudio.google.com/reporting/cc94f953-4b7c-4073-aa51-5b84f3d349ba">📊 View dashboard</a></p>
    </div>

    <div class="project">
      <h3>📽️ SoulCode Video Presentation in Portuguese</h3>
      <iframe src="https://www.youtube.com/embed/uP_FguBz6xs" title="SoulCode Project" allowfullscreen></iframe>
    </div>

    <div class="project">
      <h3>🧮 Customer Segmentation</h3>
      <img class="dashboard-img" src="https://github.com/ellenoda/data-analysis-portfolio/blob/e106ab24c3bfd3a8d7c17747773bee181659cc53/client-ANIMATION.gif?raw=true" alt="Client Segmentation" />
      <p><strong>🧠 What I did:</strong> I applied RFM (Recency, Frequency, Monetary) analysis to segment customers based on purchase behavior using Google Sheets and Looker Studio.<br>
         <strong>📈 Outcome:</strong> Identified key groups such as Loyal, Potential, and At Risk clients, enabling personalized strategies and boosting retention.<br>
         <a href="https://lookerstudio.google.com/reporting/6a5294c0-8e8c-4d63-9d5e-de8e7b2b137b">📊 View dashboard</a></p>
    </div>

    <div class="project">
      <h3>📺 Customer Segmentation Video (English)</h3>
      <iframe src="https://www.youtube.com/embed/CaE4RWqbOhs" title="Customer Segmentation EN" allowfullscreen></iframe>
    </div>

    <div class="project">
      <h3>📺 Segmentação de Clientes (Portuguese)</h3>
      <iframe src="https://www.youtube.com/embed/IYJ_iQxr9F0" title="Segmentação de Clientes PT" allowfullscreen></iframe>
    </div>
  </div>

  
  <div class="section">
    <h2>🎧 Spotify Streams Analysis</h2>
    <div class="project">
      <img class="dashboard-img" src="https://github.com/ellenoda/data-analysis-portfolio/blob/d2a9c28d48466d4551f5d8a95a4331dd2065cfb7/Spotify_ANIMATION.gif?raw=true" alt="Spotify Dashboard" />
      <img class="dashboard-img" src="https://github.com/ellenoda/data-analysis-portfolio/blob/a6d3baf85fdc2a94c2a6a591c123264d32af104b/Spotify2_ANIMATION.gif?raw=true" alt="Spotify Dashboard 2" />
      <p><strong>🧠 What I did:</strong> I analyzed Spotify data from 2023 to understand how playlists, charts, and sound features affect stream counts.<br>
         <strong>📈 Outcome:</strong> Strategic insights for record labels and new artists based on the impact of features like BPM, speechiness, and instrumentalness.<br>
         <strong>🔧 Tools:</strong> BigQuery, Google Colab, Power BI<br>
         <a href="https://drive.google.com/file/d/1KTBauguz4EUViJuggFjAHwpwFezPweDB/view">📊 Download Power BI file</a></p>
    </div>

    <div class="project">
      <h3>📺 Spotify Analysis Video (English)</h3>
      <iframe src="https://www.youtube.com/embed/DUdmvV8ZlRk" title="Spotify Analysis EN"
        allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
        allowfullscreen>
      </iframe>
    </div>

    <div class="project">
      <h3>📺 Spotify Analysis Video (Portuguese)</h3>
      <iframe src="https://www.youtube.com/embed/lp5Ksffx6ac" title="Spotify Analysis PT"
        allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
        allowfullscreen>
      </iframe>
    </div>
  </div>

  <div class="section">
    <h2><img class="icon" src="https://github.com/ellenoda/data-analysis-portfolio/blob/1c80d8e66b791ea38e123ece5209e5a685c94de8/email-unscreen.gif?raw=true" alt="Email Icon" /> Contact</h2>
    <div class="contact">
      <p><a href="mailto:ellenoda@gmail.com">ellenoda@gmail.com</a></p>
      <p><a href="https://www.linkedin.com/in/ellen-noda">linkedin.com/in/ellen-noda</a></p>
    </div>
  </div>

  <div class="section coming-soon">
    <h3>Coming Soon: More Projects</h3>
    <p>New data adventures are on the way. Stay tuned for fresh insights and visual stories!</p>
  </div>
</body>
</html>



