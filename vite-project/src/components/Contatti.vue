
<script>
export default {

}
</script>

<template>
    <div >
        <div class="pag4" id="pag4">
            <div class="top-pag4">
             <h2 id="pagina-4">CONTATTI</h2>
            </div>
            <div class="bottom-pag4">
                <div class="right-pag4"></div>
                <h3>Giacomo Vigarelli</h3>
                <p>Copyright © #/09/2023. Tutti i diritti riservati.</p></div>
            </div>
        </div>
</template>


<style lang="scss" scoped>
   .pag4{
    height: 900px;
    background: rgb(142,171,215);
    background: linear-gradient(338deg, rgba(142,171,215,1) 0%, rgba(220,234,255,1) 100%);
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    align-items: center;
    
}
.pag4 h2{
    color: white;
    font-size: 50px;
    margin-top: 50px;
}
.bottom-pag4{
    display: flex;
    flex-direction: column;
    align-items: center;
    row-gap: 10px;
}
.bottom-pag4 h3{
    font-size: 30px;
    color: #6e88ad;
    
}
.bottom-pag4 p{
    font-size: 20px;
    padding-bottom: 60px;
    color: white;
}
</style>