

<script>
    let services = [
        {
            title: "Peluquería",
            description: "Nuestro servicio de peluquería incluye baño, corte de pelo, cepillado y arreglo de uñas.",
            schedule: "Lunes a viernes: 9:00 am - 6:00 pm",

        },
        {
            title: "Entrenamiento",
            description: "Ofrecemos sesiones de entrenamiento personalizadas para perros de todas las edades y niveles de habilidad.",
            schedule: "Martes y jueves: 10:00 am - 4:00 pm",
        },
        {
            title: "Cuidado durante las vacaciones",
            description: "Durante tus vacaciones, cuidaremos de tu mascota en nuestras instalaciones. Les proporcionaremos alimentación adecuada, ejercicio y atención individualizada.",
            schedule: "Disponible todo el año",
        },
    ];
    import imagena from "../../assets/Imagenes/1.jpg"
    import imagenb from "../../assets/Imagenes/2.jpg"



</script>

<section>
    <div class="fototitulo"> <img src={imagenb}/>
    </div>
    <h2>Nuestros Servicios</h2>
  <!--<img src="../../assets/Imagenes/Serviciosimagen1.jpg"> -->

    {#each services as service}
        <div class="service">

            <h3>{service.title}</h3>
            <p>{service.description}</p>
            <p><strong>Horario:</strong> {service.schedule}</p>
        </div>
    {/each}

    <div class="fototitulo"> <img src={imagena}/>
    </div>

</section>

<style>
    .service {
        margin-bottom: 20px;
    }

    h2 {
        font-size: 24px;
        margin-bottom: 10px;
    }

    h3 {
        font-size: 18px;
        margin-bottom: 5px;
    }

    p {
        font-size: 14px;
        line-height: 1.5;
        margin-bottom: 5px;
    }

    strong {
        font-weight: bold;
    }

    .fototitulo {

         display: flex;
        justify-content: center;

    }

    img {
        width: 700px;
        height: 350px;
    }
</style>
