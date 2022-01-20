<template>
  <div class="font-sans">
    <button
      class="
        py-2
        px-4
        font-medium
        text-white
        rounded-md
        bg-blue-400
        border-transparent
        hover:bg-white hover:text-black hover:border-2 hover:border-gray-400
      "
    >
      {{ buttonLabel }}
    </button>
  </div>
</template>

<script>
export default {
  name: 'BaseButton',
  props: ['buttonLabel'],
};
</script>
