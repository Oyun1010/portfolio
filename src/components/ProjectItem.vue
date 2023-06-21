<script>
import '../scss/projects.scss';
export default {
    props: {
        title: String,
        git_url: String,
        domain: String,
        domain_url: String,
        img_path: String,
        libraries: Array,
        figma: String
    }
}
</script>

<template>
    <div class="pro-item">
        <img :src=img_path width="450" height="250" alt="img" />
        <div class="frameworks">
            <span v-for="library in libraries">{{ library }}</span>
        </div>
        <a :href=domain_url target="_blank" class="domain">{{ domain }}</a>
        <div class="links">
            <a :href=git_url target="_blank">
                <img src="../assets/icons/github.png" /><span>Souce code</span>
            </a>
            <a :href=figma target="_blank">
                <img src="../assets/icons/figma.png" /><span>Figma</span>
            </a>
        </div>

    </div>
</template>