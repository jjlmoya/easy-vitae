<template>
    <div class="cv">
        <Layout>
            <Basic />
        </Layout>
    </div>
</template>

<script>
    import Layout from '@/layouts/Default.vue'
    import Basic from '@/layouts/Basic.vue'
    export default {
        name: 'CV',
        components: {
            Layout,
            Basic
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
