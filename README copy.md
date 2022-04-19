# mywebsite
Code for 11056 front-end website
 <a href="index.htm"><img src="images/background.jpeg"></a>
            <div class="nav-links" id="navLinks">
                <i class="fa fa-times" onclick="hideMenu()"></i>
                <ul>
                    <li><a href="#">Home</a></li>
                    <li><a href="#">About</a></li>
                    <li><a href="#">Festivals</a></li>
                </ul> 
            </div>
            <i class="fa fa-bars" onclick="showMenu()"></i>
        </nav>
<div class="text-box">
     <h2>Canberra Art Biennial 1-29</h2>
      <a href='#'>contour556 returns for the 4th edition this October - bigger and better than before.</a>   
        </div>
    </section>

        <!-- my comment --> 
        <main>
            
            <section class="first">
                <h1>Information About Us</h1>
                <p>Lorem ipsum dolor sit amet,consectetur adipiscing elit.</p>
                
                <div class="row">
                    <div class="first-col">
                        <h3>Festivals</h3>
                        <p>contour556 returns for The 4th edition this October - bigger and better than before.</p>
                    </div>
                     <div class="first-col">
                        <h3>About</h3>
                        <p>Contour 556 is the water level of Lake Burley Griffin, which links the event in name as well as in purpose to the history of the central Canberra landscape. The artworks and installations selected for the festival respond in some way to Canberra’s history, from 50,000 years to the present day. contour 556 will therefore offer the Canberra, Australian and international community a unique opportunity to engage with and understand the layers of Canberra’s history through art.</p>
                    </div>
                </div>
            </section>
            
   <!----- Photos ----->
            
<section class="photos">
    <h1>Some Art Works</h1> 
    <p>Lorem ipsum dolor sit amet,consectetur adipiscing elit.</p>
    
    <div class="row">
        <div class="photos-col">
            <img src="2020.jpeg">
            <div class="layer">
                <h3>2020</h3>
            </div>
        </div>
        <div class="photos-col">
            <img src="2018.jpeg">
            <div class="layer">
                <h3>2018</h3>
            </div>
        </div>
        <div class="photos-col">
            <img src="2016.jpeg">
            <div class="layer">
                <h3>2016</h3>
            </div>
        </div>
    </div>
            
</section>
            
<!----- Covid 19 ----->
            
<section class="covid-19">
    <h1>Covid 19</h1>
    <p>Lorem ipsum dolor sit amet,consectetur adipiscing elit.</p>
    
    <div class="row">
        <div class="covid-19-col">
        <h3>Visistors</h3>
        <p>If you are feeling unwell, or in the last 14 days have visited a COVID 19 hotspot please stay at home, seek medical attention and follow government recommendations.<br>Refer to https://www.covid19.act.gov.au/</p>
        </div>
    
    </div>
            
</section>
            
<!----- City Commissions ----->
            
<section class="City-Commissions">
    <h1>City Commissions</h1>
    <p>Lorem ipsum dolor sit amet,consectetur adipiscing elit.</p>
    
    <div class="row">
        <div class="City-Commissions-col">
            <img src="city-commissions.png">
            <div>
                <h3>our ongoing project</h3>
                <p>Here is some description text. Nunc cursus erat ut nisi facilisis, vel fringilla neque pellentesque. Pellentesque habitant morbi tristique senectus et netus et malesuada fames.</p>
                
                <p>Etiam et turpis mattis, efficitur mi ut, ultrices diam. Donec consectetur, odio eget porta varius, orci mauris viverra ante, eget egestas turpis sapien vel orci. Donec eu ornare augue, ut efficitur velit. Vestibulum et magna mattis, sollicitudin ligula ac, facilisis dui. Ut blandit lectus neque, sit amet.</p>
            </div>
        </div>
    </div>
</section>
            
<!---- Subscribe to our Newsletter ---->
        
 <section class="Ston">
    <h1>Subscribe to our Newsletter</h1> 
    <a href="" class="hero-btn">SIGN UP</a>
</section>
            
            
<!---- Footer ---->
<section class="Footer">
    <h4>About Us</h4>
</section>
            
 <!----- JavaScript for Toggle Menu ----->
    
<script>
    
    var navLinks = document.getElementById("navLinks");
          
    function showMenu(){
        navLinks.style.right = "0";
    }
    function hideMenu(){
        navLinks.style.right = "-200px";
    }
</script>
            </main>
        
    </body>
</html>