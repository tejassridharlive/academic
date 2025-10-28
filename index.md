<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Tejas Sridhar | Portfolio</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>

<body>

  <!-- ① HAMBURGER MENU GOES HERE -->
  <div class="nav-container">
    <div class="hamburger" onclick="toggleMenu(this)">
      <span></span>
      <span></span>
      <span></span>
    </div>
    <div class="menu" id="menu">
      <a href="/index.html">Home</a>
      <a href="https://medium.com/@tejas-sridhar" target="_blank">Blogs</a>
      <a href="mailto:tejassridhar.acad@gmail.com">Contact</a>
    </div>
  </div>

  <style>
    .nav-container {
      position: fixed;
      top: 10px;
      right: 20px;
      background: transparent;
      z-index: 1000;
    }
    .hamburger {
      cursor: pointer;
      width: 20px;
      height: 14px;
      display: flex;
      flex-direction: column;
      justify-content: space-between;
    }
    .hamburger span {
      height: 3px;
      width: 100%;
      background-color: #004d66;
      border-radius: 2px;
      transition: 0.3s;
    }
    .menu {
      position: absolute;
      top: 35px;
      right: 0;
      background: white;
      border-radius: 8px;
      box-shadow: 0 2px 8px rgba(0,0,0,0.1);
      display: none;
      min-width: 140px;
      text-align: right;
    }
    .menu a {
      display: block;
      padding: 10px 15px;
      color: #004d66;
      text-decoration: none;
      font-family: 'Segoe UI', Arial, sans-serif;
      font-size: 14px;
      border-bottom: 1px solid #eee;
    }
    .menu a:last-child { border-bottom: none; }
    .menu a:hover { background: #f2f9fa; }
    .menu.show { display: block; }
    .hamburger.active span:nth-child(1) { transform: rotate(45deg) translateY(8px); }
    .hamburger.active span:nth-child(2) { opacity: 0; }
    .hamburger.active span:nth-child(3) { transform: rotate(-45deg) translateY(-8px); }
  </style>

  <script>
    function toggleMenu(el) {
      el.classList.toggle('active');
      document.getElementById('menu').classList.toggle('show');
    }
  </script>

<div style="
  position: relative;
  width: 100%;
  max-width: 950px;
  margin: 0 auto 40px auto;
  border-radius: 10px;
  overflow: hidden;
  box-shadow: 0 4px 20px rgba(0,0,0,0.1);
  font-family: 'Segoe UI', Arial, sans-serif;
">

  <!-- Cover Photo -->
  <div style="
    width: 100%;
    height: 220px;
    background-image: url('assets/coverpicture.jpg');
    background-size: cover;
    background-position: center;
    border-bottom: 3px solid #004d66;
  ">
  </div>

  <!-- Profile Info Section -->
  <div style="
    position: relative;
    background: #fff;
    padding: 70px 20px 20px;
    text-align: center;
  ">
    <!-- Profile Photo -->
    <img src="assets/profile.jpg" alt="Profile Picture" style="
      position: absolute;
      top: -70px;
      left: 50%;
      transform: translateX(-50%);
      width: 130px;
      height: 130px;
      border-radius: 50%;
      border: 5px solid #fff;
      object-fit: cover;
      box-shadow: 0 2px 8px rgba(0,0,0,0.2);
    ">

  <h2 style="margin: 0; font-size: 26px; color: #004d66;">Tejas Sridhar</h2>
  <p style="margin: 6px 0 12px; font-size: 16px; color: #333;">
    Senior Data Scientist&nbsp;|&nbsp;Educator&nbsp;|&nbsp;Researcher
  </p>

  <!-- Contact Links -->
  <p style="margin: 0; font-size: 15px;">
    <a href="mailto:tejassridhar.acad@gmail.com" style="color:#004d66; text-decoration:none;">Email</a>
    &nbsp;|&nbsp;
    <a href="https://linkedin.com/in/tejas-sridhar" style="color:#004d66; text-decoration:none;">LinkedIn</a>
    &nbsp;|&nbsp;
    <span style="color:#333;">+1 (385) 212-6841</span>
  </p>
  </div>
</div>

<div style="
  border-left: 6px solid #004d66;
  background: linear-gradient(to right, #f9f9f9, #ffffff);
  padding: 20px 25px;
  margin: 25px 0;
  border-radius: 10px;
  box-shadow: 0 2px 10px rgba(0,0,0,0.1);
">

  <h2 style="color:#004d66; text-align:center; letter-spacing:1px; margin-top:0;">SUMMARY</h2>

  <p style="font-size:15.5px; line-height:1.6; color:#333;">
  <strong>Senior Data Scientist</strong> in the <em>Research & Development</em> team at <strong>Swire Coca-Cola USA</strong> 
  with over <strong>6 years of corporate experience</strong> across analytics, AI, and applied machine learning. 
  Passionate about <strong>teaching and inspiring students</strong> in the fields of data science and business analytics, 
  as evidenced by course development and teaching experience across <strong>North America, Asia, and the Middle East</strong>.
  </p>

  <p style="font-size:15.5px; line-height:1.6; color:#333;">
  Experienced in teaching graduate and executive courses in 
  <strong>Business Analytics, Artificial Intelligence, Machine Learning, Statistics, and Decision Modeling</strong>, 
  with consistently high student evaluations. Capable of designing, developing, and delivering 
  rigorous, industry-relevant courses that integrate real-world case studies and technologies such as 
  <strong>Python, Azure, and Databricks</strong>.
  </p>

  <p style="font-size:15.5px; line-height:1.6; color:#333;">
  Brings extensive applied experience from the <strong>consumer goods, manufacturing, and technology sectors</strong> into the classroom 
  to connect theory with practice and motivate learners to think analytically and creatively.
  </p>

</div>

<!-- EDUCATION SECTION -->
<div style="
  font-family: 'Segoe UI', Arial, sans-serif; 
  color: #333; 
  background: linear-gradient(to right, #ffffff, #f9f9f9);
  padding: 25px 30px; 
  border-radius: 10px; 
  box-shadow: 0 2px 10px rgba(0,0,0,0.1);
  max-width: 900px;
  margin: 0 auto 40px auto;
">

  <h2 style="
    color: #004d66; 
    letter-spacing: 1px; 
    text-align: center; 
    margin-top: 0; 
    margin-bottom: 20px;
  ">
    EDUCATION
  </h2>

  <div style="display: flex; flex-direction: column; gap: 20px;">

  <!-- Entry 1 -->
  <div style="display: flex; justify-content: space-between; align-items: flex-start;">
    <div style="flex: 1;">
      <p style="margin: 0; font-weight: 600;">Master of Science, Business Analytics</p>
      <p style="margin: 4px 0 0; font-style: italic;">University of Utah - David Eccles School of Business</p>
    </div>
    <div style="text-align: right; min-width: 160px;">
      <p style="margin: 0;">Salt Lake City, UT</p>
      <p style="margin: 0;">2023</p>
    </div>
  </div>

  <!-- Entry 2 -->
  <div style="display: flex; justify-content: space-between; align-items: flex-start;">
    <div style="flex: 1;">
      <p style="margin: 0; font-weight: 600;">Faculty Development Program - Case Based Teaching and Research</p>
      <p style="margin: 4px 0 0; font-style: italic;">N. L. Dalmia Institute of Management Studies and Research</p>
    </div>
    <div style="text-align: right; min-width: 160px;">
      <p style="margin: 0;">Mumbai, IN</p>
      <p style="margin: 0;">2023</p>
    </div>
  </div>

  <!-- Entry 3 -->
  <div style="display: flex; justify-content: space-between; align-items: flex-start;">
    <div style="flex: 1;">
      <p style="margin: 0; font-weight: 600;">Integrated Program (E-MBA) in Business Analytics</p>
      <p style="margin: 4px 0 0; font-style: italic;">Indian Institute of Management</p>
    </div>
    <div style="text-align: right; min-width: 160px;">
      <p style="margin: 0;">Indore, IN</p>
      <p style="margin: 0;">2021</p>
    </div>
  </div>

  <!-- Entry 4 -->
  <div style="display: flex; justify-content: space-between; align-items: flex-start;">
    <div style="flex: 1;">
      <p style="margin: 0; font-weight: 600;">Faculty Development Program - Case Based Teaching and Research</p>
      <p style="margin: 4px 0 0; font-style: italic;">Indian Institute of Management</p>
    </div>
    <div style="text-align: right; min-width: 160px;">
      <p style="margin: 0;">Indore, IN</p>
      <p style="margin: 0;">2020</p>
    </div>
  </div>

  <!-- Entry 5 -->
  <div style="display: flex; justify-content: space-between; align-items: flex-start;">
    <div style="flex: 1;">
      <p style="margin: 0; font-weight: 600;">Management Development Program - Marketing Analytics</p>
      <p style="margin: 4px 0 0; font-style: italic;">Symbiosis Institute of Business Management</p>
    </div>
    <div style="text-align: right; min-width: 160px;">
      <p style="margin: 0;">Pune, IN</p>
      <p style="margin: 0;">2019</p>
    </div>
  </div>

  <!-- Entry 6 -->
  <div style="display: flex; justify-content: space-between; align-items: flex-start;">
    <div style="flex: 1;">
      <p style="margin: 0; font-weight: 600;">Postgraduate Program in Data Science and Entrepreneurship</p>
      <p style="margin: 4px 0 0; font-style: italic;">Indian School of Management and Entrepreneurship</p>
      <p style="margin: 4px 0 0;">Awards and Recognition: Emerging Leader Award, Valedictorian</p>
    </div>
    <div style="text-align: right; min-width: 160px;">
      <p style="margin: 0;">Mumbai, IN</p>
      <p style="margin: 0;">2019</p>
    </div>
  </div>

  <!-- Entry 7 -->
  <div style="display: flex; justify-content: space-between; align-items: flex-start;">
    <div style="flex: 1;">
      <p style="margin: 0; font-weight: 600;">Bachelor of Business Administration - Business and Quantitative Economics</p>
      <p style="margin: 4px 0 0; font-style: italic;">University of Mumbai</p>
      <p style="margin: 4px 0 0;">Thesis: <em>Corporate Governance for PII in Digital Marketing Practices</em></p>
      <p style="margin: 4px 0 0;">Advisor: Dr. Rinkesh Chheda</p>
    </div>
    <div style="text-align: right; min-width: 160px;">
      <p style="margin: 0;">Mumbai, IN</p>
      <p style="margin: 0;">2018</p>
    </div>
  </div>
  </div>
</div>


<!-- PROFESSIONAL CERTIFICATIONS SECTION -->
<div style="
  font-family: 'Segoe UI', Arial, sans-serif; 
  color: #333; 
  background: linear-gradient(to right, #ffffff, #f9f9f9);
  padding: 25px 30px; 
  border-radius: 10px; 
  box-shadow: 0 2px 10px rgba(0,0,0,0.1);
  max-width: 900px;
  margin: 0 auto 40px auto;
">

  <h2 style="
    color: #004d66; 
    letter-spacing: 1px; 
    text-align: center; 
    margin-top: 0; 
    margin-bottom: 20px;
  ">
    PROFESSIONAL CERTIFICATIONS
  </h2>

  <div style="display: flex; flex-direction: column; gap: 20px;">

  <!-- ITIL -->
  <div style="display: flex; justify-content: space-between; align-items: center;">
    <p style="margin: 0; font-weight: 600;">ITIL 4 Foundation</p>
    <p style="margin: 0;">2025</p>
  </div>

  <!-- Lean Six Sigma -->
  <div style="display: flex; justify-content: space-between; align-items: center;">
    <p style="margin: 0; font-weight: 600;">Lean Six Sigma Green Belt</p>
    <p style="margin: 0;">2019</p>
  </div>

  <!-- CSM -->
  <div style="display: flex; justify-content: space-between; align-items: center;">
    <p style="margin: 0; font-weight: 600;">Certified Scrum Master</p>
    <p style="margin: 0;">2019</p>
  </div>

  </div>
</div>

<!-- ACADEMIC APPOINTMENTS SECTION -->
<div style="
  font-family: 'Segoe UI', Arial, sans-serif; 
  color: #333; 
  background: linear-gradient(to right, #ffffff, #f9f9f9);
  padding: 25px 30px; 
  border-radius: 10px; 
  box-shadow: 0 2px 10px rgba(0,0,0,0.1);
  max-width: 900px;
  margin: 0 auto 40px auto;
">

  <h2 style="
    color: #004d66; 
    letter-spacing: 1px; 
    text-align: center; 
    margin-top: 0; 
    margin-bottom: 25px;
  ">
    ACADEMIC APPOINTMENTS AS INSTRUCTOR OF RECORD
  </h2>

  <div style="display: flex; flex-direction: column; gap: 25px;">

  <!-- Engage7x Consulting -->
  <div style="display: flex; justify-content: space-between; align-items: flex-start;">
    <div style="flex: 1;">
      <p style="margin: 0; font-weight: 600;">Professor – Business Analytics and AI</p>
      <p style="margin: 4px 0 8px; font-style: italic;">Engage7x Consulting</p>
      <ul style="margin: 0 0 0 20px; padding-left: 0;">
        <li>Co-developed and launched a national-level MOOC in Analytics, Data Science, and AI in collaboration with industry leaders in marketing, strategy, and blockchain.</li>
        <li>Designed and co-created curricula with industry partners, integrating applied analytics for finance, marketing, HR, and operations domains.</li>
        <li>Supervised and mentored 150+ research projects and papers, guiding students from India's top business schools.</li>
        <li>Delivered masterclasses and virtual lectures on data mining, statistical research methods, data ethics, and innovation in analytics education.</li>
      </ul>
    </div>
    <div style="text-align: right; min-width: 200px;">
      <p style="margin: 0;">Mumbai, IN (Remote)</p>
      <p style="margin: 0;">April 2020 – Present</p>
    </div>
  </div>

  <!-- NMIMS -->
  <div style="display: flex; justify-content: space-between; align-items: flex-start;">
    <div style="flex: 1;">
      <p style="margin: 0; font-weight: 600;">Visiting Professor – Statistics and Machine Learning</p>
      <p style="margin: 4px 0 8px; font-style: italic;">NMIMS Global Access School</p>
      <ul style="margin: 0 0 0 20px; padding-left: 0;">
        <li>Instructed Executive MBA cohorts in Exploratory Data Analysis, Python, Data Mining, Machine Learning, Advanced Statistics, SQL, Big Data Analytics, Tableau, and Digital Marketing Analytics.</li>
        <li>Designed and facilitated case-based learning modules demonstrating analytics applications in retail and business strategy contexts.</li>
      </ul>
    </div>
    <div style="text-align: right; min-width: 200px;">
      <p style="margin: 0;">Mumbai, IN (Remote)</p>
      <p style="margin: 0;">July 2021 – October 2022</p>
    </div>
  </div>

  <!-- Nuclei Technologies -->
  <div style="display: flex; justify-content: space-between; align-items: flex-start;">
    <div style="flex: 1;">
      <p style="margin: 0; font-weight: 600;">Visiting Lecturer – Microsoft Azure AI and Machine Learning</p>
      <p style="margin: 4px 0 8px; font-style: italic;">Nuclei Technologies</p>
      <ul style="margin: 0 0 0 20px; padding-left: 0;">
        <li>Taught engineering and business cohorts, and corporate clients including Deloitte India and the National Skill Development Corporation (NSDC), on Microsoft Azure and Azure ML Studio.</li>
        <li>Delivered comprehensive training across certification tracks – DP-100 (Data Science on Azure), AI-900 (AI Fundamentals), and AZ-900 (Cloud Fundamentals).</li>
        <li>Developed AI and ML curricula for high school programs, introducing early learners to cloud-based analytics and machine learning concepts.</li>
      </ul>
    </div>
    <div style="text-align: right; min-width: 200px;">
      <p style="margin: 0;">Mumbai, IN (Remote)</p>
      <p style="margin: 0;">September 2020 – December 2021</p>
    </div>
  </div>

  <!-- CATKing Educare -->
  <div style="display: flex; justify-content: space-between; align-items: flex-start;">
    <div style="flex: 1;">
      <p style="margin: 0; font-weight: 600;">Core Faculty – Test Preparation and Admissions Strategy</p>
      <p style="margin: 4px 0 8px; font-style: italic;">CATKing Educare</p>
      <ul style="margin: 0 0 0 20px; padding-left: 0;">
        <li>Developed course plans, teaching schedules, and MBA admissions strategies across six centers, serving 1,200+ students alongside alumni from Harvard Business School and the IIMs.</li>
        <li>Collaborated with faculty from leading business schools and NGOs to design student profile enhancement frameworks for graduate admissions.</li>
        <li>Taught and mentored candidates for exams including CAT, CET, GRE, GMAT, and IELTS, emphasizing reasoning, comprehension, and personalized study methods.</li>
        <li>Led coordination among students, universities, and NGOs, offering tailored mentorship and strategic application guidance.</li>
        <li>Developed dashboards, mock examinations, and lecture modules for GRE preparation and admissions counseling.</li>
        <li>Provided individualized mentorship resulting in 200+ successful admissions to Tier-1 management and technical programs globally.</li>
      </ul>
    </div>
    <div style="text-align: right; min-width: 200px;">
      <p style="margin: 0;">Mumbai, IN</p>
      <p style="margin: 0;">July 2019 – November 2021</p>
    </div>
  </div>

  </div>
</div>




<!-- ACADEMIC APPOINTMENTS AS TEACHING / RESEARCH ASSISTANT -->
<div style="
  font-family: 'Segoe UI', Arial, sans-serif; 
  color: #333; 
  background: linear-gradient(to right, #ffffff, #f9f9f9);
  padding: 25px 30px; 
  border-radius: 10px; 
  box-shadow: 0 2px 10px rgba(0,0,0,0.1);
  max-width: 900px;
  margin: 0 auto 40px auto;
">

  <h2 style="
    color: #004d66; 
    letter-spacing: 1px; 
    text-align: center; 
    margin-top: 0; 
    margin-bottom: 25px;
  ">
    ACADEMIC APPOINTMENTS AS TEACHING / RESEARCH ASSISTANT
  </h2>

  <div style="display: flex; flex-direction: column; gap: 25px;">

  <!-- University of Utah -->
  <div style="display: flex; justify-content: space-between; align-items: flex-start;">
    <div style="flex: 1;">
      <p style="margin: 0; font-weight: 600;">Graduate Teaching Assistant – Frameworks and Decision Models in Management Analytics</p>
      <p style="margin: 4px 0 8px; font-style: italic;">University of Utah – David Eccles School of Business</p>
      <ul style="margin: 0 0 0 20px; padding-left: 0;">
        <li>Supported undergraduate instruction in quantitative modeling, optimization, and data-driven managerial decision-making.</li>
        <li>Facilitated labs, grading, and mentoring for Business major students, reinforcing applied problem-solving using Excel Solver and Python-based analytics.</li>
      </ul>
    </div>
    <div style="text-align: right; min-width: 200px;">
      <p style="margin: 0;">Salt Lake City, UT</p>
      <p style="margin: 0;">January 2022 – May 2022</p>
    </div>
  </div>

  <!-- CATKing Educare (Graduate Teaching Fellow) -->
  <div style="display: flex; justify-content: space-between; align-items: flex-start;">
    <div style="flex: 1;">
      <p style="margin: 0; font-weight: 600;">Graduate Teaching Fellow – Test Preparation and Admissions Strategy</p>
      <p style="margin: 4px 0 8px; font-style: italic;">CATKing Educare</p>
      <ul style="margin: 0 0 0 20px; padding-left: 0;">
        <li>Collaborated with senior faculty in designing instructional materials and refining teaching frameworks for CAT, CET, GRE, and GMAT examinations.</li>
        <li>Assisted in curriculum planning and delivery pilots for verbal reasoning and reading comprehension modules.</li>
        <li>Conducted small-group tutorials and individualized coaching sessions, supporting students in analytical writing and comprehension techniques.</li>
        <li>Participated in faculty coordination meetings to enhance teaching consistency and evaluation practices.</li>
      </ul>
    </div>
    <div style="text-align: right; min-width: 200px;">
      <p style="margin: 0;">Mumbai, IN</p>
      <p style="margin: 0;">June 2019 – July 2019</p>
    </div>
  </div>

  <!-- ISME (Advisor to Economics Society) -->
  <div style="display: flex; justify-content: space-between; align-items: flex-start;">
    <div style="flex: 1;">
      <p style="margin: 0; font-weight: 600;">Advisor to the Economics Society</p>
      <p style="margin: 4px 0 8px; font-style: italic;">Indian School of Management and Entrepreneurship</p>
      <ul style="margin: 0 0 0 20px; padding-left: 0;">
        <li>Advised undergraduate Economics majors in developing student-led research initiatives, case archives, and policy think-tank activities.</li>
        <li>Collaborated with Professor Aditya Kashyap (Centre for Economic Policy) to organize seminars, conventions, and finance-policy outreach programs.</li>
        <li>Led academic simulations analyzing World Economic Forum sessions, national policy shifts, and global economic implications.</li>
        <li>Moderated public discussions on Union Budget analysis and India’s macroeconomic positioning.</li>
      </ul>
    </div>
    <div style="text-align: right; min-width: 200px;">
      <p style="margin: 0;">Mumbai, IN</p>
      <p style="margin: 0;">February 2019 – July 2019</p>
    </div>
  </div>

  <!-- ISME (Marketing Analytics) -->
  <div style="display: flex; justify-content: space-between; align-items: flex-start;">
    <div style="flex: 1;">
      <p style="margin: 0; font-weight: 600;">Graduate Teaching Assistant – Marketing Analytics</p>
      <p style="margin: 4px 0 8px; font-style: italic;">Indian School of Management and Entrepreneurship</p>
      <ul style="margin: 0 0 0 20px; padding-left: 0;">
        <li>Collaborated with Dr. Anshul Gupta (Head, Centre for Business Analytics) to develop and deliver the Marketing Analytics curriculum within the School of Marketing Communications.</li>
        <li>Delivered case-based sessions integrating media analytics, retail strategy, and market research applications.</li>
        <li>Assisted in exam design and evaluation on pricing experiments, data-driven decisions, and RCTs.</li>
        <li>Facilitated a marketing analytics bootcamp for engineering graduates transitioning into MBA programs.</li>
      </ul>
    </div>
    <div style="text-align: right; min-width: 200px;">
      <p style="margin: 0;">Mumbai, IN</p>
      <p style="margin: 0;">October 2018 – June 2019</p>
    </div>
  </div>

  <!-- Egyptian Association for Comprehensive Development -->
  <div style="display: flex; justify-content: space-between; align-items: flex-start;">
    <div style="flex: 1;">
      <p style="margin: 0; font-weight: 600;">Research Associate</p>
      <p style="margin: 4px 0 8px; font-style: italic;">Egyptian Association for Comprehensive Development</p>
      <ul style="margin: 0 0 0 20px; padding-left: 0;">
        <li>Conducted interdisciplinary research on social analytics and human-development indices focused on women's empowerment and entrepreneurship.</li>
        <li>Led a global research team across Japan, Pakistan, the U.S., Turkey, and Australia to produce white papers and economic index models.</li>
        <li>Designed and analyzed RCTs and behavioral-economics models for digital fundraising and engagement campaigns.</li>
        <li>Collaborated with UNDP, British University in Egypt, and Nile University to integrate legal, policy, and economic perspectives in social-equity research.</li>
      </ul>
    </div>
    <div style="text-align: right; min-width: 200px;">
      <p style="margin: 0;">Cairo, EG</p>
      <p style="margin: 0;">December 2017 – February 2018</p>
    </div>
  </div>

  </div>
</div>


<!-- RESEARCH EXPERIENCE / PUBLICATIONS -->
<div style="
  font-family: 'Segoe UI', Arial, sans-serif; 
  color: #333; 
  background: linear-gradient(to right, #ffffff, #f9f9f9);
  padding: 25px 30px; 
  border-radius: 10px; 
  box-shadow: 0 2px 10px rgba(0,0,0,0.1);
  max-width: 900px;
  margin: 0 auto 40px auto;
">

  <h2 style="
    color: #004d66; 
    letter-spacing: 1px; 
    text-align: center; 
    margin-top: 0; 
    margin-bottom: 25px;
  ">
    RESEARCH EXPERIENCE / PUBLICATIONS
  </h2>

  <!-- Manuscripts in Preparation -->
  <div style="margin-bottom: 20px;">
    <h3 style="color:#004d66; font-size:17px; margin-bottom:8px; margin-top:0;">Manuscripts in Preparation</h3>
    <ul style="margin: 0 0 0 20px; padding-left: 0;">
      <li>Agogo, D., &amp; Sridhar, T. (in preparation). <em>Reframing the CRISP-DM Framework: Integrating Modern AI Pipelines for Business Analytics Education.</em> University of Utah, David Eccles School of Business.</li>
    </ul>
  </div>

  <!-- Applied Research -->
  <div style="margin-bottom: 20px;">
    <h3 style="color:#004d66; font-size:17px; margin-bottom:8px; margin-top:0;">Selected Applied Research and Case Studies</h3>
    <ul style="margin: 0 0 0 20px; padding-left: 0;">
      <li>Behavioral Bayesian Modeling in cognitive bias processing in consumer analytics, <strong>2024</strong>.</li>
      <li>Temporal Association Rule Mining in Preventive Maintenance, <strong>2024</strong>.</li>
      <li>Agile frameworks in the context of AI in short-sprint product organizations, <strong>2024</strong>.</li>
    </ul>
  </div>

  <!-- Research Interests -->
  <div>
    <h3 style="color:#004d66; font-size:17px; margin-bottom:8px; margin-top:0;">Research Interests</h3>
    <p style="margin: 0; line-height: 1.6;">
      Applied Machine Learning, Maintenance Analytics, Human-AI Collaboration, Data-Driven Decision-Making, 
      Operations Optimization, and Business Analytics Education.
    </p>
  </div>

</div>


<!-- TEACHING PORTFOLIO -->
<div style="
  font-family: 'Segoe UI', Arial, sans-serif;
  color: #333;
  background: linear-gradient(to right, #ffffff, #f9f9f9);
  padding: 25px 30px;
  border-radius: 10px;
  box-shadow: 0 2px 10px rgba(0,0,0,0.1);
  max-width: 900px;
  margin: 0 auto 40px auto;
">

  <h2 style="
    color: #004d66;
    letter-spacing: 1px;
    text-align: center;
    margin-top: 0;
    margin-bottom: 25px;
  ">
    TEACHING PORTFOLIO
  </h2>

  <!-- Teaching Philosophy -->
  <div style="margin-bottom: 25px;">
    <h3 style="color:#004d66; font-size:17px; margin-bottom:8px;">Teaching Philosophy</h3>
    <p style="margin: 0; line-height: 1.6;">
      My teaching philosophy emphasizes experiential learning through data-driven inquiry, connecting statistical and computational concepts to real-world business contexts. 
      I encourage analytical reasoning, collaboration, and applied experimentation in every course. 
      Analytical thinking in models, as I believe, is the core foundation to design experiments and advance scientific enquiry in any field.
    </p>
  </div>

  <!-- Table of Courses -->
  <div style="margin-bottom: 25px;">
    <h3 style="color:#004d66; font-size:17px; margin-bottom:8px;">Courses Taught Overview</h3>
    <div style="overflow-x: auto;">
      <table style="
        width: 100%;
        border-collapse: collapse;
        font-size: 15px;
        border: none;
      ">
        <thead>
          <tr style="background-color:#004d66; color:#fff; text-align:left;">
            <th style="padding:8px;">Institution</th>
            <th style="padding:8px;">Course</th>
            <th style="padding:8px;">Role</th>
            <th style="padding:8px;">Level</th>
            <th style="padding:8px;">Term</th>
          </tr>
        </thead>
        <tbody>
          <tr><td style="padding:8px;">Engage7x Consulting</td><td style="padding:8px;">Intro To Business Analytics</td><td style="padding:8px;">Professor</td><td style="padding:8px;">Graduate</td><td style="padding:8px;">Fall 2020 – Present</td></tr>
          <tr style="background-color:#f3f3f3;"><td style="padding:8px;">Engage7x Consulting</td><td style="padding:8px;">Intro To Artificial Intelligence</td><td style="padding:8px;">Professor</td><td style="padding:8px;">Graduate</td><td style="padding:8px;">Spring 2025 – Present</td></tr>
          <tr><td style="padding:8px;">University of Utah</td><td style="padding:8px;">Frameworks and Decision Models in Management Analytics</td><td style="padding:8px;">Teaching Assistant</td><td style="padding:8px;">Undergraduate</td><td style="padding:8px;">Spring 2022</td></tr>
          <tr style="background-color:#f3f3f3;"><td style="padding:8px;">NMIMS Global Access School</td><td style="padding:8px;">Exploratory Data Analytics, Big Data, and SQL</td><td style="padding:8px;">Professor</td><td style="padding:8px;">Graduate</td><td style="padding:8px;">Fall 2021 – Spring 2022</td></tr>
          <tr><td style="padding:8px;">NMIMS Global Access School</td><td style="padding:8px;">Business Statistics for Decision Makers</td><td style="padding:8px;">Professor</td><td style="padding:8px;">Graduate</td><td style="padding:8px;">Fall 2021 – Spring 2022</td></tr>
          <tr style="background-color:#f3f3f3;"><td style="padding:8px;">Nuclei Technologies</td><td style="padding:8px;">Microsoft Azure AI and Machine Learning</td><td style="padding:8px;">Professor</td><td style="padding:8px;">Professional</td><td style="padding:8px;">Fall 2020 – Spring 2022</td></tr>
          <tr><td style="padding:8px;">Indian School of Management and Entrepreneurship</td><td style="padding:8px;">Econometrics for Policy</td><td style="padding:8px;">Teaching Assistant</td><td style="padding:8px;">Undergraduate</td><td style="padding:8px;">Fall 2019</td></tr>
          <tr style="background-color:#f3f3f3;"><td style="padding:8px;">Indian School of Management and Entrepreneurship</td><td style="padding:8px;">Intro To Marketing Analytics</td><td style="padding:8px;">Teaching Assistant</td><td style="padding:8px;">Undergraduate</td><td style="padding:8px;">Spring 2019</td></tr>
        </tbody>
      </table>
    </div>
  </div>

  <!-- Detailed Courses -->
  <div style="margin-bottom: 25px;">
    <h3 style="color:#004d66; font-size:17px; margin-bottom:8px;">Detailed Courses Taught</h3>
    <ul style="margin: 0 0 0 20px; padding-left: 0;">
      <li><strong>Intro To Business Analytics (Graduate, Engage7x Consulting, Fall 2020 – Present):</strong> Descriptive and Inferential Statistics, Hypothesis Testing, Machine Learning Methods, Data Mining Methodologies.</li>
      <li><strong>Intro To Artificial Intelligence (Graduate, Engage7x Consulting, Spring 2025 – Present):</strong> LLMs, RAGs, Agents, Neural Networks, LangChain, Model Training and Tuning.</li>
      <li><strong>Frameworks and Decision Models in Management Analytics (Undergraduate, University of Utah, Spring 2022):</strong> Probability, Normal Distribution, Linear Programming, Decision Modeling.</li>
      <li><strong>Exploratory Data Analytics, Big Data, and SQL (Graduate, NMIMS Global, 2021–2022):</strong> SQL, Python, Outlier Detection, Descriptive Statistics, PySpark.</li>
      <li><strong>Business Statistics for Decision Makers (Graduate, NMIMS Global, 2021–2022):</strong> Normal Distributions, Bayesian Statistics, A/B Testing, Inferential Statistics.</li>
      <li><strong>Microsoft Azure AI and Machine Learning (Professional, Nuclei Technologies, 2020–2022):</strong> Azure ML, Azure AI, DP-100, AZ-900, AI-100 Certification Content.</li>
      <li><strong>Econometrics for Policy (Undergraduate, ISME, Fall 2019):</strong> Regression Analysis, OLS, PLS, Causality, Correlation, Hypothesis Testing.</li>
      <li><strong>Intro To Marketing Analytics (Undergraduate, ISME, Spring 2019):</strong> Data Mining, Regression, Classification, Clustering, Probability, Descriptive Statistics.</li>
    </ul>
  </div>

  <!-- Curriculum Innovation -->
  <div style="margin-bottom: 25px;">
    <h3 style="color:#004d66; font-size:17px; margin-bottom:8px;">Curriculum and Pedagogical Innovation</h3>
    <ul style="margin: 0 0 0 20px; padding-left: 0;">
      <li>Developed first-of-its-kind MOOC in Analytics and AI for early-career MBAs.</li>
      <li>Introduced simulation-based learning for Business Decision Making.</li>
      <li>Implemented case-based learning pedagogy for EDA and Machine Learning courses.</li>
    </ul>
  </div>

  <!-- Mentorship -->
  <div style="margin-bottom: 25px;">
    <h3 style="color:#004d66; font-size:17px; margin-bottom:8px;">Mentorship and Advising</h3>
    <ul style="margin: 0 0 0 20px; padding-left: 0;">
      <li>Supervised 150+ research papers and applied analytics projects.</li>
      <li>Advised 200+ students on MBA admissions and case-competition strategy.</li>
    </ul>
  </div>

  <!-- Teaching Effectiveness -->
  <div style="margin-bottom: 25px;">
    <h3 style="color:#004d66; font-size:17px; margin-bottom:8px;">Teaching Effectiveness</h3>
    <p style="margin: 0;">Average teaching evaluation: <strong>4.8/5</strong> across two consecutive semesters (Executive MBA Analytics Cohort, NMIMS).</p>
  </div>

  <!-- Tools and Methods -->
  <div>
    <h3 style="color:#004d66; font-size:17px; margin-bottom:8px;">Teaching Tools and Methods</h3>
    <p style="margin: 0; line-height: 1.6;">
      Python, R, SQL, Power BI, Tableau, Excel Solver, Databricks, Snowflake, Azure ML, Microsoft Power Platform, Streamlit, 
      case-based learning, flipped classrooms, and MOOC platforms.
    </p>
  </div>

</div>


<!-- INVITED TALKS / PANELS / ACADEMIC ENGAGEMENTS (Aligned Version) -->
<div style="
  font-family: 'Segoe UI', Arial, sans-serif;
  color: #333;
  background: linear-gradient(to right, #ffffff, #f9f9f9);
  padding: 25px 30px;
  border-radius: 10px;
  box-shadow: 0 2px 10px rgba(0,0,0,0.1);
  max-width: 900px;
  margin: 0 auto 40px auto;
">

  <h2 style="
    color: #004d66;
    letter-spacing: 1px;
    text-align: center;
    margin-top: 0;
    margin-bottom: 25px;
  ">
    INVITED TALKS / PANELS / ACADEMIC ENGAGEMENTS
  </h2>

  <!-- University of Utah -->
  <div style="margin-bottom: 20px;">
    <p style="margin: 0; font-weight: 600;">University of Utah – David Eccles School of Business</p>
    <table style="width: 100%; border-collapse: collapse; font-size: 15px; margin-top: 6px;">
      <tbody>
        <tr>
          <td style="padding: 4px 8px;">Panelist, <em>“MSBA Incoming Student Orientation”</em></td>
          <td style="text-align: right; padding: 4px 8px;">August 2023</td>
        </tr>
        <tr style="background-color:#f9f9f9;">
          <td style="padding: 4px 8px;">Panelist, <em>“International Students Orientation in MSBA and MSIS”</em></td>
          <td style="text-align: right; padding: 4px 8px;">September 2023</td>
        </tr>
        <tr>
          <td style="padding: 4px 8px;">Panelist, <em>“Data Scientist Industry Perspectives”</em></td>
          <td style="text-align: right; padding: 4px 8px;">March 2025</td>
        </tr>
        <tr style="background-color:#f9f9f9;">
          <td style="padding: 4px 8px;">Guest Speaker, <em>“AI Project Management”</em></td>
          <td style="text-align: right; padding: 4px 8px;">October 2025</td>
        </tr>
      </tbody>
    </table>
  </div>
  <br>
  <!-- Executive Board Member -->
  <div style="display: flex; justify-content: space-between; align-items: flex-start; margin-bottom: 10px;">
    <p style="margin: 0;; font-weight: 600;">Served as Executive Board Member for multiple international Model UN Councils</p>
    <p style="margin: 0; text-align: right; min-width: 200px;; font-weight: 600;">2019 – 2020</p>
  </div>
  <br>
  <!-- MUN Mentor / Adjudicator -->
  <div style="display: flex; justify-content: space-between; align-items: flex-start;">
    <p style="margin: 0;; font-weight: 600;">Regular Mentor and Adjudicator for national and international Model UN and debate events.</p>
    <p style="margin: 0; text-align: right; min-width: 200px;; font-weight: 600;">2018 – 2021</p>
  </div>
  <br>
    <!-- News Debate Panelist -->
  <div style="display: flex; justify-content: space-between; align-items: flex-start;">
    <p style="margin: 0;; font-weight: 600;">Panelist on an online newsroom debate in <em> Hamdard University, Pakistan</em> discussing the verdict of the International Court of Justice on Kulbhushan Jadhav</p>
    <p style="margin: 0; text-align: right; min-width: 200px;; font-weight: 600;">2020</p>
  </div>
  <br>
  <!-- Guest Lecture in International Law -->
  <div style="display: flex; justify-content: space-between; align-items: flex-start;">
    <p style="margin: 0;; font-weight: 600;">Guest lecturer at <em> Sandeep University School of Law, India, </em> on International Law and Foreign Policy.</p>
    <p style="margin: 0; text-align: right; min-width: 200px;; font-weight: 600;">2019</p>
  </div>
</div>


<!-- PROFESSIONAL EXPERIENCE -->
<div style="
  font-family: 'Segoe UI', Arial, sans-serif;
  color: #333;
  background: linear-gradient(to right, #ffffff, #f9f9f9);
  padding: 25px 30px;
  border-radius: 10px;
  box-shadow: 0 2px 10px rgba(0,0,0,0.1);
  max-width: 950px;
  margin: 0 auto 40px auto;
">

  <h2 style="
    color: #004d66;
    letter-spacing: 1px;
    text-align: center;
    margin-top: 0;
    margin-bottom: 25px;
  ">
    PROFESSIONAL EXPERIENCE
  </h2>

  <table style="width:100%; border-collapse:collapse; font-size:15px;">
    <tbody>

  <!-- Senior Data Scientist - R&D -->
  <tr>
    <td style="vertical-align: top; padding: 10px 8px;">
      <p style="margin:0; font-weight:600;">Senior Data Scientist – Research and Development</p>
      <p style="margin:2px 0 6px; font-style:italic;">Swire Coca-Cola USA</p>
      <ul style="margin: 0 0 0 18px; padding-left: 0;">
        <li>Developed and deployed LLM frameworks in Microsoft Azure OpenAI for advanced analytics and automation use cases.</li>
        <li>Co-created an LLM-driven ETL pipeline for procurement invoice processing with the Data Engineering team, improving data structuring and reducing manual intervention.</li>
        <li>Conducted pilot studies in predictive maintenance, testing equipment-asset strategy models for multi-plant scaling.</li>
        <li>Partnered with IT and leadership to define team growth strategy, contributing to onboarding, technical maturity, and project-costing methodologies under the new IT Operating Model.</li>
      </ul>
    </td>
    <td style="vertical-align: top; text-align: right; white-space:nowrap; padding: 10px 8px;">Draper, UT</td>
    <td style="vertical-align: top; text-align: right; white-space:nowrap; padding: 10px 8px;">May 2025 – Present</td>
  </tr>

  <!-- Data Scientist - R&D -->
  <tr style="background-color:#f9f9f9;">
    <td style="padding:10px 8px;">
      <p style="margin:0; font-weight:600;">Data Scientist – Research and Development</p>
      <p style="margin:2px 0 0; font-style:italic;">Swire Coca-Cola USA</p>
    </td>
    <td style="text-align:right; padding:10px 8px;">Draper, UT</td>
    <td style="text-align:right; padding:10px 8px;">July 2024 – May 2025</td>
  </tr>

  <!-- Data Scientist - ERA -->
  <tr>
    <td style="padding:10px 8px;">
      <p style="margin:0; font-weight:600;">Data Scientist – Enterprise Research and Analytics</p>
      <p style="margin:2px 0 0; font-style:italic;">Swire Coca-Cola USA</p>
    </td>
    <td style="text-align:right; padding:10px 8px;">Draper, UT</td>
    <td style="text-align:right; padding:10px 8px;">June 2023 – July 2024</td>
  </tr>

  <!-- Data Science Intern -->
  <tr style="background-color:#f9f9f9;">
    <td style="padding:10px 8px;">
      <p style="margin:0; font-weight:600;">Data Science Intern – Macroeconomics</p>
      <p style="margin:2px 0 0; font-style:italic;">Wheeler Machinery Company (Caterpillar Mining Equipment)</p>
    </td>
    <td style="text-align:right; padding:10px 8px;">Salt Lake City, UT</td>
    <td style="text-align:right; padding:10px 8px;">February 2022 – March 2022</td>
  </tr>

  <!-- Group Head -->
  <tr>
    <td style="padding:10px 8px;">
      <p style="margin:0; font-weight:600;">Group Head – Analytics, Insights and Strategy</p>
      <p style="margin:2px 0 0; font-style:italic;">Kren Martech</p>
    </td>
    <td style="text-align:right; padding:10px 8px;">Mumbai, IN</td>
    <td style="text-align:right; padding:10px 8px;">August 2020 – July 2021</td>
  </tr>

  <!-- Avionics Engineer -->
  <tr style="background-color:#f9f9f9;">
    <td style="padding:10px 8px;">
      <p style="margin:0; font-weight:600;">Avionics Engineer</p>
      <p style="margin:2px 0 0; font-style:italic;">Space Technology and Aeronautical Rocketry</p>
    </td>
    <td style="text-align:right; padding:10px 8px;">Surat, IN</td>
    <td style="text-align:right; padding:10px 8px;">October 2020 – November 2020</td>
  </tr>

  <!-- Senior Data Analyst -->
  <tr>
    <td style="padding:10px 8px;">
      <p style="margin:0; font-weight:600;">Senior Data Analyst</p>
      <p style="margin:2px 0 0; font-style:italic;">WNS Global Services</p>
    </td>
    <td style="text-align:right; padding:10px 8px;">Mumbai, IN</td>
    <td style="text-align:right; padding:10px 8px;">October 2019 – January 2020</td>
  </tr>

  <!-- Client Solutions Engineer -->
  <tr style="background-color:#f9f9f9;">
    <td style="padding:10px 8px;">
      <p style="margin:0; font-weight:600;">Client Solutions Engineer – Martech</p>
      <p style="margin:2px 0 0; font-style:italic;">VMLY&amp;R Asia</p>
    </td>
    <td style="text-align:right; padding:10px 8px;">Mumbai, IN</td>
    <td style="text-align:right; padding:10px 8px;">June 2019 – October 2019</td>
  </tr>

  <!-- Risk Analytics Intern -->
  <tr>
    <td style="padding:10px 8px;">
      <p style="margin:0; font-weight:600;">Risk Analytics Intern</p>
      <p style="margin:2px 0 0; font-style:italic;">TransAsia Risk Advisors</p>
    </td>
    <td style="text-align:right; padding:10px 8px;">Mumbai, IN</td>
    <td style="text-align:right; padding:10px 8px;">April 2019 – June 2019</td>
  </tr>

  <!-- Brand Collaborations Intern -->
  <tr style="background-color:#f9f9f9;">
    <td style="padding:10px 8px;">
      <p style="margin:0; font-weight:600;">Intern – Brand Collaborations</p>
      <p style="margin:2px 0 0; font-style:italic;">The Paperless Postcards Venture Pvt Ltd</p>
    </td>
    <td style="text-align:right; padding:10px 8px;">Mumbai, IN</td>
    <td style="text-align:right; padding:10px 8px;">April 2017 – June 2017</td>
  </tr>

  </tbody>
  </table>
</div>


<!-- TECHNICAL AND ANALYTICAL COMPETENCIES -->
<div style="
  font-family: 'Segoe UI', Arial, sans-serif;
  color: #333;
  background: linear-gradient(to right, #ffffff, #f9f9f9);
  padding: 25px 30px;
  border-radius: 10px;
  box-shadow: 0 2px 10px rgba(0,0,0,0.1);
  max-width: 900px;
  margin: 0 auto 40px auto;
">

  <h2 style="
    color: #004d66;
    letter-spacing: 1px;
    text-align: center;
    margin-top: 0;
    margin-bottom: 25px;
  ">
    TECHNICAL AND ANALYTICAL COMPETENCIES
  </h2>

  <div style="display: flex; flex-direction: column; gap: 16px; font-size: 15px; line-height: 1.6;">

  <!-- Programming -->
  <div>
    <p style="margin: 0; font-weight: 600; color: #004d66;">Programming and Data Analysis</p>
    <p style="margin: 2px 0 0 16px;">
      Python (<em>NumPy, Pandas, Scikit-learn, Statsmodels, Plotly, Matplotlib, Seaborn</em>), 
      R (<em>tidyverse, caret</em>), SQL, PySpark, Databricks Notebooks, Jupyter, Excel.
    </p>
  </div>

  <!-- Machine Learning -->
  <div>
    <p style="margin: 0; font-weight: 600; color: #004d66;">Machine Learning and Statistical Modeling</p>
    <p style="margin: 2px 0 0 16px;">
      Regression and Classification Models, Time-Series Forecasting, Survival Analysis, 
      Crow-AMSAA Reliability Models, Clustering and Segmentation, ANOVA, Hypothesis Testing, 
      NLP, and LLM Applications.
    </p>
  </div>

  <!-- Data Engineering -->
  <div>
    <p style="margin: 0; font-weight: 600; color: #004d66;">Data Engineering and Cloud Platforms</p>
    <p style="margin: 2px 0 0 16px;">
      Microsoft Azure (<em>Azure ML, Blob Storage, OpenAI Service</em>), Azure DevOps, 
      Power Automate, Power BI, Snowflake, Tableau, Streamlit.
    </p>
  </div>

  <!-- Operations -->
  <div>
    <p style="margin: 0; font-weight: 600; color: #004d66;">Operations and Reliability Analytics</p>
    <p style="margin: 2px 0 0 16px;">
      Preventive Maintenance Modeling, MTTR / MTBF / MTBR Analysis, Risk and Safety Analytics, 
      Reliability Growth Modeling, Linear Programming and Process Optimization Frameworks.
    </p>
  </div>

  <!-- Project Management -->
  <div>
    <p style="margin: 0; font-weight: 600; color: #004d66;">Project Management and Methodologies</p>
    <p style="margin: 2px 0 0 16px;">
      Agile, Scrum, Lean Six Sigma (<em>Green Belt Certified</em>), ITIL4 Foundation, 
      Design Thinking, and Change Management.
    </p>
  </div>

  <!-- Business Domain -->
  <div>
    <p style="margin: 0; font-weight: 600; color: #004d66;">Business and Domain Expertise</p>
    <p style="margin: 2px 0 0 16px;">
      Supply Chain and Operations Analytics, Manufacturing Reliability, Safety and Risk Analytics, 
      Marketing Analytics, and Financial Forecasting.
    </p>
  </div>

  <!-- Productivity -->
  <div>
    <p style="margin: 0; font-weight: 600; color: #004d66;">Productivity and Collaboration Tools</p>
    <p style="margin: 2px 0 0 16px;">
      Microsoft 365, PowerPoint (<em>Data Storytelling</em>), GitHub, SharePoint.
    </p>
  </div>

  </div>
</div>


<!-- HONORS AND AWARDS -->
<div style="
  font-family: 'Segoe UI', Arial, sans-serif;
  color: #333;
  background: linear-gradient(to right, #ffffff, #f9f9f9);
  padding: 25px 30px;
  border-radius: 10px;
  box-shadow: 0 2px 10px rgba(0,0,0,0.1);
  max-width: 900px;
  margin: 0 auto 40px auto;
">

  <h2 style="
    color: #004d66;
    letter-spacing: 1px;
    text-align: center;
    margin-top: 0;
    margin-bottom: 25px;
  ">
    HONORS AND AWARDS
  </h2>

  <!-- Academic and Research Honors -->
  <div style="margin-bottom: 20px;">
    <h3 style="color:#004d66; font-size:17px; margin-bottom:8px;">Academic and Research Honors</h3>
    <ul style="margin: 0 0 0 20px; padding-left: 0; line-height: 1.6;">
      <li><strong>Emerging Leader Award (Valedictorian)</strong>, Indian School of Management and Entrepreneurship, 2019</li>
      <li><strong>Youth Leadership Award</strong>, Rotaract Club of Mumbai, 2019</li>
      <li><strong>Academic Excellence Award</strong> as Student Mentor, CATKing Educare, 2018</li>
      <li><strong>National Policy Essay Writing Competition – Winner</strong>, United Nations Information Center for India and Bhutan, 2014</li>
      <li><strong>Intracollegiate Business Case Competition</strong> – Winner (2017); Runner-Up (2016)</li>
      <li><strong>Interstate Science Competition Series – Winner</strong>, Iken Scientifica, 2009</li>
    </ul>
  </div>

  <!-- Literary and Public Speaking -->
  <div>
    <h3 style="color:#004d66; font-size:17px; margin-bottom:8px;">Literary and Public-Speaking Achievements (Selected Highlights)</h3>
    <ul style="margin: 0 0 0 20px; padding-left: 0; line-height: 1.6;">
      <li>Multiple first-place awards in intercollegiate debates, elocutions, and group discussions (2015–2018), including Best Speaker and Best Delegate distinctions.</li>
      <li>Recognized as <strong>Outstanding Delegate</strong> and <strong>Executive Board Member</strong> at National Model United Nations Councils (UNSC, UNHRC, WHO, ECOSOC, SAARC, ICJ).</li>
      <li><strong>Runner-Up</strong>, Dr. Shashi Tharoor Youth Parliament, 2020.</li>
    </ul>
  </div>

</div>


<!-- REFERENCES -->
<div style="
  font-family: 'Segoe UI', Arial, sans-serif;
  color: #333;
  background: linear-gradient(to right, #ffffff, #f9f9f9);
  padding: 25px 30px;
  border-radius: 10px;
  box-shadow: 0 2px 10px rgba(0,0,0,0.1);
  max-width: 900px;
  margin: 0 auto 40px auto;
">

  <h2 style="
    color: #004d66;
    letter-spacing: 1px;
    text-align: center;
    margin-top: 0;
    margin-bottom: 25px;
  ">
    REFERENCES
  </h2>

  <div style="overflow-x: auto;">
    <table style="width: 100%; border-collapse: collapse; font-size: 15px; border: none;">
      <thead style="background-color: white; color: #004d66;">
        <tr>
          <th style="text-align: left; padding: 10px;">Name & Title</th>
          <th style="text-align: left; padding: 10px;">Affiliation</th>
          <th style="text-align: left; padding: 10px;">Contact Information</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td style="padding: 10px; vertical-align: top;">
            <strong>Dr. David Agogo</strong><br>
            Assistant Professor
          </td>
          <td style="padding: 10px; vertical-align: top;">
            David Eccles School of Business,<br>
            University of Utah
          </td>
          <td style="padding: 10px; vertical-align: top;">
            (786) 781-2064<br>
            <a href="mailto:David.agogo@eccles.utah.edu" style="color:#004d66; text-decoration:none;">
              David.agogo@eccles.utah.edu
            </a>
          </td>
        </tr>
      </tbody>
    </table>
  </div>

  <p style="margin-top: 20px; text-align: center; font-style: italic; color: #444;">
    Additional references available upon request.
  </p>
</div>
