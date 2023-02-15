<template>
    <div class="bg-light pb-5">
        <div class="container">
            <div class="row justify-content-center">
                <div class="col-6 mt-5 ">
                    <div class="row bg-soft-primary  auth-block">
                        <div class="col">
                            <div class="p-3">
                                <h3 class="title-font">Connectez-vous</h3>
                            </div>
                        </div>
                        <div class="col align-self-end"> <img style="width: 200px;"
                                src="../../static/images/profile-img.png" />
                        </div>
                    </div>
                    <div class="row bg-white pb-5">
                        <form method="post" class="p-4">
                            <div class="">
                                <div class="form-group mt-3">
                                    <label class=" fw-bold pb-1">Email</label>
                                    <div>
                                        <input class="form-control" />
                                    </div>
                                </div>

                                <div class="form-group mt-3">
                                    <label class=" fw-bold pb-1">Mot de passe</label>
                                    <div>
                                        <input class="form-control" />
                                    </div>
                                </div>

                                <div class="d-grid mt-4">
                                    <button class="btn btn-primary">Connxion</button>
                                </div>
                            </div>
                        </form>
                    </div>

                    <div class="row">
                        <div class="mt-5 text-center fw-semibold">
                            <p>
                                Vous n'avez pas de compte ?
                                <router-link to="/register" class="fw-semibold link">
                                    S'inscrire
                                </router-link>
                            </p>
                            <div class="col-12 col-sm-12 col-xl-12 pb-4">
                                <p class="mb-2">
                                    On reste en contact ?
                                </p>
                                <p class="text-uppercase mb-2">
                                    Suivez-nous !
                                </p>
                            </div>
                        </div>
                    </div>


                </div>
            </div>
        </div>
    </div>

</template>

<style scoped>
.bg-soft-primary {
    background: #d9f6f1;
}

.auth-block {
    border-radius: 20px 20px 0 0;
}

.btn-primary {
    background: #68dbc9;
    color: white;
    border: none
}

.link {
    color: #68dbc9;
    text-decoration: none;
}

.link:hover {
    color: #4fa397;
}


</style>

<style>
.title-font{
    font-family:'Segoe UI', Tahoma, Geneva, Verdana, sans-serif
}
</style>