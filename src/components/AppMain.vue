<template>
    <!-- sezione profilo -->
    <section class="profile">
        <div class="d-flex justify-content-center align-items-center">
            <div class="pic-container">
                <img src="../assets/Foto cv.jpg" alt="Luigi Riva Foto">
            </div>
            <div class="description p-4 text-center">
                <p>Hello i'm</p>
                <h1>Luigi Riva</h1>
                <p>Jr web developer</p>
                <div class="btn-container">
                    <button class="btn"><a href="https://www.linkedin.com/in/luigi-antony-riva/" target="_blank"><img src="../assets/linkedin.png"></img></a></button>
                    <button class="btn"><a href="https://github.com/LuigiRiva99" target="_blank"><img src="../assets/github.png"></img></a></button>
                    <button class="btn"><a href="/public/LUIGI ANTONY RIVA CV INV.pdf" target="_blank">CV</a></button>
                </div>
            </div>
        </div>
    </section>

    <!-- sezione about -->
     <section class="about">
        <div class="container">
            <div class="row justify-content-center text-center">
                <h2 class="mb-5">About Me</h2>
                <div class="col-4 education-container">
                    <div class="d-flex align-items-center justify-content-center">
                        <img class="icon" src="../assets/education.png" alt="">
                        <h3 class=" m-0">Education</h3>
                    </div>
                    <div class="boolean-container d-flex align-items-center">
                        <div class="d-flex align-items-center justify-content-center">   
                            <img class="icon" src="../assets/education.png" alt="">
                            <h3 class=" m-0">JR Full Stack Developer Trainee</h3>
                        </div>
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
                                <img class="icon" src="../assets/experience.png" alt="">
                                <h3 class=" m-0">HTML</h3>
                            </div>
                            <div class="col-4 d-flex align-items-center tech">
                                <img class="icon" src="../assets/experience.png" alt="">
                                <h3 class=" m-0">CSS</h3>
                            </div>
                            <div class="col-4 d-flex align-items-center tech">
                                <img class="icon" src="../assets/experience.png" alt="">
                                <h3 class=" m-0">SASS</h3>
                            </div>
                            <div class="col-4 d-flex align-items-center tech">
                                <img class="icon" src="../assets/experience.png" alt="">
                                <h3 class=" m-0">Bootstrap</h3>
                            </div>
                            <div class="col-4 d-flex align-items-center tech">
                                <img class="icon" src="../assets/experience.png" alt="">
                                <h3 class=" m-0">JS</h3>
                            </div>
                            <div class="col-4 d-flex align-items-center tech">
                                <img class="icon" src="../assets/experience.png" alt="">
                                <h3 class=" m-0">Vue JS</h3>
                            </div>
                            <div class="col-4 d-flex align-items-center tech">
                                <img class="icon" src="../assets/experience.png" alt="">
                                <h3 class=" m-0">Vite</h3>
                            </div>
                            <div class="col-4 d-flex align-items-center tech">
                                <img class="icon" src="../assets/experience.png" alt="">
                                <h3 class=" m-0">PHP</h3>
                            </div>
                            <div class="col-4 d-flex align-items-center tech">
                                <img class="icon" src="../assets/experience.png" alt="">
                                <h3 class=" m-0">Laravel</h3>
                            </div>
                            <div class="col-4 d-flex align-items-center tech">
                                <img class="icon" src="../assets/experience.png" alt="">
                                <h3 class=" m-0">MySQL</h3>
                            </div>
                        </div>
                    </div>
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
    .pic-container{
        height: 400px;
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

    .btn{
        height: 100px;
        aspect-ratio: 1/1;
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
    }

    .experience-container{
        border: 1px solid rgb(85, 85, 85);
        border-radius: 50px;
        padding: 30px;
    }
</style>