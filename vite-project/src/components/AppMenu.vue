
<script>
export default {

}
</script>

<template>
  <div class="header">
    <div class="logo">
            <div class="top-logo">Giacomo</div>
            <div class="bottom-logo">Vigarelli</div>
        </div>
        <div class="menu" id="menu">
            <div class="home"><a href="#pagina-1">Home</a></div>
            <div class="chi-siamo"><a href="#pagina-2">Chi sono</a></div>
            <div class="progetti"><a href="#pagina-3">Progetti</a></div>
            <div class="contatti"><a href="#pagina-4">Contatti</a></div>
            <div class="lingua"><a>IT</a></div>
            <div class="mod-notte"><button id="lightButton"><i class="far fa-moon"></i></button></div>
            
        </div>
        <div class="menu1050"><i class="fa-solid fa-bars"></i></div>
  </div>
</template>


<style lang="scss" scoped>
    .header{
    height: 126px;
    background: transparent linear-gradient(180deg, #A8C7F6 0%, #97B7E678 100%) 0% 0% no-repeat padding-box;
    display: flex;
    align-self: center;
    position: fixed;
    width: 100%;
    }
    /*-----LOGO-----*/ 
    .logo{
    color: white;
    font-size: 35px;
    width: 40%;
    }
    .top-logo{
    padding-top: 21px;
    padding-left: 57px;
    }
    .bottom-logo{
    padding-left: 123px;
    }
    /*-----MENU-----*/ 
    .menu{
    
    display: flex;
    justify-content: flex-end;
    align-self: center;
    gap: 80px;
    margin-right: 72px;
    color: #7189AD;
    font-size: 18px;
}
.home, .chi-siamo, .progetti, .contatti, .lingua{
    display: flex;
    align-items: center;
    padding: 10px 20px;
}
.home:hover{
    display: flex;
    align-items: center;
    background-color: #7189AD;
    color: white;
    border-radius: 20px;
    padding: 10px 20px;
}
.chi-siamo:hover{
    display: flex;
    align-items: center;
    background-color: #7189AD;
    color: white;
    border-radius: 20px;
    padding: 10px 20px;
}

.progetti:hover{
    display: flex;
    align-items: center;
    background-color: #7189AD;
    color: white;
    border-radius: 20px;
    padding: 10px 20px;
}

.contatti:hover{
    display: flex;
    align-items: center;
    background-color: #7189AD;
    color: white;
    border-radius: 20px;
    padding: 10px 20px;
}

.lingua:hover{
    display: flex;
    align-items: center;
    background-color: #7189AD;
    color: white;
    border-radius: 20px;
    padding: 10px 20px;
}
.mod-notte{
    display: flex;
    align-items: center;
}
.menu button{
    background: transparent;
    border: none;
}
.fa-moon{
    color: #7189AD;
    font-size: 20px;
}

body.dark{
    background: #313840;
    color: #e8f2fc;
    transition: 0.25s ease background-color;
}
body.dark .menu a{
    color: white;
}

.menu.fa-sun{
    color: #e8f2fc;
}
.menu1050{
    display: none;
    
}
</style>