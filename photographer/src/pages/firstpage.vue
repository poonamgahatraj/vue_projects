<template>
    <div class="image">
        <img src="public/assets/photographer.jpg" style="height:400px;width:100%">

        <div class="text">
            <h1 style="font-size:50px">I am John Doe</h1>
            <p>And I'm a Photographer</p>
            <button>Hire me</button>
        </div>
    </div>
</template>

<style>
.image{
    width:100vw;
    background-image:linear-gradient(rgba(0, 0, 0, 0.5), rgba(0, 0, 0, 0.5)), url("photographer.jpg");
}

.text{
    position: absolute;
    top: 20%;
    right: 40%;
    color: white;
    text-align: center;
    width: 20%;
}
</style>