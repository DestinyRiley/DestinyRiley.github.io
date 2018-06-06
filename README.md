<!DOCTYPE HTML>
<html>
    <head>
        <title>Destiny Amazing Website</title>
        <style>
            body {
                background: rgb(123, 198, 205);
                color: rgb(45, 45, 45);
                padding: 10px;
                font-family: arial;
            }
            header {
                font-size: 1.5em;
                font-weight: bold;
            }
            #all-contents {
                max-width: 800px;
                margin: auto;
            }
    
            /* navigation menu */
            nav {
                background: rgb(125, 000, 41);
                margin: 0 auto;
                display: flex;
                padding: 10px;
            }
            nav header {
                display: flex;background: rgb(111, 111, 222);
        margin: 0 auto;
        display: flex;
        padding: 10px;
                align-items: center;
                color: rgb(111, 222, 333);
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
                color: #111;
            }
    
            /* main container area beneath menu */
            main {
                background: rgb(245, 238, 219);
                display: flex;
            }
            .sidebar {
                margin-right: 25px;
                padding: 10px;
            }
            .sidebar img {
                width: 200px;
                border:10px solid black;
                border-radius:30px;
            }
            .content {
                flex: 1;
                padding: 15px;
            }
            .interests header {
                font-size: 1.25em;
            }
        </style>
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
