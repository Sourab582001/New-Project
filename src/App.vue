<template>
  <div>
   <navigationbar />
   <heroarea />
   <aboutus />
   <services />
   <testimonial />
   <contactus />
  </div>
</template>
<script>
import Aboutus from './components/aboutus.vue'
import Contactus from './components/contactus.vue'
import Heroarea from './components/heroarea.vue'
import Navigationbar from './components/navigationbar.vue'
import Services from './components/services.vue'
import Testimonial from './components/testimonial.vue'

export default {
  components: {
    Navigationbar,
    Heroarea,
    Aboutus,
    Services,
    Testimonial,
    Contactus
    
  }
}
</script>,
    Testimonial