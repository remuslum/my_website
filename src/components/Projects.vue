<template>
<body>
    <link href="https://fonts.googleapis.com/css2?family=Ubuntu:wght@500&display=swap" rel="stylesheet">
    <div>
        <h1 class="heading"> My projects</h1>
    </div>
    <div class="project1">
        <img src="../assets/cdl.jpg"/>
    </div>
    <div class="project1">
        <span class="subtitle1"> 2019 Financial Statement Analysis of <br> City Developments Limited <br>
            <a href="https://drive.google.com/file/d/1VOg81VkbROXAaQYP_npVOwOWYrdcZp-u/view?usp=sharing" class="website"> View the Full Report Here </a>
        </span>
    </div>
    <div class="project1">
        <img src="../assets/feedmenow.jpg"/>
    </div>
    <div class="project1">
        <span class="subtitle1"> Web application for animal lovers <br> developed using Vue.js <br>
            <a href="https://bt3103-feed-me-now.web.app/" class="website"> View the Website Here </a>
        </span>  
    </div>
    <div class="project1">
        <img src="../assets/pie-chart.png"/>
    </div>
    <div class="project1">
        <span class="subtitle1"> Data Visualisation of Alpha <br> Airlines and its Competitor <br>
            <a href="https://drive.google.com/file/d/1Fe8w4rLmGdE88XWX-qv4p4ym_zcsuSfX/view?usp=sharing" class="website"> View Our Findings Here</a>
        </span>
    </div>    
    <div class="project1">
        <img src="../assets/machine-learning.jpeg" class="image1"/>
    </div>
    <div class="project1">
        <span class="subtitle1"> Machine Learning Model to predict <br> whether a credit card payment will default <br>
            <a href="https://docs.google.com/document/d/13XYNIUBgho2dfupskgVRsedBXfDBzCbPkbMz2FdL8mM/edit?usp=sharing" class="website"> View Our Full Report Here </a>
        </span>  
    </div>
</body>
</template>

<style scoped>
    .project1 {
        text-align: center;
        padding-top : 5vh ; 
    }
    .heading {
        font-family: 'Gloria Hallelujah', cursive;
        text-align: center;
        font-size: 10vh ; 
    }
    .image1 {
        height: 15vh ;
        width: 15vw ; 
        border-radius : 50% ; 
    }
    .subtitle1 {
        font-family: 'PT Sans Narrow', sans-serif;
        font-size: 5vh ; 
    }
    .website {
        text-decoration: none ;
        color: #0023DC ; 
    }
</style>