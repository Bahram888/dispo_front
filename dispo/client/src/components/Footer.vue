<template>
    <div class="footer_container">
            <ul>
                <li><a href="#">Log In</a></li>
                <li><a href="#">Sign Up</a></li>
                <li><a href="#">Partners</a></li>
                <li><a href="#">About</a></li>
                <li><a href="#">FAQ</a></li>
            </ul>
            <div class="logo_footer">
                <img src="../assets/images/logo_dispo.png" alt="">
            </div>
            <ul>
                <li><a href="#">Terms of Service</a></li>
                <li><a href="#">Privacy Policy</a></li>
                <li><a href="#">Cookies</a></li>
            </ul>
    </div>
</template>
<script>
import '../assets/images/logo_dispo.png'
export default {
    
}
</script>
<style scoped>
    ul{
        display: flex;
        align-items: center;
        list-style-type: none;
        width: 45%;
        justify-content: space-around;
    }
    a{
        text-decoration: none;
        color: #000;
    }
    .logo_footer{
        display: flex;
        align-items: center;
        justify-content: center;
        width: 50%;
    }
    .footer_container{
        display: flex;
        align-items: center;
        width: 84%;
        margin: auto;
        font-family: system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
        font-weight: 700;
        justify-content: space-around;
    }
</style>