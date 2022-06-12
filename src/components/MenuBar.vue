<template>
        <div class = "menu">
            <div class = "menuItem">
                Home
            </div>
            <div class = "menuItem">
                Services
            </div>
            <div class = "menuItem">
                Our History
            </div>
            <div class = "menuItem">
                Contact
            </div>

        </div>
</template>

<script>
export default {
    name: 'menuBar-view'
}
</script>

<style scoped>
    .menu{
        display: flex;
        align-items: center;
        justify-content: center;
        vertical-align: middle;
    }
    .menuItem{
        text-align: center;
        padding: 2em;
        font-size: 1.7em;
    }
</style>
