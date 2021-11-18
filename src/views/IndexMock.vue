<template>
    <div id="container">
      <h1 class="mt-5 mb-2">Emoji to <mark>Favicon</mark></h1>
      <h2 class="fs-5 text fw-light text-secondary">Quickly create a copy & paste ready Favicon by selecting an Emoji</h2>

      <section class="mt-5 d-flex d-flex justify-content-center">
        <ul class="list-unstyled text-start w-40">
          <li class="py-1 fs-5 text"><span class="me-3">✔️</span> Select an emoji from the list below</li>
          <li class="py-1 fs-5 text"><span class="me-3">✂️</span> Copy the code in the textarea</li>
          <li class="py-1 fs-5 text"><span class="me-3">🖥️</span> Paste it into the head part of your website</li>
          <li class="py-1 fs-5 text"><span class="me-3">🎉</span> Enjoy your new emoji favicon</li>
        </ul>
      </section>

      <section class="mt-5">
        <textarea 
          id="favicon-code"
          readonly 
          placeholder="Select an emoji to generate the favicon code" 
          class="form-control user-select-all shadow-sm"
        ></textarea>
        <p class="text-black-50 mt-1 text-start">Click inside textarea  to copy code to clipboard</p>
      </section>
  
  </div>
</template>

<script>
export default {
  name: 'IndexMock',
  components: {}
}
</script>

<style>

</style>