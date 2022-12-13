<template>
  <div class="informacion">
    <div class="portafolio">
    

      <div class="nombre">
        <p class="name">Yuliana Serna</p>
        <p class="adsi">Aprendiz SENA</p>
      </div>
      <div class="imagen">
        <img src="../assets/yuliana.png" />
      </div>
    </div>
    <div class="texto1">
      <div class="tex">
        <p class="personal">SOBRE MI</p>
      </div>
      <div class="sobremi">
        <img class="in" src="../assets/in.jpg" />
        <img class="in" src="../assets/twiter.jpg" />
        <img class="in" src="../assets/face.jpg" alt="" />
      </div>
    </div>
    <div class="miinformacion">
      <div class="div">
        <p class="lorrem">
          La inteligencia consiste no sólo en el conocimiento, sino también en la 
          destreza de aplicar los conocimientos 
          en la práctica. 
           Aristóteles-Filósofo griego.
        </p>
      </div>
    
      <div class="div">
        <p class="lorrem">
          Si quieres ser sabio, aprende a interrogar razonablemente, a escuchar con atención, 
          a responder tranquilamente y a callar cuando no tengas nada que decir.
        </p>
      </div>
    </div>
    <div class="inconos">
      <div class="conctado">
        <div class="info">
          <h1>INFORMACION</h1>
        </div>
        <div class="telefono">
          <p class="telefono">TELEFONO : 3013208860</p>
          <p class="email">EMAIL : syserna12@misena.edu.co</p>
          <p class="direcion">DIRECION : VEREDAD LA YUNGA</p>
        </div>
      </div>
      <div class="registro">
        <div class="todo">
            <h1>CONCTADO</h1>
          </div>
        <div class="llenar">
          <div class="nombre">
            <label>Nombre*</label>
            <input class="input" type="text"/>
          </div>
          <div class="apelli">
            <label for="">Apellido*</label>
            <input class="input" type="text">
          </div>
        </div>
        <div class="emaill">
          <label> EMAIL</label>
          <input  class="emi" type="text" >
        </div>
        <div class="mensaje">
          <label> MENSAJE</label>
          <input class="mesaje" type="text">
        </div>
        <br>
        <div class="cont-enviar">
            <button class="enviar" type="button">enviar</button>
        </div>
        
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "HelloWorld",
  props: {
    msg: String,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.cont-enviar{
  display: flex;
  margin: auto;
}
.div{
  display: flex;

}
.enviar{
  background-color: transparent;
  text-align: center;
  margin: auto;
padding: 2px 20px 2px 20px;
border-radius: 20px;
  /* margin-top: 5%; */
}

.inconos{
  display: flex;
}
.nombre{
  width: 100%;
}
.apelli{
  width: 100%;
}


.mesaje{
  margin: auto;
  height: 70px;
  width: 50%;
}
.emi{
  margin: auto;
  width: 50%;
}
.llenar{
  display: flex;
}
.registro{
  background-color: rgb(185, 185, 221);
width: 100%;
}
.button {
  background-color: transparent;
}

.input {
  margin: auto;
  width: 90%;
  
}
.conctado {
  width: 100%; 
  background-color: rgb(117, 231, 231);
}
.miinformacion {
  display: flex;
}
.lorrem {
  width: 100%;
  font-size: 25px;
  text-align: left;
  
}


.tex {
  width: 100%;
}

.texto1 {
  display: flex;
}

.personal {
  font-size: 40px;
}

.portafolio {
  background-color: rgba(100, 82, 61, 0.377);
}

.in {
  height: 10vh;
  width: 10vh;
}

.name {
  font-size: 50px;
  color: white;
  font-family: Impact;
}

.adsi {
  font-size: 40px;
}

/* .principio{
  margin-top: 30%;
} */

input {
  display: flex;
  height: 30px;
  width: 15%;
  margin-left: auto;
  margin-top: auto;
  
}

.sobremi {
  margin-top: 20px;
  width: 100%;
}

.texto {
  font-size: 30px;
}

img {
  height: 40vh;
  width: 40vh;
  border-radius: 50%;
}

.imagen {
  margin: auto;
}
</style>
