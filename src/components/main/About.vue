<template>
<section id="about" class="py-8 sm:py-20 container mx-auto">
 <h3 class="animate-left-content text-5xl mx-4 md:mx-12 text-cyan-400 font-bold">
  {{ $t('about.content1.title') }}
 </h3>
   <div class="relative">
         <div class="grid grid-cols-1 gap-2 sm:grid-cols-2">
    <!-- about me -->
    <div class="col-span-2">
      <div class="grid grid-cols-1 sm:grid-cols-2 gap-10 mx-4 sm:mx-12">
        <!-- Konten sebelah kiri -->
        <div class="animate-left-content">
          <p class="mt-4 text-white">
            {{ $t('about.content1.text') }}
          </p>
        </div>
        <!-- Konten sebelah kanan -->
        <div class="animate-right-content flex items-center justify-center group">
              <img
                src="../../assets/ab2.jpg"
                class="w-80 h-56 rounded-xl md:hover:shadow-lg md:hover:shadow-cyan-400 md:hover:scale-105 transition-all duration-700 grayscale group-hover:grayscale-0"
                alt="Image 2"
              />
        </div>
      </div>
    </div>
    <!-- end about me -->
    <!-- timeline pendidikan -->
    <div class="sm:hover:bg-cyan-800 sm:hover:shadow-cyan-400 shadow-lg transition-all duration-700 bg-transparent sm:hover:bg-opacity-55 col-span-2 group animate-timeline backdrop-blur-sm mx-4 sm:mx-10 mt-8 -mb-4 border border-cyan-400 sm:border-gray-400 sm:hover:border-cyan-400 bg-clip-padding rounded-xl sm:h-56 md:h-64">
      <h3 class="text-3xl font-bold mb-4 pl-5 sm:pl-16 mt-6 text-cyan-400">{{ $t('about.timeline.title') }}</h3>
      <ol class="items-center ml-5 sm:ml-16 sm:flex mt-6">
        <li class="relative mb-6 sm:mb-0">
          <div class="flex items-center">
            <div class="z-10 flex items-center justify-center w-6 h-6 bg-blue-100 rounded-full ring-0 ring-white dark:bg-blue-900 sm:ring-8 dark:ring-gray-900 shrink-0">
              <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-mortarboard-fill" viewBox="0 0 16 16">
                <path d="M8.211 2.047a.5.5 0 0 0-.422 0l-7.5 3.5a.5.5 0 0 0 .025.917l7.5 3a.5.5 0 0 0 .372 0L14 7.14V13a1 1 0 0 0-1 1v2h3v-2a1 1 0 0 0-1-1V6.739l.686-.275a.5.5 0 0 0 .025-.917z" />
                <path d="M4.176 9.032a.5.5 0 0 0-.656.327l-.5 1.7a.5.5 0 0 0 .294.605l4.5 1.8a.5.5 0 0 0 .372 0l4.5-1.8a.5.5 0 0 0 .294-.605l-.5-1.7a.5.5 0 0 0-.656-.327L8 10.466z" />
              </svg>
            </div>
            <!-- garis setelah icon -->
            <div class="hidden sm:block w-full bg-gray-200 h-0.5 dark:bg-gray-700"></div>
          </div>
          <div class="mt-3 sm:pe-8">
            <h3 class="text-lg font-semibold text-cyan-400 dark:text-white">{{ $t('about.timeline.items.0.title') }}</h3>
            <time class="block mb-2 text-sm font-normal leading-none text-gray-400 dark:text-gray-500">{{ $t('about.timeline.items.0.date') }}</time>
          </div>
        </li>
        <li class="relative mb-6 sm:mb-0">
          <div class="flex items-center">
            <div class="z-10 flex items-center justify-center w-6 h-6 bg-blue-100 rounded-full ring-0 ring-white dark:bg-blue-900 sm:ring-8 dark:ring-gray-900 shrink-0">
              <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-mortarboard-fill" viewBox="0 0 16 16">
                <path d="M8.211 2.047a.5.5 0 0 0-.422 0l-7.5 3.5a.5.5 0 0 0 .025.917l7.5 3a.5.5 0 0 0 .372 0L14 7.14V13a1 1 0 0 0-1 1v2h3v-2a1 1 0 0 0-1-1V6.739l.686-.275a.5.5 0 0 0 .025-.917z" />
                <path d="M4.176 9.032a.5.5 0 0 0-.656.327l-.5 1.7a.5.5 0 0 0 .294.605l4.5 1.8a.5.5 0 0 0 .372 0l4.5-1.8a.5.5 0 0 0 .294-.605l-.5-1.7a.5.5 0 0 0-.656-.327L8 10.466z" />
              </svg>
            </div>
            <!-- garis setelah icon -->
            <div class="hidden sm:block w-full bg-gray-200 h-0.5 dark:bg-gray-700"></div>
          </div>
          <div class="mt-3 sm:pe-8">
            <h3 class="text-lg font-semibold text-cyan-400 dark:text-white">{{ $t('about.timeline.items.1.title') }}</h3>
            <time class="block mb-2 text-sm font-normal leading-none text-gray-400 dark:text-gray-500">{{ $t('about.timeline.items.1.date') }}</time>
          </div>
        </li>
        <li class="relative mb-6 sm:-mb-5">
          <div class="flex items-center">
            <div class="z-10 flex items-center justify-center w-6 h-6 bg-blue-100 rounded-full ring-0 ring-white dark:bg-blue-900 sm:ring-8 dark:ring-gray-900 shrink-0">
              <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-mortarboard-fill" viewBox="0 0 16 16">
                <path d="M8.211 2.047a.5.5 0 0 0-.422 0l-7.5 3.5a.5.5 0 0 0 .025.917l7.5 3a.5.5 0 0 0 .372 0L14 7.14V13a1 1 0 0 0-1 1v2h3v-2a1 1 0 0 0-1-1V6.739l.686-.275a.5.5 0 0 0 .025-.917z" />
                <path d="M4.176 9.032a.5.5 0 0 0-.656.327l-.5 1.7a.5.5 0 0 0 .294.605l4.5 1.8a.5.5 0 0 0 .372 0l4.5-1.8a.5.5 0 0 0 .294-.605l-.5-1.7a.5.5 0 0 0-.656-.327L8 10.466z" />
              </svg>
            </div>
          </div>
          <div class="mt-3 sm:pe-8">
            <h3 class="text-lg font-semibold text-cyan-400 dark:text-white">
              {{ $t('about.timeline.items.2.title') }}
              <span class="flex mb-2 text-sm md:text-xs" v-if="isHighSchool">{{ $t('about.timeline.items.2.major')}}</span>
            </h3>
            <time class="block mb-2 text-sm font-normal leading-none text-gray-400 dark:text-gray-500">{{ $t('about.timeline.items.2.date') }}</time>
          </div>
        </li>
      </ol>
    </div>
    <!-- end timeline -->
      </div>

    <div class="grid grid-cols-1 sm:grid-cols-2 gap-0 sm:gap-4 mx-4 sm:mx-10">       
   <!-- timeline working -->
    <div class="sm:hover:bg-cyan-800 sm:hover:shadow-cyan-400 shadow-lg transition-all duration-700 bg-transparent sm:hover:bg-opacity-55 animate-timeline backdrop-blur-sm mt-8 -mb- sm:mb-6 border border-cyan-400 sm:border-gray-400 sm:hover:border-cyan-400 bg-clip-padding rounded-xl">
      <h3 class="text-3xl font-bold mb-4 pl-5 sm:pl-16 mt-6 text-cyan-400">{{ $t('about.timeline-working.title') }}</h3>
      <ol class="ml-8 sm:ml-16 mt-6 relative border-s border-gray-200 dark:border-gray-700">
        <li class="mb-6 ms-4">
          <div class="absolute w-3 h-3 bg-gray-200 rounded-full mt-1.5 -start-1.5 border border-white dark:border-gray-900 dark:bg-gray-700"></div>
          <time class="mb-1 text-sm font-normal leading-none text-gray-200">{{ $t('about.timeline-working.items.0.date') }}</time>
          <h3 class="text-lg font-semibold text-cyan-400 dark:text-white">{{ $t('about.timeline-working.items.0.title') }}</h3>
          <span class="mb-4 text-base font-normal text-gray-300 dark:text-gray-400">{{ $t('about.timeline-working.items.0.subtitle') }}</span>
          <ul class="max-w-md space-y-1 text-gray-300 list-disc list-inside dark:text-gray-400 mx-2 mb-2 text-sm">
            <li class="mb-2">{{ $t('about.timeline-working.items.0.items-works.0.name') }}</li>
            <li class="mb-2">{{ $t('about.timeline-working.items.0.items-works.1.name') }}</li>
            <li class="mb-2">{{ $t('about.timeline-working.items.0.items-works.2.name') }}</li>
          </ul>
        </li>
        <li class="mb-6 ms-4">
          <div class="absolute w-3 h-3 bg-gray-200 rounded-full mt-1.5 -start-1.5 border border-white dark:border-gray-900 dark:bg-gray-700"></div>
          <time class="mb-1 text-sm font-normal leading-none text-gray-200">{{ $t('about.timeline-working.items.1.date') }}</time>
          <h3 class="text-lg font-semibold text-cyan-400 dark:text-white">{{ $t('about.timeline-working.items.1.title') }}</h3>
          <span class="mb-4 text-base font-normal text-gray-300 dark:text-gray-400">{{ $t('about.timeline-working.items.1.subtitle') }}</span>
          <ul class="max-w-md space-y-1 text-gray-300 list-disc list-inside dark:text-gray-400 mx-2 mb-2 text-sm">
            <li class="mb-2">{{ $t('about.timeline-working.items.1.items-works.0.name') }}</li>
            <li class="mb-2">{{ $t('about.timeline-working.items.1.items-works.1.name') }}</li>
            <li class="mb-2">{{ $t('about.timeline-working.items.1.items-works.2.name') }}</li>
            <li class="mb-2">{{ $t('about.timeline-working.items.1.items-works.3.name') }}</li>
          </ul>
        </li>
      </ol>
    </div>
    <!-- end timeline working -->
<!-- certificate -->
<div class="sm:hover:bg-cyan-800 sm:hover:shadow-cyan-400 shadow-lg transition-all duration-700 bg-transparent sm:hover:bg-opacity-55 animate-timeline backdrop-blur-sm mt-8 mb-6 border border-cyan-400 sm:border-gray-400 sm:hover:border-cyan-400 bg-clip-padding rounded-xl">
  <h3 class="text-3xl font-bold mb-4 pl-5 sm:pl-16 mt-6 text-cyan-400">{{ $t('about.certificate.title') }}</h3>
  <ol class="ml-8 sm:ml-16 mt-6 relative border-s border-gray-200 dark:border-gray-700">
    <li class="mb-6 ms-4">
      <div class="absolute w-3 h-3 bg-gray-200 rounded-full mt-1.5 -start-1.5 border border-white dark:border-gray-900 dark:bg-gray-700"></div>
      <time class="mb-1 text-sm font-normal leading-none text-gray-200">{{ $t('about.certificate.items.0.date') }}</time>
      <h3 class="text-lg font-semibold text-cyan-400 dark:text-white">{{ $t('about.certificate.items.0.title') }}</h3>
      <span class="mb-4 text-base font-normal text-gray-300 dark:text-gray-400">{{ $t('about.certificate.items.0.subtitle') }}</span>
      <img
        :src="certificateImages[0]"
        alt="Description of image 1"
        class="w-62 h-32 mb-5 mt-5 rounded-md hover:scale-105 transition-all object-cover"
        @click="showPreview(0)"
      />
    </li>
    <li class="mb-6 ms-4">
      <div class="absolute w-3 h-3 bg-gray-200 rounded-full mt-1.5 -start-1.5 border border-white dark:border-gray-900 dark:bg-gray-700"></div>
      <time class="mb-1 text-sm font-normal leading-none text-gray-200">{{ $t('about.certificate.items.1.date') }}</time>
      <h3 class="text-lg font-semibold text-cyan-400 dark:text-white">{{ $t('about.certificate.items.1.title') }}</h3>
      <span class="mb-4 text-base font-normal text-gray-300 dark:text-gray-400">{{ $t('about.certificate.items.1.subtitle') }}</span>
      <img
        :src="certificateImages[1]"
        alt="Description of image 2"
        class="w-62 h-32 mb-5 mt-5 rounded-md hover:scale-105 transition-all object-cover"
        @click="showPreview(1)"
      />
    </li>
  </ol>
  <div v-show="showPreviewImage" @click="hidePreview" class="absolute top-0 left-0 w-full h-full flex items-center justify-center bg-black bg-opacity-75">
    <img :src="previewImage" alt="Preview Image" class="max-w-3/4 max-h-3/4" @click.stop>
  </div>
</div>
<!-- certificate -->
     </div>
   </div>
</section>
</template>
<script>
import { mapGetters } from 'vuex';

export default {
  data() {
    return {
      zoomed: null,
      certificateImages: [
        'https://i.ibb.co.com/6P0Mb8z/Certificate-Freee-Code-Camp-daffa-hd.jpg',
        'https://i.ibb.co.com/mtCXPj4/sertifikat-magang-Muhammad-Daffa-Fauzan.jpg'
      ],
      showPreviewImage: false,
      previewImage: ''
    }
  },
  mounted() {
    this.setupIntersectionObserver('.animate-left-content');
    this.setupIntersectionObserver('.animate-right-content');
    this.setupIntersectionObserver('.animate-timeline');
  },
  computed: {
    ...mapGetters('property', ['getAbout', 'getTextAbout']),
  }, 
  methods: {
    showPreview(index) {
      this.previewImage = this.certificateImages[index];
      this.showPreviewImage = true;
    },
    hidePreview() {
      this.showPreviewImage = false;
      this.previewImage = '';
    },
    isHighSchool() {
      return JSON.stringify(this.$t.about.timeline.items) === JSON.stringify([2]);
    },
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
};
</script>

<style scoped>
/* Animasi fade-in dan fade-out menggunakan CSS */
.animate-left-content {
  opacity: 0;
  transform: translateX(-50%);
  transition: opacity 1s, transform 1s;
}

.animate-right-content {
  opacity: 0;
  transform: translateY(50%);
  transition: opacity 2s, transform 1s;
}

.animate-timeline {
  opacity: 0;
  transition: opacity 1s;
}

</style>
