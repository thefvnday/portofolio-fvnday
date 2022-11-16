<template>
    <section class="portfolio section" id="portfolio">
        <h2 class="section__title">Portofolio</h2>
        <span class="section__subtitle">Most recent work</span>

        <div class="portofolio__container container swiper">
            <div class="swiper-wrapper">
                <!--==================== PORTFOLIO 1 ====================-->
                <div class="portofolio__content grid swiper-slide">
                    <img src="frontend/assets/img/1.jpeg" alt="" class="portofolio__img">

                    <div class="portofolio__data">
                        <h3 class="portofolio__title">Redisgn Web Kimia</h3>
                        <p class="portofolio__description">Website adaptable to all devices, with ui components and
                            animated interactions.
                        </p>
                        <a href="https://tensholiday.com/" class="button button--flex button--small portofolio__button">
                            Demo
                            <i class="uil uil-arrow-right button__icon"></i>
                        </a>
                    </div>
                </div>

                <!--==================== PORTFOLIO 2 ====================-->
                <div class="portofolio__content grid swiper-slide">
                    <img src="frontend/assets/img/bpn.png" alt="" class="portofolio__img">

                    <div class="portofolio__data">
                        <h3 class="portofolio__title">Develop Webiste BPN Kaltim</h3>
                        <p class="portofolio__description">Website adaptable to all devices, with ui components and
                            animated interactions.
                        </p>
                        <a href="https://siapukur.atrbpnkaltim.net/login"
                            class="button button--flex button--small portofolio__button">
                            Demo
                            <i class="uil uil-arrow-right button__icon"></i>
                        </a>
                    </div>
                </div>

                <!--==================== PORTFOLIO 3 ====================-->
                <div class="portofolio__content grid swiper-slide">
                    <img src="frontend/assets/img/aladinmall.png" alt="" class="portofolio__img">

                    <div class="portofolio__data">
                        <h3 class="portofolio__title">Aladin Mall</h3>
                        <p class="portofolio__description">Website adaptable to all devices, with ui components and
                            animated interactions.
                        </p>
                        <a href="https://aladinmall.misteraladin.com/" class="button button--flex button--small portofolio__button">
                            Demo
                            <i class="uil uil-arrow-right button__icon"></i>
                        </a>
                    </div>
                </div>

                <!--==================== PORTFOLIO 4 ====================-->
                <div class="portofolio__content grid swiper-slide">
                    <img src="frontend/assets/img/skala.jpg" alt="" class="portofolio__img">

                    <div class="portofolio__data">
                        <h3 class="portofolio__title">SKALA MOBILE</h3>
                        <p class="portofolio__description">Website adaptable to all devices, with ui components and
                            animated interactions.
                        </p>
                        <a href="https://www.youtube.com/watch?v=CudxMLgMvgk&t=180s"
                            class="button button--flex button--small portofolio__button">
                            Demo
                            <i class="uil uil-arrow-right button__icon"></i>
                        </a>
                    </div>
                </div>

                <!--==================== PORTFOLIO 5 ====================-->
                <div class="portofolio__content grid swiper-slide">
                    <img src="frontend/assets/img/5.jpeg" alt="" class="portofolio__img">

                    <div class="portofolio__data">
                        <h3 class="portofolio__title">SMARTDIO MOBILE</h3>
                        <p class="portofolio__description">Website adaptable to all devices, with ui components and
                            animated interactions.
                        </p>
                        <a href="https://smkwidyadirgantara.sch.id/"
                            class="button button--flex button--small portofolio__button">
                            Demo
                            <i class="uil uil-arrow-right button__icon"></i>
                        </a>
                    </div>
                </div>

                <!--==================== PORTFOLIO 6 ====================-->
                <!-- <div class="portofolio__content grid swiper-slide">
                    <img src="frontend/assets/img/6.jpeg" alt="" class="portofolio__img">

                    <div class="portofolio__data">
                        <h3 class="portofolio__title">Modern Wedding Website</h3>
                        <p class="portofolio__description">Website adaptable to all devices, with ui components and
                            animated interactions.
                        </p>
                        <a href="https://risalahati.id/" class="button button--flex button--small portofolio__button">
                            Demo
                            <i class="uil uil-arrow-right button__icon"></i>
                        </a>
                    </div>
                </div> -->
            </div>
            <!-- add arrows -->
            <div class="swiper-button-next">
                <i class="uil uil-angle-right-b swiper-portofolio-icon"></i>
            </div>
            <div class="swiper-button-prev">
                <i class="uil uil-angle-left-b swiper-portofolio-icon"></i>
            </div>

            <!-- add pagination -->
            <div class="swiper-pagination"></div>
        </div>
    </section>
</template>

<script>
export default {
    name: 'Portfolio'
}
</script>