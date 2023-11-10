<template>
  <div>
    <div class="fa">
      +3115656296 babytracker@gmail.com
    </div>

    <div class="hom1">
    
    <nav>
      <img class="Logou" alt="Bebe" src="../assets/bebe.png"> |
      <router-link class="link" to="/about">Home</router-link> |
      <router-link class="link" to="/about">About</router-link> |
      <router-link class="link" to="/about">Clickme</router-link>
    </nav>
    </div>

    <div>
      <div class="todo">
        <img class="fondo1" alt="Bebe1" src="../assets/bta.jpg">
        <img class="fondo2" alt="Bebe2" src="../assets/ofi.jpg">
      </div>
      <div class="text1">
        <h1>HOLA MUNDO</h1>
      </div>
    </div>


  </div>
</template>

<script>
// @ is an alias to /src

</script>

<style>

.hom1{
  background-color: black;
  margin: auto;
  position: top;
  text-align: center;
}

.fa{
  background-color: greenyellow;
}

.Logou {
  width: 30px;
  height: 30px;
}

.fondo1{
  width: 50%;
  height: 50%;  
}

.fondo2{
  width: 50%;
  height: 50%;
}

.text1{
  position: relative;

}
.link{
  color: whitesmoke;
}
.todo{
  position: absolute;
}


</style>