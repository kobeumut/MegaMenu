<template>
    <div>
        <div v-if="selectedTab == 1">
            <h1>TAB 1</h1>
            <p>Now <b>tab 1</b> is selected.if once more clicked it will be deselected else click on other tabs to view them</p>
        </div>
        <div  v-if="selectedTab == 2">
            <h1>TAB 2</h1>
            <p>Now <b>tab 2</b> is selected.if once more clicked it will be deselected else click on other tabs to view them</p>
        </div>
        <div v-if="selectedTab == 3">
            <h1>TAB 3</h1>
            <p>Now <b>tab 3</b> is selected.if once more clicked it will be deselected else click on other tabs to view them</p>
        </div>
    </div>
</template>

<script>
export default {
    props: ['selectedTab']
}
</script>