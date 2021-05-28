<template>
<div>
     <img src="../assets/meme.png" alt="Meme">
     <p>Ti prego risparmiami...</p>
     <img src="../assets/lontra.jpg" alt="Lontra">
</div>
</template>


<script>
export default {
    name: "Hero"
}
</script>

<style>
div {
    display: flex;
    flex-direction: column;
    align-items: center;
}
img {
    width: 600px;
    border-radius: 10px;
    margin-bottom: 10px;
}
p {
    margin: 20px 0 30px 0;
    font-size: 30px;
    font-weight: bolder;
    color: rgb(21, 57, 122);
}
</style>