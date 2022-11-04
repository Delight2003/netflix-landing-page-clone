<!DOCTYPE html>
<html>
    <head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.2.0/css/all.min.css" integrity="sha512-xh6O/CkQoPOWDdYTDqeRdPCVd1SpvCA9XXcUnZS2FmJNp1coAFzvtCN9BmamE+4aHK8yyUHUSCcJHgXloTyT2A==" crossorigin="anonymous" referrerpolicy="no-referrer" />
            <link href='https://unpkg.com/boxicons@2.1.2/css/boxicons.min.css' rel='stylesheet'>
        <title>Netflix landing page clone</title>
        <link rel="stylesheet" type="text/css" href="netflix.css">
        
    </head>
    <body>
    <div class="loader">
    <div class="bar"></div>
    <div class="bar2"></div>
    <div class="bar3"></div>
    </div>
    <main>
        <header>
         <svg viewBox ="0 0 111 30" class="logo" focusable="true"><g><path d="M105.06233,14.2806261 L110.999156,30 C109.249227,29.7497422 107.500234,29.4366857 105.718437,29.1554972 L102.374168,20.4686475 L98.9371075,28.4375293 C97.2499766,28.1563408 95.5928391,28.061674 93.9057081,27.8432843 L99.9372012,14.0931671 L94.4680851,-5.68434189e-14 L99.5313525,-5.68434189e-14 L102.593495,7.87421502 L105.874965,-5.68434189e-14 L110.999156,-5.68434189e-14 L105.06233,14.2806261 Z M90.4686475,-5.68434189e-14 L85.8749649,-5.68434189e-14 L85.8749649,27.2499766 C87.3746368,27.3437061 88.9371075,27.4055675 90.4686475,27.5930265 L90.4686475,-5.68434189e-14 Z M81.9055207,26.93692 C77.7186241,26.6557316 73.5307901 26.4064111 69.250164,26.3117443 L69.250164,-5.68434189e-14 L73.9336389,-5.68434189e-14 L73.9336389,21.8745899 C76.6248008,21.9373887 79.3120255,22.1557784 81.9055207,22.2804387 L81.9055207,23.93692 Z M64.2496954,10.6561065 L64.2496954,15.3435186 L57.8442216,15.3735186 L57.8442216,25.9996251 L53.2186709,25.9996251 L53.2186709,-5.68434189e-14 L66.3438123,-5.68434189e-14 L66.3436123,4.68741213 L57.8442216,4.68741213 L57.8442216,10.6561065 L64.2496954,10.6561065 Z M45.3435186,4.68741213 L45.3435186,26.2498828 C43.7810479,26.2498828 42.1876465,26.2498828 40.6561065,26.3117443 L40.6561065,4.68741213 L35.8121661,4.68741213 L35.8121661, -5.68434189e-14 L50.2183897,-5.68434189e-14 L50.2183897,4.68741213 L45.3435186,4.68741213 Z M30.749836,15.5928391 C28.687787,15.5928391 26.2498828,15.5928391 24.4999531,15.6875059 L24.4999531,22.6562030 C27.2499766,22.4678976 30,22.2495079 32.7809542,22.1557784 L32.7809542,26.6557316 L19.812541,27.6876933 L19.8812541,-5.68434189e-14 32.7809542,-5.68434189e-14 32.7809542,4.68741213 L24.4999531,4.68741214 L24.4999531,10.9991564 C26.3126816,10.9991564 29.0936358,10.9054269 30.749836,10.9054269 L30.749836,15.5928391 Z M4.78114163,12.9684132 L4.78114163,29.7497422 0,30 L0,-5.68434189e-14 L4.4690224,-5.68434189e-14 L10.562377,17.0315868 L10.562377,-5.68434189e-14 L15.2497891,-5.68434189e-14 L15.2497891,28.061674 C13.5935889,28.3437998 11.906458,28.4375293 10.1246602,28.6868498 L4.78114163,12.9684132 Z" fill="#d81f26"></path></g></svg>
            <button class="sign-in">Sign In</button>
            <h3>Unlimited movies, TV shows and more</h3>
            <p>Watch anywhere. Cancel anytime.</p>
            <span>Ready to watch? Enter your email to create or restart your membership.</span>
            <form>
            <div class="input">
            <label for="email" class ="label">Email address</label>
            <input type = "email" required class="email">
            </div>
            <button class="start">Get Started<span class="bx bx-chevron-right"></span></button>
            </form>
        </header>
        <section class="tv">
            <h3>Enjoy on your TV.</h3>
            <span>Watch on Smart TVs, Playstation, Xbox, Chromecast, Apple TV, Blu-ray players, and more.</span>
            <img src="https://www.dropbox.com/s/e9jjhufuq0jezz3/tv.png?dl=1" alt="tv">
            <img src="https://www.dropbox.com/s/jpy5tbjwpyjt63q/unnamed.gif?dl=1" class="gif">
        </section>
        
        <section class="mobile">
            <h3>Download your shows to watch offline.</h3>
            <span>Save your favorites easily and always have something to watch.</span>
            <img src="https://www.dropbox.com/s/y5u59clve2oksmr/mobile-0819.jpg?dl=1" alt="mobilephone">
            <div class="download">
                <img src ="https://www.dropbox.com/s/y72me3jp0r1xyt1/boxshot.png?dl=1">
                <div class="st"><span>Stranger Things</span><span>Downloading...</span></div>
                <i class="bx bx-download"></i>
            </div>
        </section>
        
        <section class="desktop">
            <h3>Watch everywhere</h3>
            <span>Stream unlimited movies and TV shows on your phone, tablet, laptop and TV without paying more.</span>
            <img src ="https://www.dropbox.com/s/h3urho65smjvaua/device-pile.png?dl=1" alt="desktop">
        <img src="https://www.dropbox.com/s/9cyol97v8rfbgyf/H95B.gif?dl=1" class="gif2" alt="gif">
        </section>
        
        <section class="kids">
            <h3>Create profiles for kids.</h3>
            <span>Send kids on adventures with their favorite characters in a space made just for them-free with your membership.</span>
            <img src="https://www.dropbox.com/s/sufteyq2gqc3l7r/kids.png?dl=1" alt="kids">
        </section>
        
        <section class="faqs">
            <h3>Frequently Asked Questions</h3>
            <div class="question">
            <div class="faq-container">
            <div class="faq faq1">What is Netflix?<svg class="thin-x" viewBox="0 0 26 26" class="x1" focusable="true"><path d ="M10.5 9.3L1.8 0.5 0.5 1.8 9.3 10.5 0.5 19.3 1.8 20.5 10.5 11.8 19.3 20.5 20.5 19.3 11.8 10.5 20.5 1.8 19.3 0.5 10.5 9.3Z"></path></svg>
            </div>
            <div class="answer ans1">
            <p>Netflix is a streaming service that offers a wide variety of award-winning TV shows, movies, anime, documentaries, and more on thousands of internet-connected devices.</p>
<br/>
              <p>You can watch as much as you want, whenever you want without a single commercial – all for one low monthly price. There's always something new to discover and new TV shows and movies are added every week!</p>
              </div>
            </div>
            
            <div class="faq-container">            
            <div class="faq faq2"><span>How much does netflix cost?</span><svg class="thin-x" viewBox="0 0 26 26" class="x2" focusable="true"><path d ="M10.5 9.3L1.8 0.5 0.5 1.8 9.3 10.5 0.5 19.3 1.8 20.5 10.5 11.8 19.3 20.5 20.5 19.3 11.8 10.5 20.5 1.8 19.3 0.5 10.5 9.3Z"></path></svg>
            </div>
            <div class="answer ans2">
                <p>Watch Netflix on your smartphone, tablet, Smart TV, laptop, or streaming device, all for one fixed monthly fee. Plans range from EUR8.99 to EUR17.99 a month. No extra costs, no contracts.</p>
            </div>
            </div>
            <div class="faq-container">
                
            <div class="faq faq3"><span>Where can I watch?</span><svg class="thin-x" viewBox="0 0 26 26" class="x3" focusable="true"><path d ="M10.5 9.3L1.8 0.5 0.5 1.8 9.3 10.5 0.5 19.3 1.8 20.5 10.5 11.8 19.3 20.5 20.5 19.3 11.8 10.5 20.5 1.8 19.3 0.5 10.5 9.3Z"></path></svg>
            </div>
            <div class="answer ans3">
               <p>Watch anywhere, anytime. Sign in with your Netflix account to watch instantly on the web at netflix.com from your personal computer or on any internet-connected device that offers the Netflix app, including smart TVs, smartphones, tablets, streaming media players and game consoles.</p>
<br />
<p>You can also download your favorite shows with the iOS, Android, or Windows 10 app. Use downloads to watch while you're on the go and without an internet connection. Take Netflix with you anywhere.</p> 
            </div>
            </div>
            <div class="faq-container">             
            <div class="faq faq4"><span>How do I cancel?</span><svg class="thin-x" viewBox="0 0 26 26" class="x4" focusable="true"><path d ="M10.5 9.3L1.8 0.5 0.5 1.8 9.3 10.5 0.5 19.3 1.8 20.5 10.5 11.8 19.3 20.5 20.5 19.3 11.8 10.5 20.5 1.8 19.3 0.5 10.5 9.3Z" ></path></svg>
            </div>
            <div class="answer ans4">
                <p>Netflix is flexible. There are no pesky contracts and no commitments. You can easily cancel your account online in two clicks. There are no cancellation fees – start or stop your account anytime.</p>
            </div>
            </div>
            <div class="faq-container">
            <div class="faq faq5"><span>What can I watch on Netflix?</span><svg class="thin-x" viewBox="0 0 26 26" class="x5" focusable="true"><path d ="M10.5 9.3L1.8 0.5 0.5 1.8 9.3 10.5 0.5 19.3 1.8 20.5 10.5 11.8 19.3 20.5 20.5 19.3 11.8 10.5 20.5 1.8 19.3 0.5 10.5 9.3Z"></path></svg>
            </div>
            <div class="answer ans5">
                <p>Netflix has an extensive library of feature films, documentaries, TV shows, anime, award-winning Netflix originals, and more. Watch as much as you want, anytime you want.</p>
            </div>
            </div>
            <div class="faq-container">
            <div class="faq faq6"><span>Is Netflix good for kids?</span><svg class="thin-x" viewBox="0 0 26 26" class="x6" focusable="true"><path d ="M10.5 9.3L1.8 0.5 0.5 1.8 9.3 10.5 0.5 19.3 1.8 20.5 10.5 11.8 19.3 20.5 20.5 19.3 11.8 10.5 20.5 1.8 19.3 0.5 10.5 9.3Z"></path></svg>
            </div>
            <div class="answer ans6">
               <p>The Netflix Kids experience is included in your membership to give parents control while kids enjoy family-friendly TV shows and movies in their own space.</p>
<br />
<p>Kids profiles come with PIN-protected parental controls that let you restrict the maturity rating of content kids can watch and block specific titles you don’t want kids to see.</p> 
            </div>
            </div>
            </div>
            <p>Ready to watch? Enter your email to create or restart your membership.</p>
            <form>
            <div class="input2">
            <label for="email2" class ="label2">Email address</label>
            <input type = "email" required class="email2">
            </div>
            <button class="start2">Get Started<span class="bx bx-chevron-right"></span></button>
            </form>
        </section>
        
        <footer>
            <p><a href="">Questions? Contact us</a></p>
            
            <div class="links">
              <span><a href="">FAQ</a></span>  
              <span><a href="">Account</a></span> 
              <span><a href="">Investor Relations</a></span> 
              <span><a href="">Ways to Watch</a></span>  
              <span><a href="">Privacy</a></span> 
              <span><a href="">Corporate Information</a></span>
              <span><a href="">Speed Test</a></span>  
              <span><a href="">Only on Netflix</a></span> 
              <span><a href="">Help Center</a></span> 
              <span><a href="">Media Center</a></span>  
              <span><a href="">Jobs</a></span> 
              <span><a href="">Terms of use</a></span> 
              <span><a href="">Cookie Preferences</a></span> 
              <span><a href="">Contacts Us</a></span> 
              <span><a href="">Legal notices</a></span> 
            </div>
            
            <span class="nn">Netflix Nigeria</span>
        </footer>
        </main>
        
        <script>
        //declaring variables
      const faq = document.getElementsByClassName("faq");
let i;
let x;

      for (i = 0; i < faq.length; i++) {
  faq[i].addEventListener("click", function() {
    this.classList.toggle("active");
    
    let answer = this.nextElementSibling;
    if (answer.style.maxHeight) {
      answer.style.maxHeight = null;
      
    } else {
      answer.style.maxHeight = answer.scrollHeight + "px";     
      closeAllExcept(answer);
  };
})
}

    const closeAllExcept = (pan) => {
  for (x = 0; x < faq.length; x++) {
    let panelToClose = faq[x].nextElementSibling;
    if(panelToClose !== pan){
       faq[x].classList.remove("active");
       panelToClose.style.maxHeight = null;
       panelToClose.style.transition = "0.3s ease-out"
    }
  }
}  
   
                
            window.addEventListener("load", () => {
        document.querySelector(".loader").style.display = "none";
        document.querySelector("main").style.display = "block";
      });
    

        </script>
    </body>
</html>
