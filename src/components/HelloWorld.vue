<template>
<span>
  <navigation/>
  <v-container fluid>  
    <v-row class="text-center">
      <slider-promo/>
    </v-row>
    <v-row>
      <small-detail/>
    </v-row>
  </v-container>

</span>
</template>

<script>
  import Navigation from '@/components/Navigation'
  import SliderPromo from '@/components/SliderPromo';
  import SmallDetail from '@/components/SmallDetail.vue';

  export default {
    name: 'HelloWorld',
    data () {
    
    },
    components: {
        SliderPromo,
        Navigation,
        SmallDetail
    }
  }
</script>
