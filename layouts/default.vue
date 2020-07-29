<template>
  <div class="flex flex-col h-screen w-screen">
    <!--
      Navigation Bar

      PARAMETERS
      :logoURL  (URL for Logo)
    -->
    <NaviWrapper
      imgURL="https://images-platform.99static.com//CaMLcQRQFJGx8WrAvVX5wjEZQdw=/43x0:1957x1914/fit-in/590x590/99designs-contests-attachments/102/102621/attachment_102621668"
    ></NaviWrapper>

    <div class="flex-1">
      <div class="flex">
        <Nuxt class="w-full h-screen overflow-y-auto"/>
      </div>
    </div>
    <FooterWrapper/>
  </div>
</template>
<script>
export default {};
</script>