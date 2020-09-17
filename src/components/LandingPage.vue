<template>
  <!-- <div id="landing-page">
    <div class="url">
      <a href>Home</a> >
      <a href class="next">Kolaborasi</a>
    </div>
    <div class="landing-content">
      <div class="text-landing">
        <h1>Ayo Kolaborasi</h1>
        <p>
          Mari beri kontribusiMari beri kontribusi terbaik
          dalam meningkatkan kualitas sumber daya manusia Indonesia
          dalam mengembangkan UMKM dengan menjadi
          <a
            href
          >Mitra LatihID</a>
        </p>
      </div>
      <div class="img-landing">
        <img src="../assets/teams.svg" alt="Teams" />
      </div>
    </div>
  </div>-->
  <div id="landing-page">
    <b-container fluid class="bv-example-row">
      <b-row class="d-flex">
        <b-col>
          <div class="url">
            <p>
              <router-link to="/" class="text-dark">Home</router-link>>
              <router-link to="/" class="active">Kolaborasi</router-link>
            </p>
          </div>
        </b-col>
      </b-row>

      <b-row>
        <b-col lg="6" md="6" sm="12" class="text-landing">
          <h1 class="font-weight-bold">Ayo Kolaborasi</h1>
          <p>
            Mari beri kontribusi terbaik dalam meningkatkan kualitas sumber daya manusia Indonesia dalam mengembangkan UMKM dengan menjadi
            <a
              href
            >Mitra LatihID</a>
          </p>
        </b-col>
        <b-col lg="6" sm="12" md="6">
          <img src="../assets/teams.svg" class="img-landing" alt="Teams" />
        </b-col>
      </b-row>
    </b-container>
  </div>
</template>

<script>
export default {};
</script>

<style scoped lang="scss">
#landing-page {
  background-image: url(../assets/vector22.svg), url(../assets/vector23.svg);
  background-position: center, right bottom;
  background-size: cover, 100%;
  padding: 0 50px;
  .url {
    margin-top: 50px;
    a {
      text-decoration: none;
    }
    .active {
      color: orange !important;
    }
  }
}

// MD
@media screen and (min-width: 768px) {
  .text-landing {
    h1 {
      font-size: 35px;
    }
    p {
      font-size: 17pt;
    }
  }
  .img-landing {
    width: 100%;
    // display: none;
  }
  .url {
    font-size: 15px;
  }
}

// XS
@media screen and (max-width: 576px) {
  .landing-content {
    flex-direction: column-reverse !important;
  }
  .img-landing {
    width: 100%;
  }
  .url p {
    font-size: 10pt;
  }
  .text-landing {
    p {
      font-size: 12pt;
    }
  }
}

// SM
@media screen and (max-width: 768px) {
  #landing-page{
    background-size: cover;
    background-position: center, center top;
  }
  .img-landing {
    width: 100%;
  }
  .url p {
    font-size: 10pt;
  }
  .text-landing {
    p {
      font-size: 12pt;
    }
  }
}
</style>