<script setup>
import WelcomeItem from './WelcomeItem.vue'
import DocumentationIcon from './icons/IconDocumentation.vue'
import ToolingIcon from './icons/IconTooling.vue'
import EcosystemIcon from './icons/IconEcosystem.vue'
import CommunityIcon from './icons/IconCommunity.vue'
import SupportIcon from './icons/IconSupport.vue'
</script>

<template>
  <WelcomeItem>
    <template #icon>
      <DocumentationIcon />
    </template>
    <template #heading>Biodata</template>

    <a href="https://vuejs.org/" target="_blank" rel="noopener"></a>
    Perkenalkan nama saya Aprialdi Nurhidayat, saya lahir di pasir pengaraian,rokanhulu pada tanggal
    12 april 2004.Saya merupakan anak pertama dari 4 bersudara.
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>Hobi</template>

     Saya mempunyai banyak hobi tetapi yang sering saya lakukan ialah futsal dan bermain gitar. Awal
    saya menyukai olahraga futsal itu pada waktu saya masih sd, dimana waktu itu setiap hari sabtu
    di sekolah saya guru olahraga nya mengadakan futsal buat mengisi jam pelajaran yang kosong.
    <br />
    <br />
    Bermain gitar adalah hobi kreatif yang memungkinkan saya menciptakan musik yang indah dan mengekspresikan diri melalui melodi dan lirik. Ini membutuhkan ketekunan dan kesabaran, tetapi memberikan penghargaan besar saat berhasil memainkan lagu-lagu favorit atau menciptakan musik sendiri. 
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <EcosystemIcon />
    </template>
    <template #heading>Riwayat Pendidikan</template>
    <ul>
  <li><a href="https://sekolah.data.kemdikbud.go.id/index.php/chome/profil/10c4d4c7-2ff5-e011-9a70-ffbc13a59d30" target="_blank" rel="noopener">SDN 002 Rambah</a></li>
  <li><a href="https://sekolah.data.kemdikbud.go.id/index.php/chome/profil/b0499c24-8b18-e111-a4da-052b49722394" target="_blank" rel="noopener">Mts Pondok modern AL-KAUTSAR</a></li>
  <li><a href="https://sman6pekanbaru.sch.id/" target="_blank" rel="noopener">MAN 3 PEKANBARU</a></li>
  <li><a href="https://uir.ac.id/profil" target="_blank" rel="noopener">Universitas Islam Riau</a></li>
</ul>

   
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <CommunityIcon />
    </template>
    <template #heading>Prestasi</template>
    <ul>
  <li><a href="https://sekolah.data.kemdikbud.go.id/index.php/chome/profil/10c4d4c7-2ff5-e011-9a70-ffbc13a59d30" target="_blank" rel="noopener">juara 1 lomba di Perkemahan Rohis se kota Pekanbaru antar SMS/SMK sederajat</a></li>
  <li><a href="https://sekolah.data.kemdikbud.go.id/index.php/chome/profil/b0499c24-8b18-e111-a4da-052b49722394" target="_blank" rel="noopener">Juara 2 lomba nasyid di UNRI Antar SMA/SMK sedrajat</a></li>
 
</ul>
    
  </WelcomeItem>


</template>
