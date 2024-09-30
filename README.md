<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <meta http-equiv="X-UA-Compatible" content="ie=edge" />
    <link
      href="https://fonts.googleapis.com/css?family=Lato"
      rel="stylesheet"
    />
    <link rel="stylesheet" href="stylesheets/css/main.css" />
    <title>Ashutosh Kumar</title>
  </head>
  <body bgcolor="green">
<style>
html {
  scroll-behavior: smooth;
}
body {
  margin: 0;
  font-family: "Lato", sans-serif;
}
body #navbar {
  top: 0;
  width: 100%;
  position: fixed;
}
body #navbar ul {
  margin: 0;
  color: #fff;
  display: flex;
  background: #009688;
  justify-content: flex-end;
}
body #navbar ul li {
  margin: 20px 20px;
  list-style-type: none;
}
body #navbar ul li a {
  all: unset;
  cursor: pointer;
}
body main #welcome-section {
  background-size: cover;
  background-repeat: no-repeat;
  background-image: linear-gradient(rgba(0, 0, 0, 0.12), rgba(0, 0, 0, 0.37)), url("https://raw.githubusercontent.com/Confidence-Okoghenun/Responsive-Web-Design-Projects---Build-a-Personal-Portfolio-Webpage/master/image/cover1.jpg");
}
body main #welcome-section .welcome-contents {
  color: white;
  margin: 0 10%;
  font-size: 1.3em;
  min-height: 70vh;
  padding-top: 30vh;
}
@media (max-width: 600px) {
  body main #welcome-section .welcome-contents {
    font-size: 1.1em;
    padding-top: 10vh;
    min-height: 90vh;
  }
}
body main #welcome-section .welcome-contents h1 {
  font-size: 3em;
}
body main #welcome-section .welcome-contents div {
  font-size: 1.5em;
}
body main #projects {
  background: #009688;
}
body main #projects .projects-title {
  color: white;
  font-size: 2em;
  padding: 20px 0;
  font-weight: bold;
  text-align: center;
  letter-spacing: 2px;
}
body main #projects .porjects-container {
  display: flex;
  flex-wrap: wrap;
  padding: 0 0 30px;
  justify-content: center;
}
@media (max-width: 880px) {
  body main #projects .porjects-container .hide-on-moblie {
    display: none;
  }
}
body main #projects .porjects-container .project-tile {
  border: 2px solid white;
  margin: 20px;
}
body main #projects .porjects-container .project-tile-image img {
  width: 250px;
}
body main #projects .porjects-container .project-tile-link {
  text-align: center;
  margin-bottom: 10px;
}
body main #projects .porjects-container .project-tile-link a {
  color: white;
}
body main #contact {
  margin: 30px 0;
  min-height: 30vh;
}
body main #contact .contact-header {
  font-size: 2em;
  padding: 20px 0;
  font-weight: bold;
  text-align: center;
  letter-spacing: 2px;
}
body main #contact .contact-me {
  display: flex;
  margin-top: 40px;
  justify-content: space-evenly;
}
body main #contact .contact-me-link a img {
  width: 50px;
}
body footer {
  color: white;
  padding: 20px 0;
  text-align: center;
  background: #048e81;
}

/*# sourceMappingURL=main.css.map */
</style>
    <nav id="navbar">
      <ul>
        <li><a href="#welcome-section">About</a></li>
        <li><a href="#projects">Projects</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </nav>
    <main>
      <section id="welcome-section">
        <div class="welcome-contents">
          <h1>Hey there!</h1>
          <div>
            I'm Ashutosh Kumar, a front-end web developer and UX/UI designer, with
            practical experience in project management, branding strategy, and
            creative direction; devoted to functional programming and
            information architecture. I design, build, operate & sometimes
            rescue full-stack Web applications.I am also a ex-michaelite, ex-dominician 
           ex-amitian and currently a Llyodian.I am pursuing my master's in computer application from Llyod institute
            of engineering and technology,Greater Noida in 2024.I am
            a computer science graduate.
            (NOTE: you can contact me via this number:+917739675920 or if you have any query you can mail me
            on ashutoshkumar05rahul@gmail.com)
          </div>
        </div>
      </section>
      <section id="projects">
        <div class="projects-title">Projects</div>
        <div class="porjects-container">
          <div class="project-tile">
            <div class="project-tile-image">
              <img src="https://raw.githubusercontent.com/Confidence-Okoghenun/Responsive-Web-Design-Projects---Build-a-Personal-Portfolio-Webpage/master/image/1.png" alt="The Great RGB Color Guessing Game" />
            </div>
            <div class="project-tile-link">
              <a href="https://codepen.io/ConfidenceOkoghenun/full/aGZKao"
                >Color Guessing Game</a
              >
            </div>
          </div>
          <div class="project-tile">
            <div class="project-tile-image">
              <img src="https://raw.githubusercontent.com/Confidence-Okoghenun/Responsive-Web-Design-Projects---Build-a-Personal-Portfolio-Webpage/master/image/2.png" alt="To Do List" />
            </div>
            <div class="project-tile-link">
              <a href="https://codepen.io/ConfidenceOkoghenun/full/rvYWxQ"
                >To Do List</a
              >
            </div>
          </div>
          <div class="project-tile">
            <div class="project-tile-image">
              <img src="https://raw.githubusercontent.com/Confidence-Okoghenun/Responsive-Web-Design-Projects---Build-a-Personal-Portfolio-Webpage/master/image/3.png" alt="Quote Engine" />
            </div>
            <div class="project-tile-link">
              <a href="https://codepen.io/ConfidenceOkoghenun/full/yjvXjr"
                >Quote Engine</a
              >
            </div>
          </div>
          <div class="project-tile hide-on-moblie">
            <div class="project-tile-image">
              <img src="https://raw.githubusercontent.com/Confidence-Okoghenun/Responsive-Web-Design-Projects---Build-a-Personal-Portfolio-Webpage/master/image/4.png" alt="Address Book" />
            </div>
            <div class="project-tile-link">
              <a href="https://codepen.io/ConfidenceOkoghenun/full/MVzgGE"
                >Address Book</a
              >
            </div>
          </div>
          <div class="project-tile">
            <div class="project-tile-image">
              <img
                src="https://raw.githubusercontent.com/Confidence-Okoghenun/Responsive-Web-Design-Projects---Build-a-Personal-Portfolio-Webpage/master/image/5.png"
                alt="Tribute Page of Charles Taze Russell"
              />
            </div>
            <div class="project-tile-link">
              <a href="https://codepen.io/ConfidenceOkoghenun/full/jZRXpb"
                >Tribute Page</a
              >
            </div>
          </div>
          <div class="project-tile">
            <div class="project-tile-image">
              <img src="https://raw.githubusercontent.com/Confidence-Okoghenun/Responsive-Web-Design-Projects---Build-a-Personal-Portfolio-Webpage/master/image/6.png" alt="Purrfect Match" />
            </div>
            <div class="project-tile-link">
              <a href="https://codepen.io/ConfidenceOkoghenun/full/LdBEzX"
                >Purrfect Match</a
              >
            </div>
          </div>
          <div class="project-tile">
            <div class="project-tile-image">
              <img src="https://raw.githubusercontent.com/Confidence-Okoghenun/Responsive-Web-Design-Projects---Build-a-Personal-Portfolio-Webpage/master/image/7.png" alt="GitFinder" />
            </div>
            <div class="project-tile-link">
              <a href="https://codepen.io/ConfidenceOkoghenun/full/jpWgXV"
                >GitFinder</a
              >
            </div>
          </div>
          <div class="project-tile">
            <div class="project-tile-image">
              <img src="https://raw.githubusercontent.com/Confidence-Okoghenun/Responsive-Web-Design-Projects---Build-a-Personal-Portfolio-Webpage/master/image/8.png" alt="Loan Calculator" />
            </div>
            <div class="project-tile-link">
              <a href="https://codepen.io/ConfidenceOkoghenun/full/MXQzaY"
                >Loan Calculator</a
              >
            </div>
          </div>
          <div class="project-tile">
            <div class="project-tile-image">
              <img src="https://raw.githubusercontent.com/Confidence-Okoghenun/Responsive-Web-Design-Projects---Build-a-Personal-Portfolio-Webpage/master/image/9.png" alt="Cat Photo App" />
            </div>
            <div class="project-tile-link">
              <a href="https://codepen.io/ConfidenceOkoghenun/full/BGjrYb"
                >Cat Photo App</a
              >
            </div>
          </div>
        </div>
      </section>
      <section id="contact">
        <div class="contact-header">Where to find me</div>
        <div class="contact-me">
          <div class="contact-me-link">
            <a href="https://github.com/ashu64" target="_blank" id="profile-link"
              ><img src="data:image/svg+xml;base64,PD94bWwgdmVyc2lvbj0iMS4wIiBlbmNvZGluZz0iaXNvLTg4NTktMSI/Pg0KPCEtLSBHZW5lcmF0%0D%0Ab3I6IEFkb2JlIElsbHVzdHJhdG9yIDE2LjAuMCwgU1ZHIEV4cG9ydCBQbHVnLUluIC4gU1ZHIFZl%0D%0AcnNpb246IDYuMDAgQnVpbGQgMCkgIC0tPg0KPCFET0NUWVBFIHN2ZyBQVUJMSUMgIi0vL1czQy8v%0D%0ARFREIFNWRyAxLjEvL0VOIiAiaHR0cDovL3d3dy53My5vcmcvR3JhcGhpY3MvU1ZHLzEuMS9EVEQv%0D%0Ac3ZnMTEuZHRkIj4NCjxzdmcgdmVyc2lvbj0iMS4xIiBpZD0iQ2FwYV8xIiB4bWxucz0iaHR0cDov%0D%0AL3d3dy53My5vcmcvMjAwMC9zdmciIHhtbG5zOnhsaW5rPSJodHRwOi8vd3d3LnczLm9yZy8xOTk5%0D%0AL3hsaW5rIiB4PSIwcHgiIHk9IjBweCINCgkgd2lkdGg9IjQzOC41MzZweCIgaGVpZ2h0PSI0Mzgu%0D%0ANTM2cHgiIHZpZXdCb3g9IjAgMCA0MzguNTM2IDQzOC41MzYiIHN0eWxlPSJlbmFibGUtYmFja2dy%0D%0Ab3VuZDpuZXcgMCAwIDQzOC41MzYgNDM4LjUzNjsiDQoJIHhtbDpzcGFjZT0icHJlc2VydmUiPg0K%0D%0APGc+DQoJPGc+DQoJCTxwYXRoIGQ9Ik0xNTguMTczLDM1Mi41OTljLTMuMDQ5LDAuNTY4LTQuMzgx%0D%0ALDEuOTk5LTMuOTk5LDQuMjgxYzAuMzgsMi4yODMsMi4wOTMsMy4wNDYsNS4xMzgsMi4yODMNCgkJ%0D%0ACWMzLjA0OS0wLjc2LDQuMzgtMi4wOTUsMy45OTctMy45OTdDMTYyLjkzMSwzNTMuMDc0LDE2MS4y%0D%0AMTgsMzUyLjIxNiwxNTguMTczLDM1Mi41OTl6Ii8+DQoJCTxwYXRoIGQ9Ik0xNDEuODk4LDM1NC44%0D%0AODVjLTMuMDQ2LDAtNC41NjgsMS4wNDEtNC41NjgsMy4xMzljMCwyLjQ3NCwxLjYxOSwzLjUxOCw0%0D%0ALjg1MywzLjEzOGMzLjA0NiwwLDQuNTctMS4wNDcsNC41Ny0zLjEzOA0KCQkJQzE0Ni43NTMsMzU1%0D%0ALjU1MywxNDUuMTM0LDM1NC41MDIsMTQxLjg5OCwzNTQuODg1eiIvPg0KCQk8cGF0aCBkPSJNMTE5%0D%0ALjYyOSwzNTQuMDIyYy0wLjc2LDIuMDk1LDAuNDc4LDMuNTE5LDMuNzExLDQuMjg0YzIuODU1LDEu%0D%0AMTM3LDQuNjY0LDAuNTY4LDUuNDI0LTEuNzE0DQoJCQljMC41NzItMi4wOTEtMC42NjYtMy42MS0z%0D%0ALjcxMS00LjU2OEMxMjIuMTk3LDM1MS4yNjUsMTIwLjM5LDM1MS45MjIsMTE5LjYyOSwzNTQuMDIy%0D%0AeiIvPg0KCQk8cGF0aCBkPSJNNDE0LjQxLDI0LjEyM0MzOTguMzI2LDguMDQyLDM3OC45NjQsMCwz%0D%0ANTYuMzA5LDBIODIuMjI1QzU5LjU3NywwLDQwLjIwOCw4LjA0MiwyNC4xMjMsMjQuMTIzDQoJCQlD%0D%0AOC4wNDIsNDAuMjA3LDAsNTkuNTc2LDAsODIuMjI1djI3NC4wODhjMCwyMi42NSw4LjA0Miw0Mi4w%0D%0AMTcsMjQuMTIzLDU4LjA5OGMxNi4wODQsMTYuMDg0LDM1LjQ1NCwyNC4xMjYsNTguMTAyLDI0LjEy%0D%0ANmg2My45NTMNCgkJCWM0LjE4NCwwLDcuMzI3LTAuMTQ0LDkuNDItMC40MjRjMi4wOTItMC4yODgs%0D%0ANC4xODQtMS41MjYsNi4yNzktMy43MTdjMi4wOTYtMi4xODcsMy4xNC01LjM3NiwzLjE0LTkuNTYy%0D%0ADQoJCQljMC0wLjU2OC0wLjA1LTcuMDQ2LTAuMTQ0LTE5LjQxN2MtMC4wOTctMTIuMzc1LTAuMTQ0%0D%0ALTIyLjE3Ni0wLjE0NC0yOS40MWwtNi41NjcsMS4xNDNjLTQuMTg3LDAuNzYtOS40NjksMS4wOTUt%0D%0AMTUuODQ2LDAuOTk5DQoJCQljLTYuMzc0LTAuMDk2LTEyLjk5LTAuNzYtMTkuODQxLTEuOTk4Yy02%0D%0ALjg1NS0xLjIzOS0xMy4yMjktNC4wOTMtMTkuMTMtOC41NjJjLTUuODk4LTQuNDc3LTEwLjA4NS0x%0D%0AMC4zMjgtMTIuNTYtMTcuNTU5DQoJCQlsLTIuODU2LTYuNTcxYy0xLjkwMy00LjM3My00Ljg5OS05%0D%0ALjIyOS04Ljk5Mi0xNC41NTRjLTQuMDkzLTUuMzMyLTguMjMyLTguOTQ5LTEyLjQxOS0xMC44NTJs%0D%0ALTEuOTk5LTEuNDI4DQoJCQljLTEuMzMxLTAuOTUxLTIuNTY4LTIuMDk4LTMuNzExLTMuNDI5Yy0x%0D%0ALjE0MS0xLjMzNS0xLjk5Ny0yLjY2OS0yLjU2OC0zLjk5N2MtMC41NzEtMS4zMzUtMC4wOTctMi40%0D%0AMywxLjQyNy0zLjI4OQ0KCQkJYzEuNTI0LTAuODU1LDQuMjgxLTEuMjc5LDguMjgtMS4yNzlsNS43%0D%0AMDgsMC44NTVjMy44MDgsMC43Niw4LjUxNiwzLjA0MiwxNC4xMzQsNi44NTFjNS42MTQsMy44MDYs%0D%0AMTAuMjI5LDguNzU0LDEzLjg0NiwxNC44NDMNCgkJCWM0LjM4LDcuODA2LDkuNjU3LDEzLjc1LDE1%0D%0ALjg0NiwxNy44NDNjNi4xODQsNC4wOTcsMTIuNDE5LDYuMTQzLDE4LjY5OSw2LjE0M3MxMS43MDQt%0D%0AMC40NzYsMTYuMjc0LTEuNDI0DQoJCQljNC41NjUtMC45NTQsOC44NDgtMi4zODUsMTIuODQ3LTQu%0D%0AMjg4YzEuNzEzLTEyLjc1MSw2LjM3Ny0yMi41NTksMTMuOTg4LTI5LjQxYy0xMC44NDgtMS4xNDMt%0D%0AMjAuNjAyLTIuODU0LTI5LjI2NS01LjE0DQoJCQljLTguNjU4LTIuMjg2LTE3LjYwNS01Ljk5NS0y%0D%0ANi44MzUtMTEuMTM2Yy05LjIzNC01LjE0LTE2Ljg5NC0xMS41MTItMjIuOTg1LTE5LjEzYy02LjA5%0D%0ALTcuNjE4LTExLjA4OC0xNy42MS0xNC45ODctMjkuOTc4DQoJCQljLTMuOTAxLTEyLjM3NS01Ljg1%0D%0AMi0yNi42NTItNS44NTItNDIuODI5YzAtMjMuMDI5LDcuNTIxLTQyLjYzNywyMi41NTctNTguODE0%0D%0AYy03LjA0NC0xNy4zMi02LjM3OS0zNi43MzIsMS45OTctNTguMjQyDQoJCQljNS41Mi0xLjcxNCwx%0D%0AMy43MDYtMC40MjgsMjQuNTU0LDMuODU1YzEwLjg1LDQuMjg2LDE4Ljc5NCw3Ljk1MSwyMy44NCwx%0D%0AMC45OTJjNS4wNDYsMy4wNDIsOS4wODksNS42MTQsMTIuMTM1LDcuNzENCgkJCWMxNy43MDUtNC45%0D%0ANDksMzUuOTc2LTcuNDIzLDU0LjgxOC03LjQyM2MxOC44NDEsMCwzNy4xMTUsMi40NzQsNTQuODIx%0D%0ALDcuNDIzbDEwLjg0OS02Ljg1MmM3LjQyNi00LjU3LDE2LjE4LTguNzU3LDI2LjI2OS0xMi41NjIN%0D%0ACgkJCWMxMC4wODgtMy44MDYsMTcuNzk1LTQuODU0LDIzLjEyNy0zLjE0YzguNTYyLDIxLjUxLDku%0D%0AMzI4LDQwLjkyMiwyLjI3OSw1OC4yNDFjMTUuMDM2LDE2LjE3OSwyMi41NTksMzUuNzg2LDIyLjU1%0D%0AOSw1OC44MTUNCgkJCWMwLDE2LjE4LTEuOTUxLDMwLjUwNS01Ljg1Miw0Mi45NjljLTMuODk4LDEy%0D%0ALjQ2Ny04LjkzOSwyMi40NjMtMTUuMTMsMjkuOTgxYy02LjE4NCw3LjUxOS0xMy44OTQsMTMuODQz%0D%0ALTIzLjEyNCwxOC45ODYNCgkJCWMtOS4yMzIsNS4xMzctMTguMTc4LDguODUzLTI2Ljg0LDExLjEz%0D%0AMmMtOC42NjEsMi4yODYtMTguNDE0LDQuMDA0LTI5LjI2Myw1LjE0N2M5Ljg5MSw4LjU2MiwxNC44%0D%0AMzksMjIuMDcyLDE0LjgzOSw0MC41Mzh2NjguMjM4DQoJCQljMCwzLjIzNywwLjQ3Miw1Ljg1Miwx%0D%0ALjQyNCw3Ljg1MWMwLjk1OCwxLjk5OCwyLjQ3OCwzLjM3NCw0LjU3MSw0LjE0MWMyLjEwMiwwLjc2%0D%0ALDMuOTQ5LDEuMjM1LDUuNTcxLDEuNDI0DQoJCQljMS42MjIsMC4xOTEsMy45NDksMC4yODcsNi45%0D%0AOTUsMC4yODdoNjMuOTUzYzIyLjY0OCwwLDQyLjAxOC04LjA0Miw1OC4wOTUtMjQuMTI2YzE2LjA4%0D%0ANC0xNi4wODQsMjQuMTI2LTM1LjQ1NCwyNC4xMjYtNTguMTAyDQoJCQlWODIuMjI1QzQzOC41MzMs%0D%0ANTkuNTc2LDQzMC40OTEsNDAuMjA0LDQxNC40MSwyNC4xMjN6Ii8+DQoJCTxwYXRoIGQ9Ik04Ni43%0D%0AOTMsMzE5LjE5NWMtMS4zMzEsMC45NDgtMS4xNDEsMi40NzEsMC41NzIsNC41NjVjMS45MDYsMS45%0D%0AMDIsMy40MjcsMi4xODksNC41NywwLjg1NQ0KCQkJYzEuMzMxLTAuOTQ4LDEuMTQxLTIuNDcxLTAu%0D%0ANTc1LTQuNTY5Qzg5LjQ1OCwzMTguMzM2LDg3LjkzNiwzMTguMDQ5LDg2Ljc5MywzMTkuMTk1eiIv%0D%0APg0KCQk8cGF0aCBkPSJNNzcuMzc0LDMxMi4wNTdjLTAuNTcsMS4zMzUsMC4wOTYsMi40NzgsMS45%0D%0AOTksMy40MjZjMS41MjEsMC45NTUsMi43NjIsMC43NjcsMy43MTEtMC41NjgNCgkJCWMwLjU3LTEu%0D%0AMzM1LTAuMDk2LTIuNDc4LTEuOTk5LTMuNDMzQzc5LjE4MiwzMTAuOTEsNzcuOTQ1LDMxMS4xMDIs%0D%0ANzcuMzc0LDMxMi4wNTd6Ii8+DQoJCTxwYXRoIGQ9Ik05NS42NDYsMzMwLjMzMWMtMS43MTUsMC45%0D%0ANDgtMS43MTUsMi42NjYsMCw1LjEzN2MxLjcxMywyLjQ3OCwzLjMyOCwzLjE0Miw0Ljg1MywxLjk5%0D%0AOGMxLjcxNC0xLjMzNCwxLjcxNC0zLjE0MiwwLTUuNDI3DQoJCQlDOTguOTc4LDMyOS41NzEsOTcu%0D%0AMzU5LDMyOC45OTMsOTUuNjQ2LDMzMC4zMzF6Ii8+DQoJCTxwYXRoIGQ9Ik0xMDUuNjQxLDM0My4x%0D%0ANzRjLTEuNzE0LDEuNTI2LTEuMzM2LDMuMzI3LDEuMTQyLDUuNDI4YzIuMjgxLDIuMjc5LDQuMTg1%0D%0ALDIuNTY2LDUuNzA4LDAuODQ5DQoJCQljMS41MjQtMS41MTksMS4xNDMtMy4zMjYtMS4xNDItNS40%0D%0AMkMxMDkuMDY4LDM0MS43NTEsMTA3LjE2NCwzNDEuNDYzLDEwNS42NDEsMzQzLjE3NHoiLz4NCgk8%0D%0AL2c+DQo8L2c+DQo8Zz4NCjwvZz4NCjxnPg0KPC9nPg0KPGc+DQo8L2c+DQo8Zz4NCjwvZz4NCjxn%0D%0APg0KPC9nPg0KPGc+DQo8L2c+DQo8Zz4NCjwvZz4NCjxnPg0KPC9nPg0KPGc+DQo8L2c+DQo8Zz4N%0D%0ACjwvZz4NCjxnPg0KPC9nPg0KPGc+DQo8L2c+DQo8Zz4NCjwvZz4NCjxnPg0KPC9nPg0KPGc+DQo8%0D%0AL2c+DQo8L3N2Zz4NCg==" alt="Github"
            /></a>
          </div>
          <div class="contact-me-link">
            <a href="https://twitter.com/@Ashutos47235354" target="_blank"><img src="data:image/svg+xml;base64,PD94bWwgdmVyc2lvbj0iMS4wIiBlbmNvZGluZz0iaXNvLTg4NTktMSI/Pg0KPCEtLSBHZW5lcmF0%0D%0Ab3I6IEFkb2JlIElsbHVzdHJhdG9yIDE5LjAuMCwgU1ZHIEV4cG9ydCBQbHVnLUluIC4gU1ZHIFZl%0D%0AcnNpb246IDYuMDAgQnVpbGQgMCkgIC0tPg0KPHN2ZyB2ZXJzaW9uPSIxLjEiIGlkPSJDYXBhXzEi%0D%0AIHhtbG5zPSJodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2ZyIgeG1sbnM6eGxpbms9Imh0dHA6Ly93%0D%0Ad3cudzMub3JnLzE5OTkveGxpbmsiIHg9IjBweCIgeT0iMHB4Ig0KCSB2aWV3Qm94PSIwIDAgNDg2%0D%0ALjM5MiA0ODYuMzkyIiBzdHlsZT0iZW5hYmxlLWJhY2tncm91bmQ6bmV3IDAgMCA0ODYuMzkyIDQ4%0D%0ANi4zOTI7IiB4bWw6c3BhY2U9InByZXNlcnZlIj4NCjxnPg0KCTxnPg0KCQk8Zz4NCgkJCTxwYXRo%0D%0AIHN0eWxlPSJmaWxsOiMwMTAwMDI7IiBkPSJNMzk1LjE5MywwSDkxLjE5OEM0MC44MjYsMCwwLDQw%0D%0ALjgyNiwwLDkxLjE5OHYzMDMuOTk1YzAsNTAuMzcyLDQwLjgyNiw5MS4xOTgsOTEuMTk4LDkxLjE5%0D%0AOA0KCQkJCWgzMDMuOTk1YzUwLjM3MiwwLDkxLjE5OC00MC44MjcsOTEuMTk4LTkxLjE5OFY5MS4x%0D%0AOThDNDg2LjM5Miw0MC44MjYsNDQ1LjU2NSwwLDM5NS4xOTMsMHogTTM2NC4xODYsMTg4LjU5OGww%0D%0ALjE4Miw3Ljc1Mg0KCQkJCWMwLDc5LjE2LTYwLjIyMSwxNzAuMzU5LTE3MC4zNTksMTcwLjM1OWMt%0D%0AMzMuODA0LDAtNjUuMjY4LTkuOTEtOTEuNzc2LTI2LjkwNGM0LjY4MiwwLjU0Nyw5LjQ1NCwwLjg1%0D%0AMSwxNC4yODgsMC44NTENCgkJCQljMjguMDU5LDAsNTMuODY4LTkuNTc2LDc0LjM1Ny0yNS42Mjdj%0D%0ALTI2LjIwNC0wLjQ4Ni00OC4zMDUtMTcuODE0LTU1LjkzNS00MS41ODZjMy42NzgsMC42NjksNy4z%0D%0AODcsMS4wMzQsMTEuMjc4LDEuMDM0DQoJCQkJYzUuNDcyLDAsMTAuNzYxLTAuNjk5LDE1Ljc3Ny0y%0D%0ALjA2N2MtMjcuMzktNS41MzMtNDguMDMxLTI5LjctNDguMDMxLTU4LjcwMXYtMC43NmM4LjA4Niw0%0D%0ALjQ5OSwxNy4yOTcsNy4xNzQsMjcuMTE2LDcuNTA5DQoJCQkJYy0xNi4wNTEtMTAuNzMxLTI2LjYz%0D%0ALTI5LjA2Mi0yNi42My00OS44MjVjMC0xMC45NzQsMi45NDktMjEuMjQ5LDguMDg2LTMwLjA5NWMy%0D%0AOS41MTgsMzYuMjM2LDczLjY1OCw2MC4wNjksMTIzLjQyMiw2Mi41NjINCgkJCQljLTEuMDM0LTQu%0D%0AMzc4LTEuNTUtOC45NjgtMS41NS0xMy42NDljMC0zMy4wNDQsMjYuODEyLTU5Ljg1Nyw1OS44ODct%0D%0ANTkuODU3YzE3LjIwNiwwLDMyLjc3MSw3LjI2NSw0My43MTQsMTguOTA4DQoJCQkJYzEzLjYxOS0y%0D%0ALjcwNiwyNi40NDgtNy42OTEsMzguMDMtMTQuNTMxYy00LjQ2OSwxMy45ODQtMTMuOTUzLDI1Ljcx%0D%0AOC0yNi4zMjYsMzMuMTM1YzEyLjA2OS0xLjQyOSwyMy42NTEtNC42ODIsMzQuMzgyLTkuNDI0DQoJ%0D%0ACQkJQzM4Ni4wNzMsMTY5LjY1OSwzNzUuODg5LDE4MC4yMDgsMzY0LjE4NiwxODguNTk4eiIvPg0K%0D%0ACQk8L2c+DQoJPC9nPg0KCTxnPg0KCTwvZz4NCgk8Zz4NCgk8L2c+DQoJPGc+DQoJPC9nPg0KCTxn%0D%0APg0KCTwvZz4NCgk8Zz4NCgk8L2c+DQoJPGc+DQoJPC9nPg0KCTxnPg0KCTwvZz4NCgk8Zz4NCgk8%0D%0AL2c+DQoJPGc+DQoJPC9nPg0KCTxnPg0KCTwvZz4NCgk8Zz4NCgk8L2c+DQoJPGc+DQoJPC9nPg0K%0D%0ACTxnPg0KCTwvZz4NCgk8Zz4NCgk8L2c+DQoJPGc+DQoJPC9nPg0KPC9nPg0KPGc+DQo8L2c+DQo8%0D%0AZz4NCjwvZz4NCjxnPg0KPC9nPg0KPGc+DQo8L2c+DQo8Zz4NCjwvZz4NCjxnPg0KPC9nPg0KPGc+%0D%0ADQo8L2c+DQo8Zz4NCjwvZz4NCjxnPg0KPC9nPg0KPGc+DQo8L2c+DQo8Zz4NCjwvZz4NCjxnPg0K%0D%0APC9nPg0KPGc+DQo8L2c+DQo8Zz4NCjwvZz4NCjxnPg0KPC9nPg0KPC9zdmc+DQo=" alt="Twitter"/></a>
          </div>
          <div class="contact-me-link">
            <a href="https://linkedin.com/in/ashutosh-kumar-8183381aa" target="_blank" id="profile-link">
<img src="data:image/svg+xml;base64,PD94bWwgdmVyc2lvbj0iMS4wIiBlbmNvZGluZz0iaXNvLTg4NTktMSI/Pg0KPCEtLSBHZW5lcmF0%0D%0Ab3I6IEFkb2JlIElsbHVzdHJhdG9yIDE2LjAuMCwgU1ZHIEV4cG9ydCBQbHVnLUluIC4gU1ZHIFZl%0D%0AcnNpb246IDYuMDAgQnVpbGQgMCkgIC0tPg0KPCFET0NUWVBFIHN2ZyBQVUJMSUMgIi0vL1czQy8v%0D%0ARFREIFNWRyAxLjEvL0VOIiAiaHR0cDovL3d3dy53My5vcmcvR3JhcGhpY3MvU1ZHLzEuMS9EVEQv%0D%0Ac3ZnMTEuZHRkIj4NCjxzdmcgdmVyc2lvbj0iMS4xIiBpZD0iQ2FwYV8xIiB4bWxucz0iaHR0cDov%0D%0AL3d3dy53My5vcmcvMjAwMC9zdmciIHhtbG5zOnhsaW5rPSJodHRwOi8vd3d3LnczLm9yZy8xOTk5%0D%0AL3hsaW5rIiB4PSIwcHgiIHk9IjBweCINCgkgd2lkdGg9IjUxMHB4IiBoZWlnaHQ9IjUxMHB4IiB2%0D%0AaWV3Qm94PSIwIDAgNTEwIDUxMCIgc3R5bGU9ImVuYWJsZS1iYWNrZ3JvdW5kOm5ldyAwIDAgNTEw%0D%0AIDUxMDsiIHhtbDpzcGFjZT0icHJlc2VydmUiPg0KPGc+DQoJPGcgaWQ9InBvc3QtbGlua2VkaW4i%0D%0APg0KCQk8cGF0aCBkPSJNNDU5LDBINTFDMjIuOTUsMCwwLDIyLjk1LDAsNTF2NDA4YzAsMjguMDUs%0D%0AMjIuOTUsNTEsNTEsNTFoNDA4YzI4LjA1LDAsNTEtMjIuOTUsNTEtNTFWNTFDNTEwLDIyLjk1LDQ4%0D%0ANy4wNSwwLDQ1OSwweg0KCQkJIE0xNTMsNDMzLjVINzYuNVYyMDRIMTUzVjQzMy41eiBNMTE0Ljc1%0D%0ALDE2MC42NWMtMjUuNSwwLTQ1LjktMjAuNC00NS45LTQ1LjlzMjAuNC00NS45LDQ1LjktNDUuOXM0%0D%0ANS45LDIwLjQsNDUuOSw0NS45DQoJCQlTMTQwLjI1LDE2MC42NSwxMTQuNzUsMTYwLjY1eiBNNDMz%0D%0ALjUsNDMzLjVIMzU3VjI5OC4zNWMwLTIwLjM5OS0xNy44NS0zOC4yNS0zOC4yNS0zOC4yNXMtMzgu%0D%0AMjUsMTcuODUxLTM4LjI1LDM4LjI1VjQzMy41SDIwNA0KCQkJVjIwNGg3Ni41djMwLjZjMTIuNzUt%0D%0AMjAuNCw0MC44LTM1LjcsNjMuNzUtMzUuN2M0OC40NSwwLDg5LjI1LDQwLjgsODkuMjUsODkuMjVW%0D%0ANDMzLjV6Ii8+DQoJPC9nPg0KPC9nPg0KPGc+DQo8L2c+DQo8Zz4NCjwvZz4NCjxnPg0KPC9nPg0K%0D%0APGc+DQo8L2c+DQo8Zz4NCjwvZz4NCjxnPg0KPC9nPg0KPGc+DQo8L2c+DQo8Zz4NCjwvZz4NCjxn%0D%0APg0KPC9nPg0KPGc+DQo8L2c+DQo8Zz4NCjwvZz4NCjxnPg0KPC9nPg0KPGc+DQo8L2c+DQo8Zz4N%0D%0ACjwvZz4NCjxnPg0KPC9nPg0KPC9zdmc+DQo=" alt="linkedin"/></a>
          </div>
<div class="contact-me-link">
     <a href="https://www.telegram.com/profile.php?id=100028995246404" target="_blank" id="profile-link">
<img src="https://ci4.googleusercontent.com/proxy/S3NoQEEM2-vo6dRqb4dgUncBwbzdZsl_KQaxnDEzvFta7Qew1vc6Eq6DeTGmIPz_mV1lwJD8wWpgPZutx3MWKOx-Eef_SiIz92a-oIRJV5C7CyUkpmgjBSEmVIW4DndGQnHPAyGbl_bOww=s0-d-e1-ft#https://email-editor-resources.s3.amazonaws.com/images/14507cd4d/Telegram%20%282%29.png" alt="Telegram"/></a>
</div>
          <div class="google-form">
            <a href="https://docs.google.com/forms/d/e/1FAIpQLSf_9T9qn5TaO7kc0pRfQPtFoQIf_2kPt3SXtsZGJLQU50ubHQ/viewform?vc=0&c=0&w=1&flr=0" target="_blank" id="profile-link">
              </div>
      </section>
    </main>
    <footer>
      <div class="text">Copyright © 2024, All Rights Reserved | Feedback | Privacy Policy | Terms and Conditions | Disclaimer | Sitemap</div>
    </footer>
        <script src="https://cdn.freecodecamp.org/testable-projects-fcc/v1/bundle.js"></script>
  </body>
</html>
