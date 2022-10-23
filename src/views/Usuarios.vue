<template>
    <div class="usuario">
    <formularioUsuario/>
    <tablaUsuario/>
    </div>
</template>

<script>
import formularioUsuario from '@/components/formularioUsuario.vue'
import tablaUsuario from '@/components/tablaUsuario.vue'

export default{
    name:'Usuarios-view',
    components:{    
        formularioUsuario,tablaUsuario,
    }
}
</script>

<style scoped>
.usuario{
    text-align: center;
}
</style>