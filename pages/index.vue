<template>
  <div class="w-full">
    <!-- Hero section -->
    <section id="hero" class="w-full h-screen relative bg-hero-beach bg-cover bg-center">
      <div class="absolute inset-0 bg-black bg-opacity-30"></div>
      <div class="relative h-full flex flex-col items-center justify-center space-y-8 px-4">
        <img
          data-aos="zoom-in"
          data-aos-once="true"
          src="/img/logo/nativa.svg"
          class="w-48 sm:w-64 xl:w-80"
          alt="Nativa Logo"
        />
        <h1
          data-aos="fade-up"
          data-aos-once="true"
          data-aos-delay="300"
          class="text-4xl sm:text-5xl xl:text-7xl font-bold text-white text-center tracking-wider"
        >
          VIVE EXPERIENCIAS ÚNICAS
        </h1>
      </div>
    </section>

    <!-- Destinos destacados section -->
    <section
      class="max-w-screen-xl mx-2 sm:mx-auto px-4 sm:px-6 lg:px-8 py-12 pb-20 sm:py-16 rounded-[2.25rem] sm:rounded-xl bg-white shadow-lg sm:shadow-md transform lg:-translate-y-12"
    >
      <h2 class="text-4xl sm:text-5xl xl:text-6xl font-extrabold text-center mb-12 text-destinations-gradient tracking-wide drop-shadow-lg">
        DESCUBRE NUESTROS DESTINOS
      </h2>
      <div class="w-full grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
        <!-- Colombia Card -->
        <div
          data-aos="fade-up"
          class="destination-card group relative overflow-hidden rounded-2xl shadow-xl cursor-pointer transition-all duration-300 hover:shadow-2xl hover:-translate-y-2"
        >
          <div class="destination-image bg-colombia bg-cover bg-center h-80 relative">
            <div class="absolute inset-0 bg-gradient-to-t from-black via-black/40 to-transparent opacity-70 group-hover:opacity-80 transition-opacity duration-300"></div>
            <div class="absolute bottom-0 left-0 right-0 p-6 text-white">
              <h3 class="text-3xl font-bold mb-2">Colombia</h3>
              <p class="text-sm opacity-90">Naturaleza y cultura vibrante</p>
            </div>
            <div class="absolute bottom-6 right-6 bg-white rounded-full p-3 shadow-lg group-hover:bg-blue-500 transition-all duration-300">
              <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6 text-gray-800 group-hover:text-white transition-colors duration-300" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="2">
                <path stroke-linecap="round" stroke-linejoin="round" d="M17 8l4 4m0 0l-4 4m4-4H3" />
              </svg>
            </div>
          </div>
        </div>

        <!-- Perú Card -->
        <div
          data-aos="fade-up"
          data-aos-delay="150"
          class="destination-card group relative overflow-hidden rounded-2xl shadow-xl cursor-pointer transition-all duration-300 hover:shadow-2xl hover:-translate-y-2"
        >
          <div class="destination-image bg-peru bg-cover bg-center h-80 relative">
            <div class="absolute inset-0 bg-gradient-to-t from-black via-black/40 to-transparent opacity-70 group-hover:opacity-80 transition-opacity duration-300"></div>
            <div class="absolute bottom-0 left-0 right-0 p-6 text-white">
              <h3 class="text-3xl font-bold mb-2">Perú</h3>
              <p class="text-sm opacity-90">Historia milenaria y aventura</p>
            </div>
            <div class="absolute bottom-6 right-6 bg-white rounded-full p-3 shadow-lg group-hover:bg-blue-500 transition-all duration-300">
              <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6 text-gray-800 group-hover:text-white transition-colors duration-300" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="2">
                <path stroke-linecap="round" stroke-linejoin="round" d="M17 8l4 4m0 0l-4 4m4-4H3" />
              </svg>
            </div>
          </div>
        </div>

        <!-- Honduras Card -->
        <div
          data-aos="fade-up"
          data-aos-delay="300"
          class="destination-card group relative overflow-hidden rounded-2xl shadow-xl cursor-pointer transition-all duration-300 hover:shadow-2xl hover:-translate-y-2"
        >
          <div class="destination-image bg-honduras bg-cover bg-center h-80 relative">
            <div class="absolute inset-0 bg-gradient-to-t from-black via-black/40 to-transparent opacity-70 group-hover:opacity-80 transition-opacity duration-300"></div>
            <div class="absolute bottom-0 left-0 right-0 p-6 text-white">
              <h3 class="text-3xl font-bold mb-2">Honduras</h3>
              <p class="text-sm opacity-90">Paraísos caribeños inexplorados</p>
            </div>
            <div class="absolute bottom-6 right-6 bg-white rounded-full p-3 shadow-lg group-hover:bg-blue-500 transition-all duration-300">
              <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6 text-gray-800 group-hover:text-white transition-colors duration-300" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="2">
                <path stroke-linecap="round" stroke-linejoin="round" d="M17 8l4 4m0 0l-4 4m4-4H3" />
              </svg>
            </div>
          </div>
        </div>
      </div>
    </section>

    <!-- Servicios section -->
    <section class="w-full my-24 px-4">
      <div class="max-w-screen-xl mx-auto">
        <div class="text-center mb-16">
          <h2
            data-aos="fade-up"
            class="text-4xl sm:text-5xl font-bold mb-4 text-gray-800"
          >
            Nuestros <span class="text-header-gradient">Servicios</span>
          </h2>
          <p data-aos="fade-up" data-aos-delay="100" class="text-lg text-gray-600 max-w-2xl mx-auto">
            Hacemos de tu viaje una experiencia inolvidable con servicios de primera calidad
          </p>
        </div>

        <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
          <!-- Guías Profesionales -->
          <div
            data-aos="fade-up"
            data-aos-delay="0"
            class="service-card-container h-80"
          >
            <div class="service-card-flip">
              <!-- Front -->
              <div class="service-card-front bg-white rounded-2xl p-8 shadow-lg border border-gray-100 relative overflow-hidden">
                <div class="absolute top-0 right-0 w-32 h-32 bg-gradient-to-br from-[#3984f4]/5 to-transparent rounded-full -mr-16 -mt-16"></div>
                <div class="relative z-10 h-full flex flex-col">
                  <div class="w-16 h-16 bg-gradient-to-br from-[#3984f4] to-[#0cd3ff] rounded-xl flex items-center justify-center mb-6 shadow-lg">
                    <svg xmlns="http://www.w3.org/2000/svg" class="h-8 w-8 text-white" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="2">
                      <path stroke-linecap="round" stroke-linejoin="round" d="M17 20h5v-2a3 3 0 00-5.356-1.857M17 20H7m10 0v-2c0-.656-.126-1.283-.356-1.857M7 20H2v-2a3 3 0 015.356-1.857M7 20v-2c0-.656.126-1.283.356-1.857m0 0a5.002 5.002 0 019.288 0M15 7a3 3 0 11-6 0 3 3 0 016 0zm6 3a2 2 0 11-4 0 2 2 0 014 0zM7 10a2 2 0 11-4 0 2 2 0 014 0z" />
                    </svg>
                  </div>
                  <h3 class="text-2xl font-bold mb-3 text-gray-800">Guías Profesionales</h3>
                  <p class="text-gray-600 leading-relaxed">
                    Expertos locales certificados que te llevarán a descubrir los secretos mejor guardados de cada destino
                  </p>
                </div>
              </div>
              <!-- Back -->
              <div class="service-card-back rounded-2xl p-6 shadow-lg relative overflow-hidden">
                <img src="https://images.unsplash.com/photo-1539635278303-d4002c07eae3?q=80&w=800" class="absolute inset-0 w-full h-full object-cover" alt="Guía">
                <div class="absolute inset-0 bg-gradient-to-t from-[#002b64]/90 via-[#002b64]/50 to-transparent"></div>
                <div class="relative z-10 h-full flex flex-col justify-center items-center text-center text-white">
                  <svg xmlns="http://www.w3.org/2000/svg" class="h-16 w-16 mb-4" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="2">
                    <path stroke-linecap="round" stroke-linejoin="round" d="M9 12l2 2 4-4m6 2a9 9 0 11-18 0 9 9 0 0118 0z" />
                  </svg>
                  <h4 class="text-xl font-bold mb-3">Guías Certificados</h4>
                  <p class="text-sm opacity-90">✓ Expertos locales</p>
                  <p class="text-sm opacity-90">✓ Múltiples idiomas</p>
                  <p class="text-sm opacity-90">✓ Experiencia comprobada</p>
                </div>
              </div>
            </div>
          </div>

          <!-- Fotografía Profesional -->
          <div
            data-aos="fade-up"
            data-aos-delay="100"
            class="service-card-container h-80"
          >
            <div class="service-card-flip">
              <!-- Front -->
              <div class="service-card-front bg-white rounded-2xl p-8 shadow-lg border border-gray-100 relative overflow-hidden">
                <div class="absolute top-0 right-0 w-32 h-32 bg-gradient-to-br from-[#0cd3ff]/5 to-transparent rounded-full -mr-16 -mt-16"></div>
                <div class="relative z-10 h-full flex flex-col">
                  <div class="w-16 h-16 bg-gradient-to-br from-[#0cd3ff] to-[#2f7cf0] rounded-xl flex items-center justify-center mb-6 shadow-lg">
                    <svg xmlns="http://www.w3.org/2000/svg" class="h-8 w-8 text-white" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="2">
                      <path stroke-linecap="round" stroke-linejoin="round" d="M3 9a2 2 0 012-2h.93a2 2 0 001.664-.89l.812-1.22A2 2 0 0110.07 4h3.86a2 2 0 011.664.89l.812 1.22A2 2 0 0018.07 7H19a2 2 0 012 2v9a2 2 0 01-2 2H5a2 2 0 01-2-2V9z" />
                      <path stroke-linecap="round" stroke-linejoin="round" d="M15 13a3 3 0 11-6 0 3 3 0 016 0z" />
                    </svg>
                  </div>
                  <h3 class="text-2xl font-bold mb-3 text-gray-800">Fotografía Profesional</h3>
                  <p class="text-gray-600 leading-relaxed">
                    Capturamos los mejores momentos de tu viaje con fotógrafos expertos para que conserves recuerdos únicos
                  </p>
                </div>
              </div>
              <!-- Back -->
              <div class="service-card-back rounded-2xl p-6 shadow-lg relative overflow-hidden">
                <img src="https://images.unsplash.com/photo-1542038784456-1ea8e935640e?q=80&w=800" class="absolute inset-0 w-full h-full object-cover" alt="Fotografía">
                <div class="absolute inset-0 bg-gradient-to-t from-[#002b64]/90 via-[#002b64]/50 to-transparent"></div>
                <div class="relative z-10 h-full flex flex-col justify-center items-center text-center text-white">
                  <svg xmlns="http://www.w3.org/2000/svg" class="h-16 w-16 mb-4" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="2">
                    <path stroke-linecap="round" stroke-linejoin="round" d="M4 16l4.586-4.586a2 2 0 012.828 0L16 16m-2-2l1.586-1.586a2 2 0 012.828 0L20 14m-6-6h.01M6 20h12a2 2 0 002-2V6a2 2 0 00-2-2H6a2 2 0 00-2 2v12a2 2 0 002 2z" />
                  </svg>
                  <h4 class="text-xl font-bold mb-3">Sesión Fotográfica</h4>
                  <p class="text-sm opacity-90">✓ Fotógrafos profesionales</p>
                  <p class="text-sm opacity-90">✓ Edición incluida</p>
                  <p class="text-sm opacity-90">✓ Galería digital</p>
                </div>
              </div>
            </div>
          </div>

          <!-- Hospedaje Premium -->
          <div
            data-aos="fade-up"
            data-aos-delay="200"
            class="service-card-container h-80"
          >
            <div class="service-card-flip">
              <!-- Front -->
              <div class="service-card-front bg-white rounded-2xl p-8 shadow-lg border border-gray-100 relative overflow-hidden">
                <div class="absolute top-0 right-0 w-32 h-32 bg-gradient-to-br from-[#2f7cf0]/5 to-transparent rounded-full -mr-16 -mt-16"></div>
                <div class="relative z-10 h-full flex flex-col">
                  <div class="w-16 h-16 bg-gradient-to-br from-[#2f7cf0] to-[#0e65e8] rounded-xl flex items-center justify-center mb-6 shadow-lg">
                    <svg xmlns="http://www.w3.org/2000/svg" class="h-8 w-8 text-white" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="2">
                      <path stroke-linecap="round" stroke-linejoin="round" d="M19 21V5a2 2 0 00-2-2H7a2 2 0 00-2 2v16m14 0h2m-2 0h-5m-9 0H3m2 0h5M9 7h1m-1 4h1m4-4h1m-1 4h1m-5 10v-5a1 1 0 011-1h2a1 1 0 011 1v5m-4 0h4" />
                    </svg>
                  </div>
                  <h3 class="text-2xl font-bold mb-3 text-gray-800">Hospedaje Premium</h3>
                  <p class="text-gray-600 leading-relaxed">
                    Hoteles y alojamientos cuidadosamente seleccionados para garantizar tu comodidad y descanso
                  </p>
                </div>
              </div>
              <!-- Back -->
              <div class="service-card-back rounded-2xl p-6 shadow-lg relative overflow-hidden">
                <img src="https://images.unsplash.com/photo-1566073771259-6a8506099945?q=80&w=800" class="absolute inset-0 w-full h-full object-cover" alt="Hotel">
                <div class="absolute inset-0 bg-gradient-to-t from-[#002b64]/90 via-[#002b64]/50 to-transparent"></div>
                <div class="relative z-10 h-full flex flex-col justify-center items-center text-center text-white">
                  <svg xmlns="http://www.w3.org/2000/svg" class="h-16 w-16 mb-4" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="2">
                    <path stroke-linecap="round" stroke-linejoin="round" d="M5 3v4M3 5h4M6 17v4m-2-2h4m5-16l2.286 6.857L21 12l-5.714 2.143L13 21l-2.286-6.857L5 12l5.714-2.143L13 3z" />
                  </svg>
                  <h4 class="text-xl font-bold mb-3">Alojamiento 5 Estrellas</h4>
                  <p class="text-sm opacity-90">✓ Hoteles seleccionados</p>
                  <p class="text-sm opacity-90">✓ Ubicaciones premium</p>
                  <p class="text-sm opacity-90">✓ Desayuno incluido</p>
                </div>
              </div>
            </div>
          </div>

          <!-- Transporte Privado -->
          <div
            data-aos="fade-up"
            data-aos-delay="300"
            class="service-card-container h-80"
          >
            <div class="service-card-flip">
              <!-- Front -->
              <div class="service-card-front bg-white rounded-2xl p-8 shadow-lg border border-gray-100 relative overflow-hidden">
                <div class="absolute top-0 right-0 w-32 h-32 bg-gradient-to-br from-[#0e65e8]/5 to-transparent rounded-full -mr-16 -mt-16"></div>
                <div class="relative z-10 h-full flex flex-col">
                  <div class="w-16 h-16 bg-gradient-to-br from-[#0e65e8] to-[#3984f4] rounded-xl flex items-center justify-center mb-6 shadow-lg">
                    <svg xmlns="http://www.w3.org/2000/svg" class="h-8 w-8 text-white" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="2">
                      <path stroke-linecap="round" stroke-linejoin="round" d="M8 7h12m0 0l-4-4m4 4l-4 4m0 6H4m0 0l4 4m-4-4l4-4" />
                    </svg>
                  </div>
                  <h3 class="text-2xl font-bold mb-3 text-gray-800">Transporte Privado</h3>
                  <p class="text-gray-600 leading-relaxed">
                    Vehículos modernos y cómodos con conductores profesionales para todos tus traslados
                  </p>
                </div>
              </div>
              <!-- Back -->
              <div class="service-card-back rounded-2xl p-6 shadow-lg relative overflow-hidden">
                <img src="https://images.unsplash.com/photo-1449965408869-eaa3f722e40d?q=80&w=800" class="absolute inset-0 w-full h-full object-cover" alt="Transporte">
                <div class="absolute inset-0 bg-gradient-to-t from-[#002b64]/90 via-[#002b64]/50 to-transparent"></div>
                <div class="relative z-10 h-full flex flex-col justify-center items-center text-center text-white">
                  <svg xmlns="http://www.w3.org/2000/svg" class="h-16 w-16 mb-4" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="2">
                    <path d="M9 17a2 2 0 11-4 0 2 2 0 014 0zM19 17a2 2 0 11-4 0 2 2 0 014 0z" />
                    <path stroke-linecap="round" stroke-linejoin="round" d="M13 16V6a1 1 0 00-1-1H4a1 1 0 00-1 1v10a1 1 0 001 1h1m8-1a1 1 0 01-1 1H9m4-1V8a1 1 0 011-1h2.586a1 1 0 01.707.293l3.414 3.414a1 1 0 01.293.707V16a1 1 0 01-1 1h-1m-6-1a1 1 0 001 1h1M5 17a2 2 0 104 0m-4 0a2 2 0 114 0m6 0a2 2 0 104 0m-4 0a2 2 0 114 0" />
                  </svg>
                  <h4 class="text-xl font-bold mb-3">Traslados Exclusivos</h4>
                  <p class="text-sm opacity-90">✓ Vehículos de lujo</p>
                  <p class="text-sm opacity-90">✓ Conductores bilingües</p>
                  <p class="text-sm opacity-90">✓ Disponibilidad 24/7</p>
                </div>
              </div>
            </div>
          </div>

          <!-- Experiencias Exclusivas -->
          <div
            data-aos="fade-up"
            data-aos-delay="400"
            class="service-card-container h-80"
          >
            <div class="service-card-flip">
              <!-- Front -->
              <div class="service-card-front bg-white rounded-2xl p-8 shadow-lg border border-gray-100 relative overflow-hidden">
                <div class="absolute top-0 right-0 w-32 h-32 bg-gradient-to-br from-[#3984f4]/5 to-transparent rounded-full -mr-16 -mt-16"></div>
                <div class="relative z-10 h-full flex flex-col">
                  <div class="w-16 h-16 bg-gradient-to-br from-[#3984f4] to-[#0cd3ff] rounded-xl flex items-center justify-center mb-6 shadow-lg">
                    <svg xmlns="http://www.w3.org/2000/svg" class="h-8 w-8 text-white" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="2">
                      <path stroke-linecap="round" stroke-linejoin="round" d="M5 3v4M3 5h4M6 17v4m-2-2h4m5-16l2.286 6.857L21 12l-5.714 2.143L13 21l-2.286-6.857L5 12l5.714-2.143L13 3z" />
                    </svg>
                  </div>
                  <h3 class="text-2xl font-bold mb-3 text-gray-800">Experiencias Exclusivas</h3>
                  <p class="text-gray-600 leading-relaxed">
                    Actividades únicas y personalizadas que te conectarán con la cultura y naturaleza local
                  </p>
                </div>
              </div>
              <!-- Back -->
              <div class="service-card-back rounded-2xl p-6 shadow-lg relative overflow-hidden">
                <img src="https://images.unsplash.com/photo-1469854523086-cc02fe5d8800?q=80&w=800" class="absolute inset-0 w-full h-full object-cover" alt="Experiencias">
                <div class="absolute inset-0 bg-gradient-to-t from-[#002b64]/90 via-[#002b64]/50 to-transparent"></div>
                <div class="relative z-10 h-full flex flex-col justify-center items-center text-center text-white">
                  <svg xmlns="http://www.w3.org/2000/svg" class="h-16 w-16 mb-4" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="2">
                    <path stroke-linecap="round" stroke-linejoin="round" d="M14 10h4.764a2 2 0 011.789 2.894l-3.5 7A2 2 0 0115.263 21h-4.017c-.163 0-.326-.02-.485-.06L7 20m7-10V5a2 2 0 00-2-2h-.095c-.5 0-.905.405-.905.905 0 .714-.211 1.412-.608 2.006L7 11v9m7-10h-2M7 20H5a2 2 0 01-2-2v-6a2 2 0 012-2h2.5" />
                  </svg>
                  <h4 class="text-xl font-bold mb-3">Aventuras Únicas</h4>
                  <p class="text-sm opacity-90">✓ Tours personalizados</p>
                  <p class="text-sm opacity-90">✓ Actividades exclusivas</p>
                  <p class="text-sm opacity-90">✓ Cultura local</p>
                </div>
              </div>
            </div>
          </div>

          <!-- Soporte 24/7 -->
          <div
            data-aos="fade-up"
            data-aos-delay="500"
            class="service-card-container h-80"
          >
            <div class="service-card-flip">
              <!-- Front -->
              <div class="service-card-front bg-white rounded-2xl p-8 shadow-lg border border-gray-100 relative overflow-hidden">
                <div class="absolute top-0 right-0 w-32 h-32 bg-gradient-to-br from-[#0cd3ff]/5 to-transparent rounded-full -mr-16 -mt-16"></div>
                <div class="relative z-10 h-full flex flex-col">
                  <div class="w-16 h-16 bg-gradient-to-br from-[#0cd3ff] to-[#2f7cf0] rounded-xl flex items-center justify-center mb-6 shadow-lg">
                    <svg xmlns="http://www.w3.org/2000/svg" class="h-8 w-8 text-white" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="2">
                      <path stroke-linecap="round" stroke-linejoin="round" d="M18.364 5.636l-3.536 3.536m0 5.656l3.536 3.536M9.172 9.172L5.636 5.636m3.536 9.192l-3.536 3.536M21 12a9 9 0 11-18 0 9 9 0 0118 0zm-5 0a4 4 0 11-8 0 4 4 0 018 0z" />
                    </svg>
                  </div>
                  <h3 class="text-2xl font-bold mb-3 text-gray-800">Soporte 24/7</h3>
                  <p class="text-gray-600 leading-relaxed">
                    Asistencia constante en tu idioma, en cualquier momento y lugar durante todo tu viaje
                  </p>
                </div>
              </div>
              <!-- Back -->
              <div class="service-card-back rounded-2xl p-6 shadow-lg relative overflow-hidden">
                <img src="https://images.unsplash.com/photo-1486312338219-ce68d2c6f44d?q=80&w=800" class="absolute inset-0 w-full h-full object-cover" alt="Soporte">
                <div class="absolute inset-0 bg-gradient-to-t from-[#002b64]/90 via-[#002b64]/50 to-transparent"></div>
                <div class="relative z-10 h-full flex flex-col justify-center items-center text-center text-white">
                  <svg xmlns="http://www.w3.org/2000/svg" class="h-16 w-16 mb-4" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="2">
                    <path stroke-linecap="round" stroke-linejoin="round" d="M3 5a2 2 0 012-2h3.28a1 1 0 01.948.684l1.498 4.493a1 1 0 01-.502 1.21l-2.257 1.13a11.042 11.042 0 005.516 5.516l1.13-2.257a1 1 0 011.21-.502l4.493 1.498a1 1 0 01.684.949V19a2 2 0 01-2 2h-1C9.716 21 3 14.284 3 6V5z" />
                  </svg>
                  <h4 class="text-xl font-bold mb-3">Atención Continua</h4>
                  <p class="text-sm opacity-90">✓ Chat en vivo</p>
                  <p class="text-sm opacity-90">✓ Atención multilingüe</p>
                  <p class="text-sm opacity-90">✓ Sin horarios</p>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>

    <!-- Team section -->
    <section class="relative max-w-screen-xl mx-auto px-4 sm:px-6 lg:px-8 my-24">
      <div class="text-center mb-16">
        <h2
          data-aos="fade-up"
          class="text-4xl sm:text-5xl font-bold mb-4 text-gray-800"
        >
          Conoce a <span class="text-header-gradient">Nuestro Equipo</span>
        </h2>
        <p data-aos="fade-up" data-aos-delay="100" class="text-lg text-gray-600 max-w-2xl mx-auto">
          Profesionales apasionados dedicados a hacer de tu viaje una experiencia inolvidable
        </p>
      </div>

      <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-8">
        <!-- Team Member 1 -->
        <div
          data-aos="fade-up"
          data-aos-delay="0"
          class="group bg-white rounded-2xl shadow-lg hover:shadow-2xl transition-all duration-300 overflow-hidden"
        >
          <div class="relative h-64 overflow-hidden">
            <img
              src="https://images.unsplash.com/photo-1560250097-0b93528c311a?q=80&w=800"
              class="w-full h-full object-cover group-hover:scale-110 transition-transform duration-500"
              alt="Team member"
            />
            <div class="absolute inset-0 bg-gradient-to-t from-[#002b64]/80 to-transparent opacity-0 group-hover:opacity-100 transition-opacity duration-300"></div>
          </div>
          <div class="p-6">
            <h3 class="text-xl font-bold text-gray-800 mb-1">Carlos Mendoza</h3>
            <p class="text-sm text-[#002b64] font-semibold mb-3">Director General</p>
            <div class="flex items-center gap-2 mb-3">
              <img src="https://flagcdn.com/w20/co.png" class="w-5 h-auto" alt="Colombia" />
              <span class="text-sm text-gray-600">Colombia</span>
            </div>
            <div class="flex items-center gap-2 text-sm text-gray-600">
              <svg xmlns="http://www.w3.org/2000/svg" class="h-4 w-4" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="2">
                <path stroke-linecap="round" stroke-linejoin="round" d="M3 8l7.89 5.26a2 2 0 002.22 0L21 8M5 19h14a2 2 0 002-2V7a2 2 0 00-2-2H5a2 2 0 00-2 2v10a2 2 0 002 2z" />
              </svg>
              <a href="mailto:carlos@nativa.com" class="hover:text-[#002b64] transition-colors">carlos@nativa.com</a>
            </div>
          </div>
        </div>

        <!-- Team Member 2 -->
        <div
          data-aos="fade-up"
          data-aos-delay="100"
          class="group bg-white rounded-2xl shadow-lg hover:shadow-2xl transition-all duration-300 overflow-hidden"
        >
          <div class="relative h-64 overflow-hidden">
            <img
              src="https://images.unsplash.com/photo-1573496359142-b8d87734a5a2?q=80&w=800"
              class="w-full h-full object-cover group-hover:scale-110 transition-transform duration-500"
              alt="Team member"
            />
            <div class="absolute inset-0 bg-gradient-to-t from-[#002b64]/80 to-transparent opacity-0 group-hover:opacity-100 transition-opacity duration-300"></div>
          </div>
          <div class="p-6">
            <h3 class="text-xl font-bold text-gray-800 mb-1">María Rodríguez</h3>
            <p class="text-sm text-[#002b64] font-semibold mb-3">Coordinadora de Viajes</p>
            <div class="flex items-center gap-2 mb-3">
              <img src="https://flagcdn.com/w20/pe.png" class="w-5 h-auto" alt="Perú" />
              <span class="text-sm text-gray-600">Perú</span>
            </div>
            <div class="flex items-center gap-2 text-sm text-gray-600">
              <svg xmlns="http://www.w3.org/2000/svg" class="h-4 w-4" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="2">
                <path stroke-linecap="round" stroke-linejoin="round" d="M3 8l7.89 5.26a2 2 0 002.22 0L21 8M5 19h14a2 2 0 002-2V7a2 2 0 00-2-2H5a2 2 0 00-2 2v10a2 2 0 002 2z" />
              </svg>
              <a href="mailto:maria@nativa.com" class="hover:text-[#002b64] transition-colors">maria@nativa.com</a>
            </div>
          </div>
        </div>

        <!-- Team Member 3 -->
        <div
          data-aos="fade-up"
          data-aos-delay="200"
          class="group bg-white rounded-2xl shadow-lg hover:shadow-2xl transition-all duration-300 overflow-hidden"
        >
          <div class="relative h-64 overflow-hidden">
            <img
              src="https://images.unsplash.com/photo-1519085360753-af0119f7cbe7?q=80&w=800"
              class="w-full h-full object-cover group-hover:scale-110 transition-transform duration-500"
              alt="Team member"
            />
            <div class="absolute inset-0 bg-gradient-to-t from-[#002b64]/80 to-transparent opacity-0 group-hover:opacity-100 transition-opacity duration-300"></div>
          </div>
          <div class="p-6">
            <h3 class="text-xl font-bold text-gray-800 mb-1">Jorge Martínez</h3>
            <p class="text-sm text-[#002b64] font-semibold mb-3">Guía Turistico Senior</p>
            <div class="flex items-center gap-2 mb-3">
              <img src="https://flagcdn.com/w20/hn.png" class="w-5 h-auto" alt="Honduras" />
              <span class="text-sm text-gray-600">Honduras</span>
            </div>
            <div class="flex items-center gap-2 text-sm text-gray-600">
              <svg xmlns="http://www.w3.org/2000/svg" class="h-4 w-4" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="2">
                <path stroke-linecap="round" stroke-linejoin="round" d="M3 8l7.89 5.26a2 2 0 002.22 0L21 8M5 19h14a2 2 0 002-2V7a2 2 0 00-2-2H5a2 2 0 00-2 2v10a2 2 0 002 2z" />
              </svg>
              <a href="mailto:jorge@nativa.com" class="hover:text-[#002b64] transition-colors">jorge@nativa.com</a>
            </div>
          </div>
        </div>

        <!-- Team Member 4 -->
        <div
          data-aos="fade-up"
          data-aos-delay="300"
          class="group bg-white rounded-2xl shadow-lg hover:shadow-2xl transition-all duration-300 overflow-hidden"
        >
          <div class="relative h-64 overflow-hidden">
            <img
              src="https://images.unsplash.com/photo-1580489944761-15a19d654956?q=80&w=800"
              class="w-full h-full object-cover group-hover:scale-110 transition-transform duration-500"
              alt="Team member"
            />
            <div class="absolute inset-0 bg-gradient-to-t from-[#002b64]/80 to-transparent opacity-0 group-hover:opacity-100 transition-opacity duration-300"></div>
          </div>
          <div class="p-6">
            <h3 class="text-xl font-bold text-gray-800 mb-1">Ana Gómez</h3>
            <p class="text-sm text-[#002b64] font-semibold mb-3">Atención al Cliente</p>
            <div class="flex items-center gap-2 mb-3">
              <img src="https://flagcdn.com/w20/co.png" class="w-5 h-auto" alt="Colombia" />
              <span class="text-sm text-gray-600">Colombia</span>
            </div>
            <div class="flex items-center gap-2 text-sm text-gray-600">
              <svg xmlns="http://www.w3.org/2000/svg" class="h-4 w-4" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="2">
                <path stroke-linecap="round" stroke-linejoin="round" d="M3 8l7.89 5.26a2 2 0 002.22 0L21 8M5 19h14a2 2 0 002-2V7a2 2 0 00-2-2H5a2 2 0 00-2 2v10a2 2 0 002 2z" />
              </svg>
              <a href="mailto:ana@nativa.com" class="hover:text-[#002b64] transition-colors">ana@nativa.com</a>
            </div>
          </div>
        </div>
      </div>
    </section>

    <!-- Testimonials section -->
    <section class="w-full my-36 px-4">
      <div class="max-w-screen-xl mx-auto">
        <div class="text-center mb-16">
          <h2
            data-aos="fade-up"
            class="text-4xl sm:text-5xl font-bold mb-4 text-gray-800"
          >
            Lo Que Dicen <span class="text-header-gradient">Nuestros Viajeros</span>
          </h2>
          <p data-aos="fade-up" data-aos-delay="100" class="text-lg text-gray-600 max-w-2xl mx-auto">
            Experiencias reales de personas que confiaron en nosotros para vivir aventuras inolvidables
          </p>
        </div>

        <div class="space-y-8">
          <!-- Testimonial 1 - Horizontal Large Card -->
          <div
            data-aos="fade-right"
            data-aos-delay="0"
            class="group relative overflow-hidden rounded-3xl shadow-2xl hover:shadow-3xl transition-all duration-500"
          >
            <div class="grid md:grid-cols-2 min-h-[400px]">
              <!-- Image Side -->
              <div class="relative h-80 md:h-auto overflow-hidden">
                <img
                  src="https://images.unsplash.com/photo-1568632234157-ce7aecd03d0d?q=80&w=1200"
                  class="w-full h-full object-cover group-hover:scale-110 transition-transform duration-700"
                  alt="Cartagena, Colombia"
                />
                <div class="absolute inset-0 bg-gradient-to-r from-[#002b64]/95 via-[#002b64]/40 to-transparent"></div>
              </div>
              <!-- Content Side -->
              <div class="relative bg-gradient-to-br from-white to-gray-50 p-8 lg:p-12 flex flex-col justify-center">
                <div class="absolute top-6 right-6">
                  <svg class="w-16 h-16 text-[#002b64]/10" fill="currentColor" viewBox="0 0 24 24">
                    <path d="M14.017 21v-7.391c0-5.704 3.731-9.57 8.983-10.609l.995 2.151c-2.432.917-3.995 3.638-3.995 5.849h4v10h-9.983zm-14.017 0v-7.391c0-5.704 3.748-9.57 9-10.609l.996 2.151c-2.433.917-3.996 3.638-3.996 5.849h3.983v10h-9.983z"/>
                  </svg>
                </div>
                <div class="flex items-center mb-6">
                  <div class="flex text-yellow-400">
                    <svg class="w-6 h-6" fill="currentColor" viewBox="0 0 20 20"><path d="M9.049 2.927c.3-.921 1.603-.921 1.902 0l1.07 3.292a1 1 0 00.95.69h3.462c.969 0 1.371 1.24.588 1.81l-2.8 2.034a1 1 0 00-.364 1.118l1.07 3.292c.3.921-.755 1.688-1.54 1.118l-2.8-2.034a1 1 0 00-1.175 0l-2.8 2.034c-.784.57-1.838-.197-1.539-1.118l1.07-3.292a1 1 0 00-.364-1.118L2.98 8.72c-.783-.57-.38-1.81.588-1.81h3.461a1 1 0 00.951-.69l1.07-3.292z"></path></svg>
                    <svg class="w-6 h-6" fill="currentColor" viewBox="0 0 20 20"><path d="M9.049 2.927c.3-.921 1.603-.921 1.902 0l1.07 3.292a1 1 0 00.95.69h3.462c.969 0 1.371 1.24.588 1.81l-2.8 2.034a1 1 0 00-.364 1.118l1.07 3.292c.3.921-.755 1.688-1.54 1.118l-2.8-2.034a1 1 0 00-1.175 0l-2.8 2.034c-.784.57-1.838-.197-1.539-1.118l1.07-3.292a1 1 0 00-.364-1.118L2.98 8.72c-.783-.57-.38-1.81.588-1.81h3.461a1 1 0 00.951-.69l1.07-3.292z"></path></svg>
                    <svg class="w-6 h-6" fill="currentColor" viewBox="0 0 20 20"><path d="M9.049 2.927c.3-.921 1.603-.921 1.902 0l1.07 3.292a1 1 0 00.95.69h3.462c.969 0 1.371 1.24.588 1.81l-2.8 2.034a1 1 0 00-.364 1.118l1.07 3.292c.3.921-.755 1.688-1.54 1.118l-2.8-2.034a1 1 0 00-1.175 0l-2.8 2.034c-.784.57-1.838-.197-1.539-1.118l1.07-3.292a1 1 0 00-.364-1.118L2.98 8.72c-.783-.57-.38-1.81.588-1.81h3.461a1 1 0 00.951-.69l1.07-3.292z"></path></svg>
                    <svg class="w-6 h-6" fill="currentColor" viewBox="0 0 20 20"><path d="M9.049 2.927c.3-.921 1.603-.921 1.902 0l1.07 3.292a1 1 0 00.95.69h3.462c.969 0 1.371 1.24.588 1.81l-2.8 2.034a1 1 0 00-.364 1.118l1.07 3.292c.3.921-.755 1.688-1.54 1.118l-2.8-2.034a1 1 0 00-1.175 0l-2.8 2.034c-.784.57-1.838-.197-1.539-1.118l1.07-3.292a1 1 0 00-.364-1.118L2.98 8.72c-.783-.57-.38-1.81.588-1.81h3.461a1 1 0 00.951-.69l1.07-3.292z"></path></svg>
                    <svg class="w-6 h-6" fill="currentColor" viewBox="0 0 20 20"><path d="M9.049 2.927c.3-.921 1.603-.921 1.902 0l1.07 3.292a1 1 0 00.95.69h3.462c.969 0 1.371 1.24.588 1.81l-2.8 2.034a1 1 0 00-.364 1.118l1.07 3.292c.3.921-.755 1.688-1.54 1.118l-2.8-2.034a1 1 0 00-1.175 0l-2.8 2.034c-.784.57-1.838-.197-1.539-1.118l1.07-3.292a1 1 0 00-.364-1.118L2.98 8.72c-.783-.57-.38-1.81.588-1.81h3.461a1 1 0 00.951-.69l1.07-3.292z"></path></svg>
                  </div>
                </div>
                <p class="text-lg md:text-xl italic text-gray-700 mb-8 leading-relaxed relative z-10">
                  "La experiencia en Cartagena fue absolutamente mágica. El guía conocía cada rincón histórico de la ciudad amurallada y nos hizo sentir como en casa. Las puestas de sol desde las murallas son inolvidables. Definitivamente volveré con Nativa."
                </p>
                <div class="flex items-center gap-4 mt-auto">
                  <div class="w-16 h-16 rounded-full overflow-hidden border-3 border-[#002b64] shadow-lg">
                    <img src="https://i.pravatar.cc/150?img=1" class="w-full h-full object-cover" alt="Sofia" />
                  </div>
                  <div>
                    <h4 class="font-bold text-lg text-gray-800">Sofía Martínez</h4>
                    <p class="text-sm text-[#002b64] font-semibold">Cartagena, Colombia</p>
                  </div>
                </div>
              </div>
            </div>
          </div>

          <!-- Testimonial 2 - Horizontal Large Card (Reversed) -->
          <div
            data-aos="fade-left"
            data-aos-delay="100"
            class="group relative overflow-hidden rounded-3xl shadow-2xl hover:shadow-3xl transition-all duration-500"
          >
            <div class="grid md:grid-cols-2 min-h-[400px]">
              <!-- Content Side -->
              <div class="relative bg-gradient-to-br from-white to-gray-50 p-8 lg:p-12 flex flex-col justify-center order-2 md:order-1">
                <div class="absolute top-6 left-6">
                  <svg class="w-16 h-16 text-[#002b64]/10" fill="currentColor" viewBox="0 0 24 24">
                    <path d="M14.017 21v-7.391c0-5.704 3.731-9.57 8.983-10.609l.995 2.151c-2.432.917-3.995 3.638-3.995 5.849h4v10h-9.983zm-14.017 0v-7.391c0-5.704 3.748-9.57 9-10.609l.996 2.151c-2.433.917-3.996 3.638-3.996 5.849h3.983v10h-9.983z"/>
                  </svg>
                </div>
                <div class="flex items-center mb-6">
                  <div class="flex text-yellow-400">
                    <svg class="w-6 h-6" fill="currentColor" viewBox="0 0 20 20"><path d="M9.049 2.927c.3-.921 1.603-.921 1.902 0l1.07 3.292a1 1 0 00.95.69h3.462c.969 0 1.371 1.24.588 1.81l-2.8 2.034a1 1 0 00-.364 1.118l1.07 3.292c.3.921-.755 1.688-1.54 1.118l-2.8-2.034a1 1 0 00-1.175 0l-2.8 2.034c-.784.57-1.838-.197-1.539-1.118l1.07-3.292a1 1 0 00-.364-1.118L2.98 8.72c-.783-.57-.38-1.81.588-1.81h3.461a1 1 0 00.951-.69l1.07-3.292z"></path></svg>
                    <svg class="w-6 h-6" fill="currentColor" viewBox="0 0 20 20"><path d="M9.049 2.927c.3-.921 1.603-.921 1.902 0l1.07 3.292a1 1 0 00.95.69h3.462c.969 0 1.371 1.24.588 1.81l-2.8 2.034a1 1 0 00-.364 1.118l1.07 3.292c.3.921-.755 1.688-1.54 1.118l-2.8-2.034a1 1 0 00-1.175 0l-2.8 2.034c-.784.57-1.838-.197-1.539-1.118l1.07-3.292a1 1 0 00-.364-1.118L2.98 8.72c-.783-.57-.38-1.81.588-1.81h3.461a1 1 0 00.951-.69l1.07-3.292z"></path></svg>
                    <svg class="w-6 h-6" fill="currentColor" viewBox="0 0 20 20"><path d="M9.049 2.927c.3-.921 1.603-.921 1.902 0l1.07 3.292a1 1 0 00.95.69h3.462c.969 0 1.371 1.24.588 1.81l-2.8 2.034a1 1 0 00-.364 1.118l1.07 3.292c.3.921-.755 1.688-1.54 1.118l-2.8-2.034a1 1 0 00-1.175 0l-2.8 2.034c-.784.57-1.838-.197-1.539-1.118l1.07-3.292a1 1 0 00-.364-1.118L2.98 8.72c-.783-.57-.38-1.81.588-1.81h3.461a1 1 0 00.951-.69l1.07-3.292z"></path></svg>
                    <svg class="w-6 h-6" fill="currentColor" viewBox="0 0 20 20"><path d="M9.049 2.927c.3-.921 1.603-.921 1.902 0l1.07 3.292a1 1 0 00.95.69h3.462c.969 0 1.371 1.24.588 1.81l-2.8 2.034a1 1 0 00-.364 1.118l1.07 3.292c.3.921-.755 1.688-1.54 1.118l-2.8-2.034a1 1 0 00-1.175 0l-2.8 2.034c-.784.57-1.838-.197-1.539-1.118l1.07-3.292a1 1 0 00-.364-1.118L2.98 8.72c-.783-.57-.38-1.81.588-1.81h3.461a1 1 0 00.951-.69l1.07-3.292z"></path></svg>
                    <svg class="w-6 h-6" fill="currentColor" viewBox="0 0 20 20"><path d="M9.049 2.927c.3-.921 1.603-.921 1.902 0l1.07 3.292a1 1 0 00.95.69h3.462c.969 0 1.371 1.24.588 1.81l-2.8 2.034a1 1 0 00-.364 1.118l1.07 3.292c.3.921-.755 1.688-1.54 1.118l-2.8-2.034a1 1 0 00-1.175 0l-2.8 2.034c-.784.57-1.838-.197-1.539-1.118l1.07-3.292a1 1 0 00-.364-1.118L2.98 8.72c-.783-.57-.38-1.81.588-1.81h3.461a1 1 0 00.951-.69l1.07-3.292z"></path></svg>
                  </div>
                </div>
                <p class="text-lg md:text-xl italic text-gray-700 mb-8 leading-relaxed relative z-10">
                  "Machu Picchu siempre fue un sueño para mí. Gracias a Nativa todo fue perfecto: el transporte, el hospedaje de lujo y especialmente nuestro guía Jorge que compartió la historia ancestral de los incas. ¡Una experiencia que cambió mi vida!"
                </p>
                <div class="flex items-center gap-4 mt-auto">
                  <div class="w-16 h-16 rounded-full overflow-hidden border-3 border-[#002b64] shadow-lg">
                    <img src="https://i.pravatar.cc/150?img=33" class="w-full h-full object-cover" alt="Roberto" />
                  </div>
                  <div>
                    <h4 class="font-bold text-lg text-gray-800">Roberto Silva</h4>
                    <p class="text-sm text-[#002b64] font-semibold">Machu Picchu, Perú</p>
                  </div>
                </div>
              </div>
              <!-- Image Side -->
              <div class="relative h-80 md:h-auto overflow-hidden order-1 md:order-2">
                <img
                  src="https://images.unsplash.com/photo-1526392060635-9d6019884377?q=80&w=1200"
                  class="w-full h-full object-cover group-hover:scale-110 transition-transform duration-700"
                  alt="Machu Picchu, Peru"
                />
                <div class="absolute inset-0 bg-gradient-to-l from-[#002b64]/95 via-[#002b64]/40 to-transparent"></div>
              </div>
            </div>
          </div>

          <!-- Testimonial 3 - Horizontal Large Card -->
          <div
            data-aos="fade-right"
            data-aos-delay="200"
            class="group relative overflow-hidden rounded-3xl shadow-2xl hover:shadow-3xl transition-all duration-500"
          >
            <div class="grid md:grid-cols-2 min-h-[400px]">
              <!-- Image Side -->
              <div class="relative h-80 md:h-auto overflow-hidden">
                <img
                  src="https://images.unsplash.com/photo-1544551763-46a013bb70d5?q=80&w=1200"
                  class="w-full h-full object-cover group-hover:scale-110 transition-transform duration-700"
                  alt="Roatan, Honduras"
                />
                <div class="absolute inset-0 bg-gradient-to-r from-[#002b64]/95 via-[#002b64]/40 to-transparent"></div>
              </div>
              <!-- Content Side -->
              <div class="relative bg-gradient-to-br from-white to-gray-50 p-8 lg:p-12 flex flex-col justify-center">
                <div class="absolute top-6 right-6">
                  <svg class="w-16 h-16 text-[#002b64]/10" fill="currentColor" viewBox="0 0 24 24">
                    <path d="M14.017 21v-7.391c0-5.704 3.731-9.57 8.983-10.609l.995 2.151c-2.432.917-3.995 3.638-3.995 5.849h4v10h-9.983zm-14.017 0v-7.391c0-5.704 3.748-9.57 9-10.609l.996 2.151c-2.433.917-3.996 3.638-3.996 5.849h3.983v10h-9.983z"/>
                  </svg>
                </div>
                <div class="flex items-center mb-6">
                  <div class="flex text-yellow-400">
                    <svg class="w-6 h-6" fill="currentColor" viewBox="0 0 20 20"><path d="M9.049 2.927c.3-.921 1.603-.921 1.902 0l1.07 3.292a1 1 0 00.95.69h3.462c.969 0 1.371 1.24.588 1.81l-2.8 2.034a1 1 0 00-.364 1.118l1.07 3.292c.3.921-.755 1.688-1.54 1.118l-2.8-2.034a1 1 0 00-1.175 0l-2.8 2.034c-.784.57-1.838-.197-1.539-1.118l1.07-3.292a1 1 0 00-.364-1.118L2.98 8.72c-.783-.57-.38-1.81.588-1.81h3.461a1 1 0 00.951-.69l1.07-3.292z"></path></svg>
                    <svg class="w-6 h-6" fill="currentColor" viewBox="0 0 20 20"><path d="M9.049 2.927c.3-.921 1.603-.921 1.902 0l1.07 3.292a1 1 0 00.95.69h3.462c.969 0 1.371 1.24.588 1.81l-2.8 2.034a1 1 0 00-.364 1.118l1.07 3.292c.3.921-.755 1.688-1.54 1.118l-2.8-2.034a1 1 0 00-1.175 0l-2.8 2.034c-.784.57-1.838-.197-1.539-1.118l1.07-3.292a1 1 0 00-.364-1.118L2.98 8.72c-.783-.57-.38-1.81.588-1.81h3.461a1 1 0 00.951-.69l1.07-3.292z"></path></svg>
                    <svg class="w-6 h-6" fill="currentColor" viewBox="0 0 20 20"><path d="M9.049 2.927c.3-.921 1.603-.921 1.902 0l1.07 3.292a1 1 0 00.95.69h3.462c.969 0 1.371 1.24.588 1.81l-2.8 2.034a1 1 0 00-.364 1.118l1.07 3.292c.3.921-.755 1.688-1.54 1.118l-2.8-2.034a1 1 0 00-1.175 0l-2.8 2.034c-.784.57-1.838-.197-1.539-1.118l1.07-3.292a1 1 0 00-.364-1.118L2.98 8.72c-.783-.57-.38-1.81.588-1.81h3.461a1 1 0 00.951-.69l1.07-3.292z"></path></svg>
                    <svg class="w-6 h-6" fill="currentColor" viewBox="0 0 20 20"><path d="M9.049 2.927c.3-.921 1.603-.921 1.902 0l1.07 3.292a1 1 0 00.95.69h3.462c.969 0 1.371 1.24.588 1.81l-2.8 2.034a1 1 0 00-.364 1.118l1.07 3.292c.3.921-.755 1.688-1.54 1.118l-2.8-2.034a1 1 0 00-1.175 0l-2.8 2.034c-.784.57-1.838-.197-1.539-1.118l1.07-3.292a1 1 0 00-.364-1.118L2.98 8.72c-.783-.57-.38-1.81.588-1.81h3.461a1 1 0 00.951-.69l1.07-3.292z"></path></svg>
                    <svg class="w-6 h-6" fill="currentColor" viewBox="0 0 20 20"><path d="M9.049 2.927c.3-.921 1.603-.921 1.902 0l1.07 3.292a1 1 0 00.95.69h3.462c.969 0 1.371 1.24.588 1.81l-2.8 2.034a1 1 0 00-.364 1.118l1.07 3.292c.3.921-.755 1.688-1.54 1.118l-2.8-2.034a1 1 0 00-1.175 0l-2.8 2.034c-.784.57-1.838-.197-1.539-1.118l1.07-3.292a1 1 0 00-.364-1.118L2.98 8.72c-.783-.57-.38-1.81.588-1.81h3.461a1 1 0 00.951-.69l1.07-3.292z"></path></svg>
                  </div>
                </div>
                <p class="text-lg md:text-xl italic text-gray-700 mb-8 leading-relaxed relative z-10">
                  "Roatán es un paraíso caribeño y con Nativa descubrí lugares secretos que jamás hubiera encontrado sola. El arrecife de coral, las playas vírgenes... El servicio de fotografía capturó momentos que atesoraré por siempre."
                </p>
                <div class="flex items-center gap-4 mt-auto">
                  <div class="w-16 h-16 rounded-full overflow-hidden border-3 border-[#002b64] shadow-lg">
                    <img src="https://i.pravatar.cc/150?img=5" class="w-full h-full object-cover" alt="Laura" />
                  </div>
                  <div>
                    <h4 class="font-bold text-lg text-gray-800">Laura Gómez</h4>
                    <p class="text-sm text-[#002b64] font-semibold">Roatán, Honduras</p>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>

        <!-- CTA Button -->
        <div class="text-center mt-12" data-aos="fade-up" data-aos-delay="300">
          <a
            href="#"
            class="inline-flex items-center gap-2 px-8 py-4 bg-gradient-to-r from-[#002b64] to-[#0e65e8] text-white font-semibold rounded-full shadow-lg hover:shadow-xl hover:scale-105 transition-all duration-300"
          >
            <span>Vive Tu Propia Aventura</span>
            <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="2">
              <path stroke-linecap="round" stroke-linejoin="round" d="M17 8l4 4m0 0l-4 4m4-4H3" />
            </svg>
          </a>
        </div>
      </div>
    </section>

    <!-- Advanced trading tools section -->
    <section class="bg-trading-tools relative max-w-full sm:mx-4 my-20 py-16 shadow rounded-2xl overflow-hidden">
      <div class="relative max-w-screen-xl px-4 sm:px-2 mx-auto grid grid-cols-12 gap-x-6">
        <LandingTradingToolImage class="sm:hidden" />
        <div data-aos="fade-right" class="col-span-12 lg:col-span-6 space-y-8 sm:space-y-6 px-4 sm:px-6 mt-8">
          <h2 class="text-4xl font-semibold">Advanced Trading <span class="text-header-gradient">Tools</span></h2>
          <div class="space-y-2">
            <h4 class="text-lg font-medium">Professional Access, Non-stop Availability</h4>
            <p class="paragraph text-sm xl:text-base">
              We provide premium access to crypto trading for both individuals and institutions through high liquidity,
              reliable order execution and constant uptime.
            </p>
          </div>
          <div class="space-y-2">
            <h4 class="text-lg font-medium">A Range of Powerful Apis</h4>
            <p class="paragraph text-sm xl:text-base">
              Set up your own trading interface or deploy your algorithmic strategy with our high-performance FIX and
              HTTP APIs. Connect to our WebSocket for real-time data streaming.
            </p>
          </div>
          <div class="space-y-2">
            <h4 class="text-lg font-medium">Customer Support</h4>
            <p class="paragraph text-sm xl:text-base">
              Premium 24/7 support available to all customers worldwide by phone or email. Dedicated account managers
              for partners.
            </p>
          </div>
          <div class="flex flex-col sm:flex-row">
            <BaseButton class="px-10 py-4 bg-inherit text-gradient border border-[#4A8FF6] text-base">
              Get Started
            </BaseButton>
            <BaseButton class="bg-inherit text-[#4A8FF6] px-10 py-4 text-center underline rounded-full">
              Learn More
            </BaseButton>
          </div>
        </div>
        <LandingTradingToolImage data-aos="fade-left" class="hidden sm:block" />
      </div>
    </section>

    <!-- Industry-leading security section -->
    <section class="w-full my-24">
      <div class="relative max-w-screen-xl px-8 mx-auto grid grid-cols-12 gap-x-6">
        <div data-aos="fade-right" class="col-span-12 lg:col-span-6">
          <div class="w-full">
            <img src="/img/industry-leading-security.webp" class="w-full" alt="" />
          </div>
        </div>
        <div data-aos="fade-left" class="col-span-12 lg:col-span-5 space-y-8 sm:space-y-6 mt-8 xl:px-8">
          <h2 class="text-4xl font-semibold">Industry-leading security from day one</h2>
          <ul class="space-y-8 sm:space-y-4">
            <LandingListItem title="Safety, security and compliance">
              <p class="text-sm text-gray-700 leading-relaxed">
                Nativa is a licensed New York trust company that undergoes regular bank exams and is subject to the
                cybersecurity audits conducted by the New York Department of Financial Services.
                <span class="underline">Learn more</span> about our commitment to security.
              </p>
            </LandingListItem>
            <LandingListItem title="Hardware security keys">
              <p class="text-sm text-gray-700 leading-relaxed">
                With Nativa you can secure your account with a hardware security key via WebAuthn.
              </p>
            </LandingListItem>
            <LandingListItem title="SOC Certifications">
              <p class="text-sm text-gray-700 leading-relaxed">
                Nativa is <span class="underline">SOC 1 Type 2</span> and
                <span class="underline">SOC 2 Type 2</span> compliant. We are the world’s first cryptocurrency exchange
                and custodian to complete these exams.
              </p>
            </LandingListItem>
          </ul>
        </div>
      </div>
    </section>

    <!-- Getting started section -->
    <section class="bg-trading-tools relative max-w-full sm:mx-4 xl:mx-10 my-24 shadow sm:rounded-2xl overflow-hidden">
      <div class="w-full py-16 flex flex-col items-center">
        <h2 data-aos="flip-down" class="text-3xl sm:text-4xl font-semibold text-center">
          Get started in just a few minutes
        </h2>
        <div
          data-aos="fade-up"
          class="relative w-full flex flex-col lg:flex-row items-center justify-between space-y-12 lg:space-y-0 px-4 xl:px-10 mt-16 sm:mt-8"
        >
          <LandingStep v-for="step in steps" :key="step.title" :step="step" />
          <img
            src="/img/getting-started/arrow.png"
            class="hidden lg:inline-block absolute top-32 left-64 xl:left-[22rem] w-24 xl:w-[9.5rem]"
            alt=""
          />
          <img
            src="/img/getting-started/arrow.png"
            class="hidden lg:inline-block absolute top-32 right-64 xl:right-[22rem] w-24 xl:w-[9.5rem]"
            alt=""
          />
        </div>
      </div>
    </section>

    <!-- FAQ section -->
    <section class="w-full my-24">
      <BaseSection>
        <div data-aos="fade-right" data-aos-delay="150" class="col-span-12 lg:col-span-6">
          <div class="w-full">
            <img src="/img/faq.webp" class="w-full" alt="" />
          </div>
        </div>
        <div data-aos="fade-left" data-aos-delay="150" class="col-span-12 lg:col-span-6 px-4 sm:px-6 mt-8">
          <span class="text-base text-gradient font-semibold uppercase mb-4 sm:mb-2">Support</span>
          <h2 class="text-3xl sm:text-4xl font-semibold mb-10 sm:mb-6">Frequently asked questions</h2>

          <ul class="shadow-box">
            <BaseAccordion v-for="(accordion, index) in accordions" :key="index" :accordion="accordion" />
          </ul>
        </div>
      </BaseSection>
    </section>

    <div class="w-full my-10 flex justify-center">
      <a
        @click.prevent="scrollToTop"
        data-aos="flip-down"
        data-aos-delay="150"
        href="#navbar"
        class="px-6 py-3 flex items-center space-x-2 bg-[#FAFAFA] hover:bg-gray-100 hover:shadow-md border border-[#DDDDDD] rounded-md text-gray-700 cursor-pointer"
      >
        <span>Back to top</span>
        <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><line x1="12" y1="19" x2="12" y2="5"></line><polyline points="5 12 12 5 19 12"></polyline></svg>
      </a>
    </div>
  </div>
</template>

<script>
import aosMixin from '@/mixins/aos'
export default {
  name: 'IndexPage',
  mixins: [aosMixin],
  methods: {
    scrollToTop() {
      window.scrollTo({ top: 0, behavior: 'smooth' })
    },
  },
  data() {
    return {
      selected: 0,
      dropdownConcurency: false,
      dropdownCrypto: false,
      currencySelected: {
        img: 'country-icon/eng.png',
        name: 'USD',
      },
      currencies: [
        {
          img: 'country-icon/eng.png',
          name: 'USD',
        },
      ],
      cryptoSelected: {
        img: 'crypto-icon/bitcoin.png',
        name: 'BTC',
      },
      cryptocurrencies: [
        {
          img: 'crypto-icon/bitcoin.png',
          name: 'BTC',
        },
      ],
      trendings: [
        {
          id: 1,
          name: 'Bitcoin',
          price: 43180.13,
          logo: 'bitcoin.png',
          increase: true,
          data: [40, 35, 60, 75, 60, 75, 50],
        },
        {
          id: 2,
          name: 'Ethereum',
          price: 3480.65,
          logo: 'ethereum.png',
          increase: false,
          data: [25, 30, 60, 50, 80, 55, 80],
        },
        {
          id: 3,
          name: 'Solana',
          price: 150.2,
          logo: 'solana.png',
          increase: true,
          data: [40, 45, 40, 80, 50, 60, 35],
        },
        {
          id: 4,
          name: 'Dogecoin',
          price: 0.1572,
          logo: 'dogecoin.png',
          increase: true,
          data: [35, 70, 60, 80, 50, 60, 40],
        },
      ],
      topGainers: [
        {
          id: 1,
          name: 'PAPPAY',
          price: 0.00374,
          logo: 'pappay.png',
          increase: true,
          data: [30, 50, 45, 60, 70, 40, 45],
        },
        {
          id: 2,
          name: 'Bitcoin Asia',
          price: 0.02096,
          logo: 'bitcoin-asia.png',
          increase: true,
          data: [25, 60, 50, 60, 35, 50, 70],
        },
        {
          id: 3,
          name: 'MoonRock',
          price: 0.004907,
          logo: 'moonrock.png',
          increase: true,
          data: [40, 35, 40, 25, 50, 70, 45],
        },
        {
          id: 4,
          name: 'NinjaFloki',
          price: 0.000123,
          logo: 'ninjafloki.png',
          increase: true,
          data: [45, 35, 40, 30, 25, 45, 35],
        },
      ],
      recents: [
        {
          id: 1,
          name: 'MetaCraft',
          price: 0.0608,
          logo: 'metacraft.png',
          increase: false,
          data: [40, 50, 45, 60, 35, 40, 45],
        },
        {
          id: 2,
          name: 'Frog',
          price: 0.5875,
          logo: 'frog.png',
          increase: false,
          data: [25, 50, 45, 48, 40, 60, 45],
        },
        {
          id: 3,
          name: 'Musk Doge',
          price: 0.04041,
          logo: 'musk-doge.png',
          increase: true,
          data: [25, 35, 60, 45, 50, 45, 45],
        },
        {
          id: 4,
          name: '2SHARE',
          price: 1366.24,
          logo: '2share.png',
          increase: true,
          data: [35, 30, 60, 50, 35, 45, 40],
        },
      ],
      accordions: [
        {
          title: 'Why should I choose NATIVA?',
          description:
            "We're industry pioneers, having been in the cryptocurrency industry since 2016. We've facilitated more than 21 billion USD worth of transactions on our exchange for customers in over 40 countries. Today, we're trusted by over 8 million customers around the world and have received praise for our easy-to-use app, secure wallet, and range of features.",
        },
        {
          title: 'How secure is NATIVA?',
          description:
            "We're industry pioneers, having been in the cryptocurrency industry since 2016. We've facilitated more than 21 billion USD worth of transactions on our exchange for customers in over 40 countries. Today, we're trusted by over million customers around the world and have received praise for our easy-to-use app, secure wallet, and range of features.",
        },
        {
          title: 'Do I have to buy a whole Bitcoin?',
          description:
            "We're industry pioneers, having been in the cryptocurrency industry since 2016. We've facilitated more than 21 billion USD worth of transactions on our exchange for customers in over 40 countries. Today, we're trusted by over million customers around the world and have received praise for our easy-to-use app, secure wallet, and range of features.",
        },
        {
          title: 'How do I actually buy Bitcoin?',
          description:
            "We're industry pioneers, having been in the cryptocurrency industry since 2016. We've facilitated more than 21 billion USD worth of transactions on our exchange for customers in over 40 countries. Today, we're trusted by over million customers around the world and have received praise for our easy-to-use app, secure wallet, and range of features.",
        },
      ],
      steps: [
        {
          img: 'sign-up.png',
          title: 'Sign Up',
          description:
            'Sign up for your free NATIVA Wallet on web, iOS or Android and follow our easy process to set up your profile',
        },
        {
          img: 'fund.png',
          title: 'Fund',
          description:
            'Choose your preferred payment method such as bank transfer or credit card to top up your NATIVA Wallet',
        },
        {
          img: 'buy-crypto.png',
          title: 'Buy Crypto',
          description:
            'Buy Bitcoin or Ethereum, then securely store it in your Wallet or send it on easily to your friends anywhere',
        },
      ],
    }
  },
}
</script>
<style scoped>
.text-header-gradient {
  background: rgb(57, 132, 244);
  background: linear-gradient(169.4deg, #3984f4 -6.01%, #0cd3ff 36.87%, #2f7cf0 78.04%, #0e65e8 103.77%);
  background-clip: text;
  -webkit-text-fill-color: transparent;
}
.text-destinations-gradient {
  background: linear-gradient(135deg, #3984f4 0%, #0cd3ff 30%, #2f7cf0 60%, #0e65e8 100%);
  background-size: 200% auto;
  background-clip: text;
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  animation: gradient-shift 4s ease infinite;
}
@keyframes gradient-shift {
  0%, 100% {
    background-position: 0% 50%;
  }
  50% {
    background-position: 100% 50%;
  }
}
.bg-hero-beach {
  background: url('https://images.unsplash.com/photo-1507525428034-b723cf961d3e?q=80&w=2000');
  background-size: cover;
  background-position: center;
}
.bg-colombia {
  background: url('https://images.unsplash.com/photo-1568632234157-ce7aecd03d0d?q=80&w=2000');
  background-size: cover;
  background-position: center;
}
.bg-peru {
  background: url('https://images.unsplash.com/photo-1587595431973-160d0d94add1?q=80&w=2000');
  background-size: cover;
  background-position: center;
}
.bg-honduras {
  background: url('https://images.unsplash.com/photo-1559827260-dc66d52bef19?q=80&w=2000');
  background-size: cover;
  background-position: center;
}
.destination-card:hover .destination-image {
  transform: scale(1.05);
  transition: transform 0.3s ease-in-out;
}
.service-card-container {
  perspective: 1000px;
  cursor: pointer;
}
.service-card-flip {
  position: relative;
  width: 100%;
  height: 100%;
  transition: transform 0.6s;
  transform-style: preserve-3d;
}
.service-card-container:hover .service-card-flip {
  transform: rotateY(180deg);
}
.service-card-front,
.service-card-back {
  position: absolute;
  width: 100%;
  height: 100%;
  backface-visibility: hidden;
  -webkit-backface-visibility: hidden;
}
.service-card-back {
  transform: rotateY(180deg);
}
.bg-partner {
  background: url('../assets/img/partner/background.png');
  background-size: cover;
  background-position: center;
}
.bg-trading-tools {
  background: url('../assets/img/bg-trading-tools.webp');
  background-size: cover;
  background-position: center;
}
.max-h-0 {
  max-height: 0;
}
</style>
