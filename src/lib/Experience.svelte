<!--
  Heads up! 👋

  This component comes with some `rtl` classes. Please remove them if they are not needed in your project.
-->
<script>
  import experiences from './Experiences.json';
</script>

<section id="Experiences" class="bg-gray-50">
  <div class="max-w-screen-xl min-h-screen flex px-4 py-8 sm:px-6 sm:py-12 lg:px-8 lg:py-16">
    <div
      class="grid grid-cols-1 gap-y-8 lg:grid-cols-2 lg:items-center lg:gap-x-16"
    >
      <div
        class="p-8 mx-auto max-w-lg text-center lg:mx-0 ltr:lg:text-left rtl:lg:text-right"
      >
        <h2 class="text-3xl font-bold sm:text-4xl text-teal-600">Work Experiences</h2>

        <p class="mt-4 text-gray-600"> Proficient in Python, Javascript, Java, C++, PSQL, Mongodb</p>
        <p class="mt-4 text-gray-600"> Web Technologies: React, Svelte, Express</p>
        <p class="mt-4 text-gray-600"> Cloud and Automation: AWS, Azure, Terraform, Packer, Jenkins</p> 
        <div class="mt-8 flex flex-wrap justify-center gap-4">
          <a
            class="block w-full rounded px-12 py-3 text-sm font-medium text-teal-600 shadow hover:text-teal-700 focus:outline-none focus:ring active:text-red-500 sm:w-auto"
            href="#Contact"
          >
            Contact me?
          </a>
        </div>
      </div>

      <div class="grid md:grid-cols-2 gap-4 grid-cols-1">
        {#each experiences as {title, subtitle, date, content}}
        <a
          class="block rounded-xl border border-gray-100 p-4 shadow-sm hover:border-gray-200 hover:ring-1 hover:ring-gray-200 focus:outline-none focus:ring"
          href="https://www.linkedin.com/in/darie-chan-rong-zhi-4301a9207/" target="_blank"
        >
          <h1 class="mt-2 font-bold text-xl text-teal-600">{title}</h1>
          <h3 class="mt-2 text-gray-800 text-l">{subtitle}</h3> 
          <h3 class="mt-2 font-light text-sm">{date}</h3> 
          <ul class="mt-4 list-disc mx-1">
            {#each content as line}
              <li class="text-xs text-gray-500 list-item ml-1">
                {line}
              </li>
            {/each}
          </ul>
        </a>
        {/each}
      </div>
    </div>
  </div>
</section>