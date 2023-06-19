<script>
    import {Link} from "svelte-routing";
    import adulto from '../../assets/Catálogos/adulto.png';
    import cachorro from '../../assets/Catálogos/cachorro.png';
    import mediano from '../../assets/Catálogos/mediano.png';
</script>

<main>
    <div class="container">

            <div class="adulto">
                <img src={adulto} />
               <p>
                   Descripción Adulto : Tamaño del pienso adaptado a su mandíbula. Aporte energético: concentración en alimentos nutritivos. Fórmula denda en
                   nutrientes.
                   • Cuidado de huesos y articulaciones: sulfato de condroitina, glucosamina, omega-3, vitamina D, E y C.
                   • Buena digestión: pollo, arroz y fibras con efecto prebiótico • Cuidado de la piel: ácidos grasos omega-3 y omega-6, biotina y zinc
               </p>
            </div>

            <div class="cachorro">
                <img src={cachorro} />
                <p>
                    Descripción Cachorro: Pedigree es un alimento completo para cachorros a partir del segundo mes. Esta comida también es apropiada para perras embarazadas. Los perros de razas pequeñas y medianas crecen rápidamente. Por ello necesitan una alimentación especial que les brinde los energéticos necesarios. Pues sólo así podrán crecer saludablemente y tener un sistema inmunológico fuerte. Esta comida brinda al cachorro de razas pequeñas o medianas todo lo que necesita.
                    Características de Pedigree Junior con pollo y arroz:
                    :círculo_negro: Una relación óptima de calcio y fósforo apoya la formación de los dientes y los huesos.
                    . La vitamina E fortalece el sistema inmunológico.
                    Las proteínas de Pedigree Junior fortalecen de fibras musculares y vigorizan los músculos
                    :círculo_negro: Glucosamina como fuente natural apoya la formación de las articulaciones.
                    .
                    • Los ácidos grasos Omega 6 y Omega 3 apoyan el desarrollo saludable de la piel y del pelo.
                    • Aceite de pescado como fuente DHA natural, fomenta el desarrollo saludable del cerebro y los ojos.
                    Además contiene arroz, el cual es muy fácil de digerir, y fibras cuidadosamente escogidas para que su cachorro tenga todo lo necesario para empezar una vida saludable.
                </p>


            </div>

        <div class="mediano">
            <img src={mediano} />
            <p>
                Descripción Mediano: Purina® Dog Chow® SANO Y EN FORMAⓇ (Reduce Calories) diseñado para que tu perro controle la cantidad de calorías y logre el peso ideal, mientras disfruta de su comida.
                • 20% menos en calorias
                • Enriquecido en fibras
                • Proporciones adecuadas de proteínas y grasas que contribuyen con la energia necesaria pra que tu perro pueda permanecer sano y en forma.
                INGREDIENTES
                Maíz, harina de soja, harina de subproductos de pollo, trigo, harina de carne y hueso vacuna, fibra de soja y/o salvado de maíz, fibra de caña de azúcar y/o celulosa, digesto animal (a base de pollo y/o porcino), grasa vacuna y/o grasa porcina y/o aceite de pollo preservados con tocoferoles (fuente de Vitamina E), zanahoria deshidratada, sal, fosfato bicálcico, carbonato de calcio, cloruro de potasio, L-Lisina, cloruro de colina, colorantes permitidos (Rojo 40, Amarillo 5, Amarillo 6, Azul 2), sulfato de zinc, sulfato ferroso, suplementos vitamínicos (A, D-3, E, B-12), sulfato de manganeso, proteinato de manganeso, niacina, pantotenato de calcio, suplemento de riboflavina, clorhidrato de piridoxina, sulfato de cobre, mononitrato de tiamina, ácido fólico, iodato de calcio, selenito de sodio.
            </p>

        </div>
    </div>

</main>

<style>
div{


}
</style>