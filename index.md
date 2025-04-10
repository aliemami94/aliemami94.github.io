<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="utf-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <title>Your Name</title>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta name="description" content="Portfolio webpage of Your Name" />
    <meta
      name="keywords"
      content="portfolio,personal website,projects,academic profile,physics"
    />
    <meta name="author" content="Your Name" />
    <link
      rel="stylesheet"
      href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css"
    />
    <link rel="icon" type="image/png" href="./logo.png" />
    <link
      href="https://fonts.googleapis.com/css?family=Montserrat|Open+Sans|Raleway&display=swap"
      rel="stylesheet"
    />
    <link rel="stylesheet" href="css/animate.css" />
    <link rel="stylesheet" href="css/style.css" />
    <link
      rel="stylesheet"
      href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.5/css/bootstrap.min.css"
    />
    <script src="js/modernizr-2.6.2.min.js"></script>
    <script type="module" src="index.js"></script>
    <script src="js/profile-card.js"></script>
  </head>
  <body>
    <div id="colorlib-page">
      <div class="container-wrap">
        <a href="#" class="js-colorlib-nav-toggle colorlib-nav-toggle" data-toggle="collapse" data-target="#navbar" aria-expanded="false" aria-controls="navbar">
          <i></i>
        </a>
        <aside id="colorlib-aside" role="complementary" class="border js-fullheight no-print">
          <div class="text-center">
            <div class="author-img">
              <img alt="profile-img" src="./logo.png" />
            </div>
            <h1 id="colorlib-logo"><a href="./index.html">Your Name</a></h1>
          </div>
          <nav id="colorlib-main-menu" role="navigation" class="navbar" style="padding-top: 2em">
            <div id="navbar" class="collapse">
              <ul>
                <li><a href="#" data-nav-section="about">About</a></li>
                <li><a href="#" data-nav-section="skills">Skills</a></li>
                <li><a href="#" data-nav-section="repos">Repositories</a></li>
                <li><a href="#" data-nav-section="blogs">Blogs</a></li>
                <li><a href="#" data-nav-section="experience">Experience</a></li>
                <li><a href="#" data-nav-section="projects">Projects</a></li>
                <li><a href="#" data-nav-section="education">Education</a></li>
                <li><a href="#" data-nav-section="contact">Contact</a></li>
              </ul>
            </div>
          </nav>
        </aside>
        <div id="colorlib-main">
          <section class="colorlib-about" data-section="about">
            <div class="colorlib-narrow-content">
              <div class="row animate-box" data-animate-effect="fadeInLeft">
                <div class="about-desc">
                  <h1>About</h1>
                  <div id="bio"></div>
                </div>
              </div>
            </div>
          </section>
          <!-- Add other sections similarly -->
          <section class="colorlib-footer no-print">
            <div class="colorlib-narrow-content">
              <p id="visitorCount">Visitor Count: Loading...</p>
            </div>
          </section>
        </div>
      </div>
    </div>
    <script src="js/jquery.min.js"></script>
    <script src="js/jquery.waypoints.min.js"></script>
    <script src="js/main.js"></script>

    <script type="module">
      import { initializeApp } from "https://www.gstatic.com/firebasejs/11.4.0/firebase-app.js";
      import { getAnalytics } from "https://www.gstatic.com/firebasejs/11.4.0/firebase-analytics.js";
      import {
        getFirestore,
        doc,
        getDoc,
        setDoc,
        updateDoc,
      } from "https://www.gstatic.com/firebasejs/11.4.0/firebase-firestore.js";

      const firebaseConfig = {
        apiKey: "AIzaSyBM5-cQema1PzjpTPtCxIdmvTrWH2p1nc8",
        authDomain: "vinaysomawat-portfolio.firebaseapp.com",
        projectId: "vinaysomawat-portfolio",
        storageBucket: "vinaysomawat-portfolio.appspot.com",
        messagingSenderId: "996992279996",
        appId: "1:996992279996:web:f296555eef216d501337b9",
        measurementId: "G-8PVX0MLGSK"
      };

      const app = initializeApp(firebaseConfig);
      const analytics = getAnalytics(app);
      const db = getFirestore(app);
      const counterRef = doc(db, "visitors", "counter");

      async function updateVisitorCount() {
        try {
          const docSnap = await getDoc(counterRef);
          if (docSnap.exists()) {
            let newCount = docSnap.data().count + 1;
            await updateDoc(counterRef, { count: newCount });
            document.getElementById("visitorCount").innerText = `Visitor Count: ${newCount}`;
          } else {
            await setDoc(counterRef, { count: 1 });
            document.getElementById("visitorCount").innerText = "Visitor Count: 1";
          }
        } catch (error) {
          console.error("Error updating visitor count:", error);
        }
      }

      updateVisitorCount();
    </script>
  </body>
</html>
