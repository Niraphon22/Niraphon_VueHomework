<template>
  <div class="font-sans">
    <div class="text-center mt-4">
      <p class="uppercase text-3xl font-bold text-blue-500">
        personal information
      </p>
      <p class="uppercase text-2xl font-medium text-blue-500 mt-2">
        niraphon jongkraijak
      </p>
      <p class="uppercase text-2xl font-medium text-blue-500">apple</p>
    </div>
    <div class="flex justify-center mt-4">
      <img
        :src="profileImg"
        class="h-64 rounded-full border-2 border-blue-400 shadow-xl"
      />
    </div>
    <router-link to="/contact" class="flex justify-center mt-4">
      <base-button
        buttonLabel="CONTACT"
        class="text-lg"
      ></base-button>
    </router-link>
    <div class="flex justify-center my-4">
      <div class="border-2 border-blue-500 w-3/3 h-auto p-2">
        <p
          class="
            uppercase
            text-center text-lg
            font-semibold
            text-black
            underline
            decoration-blue-400 decoration-wavy
          "
        >
          my education
        </p>
        <ul class="list-disc list-inside font-medium">
          <li>KING MONGKUT’S UNIVERSITY OF TECHNOLOGY THONBURI</li>
          <p class="ml-6 font-normal">2019-PRESENT</p>
          <p class="ml-6 font-normal">SCHOOL OF INFORMATION TECHNOLOGY</p>
          <li>
            YOTHINBAMRUNG SCHOOL
            <p class="ml-6 font-normal">2016-2018</p>
            <p class="ml-6 font-normal">
              SCIENCE MATH TECHNOLOGY AND ENVIRONMENT
            </p>
          </li>
        </ul>

        <p
          class="
            uppercase
            text-center text-lg
            font-semibold
            text-black
            underline
            decoration-blue-400 decoration-wavy
            mt-2
          "
        >
          skills
        </p>
        <ul class="list-disc list-inside font-medium uppercase">
          <li>
            WEB TECHNOLOGY
            <p class="ml-6 font-normal">html</p>
            <p class="ml-6 font-normal">css, tailwind css</p>
            <p class="ml-6 font-normal">vue.js</p>
            <p class="ml-6 font-normal">javascript</p>
          </li>
          <li>
            database
            <p class="ml-6 font-normal">sql</p>
            <p class="ml-6 font-normal">mysql</p>
          </li>
          <li>
            database tools
            <p class="ml-6 font-normal">sql developer</p>
            <p class="ml-6 font-normal">sql data modeler</p>
            <p class="ml-6 font-normal">mysql workbench</p>
          </li>
        </ul>
      </div>
    </div>
  </div>
</template>

<script>
import BaseButton from '../components/BaseButton.vue';

export default {
  name: 'Profile',
  components: {
    BaseButton,
  },
  data() {
    return {
      profileImg:
        'https://scontent.fbkk2-4.fna.fbcdn.net/v/t39.30808-6/272059449_1261582321000237_7460094467923030383_n.jpg?_nc_cat=101&ccb=1-5&_nc_sid=09cbfe&_nc_aid=0&_nc_eui2=AeF1KlSFcUWvQ-dwS52K_mxzmsUBGGDxgQuaxQEYYPGBC7eCy3VqQKQXIvrWz0H0odH_9TBAQ4P95_WImtxZAq8r&_nc_ohc=BfVImZLWwJ8AX_yFYVw&_nc_ht=scontent.fbkk2-4.fna&oh=00_AT9PVPgO5o5UIky1HVcqOvCkoDU-j4Lw7rBKZKvRGK3t3w&oe=61ED8789',
    };
  },
};
</script>
