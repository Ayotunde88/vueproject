<template>
  
</template>
 
<script>
import { defineComponent } from 'vue'
import { plByMonth } from '@/data'
import { Chart, Grid, Bar, Line } from 'vue3-charts'

export default defineComponent({
  name: 'Main',
  components: { Chart, Grid, Bar, Line },
  setup() {
    const data = ref(plByMonth)

    const direction = ref('horizontal')
    const margin = ref({
      left: 0,
      top: 20,
      right: 20,
      bottom: 0
    })

    return {data, margin, direction}
  }
})
</script>