<template>
  <div class="md:flex">
    <div
      class="max-w-sm mx-auto bg-white rounded-3xl px-4 py-2 shadow-2xl my-4 transform flex-1 md:-rotate-12"
    >
      <div class="flex">
        <div class="flex-1">
          <i class="fas fa-align-left cursor-pointer"></i>
        </div>
        <div><i class="fas fa-search cursor-pointer"></i></div>
      </div>
      <div class="text-purple-500 text-3xl font-extrabold mt-8 mb-1">
        Fashion Week
      </div>
      <div class="text-xs mb-4">2021 Fashion show in Paris</div>
      <div class="flex mb-2">
        <div class="flex-1 font-bold text-2xl">Explore</div>
        <div><i class="fas fa-sliders-h cursor-pointer"></i></div>
      </div>
      <div class="flex text-sm mb-4">
        <div class="flex-1 text-purple-400 cursor-pointer">Recommend</div>
        <div class="flex-1 cursor-pointer">New Models</div>
        <div class="cursor-pointer">2020 Show</div>
      </div>
      <div class="flex">
        <div class="mr-2">
          <div class="shadow-2xl rounded-2xl">
            <img
              class="rounded-2xl cursor-pointer shadow-2xl"
              src="../assets/ff1.jpg"
              alt=""
            />
          </div>
          <div class="mt-4 font-semibold text-sm">Niketa William</div>
          <div class="text-sm font-light">Paris</div>
        </div>
        <div class="ml-2">
          <div class="shadow-2xl rounded-2xl">
            <img
              class="rounded-2xl cursor-pointer shadow-2xl"
              src="../assets/ff2.jpg"
              alt=""
            />
          </div>
          <div class="mt-4 font-semibold text-sm">Trisha Louis</div>
          <div class="text-sm font-light">London</div>
        </div>
      </div>
      <div class="mt-4 mb-4">
        <img
          class="rounded-2xl w-full shadow-2xl cursor-pointer"
          src="../assets/tw2.jpg"
          alt=""
        />
      </div>
    </div>
    <div
      class="max-w-sm min-h-screen shadow-2xl rounded-3xl mx-auto ot flex-1 py-4 px-4 my-2 text-white relative md:bg-center md:transform md:rotate-6"
    >
      <div class="flex">
        <div class="flex-1"><i class="fas fa-angle-left text-white"></i></div>
        <div><i class="fas fa-ellipsis-v text-white"></i></div>
      </div>
      <div class="mt-32"><i class="far fa-comment-alt"></i></div>
      <div class="ml-1 mb-4">3</div>
      <div><i class="far fa-heart"></i></div>
      <div class="mb-4">579</div>
      <div><i class="far fa-clock"></i></div>
      <div class="">18</div>

      <div
        class="rounded-2xl shadow-2xl bg-gray-200 bg-opacity-30 px-6 pt-4 pb-10 absolute bottom-4 mx-2"
      >
        <div class="font-bold mb-2 text-2xl">Milla Jovovich</div>
        <div class="text-sm">
          Milla Jovoich is an a Italian Model with impressive protofolioAnd was
          best model and ramp walk in 2018. She is famousBecause of her
          different colors styles.
        </div>
      </div>
      <div class="flex flex-row-reverse absolute bottom-6 right-6">
        <div
          class="flex bg-blue-400 py-2 pl-5 pr-2 rounded-r-full rounded-tl-full cursor-pointer"
        >
          <div class="text-sm mr-2 font-semibold">Follow</div>
          <div class="bg-white rounded-full h-6 w-6">
            <i class="fas fa-plus text-black ml-2 text-xs"></i>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style>
* {
  font-family: Helvetica;
}
.ot {
  background-image: url("../assets/tw3.jpg");
  background-size: auto 100%;
  /* background-position-x: center; */
}
</style>
