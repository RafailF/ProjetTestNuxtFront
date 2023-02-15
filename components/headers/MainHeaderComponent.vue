<template>
    <nav class="navbar navbar-expand-lg">
        <div class="container-fluid ">


            <div class="d-flex d-lg-none"><button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav"
                aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button></div>
            <div class="d-flex">
                <router-link to="/">
                    <img class="navbar-brand" src="../../static/images/logo-dark.png" />
                </router-link>
                </div>


            
            
            <div class="d-flex "><div class="collapse navbar-collapse " id="navbarNav">
                <ul class="navbar-nav">
                    <li class="nav-item me-3">
                        <a class="nav-link fw-semibold "  href="#">Livre blanc</a>
                    </li>
                    <li class="nav-item me-3">
                        <a class="nav-link fw-semibold " href="#">Offres Pro</a>
                    </li>
                    <li class="nav-item me-3">
                        <a class="nav-link fw-semibold " href="#">F.A.Q.</a>
                    </li>
                    <li class="nav-item me-3">
                        <a class="nav-link fw-semibold " href="#">Blog</a>
                    </li>
                    <li class="nav-item me-2 ">
                        <router-link to="login" class="nav-link btn btn-outline-dark  fw-semibold ">Connexion</router-link>
                    </li>
                    <li class="nav-item btn">
                        <img class="" src="../../static/images/fr.png" />
                    </li>
                </ul>
            </div>
        </div>

        
            
        </div>
    </nav>
</template>

<style>

*{
    font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
    color:#2b4d46;
    font-size:14px
}



li a:hover{
    color:#68dbc9
}

.btn-outline-dark {
    border-color: #343a40;
    color: #343a40;
}

.btn-outline-dark:hover {
    
    color: white
}

.btn{
    border-radius: 1.6em;
}
</style>

