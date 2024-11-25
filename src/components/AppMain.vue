<template>
    <!-- sezione profilo -->
    <section class="profile" id="profile">
        <div class="d-flex justify-content-center align-items-center">
            <div class="pic-container">
                <img src="../assets/Foto cv.jpg" alt="Luigi Riva Foto">
            </div>
            <div class="description p-4 text-center">
                <p>Hello i'm</p>
                <h1 class="title">Luigi Riva</h1>
                <p>Jr web developer</p>
                <div class="btn-container">
                    <button class="btn btn-link"><a href="https://www.linkedin.com/in/luigi-antony-riva/" target="_blank"><img src="../assets/linkedin.png"></img></a></button>
                    <button class="btn btn-link"><a href="https://github.com/LuigiRiva99" target="_blank"><img src="../assets/github.png"></img></a></button>
                    <button class="btn btn-link">
                        <a href="/public/LUIGI ANTONY RIVA CV INV.pdf" target="_blank" >
                            <div class="cv-content">
                                <img src="../assets/CV-icon.png" class="cv-icon" alt="CV Icon">
                                <span class="cv-text">CV</span>
                            </div>
                        </a>
                    </button>
                </div>
            </div>
        </div>
    </section>

    <!-- sezione about -->
     <section class="about" id="about">
        <div class="container">
            <div class="row justify-content-center text-center">
                <h2 class="mb-5">About Me</h2>
                <div class="col-4 education-container">
                    <div class="d-flex align-items-center justify-content-center">
                        <img class="icon" src="../assets/education.png" alt="">
                        <h3 class=" m-0">Education</h3>
                    </div>
                    <div class="boolean-container d-flex align-items-center">
                        <a href="/src/assets/certificato-boolean.png" target="_blank">
                            <div class="d-flex align-items-center justify-content-center flex-column certificate-link">   
                                <!-- <img class="icon" src="../assets/education.png" alt=""> -->
                                <h3 class=" m-0 mb-3"><strong>JR Full Stack Developer Trainee</strong></h3>
                                <img src="../assets/boolean-icon.png" alt="">
                                <h4 class="boolean">BOOLEAN</h4>
                                <span>Vedi certificato</span>
                            </div>
                        </a>
                    </div>
                </div>
                <div class="col-8">
                    <div class="experience-container ps-5">

                        <div class="d-flex align-items-center justify-content-center pb-4">
                            <img class="icon" src="../assets/experience.png" alt="">
                            <h3 class=" m-0">Experience</h3>
                        </div>
                        <div class="row flex-wrap">
                            <div class="col-4 d-flex align-items-center tech">
                                <img class="icon" src="../assets/icon-html.png" alt="">
                                <h3 class=" m-0">HTML</h3>
                            </div>
                            <div class="col-4 d-flex align-items-center tech">
                                <img class="icon" src="../assets/icon-css.png" alt="">
                                <h3 class=" m-0">CSS</h3>
                            </div>
                            <div class="col-4 d-flex align-items-center tech">
                                <img class="icon" src="../assets/icon-sass.png" alt="">
                                <h3 class=" m-0">SASS</h3>
                            </div>
                            <div class="col-4 d-flex align-items-center tech">
                                <img class="icon" src="../assets/icon-bootstrap.png" alt="">
                                <h3 class=" m-0">Bootstrap</h3>
                            </div>
                            <div class="col-4 d-flex align-items-center tech">
                                <img class="icon" src="../assets/icon-js.png" alt="">
                                <h3 class=" m-0">JS</h3>
                            </div>
                            <div class="col-4 d-flex align-items-center tech">
                                <img class="icon" src="../assets/icon-vue.png" alt="">
                                <h3 class=" m-0">Vue JS</h3>
                            </div>
                            <div class="col-4 d-flex align-items-center tech">
                                <img class="icon" src="../assets/icon-vite.png" alt="">
                                <h3 class=" m-0">Vite</h3>
                            </div>
                            <div class="col-4 d-flex align-items-center tech">
                                <img class="icon" src="../assets/icon-php.png" alt="">
                                <h3 class=" m-0">PHP</h3>
                            </div>
                            <div class="col-4 d-flex align-items-center tech">
                                <img class="icon" src="../assets/icon-laravel.png" alt="">
                                <h3 class=" m-0">Laravel</h3>
                            </div>
                            <div class="col-4 d-flex align-items-center tech">
                                <img class="icon" src="../assets/icon-mysql.png" alt="">
                                <h3 class=" m-0">MySQL</h3>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
     </section>

    <!-- sezione projects -->
     <section class="projects" id="projects">
        <div class="text-center">
            <h2 class="mb-5">Projects</h2>
            <div class="container">
                <div class="row">
                    <div class="col-4">
                        <div class="project-container">
                            <img class="project" src="../assets/boolflix.png" alt="">
                            <h3 class="pb-3">Boolflix</h3>
                            <button class="btn"><a href="https://boolflixriva.netlify.app" target="_blank">See project</a></button>
                        </div>
                    </div>
                    <div class="col-4">
                        <div class="project-container">
                            <img class="project" src="../assets/phlox.png" alt="">
                            <h3 class="pb-3">Phlox business</h3>
                            <button class="btn"><a href="https://phloxbusiness.netlify.app/" target="_blank">See project</a></button>
                        </div>
                    </div>
                    <div class="col-4">
                        <div class="project-container">
                            <img class="project" src="../assets/vue-pokedex.png" alt="">
                            <h3 class="pb-3">Pokedex</h3>
                            <button class="btn"><a href="https://pokedexriva.netlify.app" target="_blank">See project</a></button>
                        </div>
                    </div>
                </div>
            </div>
        </div>
     </section>

    <!-- sezione contacts -->
    <section class="contacts" id="contacts">
        <div class="text-center">
            <h2 class="mb-5">Contacts</h2>
            <div class="d-flex justify-content-center">
                <div class="contact-info-container ">
                    <img
                        src="../assets/mail.png"
                        alt="Email icon"
                        class="contact-icon-mail"
                    />
                    <p><a href="mailto:examplemail@gmail.com">luigi.riva.1999@gmail.com</a></p>
                </div>
                <div class="contact-info-container ps-5">
                    <a href="https://www.linkedin.com" class="contact-link">
                        <img
                            src="../assets/linkedin.png"
                            alt="LinkedIn icon"
                            class="contact-icon"
                        />
                        <p>LinkedIn</p>
                    </a>
                </div>
            </div>
        </div>
    </section>
</template>

<script>
    export default {
        data(){

        },

        methods: {
        }
    }
</script>

<style lang="scss" scoped>

    .title{
        font-size: 50px;
        font-weight: bold;
    }

    h2{
        font-size: 40px;
        font-weight: bold;
    }
    .pic-container{
        height: 350px;
        // width: 500px;
        aspect-ratio: 1/1;
        border-radius: 50%;
        overflow: hidden;
        display: flex;
        justify-content: center;
        align-items: center;

        img{
            object-fit: cover;
            width: 400px;
        }
    }

    .about {
        margin-top: 100px;
    }

    .btn-link{
        height: 100px;
        aspect-ratio: 1/1;
    }

    .btn {
        font-weight: 600;
        transition: all 300ms ease;
        border-radius: 50%;
        padding: 0;
        height: 60px;
        margin: 20px;
        
        .cv-content {
            position: relative;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;

            .cv-icon {
                height: 60px;
                transition: opacity 0.3s ease;
            }

            .img{
                display: block;
                border: 2px solid black;
                width: 100%;
                aspect-ratio: 1/1;
                border-radius: 50%;
            }

            .cv-text {
                position: absolute;
                display: none;
                font-size: 1rem;
                font-weight: bold;
                color: black;
                transition: opacity 0.3s ease;
            }
        }

        &:hover {
            .cv-icon {
                opacity: 0;
            }

            .cv-text {
                display: block;
                opacity: 1;
            }
        }
    }



    .icon{
        height: 40px;
    }

    .tech{
        padding: 10px
    }

    .education-container{
        border: 1px solid rgb(85, 85, 85);
        border-radius: 50px;
        padding: 30px;
    }
    .boolean-container{
        height: 100%;

        .certificate-link {
            padding: 20px;
            &:hover{
                background-color: rgba(85, 85, 85, 0.06);
                border: 2px solid rgba(85, 85, 85, 0.272);
                border-radius: 20px;
            }
        }
        img{
            height: 50px;
        }

        .boolean{
            color: green;
        }
    }

    .experience-container{
        border: 1px solid rgb(85, 85, 85);
        border-radius: 50px;
        padding: 30px;
    }

    .projects{

        margin-top: 150px;

        .btn{
            border: 2px solid grey;
            height: 60px;
            border-radius: 25px;
            padding: 0px 20px;
            
            a{
                padding: 1px;
            }

            &:hover{
                border: 2px solid black;
            }
        }

        .project-container{
            border: 1px solid rgb(85, 85, 85);
            border-radius: 50px;
            padding: 20px;
            height: 600px;

            img{
                width: 100%; 
                height: 300px; 
                object-fit: cover; 
                border-radius: 15%;
                margin-bottom: 30px;
            }

            // .project1{
            //     img{
                    
            //     }
            // }
        }
    }

    .contacts{
        margin-top: 100px;
        .contact-icon{
            height: 50px;
            aspect-ratio: 1/1;
        }

        // .contact-icon-mail{
        //     height: 60px;
        //     aspect-ratio: 1/1;
        // }

        .contact-link{
            &:hover{
                text-decoration: underline;
                text-underline-offset: 8px;

                p{
                    color: black;
                }
            }
        }
    }
</style>