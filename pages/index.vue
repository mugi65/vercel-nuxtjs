<template>
  <div class="block mx-auto">
    <div class="relative items-center justify-center">
      <!-- Header Text-->
      <h1 class="text-center font-serif text-3xl pt-4 pb-4">First Vue</h1>
      <h1 class="text-center text-2xl font-bold p-4 bg-gray-800 text-gray-400">with tailwind css</h1>
      <!-- All Cards Container -->
      <div class="lg:flex items-center container mx-auto my-auto">
        <!-- Card 1 -->
        <div class="lg:m-4 shadow-md hover:shadow-lg hover:bg-gray-100 rounded-lg bg-white my-12 mx-8">
          <!-- Card Image -->
          <img src="https://picsum.photos/id/1028/2106/1404" alt=""class="overflow-hidden">
          <!-- Card Content -->
          <div class="p-4">
            <h3 class="font-medium text-gray-600 text-lg my-2 uppercase">Phot0 1</h3>
            <p class="text-justify">Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Aenean commodo ligula eget dolor. Aenean massa. Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Donec quam felis, ultricies nec, pellentesque eu, pretium quis, sem. Nulla consequat massa quis enim. Donec pede justo, fringilla vel, aliquet nec, vulputate</p>
            <div class="mt-5">
              <a href="" class="hover:bg-gray-700 rounded-full py-2 px-3 font-semibold hover:text-white bg-gray-400 text-gray-100">Read More</a>
            </div>
          </div>
        </div>
        <!-- Card 2 -->
        <div class="lg:m-4 shadow-md hover:shadow-lg hover:bg-gray-100 rounded-lg bg-white my-12 mx-8">
          <!-- Card Image -->
          <img src="https://picsum.photos/id/1025/2106/1404" alt=""class="overflow-hidden">
          <!-- Card Content -->
          <div class="p-4">
            <h3 class="font-medium text-gray-600 text-lg my-2 uppercase">Photo 2</h3>
            <p class="text-justify">The quick, brown fox jumps over a lazy dog. DJs flock by when MTV ax quiz prog. Junk MTV quiz graced by fox whelps. Bawds jog, flick quartz, vex nymphs. Waltz, bad nymph, for quick jigs vex! Fox nymphs grab quick-jived waltz. Brick quiz whangs jumpy veldt fox. Bright vixens.</p>
            <div class="mt-5">
              <a href="" class="hover:bg-gray-700 rounded-full py-2 px-3 font-semibold hover:text-white bg-gray-400 text-gray-100">Read More</a>
            </div>
          </div>
        </div>
        <!-- Card 3 -->
        <div class="lg:m-4 shadow-md hover:shadow-lg hover:bg-gray-100 rounded-lg bg-white my-12 mx-8">
          <!-- Card Image -->
          <img src="https://picsum.photos/id/101/2106/1404" alt=""class="overflow-hidden">
          <!-- Card Content -->
          <div class="p-4">
            <h3 class="font-medium text-gray-600 text-lg my-2 uppercase">Photo 3</h3>
            <p class="text-justify">A wonderful serenity has taken possession of my entire soul, like these sweet mornings of spring which I enjoy with my whole heart. I am alone, and feel the charm of existence in this spot, which was created for the bliss of souls like mine. I am so happy, my</p>
            <div class="mt-5">
              <a href="" class="hover:bg-gray-700 rounded-full py-2 px-3 font-semibold hover:text-white bg-gray-400 text-gray-100">Read More</a>
            </div>
          </div>
        </div>
      </div>
      <foot />
    </div>
  </div>
</template>

<script>
import Logo from '~/components/Logo.vue'
import Foot from '~/components/Footer.vue'

export default {
  components: {
    Logo, Foot
  }
}
</script>