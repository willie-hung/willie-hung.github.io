# MiniPortFolio
## About
A ```light-weight```, ```fast``` and ```all-device compatible``` portfolio for developers, students and designers.
## Overview
![](https://i.imgur.com/882Fvty.png)

## Prerequisites
### Tools
* [Git](https://git-scm.com)
* [VScode](https://code.visualstudio.com)
### VScode extensions
* [Live Sass Compiler](https://marketplace.visualstudio.com/items?itemName=ritwickdey.live-sass)
* [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer)
* [HTML Preview](https://marketplace.visualstudio.com/items?itemName=tht13.html-preview-vscode)

## How to use
Insert following commands in your CLI

```bash
# Clone this repository
$ git clone https://github.com/Willie-The-Lord/Willie-The-Lord.github.io.git

# Go into the repository
$ cd Willie-The-Lord.github.io

# Remove current origin repository
$ git remote remove origin
```

## Get Started
When you open up the directory, navigate to ```index.html``` and right click ```Open with Live Server```. This will open up your browser and now you can modify your portfolio in real-time.

## Instructions
### HTML part
* Open up [index.html](https://github.com/Willie-The-Lord/Willie-The-Lord.github.io/blob/main/index.html)
* Customize the following sections

* Head Section
```html
    <!-- Head Section -->
    <title>Willie Hung | Developer</title>

    <meta name="keywords" content="Willie Hung, Python, C#, C++, AWS, R" />

    <meta name="description" content="Willie Hung | Developer" />

    <link rel="icon" type="image/png" href="./assets/uchicago.png" />

    <meta name="theme-color" content="#36d1dc" />

    <meta property="og:type" content="website" />

    <meta property="og:url" content="https://willie-the-lord.github.io" />
   
    <meta property="og:title" content="Willie Hung | Developer" />
  
    <meta property="og:description" content="My Personal Website" />
    
    <meta
      property="og:image"
      href ="./assets/personal_photo.png"
    />
```
* Hero Section
```html
  <!-- Hero Section -->
    <div id="hero">
      <section class="container">
        <h1 class="hero-title">
          Hi, my name is <span class="text-color-main name">Willie Hung</span>
          <br />
          I'm a CS student @ UChicago.
        </h1>
        <p class="hero-cta">
          <!-- will inherit both button class-->
          <a class="cta-btn cta-btn--hero" href="#about">Get in touch</a>
        </p>
      </section>
    </div>
```
	
* About Section
```html
  <!-- About Section -->
  <section id="about">
    <div class="container center">
      <h2 class="section-title">About Me</h2>
      <div class="row about-wrapper">
        <div class="about-wrapper__image">
          <img
            class="img-fluid"
            src="./assets/personal_photo.png"
            alt="Profile Image"
          />
        </div>
        <div class="about-wrapper__info">
          <p class="about-wrapper__info-text">
            My name is Sung-Jie (Willie) Hung. I was born and raised in Taiwan. 
            I'm currently pursing my Master in Computer Science at University of Chicago. 
            My focus include <button class="cta-btn--about">Software Development</button>, <button class="cta-btn--about">Web Applications</button> and <button class="cta-btn--about">Data Analytics</button>. 
            I'm skilled in <button class="cta-btn--about">Python</button>, <button class="cta-btn--about">C#</button>, <button class="cta-btn--about">C++</button>, and I'm always looking to learn more. 
            In my leisure time, I love running, surfing and all kinds of outdoor sports.
          </p>
          <span class="about-wrapper__cta">
            <a href="https://drive.google.com/file/d/1Gpu-pT4xgaShri0_GaF6hFvQZ5gmDtVe/view?usp=sharing" target=”_blank” class="cta-btn cta-btn--resume">View Resume</a>
          </span>
        </div>
      </div>
    </div>
  </section>
```

```html
<!-- Experience Section -->
<section id="experience">
    <div class="container">
      <h2 class="section-title">Experience</h2>
      <div class="row about-wrapper">
        <div class="about-wrapper__image">
          <img
            class="img-fluid"
            src="./assets/lumentum.jpg"
            alt="Profile Image"
          />
        </div>
        <div class="about-wrapper__info">
          <p class="about-wrapper__info-text">
            <b>Software Engineer Intern</b><br>
            Oct 2021 - Feb 2022<br>
            Skills: <button class="cta-btn--experience">C#</button> <button class="cta-btn--experience">AWS</button> <button class="cta-btn--experience">.NET</button><button class="cta-btn--experience">ShellScripting</button><br>
            Built an auto AWS-Security-Token refresh software application 8 times faster than the original one and reduced memory usage by 71% via C#, .NET, and AWS SDK.
          </p>
        </div>
      </div>
    </div>
  </section>
```

* Projects Section
```html
<!-- Projects Section -->
<section id="projects">
    <div class="container">
      <div class="project-wrapper">
        <h2 class="section-title dark-blue-text">Projects</h2>
        <article class="row">
          <div class="project-wrapper__text">
            <img
            class="img-fluid"
            src="./assets/feature-aws.jpeg"
            alt="Profile Image"
            />
            <p class="project-wrapper__text-info">
              <b>AWS-Security-Token Refresh Application</b><br>
              <button class="cta-btn--projects">C#</button> <button class="cta-btn--projects">.NET</button> <button class="cta-btn--projects">AWS SDK</button><br>
              A .NET project that can refresh your AWS security token 
              and update your AWS credential file automatically on your local machine.
            </p>
            <div class="project-wrapper__text-btns">
              <a
                href="https://github.com/Willie-The-Lord/AWS-Token-Refresh"
                target="_blank"
                rel="noopener noreferrer"
                class="cta-btn cta-btn--resume"
                >Source Code</a
              >
            </div>
          </div>
        </article>
      </div>
    </div>
  </section>
	```
	
* Education Section
```html
<!-- Education Section -->
  <section id="education">
    <div class="container">
      <h2 class="section-title">Education</h2>
      <div class="row about-wrapper">
        <div class="about-wrapper__image">
          <img
            class="img-fluid"
            src="./assets/7.jpeg"
            alt="Profile Image"
          />
        </div>
        <div class="about-wrapper__info">
          <p class="education-wrapper__info-text">
            Master of Science, Computer Science<br> 
            The University of Chicago<br>
              2022-2024
          </p>
        </div>
      </div>
    </div>
  </section>
```
	
* Extracurricular Section
```html
<!-- Extra Curricular Section -->
  <section id="extracurricular">
    <div class="container">
      <h2 class="section-title">Extra Curricular</h2>
        <div class="about-wrapper__info">
            <p class="about-wrapper__info-title"><b>National Tsing Hua University Men's Varsity Track & Field Team</b>
            <p class="about-wrapper__info-title">Sep 2017 - Jan 2022</p> 
            <p class="about-wrapper__info-title"><b>Model United Nation Membership</b></p>
            <p class="about-wrapper__info-title">Apr 2015</p>
        </div>
    </div>
  </section>
```
	
* Contact Curricular Section
```html
<!-- Contact Section -->
<section id="contact">
  <div class="container">
    <h2 class="section-title">Contact</h2>
    <div class="contact-wrapper">
      <a href="mailto:sungjiehung@uchicago.edu" class="cta-btn cta-btn--uchicagomail">sungjiehung@uchicago.edu</a>
    </div>
  </div>
</section>
```
	
* Footer Section
```html
<!-- Footer Section -->
<footer class="footer">
  <div class="container">
    <a href="#hero" class="back-to-top" aria-label="go back to top">
      <i class="fa fa-angle-up fa-2x" aria-hidden="true"></i>
    </a>
    <div class="social-links">
      <a
        href="https://www.linkedin.com/in/willie-hung/"
        target="_blank"
        rel="noopener noreferrer"
        aria-label="linkedin"
      >
        <i class="fa fa-linkedin"></i>
      </a>
</div>
</footer>
```



### CSS part
* Open up [main.css](https://github.com/Willie-The-Lord/Willie-The-Lord.github.io/blob/main/css/main.css)
* Customize the arguments in ```main.css```
* For general CSS skills and syntaxs, check out  [Learn CSS](https://web.dev/learn/css/)
* For responsive web design skills, check out [Responsive Website Design](https://www.w3schools.com/html/html_responsive.asp)



## Deployment
* Navigate to your ```GitHub account``` and create a new repo. Set your new remote for this template repo.
```bash
# Add your new remote origin
$ git remote add origin https://github.com/user.repo.git
```
* When you finish all your changes, add all your files and commit all your changes with a commit message and push the code to your newly created repo.
```bash
# add changes
$ git add .
# commit changes
$ git commit -m 'created my portfolio'
# push the changes (you can also push to other branches you created)
$ git push -u origin main 
```
* Refresh your repo page. It might take up to several minutes.
* Hoooray! Your portfolio should be live at ```https://github_username.github.io/```

## Author
Sung-Jie (Willie) Hung -- <https://github.com/Willie-The-Lord>


## License
This project is licensed under the MIT License - see the [LICENSE](https://github.com/Willie-The-Lord/Willie-The-Lord.github.io/blob/main/license) file for details.

## Acknowledgments
I was motivated and inspired by [Cobi Martínezi's](https://github.com/cobiwave) and [Anil Seervi's](https://github.com/AnilSeervi) PortFolio while learning ```Web Development Techniques```, including ```html```, ```css```, ```javascript```. Their creativity galvanized my enthusiasm towards web development and user interface design.

<h2 align="center">Create Your Own Website Now!!!</h2>