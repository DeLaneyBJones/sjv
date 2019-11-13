---
logo: ../assets/images/town_hall_logo.gif
companyName: My Fake Company 
motto: This is a motto!
bckImg: ../assets/images/background.jpeg
order: 0
title: header section
---

<header>
    <img src="{{page.bckImg}}" alt="Background image">
    <div class="centered">
        <div>
            <img src="{{page.logo}}" alt="Company logo">
        </div>
        <div>
            <h1>{{page.companyName}}</h1>
            <h2>{{page.motto}}</h2>
        </div>
    </div>
</header>

