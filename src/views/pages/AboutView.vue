<template>
    <section class="about section" id="about">
        <h2 class="section__title">About Me</h2>
        <span class="section__subtitle">My Introduction</span>

        <div class="about__container container grid">
            <img src="frontend/assets/img/home.jpg" alt="" class="about__img">

            <div class="about__data">
                <p class="about__description">Innovative individual with proven success evaluating requirements for software development projects to design 
innovative solutions. Out-of-the-box thinker and problem solver dedicated to improving performance. Works 
well in teams and consistently delivers to deadlines.
                </p>

                <!-- <div class="about__info">
                    <div>
                        <span class="about__info-title">04+</span>
                        <span class="about__info-name">Years <br> experience</span>
                    </div>
                    <div>
                        <span class="about__info-title">50+</span>
                        <span class="about__info-name">Completed <br> project</span>
                    </div>
                    <div>
                        <span class="about__info-title">04+</span>
                        <span class="about__info-name">Companies <br> worked</span>
                    </div>
                </div> -->

                <div class="about__buttons">
                    <a download="" href="frontend/assets/pdf/Fandy Ahmad Irianto-CV.pdf" class="button button--flex">
                        Download CV<i class="uil uil-download-alt button__icon"></i>
                    </a>
                </div>
            </div>
        </div>
    </section>
</template>


<script>
export default {
    name: 'About'
};
</script>