<template>
  <div>
    <!-- About -->
    <section class="about d-flex align-items-center text-light py-5">
      <div class="container">
        <div class="row d-flex align-items-center">
          <div class="col-lg-5" data-aos="fade-right">
            <!-- <p>Tentang Kami</p> -->
            <h1 class="mt-3">Tentang Kami</h1>
            <p class="py-2 para-light">
              Selama ini BPS mengumpulkan berbagai data dari berbagai sumber
              melalui sensus, survei, dan kompilasi produk administrasi. Big
              data merupakan salah satu sumber data baru yang dapat dimanfaatkan
              dalam mendukung statistik yang dikumpulkan selama ini, sehingga
              data yang disajikan akurat dan lebih cepat sesuai dengan kebutuhan
              pengguna.
            </p>

            <!-- <div class="my-3">
            <a class="btn" href="#your-link">Learn More</a>
          </div> -->
          </div>
          <div class="col-lg-7 text-center py-4 py-sm-0" data-aos="fade-down">
            <!-- <img
              class="img-fluid"
              src="mirko/assets/images/about.jpg"
              alt="about"
            /> -->
            <iframe
              width="560"
              height="315"
              src="https://www.youtube.com/embed/_ONd7uLtXTU"
              title="YouTube video player"
              frameborder="0"
              allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
              allowfullscreen
            ></iframe>
          </div>
        </div>
        <!-- end of row -->
      </div>
      <!-- end of container -->
    </section>
    <!-- end of about -->

    <!-- Services -->
    <section class="services d-flex align-items-center py-5">
      <div class="container text-light">
        <div class="text-center pb-4">
          <p>
            Badan Pusat Statistik menjadikan Big Data sebagai sumber alternatif
            pendukung statistik resmi
          </p>
          <h2 class="py-2">Mengapa Harus Big Data?</h2>
          <!-- <p class="para-light">
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Vitae
          asperiores, quia accusantium sunt corporis optio recusandae? Nostrum
          libero pariatur cumque, ipsa dolores voluptatibus voluptate alias sit
          fuga. Itaque, ea quo.
        </p> -->
        </div>
        <div class="row gy-4 py-2 text-center" data-aos="zoom-in">
          <div class="col-lg-4">
            <div class="card bg-transparent no-border">
              <i class="fas fa-home fa-2x"></i>
              <h4 class="py-2">Sumber data baru hasil Revolusi industri 4.0</h4>
              <p class="para-light">
                Tidak bisa dipungkiri dengan revolusi industri 4.0 mengakibatkan
                perkembangan teknologi dan informasi menjadi semakin cepat.
                Salah satu teknologi yang menjadi pilar dalam perkembangan
                revolusi ini adalah teknologi Big Data.
              </p>
            </div>
          </div>
          <div class="col-lg-4">
            <div class="card bg-transparent no-border">
              <i class="fas fa-wifi fa-2x"></i>
              <h4 class="py-2">Tren pemanfaatan Big Data di NSO</h4>
              <p class="para-light">
                Seiring dengan meningkatnya permintaan konsumen data akan
                penyediaan data yang cepat dan up-to-date, menuntut instansi
                penyedia data (National Statistical Office/NSO) dari berbagai
                negara untuk melakukan inovasi-inovasi agar mampu memenuhi
                tuntutan pengguna data. Oleh karena itu, perlu dilakukan
                upaya-upaya mencari sumber data baru yang lebih cepat selain
                metode pengumpulan data yang selama ini dilakukan yaitu sensus,
                survei, dan kompilasi data administrasi.
              </p>
            </div>
          </div>
          <div class="col-lg-4">
            <div class="card bg-transparent no-border">
              <i class="fas fa-phone fa-2x"></i>
              <h4 class="py-2">Peluang besar dalam pemanfaatan big data</h4>
              <p class="para-light">
                Beberapa peluang dalam pemanfaatan big data yang sudah dilakukan
                oleh beberapa National Statistical Office (NSO) dengan sumber
                yang memenuhi kriteria yang sudah ditetapkan.
              </p>
            </div>
          </div>
        </div>
        <!-- end of row -->
      </div>
      <!-- end of container -->
    </section>
    <!-- end of services -->

    <!-- Plans -->
    <section class="plans d-flex align-items-center py-5">
      <div class="container text-light">
        <div class="text-center pb-4">
          <p>Peluang</p>
          <h2 class="py-2">
            Beberapa peluang dalam pemanfaatan big data yang sudah dilakukan
            oleh beberapa National Statistical Office (NSO)
          </h2>
          <!-- <p class="para-light">
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Vitae
          asperiores, quia accusantium sunt corporis optio recusandae? Nostrum
          libero pariatur cumque, ipsa dolores voluptatibus voluptate alias sit
          fuga. Itaque, ea quo.
        </p> -->
          <div
            class="block d-flex align-items-center"
            v-for="peluang in peluangs"
            :key="peluang"
          >
            <p class="pe-2"><i class="far fa-check-circle fa-1x"></i></p>
            <p style="text-align: left">
              {{ peluang }}
            </p>
          </div>
        </div>

        <!-- end of row -->
      </div>
      <!-- end of container -->
    </section>
    <!-- end of plans -->

    <!-- Work -->
    <section class="work d-flex align-items-center py-5">
      <div class="container">
        <div class="container-fluid text-light">
          <div class="row d-flex align-items-center px-4 py-3">
            <p>Inisiatif BPS dalam mengembangkan big data</p>
            <h2 class="py-2">Apa yang telah kami lakukan?</h2>
          </div>

          <div class="row">
            <div
              class="col-lg-5 d-flex align-items-center px-4 py-3"
              data-aos=""
            >
              <div class="row">
                <div class="text-center text-lg-start py-4 pt-lg-0">
                  <p>
                    BPS telah berinisiatif melakukan kajian pemanfaatan big data
                    untuk mendukung statistik resmi yang telah ada. Beberapa
                    publikasi yang telah memanfaatkan big data diantaranya
                    adalah:
                  </p>

                  <div class="block d-flex align-items-center mt-2">
                    <p class="pe-2">
                      <i class="far fa-check-circle fa-1x"></i>
                    </p>
                    <p>
                      Perhitungan Jumlah Wisatawan Mancanegara dengan Mobile
                      Positioning Data (MPD)
                    </p>
                  </div>

                  <div class="block d-flex align-items-center my-1">
                    <p class="pe-2">
                      <i class="far fa-check-circle fa-1x"></i>
                    </p>
                    <p>Tinjauan Big Data terhadap Dampak COVID-19 Tahun 2020</p>
                  </div>

                  <div class="block d-flex align-items-center">
                    <p class="pe-2">
                      <i class="far fa-check-circle fa-1x"></i>
                    </p>
                    <p>
                      Analisis Big Data Ditengah Masa Adaptasi Kebiasaan Baru
                    </p>
                  </div>

                  <br />
                </div>

                <!-- end of container -->
              </div>
              <!-- end of row -->
            </div>

            <div
              class="col-lg-7 d-flex align-items-center"
              data-aos="fade-right"
            >
              <iframe
                width="560"
                height="315"
                src="https://www.youtube.com/embed/3bNSiBeQnCU"
                title="YouTube video player"
                frameborder="0"
                allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
                allowfullscreen
              ></iframe>
              <!-- <img
              class="img-fluid"
              src="mirko/assets/images/work.jpg"
              alt="work"
            /> -->
            </div>
          </div>

          <div class="row">
            <p>
              Selain itu, beberapa kajian big data dalam bidang ekonomi adalah
              menghitung statistik harga/inflasi, pengembangan ragam data atau
              indikator kerangka sampel area (KSA) untuk produksi padi,
              statistik ekonomi kreatif, neraca satelit pariwisata, penyusunan
              disagregasi Pembentukan Modal Tetap Bruto (PMTB), dan penghitungan
              Interregional Input-Output (IRIO). Sedangkan untuk kajian big data
              dalam bidang statistik sosial antara lain dalam menghitung
              statistik tenaga kerja, indeks mobilitas penduduk, indeks kualitas
              udara dan data penerbangan.
            </p>
          </div>
          <!-- end of row -->
        </div>
      </div>

      <!-- end of container -->
    </section>
    <!-- end of work -->

    <!-- Location -->
    <section class="location text-light py-5">
      <div class="container" data-aos="zoom-in">
        <div class="row">
          <div
            class="col-lg-3 d-flex align-items-center"
            style="cursor:pointer"
            onclick="window.open('https://twitter.com/bps_statistics')"
          >
            <div class="p-2"><i class="fab fa-twitter fa-3x"></i></div>
            <div class="ms-2">
              <h6>Twitter</h6>
              <p>@bps_statistics</p>
            </div>
          </div>
          <div
            class="col-lg-3 d-flex align-items-center"
            style="cursor:pointer"
            onclick="window.open('https://web.facebook.com/bpsstatistics')"
          >
            <div class="p-2"><i class="fab fa-facebook fa-3x"></i></div>
            <div class="ms-2">
              <h6>Facebook</h6>
              <p>@bpsstatistics</p>
            </div>
          </div>
          <div
            class="col-lg-3 d-flex align-items-center"
            style="cursor:pointer"
            onclick="window.open('https://www.instagram.com/bps_statistics')"
          >
            <div class="p-2"><i class="fab fa-instagram fa-3x"></i></div>
            <div class="ms-2">
              <h6>Instagram</h6>
              <p>@bpsstatistics</p>
            </div>
          </div>
          <div
            class="col-lg-3 d-flex align-items-center"
            style="cursor:pointer"
            onclick="window.open('https://www.youtube.com/channel/UCQZFQxmG7KQwpaMEw01t7ZA/featured')"
          >
            <div class="p-2"><i class="fab fa-youtube fa-3x"></i></div>
            <div class="ms-2">
              <h6>Youtube</h6>
              <p>pengembangan model statistik</p>
            </div>
          </div>
        </div>
        <!-- end of row -->
      </div>
      <!-- end of container -->
    </section>
    <!-- end of location -->
  </div>
</template>

<script>
export default {
  data: () => ({
    peluangs: [
      "Kerangka sampel atau pembuatan register, mengidentifikasi unit populasi survei dan / atau memberikan informasi tambahan seperti variabel stratifikasi.",
      "Pengganti data lengkap, menggantikan survei.",
      "Pengganti data parsial untuk subkelompok populasi, mengurangi ukuran sampel.",
      "Pengganti data parsial untuk beberapa item data yang diperlukan, mengurangi panjang kuesioner survei, atau memperkaya dataset.",
      "Imputasi untuk data yang hilang, mengganti unit yang sama atau serupa.",
      "Mengedit, membantu deteksi, dan penanganan anomali dalam data survei.",
      "Menghubungkan ke data lain, membuat kumpulan data yang lebih kaya dan / atau perspektif longitudinal/series.",
      "Konfrontasi data, memastikan validitas dan konsistensi data survei.",
      "Menghasilkan wawasan analitis baru, meningkatkan pengukuran dan penggambaran fenomena ekonomi, sosial, dan lingkungan.",
    ],
  }),
};
</script>
