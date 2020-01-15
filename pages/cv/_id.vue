<template>
    <div class="cv">
        <Layout>
            <div class="left">
                <div class="image">
                    <img src="">>
                </div>
                <div class="about">
                    <h2>About me</h2>
                    <p>Short text about me</p>
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
        </Layout>
    </div>
</template>

<script>
    import Layout from '@/layouts/Default.vue'
    export default {
        name: 'CV',
        components: {
            Layout
        },
        head () {
            return {
                title: 'CV',
                meta: [
                    {
                        hid: 'description',
                        name: 'description',
                        content: 'My custom description'
                    }
                ]
            }
        }
    }
</script>
