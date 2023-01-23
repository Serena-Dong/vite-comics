<script>
export default {
    name: 'AppContents'
}
</script>

<template>

    <div class="card">
        <a href="">
            <img src="https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/09/AC1000_DLX_162-001_HD_5ba13723281ab0.37845353.jpg?itok=ZsI-C5eX"
                alt="">

            <p>Action Comics</p>
        </a>
    </div>

</template>

<style lang="scss" scoped>
@use '../../assets/scss/partials/variables' as *;

a {
    color: white;

    &:hover {
        color: $dc_blue;
    }
}

.card {
    width: 180px;
    height: 270px;

    img {
        object-fit: cover;
        width: 180px;
        height: 180px;

        &:hover {
            border: $dc_blue 2px solid;
        }
    }

    p {
        margin: 1rem 0 1rem
    }
}
</style>