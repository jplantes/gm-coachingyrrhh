<template>
  <nav class="top-0 absolute z-50 w-full flex flex-wrap items-center justify-between px-2 py-3 ">
    <div class="container px-4 mx-auto flex flex-wrap items-center justify-between">
      <div class="w-full relative flex justify-between lg:w-auto lg:static lg:block lg:justify-start">
        <h1 class="text-4xl text-white">GM Couching</h1>

      </div>
      <div class="lg:flex flex-grow items-center bg-white lg:bg-transparent lg:shadow-none hidden"
        id="example-collapse-navbar">
        <ul class="flex flex-col lg:flex-row list-none lg:ml-auto">
          <li class="flex items-center">
            <a class="lg:text-white lg:hover:text-gray-300 text-gray-800 px-3 py-4 lg:py-2 flex items-center text-xs uppercase font-bold"
              href="#"><i class="lg:text-gray-300 text-gray-500 fab fa-facebook text-lg leading-lg "></i><span
                class="lg:hidden inline-block ml-2">Share</span></a>
          </li>
          <li class="flex items-center">
            <a class="lg:text-white lg:hover:text-gray-300 text-gray-800 px-3 py-4 lg:py-2 flex items-center text-xs uppercase font-bold"
              href="#"><i class="lg:text-gray-300 text-gray-500 fab fa-twitter text-lg leading-lg "></i><span
                class="lg:hidden inline-block ml-2">Tweet</span></a>
          </li>
          <li class="flex items-center">
            <a class="lg:text-white lg:hover:text-gray-300 text-gray-800 px-3 py-4 lg:py-2 flex items-center text-xs uppercase font-bold"
              href="#"><i class="lg:text-gray-300 text-gray-500 fab fa-github text-lg leading-lg "></i><span
                class="lg:hidden inline-block ml-2">Star</span></a>
          </li>
        </ul>
      </div>
    </div>
  </nav>

  <main>
    <div class="relative pt-16 pb-32 flex content-center items-center justify-center" style="min-height: 75vh;">
      <div class="absolute top-0 w-full h-full bg-center bg-cover"
        style='background-image: url("https://images.unsplash.com/photo-1557804506-669a67965ba0?ixlib=rb-1.2.1&amp;ixid=eyJhcHBfaWQiOjEyMDd9&amp;auto=format&amp;fit=crop&amp;w=1267&amp;q=80");'>
        <span id="blackOverlay" class="w-full h-full absolute opacity-75 bg-black"></span>
      </div>
      <div class="container relative mx-auto">
        <div class="items-center flex flex-wrap">
          <div class="w-full lg:w-6/12 px-4 ml-auto mr-auto text-center">
            <div class="pr-12">
              <h1 class="text-white font-semibold text-3xl md:text-5xl">
                Graciel Matines
              </h1>
              <p class="mt-4 text-lg text-gray-300 uppercase">
                coaching y recursos humanos
              </p>
            </div>
          </div>
        </div>
      </div>
    </div>

    <section class="pb-20 bg-gray-300 -mt-24">
      <div class="container mx-auto px-4">
        <div class="flex flex-wrap justify-center">

          <div class="w-full md:w-6/12 px-4 text-center">
            <div class="relative flex flex-col min-w-0 break-words bg-white w-full mb-8 shadow-lg rounded-lg">
              <div class="px-4 py-5 flex-auto">
                <div
                  class="text-white p-3 text-center inline-flex items-center justify-center w-12 h-12 mb-5 shadow-lg rounded-full bg-red-400">
                  <i class="fas fa-award"></i>
                </div>
                <h6 class="text-xl font-semibold">Misión</h6>
                <p class="mt-2 mb-4 text-gray-600 text-left">Inspirar, acompañar , guiar y empoderar a individuos y
                  equipos de trabajos a través de soluciones estratégicas en recursos humanos, coaching laboral y
                  ejecutivo, como asi tambien en mentorías personalizadas.
                  Mi objetivo es fomentar el desarrollo
                  integral y el bienestar, ayudando a mis clientes a alcanzar sus metas profesionales y personales, y a
                  crear entornos de trabajo colaborativos y eficientes.
                </p>
              </div>
            </div>
          </div>

          <div class="w-full md:w-6/12 px-4 text-center">
            <div class="relative flex flex-col min-w-0 break-words bg-white w-full mb-8 shadow-lg rounded-lg">
              <div class="px-4 py-5 flex-auto">
                <div
                  class="text-white p-3 text-center inline-flex items-center justify-center w-12 h-12 mb-5 shadow-lg rounded-full bg-blue-400">
                  <i class="fas fa-retweet"></i>
                </div>
                <h6 class="text-xl font-semibold">Visión</h6>
                <p class="mt-2 mb-4 text-gray-600 text-left">
                  Convertirme en una líder reconocida en el campo del desarrollo profesional y organizacional,
                  destacándome por mi compromiso con la excelencia, la innovación y el impacto positivo en mis clientes.
                  Aspiro a ser la elección preferida para aquellos que buscan transformar su potencial en resultados
                  tangibles y sostenibles.
                </p>
              </div>
            </div>
          </div>

          <div class="p-6 w-full md:w-11/12 px-4 text-center">
            <div class="flex flex-col min-w-0 bg-white w-full mb-8 shadow-lg rounded-lg">
              <div class="px-4 py-5">
                <div
                  class="text-white p-3 text-center inline-flex items-center justify-center w-12 h-12 mb-5 shadow-lg rounded-full bg-green-400">
                  <i class="fas fa-fingerprint"></i>
                </div>
                <h6 class="text-xl font-semibold mb-5">Valores</h6>
                <div class="grid md:grid-cols-6 md:gap-7">
                  <div class="md:col-span-2 text-gray-600 text-left rounded-md shadow-lg p-4">
                    <span class="font-bold text-black text-lg">Integridad:</span> Actúo con honestidad y transparencia,
                    manteniendo altos
                    estándares éticos en todas mis relaciones profesionales.
                  </div>
                  <div class="md:col-span-2 text-gray-600 text-left rounded-md shadow-lg p-4">
                    <span class="font-bold text-black text-lg">Excelencia:</span> Mis servicios son de la más alta
                    calidad,
                    adaptándome a
                    las necesidades específicas de cada cliente para superar sus expectativas.
                  </div>
                  <div class="md:col-span-2 text-gray-600 text-left rounded-md shadow-lg p-4">
                    <span class="font-bold text-black text-lg">Empatía:</span> Valoro y comprendo las perspectivas y
                    desafíos
                    únicos de
                    cada cliente, proporcionando un apoyo personalizado y humano.
                  </div>
                  <div class="md:col-span-2 text-gray-600 text-left rounded-md shadow-lg p-4">
                    <span class="font-bold text-black text-lg">Confidencialidad:</span> Protejo la privacidad y la
                    información
                    confidencial
                    de mis clientes, generando un ambiente de confianza y respeto.
                  </div>
                  <div class="md:col-span-2 text-gray-600 text-left rounded-md shadow-lg p-4">
                    <span class="font-bold text-black text-lg">Compromiso:</span> Estoy dedicada al éxito de mis
                    clientes,
                    trabajando
                    arduamente para acompañarlos a alcanzar sus objetivos y maximizar su potencial.
                  </div>
                  <div class="md:col-span-2 text-gray-600 text-left rounded-md shadow-lg p-4">
                    <span class="font-bold text-black text-lg">Innovación:</span> Mantengo una actitud proactiva y
                    abierta a las
                    nuevas
                    tendencias y prácticas en recursos humanos y coaching, asegurando soluciones efectivas y
                    contemporáneas.
                  </div>
                  <div class="md:col-start-2 md:col-span-2 text-gray-600 text-left rounded-md shadow-lg p-4">
                    <span class="font-bold text-black text-lg ">Desarrollo Continuo:</span> Fomento el aprendizaje y el
                    crecimiento
                    constante, tanto para mis clientes como para mí misma, apoyando el avance profesional y personal.
                  </div>
                  <div class="md:col-span-2 text-gray-600 text-left rounded-md shadow-lg p-4 ">
                    <span class="font-bold text-black text-lg">Colaboración:</span> Promuevo la cooperación y el trabajo
                    en
                    equipo, tanto
                    dentro de las organizaciones como en mis interacciones con los clientes, para lograr los mejores
                    resultados posibles.
                  </div>
                </div>
              </div>
            </div>
          </div>

        </div>

      </div>
    </section>

    <h1 class="text-5xl text-gray-600 text-center py-6">Mis sevicios</h1>

    <section class="relative py-20">
      <div class="container mx-auto px-4">
        <div class="items-center flex flex-wrap">
          <div class="w-full md:w-4/12 ml-auto mr-auto px-4">
            <img alt="..." class="max-w-full rounded-lg shadow-lg mb-5 md:mb-0"
              src="./assets/images/CONECTACONTUPOTENCIAL.jpg" />
          </div>
          <div class="w-full md:w-5/12 ml-auto mr-auto px-4">
            <div class="md:pr-12">
              <h3 class="text-3xl font-semibold">Servicios de Consultoría integral de Recursos Humanos</h3>
              <p class="mt-4 text-lg leading-relaxed text-gray-600">
                Mediante un diagnostico y evaluación de situación se evaluara la posibilidad de realizar un desarrollo
                organizacional, gestión del talento, evaluación de desempeño, gestión del cambio y clima organizacional
                como así también el servicio de gestión tercerizada del área de Recursos humanos
              </p>
            </div>
          </div>
        </div>
      </div>
    </section>

    <section class="relative py-20">
      <div class="container mx-auto px-4">
        <div class="items-center flex flex-col-reverse md:flex-row flex-wrap">
          <div class="w-full md:w-5/12 ml-auto mr-auto px-4">
            <div class="md:pr-12">
              <h3 class="text-3xl font-semibold">SESIONES 1 A 1</h3>
              <p class="mt-4 text-lg leading-relaxed text-gray-600">
                Si buscas potenciarte y superar los obstáculos en tu camino hacia el logro de tus metas, ¡estás en el
                lugar correcto

                Como coach, te acompañaré en un espacio de reflexión y aprendizaje donde exploraremos nuevas acciones y
                perspectivas. Te acompañaré a conectar con tu mejor versión y a alcanzar todos los objetivos que te
                propongas, fomentando el autoconocimiento y el crecimiento personal.
              </p>
            </div>
          </div>
          <div class="w-full md:w-4/12 ml-auto mr-auto px-4 mb-5 md:mb-0">
            <img alt="..." class="max-w-full rounded-lg shadow-lg" src="./assets/images/SESION1A1.jpg" />
          </div>
        </div>
      </div>
    </section>

    <section class="relative py-20">
      <div class="container mx-auto px-4">
        <div class="items-center flex flex-wrap">
          <div class="w-full md:w-4/12 ml-auto mr-auto px-4">
            <img alt="..." class="max-w-full rounded-lg shadow-lg  mb-5 md:mb-0" src="./assets/images/MENTORIAS.jpg" />
          </div>
          <div class="w-full md:w-6/12 ml-auto mr-auto px-4">
            <div class="md:pr-12">
              <h3 class="text-3xl font-semibold">Mentorías</h3>
              <p class="mt-4 mb-2 text-lg leading-relaxed text-gray-600 underline">Mentoría Individual:</p>
              <p class="text-lg leading-relaxed text-gray-600">
                Si queres y buscas un apoyo personalizado y estratégico como así también mejorar tu desempeño, avanzar
                en tu carrera y enfrentar con éxito los desafíos del entorno laboral. A través de sesiones uno a uno,
                trabajaremos de cerca contigo para identificar tus necesidades y objetivos, y crear un plan de acción
                efectivo que te permita alcanzar tu máximo potencial.
              </p>
              <p class="text-lg leading-relaxed text-gray-600">
                Mi servicio de mentorias personalizadas ofrecen:
                Evaluación inicial y definición de objetivos / Desarrollo profesional / Evaluación de transición de
                carrera/ Desarrollo personal
              </p>
              <p class="mt-4 mb-2 text-lg leading-relaxed text-gray-600 underline">Beneficios de Nuestra Mentoría
                Individual:</p>
              <ul class="list-none mt-6">
                <li class="py-2">
                  <div class="flex items-center">
                    <div>
                      <span
                        class="text-xs font-semibold inline-block py-1 px-2 uppercase rounded-full text-pink-600 bg-pink-200 mr-3"><i
                          class="fas fa-fingerprint"></i></span>
                    </div>
                    <div>
                      <h4 class="text-gray-600">
                        Atención Personalizada: Recibirás un apoyo individualizado que se adapta a tus necesidades y
                        metas específicas.
                      </h4>
                    </div>
                  </div>
                </li>
                <li class="py-2">
                  <div class="flex items-center">
                    <div>
                      <span
                        class="text-xs font-semibold inline-block py-1 px-2 uppercase rounded-full text-pink-600 bg-pink-200 mr-3"><i
                          class="fas fa-fingerprint"></i></span>
                    </div>
                    <div>
                      <h4 class="text-gray-600">
                        Confidencialidad y Seguridad: Trabajamos en un entorno seguro y confidencial, donde puedes
                        compartir tus preocupaciones y desafíos con total confianza.
                      </h4>
                    </div>
                  </div>
                </li>
                <li class="py-2">
                  <div class="flex items-center">
                    <div>
                      <span
                        class="text-xs font-semibold inline-block py-1 px-2 uppercase rounded-full text-pink-600 bg-pink-200 mr-3"><i
                          class="fas fa-fingerprint"></i></span>
                    </div>
                    <div>
                      <h4 class="text-gray-600">
                        Resultados Tangibles: Nuestro enfoque práctico y orientado a resultados garantiza mejoras
                        significativas en tu desempeño y satisfacción profesional.
                      </h4>
                    </div>
                  </div>
                </li>
              </ul>
            </div>
          </div>
        </div>
      </div>
    </section>


    <section class="pt-7 relative block bg-gray-900">
      <div class="container mx-auto px-4 lg:pt-24 lg:pb-64">
        <div class="flex flex-wrap text-center justify-center">
          <div class="w-full lg:w-8/12 px-4">
            <h2 class="text-4xl font-semibold text-white">PROGRAMAS</h2>
            <h4 class="text-xl text-white">CONECTA CON TU POTENCIAL</h4>
            <p class="text-xl leading-relaxed mt-4 mb-4 text-gray-500">Si estas en búsqueda de conectar con tu
              potencial, ese que está ahí adentro, este programa es para vos…</p>
            <p class="text-xl leading-relaxed mt-4 mb-4 text-gray-500">Es un programa diseñado para quien verdaderamente
              tiene el compromiso de conectar con su verdadero potencial, ese que está ahí adentro y que hace varios
              meses / años, lo has dejado ahí dormido.</p>
            <p class="text-xl leading-relaxed mt-4 mb-4 text-gray-500">Si te interesa en un primer encuentro te escucho
              y luego te cuento todo lo que podemos hacer para lograr conectar con tu potencial!</p>
          </div>
        </div>
      </div>
    </section>
  </main>
  <footer class="relative bg-gray-300 pt-8 pb-6">
    <div class="bottom-auto top-0 left-0 right-0 w-full absolute pointer-events-none overflow-hidden -mt-20"
      style="height: 80px;">
      <svg class="absolute bottom-0 overflow-hidden" xmlns="http://www.w3.org/2000/svg" preserveAspectRatio="none"
        version="1.1" viewBox="0 0 2560 100" x="0" y="0">
        <polygon class="text-gray-300 fill-current" points="2560 0 2560 100 0 100"></polygon>
      </svg>
    </div>
    <div class="container mx-auto px-4">
      <div class="flex flex-wrap">
        <div class="w-full lg:w-6/12 px-4">
          <h4 class="text-3xl font-semibold">Contacto</h4>
          <h5 class="text-lg mt-0 mb-2 text-gray-700">
            Alta Gracia, Córdoba
          </h5>
          <div class="mt-6">
            <button
              class="bg-white text-blue-400 shadow-lg font-normal h-10 w-10 items-center justify-center align-center rounded-full outline-none focus:outline-none mr-2 p-3"
              type="button">
              <i class="flex fab fa-twitter"></i></button><button
              class="bg-white text-blue-600 shadow-lg font-normal h-10 w-10 items-center justify-center align-center rounded-full outline-none focus:outline-none mr-2 p-3"
              type="button">
              <i class="flex fab fa-facebook-square"></i></button><button
              class="bg-white text-pink-400 shadow-lg font-normal h-10 w-10 items-center justify-center align-center rounded-full outline-none focus:outline-none mr-2 p-3"
              type="button">
              <i class="flex fab fa-dribbble"></i></button><button
              class="bg-white text-gray-900 shadow-lg font-normal h-10 w-10 items-center justify-center align-center rounded-full outline-none focus:outline-none mr-2 p-3"
              type="button">
              <i class="flex fab fa-github"></i>
            </button>
          </div>
        </div>
      </div>
      <hr class="my-6 border-gray-400" />
      <div class="flex flex-wrap items-center md:justify-between justify-center">
        <div class="w-full md:w-4/12 px-4 mx-auto text-center">
          <div class="text-sm text-gray-600 font-semibold py-1">
            &copy; 2024 - GM Coaching y Recursos Humanos
          </div>
        </div>
      </div>
    </div>
  </footer>
</template>

<script setup lang="ts">

</script>

<style scoped></style>