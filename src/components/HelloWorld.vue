<script setup>
defineProps({
  msg: {
    type: String,
    required: true
  }
})
</script>

<template>
  <div class="greetings">
    <h1 class="green">{{ msg }}</h1>
    <h3>
      Profil <br> 
      Nama : Aprialdi Nurhidayat<br>
      Npm : 223510662<br>
      Jurusan : Teknik <br>
      Prodi : Teknik Informatika<br>
      Asal kota : Pasir Pengaraian<br>
      
      <a href="https://vitejs.dev/" target="_blank" rel="noopener"></a> 
    </h3>
  </div>
</template>

<style scoped>
h1 {
  font-weight: 500;
  font-size: 2.6rem;
  position: relative;
  top: -10px;
}

h3 {
  font-size: 1.2rem;
}

.greetings h1,
.greetings h3 {
  text-align: center;
}

@media (min-width: 1024px) {
  .greetings h1,
  .greetings h3 {
    text-align: left;
  }
}
</style>
