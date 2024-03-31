<script setup>
import WelcomeItem from "./WelcomeItem.vue";
import DocumentationIcon from "./icons/IconDocumentation.vue";
import ToolingIcon from "./icons/IconTooling.vue";
import EcosystemIcon from "./icons/IconEcosystem.vue";
import CommunityIcon from "./icons/IconCommunity.vue";
import SupportIcon from "./icons/IconSupport.vue";
</script>

<template>
  <WelcomeItem>
    <template #icon>
      <DocumentationIcon />
    </template>
    <template #heading>Ringkasan Profil</template>

    <p>
      Saya adalah lulusan baru yang berdedikasi untuk membangun karier yang
      sukses dalam bidang Web Developer. Saya memiliki latar belakang pendidikan
      yang kuat dalam Prodi Teknik Informatika.
    </p>
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>Pendidikan Sekarang</template>

    <p>
      Fakultas Teknik Prodi Teknik Informatika <br />
      Universitas Islam Riau, Pekanbaru <br />
      Angkatan 2022
    </p>
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <EcosystemIcon />
    </template>
    <template #heading>Keterampilan</template>
    <p>
      Keterampilan Bahasa: Bahasa Indonesia (Native). <br />
      Keterampilan Teknis: Penguasaan Microsoft Office, Bahasa Pemrograman
      Python, Pengembangan Web dengan HTML/CSS/JavaScript.
    </p>
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <CommunityIcon />
    </template>
    <template #heading>Pengalaman Proyek</template>

    <p>
      Proyek : Pengembangan Aplikasi Manajemen Inventaris menggunakan Python dan
      MySQL. Bertanggung jawab untuk mengembangkan fitur-fitur utama, dan
      mengelola basis data.
    </p>
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <SupportIcon />
    </template>
    <template #heading>Kegiatan Ekstrakulikuler</template>

    <p>
      Anggota aktif dari Klub Pemrograman Alok, mengikuti berbagai kompetisi dan
      seminar terkait teknologi informasi.
    </p>
  </WelcomeItem>
</template>
