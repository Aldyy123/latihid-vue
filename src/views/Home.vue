<template>
  <div class="home">
    <LandingPage />
    <AdvantageLanding/>
    <LandingKemitraan/>
    <b-container class="mt-5" id="kolaborasi">
      <b-row class="align-items-center flex-column text-center">
        <b-col style="width : 50%!important;"><h3>Ayo Kolaborasi</h3></b-col>
        <b-col style="width : 50%!important;">
          <p>Silahkan isi dan lengkapi data berikut ini. LatihID akan segera menghubungi Anda!</p>
        </b-col>
      </b-row>
      <hr>
    </b-container>
    <FormUser/>
  </div>
</template>

<script>
// @ is an alias to /src
import LandingPage from "@/components/LandingPage.vue";
import AdvantageLanding from "@/components/AdvantageLanding.vue";
import LandingKemitraan from "@/components/LandingKemitraan.vue";
import FormUser from "@/components/FormUser.vue";

export default {
  name: "Home",
  components: {
    LandingPage,
    AdvantageLanding,
    LandingKemitraan,
    FormUser
  },
};
</script>

<style lang="scss" scoped>
#kolaborasi{
  p{
    font-size: 18px;
  }
}

@media screen and (max-width: 576px) {
  #kolaborasi{
    h3{
      font-size: 20pt;
    }
    p{
      font-size: 13pt;
    }
  }
}
</style>
