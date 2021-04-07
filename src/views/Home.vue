<template>
  <div  class="home">
<b-container class="py-3 mx-auto">
      <b-row>
        <b-col cols="2">
        <router-link class="text-decoration-none" to="/"><h5 class="font-weight-bold text-dark text-left py-1">MY BUSINESS</h5></router-link>
        </b-col>
        <b-col cols="7">
          <ul>
            <li>
              <router-link class="text-decoration-none" to="/"
                ><small class="font-weight-bold text-primary">Home</small></router-link
              >
              <p class="bottomLine"></p>
            </li>
            <li>
              <router-link class="text-decoration-none" to="/"
                ><small class="font-weight-bold">Intro</small></router-link
              >
              <p class="bottomLine"></p>
            </li>
            <li>
              <router-link class="text-decoration-none" to="/"
                ><small class="font-weight-bold">Expertises</small></router-link
              >
              <p class="bottomLine"></p>
            </li>
            <li>
              <router-link class="text-decoration-none" to="/"
                ><small class="font-weight-bold">Work</small></router-link
              >
              <p class="bottomLine"></p>
            </li>
            <li>
              <router-link class="text-decoration-none" to="/"
                ><small class="font-weight-bold">Plans</small></router-link
              >
              <p class="bottomLine"></p>
            </li>
            <li>
              <router-link class="text-decoration-none" to="/"
                ><small class="font-weight-bold">News</small></router-link
              >
              <p class="bottomLine"></p>
            </li>
          </ul>
        </b-col>
        <b-col cols="3">
        <ul class="mr-0 text-right">
            <li>
              <router-link class="text-decoration-none" to="/"
                ><small class="font-weight-bold">Sign in</small></router-link
              >
              <p class="bottomLine"></p>
            </li>
            <li>
              <router-link class="text-decoration-none" to="/"
                ><small class="font-weight-bold text-primary">Sign up</small></router-link
              >
              <p class="bottomLine"></p>
            </li>
            
          </ul>
        
        </b-col>
      </b-row>
</b-container>

<b-container class="pt-5 mx-auto">
<b-row class="pt-5">
<b-col cols="1">
<div class="pt-3">
<div class="links"><b-icon icon="facebook" font-scale="1.5"></b-icon></div>
<div class="links"><b-icon icon="instagram" font-scale="1.5"></b-icon></div>
<div class="links"><b-icon icon="twitter" font-scale="1.5"></b-icon></div>
</div>
</b-col>
<b-col class="11">
  <h1 class="w-50 text-left font-weight-bold pt-5 pl-4">Lorem ipsu consectetur, adipisicing  Nesciunt, lorem itaque?</h1>
</b-col>
</b-row>
</b-container>

<b-container class="mx-auto">
<b-row>
<b-col cols="1"></b-col>
<b-col cols="7" class="py-5 px-4">
<div><p class="text-left">Lorem ipsum dolor sit amet consectetur adipisicing elit. Voluptates asperiores molestias illum et modi soluta dolores excepturi, quia natus, possimus incidunt facilis delectus non odio, sapiente officia recusandae tenetur iusto!</p>
</div>
<div class="text-left mt-5"><button class=" text-white bg-dark border rounded-pill py-2 px-5" type="submit">Work With Us</button></div>   
</b-col>
<b-col cols="4" class="pt-5 px-0 pb-0">
<div class="bg-image">
<div class="positionAbsolute-first"></div>
</div>
</b-col>
</b-row>
</b-container>

<b-container class="pb-5 mb-5 mx-auto">
<b-row>
<b-col cols="8" class="pr-0">
<div class="bg-image1">
<div class="positionAbsolute-first">
  <h4 class="w-50 mx-auto text-white pt-5 font-weight-bold text-left">Inventore quisquam explicabo, magnam nulla alias in provident at perferendis delectus culpa consequuntur?</h4>
  <p class="w-50 mx-auto pt-4 text-left text-white">Lorem ipsum dolor sit amet consectetur adipisicing elit. Ducimus, eaque  dolor sit amet consectetur adipisicing elit.</p>
  <div class="w-50 ml-5 pl-4 mt-5"><button class=" text-white bg-dark border rounded-pill py-1 px-3" type="submit"><small>Find Out More</small></button></div>


</div>
  <div class="positionAbsolute-second"></div>
  <div class="positionAbsolute-third">
  Lorem ipsum dolor sit amet consectetur.</div>
</div>
</b-col>
<b-col >
</b-col>
</b-row>
</b-container>

<b-container fluid class="bg-light">
<b-container class="mx-auto">
<b-row>
<b-col cols="12" class="p-5">
<h2 class="text-center font-weight-bold mb-3">Oue Expertises</h2>
<p class="text-center w-75 mx-auto">Lorem ipsum dolor sit amet consectetur adipisicing elit. Porro totam, inventore similique distinctio id aut tempora quam perspiciatis voluptates! Voluptatem fugit illo a. Iure enim possimus error. Labore, perferendis dolorem.</p>
</b-col>
<b-col cols="12" class="shadow-lg mb-5">
<b-row>
<b-col cols="12" md="6" lg="4" class="px-0 py-0" v-for="base in bases" :key="base.id">
<div class=" bg-white py-4">
  <div><img :src="require(`@/assets/${base.picture}.png`)" width="88"></div>
  <div><h4 class="py-3 font-weight-bold">{{ base.title }}</h4></div>
  <div><p class="w-75 mx-auto">{{ base.text }}</p></div>
  <div><button class=" text-white bg-dark border rounded-pill py-2 px-5 my-3" type="submit">Find Out More</button></div>
</div>
</b-col>
</b-row>
</b-col>
</b-row>
</b-container>
</b-container>

<b-container fluid class="bg-image2 mt-5">
<b-row>
<b-col cols="12" class="positionAbsolute-four">
  <h1 class="width-change text-white mx-auto font-weight-bold mt-5 mb-3">How do you design content for ever language</h1>
<p class="w-50 text-white mx-auto py-3">Lorem ipsum dolor, sit amet consectetur adipisicing elit. Nisi error eius vitae fugiat, quidem ipsa quisquam eaque quam unde ullam consectetur qui ipsum repellat.</p>
    <div><button class="border-0 text-white bg-primary border rounded-pill py-2 px-5 my-3" type="submit">Work With Us</button></div>

</b-col>
</b-row>
</b-container>

<b-container fluid class="bg-white">
<b-container class="mx-auto">
<b-row>
<b-col cols="12" sm="8">
<ul class="py-3 pl-0">
  <li class="pl-0">
    <router-link class="text-decoration-none text-dark" to="/">
    Home
    </router-link>
  </li>
   <li>
    <router-link class="text-decoration-none text-dark" to="/">
    About
    </router-link>
  </li>
   <li>
    <router-link class="text-decoration-none text-dark" to="/">
    Projects
    </router-link>
  </li>
   <li>
    <router-link class="text-decoration-none text-dark" to="/">
    Services
    </router-link>
  </li>
   <li>
    <router-link class="text-decoration-none text-dark" to="/">
    Article
    </router-link>
  </li>
   <li>
    <router-link class="text-decoration-none text-dark" to="/">
    Contact
    </router-link>
  </li>
</ul>
</b-col>
<b-col cols="12" sm="4" class="py-3 text-right">
    <a href="#"><b-icon class="m-2" font-scale="1.3" variant="dark" icon="instagram"></b-icon></a>
    <a href="#"><b-icon class="m-2" font-scale="1.3" variant="dark" icon="facebook"></b-icon></a>
    <a href="#"><b-icon class="m-2" font-scale="1.3" variant="dark" icon="twitter"></b-icon></a>
    <a href="#"><b-icon class="m-2" font-scale="1.3" variant="dark" icon="linkedin"></b-icon></a>
</b-col>
</b-row>
</b-container>
</b-container>

<b-container fluid class="bg-dark py-3">
<b-container class="mx-auto">
<b-row>
<b-col cols="12" sm="6">
 <router-link class="text-decoration-none" to="/">
 <h5 class="font-weight-bold text-white text-left py-1">MY BUSINESS</h5>
 </router-link>
</b-col>
<b-col cols="12" sm="6">
<p class="text-secondary text-right">Ipsum dolor sit amet, consectetur adipisicing elit. Saepe, velit?
</p>
</b-col>
</b-row>
</b-container>
</b-container>
</div>
</template>

<script>
// @ is an alias to /src

export default {
  name: "Home",
  components: {},
  data() {
    return {
      bases:[
{
  picture:'coding',
  title:'Research',
  text:'Lorem ipsum dolor sit amet consectetur adipisicing elit. Porro totam, inventore similique distinctio id aut adipisicing elit.'
},
{
  picture:'watching-tv',
  title:'Content',
  text:'Lorem ipsum dolor sit amet consectetur adipisicing elit. Porro totam, inventore similique distinctio id aut adipisicing elit.'
},
{
  picture:'bond',
  title:'Product Design',
  text:'Lorem ipsum dolor sit amet consectetur adipisicing elit. Porro totam, inventore similique distinctio id aut adipisicing elit.'
}

      ]
    }
  },

};
</script>
<style lang="scss" scoped>
* {
  padding: 0;
  margin: 0;
  box-sizing: border-box;
  font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
}
.home {
width: 100%;
  background-image: url("../assets/bg-main.jpg");
  background-attachment: fixed;
}
ul {
  display: flex;
  margin-right: 30px;
  li {
    list-style: none;
    font-size: 20px;
    transition: all 0.5s ease;
    padding: 0 20px;
    position: relative;
    font-family: inherit;
    small {
      color: #343a40;
    }
  }
}
router-link{
text-decoration: none !important;
}
.bottomLine {
  width: 90%;
  height: 2px;
  margin: 0 auto;
  background-color: #343a40;
  position: absolute;
  left: 0;
  top: 35px;
  transform: scale(0);
  transition: all 0.5s ease;
}
ul li:hover .bottomLine {
  transform: scale(1);
}
.links{
width: 50px;
height: 50px;
border: 1px solid black;
border-radius: 100%;
display: flex;
justify-content: center;
align-items: center;
margin: 15px 10px;
}
.bg-image{
width: 100%;
height: 300px;
background-image: url('../assets/carousel1.jpg');
background-size: cover;
background-position: center center;
position: relative;
}
.bg-image1{
  width: 100%;
  max-width: 960px;
  height: 500px;
background-image: url("../assets/inno2.jpg");
background-size: cover;
position: relative;
}
.positionAbsolute-first{
  width: 100%;
  height: 100%;
  position: absolute;
  top: 0;
  left:0;
  background:rgba(#007bff, 0.7);
}
.positionAbsolute-second{
  width: 50%;
  height: 280px;
  position: absolute;
  top: 25%;
  right: -30%;
  background-image: url('../assets/pixel.jpeg');
  background-size: cover;
}
.positionAbsolute-third{
  width: 25%;
  height: 100px;
  position: absolute;
  top: 74%;
  right: -25%;
  font-weight: bold;
  transform: rotate(-90deg);
}
.width-change{
  width: 38%;
  font-size: 42px;
}
.bg-image2{
  width: 100%;
  height: 550px;
  background-image: url('../assets/inno.jpg');
  background-size: cover;
  position: relative;
}
.positionAbsolute-four{
  width: 100%;
  height: 100%;
  padding-top: 85px;
  position: absolute;
  top: 0;
  left: 0;
  background:rgba(0,0,0,0.7);
}

</style>
