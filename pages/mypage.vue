<template>
    <div class="flex flex-row justify-between gap-x-64">

        <!-- PRESENTATION, DESCRIPTION, BUTTON-->
        <div class="flex flex-col gap-12 w-1/2">
            <div class="flex flex-col gap-5">
                <div
                    class="flex flex-row justify-around items-center bg-[#DEECEE] rounded-full text-[#3AADBE] text-center text-sm font-semibold uppercase px-5 py-2 gap-2 w-fit">
                    <div class="bg-[#0091A8] rounded-full w-1.5 h-1.5"></div>
                    <span>Avaible for work</span>
                </div>
                <span class=" text-8xl font-semibold">Hola, soy un joven aventurero.</span>
            </div>
            <div>
                <span>Tengo 18 años y estoy estudiando mi pasión. Lo que me divierte y me entretiene durante horas.
                    Además,
                    estoy estudiando el mundo de las criptomonedas y leyendo libros sobre cosas muy interesantes de la
                    vida.</span>
                <div>
                    <span>Si estás interesado en un perfil como el mio, </span><button class="font-semibold">contáctame.</button>
                </div>
            </div>
        </div>

        <!-- BOXS (INTRODUCTION), ME PICTURE, BRANDS, SOCIALS-->
        <div class="flex flex-col gap-3 w-1/2 h-full">
            <!-- TOP BOXS -->
            <div class="flex flex-row gap-3">
                <div class="flex flex-col justify-between bg-[#fff] rounded-2xl p-5 gap-48 w-[45%]">
                    <div class="flex flex-col ">
                        <span class="text-xl">Daniele Dettori</span>
                        <span class="text-slate-600/80">Tenerife, Spain</span>
                    </div>
                    <div class="flex flex-col gap-3">
                        <span class="bg-[#EAEAEA] rounded-full px-4 py-2 uppercase w-fit">Student</span>
                        <span class="bg-[#EFF6FE] rounded-full text-[#2573D0] px-4 py-2 uppercase w-fit">Free</span>
                    </div>
                </div>
                <div class="flex flex-col justify-between bg-[#fff] rounded-2xl gap-36 w-[60%]">
                    <img class="w-full h-full rounded-2xl" src="public/daniele.jpg" alt="Daniele picture">
                </div>
            </div>
            <!-- BOTTOM BOXS -->
            <div class="flex flex-row bg-white rounded-xl gap-3">
                <div class="flex flex-col justify-between p-5 gap-4 w-full">
                    <span class="font-semibold">Únete a mi newsletter!</span>
                    <div class="flex flex-row gap-3">
                        <input class="rounded-lg p-2 w-2/5 outline-none" placeholder="Correo Electrónico" type="email">
                        <input class="rounded-lg p-2 w-2/5 outline-none" placeholder="Nombre" type="text">
                        <button
                            class="rounded-lg bg-[#EFF6FE] text-[#2573D0] font-semibold w-1/5 uppercase">Unirse</button>
                    </div>
                </div>
            </div>

        </div>
    </div>

    <!-- MISSION / SECOND PART -->
    <div class="flex flex-col bg-[#3DAFBF] rounded-2xl p-10 gap-5">
        <span class="text-slate-50 text-3xl font-semibold">EMPRESAS TRABAJADO</span>
        <span class="text-slate-50/80 text-xl">Ninguna</span>
    </div>

    <!--  -->
    <div class="text-3xl font-bold"><span>¿En qué te puedo ayudar?</span></div>

    <div class="flex flex-wor justify-around gap-5">
        <!-- EXPERIENCIA -->
        <div class="flex flex-col bg-slate-200 rounded-lg p-10 gap-10 w-full">
            <span class="text-4xl font-semibold">Experiencia</span>

            <div class="flex flex-row justify-between">
                <div>Criptos</div>
                <div>Teoría de juegos</div>
            </div>
            <div class="flex flex-row justify-center items-center">Programación</div>
        </div>
        <!-- TRABAJOS -->
        <div class="flex flex-col bg-slate-200 rounded-lg p-10 gap-10 w-full">
            <span class="text-4xl font-semibold">Trabajos</span>

            <div class="flex flex-row justify-between">
                <div>Proyecto Programación</div>
                <div>Proyecto ETS</div>
            </div>
            <div class="flex flex-row justify-center items-center">Mi propia página web</div>
        </div>
    </div>

</template>