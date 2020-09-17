<template>
  <b-container fluid="md" class="kebawah bv-example-row">
    <b-row>
      <b-col class="text-center">
        <h2>Jenis - Jenis Kemitraan</h2>
      </b-col>
    </b-row>
    <b-row>
      <b-col sm="6" class="mt-5 mitra" md="6" lg="3">
        <div class="kotak">
          <div class="title">
            <img class="d-flex" src="../assets/vector-1.svg" alt="Pemateri Modul" />
            <h4 class="text-center font-weight-bold mt-3">Pemateri Modul</h4>
          </div>
          <div
            class="text-center"
            style="font-size: 16px;"
          >Individu/Lembaga bermitra sebagai instruktur atau pemateri di latihID Modul, dengan menyediakan beberapa courses di dalam satu modul pembelajaran.</div>
        </div>
      </b-col>
      <b-col sm="6" class="mt-5 mitra" md="6" lg="3">
        <div class="kotak">
          <div class="title">
            <img class="d-flex" src="../assets/vector-2.svg" alt="Pembicara Talks" />
            <h4 class="text-center font-weight-bold mt-3">Pembicara Talks</h4>
          </div>
          <div
            class="text-center"
            style="font-size: 16px;"
          >Individu/Lembaga bermitra sebagai instruktur atau pemateri di latihID Talks, yang membahas topik seputar UMKM melalui webinar live atau tatap muka yang interaktif.</div>
        </div>
      </b-col>
      <b-col sm="6" class="mt-5 mitra" md="6" lg="3">
        <div class="kotak">
          <div class="title">
            <img class="d-flex" src="../assets/vector-3.svg" alt="Pembicara PETA" />
            <h4 class="text-center font-weight-bold mt-3">Pembicara PETA</h4>
          </div>
          <div
            class="text-center"
            style="font-size: 16px;"
          >Individu/Lembaga bermitra sebagai instruktur atau pemateri di latihID PETA, yang menceritakan pengalaman tentang UMKM dalam video singkat.</div>
        </div>
      </b-col>
       <b-col sm="6" class="mt-5 mitra" md="6" lg="3">
        <div class="kotak">
          <div class="title">
            <img class="d-flex" src="../assets/vector-4.svg" alt="Mitra Lainnya" />
            <h4 class="text-center font-weight-bold mt-3">Mitra Lainnya</h4>
          </div>
          <div
            class="text-center"
            style="font-size: 16px;"
          >Individu/Lembaga dapat mengajukan berbagai jenis kemitraan lainnya, seperti Media partner</div>
        </div>
      </b-col>
    </b-row>
  </b-container>
</template>


<style lang="scss" scoped>
.kebawah{
  margin-top: 15em!important;
}
.kotak {
  padding: 20px 15px;
  background: #ffffff;
  border: 1px solid #e0e0e0;
  box-sizing: border-box;
  border-radius: 8px;

  .title {
    img {
      margin: 0 auto;
    }
    h4 {
      font-size: 18px;
    }
  }
}

// MD
@media screen and (max-width: 960px) {
  h2{
    font-size: 22pt;
  }
}

// SM
@media screen and (max-width: 768px) {
  h2{
    font-size: 20pt;
  }
}

// XS
@media screen and (max-width: 576px) {
  .mitra{
    padding: 0 50px;
  }
  h2{
    font-size: 17pt;
  }
}
</style>