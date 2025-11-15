<template lang="">
    <header class="relative bg-gray-800 after:pointer-events-none after:absolute after:inset-x-0 after:inset-y-0 after:border-y after:border-white/10">
      <div class="mx-auto max-w-7xl px-4 py-6 sm:px-6 lg:px-8">
        <h1 class="text-3xl font-bold tracking-tight text-white">
            My Images
        </h1>
      </div>
    </header>
    <main>
      <div class="mx-auto max-w-7xl px-4 py-6 sm:px-6 lg:px-8">
        
      </div>
      <div class="mb-4">
          <label for="label" 
          class="block text-sm/6 font-medium text-white">
              Label
          </label>
          <div class="mt-2">
              <input type="text" 
              name="label" id="label" 
              class="block w-full rounded-md bg-white/5 px-3 py-1.5 text-base text-white outline-1 -outline-offset-1 outline-white/10 placeholder:text-gray-500 focus:outline-2 focus:-outline-offset-2 focus:outline-indigo-500 sm:text-sm/6" />
          </div>
      </div>
      <button type="submit" class="rounded-md bg-indigo-500 px-3 py-2 text-sm font-semibold text-white focus-visible:outline-2 focus-visible:outline-offset-2 focus-visible:outline-indigo-500">
          Uploads
      </button>
    </main>
</template>
<script>
export default {
    
}
</script>
<style lang="">
    
</style>