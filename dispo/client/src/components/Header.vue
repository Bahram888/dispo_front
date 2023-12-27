<template>
<header>
    <div class="logo">
        <img src="../assets/images/logo_dispo.png" alt="">
    </div>
    <div class="exchange_language">
        <p>EUR  <i class="fa-solid fa-euro-sign"></i></p>
        <p>English <i class="fa-solid fa-globe"></i></p>
    </div>
    <nav>
        <ul>
            <li><a href="#" class="text_active">Transport</a></li>
            <li><a href="#">Tours</a></li>
            <li><a href="#">Partners</a></li>
            <li><a href="#">About B2B</a></li>
            <li><a href="#">Contact</a></li>
            <a href="#" class="buttonbook">Book Today</a>
        </ul>
    </nav>
    <div class="login_signup">
        <a href="#">Log In /</a>
        <a href="#">Sign Up</a>
    </div>
</header>
</template>
<script>
import '../assets/images/logo_dispo.png'
export default {
    
}
</script>
<style scoped>
*{
    padding: 0;
    margin: 0;
    box-sizing: border-box;
}
header{
    font-family: system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
    display: flex;
    height: 80px;
    padding-top: 20px;
    width: 84%;
    margin: auto;
    justify-content: space-around;
    align-items: center;
}
.text_active{
    color: #3874c3;
}
.exchange_language{
    display: flex;
    justify-content: left;
}
nav ul{
    display: flex;
    list-style-type: none;
    align-items: center;
}
nav ul li a{
    font-weight: 600;
    text-decoration: none;
    padding-left: 20px;
    color: #000;
}
.login_signup{
    display: flex;
}
.login_signup a{
    text-decoration: none;
    color: #000;
    font-weight: 600;
}
.buttonbook{
    padding: 8px 30px;
    font-weight: 600;
    margin-left: 20px;
    text-decoration: none;
    color: #ffffff;
    background-color: #231E60;
    border-radius: 10px;
}
.exchange_language p{
    font-size: 14px;
    padding-left: 20px;
    color: rgb(107, 106, 106);
}
</style>