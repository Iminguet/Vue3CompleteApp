<template>
  <TheHeader title="Remember Me"></TheHeader>
  <StoredResources :resources="storedResources"></StoredResources>
</template>

<script>
import StoredResources from './components/learning-resources/StoredResources.vue';

import TheHeader from './components/layouts/TheHeader.vue';

export default {
  components: {
    StoredResources,
    TheHeader,
  },
  data() {
    return {
      storedResources: [
        {
          id: 'official-guide',
          tittle: 'Official Guide',
          description: 'The official VueJs documentation.',
          link: 'https://vuejs.org',
        },
        {
          id: 'google',
          tittle: 'Google',
          description: 'Goolge is cool to look for.',
          link: 'https://www.google.com',
        },
      ],
    };
  },
};
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap');

* {
  box-sizing: border-box;
}

html {
  font-family: 'Roboto', sans-serif;
}

body {
  margin: 0;
}
</style>
