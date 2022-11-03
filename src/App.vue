<template lang="en">
  <div >
    <MenuComponent/>
    
    <SlideComponent/>
    <router-view/>
    <FooterComponent/>

  </div>
</template>

<script>
import MenuComponent from '@/components/MenuComponent.vue'
import FooterComponent from '@/components/FooterComponent.vue';
import ProfileViewVue from './views/ProfileView.vue';
import SlideComponent from '@/components/SlideComponent.vue';

export default {
  name: 'HomeView',
  components: {
    MenuComponent,
    FooterComponent,
    ProfileViewVue,
    SlideComponent,
    
}
}
</script>