# hotbeans.github.io
l lang="en">
<head>
    <meta charset="utf-8">
    <title>HTML Div Layout</title>
    <link rel="stylesheet" href="CSS/StyleSheet1.css">
    <link rel="stylesheet" href="CSS/StyleSheet_Menu.css">
</head>
<body>


    <div class="container">
        <div class="header">
            <h1>hot beans company</h1>

            <ul>
                <li><a class="active" id="op_Home">Home</a></li>
                <li><a id="op_Contact">Contact</a></li>
                <li><a id="op_Teams">Our Teams</a></li>
                <li><a id="op_joinUs">join Us</a></li>
                  
                <li style="float:right"><a id="op_About">About</a></li>
            </ul>
        </div>

        <div id="home_section" class="section">
            <center>
                <h2>hot beans company by utsas mollah the ceo</h2>
            <img src="images/download.jpg" alt="Company Picture" width="250" height="150">
            </center>
            <h2>the table of courses that requires to join the company</h2>

<table style="width:100%">
  <tr>
    <th>btec course work</th>
    <th>course</th>
    <th>level</th>
  </tr>
  <tr>
    <td>webiste </td>
    <td>computing</td>
    <td>10</td>
  </tr>
  <tr>
    <td>it computing data process</td>
    <td>a-level it</td>
    <td>5</td>
  </tr>
</table>

            <br /><br /><br /><br />
            <p>&emsp;&nbsp;&nbsp;
            the hot beans applies all the people to join and become a 
        software engineering today i will allow people to join my company. toward that i will show the 
    student how to become a sernor engineering. A senior engineer is in charge of supervising all activities within a certain region. 
    A senior engineer who has years of experience and skill may be in charge of setting project goals, timelines, and budgets.</p>
    
            
            
        </div>


        <div id="about_section" class="section" hidden>
            <center>
                <h2>About</h2>
                <img src="images/CDG_blog_post_image_02-2.jpg" alt="Company Picture" width="100" height="100">
                <img src="images/download.jpg" alt="company pitures" width="100" height="100">
                <img src="images/download.png" alt="Company Picture" width="100" height="100">
            </center>
    
            <article class="all-browsers">
                <h1>achive the most A**</h1>
                <article class="browser">
                  <h2>rahman hossain</h2>
                  <p> MR rahaman got all a starts and he works in microsoft edge at london oxford univesity</p>
                </article>
                <article class="browser">
                  <h2>Mozilla Firefox</h2>
                  <p>Mozilla has achive a golden plus A** thorught her education hot beans centre and she works in senior manegger of micorsoft</p>
                </article>
                
              </article>
        </div>

        <div id="Teams_section" class="section" hidden>
            <center>
                <h2>Our Teams</h2>
                <table>
                    <tr>
                        <td><img src="images/jacob holder.avif" alt="Company Picture" width="189" height="189"></td>
                        <td><img src="images/software_engineer.jpeg.jpg" alt="Company Picture" width="189" height="189"></td>
                        <td><img src="images/GettyImages-1180183927_73387d16.webp" alt="Company Picture" width="189" height="189"></td>
                    </tr>
                    <tr>
                        <td>
                            <p>jacob holder </p>
                        </td>
                        <td>
                            <p>jisso halmet </p>
                        </td>
                        <td>
                            <p>mariam josef </p>
                        </td>
                    </tr>
                    <tr>
                        <td>
                            <p>he is a master engineer who worked for micorsot</p>
                        </td>
                        <td>
                            <p>she is the head quaters of the compay that runs the student loans and education</p>
                        </td>
                        <td>
                            <p>she is the maneger of the master student which she control the education such as exam, lecture</p>
                        </td>
                    </tr>
                </table> 
 
            </center>
        </div>

        <div id="contact_section" class="section" hidden>
            <center>
                <h2>Contact us</h2>
            </center>
            <form action="/action_page.php" style="justify-content:center">
                &emsp;&emsp;&emsp;&emsp;&emsp;<label for="fname">First name:</label>
                <input type="text" id="fname" name="fname" value=""><br><br>

                &emsp;&emsp;&emsp;&emsp;&emsp;<label for="lname">Last name:</label>
                <input type="text" id="lname" name="lname" value=""><br><br>

                &emsp;&emsp;&emsp;&emsp;&emsp;<label for="mes">Message:</label><br>
                &emsp;&emsp;&emsp;&emsp;&emsp;&nbsp;&nbsp;&nbsp;<textarea id="mes" name="mes" rows="4" cols="50"></textarea><br><br>
                &emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;<input type="submit" value="Submit">
            </form>
        </div>
        <div id="joinUs_section" class="section" hidden>
            <center>
                <h2>Join us</h2>
            </center>
            <form name="form1" action="" onsubmit="return validateEntry()">
                &emsp;&emsp;&emsp;&emsp;&emsp;<label for="fname">First name:</label>
                <input type="text" id="fname" name="fname" value=""><br><br>

                &emsp;&emsp;&emsp;&emsp;&emsp;<label for="lname">Last name:</label>
                <input type="text" id="lname" name="lname" value=""><br><br>

                &emsp;&emsp;&emsp;&emsp;&emsp;<label for="email">Email:</label>
                <input type="text" id="email" name="email" value=""><br><br>

                &emsp;&emsp;&emsp;&emsp;&emsp;<label for="notes">Notes:</label><br>
                &emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;<textarea id="notes" name="notes" rows="4" cols="50"></textarea><br><br>

                &emsp;&emsp;&emsp;&emsp;&emsp;<b>Upload Your CV: </b>
                <input type="file"
                       id="file1"
                       name="upload">
                <br><br>

                &emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;<input type="submit" value="Submit">
            </form>          
            
        </div>

        <div class="footer">
            <p>copyright &copy; Company Y</p>
           
            <h1>The email of the company @Hot beans</h1>

            <div>
            powered by hot beans company name utsas mollah
            </div>

        </div>

    </div>
    
    <script type="text/javascript">
        var _about_section = document.getElementById('about_section');
        var _home_section = document.getElementById('home_section');
        var _contact_section = document.getElementById('contact_section');
        var _joinUs_section = document.getElementById('joinUs_section');
        var _Teams_section = document.getElementById('Teams_section');


        document.getElementById('op_joinUs').onclick = function () {
            _about_section.hidden = true;
            _home_section.hidden = true;
            _contact_section.hidden = true;
            _joinUs_section.hidden = false;
            _Teams_section.hidden = true;
        }

        document.getElementById('op_Teams').onclick = function () {
            _about_section.hidden = true;
            _home_section.hidden = true;
            _contact_section.hidden = true;
            _joinUs_section.hidden = true;
            _Teams_section.hidden = false;
        }

        document.getElementById('op_About').onclick = function () {
            _about_section.hidden = false;
            _home_section.hidden = true;
            _contact_section.hidden = true;
            _joinUs_section.hidden = true;
            _Teams_section.hidden = true;
        }

        document.getElementById('op_Contact').onclick = function () {
            _about_section.hidden = true;
            _home_section.hidden = true;
            _contact_section.hidden = false;
            _joinUs_section.hidden = true;
            _Teams_section.hidden = true;
        }

        document.getElementById('op_Home').onclick = function () {
            _about_section.hidden = true;
            _home_section.hidden = false;
            _contact_section.hidden = true;
            _joinUs_section.hidden = true;
            _Teams_section.hidden = true;
        }

        function validateEntry() {
            //var fn = document.getElementById('fname').value;
            var fn = document.forms["form1"]["fname"].value;
            //alert(fn);
            if (fn == null || fn == "") { alert("Please enter first name"); }
                        
            var ln = document.forms["form1"]["lname"].value;
            //alert(ln);
            if (ln == null || ln == "") { alert("Please enter last name"); }
            

        }
    </script>
</body>
</html>
