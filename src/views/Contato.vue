<template>
    <h1>Área para contato</h1>
    <ContatoForm />
</template>

<script>
import ContatoForm from '@/components/ContatoForm.vue'

export default {
    name: 'Contato',
    components: {
      ContatoForm  
    }
}
</script>

<style scoped>
    h1 {
        margin-top: 40px;
    }

    h2 {
    text-align: center;
    font-size: 35px;
    margin-bottom: 30px;
    color: #222;
    }
</style>