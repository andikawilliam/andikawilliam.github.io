<template>
  <div>
    <h1 class="text-5xl text-left sm:text-5xl font-semibold">
      Hi there.
    </h1>
    <h2 class="text-2xl text-left sm:text-3xl font-semibold mt-2 sm:mt-6">
      My name is <span class="whitespace-no-wrap">Andika William.</span>
    </h2>
    <div class="text-base sm:text-xl text-gray-300 font-light tracking-wide mt-6 flex flex-col  gap-4 sm:gap-8">
      <p>
        I'm a software engineer at 
        <a 
          href="https://datasaur.ai" 
          target="_blank" 
          rel="noopener noreferrer" 
          class="hvr-bounce-to-top"
        >
          Datasaur.ai
        </a> 
        , specializing in Frontend Development. 
        My stacks include using 
        <span class="font-medium">TypeScript</span>, 
        <span class="font-medium">Material-UI</span>, and 
        <span class="font-medium">GraphQL</span>.
      </p>
      <p>
        I also enjoy working on website projects on the side. You can check out some of my work in my 
        <span 
          class="hvr-bounce-to-top cursor-pointer pb-1"
          v-on:click="$store.commit('changePage', 'PagePortfolio');"
        >
          portfolio
        </span>. 
        <!-- For technologies that I've used, have a look at my 
        <span 
          class="hvr-bounce-to-top cursor-pointer pb-1" 
          v-on:click="$store.commit('changePage', 'PageStacks');"
        >
          stacks
        </span>.  -->
      </p>
      <p>
        When I'm not coding or helping around the house, you'll find me reading books, going for runs, or learning to play the guitar.
      </p>
      <div class="flex justify-between text-sm sm:text-lg">
        <p class="transition duration-300 ">
          Looking to build a website? 
        <a 
          target="_blank" rel="noopener noreferrer" 
          href="mailto:andikawilliamv@gmail.com" 
          class="hvr-bounce-to-top mr-1"
        > 
          Let's chat!
            <font-awesome-icon :icon="['far', 'envelope']" fixed-width>
            </font-awesome-icon>
          </a>
        </p>
        <p>
          <a 
            target="_blank" rel="noopener noreferrer" 
            href="https://github.com/andikawilliam" 
            class="mr-2"
          >
            <font-awesome-icon 
              :icon="['fab', 'github']" 
              size='lg' 
              fixed-width
              class="transition duration-300 transform hover:scale-105 hover:-translate-y-2"
            >
            </font-awesome-icon>
          </a>
          <a 
            target="_blank" rel="noopener noreferrer" 
            href="https://www.linkedin.com/in/andika-william-62777314a/"
          >
            <font-awesome-icon 
              :icon="['fab', 'linkedin']" 
              size='lg' 
              fixed-width
              class="transition duration-300 transform hover:scale-105 hover:-translate-y-2"
            >
            </font-awesome-icon>
          </a>
        </p>
      </div>
    </div>
  </div>
</template>

<script></script>
<style></style>
