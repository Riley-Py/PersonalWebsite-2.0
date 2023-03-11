<script setup>
</script>

<template>
  <!--Naviagation bar for website-->
  <div class="titlecover">
    <nav class="navbar navbar-expand-lg bg-body-tertiary font-inconsolata">
      <div class="container-fluid">
        <a class="navbar-brand" href="#">
          <img class="image" src="/pi.svg" alt="Logo" width="30" height="24">
          RC
        </a>
        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav"
          aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarNav">
          <ul class="navbar-nav">
            <li class="nav-item">
              <a class="nav-link" href="#about">About Me</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#projects">My Projects</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#contact">Contact</a>
            </li>
          </ul>
        </div>
      </div>
    </nav>
  </div>
  <!--Main title-->
  <div class="container-fluid">
    <div class="banner"> </div>
    <h1 class="beginningtext"> riley cant</h1>
    <h2 class="subtext"> creator, tinkerer, innovator</h2>
  </div>
  <div class="container-fluid">
    <div class="bannerquote"> </div>
    <figure class="quote">
      <blockquote class="blockquote mainquote">
        <p>"The function of good software is to make the complex seem simple"</p>
      </blockquote>
      <figcaption class="blockquote-footer authorquote">
        <cite> Grady Booch</cite>
      </figcaption>
    </figure>

  </div>
  <!--About section (note: move cards with margins and make row m-0 and change out the cards/color (use rows and columns!!))-->
  <div class="container-fluid ">
    <div class="aboutbackground"> </div>
    <div class="row row-cols-1 row-cols-md-2 align-items-center">
      <!--As well, use "col-12 col-md-6" to format the cards correctly-->
      <div class="col">
        <div class="card mx-auto h-100" style="width: 28rem; margin-top: 95px; margin-bottom: 30px">
          <img src="./assets/chromebook.jpg" class="card-img-top" alt="...">
          <div class="card-body">
            <p class="card-text fonts"> I got a Chromebook running Linux as a fun hardware/software project! <a href="https://chromebookdb.com/chromebook/hp-14a-na0031wm-9fy38uaaba/"> Blooglet </a> is the codename for the Chromebook. For more information about how to do this: <a href="https://mrchromebox.tech/"> Chromebook</a></p>
          </div>
        </div>
      </div>
      <div class="col">
        <div class="card mx-auto p-4 h-100"
          style="width: 30rem; margin-top: 95px; margin-right: 10px; margin-bottom: 30px;">
          <div class="card-body">
            <h5 class="card-title titlefont" id="about"> <strong> <u>About Me </u></strong></h5>
            <p class="card-text fonts"> Hello, my name is Riley and here is my personal website to display some of my
              <u>projects</u> and <u>accomplishments</u>. Here are some things that you should know about me
            </p>
            <ul class="fonts">
              <li> Passionate</li>
              <li> Can work under tight deadlines</li>
              <li> Love technology</li>
            </ul>
          </div>
        </div>
      </div>
    </div>
  </div>
  <!--Projects that I've done-->
  <div class="container-fluid">
    <div class="projectsbackground">
      <h1 class="text-center projectfont" id="projects" style="margin-top: 25px"> <strong> <u>My Projects </u> </strong>
      </h1>
      <div class="row row-cols-auto row-cols-md-3 align-items-center m-0">
        <div class="col">
          <div class="card h-100" style="margin-top: 40px; margin-bottom: 20px">
            <video class="video1" width="435" height="auto" controls loop autoplay muted>
              <source src="./assets/Video.mp4" type="video/mp4">
              Not supported
            </video>
            <div class="card-body">
              <h5 class="card-title">Security Alarm System</h5>
              <p class="card-text">This is a project made with an Arduino microcontroller, along with:</p>
              <ul class="card-text">
                <li> LEDs</li>
                <li> LCD screen</li>
                <li> IR remote</li>
                <li> Ultrasonic sensor</li>
              </ul>
            </div>
            <p class="card-text"> There is also a PIN system to enter to disarm the alarm and when the alarm is
              triggered, a sound is played.</p>
            <div class="card-footer">
              <small class="text-muted">Tech used: Arduino, C++, sensors</small>
            </div>
          </div>
        </div>
        <div class="col">
          <div class="card h-100" style="margin-top: 40px; margin-bottom: 20px">
            <img src="./assets/GC.png" class="card-img-top" alt="Not supported"
              style="width: 295px; height:auto; margin-left: auto; margin-right: auto; object-fit:inherit">
            <div class="card-body">
              <h5 class="card-title">Apple Co-Op </h5>
              <p class="card-text"> In the summer of 2022, I did a co-op that was a collaboration between Apple Canada
                and Our Wave Hub. Some of the opportunties presented were: </p>
              <ul class="card-text">
                <li>Learning basic layout design</li>
                <li> Business concepts (how to make a professional keynote)</li>
                <li> Using some tools that big tech companies use (Notion, Miro)</li>
                <li> Learning from industry professionals on pitching</li>
              </ul>
            </div>
            <div class="card-footer">
              <small class="text-muted">Tech used: Swift, Xcode, Miro, Notion</small>
            </div>
          </div>
        </div>
        <div class="col">
          <div class="card h-100" style="margin-top: 40px; margin-bottom: 20px">
            <img src="./assets/website.png" class="card-img-top" alt="Not supported"
              style="width: 435px; height:auto; margin-left: auto; margin-right: auto; object-fit: inherit">
            <div class="card-body">
              <h5 class="card-title">This Website</h5>
              <p class="card-text">With this website that I created, I learn numerous ideas and concepts given a short
                period of time. Some of those sklls were: </p>
              <ul>
                <li> Learning basic design principles</li>
                <li> Learning HTML</li>
                <li> Learning CSS</li>
                <li> Learning how to use a framework so that expandability of the website is easier later on</li>
              </ul>
            </div>
            <div class="card-footer">
              <small class="text-muted">Tech used: CSS, HTML, VueJS, Bootstrap, Firebase</small>
            </div>
          </div>
        </div>
      </div>
      <div class="container-fluid">
        <div class="contactbackground">
          <h1 class="endingtext" id="contact"> <u>contact</u></h1>
          <div class="text-center">
            <div class="btn-group">
              <form target="_blank">
                <button type="submit" formaction="https://github.com/Riley-Py" class="btn btn-outline-secondary">
                  <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor"
                    class="bi bi-github" viewBox="0 0 16 16">
                    <path
                      d="M8 0C3.58 0 0 3.58 0 8c0 3.54 2.29 6.53 5.47 7.59.4.07.55-.17.55-.38 0-.19-.01-.82-.01-1.49-2.01.37-2.53-.49-2.69-.94-.09-.23-.48-.94-.82-1.13-.28-.15-.68-.52-.01-.53.63-.01 1.08.58 1.23.82.72 1.21 1.87.87 2.33.66.07-.52.28-.87.51-1.07-1.78-.2-3.64-.89-3.64-3.95 0-.87.31-1.59.82-2.15-.08-.2-.36-1.02.08-2.12 0 0 .67-.21 2.2.82.64-.18 1.32-.27 2-.27.68 0 1.36.09 2 .27 1.53-1.04 2.2-.82 2.2-.82.44 1.1.16 1.92.08 2.12.51.56.82 1.27.82 2.15 0 3.07-1.87 3.75-3.65 3.95.29.25.54.73.54 1.48 0 1.07-.01 1.93-.01 2.2 0 .21.15.46.55.38A8.012 8.012 0 0 0 16 8c0-4.42-3.58-8-8-8z">
                    </path>
                  </svg>
                  <span class="visually-hidden">Button</span>
                </button>
              </form>
              <form>
                <button type="submit" formaction="mailto:rileyocant@gmail.com" class="btn btn-outline-secondary">
                  <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor"
                    class="bi bi-google" viewBox="0 0 16 16">
                    <path
                      d="M15.545 6.558a9.42 9.42 0 0 1 .139 1.626c0 2.434-.87 4.492-2.384 5.885h.002C11.978 15.292 10.158 16 8 16A8 8 0 1 1 8 0a7.689 7.689 0 0 1 5.352 2.082l-2.284 2.284A4.347 4.347 0 0 0 8 3.166c-2.087 0-3.86 1.408-4.492 3.304a4.792 4.792 0 0 0 0 3.063h.003c.635 1.893 2.405 3.301 4.492 3.301 1.078 0 2.004-.276 2.722-.764h-.003a3.702 3.702 0 0 0 1.599-2.431H8v-3.08h7.545z">
                    </path>
                  </svg>
                  <span class="visually-hidden">Button</span>
                </button>
              </form>
              <form target="_blank">
              <button type="submit" formaction="https://www.linkedin.com/in/riley-o-c314/" class="btn btn-outline-secondary">
                <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor"
                  class="bi bi-linkedin" viewBox="0 0 16 16">
                  <path
                    d="M0 1.146C0 .513.526 0 1.175 0h13.65C15.474 0 16 .513 16 1.146v13.708c0 .633-.526 1.146-1.175 1.146H1.175C.526 16 0 15.487 0 14.854V1.146zm4.943 12.248V6.169H2.542v7.225h2.401zm-1.2-8.212c.837 0 1.358-.554 1.358-1.248-.015-.709-.52-1.248-1.342-1.248-.822 0-1.359.54-1.359 1.248 0 .694.521 1.248 1.327 1.248h.016zm4.908 8.212V9.359c0-.216.016-.432.08-.586.173-.431.568-.878 1.232-.878.869 0 1.216.662 1.216 1.634v3.865h2.401V9.25c0-2.22-1.184-3.252-2.764-3.252-1.274 0-1.845.7-2.165 1.193v.025h-.016a5.54 5.54 0 0 1 .016-.025V6.169h-2.4c.03.678 0 7.225 0 7.225h2.4z">
                  </path>
                </svg>
                <span class="visually-hidden">Button</span>
              </button>
              </form>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>


  <!--DO NOT REMOVE: stuff neeeded before Tuesday next week (today's Wednesday January 18th)
     - Complete "About me" section (image needed on the second card) (done as of Thrusday January 19th)
     - Complete "My Projects" (use card group to create 3 cards and go from there to choose 3 projects)
     - Create a "Contact" section with links to Github, Linkedin, and Gmail
     - Finally, try to polish it a bit and upload it to the web via Google Firebase-->
</template>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Inconsolata:wght@900&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Exo:wght@500&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Cousine&display=swap');

.navbar-nav {
  margin-left: auto;
  font-family: 'Inconsolata', monospace;

}

.navbar-brand {
  font-family: 'Inconsolata', monospace;
  color: #4FB477
}

.navbar-brand:hover {
  color: white;
}

.nav-link {
  color: #4FB477
}

.titlecover {
  position: sticky;
  width: 100%;
  background-color: rgb(50, 50, 65);


}

.nav-link:hover {
  color: white;
}

.banner {
  position: absolute;
  z-index: -1;
  left: 0;
  right: 0;
  height: 300px;
  width: 100%;
  background: rgb(45, 68, 88);
  background-size: contain;

}

.beginningtext {
  margin-top: 30;
  text-transform: uppercase;
  font-family: 'Inconsolata';
  text-align: center;
  color: white;
  font-size: 95px;
}

.subtext {
  text-align: center;
  font-family: "Exo", sans-serif;
  text-transform: uppercase;
  color: rgb(45, 124, 58)
}


.quote {
  text-align: center;
  margin-top: 20px;
  padding-top: 40px;


}

.mainquote {
  color: rgb(14, 13, 13);
  font-size: 30px;
  padding-top: 10px;
  font-family: "Cousine", monospace;
}

.authorquote {
  color: rgb(14, 12, 12);
  font-family: "Cousine", monospace;
  padding-top: 10px;
}

.bannerquote {
  position: absolute;
  left: 0;
  right: 0;
  width: 100%;
  height: 290px;
  background: rgb(0, 128, 104);
  z-index: -1;

}

.aboutbackground {
  position: absolute;
  left: 0;
  right: 0;
  width: 100%;
  height: 1200px;
  background: rgb(45, 68, 88);
  z-index: -1;
}

.fonts {
  font-family: "Inconsolata", monospace;
  font-size: 20px;
}

.titlefont {
  font-family: "Exo", sans-serif;
}

.projectsbackground {
  position: absolute;
  left: 0;
  right: 0;
  width: 100%;
  height: auto;
  background: rgb(124, 152, 133);
  z-index: -1;

}

.projectfont {
  font-family: "Exo", sans-serif;


}

.video1 {
  display: block;
  margin: auto;
}

.contactbackground {
  position: absolute;
  left: 0;
  right: 0;
  width: 100%;
  height: 150px;
  background: rgb(50, 50, 65);
  z-index: -1;
}

.endingtext {
  font-family: "Cousine", monospace;
  text-align: center;
  color: white;
  text-transform: uppercase;
  font-size: 70px;

}
</style>

