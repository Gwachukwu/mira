<template>
    <div class="big-circle">
<svg width="100%" height="100%" viewbox="0 0 100 100" class="donut-chart">
    <circle cx="75" cy="75" r="60" fill="#fff"/>
    <circle cx="75" cy="75" r="60" fill="transparent" stroke-width="27" stroke="#DB261B"/>
    <circle cx="75" cy="75" r="60" fill="transparent" stroke-width="27" stroke="#27AE60" stroke-dasharray="350.2" stroke-dashoffset="9.42"/>
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
    display: flex;
    justify-content:center;
    align-items:center;
    overflow: hidden;
}
.donut-chart{
    align-self: center;
    width:10rem;
    padding: 0.5rem;
    transform: rotate(-50deg);
}
</style>