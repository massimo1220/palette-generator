<template>
  <div class="min-h-screen">
    <header class="py-3 sm:px-8 flex justify-between items-center">
      <div class="flex items-center">
        <img
          alt="Color generator logo" 
          src="../src/logo.webp" />
      </div>
      <nav class="flex items-center">
        <a aria-label="Github" class="mx-2" href="https://github.com/devstar0202/palette-generator/" rel="noopener noreferrer" target="_blank">
          <svg-icon name="github" class="w-6 text-gray-700 fill-current h-6 hover:text-sea-buckthorn-600"/>
        </a>
      </nav>
    </header>
    <Nuxt />
    <footer class="text-sm text-center text-gray-600 py-5">
      Visit <a href="http://david0202.c1.biz" rel="noopener noreferrer" target="_blank" class="underline text-sea-buckthorn-600">David's website</a>
    </footer>
  </div>
</template>

<style>
html {
  font-family:
    'Quicksand',
    'Source Sans Pro',
    -apple-system,
    BlinkMacSystemFont,
    'Segoe UI',
    Roboto,
    'Helvetica Neue',
    Arial,
    sans-serif;
  font-size: 16px;
  word-spacing: 1px;
  -ms-text-size-adjust: 100%;
  -webkit-text-size-adjust: 100%;
  -moz-osx-font-smoothing: grayscale;
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;

  @apply box-border;
}

*,
*::before,
*::after {
  box-sizing: border-box;
  margin: 0;
}
</style>
