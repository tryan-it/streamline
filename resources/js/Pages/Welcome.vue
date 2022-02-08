<template>

    <Head title="Welcome" />

    <!-- Section 1 -->
    <section class="w-full flex-grow px-3 antialiased bg-blue-400 lg:px-6">
        <div class="mx-auto max-w-7xl">
            <nav class="flex items-center w-full h-24 select-none">
                <div class="relative flex flex-wrap items-center justify-between w-full h-24 mx-auto font-medium md:justify-center">
                    <a href="/" class="md:w-1/4 py-4 pl-6 pr-4 md:pl-4 md:py-0">
                        <span class="p-1 text-xl font-black leading-none text-white select-none"><span>Streamline Waxing</span><span class="text-indigo-300"></span></span>
                    </a>
                    <div class="fixed top-0 left-0 z-40 items-center hidden w-full h-full p-3 text-xl bg-gray-900 bg-opacity-50 md:text-sm lg:text-base md:w-3/4 md:bg-transparent md:p-0 md:relative md:flex">
                        <div class="flex-col w-full h-auto h-full overflow-hidden bg-white rounded-lg select-none md:bg-transparent md:rounded-none md:relative md:flex md:flex-row md:overflow-auto">
                            <div class="flex flex-col items-center justify-center w-full h-full mt-12 text-center text-indigo-700 md:text-indigo-200 md:w-2/3 md:mt-0 md:flex-row md:items-center">
                                <!-- <a href="#" class="inline-block px-4 py-2 mx-2 font-medium text-left text-indigo-700 md:text-white md:px-0 lg:mx-3 md:text-center">Home</a>
                                <a href="#" class="inline-block px-0 px-4 py-2 mx-2 font-medium text-left md:px-0 hover:text-indigo-800 md:hover:text-white lg:mx-3 md:text-center">Services</a>
                                <a href="#" class="inline-block px-0 px-4 py-2 mx-2 font-medium text-left md:px-0 hover:text-indigo-800 md:hover:text-white lg:mx-3 md:text-center">Contact</a> -->
                            </div>
                            <div class="flex flex-col items-center justify-end w-full h-full pt-4 md:w-1/3 md:flex-row md:py-0 hidden">
                                <a href="#_" class="w-full pl-6 mr-0 text-indigo-200 hover:text-white md:pl-0 md:mr-3 lg:mr-5 md:w-auto">Sign In</a>
                                <a href="#_" class="inline-flex items-center justify-center px-4 py-2 mr-1 text-base font-medium leading-6 text-indigo-600 whitespace-no-wrap transition duration-150 ease-in-out bg-white border border-transparent rounded-full hover:bg-white focus:outline-none focus:border-indigo-700 focus:shadow-outline-indigo active:bg-indigo-700">Register</a>
                            </div>
                        </div>
                    </div>
                    <!-- <div @click="showMenu = !showMenu" class="absolute right-0 z-50 flex flex-col items-end w-10 h-10 p-2 mr-4 rounded-full cursor-pointer md:hidden hover:bg-gray-900 hover:bg-opacity-10" :class="{ 'text-gray-400': showMenu, 'text-gray-100': !showMenu }">
                        <svg class="w-6 h-6" x-show="!showMenu" fill="none" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" viewBox="0 0 24 24" stroke="currentColor" x-cloak="">
                            <path d="M4 6h16M4 12h16M4 18h16"></path>
                        </svg>
                        <svg class="w-6 h-6" x-show="showMenu" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg" x-cloak="">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M6 18L18 6M6 6l12 12"></path>
                        </svg>
                    </div> -->
                </div>
            </nav>
            <div class="container py-32 mx-auto text-center sm:px-4">

                <h1 class="text-4xl font-extrabold leading-10 tracking-tight text-white sm:text-5xl sm:leading-none md:text-6xl xl:text-7xl"><span class="block">Streamline your life</span></h1>
                <h2 class="text-3xl"><span class="relative inline-block mt-3  text-slate-300">Call today to book an appointment!</span></h2>
                <div class="max-w-lg mx-auto mt-6 text-sm text-center text-indigo-200 md:mt-12 sm:text-base md:max-w-xl md:text-lg xl:text-xl">
                    <div class="flex-col text-white relative block">
                        <address>
                            (612) 518-5065<br>
                            <br>
                            135 Bridge St Ste A<br>
                            Arroyo Grande, CA 93420<br>
                        </address>
                    </div>
                </div>
                <div class="relative flex flex-row items-center max-w-md mx-auto mt-12 overflow-hidden text-center">
                    <div class="flex-col"><iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d815.8468565093901!2d-120.57876539702272!3d35.122004193995835!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x80ec5e8894318541%3A0xca2f9949ac0636ce!2s135%20Bridge%20St%20a%2C%20Arroyo%20Grande%2C%20CA%2093420!5e0!3m2!1sen!2sus!4v1644355895920!5m2!1sen!2sus" width="600" height="450" style="border:0;" allowfullscreen="" loading="lazy"></iframe></div>
                    <!-- <input type="text" name="email" placeholder="Email Address" class="w-full h-12 px-6 py-2 font-medium text-indigo-800 focus:outline-none">
                    <span class="relative top-0 right-0 block">
                        <button type="button" class="inline-flex items-center w-32 h-12 px-8 text-base font-bold leading-6 text-white transition duration-150 ease-in-out bg-gray-400 border border-transparent hover:bg-indigo-700 focus:outline-none active:bg-indigo-700">
                            Sign Up
                        </button>
                    </span> -->
                </div>
                <!-- <div class="mt-8 text-sm text-indigo-100">By signing up, you agree to our terms and services.</div> -->
            </div>
        </div>
    </section>

    <Footer />
</template>


<script>
import { Head, Link } from '@inertiajs/inertia-vue3';
import ApplicationLogo from '@/Components/ApplicationLogo.vue';
import Footer from '@/Components/Footer.vue';

export default {
    components: {
      Head,
      Link,
      ApplicationLogo,
      Footer,
    },
    props: {
        canLogin: Boolean,
        canRegister: Boolean,
        laravelVersion: String,
        phpVersion: String,
    },
}
</script>
