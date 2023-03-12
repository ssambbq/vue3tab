<template>
<TabsWrapper>
<TabMain title="Tab 1"> 
 <btn>Valve</btn><br>


 <div class="dropdown">
  <button class="dropbtn">Dropdown</button>
  <div class="dropdown-content">
  <a href="#">Link 1</a>
  <a href="#">Link 2</a>
  <a href="#">Link 3</a>
  </div>
</div>


 <btn>Elobow</btn><br>
 <btn>Reducer</btn><br>

</TabMain>




<TabMain title="Tab 2"> Hello from Tab2 </TabMain>




<TabMain title="Tab 3"> Hello from Tab3 </TabMain>




<TabMain title="Tab 4"> Hello from Tab4 </TabMain>




</TabsWrapper>


</template>

<script setup>


import TabsWrapper from './components/TabsWrapper.vue'
import TabMain from './components/TabMain.vue'



</script>


<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 40px;
  text-align: left;
  line-height:45px;
}


btn {
    width: 200px;
    text-align: center;
    padding: 10px 20px;
    margin-right: 10px;
    background-color: #ddd;
    border-radius: 5px;
    cursor: pointer;
    transition: 0.4s all ease-out;
}

btn:hover {
    width: 200px;
    text-align: center;
    padding: 10px 20px;
    margin-right: 10px;
    background-color: #4CAF50;
    border-radius: 5px;
    cursor: pointer;
    transition: 0.4s all ease-out;
}




  /* Style The Dropdown Button */
dropbtn {
  background-color: #209323;
  color: white;
  padding: 16px;
  font-size: 16px;
  border: none;
  cursor: pointer;
}

/* The container <div> - needed to position the dropdown content */
dropdown {
  position: relative;
  display: inline-block;
}

/* Dropdown Content (Hidden by Default) */
dropdown-content {
  display: none;
  position: absolute;
  background-color: #f9f9f9;
  min-width: 160px;
  box-shadow: 0px 8px 16px 0px rgba(0,0,0,0.2);
  z-index: 1;
}

/* Links inside the dropdown */
dropdown-content a {
  color: black;
  padding: 12px 16px;
  text-decoration: none;
  display: block;
}

/* Change color of dropdown links on hover */
dropdown-content a:hover {background-color: #f1f1f1}

/* Show the dropdown menu on hover */
dropdown:hover .dropdown-content {
  display: block;
}

/* Change the background color of the dropdown button when the dropdown content is shown */
dropdown:hover .dropbtn {
  background-color: #3e8e41;
}

</style>
