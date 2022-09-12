# info-digital-prueba01
<!DOCTYPE html>
<html lang="es">
    <head>
        <meta charset="utf-8" />
        <meta name="viewport" content="width=device-width, initial-scale=1" />
        <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-1BmE4kWBq78iYhFldvKuhfTAU6auU8tT94WrHftjDbrCEXSU1oBoqyl2QvZ6jIW3" crossorigin="anonymous" />
        <link rel="preconnect" href="https://fonts.googleapis.com" />
        <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
        <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600&display=swap" rel="stylesheet" />
        <style>
            :root {
                --bs-font-sans-serif: "Inter", sans-serif;
                --bs-body-color: #232323;
            }
            body {
                /* puede reemplazar la imagen de encabezado por otra que se funda con el color de fondo (que en este caso es #f7f7f7) */
                background: #f7f7f7 url("img/encabezado.png") center 0 no-repeat;
                background-size: auto 70vh;
            }
            @media (min-width: 992px) {
                .container {
                    max-width: 960px;
                }
            }
            h1,
            h2,
            h3,
            h4,
            h5,
            h6 {
                letter-spacing: 0.075rem;
                font-weight: 600;
            }
            p em {
                font-weight: 600;
                font-style: normal;
            }
        </style>
        <title>Reemplaza este título que se muestra en la ventana de tu navegador</title>
    </head>
    <body>
        <header class="container">
            <div class="row">
                <div class="col-sm-11 col-md-10 col-lg-9 col-xl-8 col-xxl-7 mx-auto">
                    <!--note que el h1 incluye un atributo de estilo, donde el valor es 71vh (ver línea 18 del código, es igual al segundo valor del background-size)-->
                    <h1 class="text-center" style="padding-top: 70vh;">La Tragedia de Los Andes</h1>
                    <h2 class="mt-4 mb-5 text-center fs-6 text-black-50">POR OLIVIA BACIGALUPO</h2>
                </div>
            </div>
        </header>

        <main class="container">
            <div class="row g-4 pb-5">
                <article class="col-sm-11 col-md-10 col-lg-9 col-xl-8 col-xxl-7 mx-auto">
                    <p class="lead">
                        En octubre de 1972 un vuelo de la FFAA Uruguaya se accidentó en la cordillera de Los Andes, dando inicio a una de las hazañas de supervivencia humana más recordadas en el último siglo.
                    </p>
                </article>

                <article>
                    <div class="col-sm-11 col-md-10 col-lg-9 col-xl-8 col-xxl-7 mx-auto">
                        <h3 class="fs-4 text-center mt-4 mb-3">El Viernes 13</h3>
                        <p>
                             El día 12 de octubre de 1972, un avión Fairchild 571 que lleva al equipo de rugby uruguayo Old Christians Club emprende vuelo desde Aeropuerto internacional de Carrasco, con su destino final siendo Santiago de Chile. Para evitar una tormenta al cruzar la cordillera, se toma la desición de realizar una primera parada en Mendoza, donde pasan la noche, para luego continuar al día siguiente. Ese viernes 13 de octubre, debido a la capacidad del avión, en vez de dirigirse directamente a Santiago se decide utilizar una ruta alternativa, pasando por Malagüe, para luego cruzar los andes a Curicó y finalmente girar hacia el Aeropuerto de Pudahuel. Es en este ultimo giro, debido a un error de cálculo, que el avión se estrella contra la montaña, justo en el límite entre Chile y Argentina.

                        </p>
                    </div>
                    <div class="col-md-11 col-lg-10 col-xl-9 col-xxl-8 mx-auto">
                        <object type="image/svg+xml" data="img/grafico01.svg" class="w-100 my-2">
                            Aquí corresponde un texto o una imagen alternativa
                        </object>
                    </div>
                </article>

                <article>
                    <div class="col-sm-11 col-md-10 col-lg-9 col-xl-8 col-xxl-7 mx-auto">
                        <h3 class="fs-4 text-center mt-4 mb-3">Después de la caída</h3>
                        <p>
                            De las 45 personas que se encontraban en el avión en el momento del impacto (40 pasajeros y 5 tripulantes), 11  murieron a causa de este choque. En los siguientes 72 días antes de ser encontrados y debido a las bajas temperaturas, desprendimientos de nieve en la montaña y al hambre, solamente 16 integrantes de este grupo lograron sobrevivir a este accidente.
                        </p>
                    </div>
                    <div class="col-md-11 col-lg-10 col-xl-9 col-xxl-8 mx-auto">
                        <object type="image/svg+xml" data="img/grafico02.svg" class="w-100 my-2">
                            Aquí corresponde un texto o una imagen alternativa
                        </object>
                    </div>
                </article>

                <article>
                    <div class="col-sm-11 col-md-10 col-lg-9 col-xl-8 col-xxl-7 mx-auto">
                        <h3 class="fs-4 text-center mt-4 mb-3">Los sobrevivientes</h3>
                        <p>
                            El grupo de sobrevivientes eran la mayoría hombres bastante jóvenes, siendo el menor Carlos Pues Rodríguez, quién paso su cumpleaños número 19 en la montaña y el mayor Javier Alfredo Methol, quien tenía 36 años en el momento del accidente.
                        </p>
                    </div>
                    <div class="col-md-11 col-lg-10 col-xl-9 col-xxl-8 mx-auto">
                        <object type="image/svg+xml" data="img/grafico03.svg" class="w-100 my-2">
                            Aquí corresponde un texto o una imagen alternativa
                        </object>
                    </div>
                    <div class="col-sm-11 col-md-10 col-lg-9 col-xl-8 col-xxl-7 mt-4 mx-auto">
                        <p>
                            
                        </p>
                    </div>
                </article>

                <article class="col-sm-11 col-md-10 col-lg-9 col-xl-8 col-xxl-7 mx-auto my-3">
                    <p class="text-black-50 small">
                        <a href="https://www.notaalpie.com.ar/2021/12/23/que-es-de-la-vida-de-los-sobrevivientes-de-la-tragedia-de-los-andes/" target="_blank">¿Qué es de la vida de los sobrevivientes de la Tragedia de los Andes?</a>, publicado el 23 de diciembre (2021). 
                    </p>
                    <p class="text-black-50 small">
                        <a href="https://tn.com.ar/sociedad/2021/12/23/la-tragedia-y-el-milagro-de-los-andes-como-fue-volver-al-lugar-donde-cayo-el-avion-571-de-la-fuerza-aerea-uruguaya/" target="_blank">La tragedia y el milagro de los Andes: cómo fue volver al lugar donde cayó el avión 571 de la Fuerza Aérea Uruguaya</a>, publicado por Mario Markic (2021). 
                    </p>
                    <p class="text-black-50 small">
                        <a href="https://www.rionegro.com.ar/la-cumbre-mas-emocionante-montanistas-del-alto-valle-donde-cayo-el-avion-de-la-tragedia-de-los-andes-1344451/" target="_blank">La cumbre más emocionante: montañistas del Alto Valle donde cayó el avión de la tragedia de los Andes</a>, publicado el 2020. 
                    </p>

                </article>
            </div>
        </main>
        <footer>
            <div class="container">
                <div class="row py-3">
                    <div class="col-md-11 col-lg-10 col-xl-9 col-xxl-8 mx-auto">
                        <p class="text-center"> 
                            <a href="https://github.com/profesorfaco/dno075-2022-2/tree/main/clase-06">Lunes 12 de septiembre, 2022</a>
                        </p>
                    </div>
                </div>
            </div>
        </footer>
        <script>
            var links = document.querySelectorAll("a");
            links.forEach((l) => l.classList.add("link-dark"));
            console.log("Esto es JavaScript");
        </script>
    </body>
</html>
