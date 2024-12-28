<script setup>

</script>

<template>
    <div class="top-header">
        <div class="container">
            <div class="top-header-content">

                <div class="top-header-left">
                    <h6 v-if="true">Lorem ipsum dolor sit amet consectetur, adipisicing elit. Corrupti suscipit.</h6>
                    <marquee v-else>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Corrupti suscipit, ut aliquam voluptatibus architecto consequatur ea officia obcaecati mollitia quibusdam.</marquee>
                </div>

                <div class="top-header-right">
                    <span>
                        <a href="">
                            <i class="fa-brands fa-facebook-f"></i>
                        </a>
                        
                        <a href="">
                            <i class="fa-brands fa-youtube"></i>
                        </a>
                        
                        <a href="">
                            <i class="fa-brands fa-whatsapp"></i>
                        </a>
                        
                        <a href="">
                            <i class="fa-solid fa-envelope"></i>
                            <span>diu.shakib@gmail.com</span>
                            
                        </a>

                        <a href="">
                            <i class="fa-solid fa-phone"></i>
                            <span>+880 1784801663</span>
                        </a>
                    </span>
                </div>

            </div>
        </div>
    </div>
</template>

<style scoped>
.top-header{
    background-color: var(--primary-color);
    color: #ffffff;
    padding: 10px 0;
}

.top-header-content{
    display: flex;
    justify-content: space-between;
    align-items: center;
}

.top-header-left{
    width: 60%;
}

.top-header-left h6{
    margin: 0;
}

.top-header-right a{
    color: #ffffff;
    padding: 0 5px;
}

.top-header-right a i{
    font-size: 14px;
    margin-right: 3px;
}

@media screen and (max-width: 1199px) {
    .top-header-right a span{
        display: none;
    }
}

</style>