<template>
    <div 
        class="entry-container mb-3 pointer p-2"
        @click="$router.push({ name: 'entry', params: { id: 10 } })"
    >
        <!-- Titulo -->
        <div class="entry-title d-flex">
            <span class="text-success fs-5 fw-bold">1</span>
            <span class="mx-1 fs-5">Diciembre</span>
            <span class="mx-2 fs-5 fw-light">2023, viernes</span>
        </div>

        <div class="entry-description">
            Dolore occaecat Lorem pariatur irure laboris ut duis irure. Consectetur ipsum sit nulla occaecat adipisicing amet sunt incididunt magna proident consectetur dolor. Commodo ullamco id consectetur labore incididunt amet. Anim anim nulla laborum excepteur cupidatat eu. Lorem minim ad aliquip nulla irure officia sint anim est velit. Cillum voluptate exercitation magna fugiat mollit.
        </div>
    </div>
</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>
    .entry-container {
        border-bottom: 1px solid #2c3e50;
        transition: 0.2s all ease-in;
        &:hover {
            background-color: lighten($color: grey, $amount: 45);
            transition: 0.2s all ease-in;
        }
        .entry-description {
            font-size: 12px;    
        }
    }
</style>