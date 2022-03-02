<template>
    <main id="main-container">
        <h1>Mathificent</h1>
        <SelectInput />
        <SelectInput />
        <PlayButton />
    </main>
</template>

<script>
import SelectInput from './SelectInput';
import PlayButton from './PlayButton';

export default {
    name: 'Main',
    components: {
        SelectInput,
        PlayButton
    }
}
</script>

<style scoped>
    #main-container {
        margin: auto;
        width: 380px;
    }
</style>