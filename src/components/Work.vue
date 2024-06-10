<template>
  <div id='works' className='flex w-full md:w-[60%] min-h-screen my-auto mx-auto text-[#0a192f] dark:text-gray-300 bg-slate-100 dark:bg-[#0a192f]'>
      <div className='max-w-[780px] m-auto p-4 flex flex-col justify-center w-full h-full'>
        <div className='pb-8'>
            <p className='text-4xl font-bold inline border-b-4 text-[#0a192f] dark:text-gray-300 border-pink-600' data-aos="fade-in">
                {{ text.title }}
            </p>
            <p className='py-3 text-[#112240] font-medium dark:text-[#f9b82c] dark:font-normal' data-aos="fade-in">{{ text.subtitle }}</p>
        </div>

        <div className='flex bg-slate-300 dark:bg-[#112240] bg-cover px-8 py-12 md:bg-transparent dark:md:bg-transparent md:p-0 mb-12' data-aos="fade-left">
            <a className="hidden md:flex w-[70%] h-[250px] my-auto z-0 overflow-hidden" href='https://seguromovil.com.ar/' target='_blank' rel="noreferrer">
                <div className="bg md:flex w-full h-full my-auto z-0 bg-cover hover:bg-transparent duration-300" :style="{'background-image': 'url(' + Assurant + ')', 'background-position': 'center center'}"/>
            </a>
            <div className="flex flex-col md:w-[60%] py-4">
                <div className="flex flex-col relative top-[-35px] text-right">
                    <span className="text-[#f9b82c] dark:text-[#64ffda] text-sm font-medium">{{ text.work05.subtitle }}</span>
                    <h3 className=" text-2xl font-semibold">{{ text.work05.title }}</h3>
                </div>
                <div className="md:p-4 md:w-[130%] relative md:right-[30%]  rounded md:bg-slate-300 dark:md:bg-[#112240] z-10">
                    <p className=" text-sm text-justify font-medium dark:font-normal">
                        {{ text.work05.description }}
                    </p>
                </div>
                <div className="flex md:w-[130%] relative md:right-[30%] z-10 pt-4">
                    <ul className="flex flex-wrap md:justify-end text-sm font-medium text-[#4a6087] dark:text-slate-400" :style="{'-webkit-text-stroke': '0.1px black'}">
                        <li className="md:pl- pr-4 md:pr-0 dark:text-[#06a608]"> <p>React + Vite</p> </li>
                        <li className="md:pl-4 pr-4 md:pr-0 dark:text-[#06a608] text-shadow: 8px 8px 8px rgb(0, 0, 0);"> <p>React hooks</p> </li>
                        <li className="md:pl-4 pr-4 md:pr-0 dark:text-[#06a608]"> <p>Css</p> </li>
                        <li className="md:pl-4 pr-4 md:pr-0 dark:text-[#06a608]"> <p>Material-UI</p> </li>
                        <li className="md:pl-4 pr-4 md:pr-0 dark:text-[#06a608]"> <p>Axios</p> </li>
                        <li className="md:pl-4 pr-4 md:pr-0 dark:text-[#06a608]"> <p>Aos</p> </li>
                        <li className="md:pl-4 pr-4 md:pr-0 dark:text-[#06a608]"> <p>Million</p> </li>
                        <li className="md:pl-4 pr-4 md:pr-0 dark:text-[#06a608]"> <p>Mercado Pago</p> </li>
                        <li className="md:pl-4 pr-4 md:pr-0 dark:text-[#06a608]"> <p>Google Captcha</p> </li>
                    </ul>
                </div>
                <div className="flex relative bottom-[-20px] justify-end">
                    <a className='flex justify-between items-center dark:text-white pl-4 hover:text-pink-600 dark:hover:text-pink-600 duration-300' href='https://seguromovil.com.ar/' target='_blank' rel="noreferrer"> 
                        <fa icon="arrow-up-right-from-square" class="fa-lg" />
                    </a>
                </div>
            </div>
        </div>

        <div className='flex bg-slate-300 dark:bg-[#112240] bg-cover px-8 py-12 md:bg-transparent dark:md:bg-transparent md:p-0 mb-12' data-aos="fade-right">
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
                <div className="bg md:flex w-full h-full my-auto z-0 bg-cover hover:bg-transparent duration-300" :style="{'background-image': 'url(' + Countries + ')', 'background-position': 'center center'}"/>
            </a>
        </div>

        <div className='flex bg-slate-300 dark:bg-[#112240] bg-cover px-8 py-12 md:bg-transparent dark:md:bg-transparent md:p-0 mb-12' data-aos="fade-left">
            <a className="hidden md:flex w-[70%] h-[250px] my-auto z-0 overflow-hidden" href='https://somosedison.com/' target='_blank' rel="noreferrer">
                <div className="bg md:flex w-full h-full my-auto z-0 bg-cover hover:bg-transparent duration-300 bg-bottom" :style="{'background-image': 'url(' + Edison + ')'}"/>
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

        <div className='flex bg-slate-300 dark:bg-[#112240] bg-cover px-8 py-12 md:bg-transparent dark:md:bg-transparent md:p-0 mb-12' data-aos="fade-right">
            <div className="flex flex-col md:w-[60%] py-4">
                <div className="flex flex-col relative top-[-35px]">
                    <span className="text-[#f9b82c] dark:text-[#64ffda] text-sm font-medium">{{ text.work03.subtitle }}</span>
                    <h3 className=" text-2xl font-semibold">{{ text.work03.title }}</h3>
                </div>
                <div className="md:p-4 md:w-[130%] rounded md:bg-slate-300 dark:md:bg-[#112240] z-10">
                    <p className=" text-sm text-justify font-medium dark:font-normal">
                        {{ text.work03.description }}
                    </p>
                </div>
                <div className="flex md:w-[130%] z-10 pt-4">
                    <ul className="flex flex-wrap text-sm font-medium text-[#4a6087] dark:text-slate-400" :style="{'-webkit-text-stroke': '0.1px black'}">
                        <li className="md:pl- pr-4 md:pr-0 dark:text-[#06a608]"> <p>React</p> </li>
                        <li className="md:pl-4 pr-4 md:pr-0 dark:text-[#06a608] text-shadow: 8px 8px 8px rgb(0, 0, 0);"> <p>Vite</p> </li>
                        <li className="md:pl-4 pr-4 md:pr-0 dark:text-[#06a608]"> <p>Redux toolkit</p> </li>
                        <li className="md:pl-4 pr-4 md:pr-0 dark:text-[#06a608]"> <p>Nodejs</p> </li>
                        <li className="md:pl-4 pr-4 md:pr-0 dark:text-[#06a608]"> <p>React-Query</p> </li>
                        <li className="md:pl-4 pr-4 md:pr-0 dark:text-[#06a608]"> <p>Prisma</p> </li>
                        <li className="md:pl-4 pr-4 md:pr-0 dark:text-[#06a608]"> <p>Material-UI</p> </li>
                        <li className="md:pl-4 pr-4 md:pr-0 dark:text-[#06a608]"> <p>Sass</p> </li>
                        <li className="md:pl-4 pr-4 md:pr-0 dark:text-[#06a608]"> <p>SQL</p> </li>
                        <li className="md:pl-4 pr-4 md:pr-0 dark:text-[#06a608]"> <p>AWS</p> </li>
                        <li className="md:pl-4 pr-4 md:pr-0 dark:text-[#06a608]"> <p>S3</p> </li>
                        <li className="md:pl-4 pr-4 md:pr-0 dark:text-[#06a608]"> <p>EC2</p> </li>
                    </ul>
                </div>
            </div>
            <a className="hidden md:flex w-[70%] h-[250px] my-auto z-0 overflow-hidden" target='_blank' rel="noreferrer">
                <div className="bg md:flex w-full h-full my-auto z-0 bg-cover hover:bg-transparent duration-300 bg-right" :style="{'background-image': 'url(' + Munia + ')'}"/>
            </a>
        </div>

        <div className='flex bg-slate-300 dark:bg-[#112240] bg-cover px-8 py-12 md:bg-transparent dark:md:bg-transparent md:p-0 mb-12' data-aos="fade-left">
            <a className="hidden md:flex w-[70%] h-[250px] my-auto z-0 overflow-hidden" target='_blank' rel="noreferrer">
                <div className="bg md:flex w-full h-full my-auto z-0 bg-cover hover:bg-transparent duration-300 bg-center" :style="{'background-image': 'url(' + Indian + ')'}"/>
            </a>
            <div className="flex flex-col md:w-[60%] py-4">
                <div className="flex flex-col relative top-[-35px] text-right">
                    <span className="text-[#f9b82c] dark:text-[#64ffda] text-sm font-medium">{{ text.work04.subtitle }}</span>
                    <h3 className=" text-2xl font-semibold">{{ text.work04.title }}</h3>
                </div>
                <div className="md:p-4 md:w-[130%] relative md:right-[30%]  rounded md:bg-slate-300 dark:md:bg-[#112240] z-10">
                    <p className=" text-sm text-justify font-medium dark:font-normal">
                        {{ text.work04.description }}
                    </p>
                </div>
                <div className="flex md:w-[130%] relative md:right-[30%] z-10 pt-4">
                    <ul className="flex flex-wrap md:justify-end text-sm font-medium text-[#4a6087] dark:text-slate-400" :style="{'-webkit-text-stroke': '0.1px black'}">
                        <li className="md:pl- pr-4 md:pr-0 dark:text-[#06a608]"> <p>React</p> </li>
                        <li className="md:pl-4 pr-4 md:pr-0 dark:text-[#06a608] text-shadow: 8px 8px 8px rgb(0, 0, 0);"> <p>Vite</p> </li>
                        <li className="md:pl-4 pr-4 md:pr-0 dark:text-[#06a608]"> <p>Redux toolkit</p> </li>
                        <li className="md:pl-4 pr-4 md:pr-0 dark:text-[#06a608]"> <p>Nodejs</p> </li>
                        <li className="md:pl-4 pr-4 md:pr-0 dark:text-[#06a608]"> <p>React-Query</p> </li>
                        <li className="md:pl-4 pr-4 md:pr-0 dark:text-[#06a608]"> <p>Sequelize</p> </li>
                        <li className="md:pl-4 pr-4 md:pr-0 dark:text-[#06a608]"> <p>Css</p> </li>
                        <li className="md:pl-4 pr-4 md:pr-0 dark:text-[#06a608]"> <p>Material-UI</p> </li>
                        <li className="md:pl-4 pr-4 md:pr-0 dark:text-[#06a608]"> <p>Express</p> </li>
                        <li className="md:pl-4 pr-4 md:pr-0 dark:text-[#06a608]"> <p>MongoDB</p> </li>
                        <li className="md:pl-4 pr-4 md:pr-0 dark:text-[#06a608]"> <p>Mongoose</p> </li>
                        <li className="md:pl-4 pr-4 md:pr-0 dark:text-[#06a608]"> <p>Bootstrap</p> </li>
                        <li className="md:pl-4 pr-4 md:pr-0 dark:text-[#06a608]"> <p>Passport</p> </li>
                        <li className="md:pl-4 pr-4 md:pr-0 dark:text-[#06a608]"> <p>Railway</p> </li>
                    </ul>
                </div>
                <div className="flex relative bottom-[-20px] justify-end">
                    <a className='flex justify-between items-center dark:text-white pl-4 hover:text-pink-600 dark:hover:text-pink-600 duration-300' href='https://www.indianandco.com.ar/' target='_blank' rel="noreferrer"> 
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
import Assurant from '../assets/Assurant.png'
import Countries from '../assets/PI-COUNTRIES.png'
import Munia from '../assets/Munia.png'
import Indian from '../assets/Indian.png'

export default {
    data() {
        return {
            Edison,
            Countries,
            Munia,
            Indian,
            Assurant,
            eng: {
                title: 'Work',
                subtitle: '// Check out some of my recent work',
                work01: {
                    title: 'Countries app',
                    subtitle: 'Project',
                    description: 'Project of all the countries in the world. On the home page, I fetched all the countries from an API along with their respective filters, pagination, and search bar to find the desired country as quickly as possible. Then, there is a detail page for each country that displays the specific details, and it also includes their respective activities created through a form with appropriate validations.'
                },
                work02: {
                    title: 'Edison',
                    subtitle: 'Work experience',
                    description: 'During my internship at Edison company, I had the opportunity to participate in the development of a new version of their website using various technologies (ReactJs, Nodejs, Airtable, Express, Bootstrap, Tailwind). In this project, we worked on implementing payment gateways with both national and international methods. We created the Marketplace and added sections such as forms with their respective validations, as well as informational pages. Additionally, we successfully applied the corresponding design to all the different components of the site.'
                },
                work03: {
                    title: 'Munia',
                    subtitle: 'Work experience',
                    description: 'In my work experience at Munia company, we successfully developed a platform from the ground up. The goal was to allow users to log in and register as a company, patient, professional, or administrator. I implemented the Login, Register, tables for rescheduling, confirming or rejecting appointments, a Dashboard displaying all statistics, and the connection to the backend using Redux Toolkit. Additionally, I fixed certain components that were incomplete or re-created them.'
                },
                work04: {
                    title: 'Indian&Co',
                    subtitle: 'Work experience',
                    description: 'This project is characterized by the implementation of a database, a secure payment gateway, efficient forms, an attractive marketplace, an intuitive shopping cart, login and registration functions, a comprehensive dashboard for page management, and a wide variety of components and views. These achievements span from data management to user experience, providing a comprehensive and versatile system.'
                },
                work05: {
                    title: 'Assurant',
                    subtitle: 'Work',
                    description: 'Summary of the project for the Movistar company on mobile phone insurance. In general areas, it includes forms for registration with certain validations, self-manageable frequently asked questions from the database, and in state consultation, a status bar for product tracking with its details and for payment with Mercado Pago integration.'
                }
            }, 
            es: {
                title: 'Proyectos',
                subtitle: '// Mira algunos de mis proyectos más recientes',
                work01: {
                    title: 'Aplicación de paises',
                    subtitle: 'Proyecto',
                    description: 'Proyecto de todos los paises del mundo, en el home me traje todos los paises de una api y con sus respectivos filtros, paginado y barra de busqueda para encontrar el pais que buscas lo antes posible. Luego un detail de cada pais que aparece los detalles de cada uno con sus respectivas activides creadas en un formulario con sus respectivas validaciones.'
                },
                work02: {
                    title: 'Edison',
                    subtitle: 'Práctica laboral',
                    description: 'Durante mi pasantía laboral en la empresa de Edison, tuve la oportunidad de participar en el desarrollo de una nueva versión de su sitio web utilizando diferentes tecnologías (ReactJs, Nodejs, Airtable, Express, Bootstrap, Tailwind ). En este proyecto, trabajamos en la implementación de pasarelas de pago con métodos nacionales e internacionales, creamos el Marketplace y añadimos secciones como formularios con sus respectivas validaciones, así como páginas informativas. También logramos aplicar su diseño correspondiente a todos los diferentes componentes del sitio.'
                },
                work03: {
                    title: 'Munia',
                    subtitle: 'Práctica laboral',
                    description: 'En mi práctica laboral en la empresa Munia, logramos llevar a cabo una plataforma desde las bases. La idea era poder ingresar y registrarse tanto como empresa, paciente, profesional o administrador. Llevé adelante el Login, Register, tablas para reprogramar, confirmar o rechazar turnos, Dashboard de todas las estadísticas, la conexión con el backend de la mano de Redux Toolkit, arreglar ciertos componentes dejados a medias o volverlos a hacer.'
                },
                work04: {
                    title: 'Indian&Co',
                    subtitle: 'Proyecto freelance (vendido)',
                    description: 'Este proyecto se caracteriza por la implementación de una base de datos, una segura pasarela de pagos, formularios eficientes, un atractivo marketplace, un carrito de compras intuitivo, funciones de login y registro, un completo dashboard para administrar la página y una amplia variedad de componentes y vistas. Estos logros abarcan desde la gestión de datos hasta la experiencia del usuario, proporcionando un sistema integral y versátil.'
                },
                work05: {
                    title: 'Assurant',
                    subtitle: 'Trabajo',
                    description: 'Resumen del proyecto para la compañía de Movistar sobre aseguradora de celulares. En ámbitos generales cuenta con formularios para registros por ciertas validaciones, preguntas frecuentes autogestionables desde la base de datos y en consulta de estados una barra de estados para el seguimiento del producto con sus detalles y para pagar con la integración de Mercado Pago.'
                }
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