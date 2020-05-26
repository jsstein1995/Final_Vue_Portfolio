<template>
    <div>
        <nav class="main-nav">
        <ul class="nav-links-top">
            <li><a href="landing.html">
                    <img class="short-logo" src="../assets/img/short@3x.png" alt="short-logo">
                </a>    
            </li>
            <li class='protfolio-link'>
                <a href="portfolio.html">
                SEE MY<b> PORTFOLIO</b></a>
                <img class="arrow" src="../assets/img/arrow@3x.png" alt="arrow">
                </li>
        </ul>
    </nav>
        <div class="bio-container">
        <div class="bio-image">
            <img class="selfie" src="../assets/img/0.jpg" alt="selfie">
        </div>
        <div class="email-container">
            <a class="email-link" href="mailto:jsstein1995@gmail.com">JSSTEIN1995@GMAIL.COM</a>
        </div>
        <div class="contact-number">
            214-649-1989
        </div>
        <button class="resume-btn">
            <a href="../assets/img/Resume_2020.pdf" target="_blank">Resume</a>
        </button>
    </div>
    <div class="skills-container">
        <div class="job-experience">
            <div>
                Job Experience
            </div>
            <div>
                Call Box, Dallas 
            </div>
            <div>
                Front-End Developer / UI Designer
            </div>
        </div>
        <div class="languages">
            <div>
                Software Languages
            </div>
            <ul>
                <li>
                    Javascript
                </li>
            </ul>
        </div>
        <div class="skills">
            <div>
                Skills
            </div>
            <ul>
                <li>
                    Web Development
                </li>
                <li>
                    Software Animation
                </li>
                <li>
                    Illustration
                </li>
                <li>
                    Adobe Photoshop/Illustrator/XD
                </li>
                <li>
                    Game Development (Unity)
                </li>
            </ul>
        </div>

    </div>
    </div>
</template>

<style scoped>
    .bio-container {
        text-align: center;
        width: 100%;
        padding-top: 10rem;
    }
    .bio-container > div {
        padding: .5rem;
    }
    .selfie {
        border-radius: 50%;
        max-width: 8rem;
    }
    .resume-btn {
        border: none;
        font-family: Urbana, sans-serif;
        background-color: transparent;
        letter-spacing: .1rem;
        cursor: pointer;
        font-size: 1rem;
        padding: .5rem;
        border: solid 2px black;
        border-radius: 3px;
        padding-right: 1rem;
        padding-left: 1rem;
        margin: .5rem;
    }
    .email-link {
        text-decoration: none;
        cursor: pointer;
        position: relative;
    }
    .email-link::after {
        content: "";
        position: absolute;
        left: 0rem;
        bottom: -.1rem;
        width: 100%;
        height: 2px;
        background: currentColor;
        transform: scaleX(0);
        transform-origin: right;
        transition: transform 250ms ease-in;
    }
    .email-link:hover::after {
        transform: scaleX(1);
        transform-origin: left;
    }
    .skills-container {
        display: flex;
        justify-content: space-between;
        margin-right: 12rem;
        margin-left: 12rem;
        margin-top: 2rem;
    }
    .job-experience > div {
        padding: .5rem;
    }
    .languages > div {
        padding: .5rem;
    }
    .languages > div > ul {
        list-style-type: none;
    }
    .skills > ul > li {
        padding: .5rem;
        list-style-type: none;
    }
    .skills {
        padding: .5rem;
    }
</style>
