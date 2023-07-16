
<template>
    <div id="skill">
        <div class="head">
            <h1>Skills</h1>
            <div class="head-section">
                <!-- <img class="left" alt="img" src="../assets/bee.gif" width='400' height="500" /> -->
                <img alt="img" src="../assets/ani_0.gif" width="500" height="500" />
                <!-- <img class="right" alt="img" src="../assets/bee.gif" width="400" height="500" /> -->
                <p>Technical <br /> Level</p>
            </div>

        </div>

        <div class="skills">
            <div class="skill-item">
                <h2>Frontend</h2>
                <SkillItem name="React Js" icon_src='../src/assets/icons/react-native.png' percent="--i:85%" />
                <SkillItem name="React Native" icon_src='../src/assets/icons/react-native.png' percent="--i:85%" />
                <SkillItem name="Next Js" icon_src='../src/assets/icons/react-native.png' percent="--i:90%" />
                <SkillItem name="Flutter" icon_src='../src/assets/icons/react-native.png' percent="--i:90%" />
                <SkillItem name="Vue Js" icon_src='../src/assets/icons/react-native.png' percent="--i:50%" />
            </div>
            <div class="skill-item">
                <h2>Backend</h2>
                <SkillItem name="Node Js" icon_src='../src/assets/icons/react-native.png' percent="--i:80%" />
                <SkillItem name="Express Js" icon_src='../src/assets/icons/express.png' percent="--i:80%" />
                <SkillItem name="Mongodb" icon_src='../src/assets/icons/react-native.png' percent="--i:80%" />
            </div>
            <div class="skill-item">
                <h2>Designer</h2>
                <SkillItem name="Figma" icon_src='../src/assets/icons/figma.png' percent="100%" />

            </div>

        </div>

        <div class="soft-skills">

            <div class="skill-items">
                <SoftSkillItem ind="--i:1" title="Time management" img_scr="../src/assets/time-management.png" />
                <SoftSkillItem ind="--i:2" title="Problem solving" img_scr="../src/assets/bouncy-searching-for-mental-problems-in-the-brain.png" />
                <SoftSkillItem ind="--i:3" title="Team work" img_scr="../src/assets/bonbon-robot-helps-with-business-processes-by-moving-gears.png" />
                <SoftSkillItem ind="--i:4" title="Communication" img_scr="../src/assets/worky-receiving-a-message-on-a-smartphone.png" />
                <SoftSkillItem ind="--i:5" title="Adaptability" img_scr="../src/assets/juicy-globe-earth.png" />
                <SoftSkillItem ind="--i:6" title="Resilience" img_scr="../src/assets/moji-crossed-fingers.png" />
            </div>





            <h2>Soft Skills</h2>

        </div>



    </div>
</template>

<script >
import SkillItem from '../components/SkillItem.vue';
import SoftSkillItem from '../components/SoftSkillItem.vue';
import { CIcon } from '@coreui/icons-vue';
import * as icon from '@coreui/icons';
import '../scss/skills.scss';

export default {
    components: {
        SkillItem,
        SoftSkillItem
    },

}

</script>

