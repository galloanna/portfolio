<template>
    <header>
        <nuxt-link to="/" class="logo">Anna Gallo<br><span>UX Developer</span></nuxt-link>
        <nav>
            <ul>
                <li><nuxt-link to="/">About</nuxt-link></li>
                <li><nuxt-link to="work">Work</nuxt-link></li>
                <li><nuxt-link to="contact">Contact</nuxt-link></li>
            </ul>
        </nav>
    </header>
</template>

<script>
export default {
    
}
</script>

<style lang="scss">
    @import '../../assets/css/main.scss';
    header {
        display: grid;
        grid-template-columns: repeat(2,auto);
    }

    .span {
        display: block;
    }

    .logo, li a {
        padding: 1em 2em;
        display: block;
        text-transform: uppercase;
        text-decoration: none;
        font-weight: bold;
        color: $black;
        font-size: 0.9em;
    }

    nav {
        justify-self: right;
    }
    li {
        display: inline;
    }
    li a {
        padding: 1em 2em;
        display: inline-block;
    }

</style>