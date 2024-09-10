<template>
  <nav class="top-0 absolute z-50 w-full flex flex-wrap items-center justify-between px-2 py-3 ">
    <div class="container px-4 mx-auto flex flex-wrap items-center justify-between">
      <div class="w-full relative flex justify-between lg:w-auto lg:static lg:block lg:justify-start">
        <img class="h-16" src="./assets/images/logo_header_blanco.png" alt="Logo GM">

      </div>
      <div class="lg:flex flex-grow items-center bg-white lg:bg-transparent lg:shadow-none hidden"
        id="example-collapse-navbar">
        <ul class="flex flex-col lg:flex-row list-none lg:ml-auto">
          <li class="flex items-center">
            <a class="lg:text-white lg:hover:text-gray-300 text-gray-800 px-3 py-4 lg:py-2 flex items-center text-xs uppercase font-bold"
              href="https://wa.me/5493541548717?text=Hola%20Graciela%20Martinez,%20ingrese%20en%20tu%20página%20%20y%20estoy%20interesada%20en%20tus%20servicios.%20Quiero%20que%20me%20contacten!"
              target="_blank"><i
                class="lg:text-gray-300 text-gray-500 font-bold fab fa-whatsapp text-lg leading-lg "></i><span
                class="lg:hidden inline-block ml-2">WhatsApp</span>
            </a>
          </li>
          <li class="flex items-center">
            <a class="lg:text-white lg:hover:text-gray-300 text-gray-800 px-3 py-4 lg:py-2 flex items-center text-xs uppercase font-bold"
              href="https://www.instagram.com/gracielamartinez.coach?igsh=YzljYTk1ODg3Zg==" target="_blank"><i
                class="lg:text-gray-300 text-gray-500 font-bold fab fa-instagram text-lg leading-lg "></i><span
                class="lg:hidden inline-block ml-2">Instagram</span></a>
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
                Graciela Martinez
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
                <p class="mt-2 mb-4 text-gray-600 text-left md:h-40">Inspirar, acompañar, guiar y empoderar a individuos
                  y
                  equipos de trabajos a través de soluciones estratégicas en recursos humanos, coaching laboral y
                  ejecutivo, como así también en mentorías personalizadas.
                  Mi objetivo es fomentar el desarrollo integral y el bienestar, ayudando a mis clientes a alcanzar sus
                  metas profesionales y personales, y a
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
                <p class="mt-2 mb-4 text-gray-600 text-left md:h-40">
                  Convertirme en una líder reconocida en el campo del desarrollo profesional y organizacional,
                  destacándome por mi compromiso con la excelencia, la innovación y el impacto positivo en mis clientes.
                  Aspiro a ser la elección preferida para aquellos que buscan transformar su potencial en resultados
                  tangibles y sostenibles.
                </p>
              </div>
            </div>
          </div>

          <div class="p-6 w-full px-4 text-center">
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
                    manteniendo altos estándares éticos en todas mis relaciones profesionales.
                  </div>
                  <div class="md:col-span-2 text-gray-600 text-left rounded-md shadow-lg p-4">
                    <span class="font-bold text-black text-lg">Excelencia:</span> Mis servicios son de la más alta
                    calidad, adaptándome a las necesidades específicas de cada cliente para superar sus expectativas.
                  </div>
                  <div class="md:col-span-2 text-gray-600 text-left rounded-md shadow-lg p-4">
                    <span class="font-bold text-black text-lg">Empatía:</span> Valoro y comprendo las perspectivas y
                    desafíos únicos de cada cliente, proporcionando un apoyo personalizado y humano.
                  </div>
                  <div class="md:col-span-2 text-gray-600 text-left rounded-md shadow-lg p-4">
                    <span class="font-bold text-black text-lg">Confidencialidad:</span> Protejo la privacidad y la
                    información confidencial de mis clientes, generando un ambiente de confianza y respeto.
                  </div>
                  <div class="md:col-span-2 text-gray-600 text-left rounded-md shadow-lg p-4">
                    <span class="font-bold text-black text-lg">Compromiso:</span> Estoy dedicada al éxito de mis
                    clientes, trabajando arduamente para acompañarlos a alcanzar sus objetivos y maximizar su potencial.
                  </div>
                  <div class="md:col-span-2 text-gray-600 text-left rounded-md shadow-lg p-4">
                    <span class="font-bold text-black text-lg">Innovación:</span> Mantengo una actitud proactiva y
                    abierta a las nuevas tendencias y prácticas en recursos humanos y coaching, asegurando soluciones
                    efectivas y contemporáneas.
                  </div>
                  <div class="md:col-start-2 md:col-span-2 text-gray-600 text-left rounded-md shadow-lg p-4">
                    <span class="font-bold text-black text-lg ">Desarrollo Continuo:</span> Fomento el aprendizaje y el
                    crecimiento constante, tanto para mis clientes como para mí misma, apoyando el avance profesional y
                    personal.
                  </div>
                  <div class="md:col-span-2 text-gray-600 text-left rounded-md shadow-lg p-4 ">
                    <span class="font-bold text-black text-lg">Colaboración:</span> Promuevo la cooperación y el trabajo
                    en equipo, tanto dentro de las organizaciones como en mis interacciones con los clientes, para
                    lograr los mejores resultados posibles.
                  </div>
                </div>
              </div>
            </div>
          </div>

        </div>

      </div>
    </section>

    <h1 class="text-5xl text-gray-600 text-center py-6">Mis servicios</h1>

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
                Mediante un diagnóstico y evaluación de situación se evaluará la posibilidad de realizar un desarrollo
                organizacional, gestión del talento, evaluación de desempeño, gestión del cambio y clima organizacional
                como así también el servicio de gestión tercerizada del área de Recursos Humanos.
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
                Si buscás potenciarte y superar los obstáculos en tu camino hacia el logro de tus metas, ¡Estás en el
                lugar correcto!

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
                Si querés y buscás un apoyo personalizado y estratégico como así también mejorar tu desempeño, avanzar
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
            <p class="text-xl leading-relaxed mt-4 mb-4 text-gray-500">Si estás en búsqueda de conectar con tu
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
      <div class="flex flex-col md:flex-row">
        <div class=" lg:w-6/12 px-4 mb-8 md:mb-0">
          <h4 class="text-3xl text-center md:text-left font-semibold">Contacto</h4>
          <h5 class="text-lg text-center md:text-left mt-0 mb-2 text-gray-700">
            Córdoba & Buenos Aires
          </h5>
          <div class="flex justify-center md:justify-start mt-6">
            <a href="https://wa.me/5493541548717?text=Hola%20Graciela%20Martinez,%20ingrese%20en%20tu%20página%20%20y%20estoy%20interesada%20en%20tus%20servicios.%20Quiero%20que%20me%20contacten!"
              target="_blank"
              class="bg-white text-blue-400 shadow-lg font-normal h-10 w-10 items-center justify-center align-center rounded-full outline-none focus:outline-none mr-2 p-2">
              <svg viewBox="0 0 32 32" fill="none" xmlns="http://www.w3.org/2000/svg">
                <g id="SVGRepo_bgCarrier" stroke-width="0"></g>
                <g id="SVGRepo_tracerCarrier" stroke-linecap="round" stroke-linejoin="round"></g>
                <g id="SVGRepo_iconCarrier">
                  <path fill-rule="evenodd" clip-rule="evenodd"
                    d="M16 31C23.732 31 30 24.732 30 17C30 9.26801 23.732 3 16 3C8.26801 3 2 9.26801 2 17C2 19.5109 2.661 21.8674 3.81847 23.905L2 31L9.31486 29.3038C11.3014 30.3854 13.5789 31 16 31ZM16 28.8462C22.5425 28.8462 27.8462 23.5425 27.8462 17C27.8462 10.4576 22.5425 5.15385 16 5.15385C9.45755 5.15385 4.15385 10.4576 4.15385 17C4.15385 19.5261 4.9445 21.8675 6.29184 23.7902L5.23077 27.7692L9.27993 26.7569C11.1894 28.0746 13.5046 28.8462 16 28.8462Z"
                    fill="#BFC8D0"></path>
                  <path
                    d="M28 16C28 22.6274 22.6274 28 16 28C13.4722 28 11.1269 27.2184 9.19266 25.8837L5.09091 26.9091L6.16576 22.8784C4.80092 20.9307 4 18.5589 4 16C4 9.37258 9.37258 4 16 4C22.6274 4 28 9.37258 28 16Z"
                    fill="url(#paint0_linear_87_7264)"></path>
                  <path fill-rule="evenodd" clip-rule="evenodd"
                    d="M16 30C23.732 30 30 23.732 30 16C30 8.26801 23.732 2 16 2C8.26801 2 2 8.26801 2 16C2 18.5109 2.661 20.8674 3.81847 22.905L2 30L9.31486 28.3038C11.3014 29.3854 13.5789 30 16 30ZM16 27.8462C22.5425 27.8462 27.8462 22.5425 27.8462 16C27.8462 9.45755 22.5425 4.15385 16 4.15385C9.45755 4.15385 4.15385 9.45755 4.15385 16C4.15385 18.5261 4.9445 20.8675 6.29184 22.7902L5.23077 26.7692L9.27993 25.7569C11.1894 27.0746 13.5046 27.8462 16 27.8462Z"
                    fill="white"></path>
                  <path
                    d="M12.5 9.49989C12.1672 8.83131 11.6565 8.8905 11.1407 8.8905C10.2188 8.8905 8.78125 9.99478 8.78125 12.05C8.78125 13.7343 9.52345 15.578 12.0244 18.3361C14.438 20.9979 17.6094 22.3748 20.2422 22.3279C22.875 22.2811 23.4167 20.0154 23.4167 19.2503C23.4167 18.9112 23.2062 18.742 23.0613 18.696C22.1641 18.2654 20.5093 17.4631 20.1328 17.3124C19.7563 17.1617 19.5597 17.3656 19.4375 17.4765C19.0961 17.8018 18.4193 18.7608 18.1875 18.9765C17.9558 19.1922 17.6103 19.083 17.4665 19.0015C16.9374 18.7892 15.5029 18.1511 14.3595 17.0426C12.9453 15.6718 12.8623 15.2001 12.5959 14.7803C12.3828 14.4444 12.5392 14.2384 12.6172 14.1483C12.9219 13.7968 13.3426 13.254 13.5313 12.9843C13.7199 12.7145 13.5702 12.305 13.4803 12.05C13.0938 10.953 12.7663 10.0347 12.5 9.49989Z"
                    fill="white"></path>
                  <defs>
                    <linearGradient id="paint0_linear_87_7264" x1="26.5" y1="7" x2="4" y2="28"
                      gradientUnits="userSpaceOnUse">
                      <stop stop-color="#5BD066"></stop>
                      <stop offset="1" stop-color="#27B43E"></stop>
                    </linearGradient>
                  </defs>
                </g>
              </svg>
            </a>
            <a href="https://www.instagram.com/gracielamartinez.coach?igsh=YzljYTk1ODg3Zg==" target="_blank"
              class="bg-white text-blue-600 shadow-lg font-normal h-10 w-10 items-center justify-center align-center rounded-full outline-none focus:outline-none mr-2 p-2">
              <svg viewBox="0 0 32 32" fill="none" xmlns="http://www.w3.org/2000/svg">
                <g id="SVGRepo_bgCarrier" stroke-width="0"></g>
                <g id="SVGRepo_tracerCarrier" stroke-linecap="round" stroke-linejoin="round"></g>
                <g id="SVGRepo_iconCarrier">
                  <rect x="2" y="2" width="28" height="28" rx="6" fill="url(#paint0_radial_87_7153)"></rect>
                  <rect x="2" y="2" width="28" height="28" rx="6" fill="url(#paint1_radial_87_7153)"></rect>
                  <rect x="2" y="2" width="28" height="28" rx="6" fill="url(#paint2_radial_87_7153)"></rect>
                  <path
                    d="M23 10.5C23 11.3284 22.3284 12 21.5 12C20.6716 12 20 11.3284 20 10.5C20 9.67157 20.6716 9 21.5 9C22.3284 9 23 9.67157 23 10.5Z"
                    fill="white"></path>
                  <path fill-rule="evenodd" clip-rule="evenodd"
                    d="M16 21C18.7614 21 21 18.7614 21 16C21 13.2386 18.7614 11 16 11C13.2386 11 11 13.2386 11 16C11 18.7614 13.2386 21 16 21ZM16 19C17.6569 19 19 17.6569 19 16C19 14.3431 17.6569 13 16 13C14.3431 13 13 14.3431 13 16C13 17.6569 14.3431 19 16 19Z"
                    fill="white"></path>
                  <path fill-rule="evenodd" clip-rule="evenodd"
                    d="M6 15.6C6 12.2397 6 10.5595 6.65396 9.27606C7.2292 8.14708 8.14708 7.2292 9.27606 6.65396C10.5595 6 12.2397 6 15.6 6H16.4C19.7603 6 21.4405 6 22.7239 6.65396C23.8529 7.2292 24.7708 8.14708 25.346 9.27606C26 10.5595 26 12.2397 26 15.6V16.4C26 19.7603 26 21.4405 25.346 22.7239C24.7708 23.8529 23.8529 24.7708 22.7239 25.346C21.4405 26 19.7603 26 16.4 26H15.6C12.2397 26 10.5595 26 9.27606 25.346C8.14708 24.7708 7.2292 23.8529 6.65396 22.7239C6 21.4405 6 19.7603 6 16.4V15.6ZM15.6 8H16.4C18.1132 8 19.2777 8.00156 20.1779 8.0751C21.0548 8.14674 21.5032 8.27659 21.816 8.43597C22.5686 8.81947 23.1805 9.43139 23.564 10.184C23.7234 10.4968 23.8533 10.9452 23.9249 11.8221C23.9984 12.7223 24 13.8868 24 15.6V16.4C24 18.1132 23.9984 19.2777 23.9249 20.1779C23.8533 21.0548 23.7234 21.5032 23.564 21.816C23.1805 22.5686 22.5686 23.1805 21.816 23.564C21.5032 23.7234 21.0548 23.8533 20.1779 23.9249C19.2777 23.9984 18.1132 24 16.4 24H15.6C13.8868 24 12.7223 23.9984 11.8221 23.9249C10.9452 23.8533 10.4968 23.7234 10.184 23.564C9.43139 23.1805 8.81947 22.5686 8.43597 21.816C8.27659 21.5032 8.14674 21.0548 8.0751 20.1779C8.00156 19.2777 8 18.1132 8 16.4V15.6C8 13.8868 8.00156 12.7223 8.0751 11.8221C8.14674 10.9452 8.27659 10.4968 8.43597 10.184C8.81947 9.43139 9.43139 8.81947 10.184 8.43597C10.4968 8.27659 10.9452 8.14674 11.8221 8.0751C12.7223 8.00156 13.8868 8 15.6 8Z"
                    fill="white"></path>
                  <defs>
                    <radialGradient id="paint0_radial_87_7153" cx="0" cy="0" r="1" gradientUnits="userSpaceOnUse"
                      gradientTransform="translate(12 23) rotate(-55.3758) scale(25.5196)">
                      <stop stop-color="#B13589"></stop>
                      <stop offset="0.79309" stop-color="#C62F94"></stop>
                      <stop offset="1" stop-color="#8A3AC8"></stop>
                    </radialGradient>
                    <radialGradient id="paint1_radial_87_7153" cx="0" cy="0" r="1" gradientUnits="userSpaceOnUse"
                      gradientTransform="translate(11 31) rotate(-65.1363) scale(22.5942)">
                      <stop stop-color="#E0E8B7"></stop>
                      <stop offset="0.444662" stop-color="#FB8A2E"></stop>
                      <stop offset="0.71474" stop-color="#E2425C"></stop>
                      <stop offset="1" stop-color="#E2425C" stop-opacity="0"></stop>
                    </radialGradient>
                    <radialGradient id="paint2_radial_87_7153" cx="0" cy="0" r="1" gradientUnits="userSpaceOnUse"
                      gradientTransform="translate(0.500002 3) rotate(-8.1301) scale(38.8909 8.31836)">
                      <stop offset="0.156701" stop-color="#406ADC"></stop>
                      <stop offset="0.467799" stop-color="#6A45BE"></stop>
                      <stop offset="1" stop-color="#6A45BE" stop-opacity="0"></stop>
                    </radialGradient>
                  </defs>
                </g>
              </svg>
            </a>
          </div>
        </div>
        <div class="flex justify-center md:justify-end items-center lg:w-6/12 px-4">
          <img class="w-40 h-40" src="./assets/images/logo_redondo_footer.png" alt="Logo GM Redondo">
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