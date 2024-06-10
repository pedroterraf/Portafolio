<template>
          <div id='skills' className='w-full md:w-[90%] min-h-screen mx-auto flex bg-slate-100 dark:bg-[#0a192f] text-[#0a192f] dark:text-gray-300'>
          <div className='max-w-[750px] m-auto py-4 px-5 flex flex-col justify-center w-full h-full'>
              <div>
                  <p className='text-4xl font-bold inline border-b-4 border-pink-600 ' data-aos="fade-in">{{ text.title }}</p>
                  <p className='py-4 text-[#f9b82c] font-medium dark:font-normal' data-aos="fade-in">{{ text.subtitle }}</p>
              </div>
    
              <div className='w-full grid grid-cols-2 sm:grid-cols-3 gap-4 text-center py-8 font-bold dark:font-normal' data-aos="fade-in">
                  <div className='bg-slate-200 dark:bg-[#0a192f] shadow-md shadow-[#040c16] py-2 hover:scale-110 duration-500'>
                      <img className='w-20 mx-auto' :src='HTML' alt="HTML icon" />
                      <p className='mt-4'>HTML</p>
                  </div>
                  <div className='bg-slate-200 dark:bg-[#0a192f] shadow-md shadow-[#040c16] py-2 hover:scale-110 duration-500'>
                      <img className='w-20 mx-auto' :src='CSS' alt="HTML icon" />
                      <p className='mt-4'>CSS</p>
                  </div>
                  <div className='bg-slate-200 dark:bg-[#0a192f] shadow-md shadow-[#040c16] py-2 hover:scale-110 duration-500'>
                      <img className='w-20 mx-auto' :src='JavaScript' alt="HTML icon" />
                      <p className='mt-4'>JAVASCRIPT</p>
                  </div>
                  <div className='bg-slate-200 dark:bg-[#0a192f] shadow-md shadow-[#040c16] py-2 hover:scale-110 duration-500'>
                      <img className='w-20 mx-auto' :src='typescript' alt="HTML icon" />
                      <p className='mt-4'>Typescript</p>
                  </div>
                  <div className='bg-slate-200 dark:bg-[#0a192f] shadow-md shadow-[#040c16] py-2 hover:scale-110 duration-500'>
                      <img className='w-20 mx-auto' :src='ReactImg' alt="HTML icon" />
                      <p className='mt-4'>REACT</p>
                  </div>
                  <div className='bg-slate-200 dark:bg-[#0a192f] shadow-md shadow-[#040c16] py-2 hover:scale-110 duration-500'>
                      <img className='w-20 mx-auto' :src='VueImg' alt="HTML icon" />
                      <p className='mt-4'>VUE</p>
                  </div>
                  <div className='bg-slate-200 dark:bg-[#0a192f] shadow-md shadow-[#040c16] py-2 hover:scale-110 duration-500'>
                      <img className='w-20 mx-auto' :src='Git' alt="HTML icon" />
                      <p className='mt-4'>GIT</p>
                  </div>
                  <div className='bg-slate-200 dark:bg-[#0a192f] shadow-md shadow-[#040c16] py-2 hover:scale-110 duration-500'>
                      <img className='w-20 mx-auto' :src='Node' alt="HTML icon" />
                      <p className='mt-4'>NODE JS</p>
                  </div>
                  <div className='bg-slate-200 dark:bg-[#0a192f] shadow-md shadow-[#040c16] py-2 hover:scale-110 duration-500'>
                      <img className='w-20 mx-auto' :src='Redux' alt="HTML icon" />
                      <p className='mt-4'>Redux</p>
                  </div>
                  <div className='bg-slate-200 dark:bg-[#0a192f] shadow-md shadow-[#040c16] py-2 hover:scale-110 duration-500'>
                      <img className='w-20 mx-auto' :src='PostgreSQL' alt="HTML icon" />
                      <p className='mt-4'>POSTGRESQL</p>
                  </div>
                  <div className='bg-slate-200 dark:bg-[#0a192f] shadow-md shadow-[#040c16] py-2 hover:scale-110 duration-500'>
                      <img className='w-20 mx-auto' :src='NextJs' alt="HTML icon" />
                      <p className='mt-4'>Next</p>
                  </div>
                  <div className='bg-slate-200 dark:bg-[#0a192f] shadow-md shadow-[#040c16] py-2 hover:scale-110 duration-500'>
                      <img className='w-20 mx-auto' :src='vitejs' alt="HTML icon" />
                      <p className='mt-4'>Vite</p>
                  </div>
                  <div className='bg-slate-200 dark:bg-[#0a192f] shadow-md shadow-[#040c16] py-2 hover:scale-110 duration-500'>
                      <img className='w-20 mx-auto' :src='bootstrap' alt="HTML icon" />
                      <p className='mt-4'>Bootstrap</p>
                  </div>
                  <div className='bg-slate-200 dark:bg-[#0a192f] shadow-md shadow-[#040c16] py-2 hover:scale-110 duration-500'>
                      <img className='w-20 mx-auto' :src='materialui' alt="HTML icon" />
                      <p className='mt-4'>Material-UI</p>
                  </div>
                  <div className='bg-slate-200 dark:bg-[#0a192f] shadow-md shadow-[#040c16] py-2 hover:scale-110 duration-500'>
                      <img className='w-20 mx-auto' :src='sass' alt="HTML icon" />
                      <p className='mt-4'>Sass</p>
                  </div>
                  <div className='bg-slate-200 dark:bg-[#0a192f] shadow-md shadow-[#040c16] py-2 hover:scale-110 duration-500'>
                      <img className='w-20 mx-auto' :src='express' alt="HTML icon" />
                      <p className='mt-4'>Express</p>
                  </div>
                  <div className='bg-slate-200 dark:bg-[#0a192f] shadow-md shadow-[#040c16] py-2 hover:scale-110 duration-500'>
                      <img className='w-20 mx-auto' :src='sequelize' alt="HTML icon" />
                      <p className='mt-4'>Sequelize</p>
                  </div>
                  <div className='bg-slate-200 dark:bg-[#0a192f] shadow-md shadow-[#040c16] py-2 hover:scale-110 duration-500'>
                      <img className='w-20 mx-auto' :src='aws' alt="HTML icon" />
                      <p className='mt-4'>Aws</p>
                  </div>
                  <div className='bg-slate-200 dark:bg-[#0a192f] shadow-md shadow-[#040c16] py-2 hover:scale-110 duration-500'>
                      <img className='w-20 mx-auto' :src='vercel' alt="HTML icon" />
                      <p className='mt-4'>Vercel</p>
                  </div>
                  <div className='bg-slate-200 dark:bg-[#0a192f] shadow-md shadow-[#040c16] py-2 hover:scale-110 duration-500'>
                      <img className='w-20 mx-auto' :src='prisma' alt="HTML icon" />
                      <p className='mt-4'>Prisma</p>
                  </div>
                  <div className='bg-slate-200 dark:bg-[#0a192f] shadow-md shadow-[#040c16] py-2 hover:scale-110 duration-500'>
                      <img className='w-20 mx-auto' :src='storybook' alt="HTML icon" />
                      <p className='mt-4'>Storybooks</p>
                  </div>
              </div>
          </div>
        </div>
</template>

<script>
import HTML from '../assets/html.png';
import CSS from '../assets/css.png';
import JavaScript from '../assets/javascript.png';
import ReactImg from '../assets/react.png';
import VueImg from '../assets/vue.png';
import Node from '../assets/node.png';
import Git from '../assets/git.png';
import Redux from '../assets/redux.png';
import PostgreSQL from '../assets/postgres.png';
import NextJs from '../assets/nextjs.png';
import express from '../assets/express.png';
import vitejs from '../assets/vitejs.png';
import typescript from '../assets/typescript.png';
import bootstrap from '../assets/bootstrap.png';
import materialui from '../assets/materialui.png';
import sass from '../assets/sass.png';
import sequelize from '../assets/sequelize.png';
import aws from '../assets/aws.png';
import prisma from '../assets/prisma.png';
import vercel from '../assets/vercel.png';
import storybook from '../assets/storybook.png';

export default {
    data() {
        return {
            HTML,
            CSS,
            JavaScript,
            ReactImg,
            Node,
            Git,
            Redux,
            PostgreSQL,
            VueImg,
            NextJs,
            express,
            vitejs,
            typescript,
            bootstrap,
            materialui,
            sass,
            sequelize,
            aws,
            prisma,
            vercel,
            storybook,
            eng: {
                title: 'Skills',
                subtitle: '// These are the technologies I\'ve worked with',
            },
            es: {
                title: 'Habilidades',
                subtitle: '// Estas son las tecnologías con las que he trabajado',
            },
        }
    },
    computed: {
        text() {
            return this.$store.state.lang === 'en' ? this.eng : this.es
        }
    }
}
</script>