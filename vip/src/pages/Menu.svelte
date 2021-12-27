<div class="main">
    <div class="menu">
        <div class="menu-header">
            <span class="material-icons-outlined md-48">
                account_circle
              </span>
            <h3>User Name</h3>
        </div>
        <div class="menu-nav">
            <ul>
                <li class="nav-item">
                    <span class="material-icons-outlined">payments  </span>
                    Metodos de pago
                </li>
                <hr/>

                <li class="nav-item">
                    <span class="material-icons-outlined">history  </span>
                    Mis Servicios
                </li>
                <hr/>

                <li class="nav-item">
                    <span class="material-icons-outlined">history  </span>
                    Despachos
                </li>
                <hr/>

                <li class="nav-item">
                    <span class="material-icons-outlined">account_balance_wallet  </span>
                    Billetera VIP
                </li>
                <hr/>

                <li class="nav-item">
                    <span class="material-icons-outlined">account_balance_wallet  </span>
                    Gana con VIP
                </li>
                <hr/>

                <li class="nav-item">
                    <span class="material-icons-outlined">contact_support  </span>
                    Ayuda
                </li>
                <hr/>
                
                <li class="nav-item">
                    <span class="material-icons-outlined">
                        help_outline
                        </span>
                    ¿Como pedir un taxi?
                </li>
                <hr>
                <li class="nav-item">
                    <span class="material-icons-outlined">share  </span>
                    Compartir VIP
                </li>
                <hr/>

                <li class="nav-item">
                    <span class="material-icons-outlined">
                        logout
                    </span>
                    Cerrar Sesion
                </li>
            </ul>
        </div>
    </div>
</div>
<style>
    .main{
        height:100%;
        width:80%;
        background-color: var(--light);
        border-radius: 10px 0 0 10px;
    }
    .menu-header{
        display: flex;
        flex-direction: column;
        text-align: center;
        background: var(--yellow);
        padding: 1.4em;
        border-radius: 10px 0 0 0;
    }
    h3{
        margin: 0.5em;
    }
    .menu-nav{
        display:flex;
        align-items: center;
        justify-content: center;
        margin: 0 auto;
    }
    ul{
        display: flex;
        justify-content: center;
        text-align:center;
        flex-direction:column;
    }
    li{
        display:flex;
        align-items: center;
        justify-content: center;
        padding:0.379em 0;
        margin: auto 0;
    }
    li > span {
        margin: 5px;
    }
    .md-48{
        font-size: 52px;
    }
</style>