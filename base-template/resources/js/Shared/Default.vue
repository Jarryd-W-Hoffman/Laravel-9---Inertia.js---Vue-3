<template>

    <header>
        <div class="container mx-auto p-8 m-10">
            <p class="text-3xl text-gray-700 font-bold mb-5">
                Welcome!
            </p>
        </div>
    </header>

    <main>
        <slot />
    </main>

    <footer>
        <div class="container mx-auto p-8 m-10">
            <p class="text-center text-3xl text-gray-700 font-bold mb-5">
                Now go build something amazing!
            </p>
        </div>
    </footer>

</template>

<script>
    export default {}
</script>