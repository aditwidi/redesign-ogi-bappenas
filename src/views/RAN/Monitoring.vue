<template>
  <Header />
  <div class="max-w-screen-lg mx-auto my-8 md:my-16 px-4 md:px-8">
    <TitleSection
      link="/ran"
      linkText="Rencana Aksi Nasional"
      heading="Monitoring dan Evaluasi"
      subheading=""
      :headingPrimary="false"
      :subheadingPrimary="true"
    />
    <div class="text-center font-inter text-base md:text-lg mx-auto md:mx-6">
      <div class="items-start justify-between">
        <p class="bg-white p-4 rounded-lg text-center">
          Mekanisme monitoring dan evaluasi untuk pelaksanaan RAN OGI di periode
          2022-2024, Kementerian/ Lembaga melaporkan kegiatan ko-kreasi per
          triwulan ke dalam Sistem Monitoring dan Evaluasi Kantor Staf Presiden
          (SISMONEV KSP) dan ringkasan capaian kegiatan disajikan di website OGI
          yang terbuka dan dapat diakses oleh publik. Organisasi Masyarakat
          Sipil (OMS) juga akan melaporkan kegiatan ko-kreasi yang dilakukan
          bersama dengan Kementerian/Lembaga ke dalam sistem monitoring dan
          evaluasi yang ada di website Open Government Indonesia. Berikut merupakan statistik jumlah pelaporan selama satu tahun terakhir.
        </p>
        <div class="justify-center items-center mx-8 my-8">
          <BarChart />
        </div>
      </div>
      <div class="container mx-auto flex flex-col items-center mb-5">
        <h1 class="text-[4.5rem] font-bold leading-tight">
          Ayo Laporkan Capaian Instansimu 🔎
        </h1>
      </div>

      <p class="mt-4 md:mt-8">
        Periode pelaporan kegiatan dan capaian masing-masing instansi dilakukan
        setiap semester dengan tujuan agar Kementerian/Lembaga lebih fokus dalam
        implementasi RAN dan dapat menghasilkan keluaran yang lebih berdaya
        ungkit. Dengan adanya laporan baik dari Kementerian/Lembaga dan OMS,
        diharapkan publik dapat melihat secara detail skema ko-kreasi yang telah
        dijalankan selama pelaksanaan RAN OGI 2020-2022. Dengan begitu, proses
        pelibatan masyarakat sipil dalam kegiatan pemerintah dapat terlihat
        dengan jelas.
      </p>
    </div>
    <div class="flex justify-center items-center mt-12 md:mt-20">
      <InfoCard
        iconClass="/RAN/lock.svg"
        title="Pelaporan Monev OMS"
        link="/ran/monitoring-dan-evaluasi/OMS"
      />
    </div>
  </div>
  <ScrollButton />
  <Footer />
</template>

<script>
import Header from "../../components/Header.vue";
import Footer from "../../components/Footer.vue";
import ScrollButton from "../../components/ScrollButton.vue";
import TitleSection from "../../components/TitleSection.vue";
import InfoCard from "../../components/RAN/InfoCard.vue";
import BarChart from "../../components/RAN/BarChart.vue";

export default {
  components: {
    Header,
    Footer,
    ScrollButton,
    TitleSection,
    InfoCard,
    BarChart,
  },
};
</script>

