<template>
    <body>
      <link href="https://fonts.googleapis.com/css2?family=Ubuntu:wght@500&display=swap" rel="stylesheet">
      <div class="heading">
        <h1 class="headingtitle"> My Top Skills </h1>
      </div>
        <div class="row">
            <div class="column">
              <img src="../assets/python.png" class="image"/>
              <div class="card">
                <h1 class="title"> Python </h1>
                <p class="subtitle"> 
                </p>
              </div>
            </div>
            <div class="column">
              <img src="../assets/Rlogo.png" class="image" />
              <div class="card">
                <h1 class="title"> R </h1>
                <p class="subtitle"> </p>
              </div>
            </div>
            <div class="column">
              <img src="../assets/SQL.png" class="image" />
              <div class="card">
                <h1 class="title"> SQL </h1>
                <p class="subtitle"> </p>
              </div>
            </div>
            <div class="column">
                <img src="../assets/tableaulogo.png" class="image" />
                <div class="card">
                  <h1 class="title"> Tableau </h1>
                  <p class="subtitle"> </p>
                </div>
            </div>
            <div class="column">
                <img src="../assets/Java-Logo.png" class="image" />
                <div class="card">
                  <h1 class="title"> Java </h1>
                  <p class="subtitle"> </p>
                </div>
            </div>
            <div class="column">
                <img src="../assets/vue.png" class="image" />
                <div class="card">
                  <h1 class="title"> HTML,CSS,JS </h1>
                  <p class="subtitle"> </p>
                </div>
            </div>
        </div>
    </body>
</template>

<style scoped>
* {
  box-sizing: border-box;
}

.column {
  float: left;
  width: 30vw;
  margin-left: 3vw ; 
}

.row {margin: 0 -5px;}

.row:after {
  content: "";
  display: table;
  clear: both;
}

.image {
    height: 33vh ; 
    width : 28vw ; 
}

.card {
  box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2); 
  background-color: #f1f1f1;
}

.title {
  font-size: 5vh; 
  font-family: 'Indie Flower', cursive;
  text-align: center;
}

.heading {
  text-align: center;
}

.headingtitle {
  font-size : 10vh ; 
}

@media screen and (max-width: 600px) {
  .column {
    width: 100%;
    display: block;
    margin-bottom: 20px;
  }
}
</style>