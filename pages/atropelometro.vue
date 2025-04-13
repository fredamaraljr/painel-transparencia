<script setup>
definePageMeta({
  layout: "landing",
});
</script>

<template>
  <LandingContainer>
    <LandingSectionhead>
      <template v-slot:title>Atropelometro</template>
    </LandingSectionhead>

    <div style="width: 100%">
      <div
        style="
          position: relative;
          padding-bottom: 56.25%;
          padding-top: 0;
          height: 0;
        "
      >
        <iframe
          title="Mortes no trânsito de São Paulo"
          frameborder="0"
          width="1200"
          height="675"
          style="position: absolute; top: 0; left: 0; width: 100%; height: 100%"
          src="https://view.genially.com/67fb0ac493bbdb46173b8a27"
          type="text/html"
          allowscriptaccess="always"
          allowfullscreen="true"
          scrolling="yes"
          allownetworking="all"
        ></iframe>
      </div>
    </div>
    <!-- {
        team.map((item) => (
          <div class="group">
            <div class="w-full aspect-square">
              <Image
                {...item.avatar}
                format="avif"
                alt="Team"
                class="w-full h-full object-cover rounded transition  group-hover:-translate-y-1 group-hover:shadow-xl"
              />
            </div>

            <div class="mt-4 text-center">
              <h2 class="text-lg text-gray-800"> {item.name}</h2>
              <h3 class="text-sm text-slate-500"> {item.title}</h3>
            </div>
          </div>
        ))
      } -->
  </LandingContainer>
</template>
