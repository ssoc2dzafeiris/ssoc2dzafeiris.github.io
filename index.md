
<body>
    <style>
  
    html,body{
        background-color: #222222 !important;
        margin: 0;
        padding: 0;
        width: 100%;
        height: 100%;
        color: #F3EFE0;
      }

      div,h1,h2,h3,h4,p{
        padding: 5px 10px;
        margin: 0 auto;
      
      }

      .container{
        position: absolute;
        top: 50%;
        left: 50%;
        transform: translate(-50%,-50%);
        background-color: #434242;
        padding: 40px;
        border-radius: 27px;
      }
      
      .text{
        background: linear-gradient(90deg,#00dbde,#fc00ff);
        font-size: 2.5rem;
        text-transform: uppercase;
        -webkit-background-clip: text;
        -webkit-text-fill-color: transparent;
      }


      a{
        position: relative;
        color: #00dbde;
        text-decoration: none;
        z-index: 100;
        margin: 5px;
        padding: 10px;
        border-radius: 10px;
        margin: 0 auto;
        text-transform: uppercase;
        transition: all 0.26s linear;
        opacity: .7;
      }

      a:hover{
        background: #b905bc;
        color: #F3EFE0;      
        border-bottom: 1px solid #434242;
        z-index: 300;
        opacity: 1;
        
      }

     
      p,span{
        margin: 5px;
        padding: 15px;
        font-size: 1.1rem;
        font-weight: lighter;
        align-items: center;
      }

      footer{
        left: 40%;
        border-top: 2px solid #00dbde;
        border-bottom: 2px solid #00dbde;
        padding: 10px;
        position: absolute;
        bottom: 15px;
        text-align: center;
        width: 20%;
        height: auto;
        color: #00dbde;
      }
     table,tr,td{
      padding: 3px;
      border: 2px solid #ccc;
      text-align: center;
     }
     tr:nth-child(even) {background: #CCC}

</style>
  <div class="container">

    <div>
      <a href="index.html" _target="_blank" title="Back to homepage">🏠 Home</a>
      <a href="#about" _target="_blank" title="About me">🤴 About</a>
      <a href="#contact" _target="_blank" title="Contact me">✉️ Contact</a>
      <a href="#" _target="_blank" title="My projects">💻 Projects</a>
    </div>
    
    <div id="about">
      <h1 class="text">Dimitris Zafeiris</h1>
      <h2>Junior Software Developer</h2>
      <p>Hello, world!!!👋 I am a passionate Junior Software Developer from Greece 🇬🇷.<br/> I have just graduated from Code Bootcamp of PeopleCert Greece, in the sector of Full-stack Software Development. <br/>All the included technologies were HTML,CSS,JavaScript,jQuery,C#,SQL,AngularJS,ReactJS,Git,Scrum <br/>Tools: Visual Studio and Visual studio Code,Postman,Github</p>
    </div>
      <hr/>
    <div id="contact">
      <ul>
        <li><a href="mailto:kremou115@gmail.com">Email</a></li>
        <li><a href="https://www.linkedin.com/in/dimizafe/">LinkedIn</a></li>
        <li><a href="https://github.com/ssoc2dzafeiris/">Github</a></li>
      </ul>
    </div>    
    <hr/>
    <div id="projects">
      <ol>
        <li><a href="#">Project1</a>
        </li>
      </ol>
    </div>    

  </div>
  <footer >Copyright &#169; 2022</footer>
</body>
</html>
