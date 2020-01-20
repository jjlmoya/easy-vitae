<template>
    <div class="">
        <div class="left">
            <div class="image">
                <img src="" alt="name">
            </div>
            <div class="about">
                <h2>About me</h2>
                <p>My name is {{name}} Short text about me</p>
            </div>
            <div class="contact">
                <h2>Contacto</h2>
                <ul>
                    <li>
                        <i>i</i> <span>Option</span>
                    </li>
                    <li>
                        <i>i</i> <span>Option</span>
                    </li>
                </ul>
            </div>
            <ul class="skills">
                <li>
                    <label>Skill1</label>
                    <input
                        type="range"
                        max="100"
                        min="0"
                        value="50"
                        disabled
                    >
                </li>
            </ul>
        </div>
        <div class="right">
            <div class="name"></div>
            <div class="experience"></div>
            <div class="grade"></div>
            <div class="languages"></div>
        </div>
    </div>
</template>
<style lang="scss">@import 'default.scss';
</style>
<script>
    export default {
        name: 'DefaultLayout',
        data () {
            return {
                name: 'sample name'
            }
        },
        components: {
        }
    }
</script>
