
<script>
export default {

}
</script>

<template>
  <div class="pag3">
    <div class="top-pag3">
                <h2 id="pagina-3">I MIEI PROGETTI</h2>
                <p>Breve descrizione</p>
            </div>
            <div class="bottom-pag3">
                <div class="cards-top" id="cards-top">
                    <div class="card">
                        <div class="img-card"></div>
                        <div class="nome-card">
                            <h3>PROGETTO 1</h3>
                            <h3>Descrizione</h3>
                        </div>
                        <div class="button-card">#progetto</div>
                    </div>
                    <div class="card">
                        <div class="img-card"></div>
                        <div class="nome-card">
                            <h3>PROGETTO 1</h3>
                            <h3>Descrizione</h3>
                        </div>
                        <div class="button-card">#progetto</div>
                    </div>
                    <div class="card" id="card-center">
                        <div class="img-card"></div>
                        <div class="nome-card" id="center-card">
                            <h3>PROGETTO 3</h3>
                            <h3>Descrizione</h3>
                        </div>
                        <div class="button-card">#progetto</div>
                    </div>
                </div>
                <div class="cards-bottom" id="cards-bottom">
                    <div class="card">
                        <div class="img-card"></div>
                        <div class="nome-card">
                            <h3>PROGETTO 1</h3>
                            <h3>Descrizione</h3>
                        </div>
                        <div class="button-card">#progetto</div>
                    </div>
                    <div class="card">
                        <div class="img-card"></div>
                        <div class="nome-card">
                            <h3>PROGETTO 1</h3>
                            <h3>Descrizione</h3>
                        </div>
                        <div class="button-card">#progetto</div>
                    </div>
                </div>
            </div>
  </div>
</template>


<style lang="scss" scoped>
.pag3{
    height: 1800px;
   
}
.top-pag3{
    margin: auto;
    margin-top: 200px;
    width: 70%;
}
.cards-top{
    padding-top: 150px;
    margin: 0px 100px;
    display: flex;
    justify-content: space-between;  
}
.card{
    display: flex;
    flex-direction: column;
    align-items: center;
}
.img-card{
    width: 250px;
    height: 250px;
    border-radius: 60px;
    border: 1px solid black;
}
.nome-card{
    margin-top: 40px;
    margin-bottom: 20px;
    font-size: 20px;
}
.button-card{
    width: 200px;
    height: 50px;
    border-radius: 30px;
    background: rgb(113,137,173);
    background: linear-gradient(284deg, rgba(113,137,173,1) 0%, rgba(180,210,255,1) 100%);
    display: flex;
    justify-content: center;
    align-items: center;
    font-size: 25px;
    color: white;
}
.cards-bottom{
    padding-top: 50px;
    width: 50%;
    margin: auto;
    display: flex;
    justify-content: space-between;  
}
</style>