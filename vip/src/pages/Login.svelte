<div class="login">
    <div class="login-header">
        <img src="anywhere2.png" alt="logo" class="logo">
    </div>
    <div class="form-container">
        <form action="">
            <input type="text" name="" id="" placeholder="Ingresa tu correo electronico">
            <input type="text" name="" id="" placeholder="Ingresa tu contraseña">
            <button type="submit">Iniciar Sesion</button>
        </form>
    </div>
    <footer class="extra-link">
        <p>No tienes una cuenta <a href="">Crear cuenta</a></p>
        <a href="">Olvide mi contraseña</a>
    </footer>

</div>
<style>
    a{
        color: var(--dark);
        text-decoration: underline 1.2px;
    }
    .login-header{
        height: 30%;
        padding:1em;
        border-radius: 10px 10px 0px 0px;
        background-color: black;
        display:flex;
        align-items: center;
        justify-content: center;
    }

    .logo{
        width: 150px;
    }
    .form-container{
        text-align: center;
        padding:1.5em 1em;
        /* flex-wrap: wrap; */
    }
    
    .form-container > form {
        width:90%;
        display:inline-block;
        /* align-items: center; */
        /* justify-content: center; */
    }
    .form-container > form > *{
        /* display: block; */
        width:100%;
        height:2.5em; 
        padding: 0.3em;
        margin: 0.59876em 0;
        border: none;
        border-bottom: solid 2px var(--grey);
        border-radius: 0px;
        transition:ease-in all 160ms;
    }
    .form-container > form > *:focus{
        border-bottom-color: #df9c00;
        outline: none;
    }
    .form-container> form >button{
        background-color: var(--yellow);
        color:var(--dark);
        border-radius:20px;
        border: none;
    }
    
    .form-container > form > button:focus{
        background: #df9c00;
        border: none;
        outline: none;
    }
    .extra-link{
        display: flex;
        flex-direction:column;
        justify-content: space-between;
        align-items: center;
    }
</style>