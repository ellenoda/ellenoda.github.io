<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Ellen Noda | Data Analysis Portfolio</title>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;800&display=swap" rel="stylesheet" />
  <script src="https://unpkg.com/@lottiefiles/lottie-player@latest/dist/lottie-player.js"></script>
  <style>
    body {
      font-family: 'Inter', sans-serif;
      background: #fffafc;
      color: #333;
      margin: 0;
      padding: 0;
    }
    header {
      background-color: #ffdbe8;
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
    .section {
      padding: 2rem;
      max-width: 900px;
      margin: auto;
    }
    .section h2 {
      color: #d75c8c;
      font-size: 1.8rem;
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
      background: #fbe3ee;
      text-align: center;
      padding: 2rem;
    }
    .contact a {
      display: inline-flex;
      align-items: center;
      gap: 0.5rem;
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
  </style>
</head>
<body>
  <lottie-player class="background-anim" src="https://github.com/ellenoda/data-analysis-portfolio/blob/963e07e056231f40cb00fa3a364ba6ab56bcf21a/background-vertical%20-animation.json?raw=true" background="transparent" speed="1" loop autoplay></lottie-player>

  <header>
    <h1>
      <lottie-player src="https://github.com/ellenoda/data-analysis-portfolio/blob/963e07e056231f40cb00fa3a364ba6ab56bcf21a/flower-animation.json?raw=true" background="transparent" speed="1" style="width: 60px; height: 60px;" loop autoplay></lottie-player>
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
      <h3>📽️ SoulCode Video Presentation</h3>
      <iframe src="https://www.youtube.com/embed/uP_FguBz6xs" title="SoulCode Project"
        allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
        allowfullscreen>
      </iframe>
    </div>

    <div class="project">
      <h3>🧮 Customer Segmentation</h3>
      <img class="dashboard-img" src="https://github.com/ellenoda/data-analysis-portfolio/blob/e106ab24c3bfd3a8d7c17747773bee181659cc53/client-ANIMATION.gif" alt="Client Segmentation" />
      <p><strong>🧠 What I did:</strong> I applied RFM (Recency, Frequency, Monetary) analysis to segment customers based on purchase behavior using Google Sheets and Looker Studio.<br>
         <strong>📈 Outcome:</strong> Identified key groups such as Loyal, Potential, and At Risk clients, enabling personalized strategies and boosting retention.<br>
         <a href="https://lookerstudio.google.com/reporting/6a5294c0-8e8c-4d63-9d5e-de8e7b2b137b">📊 View dashboard</a></p>
    </div>

    <div class="project">
      <h3>📺 Customer Segmentation Video (English)</h3>
      <iframe src="https://www.youtube.com/embed/CaE4RWqbOhs" title="Customer Segmentation EN"
        allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
        allowfullscreen>
      </iframe>
    </div>

    <div class="project">
      <h3>📺 Segmentação de Clientes (Português)</h3>
      <iframe src="https://www.youtube.com/embed/IYJ_iQxr9F0" title="Segmentação de Clientes PT"
        allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
        allowfullscreen>
      </iframe>
    </div>
  </div>

   <div class="section">
    <h2>📬 Contact</h2>
    <div class="contact">
      <a href="mailto:ellenoda@gmail.com">
        📧 ellenoda@gmail.com
      </a><br>
      <a href="https://www.linkedin.com/in/ellen-noda">
        <lottie-player src="https://github.com/ellenoda/data-analysis-portfolio/blob/963e07e056231f40cb00fa3a364ba6ab56bcf21a/linkedin-animation.json?raw=true" background="transparent" speed="1" style="width: 24px; height: 24px;" loop autoplay></lottie-player>
        linkedin.com/in/ellen-noda
      </a>
    </div>
  </div>
</body>
</html>
