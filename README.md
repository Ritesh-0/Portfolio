<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        .hero{
            position: relative;
            width: 100%;
            height: 100vh;
            background: rgb(74, 74, 240);
        }
        nav{
            display: flex;
            width: 84%;
            margin: auto;
            padding: 20px 0;
            align-items: center;
            justify-content: space-between;
        }
        nav ul li{
            display: inline-block;
            list-style: none;
            margin: 10px 20px;
        }
        nav ul li{
            text-decoration: none;
            color: black;
            font-weight: bold;
        }
        nav ul li a:hover{
            color: blue;
        }
        .detel{
            margin-left: 8%;
            margin-top: 15;
        }
        .detel h1{
            font-size: 50px;
            color: black;
            margin-bottom: 20px;
        }
        span{
            color: orange;
        }
        .detel p{
            color: #555;
            line-height: 22px;
        }
        .detel a{
            background: #212121;
            padding: 10px 18px;
            text-decoration: none;
            font-weight: bold;
            color: white;
            display: inline-block;
            margin: 30px 0;
            border-radius: 5px;
        }
        .images img{
            height: 35%;
            position: absolute;
            left: 88%;
            bottom: 50%;
            transform: translateX(-50%);
            transition: bottom 1s, left 1s;
        }
        #proficiency{
    width: 100%;
    height: 600px;
    background-color: rgb(255, 255, 255);
    margin-top: 80px;
  }
  #proficiency img{
    float: right;
    width: 50%;
    height: 80%;
  
  }
  
  #proficiency h1{
    font-size: 40px;
    text-align:center;
    color: solid black;
    text-decoration: underline;
  }
  
  #proficiency fieldset{
    width: 47%;
    height: 400px;
    margin-left: 20px;
  
  }
  #proficiency fieldset legend{
    font-size: 30px;
    color: solid RED;
    padding-left: 40px;
    text-align: center;
  }
  #proficiency label{
    font-size: 20px;
  }
  #proficiency input[type=range]{
    width: 60%;
    margin: 20px;
    padding-left: 20px;
    text-align: start;
  }
  
  #flex-container{
    width: 100%;
    height: 600px;
  }
  #flex-container >span{
    font-size: 50px;
    margin-top: 40px;
    margin-left: 80px;
    font-family: Georgia, 'Times New Roman', Times, serif;
    text-decoration: underline red;
  }
  #contact{
    background: rgb(74, 74, 240);
  }

    </style>
</head>
<body>
<div class="hero">
    <nav>
        <img src=" "alt="">
        <ul>
            <li><a href="#">Home</a></li>
            <li><a href="#">About</a></li>
            <li><a href="#">Portfolio</a></li>
            <li><a href="#">Skills</a></li>
            <li><a href="#">Contact</a></li>
        </ul>
    </nav>
    <div class="images">
      <img src="IMG20230514170906.jpg" class="boy">
  </div>
    <div class="detel">
        <h1>I,m Ritesh Kumar</h1>
        <p>This is official portfolio website to showes all Details and work experience of Web Development </p>
    <a href="#">Downlode Resume</a>
    </div>
    <div class="text">
        <p>A passionate Web Developer having an experience of building web application and 
          with HTML/ CSS / Javascript and having an experience of AI+ML and  Python 
          and some other cool libraries and framework. </p><br>
      </div>
    <fieldset>
        <legend>
          <span>My Skills</span>
        </legend><br><br>
        <label for="web-dev">Web Development</label>
        <input type="range" id="web-dev"><br><br>
        <label for="Data-science">Data Science</label>
        <input type="range" id="Data-science"><br><br>
        <label for="Agile-dev">Agile Development</label>
        <input type="range" id="Agile-dev"><br><br>
        <label for="java-dev">Java + DSA</label>
        <input type="range" id="java-dev">
       </fieldset>
        <!-- Contact Section -->
    <section id="contact">
        <div class="container mt-3">
            <h1 class="text-center">Contact</h1>
            <div class="row">
                <div class="col-lg-6">
                    <form>
                        <div class="form-group">
                            <label for="name">Name</label>
                            <input type="text" id="name" class="form-control">
                        </div>
                        <div class="form-group">
                            <label for="email">Email</label>
                            <input type="email" id="email" class="form-control">
                        </div>
                        <div class="form-group">
                            <label for="subject">Subject</label>
                            <input type="text" id="subject" class="form-control">
                        </div>
                        <div class="form-group">
                            <label for="message">Message</label>
                            <textarea id="message" class="form-control"></textarea>
                        </div>
                        <button type="submit" class="btn btn-primary">Send Message</button>
                    </form>
                </div>

</div>    
</body>
</html>
