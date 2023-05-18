<script>
    export default{
        name: "Foto"
    }
</script>

<template>
    <div class="foto-container">
        <p>Nel caso in cui non siate ancora convinti,
            trovate di seguito altre foto che sicuramente vi scioglieranno e faranno decidere che <span>ORA</span> è il momento giusto per prendere un gatto !
        </p>
        <img class="altre-foto" src="../assets/ancorajava.jpeg" alt="">
        <img class="altre-foto" src="../assets/semprejava.jpeg" alt="">
    </div>
</template>

<style>
    .foto-container{
        height: 400px;
        border-radius: 50px 40px;
        border: 5px solid pink;
        padding: 15px;
    }
    span{
            text-decoration: underline;
            color: purple;
        }

    .altre-foto{
        margin: 20px;
        widows: 200px;
        height: 300px;
        border-radius: 50px 40px;
        border: 5px solid pink;
    }
</style>