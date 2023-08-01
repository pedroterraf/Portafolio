<template>
  <div className='w-full md:w-[90%] mx-auto flex flex-col bg-slate-100 dark:bg-[#0a192f] text-center justify-center items-center'>
      <ul className="animate__bounce flex justify-center items-center w-[300px]">
          <li className='w-[30px] h-[50px] px-2 mx-auto flex justify-between items-center'>
              <a className='flex justify-between items-center w-full text-[#f9b82c] dark:text-white duration-300' href='https://www.linkedin.com/in/pedroterraf/' target='_blank' rel="noreferrer"> 
                  <fa :icon="['fab', 'linkedin']" class="fa-xl" />
              </a>
          </li>
          <li className='w-[25px] h-[50px] px-2 mx-auto flex justify-between items-center'>
              <a className='flex justify-between items-center w-full text-[#f9b82c] dark:text-white duration-300' href='https://github.com/pedroterraf/' target='_blank' rel="noreferrer"> 
                  <fa :icon="['fab', 'github']" class="fa-xl" />
              </a>
          </li>
          <li className='w-[25px] h-[50px] px-2 mx-auto flex justify-between items-center'>
              <a className='flex justify-between items-center w-full text-[#f9b82c] dark:text-white duration-300' href='mailto:pedroterraf@gmail.com' target='_blank' rel="noreferrer"> 
                  <fa icon="envelope" class="fa-xl" />
              </a>
          </li>
          <li className='w-[25px] h-[50px] px-2 mx-auto flex justify-between items-center'>
              <a className='flex justify-between items-center w-full text-[#f9b82c] dark:text-white duration-300' :href="link" target='_blank' rel="noreferrer"> 
                  <span class="mx-1"><fa icon="file-pdf" class="fa-xl" /></span>
              </a>
          </li>
      </ul>
    <span className='text-[#0a192f] dark:text-gray-300 text-sm font-medium dark:font-normal'>{{ text.subtitle }}</span>
    <span className='text-[#f9b82c] font-medium'>{{ text.title }}</span>
  </div>
</template>

<script>
export default {
  data() {
    return {
      eng: {
        subtitle: '// Design inspired on Brittany Chiang & Code Commerce',
        title: 'Built by Pedro Terraf'
      },
      es: {
        subtitle: '// Diseño inspirado en Brittany Chiang & Code Commerce',
        title: 'Desarrollado por Pedro Terraf'
      }
    }
  },
  computed: {
    text() {
      return this.$store.state.lang === 'en' ? this.eng : this.es
    },
    link(){
      return this.$store.state.lang === 'en' ? 'https://drive.google.com/file/d/13KyZ5zij01BA1IZOvvgVdfiAZ1wB14kU/view?usp=sharing' : 'https://drive.google.com/file/d/13KyZ5zij01BA1IZOvvgVdfiAZ1wB14kU/view?usp=sharing'
    }
  }
}
</script>

<style scoped>
    a:hover {
        color: rgb(22, 78, 169);
    }
</style>