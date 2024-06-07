<template>
   <div class="a-container">
        <div class="ac-c">
            <div class="about-words">
                    <div class="e-con">
                        <div class="e-box">
                         <h5>Experience</h5>
                         <p>2+ Years</p>
                        </div>
                        <div class="e-box">
                         <h5>Projects</h5>
                            <p>10+ Completed</p>
                        </div>
                        <div class="e-box">
                            <h5>Clients</h5>
                            <p>5+ Clients</p>
                        </div>
                    </div>
               
            <p>
                Lorem ipsum dolor sit amet, consectetur adipiscing elit. Etiam ut risus lacus. Quisque a posuere turpis, quis lacinia mi. Etiam cursus cursus consectetur. Duis ullamcorper in leo quis tempor. Proin pulvinar iaculis tristique. Morbi non sagittis velit, in pulvinar felis. Vivamus ultrices turpis quam, sed rutrum magna consectetur et. Nunc non elementum turpis. Integer sed purus semper, gravida quam et, commodo nibh. Suspendisse feugiat leo non tincidunt consequat. Pellentesque congue accumsan aliquam. Fusce at justo vel diam facilisis venenatis. Morbi at justo tincidunt, consectetur justo eu, gravida orci. Sed tempus sodales ligula sit amet egestas. Nam hendrerit mauris fringilla ornare iaculis.
            </p>
            </div>
            <div class="image">
                <div class="i-blue">
                    <div class="i-lightblue">
                        <div class="i-blue">
                            <div class="i-lightblue">
                                <div class="img-box">
                                    <img src="../assets/scorpion.jpg" alt="">
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
       
    </div>
</template>

<script>
export default {
    
}
</script>

<style scoped>
.a-container{
    display: flex;
    justify-content: center;
    margin-top: 150px;
    padding: 10px;
}

.ac-c{
    display: flex;
    gap: 100px;
    max-width: 1000px; 
}

.e-con{
    display: flex;
    gap: 20px;
    margin-bottom: 10px;
}

.e-box{
    padding: 10px;
    background-color: #0D6EFD ;
    color: white;
    border: solid black 2px;
    border-radius: 20px;
    width: 150px;
}

.image{
max-width: 500px;
}


.about-words{
max-width: 500px;
}



.i-blue:hover{
    width: 400px;
    background-color: rgba(0, 0, 255, 0.699);
    transition: ease 3s;
    transform: rotate(20deg);
}

.i-lightblue{
background-color: lightblue;
width: 400px;
transition: ease 3s;
transform: rotate(-20deg);
}

.img-box img{
    width: 400px;
    transform: rotate(40deg);
}

</style>