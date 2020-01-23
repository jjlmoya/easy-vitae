<template>
    <div class="">
        <div class="left">
            <div class="image">
                <img src="" alt="name">
            </div>
            <div class="about">
                Name: {{ name }}
                Edad: {{ age }}
                Adress: {{ address }}
                Phone {{ phone }}
                Email: {{ email }}
                Profile: {{ about }}
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
        components: {
        },
        data () {
            return {
                name: 'sample name',
                skills: [{

                }],
                experience: [
                    {
                        company: '',
                        task: '',
                        projects: []
                    }
                ],
                languages: [
                    {
                        id: 'es',
                        name: 'Spanish',
                        level: '3'
                    },
                    {
                        id: 'en',
                        name: 'English',
                        level: '1'
                    }
                ]
            }
        }
    }
</script>
