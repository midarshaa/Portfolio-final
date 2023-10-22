<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Midarsha - Developer Portfolio | Home</title>
    <link rel="stylesheet" href="style.css">
    <link rel="stylesheet" href="script.js">
    <link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Borel&family=Poppins:wght@400;700&family=Ysabeau+SC:wght@300&display=swap" rel="stylesheet">
<link rel="stylesheet" 
href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.2/css/all.min.css">
<link rel="shortcut icon" href="favicon.ico" type="image/x-icon">
  <style>
    * {
  margin: 0;
  padding: 0;
}
body {
  background-color: #0a2647;
  color: white;
  font-family: "Poppins", sans-serif;
}
nav {
  background-color: #144272;
  display: flex;
  justify-content: space-around;
  align-items: center;
  height: 80px;
}
nav ul {
  display: flex;
  justify-content: center;
  list-style: none;
}
nav ul li {
  list-style: none;
  margin: 0 23px;
}
a {
  text-decoration: none;
  color: white;
}
a:hover {
  text-decoration: none;
  color: #559bf5;
  font-size: 1.04rem;
}
.left {
  font-size: 1.5rem;
}
.First {
  display: flex;
  justify-content: space-around;
  margin: 105px 0;
}
.First > div {
  width: 30%;
}
.leftSection {
  position: relative;
  left: 30px;
  top: 20px;
  font-size: 2rem;
  margin: 20px 0;
}
.rightSection img {
  width: 70%;
}
.name {
  color: #559bf5;
}
#element {
  color: #559bf5;
}
main hr {
  border: none;
  background-color: #8abdff;
  height: 0.4px;
  margin: 30px 84px;
}
.secondSection {
  max-width: 80vw;
  margin: auto;
  height: 80vh;
}
.grey {
    color: #2C74B3;
  }
  
.secondSection h1 {
  font-size: 1.8rem;
}
.secondSection .box {
  background-color: white;
  width: 157vh;
  height: 1px;
  margin: 56px 0;
  display: flex;
}
.secondSection .vertical{
    height: 53px;
    width: 1px;
    background-color: white;
    margin: 0 100px;
}
.image-top{
    width: 0px;
    position: relative;
    bottom: 29px;
    right: 17px;
}
.vertical-title{
    width: 150px;
    position: relative;
    top: 45px;
    right: 77px; 
}
.vertical-desc{
    width: 184px;
    position: relative;
    top: 80px;
    right: 75px;
    color:#559bf5;
    text-align: left;
}
.thirdSection{
    max-width: 80vw;
    margin: auto;
    height: 80vh;
    position: relative;
    left: 30px;
}
.about h1{
    font-size:2rem ;
    margin: 30px 40px;
    margin-left: 0;
    margin-top: 0;
}
.aboutMes{
    margin-top: 50px;
    width: 800px;
    line-height: 2;
}
.foot1{
    background-color: #004a8b;
    height:190px;
  display: flex;
  justify-content: space-around;
  align-items: center;
  height: 80px;
}
footer ul {
    display: flex;
    justify-content: center;
    list-style: none;
  }
footer ul li {
    list-style: none;
    margin: 0 23px;
  }
  footer a{
    margin-left: 5px;
  }
  footer a:hover{
    font-size: 1.3rem;
    color: #76c1f2; 
  }
  </style>
</head>
<body>
    <header>
        <nav>
            <div class="left"> Midarsha's Portfolio</div>
            <div class="right">
                <ul>
                   <a href= "#Home"><li> Home</li></a>
                    <a href="#About"><li>About</li></a>
                    <a href="Services"><li>Services</li></a>
                    <a href="#Contact"><li>Contact Me</li></a>
                </ul>

            </div>
        </nav>
    </header>
    <main>
        
        <section class="First" id="Home">
            <div class="leftSection"> 
                Hello, I am <span class="name">Midarsha</span>!    
                <div>I'm a passionated </div>
                <span id="element"></span>

            </div>
            <div class="rightSection">
                <img src="pngitem-girl.png" alt=""> </div>
        </section>
 <hr>

 <section class="thirdSection" id="about">
    <div class="aboutSection">
    <div class="about">
        <span class="grey">My journey Thus Far </span>
        <h1>About</h1>
        <div class="aboutMes">

            Hello, I'm Midarsha, a 17-year-old creator shaping my path in the vibrant world of entrepreneurship. Born and raised in Bangalore, I forged my foundation at Windermere High School, achieving a remarkable 91% in the Board exams.
            
            Driven by my unquenchable thirst for entrepreneurship, I embarked on a break year during my studies at MES PU College. However, I eventually pursued a 3-year Diploma in Computer Science Engineering, guided by family expectations.
            
            From an early age, I envisioned a life of financial freedom, a dream I now chase through my dual roles as a budding entrepreneur and a content creator. My journey is a testament to my unwavering determination, and I'm confident in my success in both arenas.
            
            Beyond my professional pursuits, I'm passionate about the thrill of biking, the finesse of pencil artistry, and the excitement of sports. I'm a skilled athlete in throwball and volleyball, and in 2024, I'm broadening my horizons by delving into martial arts, including boxing and karate. Join me in this exhilarating journey towards a future of financial independence and creative expression.
        </div>
    </div>
    </div>
</section>
<hr>
        <section class="secondSection" >
            <span class="grey">What I have Done so far.</span>
            <h1 id="Services">Experience </h1>
            <div class="box">
                <div class="vertical">
                    <img class="image-top" src="front2.webp" alt="">
                    <div class="vertical-title">
                   Front web developer 2020-present
                    </div>
                    <div class="vertical-desc">
                        As a dedicated school-time Frontend Developer, I blended design and code to create immersive web experiences, igniting my passion for digital innovation.
                    </div>
                </div>
                
                <div class="vertical"><img class="image-top" src="back.png" alt="">
                    <div class="vertical-title">
                    Backend developer 2023-present
                    </div>
                    <div class="vertical-desc">
                        In my college leisure, I immersed myself in Backend Development, crafting resilient digital architectures that marry efficiency, security, and performance.
                    </div></div>


                <div class="vertical"><img class="image-top" src="full.png" alt="">
                    <div class="vertical-title">
                    Full Stack developer 2023-present
                    </div>
                    <div class="vertical-desc">
                        As a versatile Full Stack Developer, I thrive at both ends of the spectrum, creating complete web solutions with a focus on user-centered innovation.
                    </div></div>


                <div class="vertical"><img class="image-top" src="creator.png" alt="">
                    <div class="vertical-title">
                    Content Creator 2024-present
                    </div>
                    <div class="vertical-desc">
                        As a young content creator, I breathe life into ideas, crafting engaging narratives, visuals, and experiences, sharing stories with a fresh perspective.
                    </div></div>


                <div class="vertical"><img class="image-top" src="entre.png" alt="">
                    <div class="vertical-title">
                        Entrepreneur 2024-present
                    </div>
                    <div class="vertical-desc">
                        As a budding entrepreneur, I embrace innovation and determination, paving my way in the business world by turning ideas into thriving ventures."
                    </div></div>
            </div>
        </section>
        <hr>
    </main>
    <footer class="foot1" id="Contact">
       <ul>
        <li> <i class="fa-brands fa-instagram"></i>
             <a href="https://www.instagram.com/justt.midarsha_/?igshid=MzRlODBiNWFlZA%3D%3D" target="_blank">Instagram</a > </li>
            <li>
                <i class="fa-brands fa-linkedin"></i><a href="">LinkedIn</a>
            </li>
        <li>
            <i class="fa-regular fa-envelope"></i> <a href="mailto:midarshaulti876@gmail.com">Email</a>
        </li>
       </ul>
    </footer>
    <script src="https://unpkg.com/typed.js@2.0.16/dist/typed.umd.js"></script>
  <script>
    var typed = new Typed('#element', {
      strings: ['Web Developer.','Graphic Designer.', 'Video Editor.', 'Entrepreneur.'],
      typeSpeed: 50,
    });
  </script>
</body>
</html>
