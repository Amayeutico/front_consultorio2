<template>
    <div class="formUsuario">
<fieldset>
    <legend>Formulario Registro Usuario</legend>
    <form action="">
        <label for="IdUsuario">Id Usuario</label><br>
        <input type="text" name="idUsuario" id="idUsuario"><br>

        <label for="nombre">Nombre</label><br>
        <input type="text" name="nombre" id="nombre"><br>

        <label for="direccion">Dirección</label><br>
        <input type="text" name="direccion" id="direccion"><br>

        <label for="telefono">Telefono</label><br>
        <input type="text" name="telefono" id="telefono"><br>

        <label for="edad">Edad</label><br>
        <input type="text" name="edad" id="edad"><br>

        <label for="eps">Eps</label><br>
        <input type="text" name="eps" id="eps"><br>

        <label for="fechaNacimiento">Fecha de Nacimiento</label><br>
        <input type="date" name="fechaNacimiento" id="fechaNacimiento"><br>

        <label for="genero">Genero</label><br>
        <input type="text" name="genero" id="genero"><br>

        <button type="submit">Guardar</button>
        <button type="submit">Eliminar</button>
        <button type="submit">Modificar</button>
        <button type="submit">Consultar</button>

    </form>
</fieldset>

    </div>
</template>
<script>

</script>

<style scoped>
.usuario{
text-align: center;
padding: auto;
font-family: inherit;
}
</style>