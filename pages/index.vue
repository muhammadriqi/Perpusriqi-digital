<template>
  <div class="container-fluid">
    <div class="row my-5">
      <div class="col-lg-6">
        <nuxt-link to="/pengunjung/tambah">
          <div class="card bg-pengunjung rounded-5">
            <div class="card-body">
              <h2>Pengunjung</h2>
            </div>
          </div>
        </nuxt-link>
      </div>

      <div class="col-lg-6">
        <nuxt-link to="/buku">
          <div class="card bg-buku rounded-5">
            <div class="card-body">
              <h2>Cari Buku</h2>
            </div>
          </div>
        </nuxt-link>
      </div>
    </div>
  </div>.
  <h2 class="justify-content-between">STATISIK</h2>
  <div class="container-fluid">
    <div class="row justify-content-evenly rounded-5">
      <div class="col-5">
        <div class="cover">
          <h2> 1 Pengunjung </h2>
        </div>
      </div>
      <div class="col-5">
        <div class="cover1">
          <h2>3 Buku</h2>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped>
.card {
  height: 174px;
  box-shadow: 1px 1px 10px #424242;
}

.card.bg-pengunjung {
  background-image: url('../assets/img/pengunjung.jpeg');
  background-repeat: no-repeat;
  background-position: center center;
  background-size: cover;
}

.card.bg-buku {
  background: url('../assets/img/bg-home-cari-buku.jpg') no-repeat center center;
  background-size: cover;
}

.cover {
  height: 174px;
  box-shadow: 1px 1px 10px;
  border-radius: 20px;
  display: flex;
  justify-content: center;
  align-items: center;
  background-color: #BDFF00;
}

.cover1 {
  height: 174px;
  box-shadow: 1px 1px 10px;
  border-radius: 20px;
  display: flex;
  justify-content: center;
  align-items: center;
  background-color: #00FFA3;
}
</style>