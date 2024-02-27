### Hi there 👋
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
    <link rel="stylesheet" media="screen and (max-width:800px)" href="tablet.css">
    <link rel="stylesheet" media="screen and (max-width:530px)" href="phone.css">
    <title>Document</title>

    <style>
    *{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}
html{
    scroll-behavior: smooth;
}
.navbar{
    display: flex;
    justify-content: center;
    align-items: center;
    background-color: rgba(0, 0, 0, 0.5);
    position: sticky ;
    top: 0;
}
.navbar ul{
    display: flex;
    list-style: none;
    margin: 20px 0px;
}
.navbar ul li{
    font-family: century;
    font-size: 1.1rem;
    font-weight: bold;
}
.navbar ul li a{
    text-decoration: none;
    color: white;
    padding: 7px 25px;
    transition: all .5s ease;
}
.navbar ul li a:hover{
    background-color: white;
    color: black;
    box-shadow: 0 0 10px white;
}

#home{
    display: flex;
    flex-direction: column;
    background-color: rgba(0, 0, 0, 0.5);
    height: 840px;
    justify-content: center;
    align-items: center;
    color: white;
}
#home::before{
    content: "";
    position: absolute;
    top: 0;
    right: 0;
    background: url('rafi3.jpg') no-repeat center center/cover;
    height: 900px;
    width: 100%;
    z-index: -1;
    opacity:.8;
}
.main{
    display: flex;
    flex-direction: column;
    border: qpx solid white;
    align-items: center;
    position: absolute;
    top: 30%;
    right: 10%;
}
.headings{
    font-family: century;
    font-size: 3rem;
    text-align: center;
    margin: 40px 0px;
}
.btn {
    padding: 10px 35px;
    background-color: transparent;
    border: 1px solid white;
    color: white;
    outline: none;
    transition: .6s ease;
}
.btn:hover{
    cursor: pointer;
    background-color: white;
    color: black;
    box-shadow: 0 0 5px white, 0 0 10px white, 0 0 15px white;
    font-weight: bold;
}
#about{
    display: flex;
    flex-direction: column;
    box-sizing: border-box;
    padding: 20px;
    margin-bottom: 50px;

}
#pic{
    display: flex;
}
#pic img{
    width: 975px;
    height: 600px;
}
#intro{
    display: flex;
    flex-direction: column;
    text-align: justify;
    padding: 20px;

}
#intro h2{
    font-size: 2rem;
    margin-bottom: 20px; 
}
#intro p{
    font-size: larger;
}
#portfolio{
    display: flex;
    flex-direction: column;
    background-color: rgba(0, 0, 0, 0.9);
    color: white;
    align-items: center;
    padding: 20px;
}
.gallery{
    display: flex;
    flex-wrap: wrap;
    justify-content: space-around;
    box-sizing: border-box;
}
.gallery img{
    width: 560px;
    height: 340px;
    margin: 10px;
}
#skills{
    display: flex;
    flex-direction: column;
    padding: 20px;
}
.raw{
    display: flex;
    justify-content: space-around;
    flex-wrap: wrap;
    box-sizing: border-box;
}
.box{
    display: flex;
    flex-direction: column;
    width: 350px;
    height: 450px;
    border: 1px solid black;
    margin:10px;
    align-items: center;
    text-align: justify;
    padding: 10px;
    border-radius: 15px;
    background: linear-gradient(to top,rgb(255,45,45)50%, white 50%);
    background-size: 100% 200%;
    transition: all .7s;
}
.box:hover{
    background-position: left bottom;
    color: white;
    border: none;
    box-shadow: 0 0 20px rgb(255,45,45);
}

.box p{
    font-size: larger;
}
.box img{
    width: 80px;
    height: 80px;
    background-color: white;
    padding: 10px;
}
#contact{
    display: flex;
    flex-direction: column;
    box-sizing: border-box;
    background-color: rgba(0, 0, 0, 0.9);
    color: white;
    padding: 20px;
}
.form{
    display: flex;
    flex-direction: column;
    box-sizing: border-box;
    align-items: center;
    margin: 20px 0px;

}
.input{
    padding: 12px;
    margin: 15px;
    width: 30%;
    border: none;
    outline: none;
}
#msg{
    width: 20%;
    padding: 10px;
    margin: 15px;
    border: none;
    outline: none;

}
#send{
    padding: 10px;
    width: 10%;
    margin: 40px;
    border: none;
    outline: none;
}
#send:hover{
    cursor: pointer; 
    box-shadow: 0 0 10px white;
}
    </style>
    
</head>
<body>
    <nav class="navbar">
    <ul>
        <li><a href="#home">Home</a></li>
        <li><a href="#about">About me</a></li>
        <li><a href="#portfolio">Portfolio</a></li>
        <li><a href="#skills">Skills</a></li>
        <li><a href="#contact">Contact Me</a></li>
    </ul>
    </nav>

    <section id="home">
        <div class="main">
            <h1 class="headings"> I AM <br> MD Anjam Masud Rafi </h1>
            <a href="https://github.com/MDanjammasudrafi"><button class="btn">
               Hire Me 
            </button></a>
        </div>
    </section>
    <section id="about">
        <h1 class="headings">About Me</h1>
        <div id="pic">
        <img src="rafi3.jpg" alt="">
        <div id="intro">
            <h2>MD Anjam Masud Rafi</h2>
            <p>Hi i am Rafi. Thank you so much for taking the time to visit my website. Right now im doing my B.sc in Computer Science & Engieering from Leading University, sylhet. And just started my journey to be a full time web developer. For me web developing is an art. And im traying to become an artist. Thats my portfolio. Hope you will enjoy.</p><br><br>
            <p><b>Birthday:</b> 1 March 2000</p><br>
            <p><b>Phone:</b> 01859282108</p><br>
            <p><b>City:</b> Bangladesh,Sylhet</p><br>
            <p><b>Email:</b> jsrafi999@gmail.com</p><br>
        </div>
        </div>
    </section>
    <section id="portfolio">
        <h1 class="headings">Portfolio</h1>
        <div class="gallery">
            <img src="portfolio1.jpg.png" alt="">
            <img src="portfolio2.jpg.png" alt="">
            <img src="portfolio3.jpg.png" alt="">
            <img src="portfolio4.jpg.png" alt="">
        </div>
    </section>
    <section id="skills">
        <h1 class="headings">Skills</h1>
        <div class="raw">
            <div class="box">
                <img src="java.png" alt="">
                <h1 class="headings">JAVA</h1>
                <p>Java is one of the most important programming language . I have created my 3rd year project by java. Its realy good for creating android based apps.</p>
            </div>
            <div class="box">
                <img src="html.png" alt="">
                <h1 class="headings">HTML</h1>
                <p>HTML is Basic of all Programming Languages. Its lightweight & easy to learn & use. It is supported by al browsers & its the most friendly search engine.  As a new web developer. I have all the basic knowledge of HTML. Now i am Creating my 4th year project a Dynamic Website via Html ,css & js. </p>
            </div>
            <div class="box">
                <img src="css.png" alt="">
                <h1 class="headings">CSS</h1>
                <p>CSS is easy to learn & produces better and cleaner code than applying all those styles directly to the HTML. Now a days css is the new standard. It has greater consistency in design. I always use css with html to create an website</p>
            </div>
        </div>
    </section>
    <section id="contact">
        <h1 class="headings">Contact</h1>
        <form action="" class="form">
            <input type="text" name="name" class="input" placeholder="Enter Your Name">
            <input type="email" name="email" class="input" placeholder="Enter Your Email">
            <textarea name="msg" id="msg" cols="30" rows="10" placeholder="Enter Your Message"></textarea>
            <input type="submit" value="SEND" id="send">
        </form>
    </section>
</body>
</html>

<!--
**jsrafi/jsrafi** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ... js
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
