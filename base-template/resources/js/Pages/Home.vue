<template>

    <Default>

        <div class="container mx-auto bg-gray-200 rounded-xl shadow border p-8 m-10">
            <p class="text-2xl text-gray-500">
                Installed and Configured stack:
            </p>
            <p class="text-gray-500">
                <ul>
                    <li v-for="item in stack" :key="item">
                        {{ item }}
                    </li>
                </ul>
            </p>
        </div>

    </Default>

</template>

<script>
    import Default from '../Shared/Default.vue'

    export default {
        components: { Default },
        props: {
            stack: Array,
        },
    }
</script>
