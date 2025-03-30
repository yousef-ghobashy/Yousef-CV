<!DOCTYPE html><html lang="en">  <head>  
     <meta charset="UTF-8">  
     <meta name="viewport" content="width=device-width, initial-scale=1.0">  
     <title>Yousef Ahmed Ghabashy - CV</title>  
     <style>  
         body {  
             font-family: Arial, sans-serif;  
             background: linear-gradient(to bottom, #E1D4C2, #BEB5A9, #A78D78, #6E473B, #291C0E);  
             color: #291C0E;  
             text-align: center;  
             margin: 0;  
             padding: 0;  
             overflow-x: hidden;  
         }  
         .container {  
             max-width: 800px;  
             margin: 50px auto;  
             padding: 20px;  
             background: rgba(255, 255, 255, 0.8);  
             border-radius: 15px;  
             box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);  
             transition: transform 0.5s ease-in-out, opacity 0.5s ease-in-out;  
         }  
         .profile-img {  
             width: 150px;  
             height: 150px;  
             border-radius: 50%;  
             object-fit: cover;  
             border: 5px solid #6E473B;  
         }  
         h1 {  
             font-size: 24px;  
             margin-top: 10px;  
         }  
         .buttons {  
             margin-top: 20px;  
         }  
         .buttons a {  
             display: inline-block;  
             background: #6E473B;  
             color: white;  
             padding: 10px 20px;  
             text-decoration: none;  
             border-radius: 20px;  
             margin: 5px;  
             transition: transform 0.3s ease, background 0.3s ease;  
         }  
         .buttons a:hover {  
             background: #A78D78;  
             transform: scale(1.1);  
         }  
         .buttons a:active {  
             transform: scale(0.9);  
         }  
         .section {  
             padding: 20px;  
             margin-top: 30px;  
             background: rgba(255, 255, 255, 0.9);  
             border-radius: 10px;  
             opacity: 0;  
             transform: translateX(100%);  
             transition: transform 0.5s ease-in-out, opacity 0.5s ease-in-out;  
         }  
         .contact {  
             margin-top: 30px;  
             padding: 20px;  
             background: #6E473B;  
             color: white;  
             border-radius: 10px;  
         }  
         .contact a {  
             color: #E1D4C2;  
             text-decoration: none;  
             font-weight: bold;  
         }  
         footer {  
             margin-top: 20px;  
             padding: 10px;  
             background: #291C0E;  
             color: white;  
         }  
         .active-section {  
             opacity: 1 !important;  
             transform: translateX(0) !important;  
         }  
     </style>  
 </head>  
 <body>  
     <div class="container">  
         <img src="/storage/E57B-9D9E/Pictures/Galary/IMG_20240302_144244_000.jpg" alt="Profile Picture" class="profile-img">  
         <h1>Yousef Ahmed Ghabashy</h1>  
         <p>Business Information System Student | Shorouk Academy</p>  
         <p>Currently in my third year, I’m proud to have consistently achieved an excellent academic record over the past two years. My passion for technology and business drives me to excel in bridging the gap between these two fields.</p>  
         <div class="buttons">  
             <a href="#experience" onclick="showSection('experience')">Experience</a>  
             <a href="#education" onclick="showSection('education')">Education</a>  
             <a href="#skills" onclick="showSection('skills')">Skills</a>  
             <a href="#contact" onclick="showSection('contact')">Contact</a>  
         </div><div id="experience" class="section">  
         <h2>Experience</h2>  
         <p>As a current student, I am still building my professional experience. However, I am eager to apply my technical skills and knowledge in real-world projects.</p>  
     </div>  <div id="education" class="section">  
     <h2>Education</h2>  
     <p>Business Information System Student | Shorouk Academy</p>  
     <p>Fluent in English | Web Development Certified</p>  
     <p>With fluency in English, I can communicate confidently in diverse environments. I hold two certificates in web development, which have equipped me with essential web-building skills.</p>  
 </div>  
   
 <div id="skills" class="section">  
     <h2>Skills</h2>  
     <p><strong>Technical Skills:</strong> HTML, CSS, C#</p>  
     <p>I’m proficient in HTML, CSS, and C#, giving me the versatility to tackle projects across different areas—from frontend web design to programming tasks.</p>  
     <p>Web Pages Design & Develop Certificate</p>  
     <p>UI/UX Certificate</p>  
 </div>  
   
 <div id="contact" class="section">  
     <h2>Contact</h2>  
     <p>Phone: <a href="tel:+201004065608">+201004065608</a></p>  
     <p>Email: <a href="mailto:yousefshalabi302@gmail.com">yousefshalabi302@gmail.com</a></p>  
 </div>
 
 </div>  <footer>  
     <p>&copy; 2025 Yousef Ahmed Ghabashy. All rights reserved.</p>  
 </footer>  <script>  
     function showSection(sectionId) {  
         const sections = document.querySelectorAll('.section');  
         sections.forEach(section => {  
             section.classList.remove('active-section');  
         });  
         document.getElementById(sectionId).classList.add('active-section');  
     }  
 </script>  </body>  
 </html>
