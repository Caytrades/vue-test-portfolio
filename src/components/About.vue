<template>
    <div class="about-container">
        <div class="curve-top">
        <svg data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1200 120" preserveAspectRatio="none">
            <path d="M321.39,56.44c58-10.79,114.16-30.13,172-41.86,82.39-16.72,168.19-17.73,250.45-.39C823.78,31,906.67,72,985.66,92.83c70.05,18.48,146.53,26.09,214.34,3V0H0V27.35A600.21,600.21,0,0,0,321.39,56.44Z" class="shape-fill"></path>
        </svg>
        </div>
        <div class="first">
            <div class="details">
                <h3>Let's Get To Know Eachother</h3>
                <h6>About Me</h6>
            </div>
        </div>
    </div>

    
  
</template>

<script>
export default {
    
}
</script>

<style scoped>
.about-container{
    position: relative;
}

.curve-top {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    overflow: hidden;
    line-height: 0;
}

.curve-top svg {
    position: relative;
    display: block;
    width: calc(168% + 1.3px);
    height: 147px;
    transform: rotateY(180deg);
}

.curve-top .shape-fill {
    fill: #0D6EFD;
}

.first{
    position: absolute;
}

.details{
    font-family:Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
    margin-top: 20px;
    color: white;
    margin-left: 20px;
}



</style>