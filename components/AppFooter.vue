<template>
  <footer class="bg-gray-1000 text-white py-8">
    <div class="max-w-7xl mx-auto grid grid-cols-1 lg:grid-cols-3 gap-8">
      <!-- social media links -->
      <div class="flex flex-col items-start space-y-2">
        <div class="text-lg font-semibold">LET'S CONNECT</div>
        <div class="flex space-x-4">
          <a
            href="https://twitter.com/CoogEsports"
            target="_blank"
            rel="noopener noreferrer"
            class="text-2xl text-secondary"
          >
            <font-awesome-icon :icon="['fab', 'x-twitter']" />
          </a>
          <a
            href="https://www.instagram.com/CoogEsports"
            target="_blank"
            rel="noopener noreferrer"
            class="text-2xl text-secondary"
          >
            <font-awesome-icon :icon="['fab', 'instagram']" />
          </a>
          <a
            href="https://www.twitch.tv/coogesports"
            target="_blank"
            rel="noopener noreferrer"
            class="text-2xl text-secondary"
          >
            <font-awesome-icon :icon="['fab', 'twitch']" />
          </a>
          <a
            href="https://discord.com/invite/coog-gaming-154441500950921216"
            target="_blank"
            rel="noopener noreferrer"
            class="text-2xl text-secondary"
          >
            <font-awesome-icon :icon="['fab', 'discord']" />
          </a>
        </div>
      </div>

      <!-- sponsors. REPLACE LOGOS WHEN SPONSORED -->
      <div class="text-center">
        <div class="text-lg font-semibold">SPONSORED BY</div>
        <div class="flex items-center justify-center space-x-6 mt-2">
          <img
            src="/assets/img/sponsor_logos/your_logo_here.jpg"
            alt="Logo0"
            class="h-20"
          >
          <img
            src="/assets/img/sponsor_logos/your_logo_here.jpg"
            alt="Logo1"
            class="h-20"
          >
          <img
            src="/assets/img/sponsor_logos/your_logo_here.jpg"
            alt="Logo2"
            class="h-20"
          >
        </div>
      </div>

      <!-- contact info -->
      <div class="text-right flex flex-col space-y-2">
        <div class="font-semibold text-lg">
          University of Houston Esports Club
        </div>
        <div>4465 University Dr. MAILBOX 50</div>
        <div>Houston, TX 77204</div>
        <div>
          <a href="mailto:coogesports@gmail.com" class="underline"
            >coogesports@gmail.com</a
          >
        </div>
      </div>
    </div>
  </footer>
</template>

<script setup>
defineOptions({
  name: 'AppFooter',
});
</script>
