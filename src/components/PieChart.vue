<script>
import { Doughnut } from 'vue-chartjs';

export default {
  name: 'PieChart',
  extends: Doughnut,
  props: ['data', 'options'],
  mounted() {
    this.renderChart(this.data, {
    });
  },
};
</script>

<style lang="scss">
  @import '../assets/styles/variables.scss';
</style>
