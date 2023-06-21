<template>
    <span class="item">
        <img :src=icon_src alt="icon" width="50" height="50" />
        <div>
            <h3>{{ name }}</h3>
            <hr class="line">
            <div class="percent" :style=percent></div>
           

        </div>

    </span>
</template>

<script>
import '../scss/skills.scss';
export default {

    props: {
        name: String,
        icon_src: String,
        percent: String,

    }
}
</script>