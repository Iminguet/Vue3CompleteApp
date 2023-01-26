<template>
  <ul>
    <li></li>
  </ul>
</template>

<script>
export default {
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
