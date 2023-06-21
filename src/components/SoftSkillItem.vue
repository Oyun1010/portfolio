<script>
import '../scss/skills.scss';
export default {
    props: {
        img_scr: String,
        title: String,
        ind: String,
    }
}
</script>

<template>
    <div class="container" :style=ind>
        <div class="item">
            <img :src=img_scr alt="image" width="110" height="100" />
            <h3>{{ title }}</h3>
        </div>

    </div>
</template>