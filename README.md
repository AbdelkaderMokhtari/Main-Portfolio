<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Abdelkader Mokhtari | Portfolio</title>
<link rel="stylesheet" href="style2.css">
<link href='https://unpkg.com/boxicons@2.1.4/css/boxicons.min.css' rel='stylesheet'>
</head>
<body>
<header>
    <div class="hero">
    <img src="mokhtari.jpg" alt="Abdelkader Mokhtari" class="profilepic">
    <h1>Abdelkader Mokhtari</h1>
    <p>Full Stack Developer & UI/UX Enthusiast</p>
    <a href=""><i class='bx bxl-github'></i></a>
    <a href=""><i class='bx bxl-twitter'></i></a>
    <a href=""><i class='bx bxl-linkedin' ></i></a>
    </div>
</header>

<section id="skills" class="container">
    <h2 class="socend">Skills & Expertise</h2>
    <div class="skills-group">
    <div>
        <h3>Frontend</h3>
        <li>
            <h2>HTML/CSSh2 <h2 class="test">95%</h2></h2>
            <span class="bar"><span class="html"></span></span>
        </li>
        <li>
            <h2 class="h">JavaScript <h2 class="test">90%</h2></h2>
            <span class="bar"><span class="js"></span></span>
        </li>
    </div>
    <div>
        <h3 style="color: #6200ea;">Backend</h3>
        <li>
            <h2 class="h">Node.js <h2 class="test">85%</h2></h2>
            <span class="bar"><span class="node"></span></span>
        </li>
        <li>
            <h2 class="h">Python <h2 class="test">80%</h2></h2>
            <span class="bar"><span class="py"></span></span>
        </li>
        </div>
    <div>
        <h3 style="color: #4CAF50;">Design</h3>
        <li>
            <h2 class="h">UX/UI <h2 class="test">88%</h2></h2>
            <span class="bar"><span class="ux"></span></span>
        </li>
        <li>
            <h2 class="h">Figma <h2 class="test">85%</h2></h2>
            <span class="bar"><span class="figma"></span></span>
        </li>
        </div>
    </div>
</section>

<section id="projects" class="container">
    <h2 class="socend">Featured Projects</h2>
    <div class="projects">
        <div class="project">
            <img src="tt.png" alt="E-commerce Platform Image" class="project-img">
            <h3>E-commerce Platform</h3>
            <p>Full-stack solution with modern UI and secure payments.</p>
            <span style="background: #4caf4f81;">React</span><span style="background: #6200ea8e;">Node.js</span>
            <span style="background-color: rgba(0, 255, 255, 0.463);">MongoDB</span>
        </div>
        <div class="project">
            <img src="aa.png" alt="Task Management App Image" class="project-img">
            <h3>Task Management App</h3>
            <p>Collaborative tool with real-time updates.</p>
            <span style="background: #4caf4f81;">Vue.js</span><span style="background: #6200ea8e;">Firebase</span>
            <span style="background-color: rgba(0, 255, 255, 0.463);">Tailwind CSS</span>
        </div>
        <div class="project">
            <img src="mm.png" alt="AI Chat Assistant Image" class="project-img">
            <h3>AI Chat Assistant</h3>
            <p>Intelligent chatbot for customer support.</p>
            <span style="background: #4caf4f81;">Python</span><span  style="background: #6200ea8e;">Flask</span>
            <span style="background-color: rgba(0, 255, 255, 0.463);">TensorFlow</span>
        </div>
    </div>
</section>


<section id="contact" class="container">
    <h2 class="socend two">Get in Touch</h2>
    <form>
    <input type="text" placeholder="Name" required>
    <input type="email" placeholder="Email" required>
    <textarea placeholder="Your Message" rows="5" required></textarea>
    <button type="submit">Send</button>
    </form>
</section>

<footer>
    <p>© 2025 Abdelkader Mokhtari</p>
</footer>
</body>
</html>





/* General Reset */
body, h1, h2, p, input, textarea, button {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
  }
  
  body {
    font-family: 'Arial', sans-serif;
    background: #f9fafc;
    color: #333;
    line-height: 1.6;
    padding: 10px;
  }
  
  /* Header */
  .hero {
    background: #6200ea;
    color: white;
    text-align: center;
    padding: 50px 20px;
    position: relative;
  }
  .bx{
      color: white;
      font-size: 22px;
      padding-top: 10px;
  }
  .bx:hover{
      color: rgba(255, 255, 255, 0.68);
  }
  .hero .profilepic {
    width: 200px;
    height: 200px;
    border-radius: 50%;
    border: 4px solid white;
    margin-bottom: 15px;
    object-fit: cover;
  }
  .hero h1 {
    font-size: 2.2rem;
    margin-bottom: 10px;
  }
  .hero p {
    font-size: 1rem;
  }
  
  /* Section */
  .container {
    max-width: 800px;
    margin: 20px auto;
    padding: 20px;
  }
  
  /* Skills */
  .skills{
    width: 500px;
    margin: 60px auto;
    padding: #fff;
    box-shadow: 0 14px 28px rgba(0, 0, 0, 0.25), 0 10px 10px rgba(0, 0, b0, 0.22);
  }
.skills li{
    margin: 20px 0;
    padding: 10px;
}
.skills-group .bar{
    background: #353b48;
    display: block;
    height: 20px;
    margin: 5px;
    border: 1px solid rgba(0, 0, o, 0.3);
    border-radius: 10px;
    overflow: hidden;
    box-shadow: 0 1px 3px rgba(0, 0, 0, 0.25), 0 1px 2px rgba(0, 0, b0, 0.22);
    transition: all0.3s cubic-bezier(.25,.8,.25,1);
}
.skills-group li{
    list-style: none;
}
.skills-group div h3{
    font-size: 20px;
    padding-bottom: 15px;
}
.skills-group div h2{
    font-size: 16px;
    color: #353b48;
}
.bar:hover{
    box-shadow: 5px 5px 5px 6px #94a1bc75;
}
.bar span{
    height: 20px;
    float: left;
}
.bar .html{
    background: #3776AB;
}
.bar .js{
    background: #3776AB;
}
.bar .node{
    background: #6200ea;
}
.bar .ux{
    background: #4CAF50;
}
.bar .py{
    background: #6200ea;
}
.bar .figma{
    background: #4CAF50;
}
.html{
    width: 95%;
    animation: span 2.2s;
}
@keyframes span{
  0%{
    width: 0%;
  }
  100%{
    width: 95%;
  }
}
.js{
    width: 90%;
    animation: span 2.2s;
}
@keyframes span{
  0%{
    width: 0%;
  }
  100%{
    width: 90%;
  }
}
.ux{
    width: 88%;
    animation: span 2.2s;
}
@keyframes span{
  0%{
    width: 0%;
  }
  100%{
    width: 88%;
  }
}
.figma{
    width: 85%;
    animation: span 2.2s;
}
@keyframes span{
  0%{
    width: 0%;
  }
  100%{
    width: 85%;
  }
}
.node{
    width: 85%;
    animation: span 2.2s;
}
@keyframes span{
  0%{
    width: 0%;
  }
  100%{
    width: 85%;
  }
}
.py{
    width: 80%;
    animation: span 2.2s;
}
@keyframes span{
  0%{
    width: 0%;
  }
  100%{
    width: 80%;
  }
}
h2.test{
  padding-right: 285px;
  animation: h2 2.5s;
}
@keyframes h2{
  0%{
    opacity: 0;
  }
  100%{
    opacity:100% ;
  }
}
  .skills-group {
    display: flex;
    justify-content: space-around;
    text-align: center;
    gap: 10px;
    flex-wrap: wrap;
  }
  .container div{
    padding: 30px;
  }
  .skills-group div {
    background: #fff;
    margin: 10px;
    border-radius: 5px;
    padding: 15px;
    box-shadow: 0 1px 4px rgba(0, 0, 0, 0.1);
    flex: 1 1 calc(33.333% - 20px);
    margin: 10px 0;
  }
  .skills-group div h3 {
    color: #3776AB;
    margin-bottom: 5px;
  }
h3 .hh {
    color: #6200ea;
  }
  
  /* Skill Bar */
  .skill-bar {
    width: 100%;
    height: 10px;
    background: #ddd;
    border-radius: 5px;
    margin-bottom: 10px;
  }
  .skill-bar div {
    height: 100%;
    border-radius: 5px;
  }
  .skill-html {
    background: #4CAF50;
  }
  .skill-js {
    background: #f0db4f;
  }
  .skill-node {
    background: #68A063;
  }
  .skill-python {
    background: #3776AB;
  }
  .skill-ux {
    background: #ff61a6;
  }
  .skill-figma {
    background: #f24e1e;
  }
  
  /* Percentages */
  .percent {
    font-size: 0.9rem;
    color: #333;
  }
  
  /* Projects */
  .projects {
    display: grid;
    gap: 20px;
  }
  .project {
    background: white;
    padding: 15px;
    border-radius: 5px;
    box-shadow: 0 1px 4px rgba(0, 0, 0, 0.1);
  }

  .project h3 {
    color: #6200ea;
    margin-bottom: 5px;
  }
  .project-img {
    width: 100%;
    height: auto;
    border-radius: 5px;
    margin-bottom: 10px;
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
}
h2.socend{
  padding-left: 30px;
}
  .project span {
    display: inline-block;
    background: #e3f2fd;
    color: #333;
    padding: 2px 8px;
    margin-right: 5px;
    border-radius: 3px;
  }
  
  /* Contact */
  form {
    display: flex;
    flex-direction: column;
    gap: 10px;
  }
  form input, form textarea {
    padding: 10px;
    border: 1px solid #ddd;
    border-radius: 5px;
  }
  form button {
    padding: 10px;
    border: none;
    background: #6200ea;
    color: white;
    font-weight: bold;
    border-radius: 5px;
    cursor: pointer;
  }
  form button:hover {
    background: #3700b3;
  }
  h2.two{
    padding-bottom: 20px;
    padding-left: 300px;
  }
  /* Footer */
  footer {
    text-align: center;
    padding: 10px;
    background: #6200ea;
    color: white;
  }
  
  /* Responsive Design */
  @media (max-width: 768px) {
    .hero h1 {
      font-size: 1.8rem;
    }
    .hero p {
      font-size: 0.9rem;
    }
    .skills-group {
      flex-wrap: wrap;
    }
    .skills-group div {
      flex: 1 1 100%;
    }
    .project {
      padding: 10px;
    }
    form input, form textarea {
      font-size: 0.9rem;
    }
  }
 /* Responsive Design */

/* For devices with a maximum width of 768px */
@media (max-width: 768px) {
  .hero h1 {
    font-size: 1.8rem;
  }
  .hero p {
    font-size: 1rem;
  }
  .profilepic{
    width: 100PX;
    height: 100px;
  }
  .skills-group {
    flex-wrap: wrap;
  }
  .skills-group div {
    flex: 1 1 100%; /* Skills take full width on smaller screens */
    margin: 10px 0;
  }
  .project {
    padding: 10px;
  }
  form input, form textarea {
    font-size: 0.9rem;
  }
  h2.socend {
    text-align: center;
  }
  h2.two {
    text-align: center;
  }
}

/* For devices with a maximum width of 480px */
@media (max-width: 480px) {
  .hero h1 {
    font-size: 1.5rem;
  }
  .hero p {
    font-size: 0.8rem;
  }
  .profilepic {
    width: 80px;
    height: 80px;
  }
  .skills-group div {
    padding: 10px;
  }
  .container{
    padding-right: ;
  }
  .skills-group div h3 {
    font-size: 1.2rem;
  }
  .project h3 {
    font-size: 1rem;
  }
  form input, form textarea {
    font-size: 0.8rem;
  }
  footer p {
    font-size: 0.8rem;
  }
}

/* General Flexibility for Images and Containers */
.project-img, .profilepic {
  max-width: 100%;
  height: auto;
}
.container {
  padding: 10px;
}
