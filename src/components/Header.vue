<script setup>
import '../scss/styles.scss';

</script>

<script>
export default {
    name: "Modal",
    computed: {
        isActive() {
            return this.$store.getters["modals/active"] === this.name
        },
        isOpen() {
            return this.$store.getters["modals/allOpen"].includes(this.name)
        }
    },
    methods: {
        close() {
            this.$store.dispatch("modals/close", this.name)
        }
    },
    beforeDestroy() {
        if (this.isOpen) this.close()
    }
}
</script>
<template>
    <nav>
        <p>OYU</p>
        <img class="menu-icon" src="../assets/menu.png" alt="img" width="40" height="35" />
        <ul>
            <li><a href="#home">Home</a></li>
            <li><a href="#about">About</a></li>
            <li><a href="#skill">Skills</a></li>
            <li><a href="#projects">Projects</a></li>
            <li><a href="#contact">Contacts</a></li>
        </ul>
      

    </nav>
</template>