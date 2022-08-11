<template>
    <!--=============== HEADER ===============-->
    <header class="header" id="header">
        <nav class="nav container">
            <a href="#home" class="nav__logo">ALPHA</a>
            <div class="nav__menu">
                <ul class="nav__list">
                    <li class="nav__item">
                        <a href="#home" class="nav__link active-link">
                            <i class='bx bx-home-alt'></i>
                        </a>
                    </li>

                    <li class="nav__item">
                        <a href="#about" class="nav__link">
                            <i class='bx bx-user'></i>
                        </a>
                    </li>

                    <li class="nav__item">
                        <a href="#skills" class="nav__link">
                            <i class='bx bx-book'></i>
                        </a>
                    </li>

                    <li class="nav__item">
                        <a href="#work" class="nav__link">
                            <i class='bx bx-briefcase-alt-2'></i>
                        </a>
                    </li>

                    <li class="nav__item">
                        <a href="#contact" class="nav__link">
                            <i class='bx bx-message-square-detail'></i>
                        </a>
                    </li>
                </ul>
            </div>

            <!-- Theme Change Button -->
            <i class='bx bx-moon change-theme' id="theme-button"></i>
            </nav>
    </header>

    <!--=============== MAIN ===============-->
    <main class="main">
        <!--=============== HOME ===============-->
        <section class="home section" id="home">
            <div class="home__container container grid">
                <div class="home__data">
                    <span class="home__greeting">Hello, I'm</span>
                    <h1 class="home__name">Zain Ali</h1>
                    <h3 class="home__education">Web Developer</h3>

                    <div class="home__buttons">
                        <a download="" href="#" class="button button--ghost">Download CV</a>
                        <a href="#about" class="button">About me</a>
                    </div>
                </div>

                <div class="home__handle">
                    <img src="../assets/img/perfil.png" alt="" class="home__img img_profile">
                </div>

                <div class="home__social">
                    <a href="https://www.linkedin.com/in/zainali117/" class="home__social-link" target="_blank">
                        <i class='bx bxl-linkedin-square'></i>
                    </a>
                    <a href="https://github.com/ZainAli104" class="home__social-link" target="_blank">
                        <i class='bx bxl-github'></i>
                    </a>
                    <a href="https://www.instagram.com/__zainx__lyrix/" class="home__social-link" target="_blank">
                        <i class='bx bxl-instagram'></i>
                    </a>
                </div>

                <a href="#about" class="home__scroll">
                    <i class='bx bx-mouse home__scroll-icon'></i>
                    <span class="home__scroll-name">Scroll Down</span>
                </a>
            </div>
        </section>

        <!--=============== ABOUT ===============-->
        <section class="about section" id="about">
            <span class="section__subtitle">My Intro</span>
            <h2 class="section__title">About Me</h2>


            <div class="about__container container grid">
                <img src="../assets/img/about.jpg" alt="image" class="about__img">

                <div class="about__data">
                    <div class="about__info">
                        <div class="about__box">
                            <i class='bx bx-award about__icon'></i>
                            <h3 class="about__title">Experience</h3>
                            <span class="about__subtitle">2 Years Working</span>
                        </div>

                        <div class="about__box">
                            <i class='bx bx-briefcase-alt about__icon'></i>
                            <h3 class="about__title">Completed</h3>
                            <span class="about__subtitle">10 + Projects</span>
                        </div>

                        <div class="about__box">
                            <i class='bx bx-support about__icon'></i>
                            <h3 class="about__title">Support</h3>
                            <span class="about__subtitle">Online 24/7</span>
                        </div>
                    </div>

                    <p class="about__description">
                        Frontend developer, I create web pages with <span class="colo"> UI / UX </span>user interface,
                        I have years of experience and many clients are happy
                        with the projects carried out.
                    </p>

                    <a href="#contact" class="button">Contact Me</a>
                </div>
            </div>
        </section>

        <!--=============== SKILLS ===============-->
        <section class="skills section" id="skills">
            <span class="section__subtitle">My abilities</span>
            <h2 class="section__title">My Experience</h2>

            <div class="skills__container container grid">
                <div class="skills__content">
                    <h3 class="skills__title">Frontend developer</h3>

                    <div class="skills__box">
                        <div class="skills__group">
                            <div class="skills__data">
                                <i class='bx bxs-badge-check'></i>

                                <div>
                                    <h3 class="skills__name">HTML</h3>
                                    <span class="skills__level">Advanced</span>
                                </div>
                            </div>

                            <div class="skills__data">
                                <i class='bx bxs-badge-check'></i>

                                <div>
                                    <h3 class="skills__name">CSS</h3>
                                    <span class="skills__level">Advanced</span>
                                </div>
                            </div>

                            <div class="skills__data">
                                <i class='bx bxs-badge-check'></i>

                                <div>
                                    <h3 class="skills__name">JavaScript</h3>
                                    <span class="skills__level">Advanced</span>
                                </div>
                            </div>
                        </div>

                        <div class="skills__group">

                            <div class="skills__data">
                                <i class='bx bxs-badge-check'></i>

                                <div>
                                    <h3 class="skills__name">Vue Js</h3>
                                    <span class="skills__level">Expert</span>
                                </div>
                            </div>

                            <div class="skills__data">
                                <i class='bx bxs-badge-check'></i>

                                <div>
                                    <h3 class="skills__name">React</h3>
                                    <span class="skills__level">Expert</span>
                                </div>
                            </div>

                            <div class="skills__data">
                                <i class='bx bxs-badge-check'></i>

                                <div>
                                    <h3 class="skills__name">Python</h3>
                                    <span class="skills__level">Advanced</span>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>

                <div class="skills__content">
                    <h3 class="skills__title">Frontend Frameworks and <br> Backend Developer</h3>

                    <div class="skills__box">
                        <div class="skills__group">
                            <div class="skills__data">
                                <i class='bx bxs-badge-check'></i>

                                <div>
                                    <h3 class="skills__name">Vuetify</h3>
                                    <span class="skills__level">Advanced</span>
                                </div>
                            </div>

                            <div class="skills__data">
                                <i class='bx bxs-badge-check'></i>

                                <div>
                                    <h3 class="skills__name">Node Js</h3>
                                    <span class="skills__level">Basic</span>
                                </div>
                            </div>

                            <div class="skills__data">
                                <i class='bx bxs-badge-check'></i>

                                <div>
                                    <h3 class="skills__name">Bootstrap</h3>
                                    <span class="skills__level">Intermediate</span>
                                </div>
                            </div>
                        </div>

                        <div class="skills__group">
                            <div class="skills__data">
                                <i class='bx bxs-badge-check'></i>

                                <div>
                                    <h3 class="skills__name">Laravel</h3>
                                    <span class="skills__level">Expert</span>
                                </div>
                            </div>

                            <div class="skills__data">
                                <i class='bx bxs-badge-check'></i>

                                <div>
                                    <h3 class="skills__name">Firebase</h3>
                                    <span class="skills__level">Advanced</span>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!--=============== SERVICES ===============-->
        <section class="services section">
            <span class="section__subtitle">My Services</span>
            <h2 class="section__title">What I Offer</h2>

            <div class="services__container container grid">
                <div class="services__card">
                    <h3 class="services__title">Frontend <br> Developer</h3>

                    <span class="services__button" @click="activeModal">
                        See More <i class='bx bx-right-arrow-alt services__icon'></i>
                    </span>

                    <div class="services__modal">
                        <div class="services__modal-content">
                            <i class='bx bx-x services__modal-close'></i>

                            <h3 class="services__modal-title">Frontend Developer</h3>
                            <p class="services__title-description">Service with more than 2 years of experience.
                                Providing quality work to clients and companies.</p>

                            <ul class="services__modal-list">
                                <li class="services__modal-item">
                                    <i class='bx bx-check services__modal-icon'></i>
                                    <p class="services__modal-info">I develop the user interface with framworks like Vue and React Js.</p>
                                </li>

                                <li class="services__modal-item">
                                    <i class='bx bx-check services__modal-icon'></i>
                                    <p class="services__modal-info">Web page development.</p>
                                </li>

                                <li class="services__modal-item">
                                    <i class='bx bx-check services__modal-icon'></i>
                                    <p class="services__modal-info">I create ux element interactions.</p>
                                </li>

                                <li class="services__modal-item">
                                    <i class='bx bx-check services__modal-icon'></i>
                                    <p class="services__modal-info">I can rank your company brand using SEO.</p>
                                </li>

                                <li class="services__modal-item">
                                    <i class='bx bx-check services__modal-icon'></i>
                                    <p class="services__modal-info">I use Sass, Bootstarp, Tailwind CSS and Vuetify.</p>
                                </li>
                            </ul>
                        </div>
                    </div>
                </div>

                <div class="services__card">
                    <h3 class="services__title">Ui/Ux <br> Designer</h3>

                    <span class="services__button">
                        See More <i class='bx bx-right-arrow-alt services__icon'></i>
                    </span>

                    <div class="services__modal">
                        <div class="services__modal-content">
                            <i class='bx bx-x services__modal-close'></i>

                            <h3 class="services__modal-title">Ui/Ux Designer</h3>
                            <p class="services__title-description">Service with more than 1 years of experience.
                                Providing quality work to clients and companies.</p>

                            <ul class="services__modal-list">
                                <li class="services__modal-item">
                                    <i class='bx bx-check services__modal-icon'></i>
                                    <p class="services__modal-info">I develop the user interface.</p>
                                </li>

                                <li class="services__modal-item">
                                    <i class='bx bx-check services__modal-icon'></i>
                                    <p class="services__modal-info">Web page development.</p>
                                </li>

                                <li class="services__modal-item">
                                    <i class='bx bx-check services__modal-icon'></i>
                                    <p class="services__modal-info">I create ux element interactions.</p>
                                </li>

                                <li class="services__modal-item">
                                    <i class='bx bx-check services__modal-icon'></i>
                                    <p class="services__modal-info">I position your company brand.</p>
                                </li>

                                <li class="services__modal-item">
                                    <i class='bx bx-check services__modal-icon'></i>
                                    <p class="services__modal-info">Ux for inhance user experience.</p>
                                </li>
                            </ul>
                        </div>
                    </div>
                </div>

                <div class="services__card">
                    <h3 class="services__title">Backend <br> Developer</h3>

                    <span class="services__button">
                        See More <i class='bx bx-right-arrow-alt services__icon'></i>
                    </span>

                    <div class="services__modal">
                        <div class="services__modal-content">
                            <i class='bx bx-x services__modal-close'></i>

                            <h3 class="services__modal-title">Backend Developer</h3>
                            <p class="services__title-description">Service with more than 2 years of experience.
                                Providing quality work to clients and companies.</p>

                            <ul class="services__modal-list">
                                <li class="services__modal-item">
                                    <i class='bx bx-check services__modal-icon'></i>
                                    <p class="services__modal-info">I develop backend dashboard page for many clients.</p>
                                </li>

                                <li class="services__modal-item">
                                    <i class='bx bx-check services__modal-icon'></i>
                                    <p class="services__modal-info">Connect backend to web pages.</p>
                                </li>

                                <li class="services__modal-item">
                                    <i class='bx bx-check services__modal-icon'></i>
                                    <p class="services__modal-info">I create database managment system.</p>
                                </li>

                                <li class="services__modal-item">
                                    <i class='bx bx-check services__modal-icon'></i>
                                    <p class="services__modal-info">I use firebase for many projects.</p>
                                </li>

                                <li class="services__modal-item">
                                    <i class='bx bx-check services__modal-icon'></i>
                                    <p class="services__modal-info">API intigrations with frontend and also backend.</p>
                                </li>
                            </ul>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!--=============== WORK ===============-->
        <section class="work section" id="work">
            <span class="section__subtitle">My Portfolio</span>
            <h2 class="section__title">Recent Works</h2>

            <div class="work__filters">
                <span class="work__item active__work" data-filter="all">All</span>
                <span class="work__item" data-filter=".web">Web</span>
                <span class="work__item" data-filter=".movil">Movil</span>
                <span class="work__item" data-filter=".design">Design</span>
            </div>

            <div class="work__container container grid">
                <div class="work__card mix web">
                    <img src="../assets/img/Cars-website.png" alt="" class="work__img">

                    <h3 class="work__title">Car Selling Website</h3>

                    <a href="https://zain-12-project.surge.sh/" target="_blank" class="work__button">
                        Demo <i class='bx bx-right-arrow-alt work__icon'></i>
                    </a>
                </div>

                <div class="work__card mix movil">
                    <img src="../assets/img/NFT.png" alt="" class="work__img">

                    <h3 class="work__title">NFT Web3.0 Website</h3>

                    <a href="https://zain-nft-1.surge.sh/" target="_blank" class="work__button">
                        Demo <i class='bx bx-right-arrow-alt work__icon'></i>
                    </a>
                </div>

                <div class="work__card mix design">
                    <img src="../assets/img/E-Commerce-website02.png" alt="" class="work__img">

                    <h3 class="work__title">Brand design</h3>

                    <a href="https://zain-18-project.surge.sh/" target="_blank" class="work__button">
                        Demo <i class='bx bx-right-arrow-alt work__icon'></i>
                    </a>
                </div>

                <div class="work__card mix web">
                    <img src="../assets/img/Portfolio-website-2.png" alt="" class="work__img">

                    <h3 class="work__title">Portfolio Website</h3>

                    <a href="https://zain-17-project.surge.sh/" target="_blank" class="work__button">
                        Demo <i class='bx bx-right-arrow-alt work__icon'></i>
                    </a>
                </div>

                <div class="work__card mix movil">
                    <img src="../assets/img/E-Commerce.png" alt="" class="work__img">

                    <h3 class="work__title">E-Commerece Website</h3>

                    <a href="http://zain-project-e-commerce-2.surge.sh/" target="_blank" class="work__button">
                        Demo <i class='bx bx-right-arrow-alt work__icon'></i>
                    </a>
                </div>
            </div>
        </section>

        <!--=============== TESTIMONIALS ===============-->
        <section class="testimonial section">
            <span class="section__subtitle">My clients say</span>
            <h2 class="section__title">Testimonial</h2>

            <div class="testimonial__container container swiper">
                <div class="swiper-wrapper">
                    <div class="testimonial__card swiper-slide">
                        <img src="../assets/img/testimonial1.png" alt="" class="testimonial__img">

                        <h3 class="testimonial__name">Jhon Doe</h3>
                        <p class="testimonial__description">
                            A really good job, all aspects of the project were
                            followed step by step and with good results.
                        </p>
                    </div>

                    <div class="testimonial__card swiper-slide">
                        <img src="../assets/img/testimonial2.png" alt="" class="testimonial__img">

                        <h3 class="testimonial__name">Paula Vusy</h3>
                        <p class="testimonial__description">
                            He is really a nice person that helps me in my project of my business and he also helps me to run my website.
                        </p>
                    </div>

                    <div class="testimonial__card swiper-slide">
                        <img src="../assets/img/about.jpg" alt="" class="testimonial__img">

                        <h3 class="testimonial__name">Ms Liopez</h3>
                        <p class="testimonial__description">
                            Zain is a best and experienced developer. He did many projects of mine and he gaves his best for me.
                        </p>
                    </div>
                </div>

                <div class="swiper-pagination"></div>
            </div>
        </section>

        <!--=============== CONTACT ===============-->
        <section class="contact section" id="contact">
            <span class="section__subtitle">Get in touch</span>
            <h2 class="section__title">Contact Me</h2>

            <div class="contact__container container grid">
                <div class="contact__content">
                    <h3 class="contact__title">Talk to me</h3>

                    <div class="contact__info">
                        <div class="contact__card">
                            <i class='bx bx-mail-send contact__card-icon'></i>
                            <h3 class="contact__card-title">Email</h3>
                            <span class="contact__card-data">chzainali6363@gmail.com</span>

                            <a href="mailto:chzainali6363@correo.com" target="_blank" class="contact__button">
                                Write me <i class='bx bx-right-arrow-alt contact__button-icon'></i>
                            </a>
                        </div>

                        <div class="contact__card">
                            <i class='bx bxl-whatsapp contact__card-icon'></i>
                            <h3 class="contact__card-title">Whatsapp</h3>
                            <span class="contact__card-data">+92 3209642852</span>

                            <a href="https://api.whatsapp.com/send?phone=+923209642852&text=Hello, more information!"
                                target="_blank" class="contact__button">
                                Write me <i class='bx bx-right-arrow-alt contact__button-icon'></i>
                            </a>
                        </div>

                        <div class="contact__card">
                            <i class='bx bxl-messenger contact__card-icon'></i>
                            <h3 class="contact__card-title">Messenger</h3>
                            <span class="contact__card-data">Zain Ali</span>

                            <a href="https://m.me/chzain.ali.7921" target="_blank" class="contact__button">
                                Write me <i class='bx bx-right-arrow-alt contact__button-icon'></i>
                            </a>
                        </div>
                    </div>
                </div>

                <div class="contact__content">
                    <h3 class="contact__title">Write me your project</h3>

                    <form action="https://formsubmit.co/chzainali6363@gmail.com" method="POST" class="contact__form">
                        <div class="contact__form-div">
                            <label for="name" class="contact__form-tag">Name</label>
                            <input type="text" name="name" placeholder="Insert your name" class="contact__form-input" id="name" required>
                        </div>

                        <div class="contact__form-div">
                            <label for="email" class="contact__form-tag">Mail</label>
                            <input type="email" name="email" placeholder="Insert your email" class="contact__form-input" id="email" required>
                        </div>

                        <div class="contact__form-div contact__form-area">
                            <label for="message" class="contact__form-tag">Project</label>
                            <textarea name="message" id="message" cols="30" rows="10" placeholder="Write your project"
                                class="contact__form-input"></textarea>
                        </div>

                        <button class="button" type="submit">Send Message</button>
                    </form>
                </div>
            </div>
        </section>
    </main>

    <!--=============== FOOTER ===============-->
    <footer class="footer">
        <div class="footer__container container">
            <h1 class="footer__title">Alpha</h1>

            <ul class="footer__list">
                <li>
                    <a href="#about" class="footer__link">About</a>
                </li>

                <li>
                    <a href="#work" class="footer__link">Projects</a>
                </li>

                <li>
                    <a href="#contact" class="footer__link">Contact</a>
                </li>
            </ul>

            <ul class="footer__social">
                <a href="https://www.facebook.com/" target="_blank" class="footer__social-link">
                    <i class='bx bxl-facebook'></i>
                </a>
                <a href="https://www.instagram.com/__zainx__lyrix/" target="_blank" class="footer__social-link">
                    <i class='bx bxl-instagram'></i>
                </a>
                <a href="https://twitter.com/__Zainx__117" target="_blank" class="footer__social-link">
                    <i class='bx bxl-twitter'></i>
                </a>
            </ul>

            <span class="footer__copy">
                &#169; 2022. All rigths reserved Zain Ali
            </span>
        </div>
    </footer>
</template>

<script>
export default {
    mounted() {
        /*=============== CHANGE BACKGROUND HEADER ===============*/
        function scrollHeader() {
        const header = document.getElementById("header");
        // When the scroll is greater than 50 viewport height, add the scroll-header class to the header tag
        if (this.scrollY >= 50) header.classList.add("scroll-header");
        else header.classList.remove("scroll-header");
        }
        window.addEventListener("scroll", scrollHeader);

        /*=============== SERVICES MODAL ===============*/
        const modalViews = document.querySelectorAll(".services__modal"),
        modalBtns = document.querySelectorAll(".services__button"),
        modalClose = document.querySelectorAll(".services__modal-close");

        let modal = function (modalClick) {
        modalViews[modalClick].classList.add("active-modal");
        };

        modalBtns.forEach((mb, i) => {
        mb.addEventListener("click", () => {
            modal(i);
        });
        });

        modalClose.forEach((mc) => {
        mc.addEventListener("click", () => {
            modalViews.forEach((mv) => {
            mv.classList.remove("active-modal");
            });
        });
        });

        /* Link active work */
        const linkWork = document.querySelectorAll(".work__item");

        function activeWork() {
        linkWork.forEach((l) => l.classList.remove("active__work"));
        this.classList.add("active__work");
        }

        linkWork.forEach((l) => l.addEventListener("click", activeWork));

        /*=============== SCROLL SECTIONS ACTIVE LINK ===============*/
        const sections = document.querySelectorAll("section[id]");

        function scrollActive() {
        const scrollY = window.pageYOffset;

        sections.forEach((current) => {
            const sectionHeight = current.offsetHeight,
            sectionTop = current.offsetTop - 58,
            sectionId = current.getAttribute("id");

            if (scrollY > sectionTop && scrollY <= sectionTop + sectionHeight) {
            document
                .querySelector(".nav__menu a[href*=" + sectionId + "]")
                .classList.add("active-link");
            } else {
            document
                .querySelector(".nav__menu a[href*=" + sectionId + "]")
                .classList.remove("active-link");
            }
        });
        }
        window.addEventListener("scroll", scrollActive);

        /*=============== LIGHT DARK THEME ===============*/
        const themeButton = document.getElementById("theme-button");
        const lightTheme = "light-theme";
        const iconTheme = "bx-sun";

        // Previously selected topic (if user selected)
        const selectedTheme = localStorage.getItem("selected-theme");
        const selectedIcon = localStorage.getItem("selected-icon");

        // We obtain the current theme that the interface has by validating the light-theme class
        const getCurrentTheme = () =>
        document.body.classList.contains(lightTheme) ? "dark" : "light";
        const getCurrentIcon = () =>
        themeButton.classList.contains(iconTheme) ? "bx bx-moon" : "bx bx-sun";

        // We validate if the user previously chose a topic
        if (selectedTheme) {
        // If the validation is fulfilled, we ask what the issue was to know if we activated or deactivated the light
        document.body.classList[selectedTheme === "dark" ? "add" : "remove"](
            lightTheme
        );
        themeButton.classList[selectedIcon === "bx bx-moon" ? "add" : "remove"](
            iconTheme
        );
        }

        // Activate / deactivate the theme manually with the button
        themeButton.addEventListener("click", () => {
        // Add or remove the light / icon theme
        document.body.classList.toggle(lightTheme);
        themeButton.classList.toggle(iconTheme);
        // We save the theme and the current icon that the user chose
        localStorage.setItem("selected-theme", getCurrentTheme());
        localStorage.setItem("selected-icon", getCurrentIcon());
        });
    },
}
</script>

<style scoped>
@import "../assets/css/styles.css";
@import "../assets/css/swiper-bundle.min.css";
</style>