<template>
    <button class="button" 
        :class="{ double, triple, operator }">
        {{label}}
    </button>
</template>

<script>
export default {
    props: {
        label: {},
        operator: { type: boolean },
        double: { type: boolean },
        triple: { type: boolean }
    }

}
</script>

<style>

</style>
