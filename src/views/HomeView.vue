<template>
  <div>

   <MenuComponent />
   <FooterComponent />

  </div>
</template>

<script>
import MenuComponent from '@/components/MenuComponent.vue'
import FooterComponent from '@/components/FooterComponent.vue'

export default {
  name: 'HomeView',
  components: {
    MenuComponent,
    FooterComponent,
  }
}
</script>
