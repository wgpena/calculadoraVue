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

:root {
    --bg-button: #f0f0f0;
    --border-button: solid 1px #888;
}

.button {
    font-size: var(--bg-button);
    border: none;
    border-right: var(--border-button);
    border-bottom: var(--border-button);
}

</style>
