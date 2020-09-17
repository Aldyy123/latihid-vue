<template>
  <b-container>
    <b-form-row>
      <b-col md="6" sm="12">
        <div>
          <label>
            Kerja Sama yang Diinginkan
            <span class="text-danger">*</span>
          </label>
          <b-form-select></b-form-select>
        </div>
        <div class="mt-2">
          <label for="nama">
            Nama
            <span class="text-danger">*</span>
          </label>
          <b-input></b-input>
        </div>
        <div class="mt-2">
          <label for="email">
            Email
            <span class="text-danger">*</span>
          </label>
          <b-input></b-input>
        </div>
        <div class="mt-2">
          <label for="phone">
            Nomor Telepon
            <span class="text-danger">*</span>
          </label>
          <b-input></b-input>
        </div>
      </b-col>

      <b-col sm="12" md="6">
        <div>
          <label for="cv">
            Upload CV
            <span class="text-danger">*</span>
          </label>
          <b-form-file plain></b-form-file>
        </div>
        <div class="mt-2">
          <label for="portfolio">
            Upload Portofolio atau Proposal Kerjasama
            <span class="text-danger">*</span>
          </label>
          <b-form-file plain></b-form-file>
        </div>
        <div class="mt-2">
          <label for="topik">
            Topik Yang Diajukan
            <span class="text-danger">*</span>
          </label>
          <b-form-textarea max-rows="5" rows="3" size="lg"></b-form-textarea>
        </div>
      </b-col>
    </b-form-row>

    <b-row class="align-items-center flex-column text-center mt-5">
      <b-col style="width : 50%!important;">
        <a href="" class="btn">Kirim</a>
      </b-col>
    </b-row>
  </b-container>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
.btn{
    background: #FC8047;
    padding: 7px 40px;
    border-radius: 40px;
}
</style>