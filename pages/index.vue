<template>
    <div class="mt-container">
        <div class="mt-diagonal-section">
            <img class="mt-image" src="~/assets/leipzig-city_2.png" alt="leipzig-city"/>
        </div>
        <div class="bg-video">
            <video
                class="block h-full w-full"
                playsinline
                autoplay
                loop
                muted>
                <source
                    src="~/assets/mt-coding.mp4"
                    type="video/mp4">
            </video>
        </div>
    </div>
</template>

<script>
export default {}
</script>

<style>
.mt-diagonal-section {
    position: sticky;
    height: 85vh;
    overflow: hidden;
}

.mt-image {
    position: absolute;
    top: 0;
    bottom: 0;
    right: 0;
    left: 0;
    width: 100%;
    height: 100%;
    transform: skewY(-4deg);
    transform-origin: top left;
}

.bg-video {
    margin-top: -20%;
}
</style>
