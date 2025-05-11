# Website-test
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
 

<style>
        body {
            font-family: Arial, sans-serif;
        }
        nav {
            background-color: #bcd4e6 ;
            color: solid black;
            padding: 10px;
        }
        nav a {
            color: black;
            margin: 10px;
            text-decoration: none;
        }
        section {
            position: relative;
            margin-top: 4px;
            text-align: top;
            border: 1px solid #ccc;
            margin-bottom: 50px;
        
           
            display: flex;
            justify-content: center;
            align-items: top;
            flex-direction: row;
            padding-top: 10px;
            
       }
                            
             #HowItWorks{
            height: 500px;
            width: 100%;
            background-color: #f9f9f9;
            margin: auto; /* Centers section */


       }

              #WhyChooseUs{
            height: 510px;
            width: 100%;
           background-color: #f9f9f9;
            margin: auto; /* Centers section */
         

       }

              #Testimonials{
                 height: 660px;
            width: 100%;
           background-color: #f9f9f9;
            margin: auto; /* Centers section */


       }


             #ContactUs{
                  height: 1100px;
            width: 100%;
            background-color: #f9f9f9;
            padding-left: 15px; /* Centers section */
            padding-right: 10px;
            padding-bottom: 20px;
            margin-bottom: 10px;
            flex-direction: column;
       } 

    </style>


<style>
        body { transition: 0.3s; font-family: Arial, sans-serif; text-align: center; margin: 0; }
        .dark { background: #121212; color: white; }
        .toggle-container { position: absolute; top: 20px; right: 60px; }
        button { font-size: 24px; border: none; background: none; cursor: pointer; }
    </style>


<style>
        .header {
            position: relative;
            text-align: left;
            color: black;
        }
        .header img {
            width: 100%;
            height: auto;
        }
                }
    </style>

  <style>
        body {
            margin: 30px; /* Adds space around the frame */
            border: 5px cyan blue; /* Creates the frame */
            padding: 20px; /* Keeps content away from the border */
        }
    </style>

   <style>
        .contact-us {
            border: 1px solid black; /* Creates the frame */
            padding: 20px; /* Adds space inside the frame */
            margin: 20px; /* Provides spacing around the frame */
            background-color: #bcd4e6; /* Optional: Light background for better contrast */
            text-align: left; /* Centers the content */
        }

    
    </style> 

   
<style>

    .how-it-works{

        .text-box1 {
            position: absolute;
            top: 170px;
            left: 110px;
            width: 220px;
            height: 270px;
            background-color: #bcd4e6;
            transition: transform 0.1s ease;
        }

        .text-box1:hover {
            transform: scale(1.1);
        }
    
        .text-box2 {
            position: absolute; 
            top: 170px;
            left: 430px;
            width: 220px;
            height: 270px;
            background-color: #bcd4e6;
            transition: transform 0.1s ease;
        }

        .text-box2:hover {
            transform: scale(1.1);
        }

        .text-box3 {
            position: absolute;
            top: 170px;
            left: 750px;
            width: 220px;
            height: 270px;
            background-color:#bcd4e6;
            transition: transform 0.1s ease;
        }

        .text-box3:hover {
            transform: scale(1.1);
        }

        .text-box4 {
            position: absolute;
            top: 170px;
            left: 1070px;
            width: 220px;
            height: 270px;
            background-color: #bcd4e6;
            transition: transform 0.1s ease;
        }

        .text-box4:hover {
            transform: scale(1.1);
        }
  }  
  </style>


<style>
        .text-boxA {
            position: absolute;
            top: 180px;
            left: 40px;
             width: 230px;
            height: 290px;
            background-color: #bcd4e6;
            transition: transform 0.1s ease;
        }

        .text-boxA:hover {
            transform: scale(1.1);
        }
    </style>

<style>
        .text-boxB {
            position: absolute;
            top: 180px;
            left: 320px;
            width: 230px;
            height: 290px;
            background-color: #bcd4e6;
            transition: transform 0.1s ease;
        }

        .text-boxB:hover {
            transform: scale(1.1);
        }
    </style>


<style>
        .text-boxC {
            position: absolute;
            top: 180px;
            left: 590px;
             width: 230px;
            height: 290px;
            background-color: #bcd4e6;
            transition: transform 0.1s ease;
        }

        .text-boxC:hover {
            transform: scale(1.1);
        }
    </style>


<style>
        .text-boxD {
            position: absolute;
            top: 180px;
            left: 860px;
           width: 230px;
            height: 290px;
            background-color: #bcd4e6;
            transition: transform 0.1s ease;
        }

        .text-boxD:hover {
            transform: scale(1.1);
        }
    </style>


<style>
        .text-boxE {
            position: absolute;
            top: 180px;
            left: 1130px;
            width: 230px;
            height: 290px;
            background-color: #bcd4e6;
            transition: transform 0.1s ease;
        }

        .text-boxE:hover {
            transform: scale(1.1);
        }
    </style>



<style>
        .text-box-T1 {
            position: absolute;
            top: 140px;
            left: 200px;
            width: 1000px;
            height: 180px;
            background-color: #bcd4e6;
            transition: transform 0.1s ease;
        }

        .text-box-T1:hover {
            transform: scale(1.1);
        }
    </style>


<style>
        .text-box-T2 {
            position: absolute;
            top: 370px;
            left: 200px;
            width: 1000px;
            height: 180px;
            background-color: #bcd4e6;
            transition: transform 0.1s ease;
        }

        .text-box-T2:hover {
            transform: scale(1.1);
        }
    </style>

</head>
<body>

<p>
  <div class="toggle-container">
        <button onclick="toggleMode()">☀️</button>
    </div>
    
<script>
        function toggleMode() {
            document.body.classList.toggle('dark');
            let btn = document.querySelector('button');
            btn.innerHTML = document.body.classList.contains('dark') ? '🌙' : '☀️';
        }
    </script>

 </p>


<nav>
    <a href="#HowItWorks">How It Works</a>
    <a href="#WhyChooseUs">Why Choose Us</a>
    <a href="#Testimonials">Testimonials</a>
    <a href="#ContactUs">Contact Us</a>
</nav>

<p>
<font face="cambria">
<h1>Sell Your Unused Software Licenses Hassle-Free!<br></h1>
<h2>
SoftSell helps businesses maximize value by securely reselling surplus software.</h2>
</p>
    
    <div class="header">
        <img src="C:\Users\prakriti\OneDrive\Pictures\Screenshots\Screenshot 2025-05-11 192419.png" alt="Header Image">
        </div>

<p><font size="4">Turn your Unused Software into Cash!  &emsp;
<button style="width: 230px; height: 50px; background-color: #bcd4e6;"><center><b>Sell my Licenses</b></center></button>
</center>

&emsp;&emsp;

Maximize Value from your Software Investments!  &emsp;
<button style="width: 200px; height: 50px; background-color: #bcd4e6;"><center><b>Get a Quote</b></center></button>
</center>
</p>

<br>
<center>
Resell. Reinvest. Repeat! 
<button style="width: 200px; height: 50px; background-color: #bcd4e6;"><center><b>Get a Quote</b></center></button>
</center>
</center>
</p>


<br>

<section id="HowItWorks">
    
<p><font family="cambria" size="20"><b><top>How It Works</b></top>

<div class="how-it-works">
<div class="text-box1">
<p><center><font family="cambria" size="8">📝<br></center>Submit Licenses</p>
</div>

<div class="text-box2">
<p><center><font family="cambria" size="8">🔍<br>Get Free Valuation</center></p>
</div>

<div class="text-box3">
<p><center><font family="cambria" size="8">🔄️<br>Secured Validation</center></p>
</div>


<div class="text-box4">
<p><center><font family="cambria" size="8">💰<br>Get Paid Instantly</center></p>
</div>

</div>
</section>

<br><br>

<section id="WhyChooseUs">


<p><font family="cambria" size="8"><b>Why Choose Us</b>


<div class="text-boxA">
<p><center><font family="cambria" size="8">📈<br></center>Best Market Prices</center></p>
</div>

<div class="text-boxB">
<p><center><font family="cambria" size="8">🌏<br>Global Reach</center></p>
</div>

<div class="text-boxC">
<p><center><font family="cambria" size="8">💳<br>Fast & Secure Payments</center></p>
</div>


<div class="text-boxD">
<p><center><font family="cambria" size="8">🔦<br>100% Visibility</center></p>
</div>

<div class="text-boxE">
<p><center><font family="cambria" size="8">🚀<br>Hassle-Free Process</center>
</p>
</div></section>
<br><br>


<section id="Testimonials">

<p><font family="cambria" size="20"><b><center>Testimonials</b></center>

<div class="text-box-T1">
<p><font family="cambria" size="7">📢<b>Alex M., IT Manager, TechCorp </b>– <i> "SoftSell made our software resale seamless!"</i>
</p></div>


<div class="text-box-T2">
<p><font family="cambria" size="7">📢<b>Sarah T. Roe, CTO, CloudSync</b> – <i> "A simple and effective way to sell excess licenses."</i>
</p></div></section>
<br>


 <section class="contact-us">
 <section id="ContactUs"> 

<p><font family="cambria" size="20" color="black"><b>Contact Us</b><br><br>

<form {
text-align: left;
}>
<font face="Romania" size="4" color = "black" class = "left-align">

<div class="container">
    <form align:"left">
      
    <label>First Name</label><br>
      <input type="text" name="first" style="width: 600px; height: 55px;" id="f1" placeholder="Enter your first name">
  
&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;

<font face="Times New Roman" size="5" color = "black"><left>
<button style="width: 500px; height: 90px; background-color: #bcd4e6; text-align:left;"><b>📧Email:<br>contact@softsell.com</b></button>
</left></font>

<br><br>

      
    <label>Last Name</label><br><br>
      <input type="text" name="last" style="width: 600px; height:55px;" id="f2" placeholder="Enter your last name">

<br><br>
     
    <label>Email</label><br>
      <input type="text" name="email" style="width: 600px; height:55px;" id="f3" placeholder="Enter your email id">

 
&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;



<font face="Times New Roman" size="5" color = "black"><left>
<button style="width: 500px; height: 90px; background-color: #bcd4e6; text-align:left;"><b>📞Phone:<br>(758)-492-136</b></button>
</left></font>

<br><br>

     <label>Phone</label><br><br>
      <input type="text" name="phone" style="width: 600px; height:55px;" id="f4" placeholder="(206)-198-4837"><br><br>

      <label>Company</label><br>
      <input type="text" name="company" style="width: 600px; height:55px;" id="f5" placeholder="Enter your company's name">
      
 
 
&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;



<font face="Times New Roman" size="4.8" color = "black"><left>
<button style="width: 500px; height: 90px; background-color: #bcd4e6; text-align:left;"><left><b>🏢Office:<br>Street J12, High Tech Park, Seattle, 98109 </b></button>
</left></font>
<br><br>

       <label>License Type</label><br><br>
       <select id="f6" name="company" style="width: 610px; height:55px;">
         <option value="Choose your license type">Select your license type</option>
         <option value="Google">Google</option>
         <option value="Microsoft">Microsoft</option>
         <option value="Adobe">Adobe</option>
         <option value="Other">Other</option>
       </select>
<br><br>
 

     <label>If Chosen Other</label><br>
      <input type="text" name="phone" style="width: 600px; height:55px;" id="f2" placeholder="(764)-198-4837">

  
&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;

<font face="Times New Roman" size="5" color = "black"><left>
<button style="width: 500px; height: 90px; background-color: #bcd4e6; text-align:left;"><b>⌚Business Hours:<br>8:00 AM -6:00 AM (Monday to Friday)</b></button>
</left></font>




    </form>
  </div>
 </section>
 </section>




        </form>
    </body>
</html>
