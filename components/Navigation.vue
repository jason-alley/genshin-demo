<template>
    <nav class="nav">
        <ul>
            <li>
                <NuxtLink to="/">CHARACTERS</NuxtLink>
                <i class="material-icons ">arrow_drop_down</i>
            </li>
            <li>
                <NuxtLink to="/">NATIONS</NuxtLink>
                <i class="material-icons hide-carret">arrow_drop_down</i>
            </li>
        </ul>
    </nav>
</template>

<script setup>

</script>

<style scoped>
.nav {
    background-color: black;
    color: #fff;
    z-index: 4;
}

.nav ul {
    display: flex;
    justify-content: space-between;
    max-width: 70%;
    margin: 0 auto;
    padding: 0.3rem ;
}

.nav ul li {
    text-align: center;
    width: min-content;
    margin-top: 1.5rem;
}

.nav ul li :hover {
    cursor: pointer;
}

.nav ul li a {
    color: #fff;
    text-decoration: none;
    font-size: 1.6rem;
}

.hide-carret {
    opacity: 0;
}
</style>