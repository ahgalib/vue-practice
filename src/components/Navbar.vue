<script>
import { RouterLink, RouterView } from 'vue-router';
export default{
    name:"Navbar",
}
</script>
<template>
    <header>
        <nav class="container">
            <div class="branding">
                <RouterLink to="/home">Home</RouterLink>
                <router-link class="header" to="/home">FireBlogs</router-link>
                <router-view/>
            </div>
            <div class="nav-links">
                <ul>
                    <li>
                        <router-link class="link" to="#">Home</router-link>
                        <router-link class="link" to="#">Blogs</router-link>
                        <router-link class="link" to="#">Create Post</router-link>
                        <router-link class="link" to="#">login/Register</router-link>
                    </li>
                </ul>
            </div>
        </nav>
    </header>
</template>



<style>
.header{
    background-color: red;
}
</style>
