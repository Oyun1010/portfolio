<script>
import '../scss/contact.scss';
import ContactItem from '../components/ContactItem.vue';
export default {

    components: {
        ContactItem
    }
}

</script>

<template>
    <section id="contact">
        <img class="contact-bg" alt="img" src="../assets/2833951.jpg" width="500" height="400" />
        <div class="contact-section">
            <img alt="img" src="../assets/contact.gif" width="500" height="500" />
            <div>
                <h2>Contact me</h2>
                <ContactItem url="https://github.com/Oyun1010" img_scr='../src/assets/icons/github.png'
                    title="Oyun1010" />
                <ContactItem url="https://www.messenger.com/t/100008838469387" img_scr='../src/assets/icons/facebook.png'
                    title="Oyunsuren Batsuh" />
                <ContactItem img_scr='../src/assets/icons/gmail.png' title="Oyunbat0623@gmail.com" />
                <ContactItem img_scr='../src/assets/icons/phone.png' title="+976 99543988" />

            </div>
        </div>
        <!-- <img class="img-right" alt="img" src="../assets/social.png" width="500" height="400" /> -->
    </section>
</template>