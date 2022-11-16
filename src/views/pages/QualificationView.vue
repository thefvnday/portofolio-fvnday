<template>
    <section class="qualification section">
        <h2 class="section__title">Qualification</h2>
        <span class="section__subtitle">My Personal Journey</span>

        <div class="qualification__container container">
            <div class="qualification__tabs">
                <div class="qualification__button button--flex qualification__active" data-target="#education">
                    <i class="uil uil-graduation-cap qualification__icon"></i>
                    Education
                </div>

                <div class="qualification__button button--flex" data-target="#work">
                    <i class="uil uil-briefcase-alt qualification__icon"></i>
                    Work
                </div>
            </div>
            <div class="qualification__sections">
                <!--==================== QUALIFICATION CONTENT 1 ====================-->
                <div class="qualification__content qualification__active" data-content id="education">
                    <!--==================== QUALIFICATION 1 ====================-->
                    <div class="qualification__data">
                        <div>
                            <h3 class="qualification__title">Informatic Engineering</h3>
                            <span class="qualification__subtile">Sebelas Maret University</span>
                            <div class="qualification__calender">
                                <i class="uil uil-calender-alt"></i>
                                2019-2022
                            </div>
                        </div>

                        <div>
                            <span class="qualification__rounder"></span>
                            <span class="qualification__line"></span>
                        </div>
                    </div>

                    <!--==================== QUALIFICATION 2 ====================-->
                    <!-- <div class="qualification__data">
                        <div>
                            <h3 class="qualification__title">Master Computer Science</h3>
                            <span class="qualification__subtile">President - University</span>
                            <div class="qualification__calender">
                                <i class="uil uil-calender-alt"></i>
                                On Going
                            </div>
                        </div>
                        <div>
                            <span class="qualification__rounder"></span>
                            <span class="qualification__line"></span>
                        </div>
                    </div> -->

                    <!--==================== QUALIFICATION 3 ====================-->
                    <!-- <div class="qualification__data">
                        <div>
                            <h3 class="qualification__title">Fullstack Developement</h3>
                            <span class="qualification__subtile">Bootcamp - Santri Koding</span>
                            <div class="qualification__calender">
                                <i class="uil uil-calender-alt"></i>
                                2021
                            </div>
                        </div>
                        <div>
                            <span class="qualification__rounder"></span>
                            <span class="qualification__line"></span>
                        </div>
                    </div> -->

                    <!--==================== QUALIFICATION 4 ====================-->
                    <!-- <div class="qualification__data">
                        <div>
                            <h3 class="qualification__title">Fullstack Developement</h3>
                            <span class="qualification__subtile">Bootcamp - Built with Angga</span>
                            <div class="qualification__calender">
                                <i class="uil uil-calender-alt"></i>
                                2022
                            </div>
                        </div>
                        <div>
                            <span class="qualification__rounder"></span>
                            <span class="qualification__line"></span>
                        </div>
                    </div> -->



                </div>

                <!--==================== QUALIFICATION CONTENT 2 ====================-->
                <div class="qualification__content" data-content id="work">
                    <!--==================== QUALIFICATION 1 ====================-->
                    <div class="qualification__data">
                        <div></div>

                        <div>
                            <span class="qualification__rounder"></span>
                            <span class="qualification__line"></span>
                        </div>

                        <div>
                            <h3 class="qualification__title">Helpdesk Technician
                            </h3>
                            <span class="qualification__subtile">SPMB Sebelas Maret University</span>
                            <div class="qualification__calender">
                                <i class="uil uil-calender-alt"></i>
                                Juni 2021-Juli 2021
                            </div>
                        </div>
                    </div>
                    
                    <!--==================== QUALIFICATION 2 ====================-->
                    <div class="qualification__data">
                        <div></div>

                        <div>
                            <span class="qualification__rounder"></span>
                            <span class="qualification__line"></span>
                        </div>

                        <div>
                            <h3 class="qualification__title">Junior Programmer
                            </h3>
                            <span class="qualification__subtile">PT.Bix Box Teknologi Perkasa(Refactory)</span>
                            <div class="qualification__calender">
                                <i class="uil uil-calender-alt"></i>
                                November 2021 - Agustus 2022
                            </div>
                        </div>
                    </div>

                    <!--==================== QUALIFICATION 3 ====================-->
                    <div class="qualification__data">
                        <div></div>

                        <div>
                            <span class="qualification__rounder"></span>
                            <span class="qualification__line"></span>
                        </div>

                        <div>
                            <h3 class="qualification__title">Mobile Developer</h3>
                            <span class="qualification__subtile">Freelancer-Surakarta</span>
                            <div class="qualification__calender">
                                <i class="uil uil-calender-alt"></i>
                                2017-present
                            </div>
                        </div>
                    </div>

                    <!--==================== QUALIFICATION 4 ====================-->
                    <!-- <div class="qualification__data">
                        <div></div>

                        <div>
                            <span class="qualification__rounder"></span>
                            <span class="qualification__line"></span>
                        </div>

                        <div>
                            <h3 class="qualification__title">Frontend Developer</h3>
                            <span class="qualification__subtile">Freelance - Bandung</span>
                            <div class="qualification__calender">
                                <i class="uil uil-calender-alt"></i>
                                2022
                            </div>
                        </div>
                    </div> -->

                    <!--==================== QUALIFICATION 2 ====================-->
                    <!-- <div class="qualification__data">
                        <div></div>

                        <div>
                            <span class="qualification__rounder"></span>
                            <span class="qualification__line"></span>
                        </div>

                        <div>
                            <h3 class="qualification__title">UI UX Design</h3>
                            <span class="qualification__subtile">Mentor - Nurtanio University</span>
                            <div class="qualification__calender">
                                <i class="uil uil-calender-alt"></i>
                                2021
                            </div>
                        </div>
                    </div> -->

                </div>
            </div>
        </div>
    </section>
</template>

<script>
export default {
    name: 'Qualification'
}

</script>