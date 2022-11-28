<template>
    <div>
        <div class="bg-light p-3">
            <div class="ml-5 my-5">
                <h4>Complete your Room</h4>
                <h4>With what we Designed</h4>
            </div>
            <div class="d-flex justify-content-around">
                <cardcompo title="Cangkir Mauttie" price="89.300.000" index="chair-2"></cardcompo>
                <cardcompo title="Syail Ammeno" price="89.000.000" index="chair-1"></cardcompo>
                <cardcompo title="Saman Kaka " price="14.000.000" index="chair-3"></cardcompo>
                <cardcompo title="Lino Lino" price="22.000.000" index="chair-4"></cardcompo>

            </div>
        </div>
    </div>

</template>



<script>
import cardcompo from "./cardComponent.vue"

export default {
    name: 'sliderCmp',
    components: { cardcompo }

}
</script>
  
  <!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
  