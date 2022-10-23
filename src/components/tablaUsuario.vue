<template>
    <div class="tbUsuarios">
        <fieldset>
            <legend>Tabla de Usuarios</legend>
            <table>
                <tr>
                    <th>id</th>
                    <th>nombre</th>
                    <th>direccion</th>
                    <th>telefono</th>
                    <th>edad</th>
                    <th>eps</th>
                    <th>fecha de nacimiento</th>
                    <th>genero</th>
                </tr>
                <tr v-for="usuario in Usuarios" :key="usuario.idUsuario">
                    <td>{{usuario.idUsuario}}</td>
                    <td>{{usuario.nombre}}</td>
                    <td>{{usuario.direccion}}</td>
                    <td>{{usuario.telefono}}</td>
                    <td>{{usuario.edad}}</td>
                    <td>{{usuario.eps}}</td>
                    <td>{{usuario.fechaNacimiento}}</td>
                    <td>{{usuario.genero}}</td>

                </tr>
            </table>
        </fieldset>
        <router-view />
    </div>
    </template>

    <script>
    export default{

        name:"tablaUsuarios",
        props:{
            usuarios:{
                type:Array,
            }
        },
        methods:{},
    };
</script>
<style scoped>

.tbUsuario{
    padding: 5%;
    text-align: center;
}
table{
    border: 1px solid #000;
    margin: auto;
    padding: 1 px;
}
th{
    border: 1px solid #000;

}
tr,
td{
width: 20%;
text-align: left;
vertical-align: top;
border: 1px solid #000;
}
</style>