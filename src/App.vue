<template>
  <div>
    <RodapeComponent />
    <CalculatorComponent />
    <CabecalhoComponent />
  </div>
</template>

<script>
import CabecalhoComponent from './components/CabecalhoComponent.vue';
import CalculatorComponent from './components/CalculatorComponent.vue';
import RodapeComponent from './components/RodapeComponent.vue';

export default {
  components: { RodapeComponent, CabecalhoComponent, CalculatorComponent }
}
</script>