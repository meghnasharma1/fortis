<!DOCTYPE html>
<html>
  <head>
	  <title>Fortis HTML</title>
	  <link rel="stylesheet" type="text/css" href="main.css"/>
	  <link rel="icon" href="../icon.png">
  </head>
  <body>
    <div class = "Whole Thing">
       <div class = "navbar yeet">
          <h2>Menu Bar</h2>
          <ul>
            <li><a href="main.html">Home</a></li>
            <li class="dropdown">
                           <a href="javascript:void(0)" class="dropbtn">Exercises</a>
                           <div class="dropdown-content">
                               <a href="BicepsTriceps.html">Biceps/Triceps</a>
                               <a href="LatsDeltoids.html">Lats/Deltoids</a>
                               <a href="ObliquesAbdominals.html">Obliques/Abdominals</a>
                               <a href="Gluteals.html">Gluteals</a>
			       <a href="Pectorals.html">Pectorals</a>
				<a href="Thighs.html">Thighs</a>
				<a href="Calves.html">Calves</a>
                           </div>
            </li>
            <li><a href="team.html">Our Team</a></li>
        </ul>
       </div>
       <div class = "main">
       <h1>Fortis</h1>
       <p>Unhappy with your body? Wanting to get more healthy? You've come to the right place. 
          The process is easy- just choose the part of the body you want to improve or work on,
          and a variety of exercises that can get you the proper results you wish to see will pop up. 
          Follow each step carefully and do the recommended number of reps for each set of workouts, and you're on your way! 
          Browse through the different muscles and enjoy your workout.</p>
          <img src = "https://cdn.psychologytoday.com/sites/default/files/field_blog_entry_images/%20Andrey%20Burmakin_Shutterstock.jpg"/>
       
	       
	       <!-- Back to Top Button -->
           <button onclick="topFunction()" id="myBtn" title="Back to Top"></button>

           <!-- Footer -->
           <div id="footer" style="font-size:2.75vmin;">
               <i>Organized and Owned by Fortis</i>
               <br />
           </div>
           <br>
           <br>
           <script>
               // When the user clicks on the button, scroll to the top of the document 
               function topFunction() {
                   document.body.scrollTop = 0;
                   document.documentElement.scrollTop = 0;
               }
           </script>
      </div>
    </div>
  </body>
</html>
