<script setup>
import { ref } from 'vue';

const skills = ref([
    'CI/CD',
    'CSS',
    'Data Analysis',
    'Data Visualization',
    'Docker',
    'ETL Processes',
    'HTML',
    'Java',
    'JavaScript',
    'Laravel',
    'MySQL',
    'Node.js',
    'Perl',
    'PHP',
    'Pipeline Automation',
    'PostgreSQL',
    'Python',
    'Redis',
    'Reporting',
    'REST APIs',
    'Software Architecture',
    'Tableau',
    'Tailwind',
    'Vue.js',
])
</script>

<template>

    <div class="bg-gray-100">

        <section class="py-10 md:py-16">

            <div class="container max-w-screen-xl mx-auto px-4">

                <nav class="flex items-center justify-between mb-40">
                    <img src="/images/navbar-logo.png" alt="Logo">

                    <a
                        class="px-7 py-3 md:px-9 md:py-4 bg-white font-medium md:font-semibold text-gray-700 text-md rounded-md
                         hover:bg-gray-700 hover:text-white transition ease-linear duration-500"
                        href="/Resume.pdf"
                        download
                    >
                        Get my Resume
                    </a>
                </nav>

                <div class="text-center">
                    <div class="flex justify-center mb-16">
                        <img src="/images/me.jpg" alt="Image" class="object-cover rounded-full w-96 h-96">
                    </div>

                    <h5 class="font-medium text-gray-600 text-lg md:text-3xl uppercase mb-2">Nick Nash</h5>

                    <a class="font-medium text-gray-700 text-lg md:text-2xl mb-8 hover:cursor-pointer hover:underline" href="mailto:nicknashdev@gmail.com">nicknashdev@gmail.com</a>

                    <h1 class="font-normal text-gray-900 text-4xl md:text-7xl leading-none mb-8">Full Stack Developer / Data Analyst</h1>

                    <p class="font-normal text-gray-600 text-md md:text-xl mb-16">I have a passion for software and honing my expertise in front-end & back-end web development and data analysis.</p>

                    <a
                        class="px-7 py-3 md:px-9 md:py-4 font-medium md:font-semibold bg-gray-700 text-gray-50 text-sm rounded-md hover:bg-gray-50 hover:text-gray-700 transition ease-linear duration-500"
                        href="/Resume.pdf"
                        download
                    >
                        Hire me
                    </a>
                </div>

            </div>

        </section>

        <section class="py-10 md:py-16">

            <div class="container max-w-screen-xl mx-auto px-4">

                <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-2 gap-6">
                    <div class="bg-gray-50 px-8 py-10 rounded-md">
                        <div class="w-20 py-6 flex justify-center bg-gray-100 rounded-md mb-4">
                            <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-8 h-8">
                                <path stroke-linecap="round" stroke-linejoin="round" d="M2.25 21h19.5m-18-18v18m10.5-18v18m6-13.5V21M6.75 6.75h.75m-.75 3h.75m-.75 3h.75m3-6h.75m-.75 3h.75m-.75 3h.75M6.75 21v-3.375c0-.621.504-1.125 1.125-1.125h2.25c.621 0 1.125.504 1.125 1.125V21M3 3h12m-.75 4.5H21m-3.75 3.75h.008v.008h-.008v-.008Zm0 3h.008v.008h-.008v-.008Zm0 3h.008v.008h-.008v-.008Z" />
                            </svg>

                        </div>

                        <h4 class="font-medium text-gray-700 text-lg mb-4">High experience</h4>

                        <p class="font-normal text-gray-500 text-md">With nearly a decade's worth of professional software development & data analysis experience, I provide highly efficient, well-tested software, tools, and reports for clients.</p>
                    </div>
                    
                    <div class="bg-gray-50 px-8 py-10 rounded-md">
                        <div class="w-20 py-6 flex justify-center bg-gray-100 rounded-md mb-4">
                            <!-- <i class="fa-sharp fa-solid fa-check"></i> -->
                            <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-8 h-8">
                                <path stroke-linecap="round" stroke-linejoin="round" d="M10.125 2.25h-4.5c-.621 0-1.125.504-1.125 1.125v17.25c0 .621.504 1.125 1.125 1.125h12.75c.621 0 1.125-.504 1.125-1.125v-9M10.125 2.25h.375a9 9 0 0 1 9 9v.375M10.125 2.25A3.375 3.375 0 0 1 13.5 5.625v1.5c0 .621.504 1.125 1.125 1.125h1.5a3.375 3.375 0 0 1 3.375 3.375M9 15l2.25 2.25L15 12" />
                            </svg>


                        </div>

                        <h4 class="font-medium text-gray-700 text-lg mb-4">Success projects</h4>

                        <p class="font-normal text-gray-500 text-md">Some of largest successes I have in my career are building proprietary solutions - the largest being an in-house e-Signature platform and a custom collections module, both of which service tens of thousands of customers every year.</p>
                    </div>
                </div>

            </div>

        </section>

        <section class="py-10 md:py-16">

            <div class="container max-w-screen-xl mx-auto px-4">

                <div class="flex flex-col lg:flex-row justify-between">
                    <div class="mb-10 lg:mb-0">
                        <h1 class="font-medium text-gray-700 text-3xl md:text-4xl mb-5">Portfolio</h1>

                        <p class="font-normal text-gray-500 text-xs md:text-base">I have brought here my biggest and favorite works <br> as a professional.</p>
                    </div>

                    <div class="space-y-24">
                        <div class="flex space-x-6">
                            <h1 class="font-normal text-gray-700 text-3xl md:text-4xl">01</h1>

                            <span class="w-28 h-0.5 bg-gray-300 mt-5"></span>

                            <div>
                                <h1 class="font-normal text-gray-700 text-3xl md:text-4xl mb-5">e-Signature Platform</h1>

                                <p class="font-normal text-gray-500 text-sm md:text-base">A proprietary platform that allows a business entity to create, <br>capture, and manage customers' document signings.</p>
                            </div>
                        </div>
                        
                        <div class="flex space-x-6">
                            <h1 class="font-normal text-gray-700 text-3xl md:text-4xl">02</h1>

                            <span class="w-28 h-0.5 bg-gray-300 mt-5"></span>

                            <div>
                                <h1 class="font-normal text-gray-700 text-3xl md:text-4xl mb-5">Collections Module</h1>

                                <p class="font-normal text-gray-500 text-sm md:text-base">A proprietary API-based tool with an admin interface that allows users to <br>contact, record, and collect on financial products.</p>
                            </div>
                        </div>

                        <div class="flex space-x-6">
                            <h1 class="font-normal text-gray-700 text-3xl md:text-4xl">03</h1>

                            <span class="w-28 h-0.5 bg-gray-300 mt-5"></span>

                            <div>
                                <h1 class="font-normal text-gray-700 text-3xl md:text-4xl mb-5">Public Demo Dashboard</h1>

                                <p class="font-normal text-gray-500 text-sm md:text-base">A simple, demo dashboard built for demo and educational purposes.<br> <a class="underline hover:text-blue-500" target="_blank" href="https://public.tableau.com/app/profile/nicholas.nash/viz/VideoGameSalesAnalysis_16873118916600/video_game_story?publish=yes">Click here</a> to view the dashboard.</p>
                            </div>
                        </div>
                    </div>
                </div>

            </div>

        </section>

        <section class="py-10 md:py-16">

            <div class="container max-w-screen-xl mx-auto px-4">

                <h1 class="font-medium text-gray-700 text-3xl md:text-4xl mb-5">Skills</h1>

                <p class="font-normal text-gray-500 text-xs md:text-base">
                    I have accrued many skills over the years, but here <br>are a few of my favorites.
                </p>

                <div class="flex flex-wrap gap-3 justify-center px-2 md:px-4 my-6 lg:my-12">
                    <div
                        v-for="skill in skills"
                        :key="skill"
                        class="px-2 py-1 bg-gray-200 rounded hover:text-indigo-600 hover:cursor-pointer dark:bg-gray-600/50 dark:text-gray-50"
                    >
                        {{ skill }}
                    </div>
                </div>

            </div>

        </section>

        <section class="py-10 md:py-16">

            <div class="container max-w-screen-xl mx-auto px-4 py-6 bg-gray-50 rounded-md">

                <h1 class="font-medium text-gray-700 text-3xl md:text-4xl mb-5">Experience</h1>

                <p class="font-normal text-gray-500 text-xs md:text-base mb-20">Below is a summary of the places I have worked</p>

                <div class="flex flex-col lg:flex-row justify-between">
                    <div class="space-y-8 md:space-y-16 mb-16 md:mb-0">
                        <h6 class="font-medium text-gray-400 text-base uppercase underline">Company</h6>

                        <p class="font-semibold text-gray-600 text-base">Cash Express, LLC <span class="font-normal text-gray-300">/ Tennessee</span></p>

                        <p class="font-semibold text-gray-600 text-base">Cash Express, LLC <span class="font-normal text-gray-300">/ Tennessee</span></p>

                        <p class="font-semibold text-gray-600 text-base">Averitt Express <span class="font-normal text-gray-300">/ Tennessee</span></p>
                    </div>

                    <div class="space-y-8 md:space-y-16 mb-16 md:mb-0 md:mt-12">
                        <h6 class="font-medium text-gray-400 text-base uppercase underline">Position</h6>

                        <p class="font-normal text-gray-400 text-base">Team Lead Software Engineer</p>

                        <p class="font-normal text-gray-400 text-base">Software Engineer</p>

                        <p class="font-normal text-gray-400 text-base">Programmer / Analyst</p>
                    </div>

                    <div class="space-y-8 md:space-y-16 md:mt-12">
                        <h6 class="font-medium text-gray-400 text-base uppercase underline">Year</h6>

                        <p class="font-normal text-gray-400 text-base">2020 - current</p>

                        <p class="font-normal text-gray-400 text-base">2017 - 2020</p>

                        <p class="font-normal text-gray-400 text-base">2017</p>
                    </div>
                </div>
                
            </div>

        </section>

    </div>

</template>
