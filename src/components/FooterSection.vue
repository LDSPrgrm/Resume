<script setup>
</script>

<template>
  <div class="footer-wrapper">
    <!-- Big Contact Mesh -->
    <div class="mesh-footer"></div>
    
    <v-footer class="bg-transparent py-16 text-center relative pointer-events-auto">
      <v-container>
        <v-row justify="center">
          <v-col cols="12" md="10">
            <div class="ultra-glass pa-12 pa-md-16 rounded-3xl relative overflow-hidden">
               <!-- Decorators -->
               
               <div class="relative z-10">
                 <h2 class="text-h2 font-weight-black mb-6 font-display">
                   Ready to <span class="text-primary">Ship?</span>
                 </h2>
                 
                 <p class="text-h5 text-secondary font-weight-light mb-12" style="max-width: 700px; margin: 0 auto;">
                   I'm currently looking for new opportunities. Whether you have a question or just want to say hi, I'll try my best to get back to you!
                 </p>
                 
                 <div class="d-flex flex-wrap justify-center gap-6 mb-12">
                   <v-btn 
                     size="x-large" 
                     color="primary" 
                     height="64"
                     class="px-10 text-h6 font-weight-bold shadow-glow"
                     rounded="pill"
                     prepend-icon="mdi-email-fast"
                     href="mailto:ldsprgrm@gmail.com"
                   >
                     Say Hello
                   </v-btn>
                   
                   <v-btn
                     size="x-large"
                     variant="outlined"
                     color="secondary"
                     height="64"
                     class="px-10 text-h6 bg-white"
                     rounded="pill"
                     prepend-icon="mdi-github"
                     href="https://github.com/LDSPrgrm"
                     target="_blank"
                   >
                     Check Code
                   </v-btn>
                 </div>
                 
                 <!-- Social buttons removed -->
               </div>
            </div>
            
            <div class="mt-12 text-caption text-grey font-weight-bold tracking-widest text-uppercase">
               © {{ new Date().getFullYear() }} Lawrence David Subala
            </div>
          </v-col>
        </v-row>
      </v-container>
    </v-footer>
  </div>
</template>

<style scoped>
.footer-wrapper {
  position: relative;
  overflow: hidden;
}

.mesh-footer {
  position: absolute;
  bottom: 0;
  left: 0;
  width: 100%;
  height: 600px;
  background: radial-gradient(circle at 50% 100%, rgba(255, 75, 75, 0.08) 0%, transparent 70%);
  pointer-events: none;
}

.shadow-glow {
  box-shadow: 0 10px 30px rgba(255, 75, 75, 0.4);
  transition: transform 0.2s;
}
.shadow-glow:hover {
  transform: translateY(-4px);
  box-shadow: 0 15px 40px rgba(255, 75, 75, 0.5);
}

.gap-6 { gap: 24px; }
.gap-4 { gap: 16px; }

.rounded-3xl { border-radius: 32px !important; }
</style>
