
<script>
export default {

}
</script>

<template>
  <div class="pag1">
            <div class="ancor-pag1" id="pagina-1"></div>
            <div class="main-pag1">
                <div id="left-pag1">
                    <div class="top-left-p1" id="top-left-p1"><h2 id="pagina-1">Definizione della tua professione</h2></div>
                    <div class="bottom-left-p1"><p>Breve presentazione riassuntiva</p></div>
                </div>
                <div class="right-pag1" id="right-pag1"></div>
            </div>
        </div>
</template>


<style lang="scss" scoped>
   .pag1{
    height: 1000px;
    }
    .main-pag1{
        display: flex;
        margin: auto;
        justify-content: center;
        align-items: center;
        padding-top: 300px;
    }
    #left-pag1{
        display: flex;
        flex-direction: column;
    }
    .top-left-p1{
        height: 148px;
        
    }
    .bottom-left-p1{
        margin-left: 1px;
        margin-top: 50px;
    }
    .right-pag1{
        width: 630px;
        aspect-ratio: 1;
        border: 1px solid black;
    }
</style>