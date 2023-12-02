<template>
  <h1>test</h1>
  <stored-resources :resources="storedResources"></stored-resources>
</template>

<script>
import StoredResources from './components/learning-resources/StoredResources.vue';


export default {
  components: { StoredResources },
  
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
