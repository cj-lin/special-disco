<template>
  <div>
    <div class="mb-0 m-[5px] py-0 p-5">
      <h1 class="font-medium text-2xl leading-8">Hi! This is a simple Nuxt 3 app.</h1>
      <h2 class="font-normal text-base leading-8">
        Click on the buttons below to check out a server route or an API route:)
      </h2>
      <NuxtLink to="/hello" target="_blank">
        <button
          class="font-medium text-2xl leading-8 text-[white] bg-[rgb(42,219,145)] text-base ml-[5px] my-2.5 m-0 px-[30px] py-2.5 rounded-[5px] border-[none] hover:cursor-pointer hover:bg-[rgb(29,199,128)] hover:transition-[0.2s] hover:duration-[ease-in]">
          What Time Is It?
        </button>
      </NuxtLink>
      <NuxtLink to="/api/hello" target="_blank">
        <button
          class="font-medium text-2xl leading-8 text-[white] bg-[rgb(42,219,145)] text-base ml-[5px] my-2.5 m-0 px-[30px] py-2.5 rounded-[5px] border-[none] hover:cursor-pointer hover:bg-[rgb(29,199,128)] hover:transition-[0.2s] hover:duration-[ease-in]">
          Link to API Route
        </button>
      </NuxtLink>
      <h2 class="font-normal text-base leading-8">
        Deploy Nuxt 3 app with universal rendering on Azure Static Web Apps using
        <NuxtLink to="https://docs.microsoft.com/azure/static-web-apps/deploy-nuxtjs"
          class="text-[rgb(29,199,128)] font-medium no-underline hover:cursor-pointer hover:text-[rgb(18,168,106)] hover:font-medium hover:underline hover:transition-[0.2s] hover:duration-[ease-in-out]">
          the Microsoft documentation
        </NuxtLink>
      </h2>
      <NuxtPage />
    </div>
  </div>
</template>
