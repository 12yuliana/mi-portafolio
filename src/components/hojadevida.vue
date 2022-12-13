<template>
    <main>
        <h1>
            Hoja de vida
        </h1>
        <table width="1000px">
            <h1 class="personales">
                DATOS PERSONALES
        </h1>
            <tr>
                <img src="../assets/yuliana.png">
            </tr>
            <tr>
                <td> <p>Numero de cedula</p></td>
                <td><p>1002821121</p></td>
            </tr>
            <tr>
                <td><p>Nombre </p></td>
                <td> <p>Yuliana</p></td>
            </tr>
            <tr>
                <td><p>Apellido</p> </td>
                <td><p> Serna</p></td>
            </tr>
            <tr>
                <td><p>Direccion</p> </td>
                <td><p> veredad la yunga - popayan</p></td>
            </tr>
            <tr>
                <td><p> Telefono</p></td>
                <td><p>3013208860</p></td>
            </tr>
            <tr>
                <td><p> Correo </p></td>
                <td><p>syserna12@misena.edu.co</p></td>

            </tr>

            <tr>
                <td>
                   <p> Fecha De Nacimiento</p>
                </td>
                <td>
                    <p>19/12/2002</p>

                </td>
            </tr>
            <tr>
                <td>
                   <p> Genero:</p> </td>
                <td>
                   <p> mujer</p>
                </td>

            </tr>
        </table>
        <div class="prota">
            <div class="profesional">
                <h3>
                    PERFIL PROFESIONAL
                </h3>
            </div>
            <div class="div">
                <h2 class=" h2">
                    Soy una persona responsable, puntual , creativa y con buena disposicion 
                    <br>para cualquier tarea
                    que se me asigne.
                    No tengo años de experiencia en el campo  <br>profecional, 
                    actualmente me encuentro realizando un tecnologo en ADSI en el sena.
                    <br>
                    <br>
                    Me intersa principalmente, trabajar en proyecto
                    <br> con un nivel de innovacion alto y un efoque social.
                </h2>
            </div>
            <div class="formacion">
                <div class="profesional">
                    <h3> FORMACION ACADEMICA
                    </h3>
                </div>
                <div class="colegio">
                    <h2 class="MMXIX ">
                        colegio  MMXIX 
                    </h2>
                    <h2 class="cajete">
                       |  Institucion Educativa Cajete
                    </h2>
                </div>
                <div class="2019">
                     <h2 class="año">
                        2019
                     </h2>
                </div>
            </div>
        </div>

    </main>
</template>

<script>
export default {
    name: 'hojadevida-vue'
}
</script>

<style scoped>
.año{
    margin: auto;
    margin-right: 20%;
}
.colegio{
    display: flex;
    width: 40%;
    margin: auto;
}
.cajete{
    margin: auto;
    /* width: 100%; */
    
}
.MMXIX{
    color:bisque;
   /* width: 20%; */
    margin: auto;
} 
p{
    margin: auto;
    margin-left: 40%;
    font-size: 80%;
  
 
}

.h2 {
    margin-left: 20%;
    font-size: 20px;
    text-align: left;
    margin-left: 25%;

}

main{
  background-color: rgba(100, 82, 61, 0.377);
}
h3 {
    font-size: 30px;
}

.profesional {
    background-color: bisque;
    width: 60%;
    margin: auto;
}

.personales {
    font-size: 30px;
    background-color: bisque;
    width: 60%;
    margin: auto;
}

table {
    margin: auto;



}

img {
    height: 30vh;
    margin-top: 20px;
    margin-bottom: 20px;
}

td {
    font-size: 25px;
    text-align: left;
    border-radius: 1px solid red
    ;
}


</style>