<!DOCTYPE html>
<html lang="en-us">
<head>
  <title>Jacob Camp</title>
  <meta name="viewport" content="width=device-width,initial-scale=1" >
  <link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Montserrat:wght@700&family=Sora:wght@700&family=Work+Sans:ital,wght@0,400;0,700;1,600&display=swap">
    <link rel="stylesheet" href="https://unpkg.com/@fortawesome/fontawesome-free@6.2.0/css/brands.min.css">
    <link rel="stylesheet" href="https://unpkg.com/@fortawesome/fontawesome-free@6.2.0/css/solid.min.css">
    <link rel="stylesheet" href="https://unpkg.com/@fortawesome/fontawesome-free@6.2.0/css/fontawesome.min.css">

    <link rel="stylesheet" href="style.css">
    <link rel="stylesheet" href="toggle-switch.css">
</head>
<body>
   <header>
      <nav>
        <h1>Jacob Camp</h1>
        <ul>
          <li><a href="https://public.tableau.com/app/profile/jacob.camp2173" target="Blank">Work</a></li>
          <li><a href="https://acrobat.adobe.com/link/track?uri=urn:aaid:scds:US:881ce030-ddb5-3831-a36e-e54a2f70d478" target="Blank">Resume</a></li>
          <li><a href="mailto:jacobcharlescamp@gmail.com">Contact</a></li>

        </ul>
      </nav>
      <div class="controls">
        <label class="toggle-switch">
          Dark Mode
          <input type="checkbox" id="dark-mode-toggle">
          <div class="toggle-switch-border">
            <div class="toggle-switch-dot"></div>
          </div>
        </label>
      </div>
    </header>
 <style>
        .bio {
            display: flex;
            align-items: center;
        }

        .profile-image {
            margin-right: 20px; /* Adjust this value to control the spacing */
            border-radius: 50%; /* Makes the image a perfect circle */
            width: 500px; /* Adjust the width as needed */
            height: auto; /* Maintain aspect ratio */
        }
    </style>
  <section class='bio'>
    <img class='profile-image' src='https://media.licdn.com/dms/image/D4E03AQGs1nKU49af_A/profile-displayphoto-shrink_800_800/0/1694564577740?e=1700092800&v=beta&t=19_evUKXXssu59tN2z-f_o1Vllc5RGTlteNCzsF59D0'/>
    <div>
      <h1>Hello! My name is Jacob Camp. I'm looking at careers in Data Science.</h1>
      <p>
        I've been analyzing data in the commercial real estate market since 2020. In the last year I have been making         visualization projects dove deeper into (Tableau, Power BI, and SQL). In my free time I enjoy golfing and spending time with friends.</p>
      <a class='btn' href='https://public.tableau.com/app/profile/jacob.camp2173' target='blank'> See my work </a>
   </div>
    </section>

    <section class="recent-work">
      <h2>Recent Work</h2>
      <article>
        <div>
          <h3>AirBnB Rental Analysis</h3>
          <p>Analyzing real-world rental data in the New York area.</p>
          <strong>Sep 2023</strong>
          <ul>
            <li>Imported large, complex datasets for text preprocessing</li>
            <li>Analyzed data for positive and negative sentiment using Language Parsing, Word Vectorization, and Topic Modeling</li>
            <li>Generated visualizations from results</li>
          </ul>
          <a href="https://public.tableau.com/views/AirBnB_16947962686620/Dashboard1?:language=en-US&:display_count=n&:origin=viz_share_link" target='Blank'>Tableau Report</a>
        </div>
        <img class="article-img" src="https://as2.ftcdn.net/v2/jpg/00/66/35/83/1000_F_66358333_U8B2xWSWuFhMuB7ffnuBca5UV2l3y3QI.jpg" />
      </article>
      <article>
        <div>
          <h3>Covid-19 Global Impact</h3>
          <p>Data analysis and visualization on the impact and effect of Covid-19 globally from 1/1/2020-8/7/23.</p>
          <strong>Aug 2023</strong>
          <ul>
            <li>Analyzed, cleaned, then plotted data using SQL</li>
            <li>Searched for patterns or themes in data</li>
            <li>Used Tableau to create visuals and communicate findings</li>
          </ul>
          <a href="https://public.tableau.com/app/profile/jacob.camp2173" target='blank'>Tableau Report</a>
          <a href="https://github.com/JacobCamp/PortfolioProjects/blob/main/COVID%20Portfolio%20Project%20SQL%20Scripts.sql" target='blank'>GitHub Report</a>
        </div>
        <img class='article-img' src="https://as1.ftcdn.net/v2/jpg/04/94/44/14/1000_F_494441446_YAqaDxZS37hDkdZcEtfDEaxtoEWCVci8.jpg
"</a>
      </article>
      <article>
        <div>
          <h3>Industrial Real Estate Market Data</h3>
          <p>A PowerBI dashboard that allows principals to evaluate current market trends and make actionable decisions with real time data.</p>
          <strong>July 2023</strong>
          <ul>
            <li>Gathered, organized, and cleaned 3rd party market data from multiple sources to create an accurate dataset.</li>
            <li>Implemented security best practices to authenticate and authorize users</li>
            <li>Created a cache to store frequently requested data</li>
          </ul>
          <a href="https://acrobat.adobe.com/link/review?uri=urn:aaid:scds:US:cbdbd161-836a-3fd9-883b-2cfaf2318305" target="blank"> Static PowerBI Report</a>
        </div>
        <img class="article-img" src="https://as1.ftcdn.net/v2/jpg/05/35/80/56/1000_F_535805635_yyoR4bSIhbRPPd9RWCCnQJdQcD679Exs.jpg" />
      </article>
    </section>

    <footer>
      <ul>
        <li>
          <a href="https://www.linkedin.com/in/jacobcamp5/" target='blank'>
            LinkedIn
            <span class="link-icon">
              <i class="fa-brands fa-linkedin"></i>
            </span>
          </a>
        </li>
        <li>
          <a href="https://docs.google.com/document/d/1DFJNs-ngtqHzUSYW9x7k51AuJAF_P9hjjSRfYK2nH-A/edit" target='blank'>
          <a href="https://github.com/JacobCamp/Portfolio.git" target='blank'>
            GitHub
            <span class="link-icon">
              <i class="fa-brands fa-github"></i>
            </span>
          </a>
        </li>
      </ul>
      <p class="copywright">© 2023 Jacob Camp</p>
    </footer>
    <script src="script.js"></script>
  </body>
</html>
