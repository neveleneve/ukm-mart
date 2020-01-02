<template>
  <div id="apps">
    <nav class="navbar navbar-expand-md bg-primary navbar-dark">
      <a class="navbar-brand" href="#">UKM MART</a>
      <button
        class="navbar-toggler"
        type="button"
        data-toggle="collapse"
        data-target="#collapseNavbar"
      >
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="collapseNavbar">
        <ul class="navbar-nav">
          <li class="nav-item">
            <a class="nav-link" href="">Home</a>
          </li>
          <li class="nav-item dropdown">
            <a class="nav-link dropdown-toggle" data-toggle="dropdown" href=""
              >Product</a
            >
            <div class="dropdown-menu">
              <a class="dropdown-item" href="">Elektronik</a>
              <a class="dropdown-item" href="">Kecantikan</a>
              <a class="dropdown-item" href="">Kerajinan Tangan</a>
            </div>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="">About</a>
          </li>
        </ul>
      </div>
    </nav>
    <div class="container-fluid">
      <div class="row">
        <div class="col-md-2 mb-3">
          <div class="card middleThing">
            <div class="card-body">
              <img class="sizeproduct" src="jamtangan.jpg" alt="" />
              <a class="card-link" href=""><h5>Nama Barang</h5></a>
              <h6>Rp 1.000.000</h6>
            </div>
            <div class="card-footer">
              <div class="btn-wrapper text-center d-flex justify-content-between">
                <a class="btn btn-success d-flex align-items-center fa-shopping-cart"></a>
                <a class="btn btn-warning d-flex align-items-center fa-heart"></a>
              </div>
            </div>
          </div>
        </div>        
      </div>
    </div>
  </div>
</template>

<script>
</script>