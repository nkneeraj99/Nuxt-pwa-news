<template>
    <div>
        <section class="hero has-text-centered is-primary">
            <div class="hero-body">
                <div class="container">
                    <h1 class="title">PWA News</h1>
                    <h2 class="subtitle">All the headlines making the wavy!</h2>
                </div>
            </div>
        </section>
        <nuxt/>
    </div>
</template>


<script>
import axios from "axios";
// axios.defaults.headers.common['user-key'] = '61918e8c809d4809823f84170aabf08d'

export default {
  
}
</script>


<style>
    html {
        font-family: 'Source Sans Pro', -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;
    }
</style>