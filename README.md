# DestinyRiley.github.io
<html>
    <head>
        <title>Destiny Amazing Website</title>
        <link rel="stylesheet" type="text/css" href="myStyle.css"></link>
    </head>
    
    <body>
         <div id="all-contents"> 
            <nav>
                 <header>Destiny's Website</header>
                 <ul>
                    <li><a href="index.html">Home</a></li>
                    <li><a href="portfolio.html">Portfolio</a></li>
                </ul>
            </nav>
            
            <main>
                <div class="sidebar">
                 <img src="https://pmcvariety.files.wordpress.com/2017/09/beyonce.png" width="200" height="200">
                </div>+
                
    
                <div class="content">
                 <header>DestinyRiley</header>
         <p>Student at Helen Cox High School</p>
               <section class="interests">
                        <header>Interests</header>
                        <ul>
                            <li>Majorette</li>
                            <li>Sleeping</li>
                            <li>Eating</li>
                        </ul>
                    </section>
                </div>
           

            </main>
        </div>
 
    </body>
</html>
<html>
    <head>
            <Title>Destiny's Amazing Website</Title>
             <style type="text/css">
            body {
                background: rgb(225, 204, 204);
                color: rgb(245, 242, 1644);
                padding: 10px;
                font-family: arial;
            }
            header {
                font-size: 1.5em;
                font-weight: bold;
            }
            h1 {
                margin: 10px;
   
            }

            #all-contents {
                max-width: 800px;
                margin: auto;
            }
    
            /* navigation menu */
            nav {
                background: rgb(245, 242, 163);
                margin: 0 auto;
                display: flex;
                padding: 10px;
                border: 3px solid pink;
                border-radius: 25px;

            }
           
            nav header {
                display: flex;
                align-items: center;
                color: rgb(255, 164, 111);
                flex: 1;
            }
            nav ul {
                list-style-image: none;
            }
            nav li {
                display: inline-block;
                padding: 0 10px;
            }
            nav a {
                text-decoration: none;
                color: #fff;
            }
    
            /* main container area beneath menu */
            main {
                background: rgb(255, 223, 203);
                display: flex;
            }
            .content {
                flex: 1;
                padding: 15px;
            }
             /* portfolio styles */
            #portfolio {
                list-style-type: none;
                padding-left: 0;
            }
            
            #portfolio li {
                background: #225;
                padding: 100px;
                border-radius: 25px;
                margin-bottom: 25px;
            }
            
            #portfolio li:hover {
                background: #eee;
            } 
            
            #portfolio a {
                text-decoration: none;
                color: #454545;
            }
        </style>
    </head>

    <body>
        <nav>
            <header>Destiny's Amazing Website</header>
            <ul>
                <li><a href="index.html">Home</a>
                </li>
                <li><a href="portfolio.html">Portfolio</a>
                </li>
            </ul>
          <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQHIr0nw2iSk3AWFzMx3aVuFw0sa_FmVG8rFC9ibvvrDRHcx6co"></img>
        </nav>
        <main>
            <div class="content">
                <h1>Portfolio</h1>
                <ul id="portfolio">
                </ul>
            </div>
        </main>
      <div id="all-contents">
      </div>
        <script src="https://ajax.googleapis.com/ajax/libs/jquery/2.1.3/jquery.min.js"></script>
        <script id="portfolioScript">$(document).ready(function() {$.getJSON('projects/projects.json').then(function(data) { data.projects.forEach(function(project){ $('#portfolio').append('<li><a href="projects/' + project.name + '/">' + project.title + ' : ' + project.description + '</a></li>'); }); }); });</script>
    </body>
</html>
