<template>
  <Line :data="chartData" :options="chartOptions" />
</template>

<script>
import { Line } from 'vue-chartjs'
import {
  Chart as ChartJS,
  CategoryScale,
  LinearScale,
  PointElement,
  LineElement,
  Filler,
} from 'chart.js'

ChartJS.register(CategoryScale, LinearScale, PointElement, LineElement, Filler)

export default {
  name: 'LineChart',
  components: {
    Line,
  },
  props: {
    increase: {
      type: Boolean,
      required: true,
    },
    datasets: {
      type: Array,
      required: true,
    },
  },
  computed: {
    chartData() {
      return {
        labels: ['January', 'February', 'March', 'April', 'May', 'June', 'July'],
        datasets: [
          {
            label: 'Data One',
            borderColor: this.increase ? '#28C165' : '#F4574D',
            borderWidth: 1,
            backgroundColor: this.increase ? 'rgba(95, 223, 146, 0.3)' : 'rgba(255, 189, 189, 0.3)',
            data: this.datasets,
            fill: true,
          },
        ],
      }
    },
    chartOptions() {
      return {
        responsive: true,
        maintainAspectRatio: false,
        plugins: {
          legend: {
            display: false,
          },
          tooltip: {
            enabled: true,
          },
        },
        elements: {
          point: {
            radius: 0,
          },
        },
        scales: {
          y: {
            display: false,
            grid: {
              display: false,
              drawBorder: false,
            },
          },
          x: {
            display: false,
            grid: {
              display: false,
              drawBorder: false,
            },
          },
        },
      }
    },
  },
}
</script>
