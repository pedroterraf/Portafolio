<template>
  <div id='works' className='flex w-full md:w-[90%] min-h-screen my-auto mx-auto text-[#0a192f] dark:text-gray-300 bg-slate-100 dark:bg-[#0a192f]'>
      <div className='max-w-[750px] m-auto p-4 flex flex-col justify-center w-full h-full'>
        <div className='pb-8'>
            <p className='text-4xl font-bold inline border-b-4 text-[#0a192f] dark:text-gray-300 border-pink-600' data-aos="fade-in">
                {{ text.title }}
            </p>
            <p className='py-3 text-[#112240] font-medium dark:text-[#f9b82c] dark:font-normal' data-aos="fade-in">{{ text.subtitle }}</p>
        </div>

        <div className='flex bg-slate-300 dark:bg-[#112240] bg-cover px-8 py-12 md:bg-transparent dark:md:bg-transparent md:p-0 mb-12' data-aos="fade-in">
            <div className="flex flex-col md:w-[60%] py-4">
                <div className="flex flex-col relative top-[-35px]">
                    <span className="text-[#f9b82c] dark:text-[#64ffda] text-sm font-medium">{{ text.work01.subtitle }}</span>
                    <h3 className=" text-2xl font-semibold">{{ text.work01.title }}</h3>
                </div>
                <div className="md:p-4 md:w-[130%] rounded md:bg-slate-300 dark:md:bg-[#112240] z-10">
                    <p className=" text-sm text-justify font-medium dark:font-normal">
                        {{ text.work01.description }}
                    </p>
                </div>
                <div className="flex md:w-[130%] z-10 pt-4">
                    <ul className="flex flex-wrap text-sm font-medium text-[#4a6087] dark:text-slate-400" :style="{'-webkit-text-stroke': '0.1px black'}">
                        <li className="pr-4 dark:text-[#06a608]"> <p>React</p> </li>
                        <li className="pr-4 dark:text-[#06a608]"> <p>Redux</p> </li>
                        <li className="pr-4 dark:text-[#06a608]"> <p>Node</p> </li>
                        <li className="pr-4 dark:text-[#06a608]"> <p>Express</p> </li>
                        <li className="pr-4 dark:text-[#06a608]"> <p>PostgreSQL</p> </li>
                        <li className="pr-4 dark:text-[#06a608]"> <p>Sequelize</p> </li>
                    </ul>
                </div>
                <div className="flex relative bottom-[-20px]">
                    <a className='flex justify-between items-center dark:text-white pr-4 hover:text-pink-600 dark:hover:text-pink-600 duration-300' href='https://github.com/pedroterraf/Countries-PI.git' target='_blank' rel="noreferrer"> 
                        <fa :icon="['fab', 'github']" class="fa-lg" />
                    </a>
<!--                     <a className='flex justify-between items-center dark:text-white pr-4 hover:text-pink-600 dark:hover:text-pink-600 duration-300' href='https://github.com/parzybaal/PI-Dogs-main' target='_blank' rel="noreferrer"> 
                        <fa icon="arrow-up-right-from-square" class="fa-lg" />
                    </a> -->
                </div>
            </div>
            <a className="hidden md:flex w-[70%] h-[250px] my-auto z-0 overflow-hidden" href='https://github.com/pedroterraf/Countries-PI.git' target='_blank' rel="noreferrer">
                <div className="bg md:flex w-full h-full my-auto z-0 bg-cover hover:bg-transparent duration-300" :style="{'background-image': 'url(' + Countries + ')'}"/>
            </a>
        </div>

        <div className='flex bg-slate-300 dark:bg-[#112240] bg-cover px-8 py-12 md:bg-transparent dark:md:bg-transparent md:p-0 mb-12' data-aos="fade-in">
            <a className="hidden md:flex w-[70%] h-[250px] my-auto z-0 overflow-hidden" href='https://somosedison.com/' target='_blank' rel="noreferrer">
                <div className="bg md:flex w-full h-full my-auto z-0 bg-cover hover:bg-transparent duration-300" :style="{'background-image': 'url(' + Edison + ')'}"/>
            </a>
            <div className="flex flex-col md:w-[60%] py-4">
                <div className="flex flex-col relative top-[-35px] text-right">
                    <span className="text-[#f9b82c] dark:text-[#64ffda] text-sm font-medium">{{ text.work02.subtitle }}</span>
                    <h3 className=" text-2xl font-semibold">{{ text.work02.title }}</h3>
                </div>
                <div className="md:p-4 md:w-[130%] relative md:right-[30%]  rounded md:bg-slate-300 dark:md:bg-[#112240] z-10">
                    <p className=" text-sm text-justify font-medium dark:font-normal">
                        {{ text.work02.description }}
                    </p>
                </div>
                <div className="flex md:w-[130%] relative md:right-[30%] z-10 pt-4">
                    <ul className="flex flex-wrap md:justify-end text-sm font-medium text-[#4a6087] dark:text-slate-400" :style="{'-webkit-text-stroke': '0.1px black'}">
                        <li className="md:pl- pr-4 md:pr-0 dark:text-[#06a608]"> <p>React</p> </li>
                        <li className="md:pl-4 pr-4 md:pr-0 dark:text-[#06a608] text-shadow: 8px 8px 8px rgb(0, 0, 0);"> <p>Redux toolkit</p> </li>
                        <li className="md:pl-4 pr-4 md:pr-0 dark:text-[#06a608]"> <p>Express</p> </li>
                        <li className="md:pl-4 pr-4 md:pr-0 dark:text-[#06a608]"> <p>Nodejs</p> </li>
                        <li className="md:pl-4 pr-4 md:pr-0 dark:text-[#06a608]"> <p>Css</p> </li>
                        <li className="md:pl-4 pr-4 md:pr-0 dark:text-[#06a608]"> <p>Sequelize</p> </li>
                        <li className="md:pl-4 pr-4 md:pr-0 dark:text-[#06a608]"> <p>Bootstrap</p> </li>
                        <li className="md:pl-4 pr-4 md:pr-0 dark:text-[#06a608]"> <p>Tailwind</p> </li>
                        <li className="md:pl-4 pr-4 md:pr-0 dark:text-[#06a608]"> <p>Airtable</p> </li>
                        <li className="md:pl-4 pr-4 md:pr-0 dark:text-[#06a608]"> <p>Stripe</p> </li>
                        <li className="md:pl-4 pr-4 md:pr-0 dark:text-[#06a608]"> <p>Mercado Pago</p> </li>
                        <li className="md:pl-4 pr-4 md:pr-0 dark:text-[#06a608]"> <p>Deploy Amazon</p> </li>
                    </ul>
                </div>
                <div className="flex relative bottom-[-20px] justify-end">
                    <a className='flex justify-between items-center dark:text-white pl-4 hover:text-pink-600 dark:hover:text-pink-600 duration-300' href='https://somosedison.com/' target='_blank' rel="noreferrer"> 
                        <fa icon="arrow-up-right-from-square" class="fa-lg" />
                    </a>
                </div>
            </div>
        </div>
      </div>
  </div>
</template>

<script>
import Edison from '../assets/Edison.png'
import Countries from '../assets/PI-COUNTRIES.png'

export default {
    data() {
        return {
            Edison,
            Countries,
            eng: {
                title: 'Work',
                subtitle: '// Check out some of my recent work',
                work01: {
                    title: 'Countries app',
                    subtitle: 'Featured Project',
                    description: 'Project of all the countries in the world. On the home page, I fetched all the countries from an API along with their respective filters, pagination, and search bar to find the desired country as quickly as possible. Then, there is a detail page for each country that displays the specific details, and it also includes their respective activities created through a form with appropriate validations.'
                },
                work02: {
                    title: 'Edison',
                    subtitle: 'Featured Project',
                    description: 'During my internship at Edison company, I had the opportunity to participate in the development of a new version of their website using various technologies (ReactJs, Nodejs, Airtable, Express, Bootstrap, Tailwind). In this project, we worked on implementing payment gateways with both national and international methods. We created the Marketplace and added sections such as forms with their respective validations, as well as informational pages. Additionally, we successfully applied the corresponding design to all the different components of the site.'
                },
            }, 
            es: {
                title: 'Proyectos',
                subtitle: '// Mira algunos de mis proyectos más recientes',
                work01: {
                    title: 'Aplicación de paises',
                    subtitle: 'Proyecto Destacado',
                    description: 'Proyecto de todos los paises del mundo, en el home me traje todos los paises de una api y con sus respectivos filtros, paginado y barra de busqueda para encontrar el pais que buscas lo antes posible. Luego un detail de cada pais que aparece los detalles de cada uno con sus respectivas activides creadas en un formulario con sus respectivas validaciones.'
                },
                work02: {
                    title: 'Edison',
                    subtitle: 'Proyecto Destacado',
                    description: 'Durante mi pasantía laboral en la empresa de Edison, tuve la oportunidad de participar en el desarrollo de una nueva versión de su sitio web utilizando diferentes tecnologías (ReactJs, Nodejs, Airtable, Express, Bootstrap, Tailwind ). En este proyecto, trabajamos en la implementación de pasarelas de pago con métodos nacionales e internacionales, creamos el Marketplace y añadimos secciones como formularios con sus respectivas validaciones, así como páginas informativas. También logramos aplicar su diseño correspondiente a todos los diferentes componentes del sitio.'
                },
            },
        }
    }, 
    computed: {
        text() {
            return this.$store.state.lang === 'en' ? this.eng : this.es
        }
    },
}
</script>

<style scoped>
    .bg {
        background-color: #00808099;
        background-blend-mode: lighten;
        border-radius: 0.25rem;
        color: #06a608;
    }

    .bg:hover {
        cursor: pointer;
    }
</style>