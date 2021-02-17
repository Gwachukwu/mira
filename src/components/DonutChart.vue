<template>
    <div class="big-circle">
<svg width="100%" height="100%" viewbox="0 0 100 100">
    <circle cx="50" cy="50" r="40" fill="#fff"/>
    <circle cx="50" cy="50" r="40" fill="transparent" stroke-width="20" stroke="#DB261B"/>
    <circle cx="50" cy="50" r="40" fill="transparent" stroke-width="20" stroke="#27AE60" stroke-dasharray="251.2" stroke-dashoffset="25.15"/>
    <!-- <text x="40" y="50" fill="black" font-size="10">Text</text> -->
</svg>
</div>
</template>

<script>
export default {
    name: "DonutChart"
}
</script>

<style scoped>
.big-circle{
    transform: scale(1.4);
}
</style>