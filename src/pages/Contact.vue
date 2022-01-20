<template>
  <div class="font-sans my-36">
    <div class="text-center">
      <p class="uppercase text-3xl font-bold text-blue-500">my contact</p>
    </div>
    <div class="border-2 border-blue-500 w-3/3 h-auto p-2 mt-4">
      <div class="flex flex-row mt-4 text-black text-lg">
        <p class="font-medium">Telephone Number:</p>
        <p class="font-normal ml-2">66+ 935960619</p>
      </div>
      <div class="flex flex-row mt-2 text-black text-lg">
        <p class="font-medium">Email Address:</p>
        <p class="font-normal ml-2">niraphon.ple@mail.kmutt.ac.th</p>
      </div>
      <div class="flex flex-row mt-2 text-black text-lg">
        <p class="font-medium">Line Id:</p>
        <p class="font-normal ml-2">o0_apple</p>
      </div>
    </div>

    <router-link to="/" class="flex justify-center mt-4">
      <base-button buttonLabel="BACK" class="text-lg"></base-button>
    </router-link>
  </div>
</template>

<script>
import BaseButton from '../components/BaseButton.vue';

export default {
  name: 'Contact',
  components: {
    BaseButton,
  },
};
</script>
