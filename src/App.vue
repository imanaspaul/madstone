<template>
  <div class="nav w-full h-16 bg-black"></div>
  <!-- create a div with background image of full view port height -->
  <div
    class="bg-cover bg-center h-screen"
    style="
      background-image: url('https://static.wixstatic.com/media/254ac1_35dc679b04f84c148456c9b1c4bd2fe8~mv2.jpg/v1/fill/w_1640,h_858,al_c,q_85/254ac1_35dc679b04f84c148456c9b1c4bd2fe8~mv2.webp');
    "
  >
    <div class="container h-1/2 mx-auto flex justify-center items-center">
      <div class="flex mt-10 flex-col justify-center items-center">
        <img
          style="min-width: 600px"
          src="https://static.wixstatic.com/media/254ac1_7eb8b57e4e054897a6585338dd9ae851~mv2_d_6537_1724_s_2.png/v1/fill/w_400,h_106,al_c,q_85,usm_0.66_1.00_0.01/Madstone_didelis_baltas.webp"
          alt="logo"
        />
        <h3 class="text-white font-bold uppercase text-2xl tracking-widest">
          DIGITAL POST-PRODUCTION STUDIO
        </h3>
      </div>
    </div>
  </div>

  <!-- second column -->
  <div
    class="bg-cover bg-center h-screen"
    style="
      background-image: url('https://static.wixstatic.com/media/254ac1_6502a62192f3411b8e785e4fa22cb6b3~mv2.jpg/v1/fill/w_1302,h_721,al_c,q_85,usm_0.66_1.00_0.01/254ac1_6502a62192f3411b8e785e4fa22cb6b3~mv2.webp');
    "
  >
    <div class="h-full flex justify-center items-center">
      <div class="container h-auto mx-auto flex justify-center items-center">
        <div
          class="
            w-1/2
            lg:w-1/3
            h-1/3
            border-8 border-gray-200
            flex flex-col
            p-4
            md:p-10
            justify-between
            items-center
          "
        >
          <h3 class="text-white font-bold uppercase text-2xl tracking-widest">
            ABOUT US
          </h3>
          <div
            class="flex flex-col justify-center items-center my-5 text-center"
          >
            <p class="text-xl text-yellow-400 font-bold italic">
              “Be happy, but never satisfied”
            </p>
            <p class="text-xl text-yellow-400 font-bold italic">–Bruce Lee</p>
          </div>
          <div class="text-center">
            <p class="text-xl text-white">
              A bunch of like-minded professionals always thirsty for a more
              satisfying end result. <br />

              We are a Vilnius based visual post-production studio, and we
              always give our extra best when working with any project trusted
              to us.
            </p>
          </div>
        </div>
      </div>
    </div>
  </div>
  <!-- third column -->
  <div
    class="bg-cover bg-center h-screen"
    style="
      background-image: url('https://static.wixstatic.com/media/254ac1_88d600994f06402cbad2a0571cd86c9e~mv2.jpg/v1/fill/w_1722,h_858,al_c,q_85/254ac1_88d600994f06402cbad2a0571cd86c9e~mv2.webp');
    "
  >
    <div class="container h-1/2 mx-auto flex justify-center items-center">
      <div class="w-5/6 lg:w-1/2 h-full flex flex-col py-20">
        <div
          class="
            border-8 border-gray-400
            w-full
            h-40
            flex
            justify-center
            items-center
          "
        >
          <h3
            class="
              text-white
              font-bold
              uppercase
              text-2xl
              tracking-widest
              text-center
            "
          >
            SERVICES
          </h3>
        </div>
      </div>
    </div>
  </div>
</template>
