<script setup lang="ts">
useHead({
  title: 'Painel da Transparência',
  meta: [
    { name: 'Trazendo informações de maneira descomplicada', content: 'No Painel da transparência você se informa a partir de dados da administração pública, de uma forma acessível e fácil de entender.' }
  ],
  bodyAttrs: {
    class: 'test'
  },
  script: [ { innerHTML: 'console.log(\'Hello world\')' } ]
})

useSeoMeta({
  title: 'Painel da Transparência',
  ogTitle: 'Painel da Transparência',
  description: 'No Painel da transparência você se informa a partir de dados da administração pública, de uma forma acessível e fácil de entender.',
  ogDescription: 'No Painel da transparência você se informa a partir de dados da administração pública, de uma forma acessível e fácil de entender.',
  ogImage: 'https://images2.imgbox.com/a0/83/t768RA1z_o.jpg',
  twitterCard: 'summary_large_image',
})

//https://imgbox.com/gallery/edit/yvJE4GiZcr/LVRF1qS2KKDT6Lt0
</script>
<template>
  <NuxtLayout>
    <NuxtPage />
  </NuxtLayout>
</template>
