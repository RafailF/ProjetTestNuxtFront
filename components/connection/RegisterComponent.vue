<template>
    <div class="bg-light pb-5">
        <div class="container">
            <div class="row justify-content-center">
                <div class="col-6 mt-5 ">
                    <div class="row bg-soft-primary  auth-block">
                        <div class="col">
                            <div class="p-3">
                                <h3 class="title-font ">Créer votre compte</h3>
                            </div>
                        </div>
                        <div class="col align-self-end"> <img style="width: 200px;"
                                src="../../static/images/profile-img.png" />
                        </div>
                    </div>
                    <div class="row bg-white pb-5">
                        <form method="post" class="p-4">
                            <div class="">

                                <div class="text-center mt-5 mb-5"> <h5> Vous avez déjà un compte ? <router-link class="link" style="font-size:16px" to="login"> Connectez-vous</router-link></h5></div>

                                <div class="row">
                                    <div class="col"> <label class="fw-bold pb-1">Nom*</label>
                                        <div>
                                            <input type="text" class="form-control" />
                                        </div>
                                    </div>

                                    <div class="col"> <label  class="fw-bold pb-1">Prenom*</label>
                                        <div>
                                            <input type="text" class="form-control" />
                                        </div>
                                    </div>
                                </div>





                                <div class="form-group mt-3 row ">
                                    <label class="fw-bold pb-1">Email*</label>
                                    <div>
                                        <input type="email" class="form-control" />
                                    </div>
                                </div>

                                <div class="form-group mt-3 row">
                                    <label class=" fw-bold pb-1">Mot de passe*</label>
                                    <div>
                                        <input type="password" class="form-control" />
                                    </div>
                                </div>

                                <div class="d-flex justify-content-center mt-4">
                                    <button class="btn btn-primary">Créer mon compte</button>
                                </div>
                            </div>
                        </form>
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
