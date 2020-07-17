<script>
import { Pie } from 'vue-chartjs'

export default {
//   name: 'Histogramm',
  extends: Pie,
  data () {
    return {
      chartdata: {
        labels: ['HTML5', 'CSS3','Bootstrap', 'SASS', 'JS', 'Jquery' , 'Ajax', 'Wordpress'],
        datasets: [
          {
            data: [10, 10, 10, 10, 10, 10 ,10 ,10],
            backgroundColor: ["#9a2700", "#d2dd00" , "#563d7c" , "#fe9200", "#0d00fe", "#7900fe", "#46af8d", "#db434f"] ,
            
          },
        ]
        
      },
      options: {
        responsive: false,
        cutoutPercentage: 15
      }
    }
  },
  mounted () {
    this.renderChart(this.chartdata, this.options);
  }
}
</script>

<style>
</style>