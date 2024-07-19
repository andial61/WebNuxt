<template>
     <div class="footerContainer">
       
        <div class="footerBottom"> <p>Copyright &copy;2024; Designed by <span class="designer">Andi</span></p></div>
        
    </div>



</template>

<script>
export default {

}
</script>

<style>
*{
    padding: 0;
    margin: 0;
    box-sizing: border-box;
}
footer{
    background-color: #111;
}
.footerContainer{
    width: auto;
    padding: 70px 30px 20px ;
}
.footerBottom{
    background-color: #000;
    padding: 20px;
    text-align: center;
}
.footerBottom p{
    color: white;
}
.designer{
    opacity: 0.7;
    text-transform: uppercase;
    letter-spacing: 1px;
    font-weight: 400;
    margin: 0px;
}
</style>