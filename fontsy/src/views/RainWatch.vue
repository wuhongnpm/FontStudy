<template>
    <div class="rainWatch">
        <div class="svg">
            <span>RainWatch:Fight in the city</span>
        </div>
        <canvas id="canvas"></canvas>
    </div>
</template>
<script>
</script>
<style scoped>
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

.rainwatch {
    background-image: url(../assets/cc1.jpg);
    background-repeat: no-repeat;
    background-position: center;
    background-color: #86C166;
    background-size: cover;
}

#canvas {
    width: 100%;
    height: auto;
}

.svg {
    width: 800px;
    position: absolute;
    top: 10%;
    left: 50%;
    transform: translate(-50%, -50%);
    z-index: 102;
    text-align: center;
}

span {
    font-family: San Francisco;
    font-weight: 400;
    font-size: 30px;
    letter-spacing: 3px;
    fill: transparent;
    stroke: white;
    stroke-width: 1.5px;
    stroke-dasharray: 400;
    stroke-dashoffset: 400;
    animation: draw 4s linear infinite;
    text-shadow: 0 0 10px white;
    z-index: 105;
}

@keyframes draw {

    0%,
    100% {
        stroke-dasharray: 500;
        stroke-dashoffset: 625;
    }

    45%,
    55% {
        stroke-dasharray: 652;
        stroke-dashoffset: 652;
    }
}
</style>


