<template>
    <span class="item">
        <img :src=icon_src alt="icon" width="50" height="50" />
        <div>
            <h3>{{ name }}</h3>
            <div class="line">
                <p>{{ percent }}</p>
            </div>
        </div>

    </span>
</template>

<script>
import '../scss/skills.scss';
export default {

    props: {
        name: String,
        icon_src: String,
        percent: Number,
    }
}
</script>