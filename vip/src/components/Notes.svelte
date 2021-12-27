<div class="main">
    <h2>
        Notas
    </h2>
    
    <hr>
    <h3>
        Paleta de color
    </h3>
    
    <div class="pallete-container">
        <div class="color color1">
            0c0c0c
        </div>

        <div class="color color2">
            fbaf00
        </div>

        <div class="color color3">
            fbaf00
        </div>

        <div class="color color4">
            e4f1ee
        </div>

        <div class="color color5">
            df9c00
        </div>
    </div>
    <h3>
        Librerias
    </h3>
    <div>
        <ul>
            <li>Iconos <a href="https://fonts.google.com/icons?selected=Material+Icons+Outline">Google Material Icons</a></li>
            <li>Fuentes <a href="https://fonts.google.com/share?selection.family=Libre%20Franklin:wght@500;800">Libre Franklin</a></li>
        </ul>
    </div>
    <h3>
        IMPORTANTE
    </h3>
    <div class="advice">
        Con este diseño intento ejemplificar, como mejoraria la apariencia de la plataforma, si se estandarizan herramientas como iconos <br>
        tipografias o colores. Tambien pienso que apartir de este diseño podriamos elevar la experiencia de usuario hasta hacer nuestra plataforma amable con el usuario.
    </div>
</div>

<style>
    /* your styles go here */
    .main{
        padding:1em;
        background: var(--light);
        border-radius: 15px;
        width:360px;
    }

    h2{
        margin-bottom: 0.6em;
    }
    .pallete-container{
        display:flex;
        flex-wrap:wrap;
        width:100%;
        margin: 1em 0.5em;
    }
    .color{
        margin: 0.18em;
        padding: 1.5em;
        width:30%;
        height:100%;
        display: flex;
        justify-content: center;
        align-items:center;
        border-radius:18px;
    }
    .color1{color:var(--light); background: var(--dark);}
    .color2{background: var(--light);}
    .color3{background: var(--yellow);}
    .color4{background: #e4f1ee;}
    .color5{background:#df9c00;}
    ul{
        display:flex;
        flex-wrap: wrap;
        flex-direction: column;
        text-align:center;
    }
    li{
        list-style-type:none;
        margin: 0.5em;
    }

    .advice{

        padding: 0.5em 1em;
    }
</style>