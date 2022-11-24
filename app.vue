<script setup>
console.log("tst");
</script>

<template>
  <div>
    <main>
      <NuxtImg
        src="/1.jpg"
        sizes="xs:480px sm:960px md:1152px"
        format="webp"
        loading="lazy"
      />
      <NuxtImg
        src="/2.jpg"
        sizes="xs:480px sm:960px md:1152px"
        format="webp"
        loading="lazy"
      />
    </main>
  </div>
</template>
