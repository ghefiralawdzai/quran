<script>
import NavBar from "../components/NavBar.vue";
import Footer from "../components/Footer.vue";
export default {
  name: "AboutView",
  components: { NavBar, Footer },
};
</script>

<template>
  <NavBar />
  <!-- About-->
  <br />
  <br />
  <br />
  <br />
  <br />
  <section id="about">
    <div class="container">
      <div class="row text-center mt-5">
        <div class="col">
          <h2 class="display-7">About Me</h2>
        </div>
      </div>
    </div>
  </section>
  <br />
  <br />
  <br />
  <br />
  <br />
  <br />
  <br />
  <!-- Akhir About-->

  <!-- Table -->
  <section class="container my-5">
    <div class="row justify-content-center">
      <div class="col-8">
        <div class="card rounded shadow">
          <div class="card-header">Data Diri</div>
          <div class="card-body text-start">
            <table class="table">
              <tbody>
                <tr>
                  <td>Nama</td>
                  <td>:</td>
                  <td>Ghefira Lawdza'i Utsula Farey</td>
                </tr>
                <tr>
                  <td>Universitas</td>
                  <td>:</td>
                  <td>UIN Sultan Syarif Kasim Riau</td>
                </tr>
                <tr>
                  <td>Prodi</td>
                  <td>:</td>
                  <td>Teknik Informatika</td>
                </tr>
              </tbody>
            </table>
          </div>
        </div>
      </div>
    </div>
  </section>
  <!-- Akhir Table -->

  <Footer />
</template>

<style scoped></style>
