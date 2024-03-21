<script>

export default {
    data() {
        return {

        };
    }
}

</script>



<template>
    <header id="goup">
        <div class="container-fluid bg-video">
            <video autoplay muted loop id="bgVideo">
                <source src="../assets/video/forest.mp4" type="video/mp4">
                Your browser does not support the video tag.
            </video>
            <div class="row justify-content-center">
                <div class="col-12 col-lg-12 col-md-8 rounded-4 d-flex align-items-center">
                </div>
                <div class="col-12 col-lg-6 my-5 text-over-bg rounded-5">
                    <h1 class="title_init text-center">Suitability <br> Forestry Work</h1>
                    <h2>
                        This project aims to provide a geospatial analysis-based approach to improve forest planning and
                        forest machine management.<br>
                        Using <span style="color: greenyellow;">Q</span><span style="color: orange;">GIS</span> as an analysis tool to optimize forest resources in a sustainable way.
                    </h2>
                </div>
            </div>
        </div>
    </header>
</template>


<style>
.bg-video {
    position: relative;
    height: 800px; /* Altezza desiderata del video */
}

#bgVideo {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    object-fit: cover;
}

.text-over-bg {
    position: relative;
    z-index: 1;
    color: rgb(251, 249, 249);
    background-color: rgba(2, 35, 9, 0.562);
    /* Opacity added to make the text more readable */
    padding: 2rem;
    box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
}

.title_init {
    color: #13e764;
}

.logo {
    height: 30px;
    width: auto;
    margin-right: 10px;
}
</style>