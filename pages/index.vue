
import type { Ornamane } from '#build/components';
<template>
    <section id="banner">
        <div class="container flex items-center min-h-[550px] h-screen max-h-[800px]">
            <div class="flex">
                <div class="w-1/2">
                    <div class="flex flex-col gap-8">
                        <h1 class="heading-1 font-semibold leading-normal">Rizwan Gustama is a <span
                                class="text-primary">web designer </span>and <span class="text-primary">front-end
                                developer</span> </h1>
                        <p class="text-gray">He crafts responsive websites where technologies meet creativity</p>
                    </div>
                    <button class="btn-primary mt-6">Contact Me</button>
                </div>
                <div class="w-1/2 flex justify-end">
                    <div class="relative">
                        <img src="~/assets/images/people.png" alt="images">
                        <button class="flex items-center gap-2.5 py-2 border border-gray px-2 mx-auto">
                            <span class="bg-primary flex h-4 w-4"></span>
                            <p class="text-gray">Currently working on Portfolio</p>
                        </button>
                    </div>

                </div>
            </div>
        </div>
    </section>
    <section id="quote">
        <div class="container">
            <div class="flex justify-center ">
                <div class="flex flex-col">
                    <div id="quote-icon" class="border border-gray p-8">
                        <p class="wrapper-icon">With great power comes great electricity bill</p>
                    </div>
                    <div class="border border-gray p-4 w-fit ml-auto mr-0">
                        <p>- Dr. Who</p>
                    </div>
                </div>

            </div>
        </div>
    </section>

    <section class="py-20">
        <div class="container">
            <div class="flex justify-between">
                <div class="flex items-center gap-4 w-10/12">
                    <h2 class="heading-1"><span class="text-primary">#</span>project</h2>
                    <span class="h-[1px] w-full bg-primary"></span>
                </div>
                <div class="w-2/12 flex justify-end items-center">
                    <button class="flex">
                        <p>View All ~~></p>
                    </button>
                </div>
            </div>
            <div class="grid grid-cols-3 gap-4 pt-12">
                <template v-for="( items, index ) in 3" :key="index">
                    <div class="border border-gray">
                        <img class="w-full" src="~/assets/images/project.png" alt="">
                        <!-- Category -->
                        <ul class="flex gap-2 border-y border-gray p-2">
                            <li>
                                <a href="">HTML</a>
                            </li>
                            <li>
                                <a href="">CSS</a>
                            </li>
                            <li>
                                <a href="">SASS</a>
                            </li>
                            <li>
                                <a href="">Javascript</a>
                            </li>
                        </ul>
                        <!-- title -->
                        <div class="flex flex-col gap-4 p-4">
                            <h2 class="heading-2 font-medium">ChertNodes</h2>
                            <p>Minecraft servers hosting </p>
                            <div class="flex gap-4">
                                <button class="btn-primary">Live</button>
                                <button class="btn-primary">Github</button>
                            </div>

                        </div>

                    </div>
                </template>

            </div>
        </div>
    </section>


    <section id="skill">
        <div class="container">
            <div class="flex justify-between">
                <div class="flex items-center gap-4 w-10/12">
                    <h2 class="heading-1"><span class="text-primary">#</span>skill</h2>
                    <span class="h-[1px] w-full bg-primary"></span>
                </div>
                <div class="w-2/12 flex justify-end items-center">
                    <button class="flex">
                        <p>View All ~~></p>
                    </button>
                </div>
            </div>

            <div class="flex gap-4">
                <div class="w-5/12">
                    <Ornamane />
                </div>
                <div class="grid grid-cols-3 w-7/12 gap-4">
                    <div class="flex flex-col gap-4">
                        <div class="border border-gray h-fit">
                            <div class="border-b border-gray p-2">
                                <h4>Languages</h4>
                            </div>
                            <div class="flex flex-wrap gap-2 p-2">
                                <template v-for="item in 10">
                                    <p>Vuejs</p>
                                </template>
                            </div>
                        </div>
                    </div>

                    <div class="flex flex-col gap-4">
                        <div class="border border-gray h-fit">
                            <div class="border-b border-gray p-2">
                                <h4>Databases</h4>
                            </div>
                            <div class="flex flex-wrap gap-2 p-2">
                                <template v-for="item in 10">
                                    <p>Vuejs</p>
                                </template>
                            </div>
                        </div>
                        <div class="border border-gray h-fit">
                            <div class="border-b border-gray p-2">
                                <h4>Databases</h4>
                            </div>
                            <div class="flex flex-wrap gap-2 p-2">
                                <template v-for="item in 10">
                                    <p>Vuejs</p>
                                </template>
                            </div>
                        </div>
                    </div>

                    <div class="flex flex-col gap-4">
                        <div class="border border-gray h-fit">
                            <div class="border-b border-gray p-2">
                                <h4>Tools</h4>
                            </div>
                            <div class="flex flex-wrap gap-2 p-2">
                                <template v-for="item in 10">
                                    <p>Vuejs</p>
                                </template>
                            </div>
                        </div>
                        <div class="border border-gray h-fit">
                            <div class="border-b border-gray p-2">
                                <h4>Tools</h4>
                            </div>
                            <div class="flex flex-wrap gap-2 p-2">
                                <template v-for="item in 10">
                                    <p>Vuejs</p>
                                </template>
                            </div>
                        </div>
                        <div class="border border-gray h-fit">
                            <div class="border-b border-gray p-2">
                                <h4>Tools</h4>
                            </div>
                            <div class="flex flex-wrap gap-2 p-2">
                                <template v-for="item in 10">
                                    <p>Vuejs</p>
                                </template>
                            </div>
                        </div>
                    </div>

                </div>
            </div>
        </div>
    </section>

    <section id="about-me">
        <div class="container">
            <div class="flex justify-between">
                <div class="flex items-center gap-4 w-10/12">
                    <h2 class="heading-1 whitespace-nowrap"><span class="text-primary">#</span>about-me</h2>
                    <span class="h-[1px] w-full bg-primary"></span>
                </div>
                <div class="w-2/12 flex justify-end items-center">
                    <button class="flex">
                        <p>View All ~~></p>
                    </button>
                </div>
            </div>

            <div class="flex mt-6">
                <div id="content" class="w-1/2">
                    <p>Hello, i’m Elias!</p>
                    <p>
                        I’m a self-taught front-end developer based in Kyiv, Ukraine. I can develop responsive websites from
                        scratch and raise them into modern user-friendly web experiences.
                    </p>
                    <p>
                        Transforming my creativity and knowledge into a websites has been my passion for over a year. I have
                        been helping various clients to establish their presence online. I always strive to learn about the
                        newest technologies and frameworks.
                    </p>
                </div>
                <div class="w-1/2"></div>
            </div>
        </div>
    </section>
</template>

<style>
#content {
    p {
        margin-bottom: 24px;
        line-height: 1.5;
        @apply text-gray;
    }
}
#quote-icon {
    position: relative;

    &:before {
        content: '';
        display: flex;
        position: absolute;
        /* left: 10px;
        top: -10px; */
        font-size: 23px;
        transform: translate(-10px, -200%);
        width: 25px;
        height: 20px;
        background-position: center;
        background-repeat: no-repeat;
        font-family: 'Fira Code';
        background-image: url("data:image/svg+xml,%3Csvg width='26' height='21' viewBox='0 0 26 21' fill='none' xmlns='http://www.w3.org/2000/svg'%3E%3Cpath d='M10.56 15.616C10.56 17.0453 10.0373 18.2507 8.992 19.232C7.968 20.2133 6.72 20.704 5.248 20.704C3.73333 20.704 2.47467 20.2133 1.472 19.232C0.490667 18.2507 0 17.0453 0 15.616C0 14.9333 0.096 14.208 0.288 13.44C0.48 12.672 0.864 11.68 1.44 10.464L6.4 0H11.2L8.544 11.584C9.14133 12.0107 9.62133 12.576 9.984 13.28C10.368 13.9627 10.56 14.7413 10.56 15.616ZM24.8 15.616C24.8 17.0453 24.2773 18.2507 23.232 19.232C22.1867 20.2133 20.9387 20.704 19.488 20.704C18.016 20.704 16.768 20.2133 15.744 19.232C14.7413 18.2507 14.24 17.0453 14.24 15.616C14.24 14.9333 14.336 14.208 14.528 13.44C14.72 12.672 15.1147 11.68 15.712 10.464L20.704 0H25.472L22.784 11.584C23.4027 12.0107 23.8933 12.576 24.256 13.28C24.6187 13.9627 24.8 14.7413 24.8 15.616Z' fill='%23ABB2BF'/%3E%3C/svg%3E%0A");
        @apply text-gray bg-background;
    }

    .wrapper-icon {
        &::after {
            content: '';
            display: flex;
            position: absolute;
            /* left: 10px;
        top: -10px; */
            font-size: 23px;
            right: -0px;
            bottom: 0;
            transform: translate(-20px, 50%);
            width: 25px;
            height: 20px;
            background-position: center;
            background-repeat: no-repeat;
            font-family: 'Fira Code';
            background-image: url("data:image/svg+xml,%3Csvg width='26' height='21' viewBox='0 0 26 21' fill='none' xmlns='http://www.w3.org/2000/svg'%3E%3Cpath d='M10.56 15.616C10.56 17.0453 10.0373 18.2507 8.992 19.232C7.968 20.2133 6.72 20.704 5.248 20.704C3.73333 20.704 2.47467 20.2133 1.472 19.232C0.490667 18.2507 0 17.0453 0 15.616C0 14.9333 0.096 14.208 0.288 13.44C0.48 12.672 0.864 11.68 1.44 10.464L6.4 0H11.2L8.544 11.584C9.14133 12.0107 9.62133 12.576 9.984 13.28C10.368 13.9627 10.56 14.7413 10.56 15.616ZM24.8 15.616C24.8 17.0453 24.2773 18.2507 23.232 19.232C22.1867 20.2133 20.9387 20.704 19.488 20.704C18.016 20.704 16.768 20.2133 15.744 19.232C14.7413 18.2507 14.24 17.0453 14.24 15.616C14.24 14.9333 14.336 14.208 14.528 13.44C14.72 12.672 15.1147 11.68 15.712 10.464L20.704 0H25.472L22.784 11.584C23.4027 12.0107 23.8933 12.576 24.256 13.28C24.6187 13.9627 24.8 14.7413 24.8 15.616Z' fill='%23ABB2BF'/%3E%3C/svg%3E%0A");
        }
    }
}</style>