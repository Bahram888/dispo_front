<template lang="">
    <div class="container_first">
        <div class="text_first_container">
            <h2>Your daily rental details</h2>
            <div class="text_menu_first">
                <p><i class="fa-regular fa-square-check"></i> Request #779</p>
                <p><i class="fa-solid fa-calendar-days"></i> Trip Starts: 18 feb - 11:00</p>
                <p><i class="fa-solid fa-user"></i> 45 people</p>
                <a href="#" class="textmenu_a_first"><i class="fa-solid fa-euro-sign"></i> Paid 12$ <i class="fa-solid fa-check"></i></a>
                <a href="#" class="textmenu_a_second">view invoice</a>
            </div>
            <div class="copy_link">
                <a href="#"> <i class="fa-regular fa-copy"></i> copy your unique trip link</a>
            </div>

        </div>
    </div>
</template>
<script>
export default {
    
}
</script>
<style scopoed>
.container_first{
    font-family: 'Oxygen', sans-serif;
    position: absolute;
    z-index: 5;
    top: 100px; 
    height: 200px;
    background-color: #231E60;
    width: 74%;
    margin: auto;
    left: 200px;
    border-radius: 25px;
    font-family: system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
}
h2{
    color: #fff;
    padding-top: 19px;
    font-family: 'Oxygen', sans-serif;
}
.textmenu_a_second{
    color: #fff;
}
.text_menu_first{
    width: 70%;
    display: flex;
    color: #fff;
    justify-content: space-around;
    align-items: center;
    font-family: 'Oxygen', sans-serif;
    padding-top: 10px;
}
.textmenu_a_first{
    color: #fff;
    padding: 5px 23px;
    text-decoration: none;
    border: 1px solid #fff;
    border-radius: 20px;
}
.copy_link a{
    text-decoration: none;
    color: #828282;
}
.copy_link{
    padding-top: 15px;
}
.text_first_container{
    display: flex;
    flex-direction: column;
    align-items: center;
}
</style>