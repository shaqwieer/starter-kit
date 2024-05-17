<script setup>
import LogisticsCardStatistics from '@/views/dashborad/LogisticsCardStatistics.vue'
import LogisticsDeliveryExpectations from "@/views/dashborad/LogisticsDeliveryExceptions.vue"
import LogisticsDeliveryPerformance from "@/views/dashborad/LogisticsDeliveryPerformance.vue"
import LogisticsOrderByCountries from "@/views/dashborad/LogisticsOrderByCountries.vue"
import LogisticsShipmentStatistics from "@/views/dashborad/LogisticsShipmentStatistics.vue"
import LogisticsVehicleOverview from "@/views/dashborad/LogisticsVehicleOverview.vue"
</script>

<template>
  <h1>dddd</h1>
  <VRow class="match-height">
    <VCol cols="12">
      <LogisticsCardStatistics />
    </VCol>
    <VCol
      cols="12"
      md="6"
    >
      <LogisticsVehicleOverview />
    </VCol>

    <VCol
      cols="12"
      md="6"
    >
      <LogisticsShipmentStatistics />
    </VCol>

    <VCol
      cols="12"
      md="4"
    >
      <LogisticsDeliveryPerformance />
    </VCol>

    <VCol
      cols="12"
      md="4"
    >
      <LogisticsDeliveryExpectations />
    </VCol>

    <VCol
      cols="12"
      md="4"
    >
      <LogisticsOrderByCountries />
    </VCol>
  </VRow>
</template>
