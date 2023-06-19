<script>
import '../scss/skills.scss';
export default {
    props: {
        img_scr: String,
        title: String
    }
}
</script>

<template>
    <div class="item">
        <img :src=img_scr alt="image" width="150" height="150" />
        <h3>{{ title }}</h3>
    </div>
</template>