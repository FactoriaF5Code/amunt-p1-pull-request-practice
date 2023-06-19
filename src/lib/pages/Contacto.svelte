


<script>


    let nombre = '';
    let email = '';
    let mensaje = '';

    function enviarFormulario() {
        console.log('Formulario enviado');
    }
</script>

<form on:submit|preventDefault={enviarFormulario}>
    <label>
        Nombre:
        <input type="text" bind:value={nombre} />
    </label>

    <label>
        Email:
        <input type="email" bind:value={email} />
    </label>

    <label>
        Mensaje:
        <textarea bind:value={mensaje}></textarea>
    </label>

    <button type="submit">Enviar</button>
</form>
<style>

</style>