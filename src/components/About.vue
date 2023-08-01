<template>
    <div id='about' className='w-full md:w-[90%] min-h-screen flex flex-row mx-auto bg-slate-100 dark:bg-[#0a192f]' >
        <div className='flex flex-col justify-center items-center w-full h-full m-auto px-8'>
            <div className='max-w-[750px] w-full grid grid-cols-2 gap-8' data-aos="fade-in" >
                <div className='pb-8'>
                    <p className='text-4xl text-[#0a192f] dark:text-gray-300 font-bold inline border-b-4 border-pink-600'>{{ text.section }}</p>
                </div>
                <div></div>
                </div>
                <div className='max-w-[750px] w-full first:grid sm:grid-cols-2 gap-8'>
                    <div className='text-4xl font-bold text-[#f9b82c]' data-aos="fade-in">
                        <p>{{text.title}}</p>
                    </div>
                    <div>
                        <p className='text-slate-700 font-medium dark:text-slate-100 dark:font-normal text-justify my-4' data-aos="fade-in">
                            {{ text.text }} <br> <br> {{ text.subtext }}
                        </p>
                    </div>
            </div>
        </div>
    </div>
</template>

<script>

export default {
    data() {
        return {
            eng: {
                section: 'About',
                title: 'Nice to meet you. Please take a look around.',
                text: 'Since I was very young, I have been interested in technology. At the age of 11, I built my first PC. I enjoy playing video games, meeting new people, and facing challenges that put my skills to the test.',
                subtext: "To date, I have completed 2 full stack projects in Henry's bootcamp, and I continue to seek new challenges to improve my skills. If you are looking for a collaborator or recruiting new talent, feel free to contact me!"
            },
            es: {
                section: 'Sobre mi',
                title: '¡Siéntete libre de explorar mi portafolio!',
                text: 'Desde muy pequeño estuve interesado en la tecnología. A los 11 años, armé mi primera PC. Me gustan los videojuegos, conocer nuevas personas y enfrentar desafíos que pongan a prueba mis habilidades.',
                subtext: 'A la fecha, he completado 2 proyectos full stack en el bootcamp de Henry y sigo buscando nuevos desafíos para mejorar mis habilidades. Si estás buscando un colaborador o un nuevo recluta, ¡no dudes en contactarme!',
            },
            isVisible: false,
        }
    }, computed: {
        text() {
            return this.$store.state.lang === 'en' ? this.eng : this.es
        }
    }
}
</script>