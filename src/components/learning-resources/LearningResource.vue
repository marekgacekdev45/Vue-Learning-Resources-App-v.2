<template>
    <li>
        <base-card>
            <header>
                <h3>{{ title }}</h3>
                <base-button mode="flat">delete</base-button>
            </header>
            <p>{{ description }}</p>
            <nav>
              <a :href="link">View Resource</a>
            </nav>
          </base-card>
    </li>
</template>

<script>
export default {
    props:['title','description','link']
}
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

<style scoped>
li {
  margin: auto;
  max-width: 40rem;
}

header {
  display: flex;
  justify-content: space-between;
  align-items: center;
}

h3 {
  font-size: 1.25rem;
  margin: 0.5rem 0;
}

p {
  margin: 0.5rem 0;
}

a {
  text-decoration: none;
  color: #ce5c00;
}

a:hover,
a:active {
  color: #c89300;
}
</style>