<template>
    <div class="main-container">
        <form id="contato-form">
            <div class="input-container-unico">
                <input type="text" placeholder="Nome" id="nome">
            </div>
            <div class="input-container-dois">
                <input type="text" placeholder="E-mail" id="email">
                <input type="text" placeholder="Celular" id="celular">
            </div>
            <div class="input-container-dois">
                <input type="text" placeholder="Empresa" id="empresa">
                <input type="text" placeholder="País" id="pais">
            </div>
            <div class="input-container-big">
                <input type="text" placeholder="Mensagem" id="mensagem">
            </div>
            <div>
                <input type="submit" class="submit-btn" value="Enviar">
            </div>
        </form>
    </div>
</template>

<script>
export default {
    name: 'ContatoForm'
}
</script>

<style scoped>
    .main-container {
        display: flex;
        justify-content: center;
        align-items: center;
        max-width: 1010px;
        margin: 0 auto;
        min-height: 506px
    }

    .input-container-unico input,
    .input-container-big input {
        width: 1010px
    }

    .input-container-dois input {
        width: 500px
    }

    input {
        height: 50px;
        margin: 8px 5px;
        border-radius: 8px;
        border: solid 0.5px #222;
        font-size: 20px;
    }

    .submit-btn {
    width: 1010px;
    background-color: #222;
    color:#fcba03;
    font-weight: bold;
    border: 2px solid #222;
    padding: 10px;
    font-size: 16px;
    margin: 0 auto;
    cursor: pointer;
    transition: .5s;
    display: flex;
    justify-content: center;
    align-items: center;
    margin-top: 10px;
  }

  .submit-btn:hover {
    background-color: transparent;
    color: #222;
  }

  .input-container-big input {
    height: 100px;
  }

</style>