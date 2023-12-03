<template>
  <the-header title="Remember Me"></the-header>
  
</template>

<script>
import TheHeader from './components/layouts/TheHeader.vue';



export default {
  components: {TheHeader },
  
  data() {
    return {
      storedResources: [
        {
          id: '1',
          title: 'Official Guide',
          description: 'lorem ipsum dolor sit amet',
          link: 'https://vue.org',
        },
        {
          id: '2',
          title: 'google',
          description: 'lorem ipsum dolor sit amet',
          link: 'https://google.com',
        },
        {
          id: '3',
          title: 'udemy',
          description: 'lorem ipsum dolor sit amet',
          link: 'https://udemy.com',
        },
      ],
    };
  },
};
</script>
