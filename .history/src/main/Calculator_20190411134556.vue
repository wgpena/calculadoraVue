<template>
    <div class="calculator">
        <Display />
        <Button label="AC" triple />
        <Button label="/" oparetor />
        <Button label="" />
        <Button label="" />
        <Button label="" />
        <Button label="" />
        <Button label="" />
        <Button label="" />
        <Button label="" />
        <Button label="" />
        <Button label="" />
        <Button label="" />
        <Button label="" />
        <Button label="" />
        <Button label="" />
        <Button label="" />
        <Button label="" />
    </div>
</template>

<script>
import Display from '../components/Display'
import Button from '../components/Button'

export default {
    components: { Button, Display }

}
</script>

<style>

.calculator {
    height: 320px;
    width: 235px;
    border-radius: 5px;
    overflow: hidden;

    display: grid;
    grid-template-columns: repeat(4, 25%);
    grid-template-rows: 1fr 48px 48px 48px 48px 48px;
}

</style>
