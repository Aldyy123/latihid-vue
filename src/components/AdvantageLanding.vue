<template>
  <b-container fluid>
      <b-row style="margin-top: 120px;">
          <b-col class="text-center"><h2>Keuntungan Menjadi Mitra Kami</h2></b-col>
      </b-row>
      <b-row class="advantage-lg advantage-md mt-5">
        <b-col class="mt-oem" offset="1" cols="2">
          <div class="bulat">
            <img src="../assets/business.svg" alt="bisnis">
          </div>
          <div class="text">
            <b style="font-size: 18px;">Jejaring Bisnis</b>
            <p style="font-size: 16px;">Kesempatan untuk menjangkau 865 pengguna kami</p>
          </div>
        </b-col>
        <b-col cols="2" offset="1" class="mt-5 bg-aqua">
          <div class="bulat">
            <img src="../assets/carbon_money.svg" alt="insentif">
          </div>
          <div class="text">
            <b style="font-size: 18px;">Insentif</b>
            <p style="font-size: 16px;">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Ratione eius explicabo dignissimos minima</p>
          </div>
        </b-col>
        <b-col cols="2" offset="1" class="mt-oem">
          <div class="bulat">
            <img src="../assets/house.svg" alt="pengalaman">
          </div>
          <div class="text">
            <b style="font-size: 18px;">Pengalaman</b>
            <p style="font-size: 16px;">Berbagi cerita, motivasi, dan pengalaman menarik dengan menjadi pembicara pada LatihID Talks maupun PETA</p>
          </div>
        </b-col>
        <b-col cols="2" offset="1" class="mt-5">
          <div class="bulat">
            <img src="../assets/certificate.svg" alt="certificate">
          </div>
          <div class="text">
            <b style="font-size: 18px;">Sertifikat</b>
            <p style="font-size: 16px;">Dokumentasi sebagai pembicara dalam acara LatihID</p>
          </div>
        </b-col>
      </b-row>
  </b-container>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
.advantage-lg {
  background: url(../assets/vector12.svg) 90% 100%;
  height: 250px;
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
    
      h5{
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

.mt-oem{
  margin-top: 10em;
}

// Medium
@media screen and (max-width: 992px) {
  h2{
    font-size: 19pt;
  }
}

// Small
@media screen and (max-width: 768px) {
  .advantage-md{
    display: none;
  } 
  h2{
    font-size: 17pt;
  }
}

</style>