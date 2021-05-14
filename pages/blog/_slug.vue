<template>
  <article>
    <nav>
      <ul>
        <li v-for="link of article.toc" :key="link.id">
          <NuxtLink :to="`#${link.id}`">{{ link.text }}</NuxtLink>
        </li>
      </ul>
    </nav>
    <!-- Article Header -->
    <img :src="require(`~/assets/images/${article.img}`)" :alt="article.alt" />
    <h1>{{ article.title }} </h1>
    <h2>{{ article.description }} </h2>
    <h3>Article last updated: {{ formatDate(article.updatedAt) }}</h3>

    <!-- See All Article Object Data
    <pre> {{ article }} </pre> -->

    <!-- Article Content -->
    <nuxt-content :document="article" />
  </article>
</template>
<script>
  
  export default {
    
    async asyncData({ $content, params }) {
      const article = await $content('articles', params.slug).fetch()

      return { article }
    },
    methods: {
      formatDate(date) {
        const options = { year: 'numeric', month: 'long', day: 'numeric' }
        return new Date(date).toLocaleDateString('en', options)
      }
    }
  }
  
</script>
<style>
article{
  padding: 1em;
}
  img{
    width: 250px;
    height: auto;
    padding: 1em;
  }
  .nuxt-content h2 {
    font-weight: bold;
    font-size: 28px;
  }
  .nuxt-content h3 {
    font-weight: bold;
    font-size: 22px;
  }
  .nuxt-content p {
    margin-bottom: 20px;
  }
</style>