
<script>
export default {

}
</script>

<template>
    <div class="pag2">
        <div class="ancor-pag2" id="pagina-2"></div>
        <div class="top-pag2">
            <div class="left-top-pag2" id="left-top-pag2">
            <h2 >Chi sono</h2>
            <p>Breve presentazione</p>
            <p>Cosa faccio ora</p>
            <p>Quali sono i miei obbiettivi</p>
            </div>
            <div class="right-top-pag2" id="right-top-pag2"></div>
        </div>
        <div class="bottom-pag2">
                <div class="bottom-left-pag2" id="bottom-left-pag2">
                    <div class="skill" id="skill">
                        <div class="nome-skill"><h3>Skill1</h3></div>
                        <div class="barra-skill">
                            <div class="capacita-skill prima"></div>
                        </div>
                    </div>
                    <div class="skill" id="skill">
                        <div class="nome-skill"><h3>Skill 4</h3></div>
                        <div class="barra-skill">
                            <div class="capacita-skill seconda"></div>
                        </div>
                    </div>
                    <div class="skill" id="skill">
                        <div class="nome-skill"><h3>Skill 2</h3></div>
                        <div class="barra-skill">
                            <div class="capacita-skill terza"></div>
                        </div>
                    </div>
                    <div class="skill" id="skill">
                        <div class="nome-skill"><h3>Skill 5</h3></div>
                        <div class="barra-skill">
                            <div class="capacita-skill quarta"></div>
                        </div>
                    </div>
                    <div class="skill" id="skill">
                        <div class="nome-skill"><h3>Skill 3</h3></div>
                        <div class="barra-skill">
                            <div class="capacita-skill quinta"></div>
                        </div>
                    </div>
                    <div class="skill" id="skill">
                        <div class="nome-skill"><h3>Skill 6</h3></div>
                        <div class="barra-skill">
                            <div class="capacita-skill sesta"></div>
                        </div>
                    </div>
                </div>
                <div class="bottom-right-pag2" id="bottom-right-pag2">
                    Scarica il CV
                </div>
            </div>
        <div class="img3"><h2 ></h2></div>
        <div class="ancor-pag3" id="pagina-3"></div>
    </div>
</template>


<style lang="scss" scoped>
   .pag2{
    height: 800px;
    margin: 0px 100px;
}
.top-pag2{
    display: flex;
    justify-content: space-between;
}
.left-top-pag2{
    margin-top: 100px;
}
.right-top-pag2{
    width: 300px;
    height: 300px;
    background-color: #7189AD;
    margin-top: 50px;
    border-radius: 50%;
}
.bottom-pag2{
    height: 200px;
    margin: auto;
    display: flex;
    flex-wrap: wrap;
}
.bottom-left-pag2{
    width: 80%;
    height: 200px;
    display: flex;
    flex-wrap: wrap;
}
.skill{
    width: 45%;
    height: 33%;
    margin-right: 5%;
    display: flex;
    align-items: center;
}
.nome-skill{
    width: 30%;
}
.barra-skill{
    width: 70%;
    height: 40px;
    background-color: #EEEEEE;
    border-radius: 20px;
    margin-right: 10px;
    display: flex;
    align-items: center;
    
}
.capacita-skill{
    background: rgb(113,137,173);
    background: linear-gradient(284deg, rgba(113,137,173,1) 0%, rgba(180,210,255,1) 100%);
    height: 28px;
    border-radius: 20px;
    margin-left: 10px;
}
 .prima{
    width: 60%;
}
.seconda{
    width: 10%;
}
.terza{
    width: 20%;
}
.quarta{
    width: 45%;
}
.quinta{
    width: 90%;
}
.sesta{
    width: 80%;
}
.bottom-right-pag2{
    width: 150px;
    height: 50px;
    background: rgb(113,137,173);
    background: linear-gradient(284deg, rgba(113,137,173,1) 0%, rgba(180,210,255,1) 100%);
    align-self: flex-end;
    border-radius: 20px;
    margin-bottom: 10px;
    display: flex;
    justify-content: center;
    align-items: center;
    color: white;
    font-size: 20px;
}
.bottom-right-pag2:hover{
    background: rgb(113,137,173);
    background: linear-gradient(90deg, rgba(113,137,173,1) 0%, rgba(180,210,255,1) 100%);
}
.img3{
    height: 200px;
    margin-top: 150px;
    background: rgb(113,137,173);
}
</style>