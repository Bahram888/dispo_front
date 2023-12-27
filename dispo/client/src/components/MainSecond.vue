<template lang="">
    <div class="container_second">
        <div class="first_container_side">
            <div class="first_container_side_top">
                <div class="first_container_side_top_left">
                    <p style="color: #4092f7;">Active</p>
                    <h3>Chauffeur</h3>
                    <img src="../assets/images/profile.png" alt="">
                    <h4>Adam Lopoto</h4>
                    <p><i class="fa-solid fa-star" style="color: #fbff00;"></i> 4.8</p>
                </div>
                <div class="first_container_side_top_right">
                    <div class="flags">
                        <img src="https://th.bing.com/th/id/R.c128e96bc62487bfbeaf86fa88c7cf20?rik=4Sx4B9%2fZi77W2Q&riu=http%3a%2f%2fimages.alphacoders.com%2f958%2f95873.jpg&ehk=XmQea%2fzD9cL0OZt%2b5WAodplbjEoRvk5zAcdrH7Ij10Q%3d&risl=&pid=ImgRaw&r=0" alt="">
                        <img src="https://th.bing.com/th/id/R.03d0f3d4b49f52b13146c51df776cae7?rik=xr3e0nML%2b7bY2g&riu=http%3a%2f%2fwallpapercave.com%2fwp%2fwc1800984.jpg&ehk=%2fHpGhEZKHB8CUzPj7b%2fgPnTRD9jibMgCZyXwI3n1ToY%3d&risl=&pid=ImgRaw&r=0" alt="">
                        <img src="https://th.bing.com/th/id/R.d4a91ea2664bc952a78889855ca15fe7?rik=HrdtZXYEbZz%2fuw&riu=http%3a%2f%2fwww.theflagman.co.uk%2fwp-content%2fuploads%2f2017%2f03%2fflag-of-Finland.jpg&ehk=R26Ptp9B%2bgtszp5bbMJHHIaA5VDrp1MTmrIzYcJNhDw%3d&risl=&pid=ImgRaw&r=0" alt="">
                    </div>
                    <div class="text_right_side">
                        <b style="font-size:12px; color:gray;">Name of the carrier</b>
                        <h4>Bambam Sia</h4>
                    </div>
                    <div class="text_right_side">
                        <b style="font-size:12px; color:gray;">National reg.nb</b>
                        <h4>"Miranda"</h4>
                    </div>
                    <a href="#" class="phone"><i class="fa-solid fa-phone" style="color: #ffffff;"></i></a>
                </div>
            </div>
            <div class="first_container_side_bottom">
                <ul>
                    <li>
                        <p><i class="fa-solid fa-circle-check" style="color: #4092f7;"></i>   Waiting Chauffeur-14.06.2022 at 12:32</p>
                    </li>
                    <li>
                        <p><i class="fa-solid fa-circle-check" style="color: #4092f7;"></i>   Chauffeur assigned-14.06.2022 at 12:32</p>
                    </li>
                    <li>
                        <p><i class="fa-solid fa-circle-check" style="color: #4092f7;"></i>   Started -14.06.2022 at 12:32</p>
                    </li>
                    <li>
                        <p><i class="fa-solid fa-circle-check" style="color: #d7d8db;"></i>   Trip in Progress</p>
                    </li>
                    <li>
                        <p><i class="fa-solid fa-circle-check" style="color: #d7d8db;"></i>   Finished</p>
                    </li>
                </ul>
            </div>
        </div>
        <div class="second_container_side">
            <div class="top_of_secondside">
                <a href="#" class="first_tpo_secondside">Trip Details</a>
                <a href="#" class="second_tpo_secondside">Return trip details</a>
            </div>
            <div class="time">
                <a href="#"><i class="fa-solid fa-arrow-left"></i></a>
                <div class="time_date" id="active_date">6 November</div>
                <div class="time_date">7 November</div>
                <div class="time_date">8 November</div>

                <a href="#"><i class="fa-solid fa-arrow-right"></i></a>
            </div>
        <div class="main_second_side_container">
            <div class="timeline">
                <div class="event"><i class="fa-solid fa-location-dot"></i></div>
                <div class="event"><i class="fa-solid fa-location-dot"></i></div>
                <div class="event"><i class="fa-solid fa-location-dot"></i></div>
            </div>
                <ul>
                    <li>
                        <p><b>Riga International Airport</b> P133,Marupe,LV-10..</p>
                        <p><i class="fa-regular fa-clock"></i> Depart: 16:45</p>
                    </li>
                    <li>
                        <p><b>Lithuania Airport</b>Road name, LT223,Lithuania</p>
                        <p style="padding-left:10px"><i class="fa-regular fa-clock"></i> Arrive: 17:20</p>
                        <p><i class="fa-regular fa-clock"></i> Depart: 19:45</p>
                    </li>
                    <li>
                        <p><b>Lithuania Airport</b>Road name, LT223,Lithuania</p>
                        <p style="padding-left:10px"><i class="fa-regular fa-clock"></i> Arrive: 20:20</p>
                        <p><i class="fa-regular fa-clock"></i> Depart: 21:45</p>
                    </li>
                </ul>    

        </div>
        <div class="map_side_container">
            <img src="../assets/images/map_for_now.png" alt="">
        </div>
        </div>
    </div>
</template>
<script>
import '../assets/images/map_for_now.png'
export default {

}
</script>

<style scoped>
* {
    padding: 0;
    margin: 0;
    box-sizing: border-box;
}
.map_side_container{
    width: 100%;
    height: 50%;
    background-color: #231E60;
    border-radius: 50px;
}
.timeline {
  width: 2px; 
  background-color: black; 
  position: relative;
  height: 100px; 
  margin-left: 10px; 
}
.map_side_container img{
    height: 100%;
    width: 100%;
    border-radius: 50px;
}
.event {
  width: 20px;
  height: 20px;
  border-radius: 50%; 
  background-color: white; 
  border: 2px solid black; 
  position: absolute; 
  left: -9px; 
  display: flex;
  align-items: center;
  justify-content: center;
}
.event i{
    font-size:13px;
}

.event:nth-child(1) { top: 0; }
.event:nth-child(2) { top: 50%; transform: translateY(-50%); }
.event:nth-child(3) { bottom: 0; }
.main_second_side_container{
    display: flex;
}
.main_second_side_container ul li{
    display: flex;
    font-size: 15px;
    padding-bottom: 20px;
    align-items: center;
    justify-content: space-between;
    padding-left: 14px;
}
.container_second {
    width: 80%;
    margin: auto;
    position: absolute;
    top: -20px;
    z-index: 10;
    margin-bottom: 40px;
    height: 75%;
    background-color: #f8f8f8;
    position: relative;
    z-index: 10;
    border-radius: 25px;
    border: 1px solid rgb(99, 96, 96);
    display: flex;
    font-family: system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
}

ul li {
    list-style-type: none;
}

.first_container_side_bottom {
    height: 52%;
    padding: 15px;
    width: 100%;
}

.first_container_side {
    width: 38%;
    height: 90%;
    display: flex;
    flex-direction: column;
    margin: 20px;
    font-family: system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif
}

.first_container_side_top {
    height: 48%;
    width: 100%;
    display: flex;
}

.first_container_side_top_left img {
    width: 100px;
    border-radius: 20px;
}

.first_container_side_top_right {
    display: flex;
    flex-direction: column;
    justify-content: space-around;
    padding: 10px;
}

.first_container_side_top_left {
    width: 50%;
    border-right: 1px solid gray;
    display: flex;
    flex-direction: column;
    padding: 20px;
}

.second_container_side {
    width: 65%;
    height: 80%;
    margin: 40px;
}

.flags {
    display: flex;
}

.flags img {
    width: 20px;
}

.phone {
    background-color: #4092f7;
    width: 45px;
    display: flex;
    align-items: center;
    justify-content: center;
    border-radius: 5px;
    height: 45px;
    text-decoration: none;
}

.top_of_secondside {
    display: flex;
    align-items: center;
    justify-content: space-evenly;
    height: 14%;
    border-bottom: 1px solid gray;
    font-family: system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
}

.top_of_secondside a {
    text-decoration: none;
}

.first_tpo_secondside {
    color: #fff;
    padding: 12px 30px;
    background-color: #231E60;
    border-radius: 20px;
    font-size: 14px;
}

.second_tpo_secondside {
    color: #000000;
    padding: 12px 30px;
    border-radius: 20px;
    border: 1px solid #000;
    font-size: 14px;
}

.time {
    display: flex;
    height: 14%;
    width: 100%;
    align-items: center;
    justify-content: space-around;
}

.time a {
    width: 40px;
    height: 40px;
    display: flex;
    align-items: center;
    justify-content: center;
    border-radius: 50%;
    text-decoration: none;
    background-color: rgb(207, 207, 207);
    color: #231E60;
}

.time_date {
    border-radius: 20px;
    font-size: 15px;
    padding: 10px 30px;
    border: 1px solid black;
}

#active_date {
    background-color: #4092f7;
    border: none;
    color: #fff;
}</style>