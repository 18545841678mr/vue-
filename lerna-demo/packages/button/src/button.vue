<template>
    <div id="button">
        <div class="buttonWrapper">
            <div class="button">
                {{ text }}
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: 'button',
    props: ['text']
}
</script>

<style lang="scss" scoped>
    *{
        padding: 0;
        margin: 0;
    }
</style>
