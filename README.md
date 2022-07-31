<h1 align="center">My Computer Science Portfolio</h1>

## About 📖

A light-weight, fast and all-device compatible portfolio for developers, students and designers.

## Overview 🎞

![](https://i.imgur.com/882Fvty.png)

## Prerequisites 📝

### Tools
* [Git](https://git-scm.com)
* [VScode](https://code.visualstudio.com)
### VScode extensions
* [Live Sass Compiler](https://marketplace.visualstudio.com/items?itemName=ritwickdey.live-sass)
* [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer)
* [HTML Preview](https://marketplace.visualstudio.com/items?itemName=tht13.html-preview-vscode)


## How to use ❓

Insert following commands in your CLI

```bash
# Clone this repository
$ git clone https://github.com/Willie-The-Lord/Willie-The-Lord.github.io.git

# Go into the repository
$ cd Willie-The-Lord.github.io

# Remove current origin repository
$ git remote remove origin
```

## Get Started 💡

When you open up the directory, navigate to ```index.html``` and right click ```Open with Live Server```. This will open up your browser and now you can modify your portfolio in real-time.

## Instructions 🔧

### HTML part
* Open up [index.html](https://github.com/Willie-The-Lord/Willie-The-Lord.github.io/blob/main/index.html)
* Customize the following sections and replace your personal information in the bracket ```[Enter Here!]```
* Head Section
```html
    <!-- Head Section -->
    <title>Willie Hung | Developer</title>

    <meta name="keywords" content="[Keywords for SEO]" />

    <meta name="description" content="[Description]" />

    <link rel="icon" type="image/png" href="[Icon image]" />

    <meta name="theme-color" content="[Color code]" />

    <meta property="og:type" content="website" />

    <meta property="og:url" content="[GitHub page url]" />
   
    <meta property="og:title" content="[Title when you share your link]" />
  
    <meta property="og:description" content="[Description when you share your link]" />
    
    <meta
      property="og:image"
      href ="[Image when you share your link]"
    />
```
* Hero Section
```html
  <!-- Hero Section -->
    <div id="hero">
      <section class="container">
        <h1 class="hero-title">
          Hi, my name is <span class="text-color-main name">[Your name here]</span>
          <br />
          [Short Description]
        </h1>
        <p class="hero-cta">
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
            Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Aenean commodo ligula eget dolor. Aenean massa. Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Donec quam felis, ultricies nec, pellentesque eu, pretium quis, sem. Nulla consequat massa quis enim. Donec pede justo, fringilla vel, aliquet nec, vulputate eget, arcu. In enim justo, rhoncus ut, imperdiet a, venenatis vitae, justo. Nullam dictum felis eu pede mollis pretium. Integer tincidunt.
          </p>
          <span class="about-wrapper__cta">
            <a href="[Your resume link]" target=”_blank” class="cta-btn cta-btn--resume">View Resume</a>
          </span>
        </div>
      </div>
    </div>
  </section>
```

* Experience Section
```html
<!-- Experience Section -->
<section id="experience">
    <div class="container">
      <h2 class="section-title">Experience</h2>
      <div class="row about-wrapper">
        <div class="about-wrapper__image">
          <img
            class="img-fluid"
            src="[Company logo image]"
            alt="Profile Image"
          />
        </div>
        <div class="about-wrapper__info">
          <p class="about-wrapper__info-text">
            <b>[Enter your title here]</b><br>
            [Enter your date here]<br>
            Skills: <button class="cta-btn--experience">C#</button> <button class="cta-btn--experience">AWS</button> <button class="cta-btn--experience">.NET</button><button class="cta-btn--experience">ShellScripting</button><br>
            Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Aenean commodo ligula eget dolor.
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
          src="[Project Image]"
          alt="Profile Image"
          />
          <p class="project-wrapper__text-info">
            <b>[Enter your project name here]</b><br>
            <button class="cta-btn--projects">C#</button> <button class="cta-btn--projects">.NET</button> <button class="cta-btn--projects">AWS SDK</button><br>
            Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Aenean commodo ligula eget dolor.
          </p>
          <div class="project-wrapper__text-btns">
            <a
              href="[GitHub source code link]"
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
            src="[School logo image]"
            alt="Profile Image"
          />
        </div>
        <div class="about-wrapper__info">
          <p class="education-wrapper__info-text">
            Master of Science, Computer Science<br> 
            The University of Chicago<br>2022-2024
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
            <p class="about-wrapper__info-title"><b>[Your extracurricular experience]</b>
            <p class="about-wrapper__info-title">[Date]</p> 
            <p class="about-wrapper__info-title"><b>[Your extracurricular experience]</b></p>
            <p class="about-wrapper__info-title">[Date]</p>
        </div>
    </div>
  </section>
```
	
* Contact Section
```html
<!-- Contact Section -->
<section id="contact">
  <div class="container">
    <h2 class="section-title">Contact</h2>
    <div class="contact-wrapper">
      <a href="mailto:[email]" class="cta-btn cta-btn--uchicagomail">[Enter your email here]</a>
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
        href="[Enter your linkedin link here]"
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
* Customize the parameters in ```main.css```
* For general CSS skills and syntaxs, check out  [Learn CSS](https://web.dev/learn/css/)
* For responsive web design skills, check out [Responsive Website Design](https://www.w3schools.com/html/html_responsive.asp)


## Deployment 📦

* Navigate to your ```GitHub account``` and ```create a new repo```. Set your new remote for this template repo.
```bash
# Add your new remote origin
$ git remote add origin https://github.com/user.repo.git
```
* When you finish all your changes, add all your files and commit all your changes with a commit message and push the code to your newly created repo.
```bash
# Add all the changes
$ git add .
# Commit changes
$ git commit -m 'created my portfolio'
# Push the changes (you can also push to other branches you created)
$ git push -u origin main 
```
* Refresh your repo page. It might take up to several minutes.
* Hoooray! Your portfolio should be live at ```https://github_username.github.io/```

## Author 🧑🏻‍💻

Sung-Jie (Willie) Hung -- <https://github.com/Willie-The-Lord>


## License 📜

This project is licensed under the MIT License - see the [LICENSE](https://github.com/Willie-The-Lord/Willie-The-Lord.github.io/blob/main/license) file for details.

## Acknowledgments 🎁

I was motivated and inspired by [Cobi Martínezi's](https://github.com/cobiwave) and [Anil Seervi's](https://github.com/AnilSeervi) portFolio while learning ```Web Development Techniques```, including ```html```, ```css```, ```javascript``` etc. Their creativity galvanized my enthusiasm towards web development and user interface design. I refactored some of the code and redesigned the interface. Hope you all enjoy the content!

<h2 align="center">Create Your Own Website Now!!!</h2>