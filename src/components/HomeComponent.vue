<template>
    <div class="home">
        <h1>First created component</h1>
        <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Voluptatem culpa quidem eligendi et. Necessitatibus reiciendis explicabo molestiae ratione esse inventore minus ipsam error assumenda, veritatis non deleniti beatae dolorum asperiores!</p>
        <button>Learn More</button>

    </div>
</template>

<script>
    export default {
        name: 'HomeComponent',
        
    }
</script>

<style  scoped>
.home{
    padding: 20px;
    text-align: start;
}
button{ 
    background: rgb(217, 255, 0);
    color: white;

}

</style>