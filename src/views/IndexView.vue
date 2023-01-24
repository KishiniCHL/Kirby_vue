<template>
    <div>
        <h1>Allo</h1>
        <div class="background_home_container">
            <img src="@/assets/9ebe8725a74c6d55893f1aa6ea6fb5e9.png" alt="background home" class="background_home_image">
        </div>
        <div class="start_container">
            <div class="start_container_img">
                <img src="@/assets/kirby_start.png" alt="start button" id="start_button">
            </div>
            <div class="starting_text">
                <p>Press enter to start</p>
            </div>
        </div>
    </div>
</template>
<script>
export default {
    name : 'IndewView'
}
</script>
<style>

/* body{
    background-color: blue;
    background-image: url(~@/assets/9ebe8725a74c6d55893f1aa6ea6fb5e9.png);
    object-fit: contain;
} */
    .background_home_container{
        position: fixed;
        left: 0;
        top: 0;
        z-index: -1;
    }
    .background_home_image{
        height: 100%;
        width: 100%;
    }

    #start_button{
        position: relative;
        z-index: 1;
    }

    .start_container_img{
        width: 50vh;
    }

    #start_button{
        width: 100%;
        height: 100%;
        object-fit: contain;
    }

    .start_container{
        width: 100%;
        height: 80%;
        display: flex;
        /* justify-content: flex-end; */
        flex-direction: column;
        align-items: center;
    }
</style>