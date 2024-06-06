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
                text: 'Since I was a child, I have always grown up with the computer. At the age of 12, I had already managed to create 2 servers in different online games. At 13, I became interested in starting to develop, and at the age of 23, I resumed a career focused on programming. Currently, I have completed 2 internships and sold 1 freelance project. On the other hand, I pursued Civil Engineering for several years but decided to switch to Systems Engineering, which I will be starting next year in 2024 with several credits already completed.',
                subtext: "I continue to seek new challenges to improve my skills. If you are looking for a collaborator or recruiting new talent, feel free to contact me!"
            },
            es: {
                section: 'Sobre mi',
                title: '¡Siéntete libre de explorar mi portafolio!',
                text: 'Desde chico, siempre me crié con la computadora. A los 12 años, ya había logrado crear 2 servidores en juegos diferentes abiertos en línea. A los 13, me interesó comenzar a desarrollar, y a los 23 años retomé una carrera enfocada en la programación. Actualmente estoy trabajando desde enero del 2024, anteriormente he realizado 3 prácticas laborales y 1 proyecto freelance que ya fue vendido. Por otro lado, cursé Ingeniería durante varios años',
                subtext: 'Sigo buscando nuevos desafíos para mejorar mis habilidades. Si estás buscando un colaborador o un nuevo recluta, ¡no dudes en contactarme!',
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