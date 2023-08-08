<script>
  import github from "super-tiny-icons/images/svg/github.svg"
  import linkedin from "super-tiny-icons/images/svg/linkedin.svg"
  import gmail from "super-tiny-icons/images/svg/gmail.svg"
</script>

<section id="Contact" class="bg-gray-50 h-screen flex">
  <div class="mx-auto max-w-screen-xl px-4 py-12 sm:px-6 md:py-48 lg:px-8">
    <div class="mx-auto max-w-3xl text-center">
      <h2 class="text-3xl font-bold text-teal-600 sm:text-4xl">
        Checkout my socials!
      </h2>

      <p class="mt-4 text-gray-500 sm:text-xl">
        Reach out, say hi or maybe hire me? 😳
      </p>
    </div>

    <div class="mt-8 sm:mt-12 bg-gray-100 p-8 rounded-lg shadow-lg">
      <dl
        class="grid grid-cols-1 gap-8 sm:grid-cols-3 sm:divide-x sm:divide-gray-100"
      >
        <a href="https://github.com/NappySprout" target="_blank"><img src={github} alt="github logo" class="rounded-full hover:scale-110 transition"></a>
        <a href="https://www.linkedin.com/in/darie-chan-rong-zhi-4301a9207/" target="_blank"><img src={linkedin} alt="github logo" class="rounded-full hover:scale-110 transition"></a>
        <a href="mailto:sleepylog20@gmail.com" target="_blank"><img src={gmail} alt="github logo" class="rounded-full hover:scale-110 transition"></a>
      </dl>
    </div>
  </div>
</section>