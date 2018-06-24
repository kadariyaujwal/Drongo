<template>
  <div>
    <section id="pre_header">
      <div class="container">
        <div class="row">
          <div class="col-md-4">
            <a href="#"><img src="../assets/img/logo.png" alt="logo" class="img-fluid"></a>
          </div>
          <div class="col-md-8 text-right">
            <ul class="list-inline">
              <li class="list-inline-item"><button class="btn btn-primary pull-right add_space" data-toggle="modal" data-target=".bd-example-modal-lg">+</button></li>
              <li class="list-inline-item"><a href="#">Help</a></li>
              <li class="list-inline-item"><a href="#">Notifications</a></li>
              <li class="list-inline-item"><a href="#">R</a></li>
            </ul>
          </div>
        </div>
      </div>
    </section>

    <!-- header -->

    <header>
      <nav class="navbar navbar-expand-md">
        <div class="container">
          <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarTogglerDemo01" aria-controls=" navbarTogglerDemo01" aria-expanded="false" aria-label="Toggle navigation">
                           <span class="navbar-toggler-icon"><i class="fa fa-bars"></i></span>
                      </button>
          <a class="navbar-brand d-block d-md-none" href="#"><img src="../assets/img/logo.png" alt="..." class="img-fluid"></a>
          <div class="collapse navbar-collapse" id="navbarTogglerDemo01">
            <ul class="navbar-nav mr-auto">
              <li class="nav-item d-none d-md-block">
                <a class="nav-link" href="#"><img src="../assets/img/bars.png" alt="bars"></a>
              </li>
              <li class="nav-item active">
                <a class="nav-link" href="#">Space Names</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="#">Services</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="#">Dashboard</a>
              </li>
              <li class="nav-item">
                <a class="nav-link sign_up" href="#">Settings</a>
              </li>
            </ul>
            <ul class="navbar-nav d-block d-md-none">
              <li class="nav-item"><a href="#" class="nav-link">Help</a></li>
              <li class="nav-item"><a href="#" class="nav-link">Notifications</a></li>
              <li class="nav-item"><a href="#" class="nav-link big_r">R</a></li>
            </ul>
            <ul class="navbar-nav ml-auto">
              <li class="nav-item">
                <div class="input-group mt-2">
                  <input type="text" class="form-control">
                  <div class="input-group-append">
                    <button class="btn btn-outline-secondary" type="button">Search</button>
                  </div>
                </div>
              </li>
            </ul>
          </div>
        </div>
      </nav>
    </header>
  </div>
</template>
