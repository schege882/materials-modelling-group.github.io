---
layout: framework
title: About Us
---
<!-- <link rel="stylesheet" href="/assets/css/custom.css"> -->
<head>
    <style>
        abbr {
            text-decoration: none;
        }
        .member-name {
            text-align: center;
            font-size: 0.9rem;
            font-weight: bold;
            margin: 0;
        }
        .members-container {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 15px;
            padding: 15px;
            justify-content: center;
        }
        .member {
            display: flex;
            flex-direction: column;
            align-items: center;
            min-height: 250px;
        }
        .member img {
            width: 100%;
            aspect-ratio: 1 / 1;  /* Forces square images */
            /* height: 200px; */ /* Fixed height to ensure uniformity */
            object-fit: cover;
            object-position: center;
            border-radius: 10px;
            margin-bottom: 10px;
            max-width: 100%;
        }
        @media (max-width: 600px) {
            .members-container {
                grid-template-columns: repeat(auto-fit, minmax(150px, 1fr));
            }
            .member img {
                height: 140px; /* Smaller height for mobile */
            }
        }
    </style>
</head>

# **ABOUT US**

<p style="text-align: justify;">
    The Materials Modelling Group is based at the Technical University of Kenya.
    We are dedicated in contributing to the advancement of theoretical and computational
    material science.
    Our research focuses on predicting and understanding properties of
    materials using <i>first principles</i> codes such as
    <abbr title="Quantum ESPRESSO">
        <a href="https://www.quantum-espresso.org/" target="_blank">QE,</a>
    </abbr>
    <abbr title="Vienna Ab initio Simulation Package">
        <a href="https://www.vasp.at/" target="_blank">VASP,</a>
    </abbr>
    <abbr title="Spanish Initiative for Electronic Simulations with Thousands of Atoms">
        <a href="https://siesta-project.org/siesta/" target="_blank">SIESTA,</a>
    </abbr>
    <a href="https://abinit.github.io/abinit_web/" target="_blank">ABINIT</a> and
    <a href="https://www.yambo-code.eu/" target="_blank">YAMBO.</a>
    The Materials Modelling Group is composed of researchers with expertise in condensed matter
    physics and computational techniques. The team includes faculty members and graduate students,
    all working collaboratively to address various research questions.
</p>

# **Our Members**
<div class="members-container">
    <div class="member">
        <img src="assets/images/members/amolo-go-passport.jpg" alt="Prof. George Amolo" >
        <p class="member-name">Prof. George Amolo</p>
    </div>
    <!--%%%%%%%%%%%%-->
    <div class="member">
        <img src="assets/images/members/DrMikeAtambo.jpeg" alt="Dr. Mike Atambo">
        <p class="member-name">Dr. Mike Atambo</p>
    </div>
    <!--%%%%%%%%%%%%-->
    <div class="member">
        <img src="assets/images/members/DrRobertOnyancha.jpg" alt="Dr. Robert Onyancha" >
        <p class="member-name">Dr. Robert Onyancha</p>
    </div>
    <!--%%%%%%%%%%%%-->
    <div class="member">
        <img src="assets/images/members/Lady.jpeg" alt="Dr. Mirriam Chepkoech">
        <p class="member-name">Dr. Mirriam Chepkoech</p>
    </div>
     <!--%%%%%%%%%%%%-->
    <div class="member">
        <img src="assets/images/members/Lady.jpeg" alt="Dr. Gladys King'ori">
        <p class="member-name">Dr. Gladys King'ori</p>
    </div>
    <!--%%%%%%%%%%%%-->
    <div class="member">
        <img src="assets/images/members/Lady.jpeg" alt="Perpetua Muchiri">
        <p class="member-name">Perpetua Muchiri</p>
    </div>
    <!--%%%%%%%%%%%%-->
    <!--%%%%%%%%%%%%-->
    <div class="member">
        <img src="assets/images/members/Lady.jpeg" alt="Carolyne Bakasa">
        <p class="member-name">Carolyne Bakasa</p>
    </div>
    <!--%%%%%%%%%%%%-->
    <div class="member">
        <img src="assets/images/members/ManPlaceHolder.png" alt="Renson">
        <p class="member-name">Renson</p>
    </div>
    <!--%%%%%%%%%%%%-->
    <!--%%%%%%%%%%%%-->
    <div class="member">
        <img src="assets/images/members/BillOyomo.jpeg" alt="Bill Clintone">
        <p class="member-name">Bill Clintone</p>
    </div>
    <!--%%%%%%%%%%%%-->
    <div class="member">
        <img src="assets/images/members/StephenChege.jpeg" alt="Stephen Chege">
        <p class="member-name">Stephen Chege</p>
    </div>
    <!--%%%%%%%%%%%%-->
    <div class="member">
        <img src="assets/images/members/LeahWairimu.jpg" alt="Leah Wairimu">
        <p class="member-name">Leah Wairimu</p>
    </div>
    <!--%%%%%%%%%%%%-->
    <div class="member">
        <img src="assets/images/members/CharlesRotich.jpeg" alt="Charles Rotich">
        <p class="member-name">Charles Rotich</p>
    </div>
</div>
