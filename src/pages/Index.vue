<template>
    <div id="app">
        <site-header></site-header>
        <main>
            <div class="container pb-20 px-3 mx-auto items-center">
                <section class="container mx-auto pt-6">
                    <slot name="main-content" />
                    <g-link class="nav__link" to="/hero/">Cliquez ici pour voir le Hero </g-link>
                </section>
            </div>
        </main>
        <site-footer></site-footer>
    </div>
</template>

<script>
export default {
  metaInfo: {
    title: 'Hello, world!'
  }
}
</script>

<style>
.home-links a {
  margin-right: 1rem;
}
*{
  margin:0;
  padding:0;
}
body, html{height:100%;}

body{
text-align:center;
}
main{
  max-width:1280px;
  min-height:100%;
  margin:0 auto;
  position:relative;
}
</style>
