<template>
  <!-- component -->
  <section id="tech" class='flex min-h-screen items-center justify-center px-[5rem]'>
    <div class="container mx-auto">
        <div class="relative flex items-center pl-4 -ml-4 animate-left-title group scroll-mt-40">
        <h2 class="text-5xl font-bold leading-snug !mb-2  text-cyan-400">{{ $t('tech.title') }}</h2>
        </div>
        <p class="animate-slideUp-subtitle block antialiased font-sans text-base font-light leading-relaxed text-inherit !mb-4  !text-white">{{ $t('tech.subtitle') }}</p>
        <div class="grid grid-cols-2 gap-6 mt-8 md:grid-cols-4" id="frameworks-integration">
          <!-- html -->
        <span class="group grid animate-tech backdrop-blur-sm transition duration-700 w-full min-w-[7rem] transform place-items-center rounded-xl border border-blue-gray-50 bg-cyan-800 shadow-lg sm:rounded-3xl sm:hover:border-cyan-400 bg-clip-padding bg-opacity-55 sm:hover:shadow-cyan-400 px-3 py-2 hover:scale-105 sm:border-cyan-50 border-cyan-400 hover:bsm:g-opacity-25">
            <span class="grid w-24 h-24 my-6 place-items-center">
         <svg width="90" height="90" viewBox="0 0 32 32" fill="none" class="transition-all duration-300 group-hover:brightness-100 group-hover:contrast-200 grayscale group-hover:grayscale-0" xmlns="http://www.w3.org/2000/svg">
            <path d="M6 28L4 3H28L26 28L16 31L6 28Z" fill="#E44D26"/>
            <path d="M26 5H16V29.5L24 27L26 5Z" fill="#F16529"/>
            <path d="M9.5 17.5L8.5 8H24L23.5 11H11.5L12 14.5H23L22 24L16 26L10 24L9.5 19H12.5L13 21.5L16 22.5L19 21.5L19.5 17.5H9.5Z" fill="white"/>
            </svg>
            </span>
        </span>
        <!-- css -->
         <span class="group grid animate-tech backdrop-blur-sm transition duration-700 w-full min-w-[7rem] transform place-items-center rounded-xl border border-blue-gray-50 bg-cyan-800 shadow-lg sm:rounded-3xl sm:hover:border-cyan-400 bg-clip-padding bg-opacity-55 sm:hover:shadow-cyan-400 px-3 py-2 hover:scale-105 sm:border-cyan-50 border-cyan-400 hover:bsm:g-opacity-25">
            <span class="grid w-24 h-24 my-6 place-items-center">
            <svg width="90" height="90" viewBox="0 0 32 32" class="transition-all duration-300 group-hover:brightness-100 group-hover:contrast-200 grayscale group-hover:grayscale-0" fill="none" xmlns="http://www.w3.org/2000/svg">
              <path d="M6 28L4 3H28L26 28L16 31L6 28Z" fill="#1172B8"/>
              <path d="M26 5H16V29.5L24 27L26 5Z" fill="#33AADD"/>
              <path d="M19.5 17.5H9.5L9 14L17 11.5H9L8.5 8.5H24L23.5 12L17 14.5H23L22 24L16 26L10 24L9.5 19H12.5L13 21.5L16 22.5L19 21.5L19.5 17.5Z" fill="white"/>
              </svg>
            </span>
        </span>
        <!-- javascript -->
         <span class="group grid animate-tech backdrop-blur-sm transition duration-700 w-full min-w-[7rem] transform place-items-center rounded-xl border border-blue-gray-50 bg-cyan-800 shadow-lg sm:rounded-3xl sm:hover:border-cyan-400 bg-clip-padding bg-opacity-55 sm:hover:shadow-cyan-400 px-3 py-2 hover:scale-105 sm:border-cyan-50 border-cyan-400 hover:bsm:g-opacity-25">
            <span class="grid w-24 h-24 my-6 place-items-center">
           <svg width="90" height="90" viewBox="0 0 256 256" version="1.1" class="transition-all duration-300 group-hover:brightness-100 group-hover:contrast-200 grayscale group-hover:grayscale-0" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" preserveAspectRatio="xMidYMid">
            <g>
        <path d="M0,0 L256,0 L256,256 L0,256 L0,0 Z" fill="#F7DF1E">
        </path>
        <path d="M67.311746,213.932292 L86.902654,202.076241 C90.6821079,208.777346 94.1202286,214.447137 102.367086,214.447137 C110.272203,214.447137 115.256076,211.354819 115.256076,199.326883 L115.256076,117.528787 L139.313575,117.528787 L139.313575,199.666997 C139.313575,224.58433 124.707759,235.925943 103.3984,235.925943 C84.1532952,235.925943 72.9819429,225.958603 67.3113397,213.93026" fill="#000000">
     </path>
        <path d="M152.380952,211.354413 L171.969422,200.0128 C177.125994,208.433981 183.827911,214.619835 195.684368,214.619835 C205.652521,214.619835 212.009041,209.635962 212.009041,202.762159 C212.009041,194.513676 205.479416,191.592025 194.481168,186.78207 L188.468419,184.202565 C171.111213,176.81473 159.597308,167.53534 159.597308,147.944838 C159.597308,129.901308 173.344508,116.153295 194.825752,116.153295 C210.119924,116.153295 221.117765,121.48094 229.021663,135.400432 L210.29059,147.428775 C206.166146,140.040127 201.699556,137.119289 194.826159,137.119289 C187.78047,137.119289 183.312254,141.587098 183.312254,147.428775 C183.312254,154.646349 187.78047,157.568406 198.089956,162.036622 L204.103924,164.614095 C224.553448,173.378641 236.067352,182.313448 236.067352,202.418387 C236.067352,224.071924 219.055137,235.927975 196.200432,235.927975 C173.860978,235.927975 159.425829,225.274311 152.381359,211.354413" fill="#000000">
        </path>
        </g>
        </svg>
            </span>
        </span>
        <!-- Tailwind -->
        <span class="group grid animate-tech backdrop-blur-sm transition duration-700 w-full min-w-[7rem] transform place-items-center rounded-xl border border-blue-gray-50 bg-cyan-800 shadow-lg sm:rounded-3xl sm:hover:border-cyan-400 bg-clip-padding bg-opacity-55 sm:hover:shadow-cyan-400 px-3 py-2 hover:scale-105 sm:border-cyan-50 border-cyan-400 hover:bsm:g-opacity-25">
            <span class="grid w-24 h-24 my-6 place-items-center">
              <svg width="90" height="90" class="transition-all duration-300 group-hover:brightness-100 group-hover:contrast-200 grayscale group-hover:grayscale-0" viewBox="0 0 32 32" xmlns="http://www.w3.org/2000/svg">
              <path
                d="M9,13.7q1.4-5.6,7-5.6c5.6,0,6.3,4.2,9.1,4.9q2.8.7,4.9-2.1-1.4,5.6-7,5.6c-5.6,0-6.3-4.2-9.1-4.9Q11.1,10.9,9,13.7ZM2,22.1q1.4-5.6,7-5.6c5.6,0,6.3,4.2,9.1,4.9q2.8.7,4.9-2.1-1.4,5.6-7,5.6c-5.6,0-6.3-4.2-9.1-4.9Q4.1,19.3,2,22.1Z"
                style="fill:#44a8b3" />
            </svg>
            </span>
        </span>
        <!-- boostrap -->
                <span class="group grid animate-tech backdrop-blur-sm transition duration-700 w-full min-w-[7rem] transform place-items-center rounded-xl border border-blue-gray-50 bg-cyan-800 shadow-lg sm:rounded-3xl sm:hover:border-cyan-400 bg-clip-padding bg-opacity-55 sm:hover:shadow-cyan-400 px-3 py-2 hover:scale-105 sm:border-cyan-50 border-cyan-400 hover:bsm:g-opacity-25">
            <span class="grid w-24 h-24 my-6 place-items-center">
          <svg width="90" height="90" class="transition-all duration-300 group-hover:brightness-100 group-hover:contrast-200 grayscale group-hover:grayscale-0" viewBox="0 0 256 256" version="1.1"
          xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink"
          preserveAspectRatio="xMidYMid">
          <g>
        <path
            d="M0,222.991225 C0,241.223474 14.7785318,256 33.0087747,256 L222.991225,256 C241.223474,256 256,241.221468 256,222.991225 L256,33.0087747 C256,14.7765263 241.221468,0 222.991225,0 L33.0087747,0 C14.7765263,0 0,14.7785318 0,33.0087747 L0,222.991225 Z"
            fill="#563D7C">

        </path>
        <path
            d="M106.157563,113.238095 L106.157563,76.9845938 L138.069328,76.9845938 C141.108559,76.9845938 144.039202,77.2378593 146.861345,77.7443978 C149.683488,78.2509362 152.179961,79.1554557 154.35084,80.4579832 C156.52172,81.7605107 158.258397,83.5695496 159.560924,85.8851541 C160.863452,88.2007585 161.514706,91.1675823 161.514706,94.7857143 C161.514706,101.298352 159.560944,106.001853 155.653361,108.896359 C151.745779,111.790864 146.752832,113.238095 140.67437,113.238095 L106.157563,113.238095 L106.157563,113.238095 Z M72.07493,50.5 L72.07493,205.5 L147.186975,205.5 C154.133788,205.5 160.899594,204.631661 167.484594,202.894958 C174.069594,201.158255 179.93088,198.480877 185.068627,194.862745 C190.206375,191.244613 194.294803,186.577293 197.334034,180.860644 C200.373264,175.143996 201.892857,168.37819 201.892857,160.563025 C201.892857,150.866431 199.541107,142.581033 194.837535,135.706583 C190.133963,128.832132 183.00635,124.020088 173.454482,121.270308 C180.401295,117.941627 185.647508,113.672295 189.193277,108.462185 C192.739047,103.252075 194.511905,96.7395349 194.511905,88.9243697 C194.511905,81.6881057 193.317939,75.6097352 190.929972,70.6890756 C188.542005,65.7684161 185.177193,61.8247114 180.835434,58.8578431 C176.493676,55.8909749 171.283644,53.756309 165.205182,52.4537815 C159.12672,51.151254 152.397096,50.5 145.016106,50.5 L72.07493,50.5 L72.07493,50.5 Z M106.157563,179.015406 L106.157563,136.466387 L143.279412,136.466387 C150.660401,136.466387 156.594049,138.166883 161.080532,141.567927 C165.567016,144.968971 167.810224,150.649353 167.810224,158.609244 C167.810224,162.661552 167.122789,165.990183 165.747899,168.595238 C164.373009,171.200293 162.527789,173.262597 160.212185,174.782213 C157.89658,176.301828 155.219203,177.387252 152.179972,178.038515 C149.140741,178.689779 145.956833,179.015406 142.628151,179.015406 L106.157563,179.015406 L106.157563,179.015406 Z"
            fill="#FFFFFF">

        </path>
    </g>
</svg>
            </span>
        </span>
                <!-- vue -->
        <span class="group grid animate-tech backdrop-blur-sm transition duration-700 w-full min-w-[7rem] transform place-items-center rounded-xl border border-blue-gray-50 bg-cyan-800 shadow-lg sm:rounded-3xl sm:hover:border-cyan-400 bg-clip-padding bg-opacity-55 sm:hover:shadow-cyan-400 px-3 py-2 hover:scale-105 sm:border-cyan-50 border-cyan-400 hover:bsm:g-opacity-25">
            <span class="grid w-24 h-24 my-6 place-items-center">
          <svg width="90" height="90" viewBox="0 0 64 64" class="transition-all duration-300 group-hover:brightness-100 group-hover:contrast-200 grayscale group-hover:grayscale-0" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" xml:space="preserve">
            <rect id="Icons" x="-512" y="-128" width="1280" height="800" style="fill:none;"/>
            <!-- Tambahkan path untuk logo Vue.js -->
            <path d="M17.595,11.204l8.91,0l5.536,9.391l5.591,-9.391l8.831,0l-14.422,25.359l-14.446,-25.359Z" style="fill:#435466;"/>
            <path d="M8.089,11.204l23.952,41.845l24.126,-41.845l-9.704,0l-14.422,25.359l-14.446,-25.359l-9.506,0Z" style="fill:#4dba87;"/>
          </svg>
            </span>
        </span>
        <!-- node js -->
         <span class="group grid animate-tech backdrop-blur-sm transition duration-700 w-full min-w-[7rem] transform place-items-center rounded-xl border border-blue-gray-50 bg-cyan-800 shadow-lg sm:rounded-3xl sm:hover:border-cyan-400 bg-clip-padding bg-opacity-55 sm:hover:shadow-cyan-400 px-3 py-2 hover:scale-105 sm:border-cyan-50 border-cyan-400 hover:bsm:g-opacity-25">
            <span class="grid w-24 h-24 my-6 place-items-center">
           <img src="https://upload.wikimedia.org/wikipedia/commons/d/d9/Node.js_logo.svg" alt="Node.js logo.svg" height="361" width="590" class="transition-all duration-300 group-hover:brightness-100 group-hover:contrast-200 grayscale group-hover:grayscale-0">
            </span>
        </span>
        <!-- sequelize -->
        <span class="group grid animate-tech backdrop-blur-sm transition duration-700 w-full min-w-[7rem] transform place-items-center rounded-xl border border-blue-gray-50 bg-cyan-800 shadow-lg sm:rounded-3xl sm:hover:border-cyan-400 bg-clip-padding bg-opacity-55 sm:hover:shadow-cyan-400 px-3 py-2 hover:scale-105 sm:border-cyan-50 border-cyan-400 hover:bsm:g-opacity-25">
            <span class="grid w-24 h-24 my-6 place-items-center">
           <img src="https://www.vectorlogo.zone/logos/sequelizejs/sequelizejs-ar21.svg" alt="sequelize" srcset="" class="transition-all duration-300 scale:125 sm:scale-150 group-hover:brightness-100 group-hover:contrast-200 grayscale group-hover:grayscale-0">
            </span>
        </span>
        <!-- mysql -->
         <span class="group grid animate-tech backdrop-blur-sm transition duration-700 w-full min-w-[7rem] transform place-items-center rounded-xl border border-blue-gray-50 bg-cyan-800 shadow-lg sm:rounded-3xl sm:hover:border-cyan-400 bg-clip-padding bg-opacity-55 sm:hover:shadow-cyan-400 px-3 py-2 hover:scale-105 sm:border-cyan-50 border-cyan-400 hover:bsm:g-opacity-25">
            <span class="grid w-24 h-24 my-6 place-items-center">
           <svg width="120" height="120"  viewBox="-18.458 -22.75 191.151 191.151" class="-mx-4 -mt-4 transition-all duration-300 group-hover:brightness-100 group-hover:contrast-200 grayscale group-hover:grayscale-0"
            xmlns="http://www.w3.org/2000/svg">
            <path d="M-18.458 6.58h191.151v132.49H-18.458V6.58z" fill="none" />
            <path
              d="M40.054 113.583h-5.175c-.183-8.735-.687-16.947-1.511-24.642h-.046l-7.879 24.642h-3.94l-7.832-24.642h-.045c-.581 7.388-.947 15.602-1.099 24.642H7.81c.304-10.993 1.068-21.299 2.289-30.919h6.414l7.465 22.719h.046l7.511-22.719h6.137c1.344 11.268 2.138 21.575 2.382 30.919M62.497 90.771c-2.107 11.434-4.887 19.742-8.337 24.928-2.688 3.992-5.633 5.99-8.84 5.99-.855 0-1.91-.258-3.16-.77v-2.757c.611.088 1.328.138 2.152.138 1.498 0 2.702-.412 3.62-1.238 1.098-1.006 1.647-2.137 1.647-3.388 0-.858-.428-2.612-1.282-5.268L42.618 90.77h5.084l4.076 13.19c.916 2.995 1.298 5.086 1.145 6.277 2.229-5.953 3.786-12.444 4.673-19.468h4.901v.002z"
              fill="#5d87a1" />
            <path
              d="M131.382 113.583h-14.7V82.664h4.945v27.113h9.755v3.806zM112.834 114.33l-5.684-2.805c.504-.414.986-.862 1.42-1.381 2.416-2.838 3.621-7.035 3.621-12.594 0-10.229-4.014-15.346-12.045-15.346-3.938 0-7.01 1.298-9.207 3.895-2.414 2.84-3.619 7.022-3.619 12.551 0 5.435 1.068 9.422 3.205 11.951 1.955 2.291 4.902 3.438 8.843 3.438 1.47 0 2.819-.18 4.048-.543l7.4 4.308 2.018-3.474zm-18.413-6.934c-1.252-2.014-1.878-5.248-1.878-9.707 0-7.785 2.365-11.682 7.1-11.682 2.475 0 4.289.932 5.449 2.792 1.25 2.017 1.879 5.222 1.879 9.619 0 7.849-2.367 11.774-7.099 11.774-2.476.001-4.29-.928-5.451-2.796M85.165 105.013c0 2.622-.962 4.773-2.884 6.458-1.924 1.678-4.504 2.519-7.737 2.519-3.024 0-5.956-.966-8.794-2.888l1.329-2.655c2.442 1.223 4.653 1.831 6.638 1.831 1.863 0 3.319-.413 4.375-1.232 1.055-.822 1.684-1.975 1.684-3.433 0-1.837-1.281-3.407-3.631-4.722-2.167-1.19-6.501-3.678-6.501-3.678-2.349-1.712-3.525-3.55-3.525-6.578 0-2.506.877-4.529 2.632-6.068 1.757-1.545 4.024-2.315 6.803-2.315 2.87 0 5.479.769 7.829 2.291l-1.192 2.656c-2.01-.854-3.994-1.281-5.951-1.281-1.585 0-2.809.381-3.66 1.146-.858.762-1.387 1.737-1.387 2.933 0 1.828 1.308 3.418 3.722 4.759 2.196 1.192 6.638 3.723 6.638 3.723 2.409 1.709 3.612 3.53 3.612 6.534"
              fill="#f8981d" />
            <path
              d="M137.59 72.308c-2.99-.076-5.305.225-7.248 1.047-.561.224-1.453.224-1.531.933.303.3.338.784.601 1.198.448.747 1.229 1.752 1.942 2.276.783.6 1.569 1.194 2.393 1.717 1.453.899 3.1 1.422 4.516 2.318.825.521 1.645 1.195 2.471 1.756.406.299.666.784 1.193.971v-.114c-.264-.336-.339-.822-.598-1.196l-1.122-1.082c-1.084-1.456-2.431-2.727-3.884-3.771-1.196-.824-3.812-1.944-4.297-3.322l-.076-.076c.822-.077 1.797-.375 2.578-.604 1.271-.335 2.43-.259 3.734-.594.6-.15 1.195-.338 1.797-.523v-.337c-.676-.673-1.158-1.567-1.869-2.203-1.902-1.643-3.998-3.25-6.164-4.595-1.16-.749-2.652-1.231-3.887-1.868-.445-.225-1.195-.336-1.457-.71-.67-.822-1.047-1.904-1.533-2.877-1.08-2.053-2.129-4.331-3.061-6.502-.674-1.456-1.084-2.91-1.906-4.257-3.85-6.35-8.031-10.196-14.457-13.971-1.381-.786-3.024-1.121-4.779-1.533l-2.803-.148c-.598-.262-1.197-.973-1.719-1.309-2.132-1.344-7.621-4.257-9.189-.411-1.01 2.431 1.494 4.821 2.354 6.054.635.856 1.458 1.83 1.902 2.802.263.635.337 1.309.6 1.98.598 1.644 1.157 3.473 1.943 5.007.41.782.857 1.604 1.381 2.312.3.414.822.597.936 1.272-.521.744-.562 1.867-.861 2.801-1.344 4.221-.819 9.45 1.086 12.552.596.934 2.018 2.99 3.92 2.202 1.684-.672 1.311-2.801 1.795-4.668.111-.451.038-.747.262-1.043v.073c.521 1.045 1.047 2.052 1.53 3.1 1.159 1.829 3.177 3.735 4.858 5.002.895.676 1.604 1.832 2.725 2.245V74.1h-.074c-.227-.335-.559-.485-.857-.745-.674-.673-1.42-1.495-1.943-2.241-1.566-2.093-2.952-4.41-4.182-6.801-.602-1.16-1.121-2.428-1.606-3.586-.226-.447-.226-1.121-.601-1.346-.562.821-1.381 1.532-1.791 2.538-.711 1.609-.785 3.588-1.049 5.646l-.147.072c-1.19-.299-1.604-1.53-2.056-2.575-1.119-2.654-1.307-6.914-.336-9.976.26-.783 1.385-3.249.936-3.995-.225-.715-.973-1.122-1.383-1.685-.482-.708-1.01-1.604-1.346-2.39-.896-2.091-1.347-4.408-2.312-6.498-.451-.974-1.234-1.982-1.868-2.879-.712-1.008-1.495-1.718-2.058-2.913-.186-.411-.447-1.083-.148-1.53.073-.3.225-.412.523-.487.484-.409 1.867.111 2.352.336 1.385.56 2.543 1.083 3.699 1.867.523.375 1.084 1.085 1.755 1.272h.786c1.193.26 2.538.072 3.661.41 1.979.636 3.772 1.569 5.38 2.576 4.893 3.103 8.928 7.512 11.652 12.778.447.858.637 1.644 1.045 2.539.787 1.832 1.76 3.7 2.541 5.493.785 1.755 1.533 3.547 2.654 5.005.559.784 2.805 1.195 3.812 1.606.745.335 1.905.633 2.577 1.044 1.271.783 2.537 1.682 3.732 2.543.595.448 2.465 1.382 2.576 2.13M99.484 39.844a5.82 5.82 0 0 0-1.529.188v.075h.072c.301.597.824 1.011 1.197 1.532.301.599.562 1.193.857 1.791l.072-.074c.527-.373.789-.971.789-1.868-.227-.264-.262-.522-.451-.784-.22-.374-.705-.56-1.007-.86"
              fill="#5d87a1" />
            <path
              d="M141.148 113.578h.774v-3.788h-1.161l-.947 2.585-1.029-2.585h-1.118v3.788h.731v-2.882h.041l1.078 2.882h.557l1.074-2.882v2.882zm-6.235 0h.819v-3.146h1.072v-.643h-3.008v.643h1.115l.002 3.146z"
              fill="#f8981d" />
          </svg>
            </span>
        </span>
        <!-- postgres -->
          <span class="group grid animate-tech backdrop-blur-sm transition duration-700 w-full min-w-[7rem] transform place-items-center rounded-xl border border-blue-gray-50 bg-cyan-800 shadow-lg sm:rounded-3xl sm:hover:border-cyan-400 bg-clip-padding bg-opacity-55 sm:hover:shadow-cyan-400 px-3 py-2 hover:scale-105 sm:border-cyan-50 border-cyan-400 hover:bsm:g-opacity-25">
            <span class="grid w-24 h-24 my-6 place-items-center">
              <svg xmlns="http://www.w3.org/2000/svg" x="0px" y="0px" class="transition-all duration-300 group-hover:brightness-100 group-hover:contrast-200 grayscale group-hover:grayscale-0" width="100" height="100" viewBox="0 0 100 100">
        <path fill="#6e78ac" d="M83.242,60.482c-6.349,1.924-9.957-0.415-9.957-0.415s-0.006,0-0.007,0l-0.394-0.488	c0.131-0.117,0.264-0.242,0.4-0.381l0.019-0.017l-0.001-0.002c5.639-5.753,15.838-29.562,9.749-37.378	c-8.553-10.979-25.66-5.745-25.66-5.745l0.064,0.183c-4.889-1.666-9.947-1.625-13.851,0.838c-0.661,0.417-1.273,0.873-1.844,1.357	l0.014-0.187c0,0-8.149-3.213-15.851-2.383c-7.954,0.857-12.319,6.83-12.319,15.83s6.17,30.553,10.17,34.553s6,2,7,1	c0.896-0.896,6.588-7.387,7.771-8.738c2.143,1.4,4.575,1.743,5.983,1.748c-0.184,0.991-1.31,4.988-7.562,5.714	c-2.809,0.447-1.915,2.298,0.128,2.872c2.002,0.563,8.415,1.967,12.335-3.509c-0.052,3.397-0.183,9.771,0.304,15.126	c0.574,6.319,3.983,8.376,6.511,8.713c7.878,1.048,10.628-4.308,11.394-6.702c0.702-2.194,1.839-10.809,2.213-16.588l0.503-0.089	l-0.004,0.05c8.106,1.277,12.734-1.66,14.362-3.191C86.338,61.12,85.349,59.844,83.242,60.482z"></path><path fill="none" stroke="#1f212b" stroke-miterlimit="10" stroke-width="2" d="M39,58c0,0-6.75,7.562-7.75,8.562s-3,3-7-1	s-10.25-25-10.25-34s4.234-15.518,12.188-16.375C33.89,14.358,42,18,42,18"></path><path fill="none" stroke="#1f212b" stroke-miterlimit="10" stroke-width="2" d="M71.213,56.947	c2.681-2.106,2.968-8.713,2.489-12.734c-0.479-4.021,0.331-6.392,0.235-11.275C70.682,19.629,53.612,10.839,43.75,17.062	s-8.854,20.137-8.375,24.062s-2.444,6.539-0.625,12.188s7.644,6.698,10.037,6.698c2.394,0,4.883,0.957,4.883,3.543	s-0.287,10.34,0.287,16.66c0.574,6.319,3.983,8.376,6.511,8.713c7.878,1.048,10.628-4.309,11.394-6.702s2.052-12.439,2.298-18.096	c0.191-4.404,3.351-4.309,3.351-4.309s3.608,2.339,9.957,0.415c2.106-0.638,3.096,0.638,1.468,2.17	c-1.628,1.532-6.017,4.56-14.124,3.283"></path><path fill="none" stroke="#1f212b" stroke-miterlimit="10" stroke-width="2" d="M74.085,33.617c0,0-6.523-2.242-8.71,2.195	c-1.893,3.841,3.987,18.294,8.199,23.592"></path><path fill="none" stroke="#1f212b" stroke-miterlimit="10" stroke-width="2" d="M34.574,36.617c0,0,7.652-4.612,11.801-1.867	S48.936,48.106,47.149,52c-1.787,3.894-2.362,7.787-2.362,7.787s-0.447,5.106-7.596,5.936c-2.809,0.447-1.915,2.298,0.128,2.872	c2.043,0.574,8.681,2.043,12.574-3.83"></path><path fill="none" stroke="#1f212b" stroke-linecap="round" stroke-miterlimit="10" stroke-width="2" d="M57.617,15.809	c0,0,17.356-4.174,25.383,5.629c6.553,8.003-4.766,33.882-10.191,38.158"></path><path fill="#1f212b" d="M69.154,38.037c-1.652,0.168-3.423-1.939-0.096-2.346C72.177,35.31,71.323,37.817,69.154,38.037z"></path><path fill="#1f212b" d="M43.223,38.848c-1.824-0.23-3.212-2.945,0.481-2.556C47.165,36.657,45.619,39.151,43.223,38.848z"></path><path fill="none" stroke="#1f212b" stroke-linecap="round" stroke-linejoin="round" stroke-miterlimit="10" d="M39.492,27.447	c-0.236,0.688-0.451,1.425-0.641,2.213"></path><path fill="none" stroke="#1f212b" stroke-linecap="round" stroke-linejoin="round" stroke-miterlimit="10" d="M47.808,18.479	c-2.789,0.876-5.771,2.939-7.731,7.456"></path><path fill="none" stroke="#1f212b" stroke-linecap="round" stroke-linejoin="round" stroke-miterlimit="10" d="M55.064,18.298	c0,0-2.11-0.621-4.851-0.319"></path><path fill="none" stroke="#1f212b" stroke-linecap="round" stroke-linejoin="round" stroke-miterlimit="10" d="M20.148,21.817	c-1.921,2.074-3.369,5.451-3.173,10.945"></path><path fill="none" stroke="#1f212b" stroke-linecap="round" stroke-linejoin="round" stroke-miterlimit="10" d="M28.319,18.553	c0,0-3.417-0.258-6.503,1.833"></path><path fill="none" stroke="#1f212b" stroke-linecap="round" stroke-linejoin="round" stroke-miterlimit="10" d="M53.549,82.6	c0.649,1.702,1.858,3.266,4.1,3.613"></path><path fill="none" stroke="#1f212b" stroke-linecap="round" stroke-linejoin="round" stroke-miterlimit="10" d="M52.83,77.596	c0,0-0.095,1.358,0.186,3.001"></path>
        </svg>
            </span>
        </span>
        <!-- vscode -->
         <span class="group grid animate-tech backdrop-blur-sm transition duration-700 w-full min-w-[7rem] transform place-items-center rounded-xl border border-blue-gray-50 bg-cyan-800 shadow-lg sm:rounded-3xl sm:hover:border-cyan-400 bg-clip-padding bg-opacity-55 sm:hover:shadow-cyan-400 px-3 py-2 hover:scale-105 sm:border-cyan-50 border-cyan-400 hover:bsm:g-opacity-25">
            <span class="grid w-24 h-24 my-6 place-items-center">
          <svg xmlns="http://www.w3.org/2000/svg" class="transition-all duration-300 group-hover:brightness-100 group-hover:contrast-200 grayscale group-hover:grayscale-0" x="0px" y="0px" width="100" height="100" viewBox="0 0 48 48">
          <path fill="#29b6f6" d="M44,11.11v25.78c0,1.27-0.79,2.4-1.98,2.82l-8.82,4.14L34,33V15L33.2,4.15l8.82,4.14 C43.21,8.71,44,9.84,44,11.11z"></path><path fill="#0277bd" d="M9,33.896L34,15V5.353c0-1.198-1.482-1.758-2.275-0.86L4.658,29.239 c-0.9,0.83-0.849,2.267,0.107,3.032c0,0,1.324,1.232,1.803,1.574C7.304,34.37,8.271,34.43,9,33.896z"></path><path fill="#0288d1" d="M9,14.104L34,33v9.647c0,1.198-1.482,1.758-2.275,0.86L4.658,18.761 c-0.9-0.83-0.849-2.267,0.107-3.032c0,0,1.324-1.232,1.803-1.574C7.304,13.63,8.271,13.57,9,14.104z"></path>
          </svg>
            </span>
        </span>
           <span class="group grid animate-tech backdrop-blur-sm transition duration-700 w-full min-w-[7rem] transform place-items-center rounded-xl border border-blue-gray-50 bg-cyan-800 shadow-lg sm:rounded-3xl sm:hover:border-cyan-400 bg-clip-padding bg-opacity-55 sm:hover:shadow-cyan-400 px-3 py-2 hover:scale-105 sm:border-cyan-50 border-cyan-400 hover:bsm:g-opacity-25">
            <span class="grid w-24 h-24 my-6 place-items-center">
         <svg xmlns="http://www.w3.org/2000/svg" class="transition-all duration-300 group-hover:brightness-100 group-hover:contrast-200 grayscale group-hover:grayscale-0" x="0px" y="0px" width="100" height="100" viewBox="0 0 24 24">
        <path d="M10.9,2.1c-4.6,0.5-8.3,4.2-8.8,8.7c-0.5,4.7,2.2,8.9,6.3,10.5C8.7,21.4,9,21.2,9,20.8v-1.6c0,0-0.4,0.1-0.9,0.1 c-1.4,0-2-1.2-2.1-1.9c-0.1-0.4-0.3-0.7-0.6-1C5.1,16.3,5,16.3,5,16.2C5,16,5.3,16,5.4,16c0.6,0,1.1,0.7,1.3,1c0.5,0.8,1.1,1,1.4,1 c0.4,0,0.7-0.1,0.9-0.2c0.1-0.7,0.4-1.4,1-1.8c-2.3-0.5-4-1.8-4-4c0-1.1,0.5-2.2,1.2-3C7.1,8.8,7,8.3,7,7.6C7,7.2,7,6.6,7.3,6 c0,0,1.4,0,2.8,1.3C10.6,7.1,11.3,7,12,7s1.4,0.1,2,0.3C15.3,6,16.8,6,16.8,6C17,6.6,17,7.2,17,7.6c0,0.8-0.1,1.2-0.2,1.4 c0.7,0.8,1.2,1.8,1.2,3c0,2.2-1.7,3.5-4,4c0.6,0.5,1,1.4,1,2.3v2.6c0,0.3,0.3,0.6,0.7,0.5c3.7-1.5,6.3-5.1,6.3-9.3 C22,6.1,16.9,1.4,10.9,2.1z"></path>
    </svg>
            </span>
        </span>
        </div>
    </div>
</section>
</template>
<script>
export default {
  methods: {
     setupIntersectionObserver(targetClass) {
      const options = {
        root: null,
        rootMargin: '0px',
        threshold: 0.5,
      };

      const observer = new IntersectionObserver((entries) => {
        entries.forEach((entry) => {
          if (entry.isIntersecting) {
            entry.target.style.opacity = 1;
            entry.target.style.transform = 'translateY(0)';
          }
        });
      }, options);

      const targets = document.querySelectorAll(targetClass);
      targets.forEach((target) => {
        observer.observe(target);
      });
    },
  },
  mounted() {
    this.setupIntersectionObserver('.animate-tech'),
    this.setupIntersectionObserver('.animate-left-title'),
    this.setupIntersectionObserver('.animate-slideUp-subtitle')
  },
};
</script>
<style>
.animate-tech {
  opacity: 0;
  transition: opacity 2s;
}
.animate-left-title {
  opacity: 0;
  transform: translateX(-50%);
  transition: opacity 1s, transform 1s;
}
.animate-slideUp-subtitle {
  opacity: 0;
  transform: translatey(50%);
  transition: opacity 2s, transform 1s;
}
</style>