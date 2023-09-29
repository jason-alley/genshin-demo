<template>
    <header>
        <img class="header_logo" src="https://res.cloudinary.com/connexmedia/image/upload/v1695950464/logo-gsi-main.png"
            alt="Genshin Impact logo">
        <video class="header_video" autoplay loop="true" muted="true"
            src="https://res.cloudinary.com/connexmedia/video/upload/v1695949419/header-vid.mp4"></video>
        <Navigation />
    </header>
</template>


<style scoped>
.header_video {
    /* position: absolute; */
    top: 0;
    left: 0;
    width: 100%;
    height: 80vh;
    object-fit: cover;
    margin-bottom: -0.5rem;
}

.header_logo {
    position: absolute;
    top: 15vw;
    right: 33vw;
    width: 30%;
    opacity: 0.9;
    z-index: 1;
}</style>