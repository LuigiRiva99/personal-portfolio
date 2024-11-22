<template>
    <nav id="nav">
        <div class=" nav d-flex justify-content-around align-items-center">
            <div class="logo">
                LR
            </div>
            <div>
                <ul class="nav-list p-0 d-flex list-unstyled">
                    <li><a href="#about">About</a></li>
                    <li><a href="#experience">experience</a></li>
                    <li><a href="#projects">Projects</a></li>
                    <li><a href="#contacts">Contacts</a></li>
                </ul>
            </div>
        </div>
    </nav>
</template>

<script>
    export default {
        
    }
</script>

<style lang="scss" scoped>
.nav{
    height: 8vh;
    font-size: 20px;
}

.nav-list{
    gap: 20px;

    li{
        
        a:hover{
            color: black;
            text-decoration: underline;
            text-underline-offset: 10px;
        }
    }

}
</style>