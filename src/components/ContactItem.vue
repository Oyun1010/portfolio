<script>
import '../scss/skills.scss';
export default {
    props: {
        img_scr: String,
        title: String,
        url: String,
    }
}
</script>

<template>
    <div class="item">
        <img :src=img_scr alt="image" width="50" height="50" />
        <a :href=url>
            <p>{{ title }}</p>
        </a>
    </div>
</template>