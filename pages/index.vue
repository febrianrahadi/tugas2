<template>
  <div>
    <article id="home">
      <div class="home-con">
        <h1>Get on the driver’s seat</h1>
        <p>Go ahead. Grab your license or learn how to ride a bike. You’ll love all the freedom it brings you.⁣⁣</p>
        <a href="#about"><button id="home-Btn">Learn More</button></a>
      </div>
    </article>

    <article id="blok">
      <div class="blok-column">
        <img src="./assets/img/project.png">
        <p>Competency Based Training</p>
      </div>
      
      <div class="blok-column">
        <img src="./assets/img/tuition.png">
        <p>Comprehensive Lesson Plan</p>
      </div>
      
      <div class="blok-column">
        <img src="./assets/img/reward.png">
        <p>Certified Trainer</p>
      </div>
    </article>

    <article id="about">
      <div class="about">
        <h1><span class="orange">Welcome</span> to our driving school</h1>
      </div>
      
      <div class="about-con">
        <div class="about-col">
          <h2>Learn to Drive with Driving</h2>
          <p>Best driver instructors in town! 
            With qualified driving instructors nationwide, 
            learning to drive with Driving couldn't be simpler. 
            Driving instructors are trained to the highest standards, 
            go through frequent background checks and drive new vehicles maintained to the highest standards
          </p>
        </div>
        
        <div class="about-col">
          <img src="./assets/img/Photo.jpg">
        </div>
      </div>
    </article>
  </div>
</template>

<script>
export default {
  name: 'IndexPage',
}
</script>

<style>
  * {
    font-family: "Muli", sans-serif;
    color: #19345E;
    padding: 0;
    margin: 0;
    }

  .header-con {
    display: flex;
    align-items: center;
    width: cover;
    height: 70px;
    padding: 0;
  }

  .header-title {
    flex-grow: 3;
    padding-left: 80px;    
    font-weight: bolder;
  }

  .header-menu {
    flex-grow: 1;    
  }

  nav li {
    display: inline;
    list-style-type: none;
  }

  nav a {
    color: #19345E;
    margin-right: 30px;
    font-size: 15px;
    font-weight: bolder;
    text-decoration: none;
    text-align: right;
  }

  nav a:hover {
    color: #ff7701;
  }

  span {
    color: #ff7701;
  }


  #about {
    max-width: 1300px;
    margin: 0 auto;
    padding: 50px 50px;
}

.about {
    padding-bottom: 40px;
    margin-bottom: 50px;
    border-bottom-style: solid;
    border-bottom-width: 1px;
}

.about-con {
    display: flex;
    align-items: center;
}


.about-con h2 {
    padding-bottom: 20px;
    margin-bottom: 20px;
    font-weight: normal;
}

.about-con p {
    color: #19345E;
    padding-left: 0;
    padding-right: 50px;
    font-weight: normal;
}

.about-col {
    flex-basis: 50%;
}

.about-col img {
    width: 100%;
}


/*-----course-----*/
#courses {
    max-width: 1300px;
    margin: 0 auto;
    padding: 50px 50px;
}


.course-title {
    padding-bottom: 40px;
    margin-bottom: 50px;
    border-bottom-style: solid;
    border-bottom-width: 1px;
}

.course-con {
    display: flex;
    flex-wrap: wrap;
    width: 100%;
    margin: auto;
    align-items: center;
    justify-content: space-evenly;
}

.course-column {
    height: 400px;
    flex-basis: 30%;
    text-align: center;
    border-style: solid;
    border-width: 1px;
    box-shadow: 1px 1px 6px 2px #19345E;
    cursor: pointer;
}

.course-column img {
    width: 100%;
}

.course-column h2 {
    font-weight: bolder;
    padding: 10px;
}

.course-column p {
    color: #19345E;
    padding: 10px;
    font-weight: 100;
}

/*-----contact-----*/
#contact {
    max-width: 1300px;
    margin: 0 auto;
    padding: 50px;
}

.contact {
    padding-bottom: 40px;
    margin-bottom: 50px;
    border-bottom-style: solid;
    border-bottom-width: 1px;
}

.contact-img { 
    padding-bottom: 50px;
    margin: 0 auto;
    max-width: 200px;
    text-align: center;
}

.contact-img img {
    padding-bottom: 20px;
    margin: auto;
    width: 200px;
    border-radius: 10%;
}

.contact-con {
    display: flex;
    flex-wrap: wrap;
    margin: 0 auto;
    align-items: center;
    justify-content: space-evenly;
    padding: 0;
}

.contact-column {
    flex-basis: 30%;
    text-align: center;
    padding: 10px 0;
    width: 100px;
}

.contact-column img {
    padding-bottom: 20px;
}

#btn {    
    width: 100px;
    padding: 10px 0;
    border-radius: 25px;
    color: #ff7701;
    border-color: #ff7701;
    border-style: solid;
    font-weight: bolder;
    margin: 0 30px;
    cursor: pointer;
    margin: 0 auto;
}

#btn:hover {
    background-color: #ff7701;
    color: white;
}

/*-----footer-----*/
.footer {
    background-color: #19345E;
    height: 25px;
    width: cover;
    text-align: center;
    color: white;
    
}

.home-con {
    text-align: center;
    background-image: url('./assets/img/drive.jpg');
    background-repeat: no-repeat;
    background-position: center 75%;
    background-size: cover;
    position: relative;
    overflow: hidden;
    padding: 200px 0;
    
  }

  .home-con h1, p {
    font-weight: bolder;
    color: white;
    padding: 20px;
    
  }

  #home-Btn {
    background-color: #ff7701;    
    padding: 10px 25px;
    border-radius: 25px;
    color: white;
    border-color: #ff7701;
    font-weight: bolder;
    margin: 0 30px;
    cursor: pointer;
  }

  #home-Btn:hover {
    background-color: white;
    color: #19345E;
  }


  #blok {
    padding: 50px 0;
    width: cover;
    background-color: #19345E;
    margin: auto;
    display: flex;    
  }

  .blok-column {
    flex-grow: 1;
    flex-basis: 25%;
    text-align: center;
  }

  .blok-column p {
    color: white;
    padding-top: 30px;
    font-weight: bold;
  }

</style>
