<template>
  <div id="app">
    <Header />
    <div class="container mx-auto">
      <div class="h-[calc(12vh)]"></div>
      <div class="text-center">
        <TitleSection
          link="/pelajari"
          linkText="PELAJARI"
          heading="Perjalanan "
          subheading1="Singkat OGI"
          :headingPrimary="true"
          :subheading1Primary="false"
        />
        <p class="text-black font-inter" :style="{ fontSize: '20px' }">
          Kolaborasi antara Pemerintah Indonesia dan Organisasi Masyarakat Sipil
          (OMS) untuk melahirkan <br />
          ide dan aksi dalam mendorong implementasi nilai
          <span class="text-primary-3"
            >transparansi, partisipasi, inovasi, akuntabilitas dan <br />
            inklusif</span
          >
          guna menciptakan tata kelola pemerintahan yang bersih, efektif,
          demokratis, dan <br />
          terpercaya.
        </p>
      </div>
      <div class="mt-4 space-y-11">
        <CustomDetails title="2023">
          <div class="details-text">
            <h2 class="text-lg font-semibold font-inter">
              1. Peluncuran RAN OGI VII 2023-2024
            </h2>
            <h2 class="text-lg font-semibold mt-4 font-inter">
              2. OGP Summit 2023 di Tallinn, Estonia
            </h2>
            <p class="ml-5 font-inter font-normal">
              Indonesia mengirimkan delegasi untuk menghadiri OGP Summit 2023 di
              Tallinn, Estonia. OGP Summit merupakan pertemuan tingkat tinggi
              yang diselenggarakan setiap dua tahun sekali untuk mengakselerasi
              inisiatif keterbukaan pemerintah yang dihadiri oleh berbagai
              perwakilan pemerintah, masyarakat sipil, serta mitra pembangunan.
              Penyelenggaraan OGP Summit 2023 ini bertujuan untuk mengakselerasi
              inisiatif keterbukaan pemerintah di tingkat nasional dan lokal
              melalui pembahasan di isu-isu strategis global keterbukaan
              pemerintah.
            </p>
            <h2 class="text-lg font-semibold mt-4 font-inter">
              3. Indonesia memenangkan OGP Awards
            </h2>
            <p class="ml-5 font-inter font-normal">
              Indonesia memenangkan OGP Awards untuk komitmen Perluasan Bantuan
              Hukum bagi Individu dan Kelompok Rentan.
            </p>
          </div>
        </CustomDetails>
        <CustomDetails title="2022">
          <div class="details-text">
            <h2 class="text-lg font-semibold font-inter">
              1. Penyelenggaraan Side Event pada Pertemuan G20 ke-3
            </h2>
            <p class="ml-5 font-inter font-normal">
              Penyelenggaraan Side Event pada Pertemuan G20 ke-3 dengan tema
              “Pengarusutamaan Nilai-Nilai Keterbukaan Pemerintah dalam
              Pemerintahan dan Pembangunan Berkelanjutan”
            </p>
            <h2 class="text-lg font-semibold mt-4 font-inter">
              2. Terpilihnya Indonesia sebagai anggota Dewan Pengarah OGP
              periode 2022-2025
            </h2>
            <h2 class="text-lg font-semibold mt-4 font-inter">
              3. Side Event 3rd DWG G20
            </h2>
          </div>
        </CustomDetails>
        <CustomDetails title="2021">
          <div class="details-text">
            <h2 class="text-lg font-semibold font-inter">
              1. OGP Global Summit 2021
            </h2>
            <p class="ml-5 font-inter font-normal">
              Bapak Presiden Joko Widodo memberikan pidato pembuka di acara OGP
              Global Summit 2021. Selain itu, Bapak Menteri PPN/Bappenas,
              Suharso Monoarfa menjadi salah satu pembicara dalam sesi pleno The
              Future of Governance in Asia and Pacific dalam acara OGP Global
              Summit 2021
            </p>
            <h2 class="text-lg font-semibold mt-4 font-inter">
              2. Prestasi dan penghargaan Indonesia dalam 10 tahun OGP:
            </h2>
            <ul class="list-disc ml-9 mt-2 font-inter font-normal">
              <li>
                Lembaga Kebijakan Pengadaan Barang/Jasa Pemerintah (LKPP)
                bersama dengan Indonesia Corruption Watch (ICW) memperoleh Juara
                2 OGP Impact Award melalui komitmen portal keterbukaan informasi
                pengadaan barang dan jasa.
              </li>
              <li>
                Kabupaten Banggai mendapat penghargaan OGP Accelerator Award
                melalui komitmen pengembangan aplikasi layanan kesehatan bagi
                seksual dan reproduksi.
              </li>
              <li>
                Kabupaten Sumbawa Barat memperoleh Juara 1 OGP Spotlight Award
                melalui komitmen forum pengaduan layanan publik.
              </li>
              <li>
                Provinsi Nusa Tenggara Barat memperoleh Juara 2 OGP Spotlight
                Award melalui komitmen pengembangan aplikasi pengaduan layanan
                publik.
              </li>
              <li>
                Kota Semarang memperoleh Juara 3 OGP Spotlight Award melalui
                komitmen pengembangan portal pengaduan layanan publik yang
                dikhususkan untuk Kelompok Rentan
              </li>
            </ul>
          </div>
        </CustomDetails>
        <CustomDetails title="2020">
          <div class="details-text">
            <h2 class="text-lg font-semibold font-inter">
              1. Working Level Meeting di Jerman
            </h2>
            <p class="ml-5 font-inter font-normal">
              Pemerintah Indonesia sebagai anggota Steering Committee menghadiri
              OGP Steering Committee
            </p>
            <h2 class="text-lg font-semibold mt-4 font-inter">
              2. Peluncuran RAN OGI 2020-2022
            </h2>
            <h2 class="text-lg font-semibold mt-4 font-inter">
              3. Terpilihnya 5 daerah di Indonesia dalam OGP Local
            </h2>
            <div class="flex space-x-4 mt-2 ml-5 font-inter text-neutral-2">
              <LogoCard
                LogoSrc="/assets/bangai.png"
                alt="Kab. Banggai"
                label="Kab. Bangai"
              />
              <LogoCard
                LogoSrc="/assets/semarang.png"
                alt="Kota Semarang"
                label="Kota Semarang"
              />
              <LogoCard LogoSrc="/assets/ntb.png" alt="NTB" label="NTB" />
              <LogoCard
                LogoSrc="/assets/sumbawa.png"
                alt="Sumbawa Barat"
                label="Sumbawa Barat"
              />
              <LogoCard
                LogoSrc="/assets/brebes.png"
                alt="Kab. Brebes"
                label="Kab. Brebes"
              />
            </div>
            <p class="mt-4 ml-5 font-inter font-normal">
              <span class="text-primary-1 font-semibold"
                >Open Government Partnership (OGP) Local</span
              >
              merupakan sebuah upaya untuk mendorong kolaborasi antara
              pemerintah daerah dengan masyarakat sipil dalam mewujudkan
              pemerintahan yang transparan, partisipatif, dan akuntabel.
            </p>
            <h3 class="mt-2 ml-5 font-inter font-normal">
              <span class="text-primary-1 font-semibold">Tujuan utamanya</span>
              meliputi :
            </h3>
            <ul class="list-disc ml-9 mt-2 font-inter font-normal">
              <li>
                Mengembangkan nilai keterbukaan pemerintah untuk mewujudkan tata
                kelola pemerintahan di tingkat daerah yang bersifat
                masyarakat-sentris dan meningkatkan pelayanan publik
              </li>
              <li>
                Memperkuat koordinasi dan kolaborasi pemerintah pusat dan daerah
                dalam mendorong implementasi nilai dan praktik keterbukaan
                pemerintah
              </li>
            </ul>
          </div>
        </CustomDetails>
        <CustomDetails title="2019">
          <div class="details-text">
            <h2 class="text-lg font-semibold font-inter">
              1. OGP Summit di Kanada
            </h2>
            <p class="ml-5 font-inter font-normal">
              Pemerintah Indonesia menghadiri OGP Summit di Kanada dan terpilih
              sebagai anggota Steering Committee OGP periode 2019-2022.
            </p>
            <h2 class="text-lg font-semibold mt-4 font-inter">
              2. Pemerintah Indonesia terpilih sebagai Co-Chair of Thematic
              Leadership Subcommittee OGP
            </h2>
          </div>
        </CustomDetails>
        <CustomDetails title="2018">
          <div class="details-text">
            <h2 class="text-lg font-semibold font-inter">
              1. OGP Summit di Georgia
            </h2>
            <p class="ml-5 font-inter font-normal">
              Pemerintah Indonesia menghadiri OGP Summit di Georgia dan Asia
              Pacific Regional Meeting di Korea Selatan.
            </p>
            <h2 class="text-lg font-semibold mt-4 font-inter">
              2. Peluncuran RAN Open Government yang kelima
            </h2>
            <p class="ml-5 font-inter font-normal">
              RAN ini berfokus pada keterbukaan informasi publik, partisipasi
              masyarakat, transparansi data anggaran pendidikan, kesehatan, dan
              pengentasan kemiskinan, peningkatan pelayanan publik, serta
              perluasan akses layanan bantuan hukum.
            </p>
          </div>
        </CustomDetails>
      </div>
      <div class="h-[calc(20vh)]"></div>
    </div>
    <Footer />
    <ScrollButton />
  </div>
</template>

<script>
import Header from "../../components/Header.vue";
import Footer from "../../components/Footer.vue";
import ScrollButton from "../../components/ScrollButton.vue";
import TitleSection from "../../components/TitleSection.vue";
import CustomDetails from "../../components/Pelajari/CustomDetails.vue";
import LogoCard from "../../components/Pelajari/LogoCardPelajari.vue";

export default {
  name: "Perjalanan",
  components: {
    Header,
    Footer,
    ScrollButton,
    TitleSection,
    CustomDetails,
    LogoCard,
  },
};
</script>

<style>
/* Add any global styles here */
</style>
