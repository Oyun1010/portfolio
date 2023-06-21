<script>
import ProjectItem from '../components/ProjectItem.vue';
import '../scss/projects.scss';
export default {
    components: {
        ProjectItem,
    }
}
</script>

<template>
    <section id="projects">
        <h1>Projects</h1>
        <div class="items">
            <ProjectItem img_path="../src/assets/projects/pro_0.png" :libraries='["vueJs", "sass"]'
                domain_url="https://oyun1010.github.io/" domain="oyun1010.github.io"
                git_url="https://github.com/Oyun1010/portfolio" />
            <ProjectItem img_path="../src/assets/projects/pro_1.png" :libraries='["nextJs", "tailwindCss"]'
                domain_url="https://davgu.mn/" domain="davgu.mn" />

            <ProjectItem img_path="../src/assets/projects/pro_1.png" :libraries='["flutter"]'
                domain_url="http://owner.davgu.mn/" domain="owner.davgu.mn"
                figma="https://www.figma.com/file/u2QmaoEt6GsG9nmGLir2fV/Web-Prototype(davg%C3%B9-customer)?type=design&node-id=0-1&mode=design&t=FC4wylhzq5QJWL86-0" />
            <ProjectItem img_path="../src/assets/projects/pro_3.png" :libraries='["flutter", "firebase"]'
                git_url="https://github.com/Oyun1010/mobile_project"
                figma="https://www.figma.com/file/l0Yrg1P8DRjxPJ2kyyZmjV/%5BFREEBIES%5D-Income-%26-Expense-Tracker-(Community)?type=design&node-id=0-1&t=LwJeUW9z1t9FB6kS-0" />
            <ProjectItem img_path="../src/assets/projects/pro_4.png"
                :libraries='["react native", "native wind", "mongobd", "nodejs"]'
                git_url="https://github.com/Oyun1010/rentalapp"
                figma="https://www.figma.com/file/22bCs2Ja1WmxY9arRxrWEs/Untitled?type=design&node-id=0-1&mode=design&t=4pYSbYn6XPYo9mIo-0" />

            <div class="more">
                <a href="https://github.com/Oyun1010">More >></a>

            </div>
        </div>

    </section>
</template>