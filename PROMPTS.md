# AI Prompt

Hey, Bro You know i am learning web development  and planning to continue it next seven month alongwith every single day 6 to seven hour coding, now i want create section where it they suggest like :  


1. Prompt

I am building a developer conference landing page called DevConf 2026 using only HTML and CSS.

The website already contains these sections:

Navbar with logo, navigation links, and a register button.
Hero section with a dark background image and blue call-to-action button.
Speaker section with four cards.
Pricing section with three pricing cards.
Footer with social media icons.

The design language of the website is:

Main colors: dark navy (#0D1B2A), white, and blue (#2563EB).
Google fonts: Inter and Arimo.
Rounded cards and modern spacing.
Professional developer-conference theme.
No JavaScript and no CSS frameworks.

I need a new AI-generated section for the assignment's placeholder section.

The section must:

Feel like it naturally belongs between the pricing section and the footer.
Be more creative than a normal FAQ or newsletter section.
Match the visual style of the rest of the website.
Look premium and futuristic.
Use cards, icons, and clean typography.
Be responsive.

Generate a "DevConf Hackathon Arena" section that contains:

A section title and subtitle.
Four challenge cards.
Each card should have:
Challenge name.
Difficulty level.
Prize amount.
Small description.
Team size.
Add a highlighted grand-prize card.
Use only semantic HTML and CSS.


2. and also;

Create a unique section for my DevConf 2026 landing page.

Requirements:

The section must fit a developer conference website.
Use only HTML and CSS.
Match the existing design language:
   Dark blue and white colors.
   Rounded cards.
   Blue buttons.
   Inter font.
Make it more unique than a normal FAQ or newsletter section.

Generate a "DevConf Hackathon Arena" section with four challenge cards and prize amounts.

current live website link for you to see this for better understanding well :  https://ridwanulhaquekawsar.github.io/B14-A01-DevConf-2026/


my code without you suggetion section one : 

html : 

<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Dev Conference</title>
    <link rel="stylesheet" href="./styles/style.css">

    <!-- Google Font inter -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link
        href="https://fonts.googleapis.com/css2?family=Inter:ital,opsz,wght@0,14..32,100..900;1,14..32,100..900&display=swap"
        rel="stylesheet">

    <!-- Google font Arimo -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link
        href="https://fonts.googleapis.com/css2?family=Arimo:ital,wght@0,400..700;1,400..700&family=Inter:ital,opsz,wght@0,14..32,100..900;1,14..32,100..900&display=swap"
        rel="stylesheet">


    <!-- font awesome cdn -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/7.0.1/css/all.min.css"
        integrity="sha512-2SwdPD6INVrV/lHTZbO2nodKhrnDdJK9/kg2XD1r9uGqPo1cUbujc+IYdlYdEErWNu69gVcYgdxlmVmzTWnetw=="
        crossorigin="anonymous" referrerpolicy="no-referrer" />
</head>

<body>
    <!-- navbar section start -->
    <nav>
        <!-- left icon -->
        <div class="nav-left-icon-parent">
            <img src="./assets/logo.png" alt="">
        </div>

        <!-- middle items -->
        <div class="nav-middle-items-parent">
            <ul class="nav-middle-items">
                <li class="Speakers"> <a href="#">Speakers</a> </li>
                <li class="Schedule"> <a href="#">Schedule</a> </li>
                <li class="Tracks"> <a href="#">Tracks</a> </li>
                <li class="Venue"> <a href="#">Venue</a> </li>
                <li class="Blog "> <a href="#">Blog</a> </li>
            </ul>
        </div>

        <!-- right register button -->
        <div class="nav-right-button-parent">
            <button>
                <h2>Register Now</h2>
            </button>
        </div>
    </nav>
    <!-- navbar section end -->


    <!-- Hero section start -->
    <section class="hero-parent">
        <!-- hero text -->
        <div class="hero-content-text">
            <em>
                <h1>Code. Connect. Create</h1>
            </em>
            <p>Join 4,000+ engineers, founders, and builders at the premier developer <br> conference of 2026. Three
                days of
                cutting-edge talks, hands-on workshops, <br> and meaningful connections.</p>
        </div>

        <!-- hero button -->
        <div class="hero-content-button">
            <button>
                <h1>Register Now</h1>
            </button>
        </div>
    </section>
    <!-- Hero section end -->


    <!-- Meet the speakers section start -->
    <section class="meet-the-speakers-root">
        <h1>Meet the Speakers</h1>

        <div class="meet-the-speakers-cards-parent">
            <!-- Andrej Karpathy -->
            <div>
                <img src="./assets/andrej.png" alt="">

                <div class="text-content">
                    <h5>AI / ML</h5>
                    <h3>Andrej Karpathy</h3>
                    <p>Pretraining team, Anthropic</p>
                </div>
            </div>

            <!-- Demis Hassabis -->
            <div>
                <img src="./assets/demis.png" alt="">

                <div class="text-content">
                    <h5>Cloud & DevOps</h5>
                    <h3>Demis Hassabis</h3>
                    <p>Co-Founder and CEO, Google DeepMind</p>
                </div>
            </div>

            <!-- Gary Marcus -->
            <div>
                <img src="./assets/gary.png" alt="">

                <div class="text-content">
                    <h5>Frontend</h5>
                    <h3>Gary Marcus</h3>
                    <p>Staff Engineer, Vercel</p>
                </div>
            </div>

            <!-- Mustafa Suleyman -->
            <div>
                <img src="./assets/mustafa.png" alt="">

                <div class="text-content">
                    <h5>Security</h5>
                    <h3>Mustafa Suleyman</h3>
                    <p>CEO of Microsoft AI</p>
                </div>
            </div>
        </div>
    </section>
    <!-- Meet the speakers section start end -->


    <!-- Secure Your Spot (Pricing) Section start -->
    <section class="secure-your-spot-root">
        <h1>Secure Your Spot</h1>
        <p>Early-bird pricing ends August 15, 2026.</p>

        <div class="secure-your-spot-cards-parent">
            <!-- Standard card -->
            <div class="standard">
                <p class="p1">STANDARD</p>
                <h1>$399</h1>
                <p class="p2">per person</p>

                <hr>

                <ul>
                    <li>Access to all 3 conference days</li>
                    <li>48 curated technical talks</li>
                    <li>2 workshop sessions</li>
                    <li>Networking lunch & coffee breaks</li>
                    <li>Conference swag bag</li>
                    <li>Digital recordings (30 days)</li>
                </ul>

                <button> <a href="#">Get Standard</a> </button>
            </div>

            <!-- Pro card -->
            <div class="pro">
                <p class="p1">PRO</p>
                <h1>$749</h1>
                <p class="p2">per person</p>

                <hr>

                <ul>
                    <li>Everything in Standard</li>
                    <li>Unlimited workshop access</li>
                    <li>Speaker meet & greet</li>
                    <li>VIP networking dinner</li>
                    <li>Lifetime recording access</li>
                    <li>1-on-1 mentorship (30 min)</li>
                </ul>

                <button> <a href="#">Get Pro</a> </button>
            </div>

            <!-- Team card -->
            <div class="team">
                <p class="p1">TEAM</p>
                <h1>$5,999</h1>
                <p class="p2">up to 10 people</p>

                <hr>

                <ul>
                    <li>Everything in Pro (10 seats)</li>
                    <li>Dedicated team lounge access</li>
                    <li>Private workshop booking</li>
                    <li>Company logo on event page</li>
                    <li>Recruitment booth (1 day)</li>
                    <li>Priority customer support</li>
                </ul>

                <button> <a href="#">Contact Us</a> </button>
            </div>
        </div>
    </section>
    <!-- Secure Your Spot (Pricing) Section end -->




    <!-- AI Suggested section start -->
    <section>
        
    </section>
    <!-- AI Suggested section end -->




    <!-- Footer Section start -->
    <section class="footer-section-root">
        <!-- Footer top -->
        <div class="footer-top">
            <img src="./assets/footer-logo.png" alt="">
            
            <div class="social-links">
                <a href="https://www.facebook.com/"> 
                    <i class="fa-brands fa-facebook"></i> 
                </a>

                <a href="https://www.youtube.com/">
                    <i class="fa-brands fa-youtube"></i>
                </a>

                <a href="https://web.telegram.org/">
                    <i class="fa-brands fa-telegram"></i>
                </a>

                <a href="https://www.instagram.com/?hl=en">
                    <i class="fa-brands fa-instagram"></i>
                </a>
            </div>
        </div>

        <hr>

        <!-- footer bottom -->
        <div class="footer-bottom">
            <p>© 2026 DevConf. All rights reserved.</p>
            <div class="footer-tmp">
                <p> <a href="#">Privacy Policy</a> </p>
                <p> <a href="#">Terms of Service</a> </p>
            </div>
        </div>
    </section>
    <!-- Footer section end -->
</body>

</html>   



css :   

/* Reset */
body {
    margin: 0;
    padding: 0;
}

/* navigation style */
nav {
    max-width: 1551px;
    display: flex;
    justify-content: space-between;
    align-items: center;
    margin: 35px auto;
}


/* left nav style */
.nav-left-icon-parent img {
    height: 60px;
}

/* middle item style */
.nav-middle-items {
    display: flex;
    gap: 40px;
}

.nav-middle-items-parent ul {
    list-style: none;
}

.nav-middle-items-parent ul a {
    text-decoration: none;
    font-size: 19px;
}

.nav-middle-items-parent ul .Speakers a {
    font-family: inter;
    color: #575757;
}

.nav-middle-items-parent ul .Schedule a {
    font-family: Arimo;
    color: #575757;
}

.nav-middle-items-parent ul .Tracks a {
    color: #575757;
    font-family: Arimo;
    font-weight: 450;
}

.nav-middle-items-parent ul .Venue a {
    color: #575757;
    font-family: Arimo;
    font-weight: 500;
}

.nav-middle-items-parent ul .Blog a {
    color: #575757;
    font-family: Arimo;
    font-weight: 600;
}

/* right nav style */
.nav-right-button-parent button h2 {
    padding: 0 45px;
    font-family: inter;
    color: #FFFFFF;
}

.nav-right-button-parent button {
    border-radius: 15px;
    background-color: #1D4ED8;
    border: #1D4ED8;
    cursor: pointer;
}



/* Hero section style */

/* parent */
.hero-parent {
    background:
        linear-gradient(rgba(0, 0, 0, 0.1),
            rgba(0, 0, 0, 0.9)),
        url('../assets/banner.jpg');
    height: 899px;
    background-size: cover;
    background-position: center;
    background-repeat: no-repeat;
}

.hero-parent {
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: space-between;
}

/* content text */
.hero-content-text {
    color: #FFFFFF;
    margin-top: 50px;
}

.hero-content-text h1 {
    text-align: center;
    font-size: 95px;
    font-family: inter;
    margin-bottom: 20px;
}

.hero-content-text p {
    text-align: center;
    width: 1000px;
    font-size: 27px;
    font-family: inter;
}

/* hero-content-button */
.hero-content-button {
    margin-bottom: 78px;
}

.hero-content-button button {
    border-radius: 10px;
    background-color: #1D4ED8;
    padding: 0 60px;
    border: #1D4ED8;
    cursor: pointer;
}

.hero-content-button h1 {
    font-family: inter;
    color: #FFFFFF;
}



/* Meet the speakers section style */
.meet-the-speakers-root {
    max-width: 1770px;
    margin: 10px auto;
    padding-bottom: 97px;
}

.meet-the-speakers-root h1 {
    text-align: center;
    margin: 90px auto;
    font-size: 65px;
    color: #000102;
    font-family: inter;
    margin-bottom: 65px;
}


/* meet-the-speakers-cards-parent style */
.meet-the-speakers-cards-parent {
    max-width: 1660px;
    display: grid;
    grid-template-columns: repeat(2, 1fr);
    gap: 35px;
    margin: 10px auto;
}

.meet-the-speakers-cards-parent img {
    width: 100%;
}

.meet-the-speakers-cards-parent>div {
    border: 1px solid #E5E7EB;
    border-radius: 10px;
    overflow: hidden;
}

.meet-the-speakers-cards-parent div h5 {
    color: #2563EB;
    font-family: inter;
    font-size: 13px;
    font-weight: 550;
    margin-bottom: 0;
}

.meet-the-speakers-cards-parent div h3 {
    font-family: inter;
    font-size: 23px;
    margin-top: 12px;
    margin-bottom: 0;
}

.meet-the-speakers-cards-parent div p {
    font-family: inter;
    color: #575757;
    margin-top: 13px;
}

.meet-the-speakers-cards-parent div .text-content {
    margin-left: 30px;
}

.meet-the-speakers-cards-parent>div {
    padding-bottom: 20px;
}




/* Secure Your Spot root style  */
.secure-your-spot-root {
    /* border: 2px solid gold; */
    max-width: 1620px;
    margin: 40px auto;
}

.secure-your-spot-root>h1 {
    text-align: center;
    font-family: inter;
    font-size: 58px;
    color: #0D1B2A;
    margin-bottom: 0;
}

.secure-your-spot-root>p {
    text-align: center;
    font-family: inter;
    font-size: 18px;
    color: #575757;
    margin-bottom: 60px;
}


/* secure-your-spot-cards-parent style */
.secure-your-spot-cards-parent {
    display: flex;
    justify-content: center;
    align-items: center;
    gap: 30px;
}

.secure-your-spot-cards-parent li {
    margin-bottom: 10px;
}

.secure-your-spot-cards-parent h1 {
    font-size: 47px;
    font-family: inter;
    margin-left: 25px;
    margin-top: 8px;
    margin-bottom: 8px;
}

.p2 {
    margin-left: 25px;
    margin-top: 0;
}

.secure-your-spot-cards-parent button {
    margin: 20px auto;
    cursor: pointer;
}

.secure-your-spot-cards-parent button a {
    text-decoration: none;
    font-size: 14px;
    font-family: inter;
    font-weight: 500;
}

.standard button {
    padding: 14px 145px;
    background-color: white;
    border-color: #2563EB;
    border-radius: 7px;
    border-width: 1px;
    margin-top: 5px;
}

.pro button {
    padding: 15px 160px;
    background-color: #2563EB;
    border-color: #2563EB;
    border-radius: 10px;
    border-width: 1px;
    font-family: inter;
    margin-top: 13px;
}

.pro button a {
    color: #FFFFFF;
    font-family: inter;
    font-weight: 570;
}

.pro .p2 {
    font-family: inter;
    color: #FFFFFF;
    font-weight: 150;
}

.standard {
    padding-left: 7px;
    border-radius: 15px;
}

.standard ul li {
    color: #333333;
}

.team ul li {
    color: #333333;
}

.pro {
    padding-left: 7px;
    border-radius: 15px;
}

.pro ul li {
    color: #FFFFFF;
    font-family: inter;
    font-weight: 230;
}

.pro .p2 {
    color: #FFFFFF;
}

.team {
    padding-left: 7px;
    border-radius: 15px;
}

.pro h1 {
    color: #FFFFFF;
}

.team .p2 {
    color: #888888;
    font-family: inter;
    font-weight: 350;
}

.team .p1 {
    font-family: inter;
    font-weight: 500;
}


.team button {
    padding: 15px 145px;
    border-radius: 8px;
    border-width: 1.8px;
    color: #0D1B2A;
    background-color: white;
    border-color: #0D1B2A;
    margin-top: 6px;
}

.team button a {
    color: #0D1B2A;
    font-family: inter;
    font-weight: 560;
}


.standard li::marker,
.pro li::marker,
.team li::marker {
    color: #2563EB;
}


/* Standard */
.secure-your-spot-cards-parent .standard {
    border: 1px solid #E5E7EB;
    background-color: #FFFFFF;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: flex-start;
    width: 430px;
    height: 520px;
}

.secure-your-spot-cards-parent .standard .p1 {
    color: #888888;
    font-size: 13px;
    font-family: inter;
    font-weight: 570;
}


/* Pro card style*/
.secure-your-spot-cards-parent .pro {
    border: 1px solid #E5E7EB;
    background-color: #0D1B2A;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: flex-start;
    width: 430px;
    height: 520px;
}

.secure-your-spot-cards-parent .pro .p1 {
    color: #93C5FD;
    font-family: inter;
}

/* Team card style */
.secure-your-spot-cards-parent .team {
    border: 1px solid #E5E7EB;
    background-color: #FFFFFF;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: flex-start;
    width: 430px;
    height: 520px;
}

.secure-your-spot-cards-parent .team .p1 {
    color: #888888;
    font-family: inter;
}

hr {
    width: calc(100% - 66px);
    margin-left: 25px;
    border: none;
    border-top: 1px solid #E5E7EB;
}

.pro hr {
    border-top: 1px solid rgba(255, 255, 255, 0.15);
}

.p1 {
    margin-left: 25px;
    margin-top: 40px;
    margin-bottom: 0px;
}




/* Footer section style */
.footer-section-root {
    background-color: #0D1B2A;
    padding-bottom: 30px;
    height: 180px;
}


/* footer top */
.footer-top {
    display: flex;
    align-items: center;
    justify-content: space-between;
    max-width: 1500px;
    margin: 20px auto;
    padding-top: 30px;
}


.social-links {
    display: flex;
    gap: 50px;
    flex-direction: row;
}

.social-links a i {
    font-size: 29px;
}

.footer-top a {
    text-decoration: none;
}

.footer-section-root hr {
    width: 1500px;
    margin: 30px auto;
    border: none;
    border-top: 1px solid rgba(255, 255, 255, 0.15);
}


/* Footer bottom */
.footer-bottom {
    display: flex;
    justify-content: space-between;
    max-width: 1500px;
    margin: 30px auto;
}

.footer-bottom p {
    color: #FFFFFF;
    font-family: inter;
    font-weight: 100;
    font-size: 14px;
}

.footer-bottom a {
    color: #FFFFFF;
    font-family: inter;
    font-weight: 100;
    font-size: 14px;
    text-decoration: none;
}

.footer-tmp {
    display: flex;
    gap: 50px;
}   
