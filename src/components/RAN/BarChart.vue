<template>
  <div class="chart-container flex justify-center items-center">
    <Bar :data="chartData" :options="chartOptions" class="" />
  </div>
</template>
  
  <script setup>
import { Bar } from "vue-chartjs";
import {
  Chart as ChartJS,
  CategoryScale,
  LinearScale,
  BarElement,
  Title,
  Tooltip,
  Legend,
} from "chart.js";

ChartJS.register(
  CategoryScale,
  LinearScale,
  BarElement,
  Title,
  Tooltip,
  Legend
);

const chartData = {
  labels: [
    "Juni 2023",
    "Juli 2023",
    "Agustus 2023",
    "September 2023",
    "Oktober 2023",
    "November 2023",
    "Desember 2023",
    "Januari 2024",
    "Februari 2024",
    "Maret 2024",
    "April 2024",
    "Mei 2024",
  ],
  datasets: [
    {
      label: "Jumlah Pelaporan Monev OMS",
      data: [76, 34, 43, 65, 33, 54, 68, 83, 54, 102, 76, 43, 54, 34, 76, 23],
      backgroundColor: "#EDC22C",
    },
  ],
};

const chartOptions = {
  responsive: true,
  plugins: {
    legend: {
      position: "bottom",
    },
    title: {
      display: true,
      text: "Jumlah Hasil Pelaporan Monitoring dan Evaluasi OMS Setahun Terakhir",
      font: {
        size: 20,
      },
    },
  },
};
</script>
  
  