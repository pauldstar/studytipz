<template>
    <div class="footer">
        <div class="container-fluid">
            <div class="row align-items-center">
                <div class="col-xl-6 col-md-6">
                    <div class="copy_right">
                        Copyright © {{ year }} Quixlab. All Rights Reserved.
                    </div>
                </div>
                <div class="col-xl-6 col-md-6 text-lg-right text-center">
                    <div class="social">
                        <a href="#"><i class="fa fa-youtube-play"></i></a>
                        <a href="#"><i class="fa fa-instagram"></i></a>
                        <a href="#"><i class="fa fa-twitter"></i></a>
                        <a href="#"><i class="fa fa-facebook"></i></a>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
    import app from '@js/App.vue';

    export default {
        extends: app
    }
</script>
