<script>
    let testimonios = [
        {
            autor: 'Juan',
            texto: '¡Excelente servicio! Recomiendo esta empresa a todos.',
        },
        {
            autor: 'María',
            texto: 'Increíble producto. Superó mis expectativas.',
        },
    ];
</script>

<div>
    {#each testimonios as testimonio}
        <div>
            <h3>{testimonio.autor}</h3>
            <p>{testimonio.texto}</p>
        </div>
    {/each}
</div>