<template>
  <div class="advantage-landing">
    <b-container fluid>
      <b-row style="margin-top: 120px;">
        <b-col class="text-center">
          <h2>Keuntungan Menjadi Mitra Kami</h2>
        </b-col>
      </b-row>
      <b-row class="advantage-lg mt-5">
        <b-col class="mt-13" md="10" offset-md="1" offset-lg="1" lg="2">
          <div class="bulat">
            <img src="../assets/business.svg" alt="bisnis" />
          </div>
          <div class="text">
            <b style="font-size: 18px;">Jejaring Bisnis</b>
            <p style="font-size: 16px;">
              Kesempatan untuk menjangkau
              <b style="color: #FC8047">865</b> pengguna kami
            </p>
          </div>
        </b-col>
        <b-col lg="2" offset-lg="1" class="mt-6">
          <div class="bulat">
            <img src="../assets/carbon_money.svg" alt="insentif" />
          </div>
          <div class="text">
            <b style="font-size: 18px;">Insentif</b>
            <p
              style="font-size: 16px;"
            >Lorem ipsum dolor sit amet, consectetur adipisicing elit. Ratione eius explicabo dignissimos minima</p>
          </div>
        </b-col>
        <b-col lg="2" offset-lg="1" class="mt-13">
          <div class="bulat">
            <img src="../assets/house.svg" alt="pengalaman" />
          </div>
          <div class="text">
            <b style="font-size: 18px;">Pengalaman</b>
            <p
              style="font-size: 16px;"
            >Berbagi cerita, motivasi, dan pengalaman menarik dengan menjadi pembicara pada LatihID Talks maupun PETA</p>
          </div>
        </b-col>
        <b-col lg="2" offset-lg="1" class="mt-6">
          <div class="bulat">
            <img src="../assets/certificate.svg" alt="certificate" />
          </div>
          <div class="text">
            <b style="font-size: 18px;">Sertifikat</b>
            <p style="font-size: 16px;">Dokumentasi sebagai pembicara dalam acara LatihID</p>
          </div>
        </b-col>
      </b-row>
    </b-container>



    <b-container class="advantage-md mt-5 d-flex flex-column justify-content-around">
      <b-row class="flex-column">
        <b-col md="6" sm="9" offset-sm="2" cols="7" offset="3" class="xs-mitra d-flex flex-row-reverse">
          <div class="bulat">
            <img src="../assets/business.svg" alt="bisnis" />
          </div>
          <div class="text mr-1">
            <b style="font-size: 18px;">Jejaring Bisnis</b>
            <p style="font-size: 16px;">
              Kesempatan untuk menjangkau
              <b style="color: #FC8047">865</b> pengguna kami
            </p>
          </div>
        </b-col>
      </b-row>
      <b-row class="flex-column">
        <b-col md="7" offset-md="5" sm="9" offset-sm="2" cols="7" offset="3" class="xs-mitra d-flex justify-content-around">
          <div class="bulat">
            <img src="../assets/carbon_money.svg" alt="insentif" />
          </div>
          <div class="text ml-3">
            <b style="font-size: 18px;">Insentif</b>
            <p
              style="font-size: 16px;"
            >Lorem ipsum dolor sit amet, consectetur adipisicing elit. Ratione eius explicabo dignissimos minima</p>
          </div>
        </b-col>
      </b-row>
      <b-row class="flex-column">
        <b-col md="6" class="d-flex flex-row-reverse xs-mitra" cols="7" offset="3" sm="9" offset-sm="2">
         <div class="bulat">
            <img src="../assets/house.svg" alt="pengalaman" />
          </div>
          <div class="text">
            <b style="font-size: 18px;">Pengalaman</b>
            <p
              style="font-size: 16px;"
            >Berbagi cerita, motivasi, dan pengalaman menarik dengan menjadi pembicara pada LatihID Talks maupun PETA</p>
          </div>
        </b-col>
      </b-row>
      <b-row class="flex-column">
        <b-col md="6" offset-md="5" class="d-flex justify-content-between xs-mitra" cols="7" offset="3" sm="9" offset-sm="2">
          <div class="bulat">
            <img src="../assets/certificate.svg" alt="certificate" />
          </div>
          <div class="text ml-3">
            <b style="font-size: 18px;">Sertifikat</b>
            <p style="font-size: 16px;">Dokumentasi sebagai pembicara dalam acara LatihID</p>
          </div>
        </b-col>
      </b-row>
    </b-container>
  </div>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
.advantage-lg {
  background: url(../assets/vector12.svg) top no-repeat;
  height: 500px;
  h3 {
    text-align: center;
    font-size: 30px;
  }
  .alur {
    display: flex;
    justify-content: space-evenly;

    .jejaring-bisnis {
      display: flex;
      flex-direction: column;
      padding: 20px;
      width: 20%;

      h5 {
        font-weight: bold;
      }
    }
  }
}

.bulat {
  padding: 20px;
  height: 100px;
  width: 100px;
  border-radius: 50%;
  box-shadow: 0px 5px 25px rgba(15, 132, 159, 0.2);
  display: flex;
  justify-content: center;
  z-index: 999;
}

.mt-13 {
  margin-top: 13em;
}
.mt-6 {
  margin-top: 6em;
}

// Large
@media screen and (min-width: 992px) {
  .advantage-md{
    display: none!important;
  }
}

// Medium
@media screen and (max-width: 992px) {
  h2 {
    font-size: 19pt;
  }
  .advantage-lg {
    display: none;
  }
  .advantage-md {
    background: url(../assets/vector14.svg) center no-repeat;
    margin-top: 15px;
    height: 900px;
  }
}

// Small
@media screen and (max-width: 768px) {
  .advantage-md{
    background: none;
  }
  h2 {
    font-size: 17pt;
  }
}

// XS
@media screen and (max-width: 576px) {
  .advantage-md {
    display: none;
  }
  .xs-mitra{
    flex-direction: column!important;
    align-items: center;
    justify-content: center;
  }
}
</style>