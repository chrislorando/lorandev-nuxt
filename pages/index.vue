<template>
  <div class="min-h-screen bg-white">
    <!-- Hero Section -->
    <section class="relative bg-gradient-to-br from-blue-600 to-blue-700 text-white py-20">
      <div class="container mx-auto px-4 text-center">
        <h1 class="text-4xl md:text-6xl font-bold mb-4">Selamat Datang di Rumah Makan Khas Sunda</h1>
        <p class="text-xl md:text-2xl mb-6 opacity-90">Citarasa Asli Sunda di Bekasi</p>
        <p class="text-lg mb-8 opacity-80 max-w-2xl mx-auto">Nikmati hidangan lezat dengan cita rasa otentik. Tempat terbaik untuk makan bersama keluarga dan teman.</p>
        <UButton to="#contact" size="xl" color="white" variant="solid">
          Hubungi Kami
        </UButton>
      </div>
    </section>

    <!-- About Section -->
    <section class="py-16 bg-gray-50">
      <div class="container mx-auto px-4">
        <div class="max-w-3xl mx-auto text-center">
          <h2 class="text-3xl font-bold mb-6">Tentang Kami</h2>
          <p class="text-lg text-gray-700 mb-4">Kami hadir untuk memberikan pengalaman kuliner terbaik dengan bahan-bahan segar dan resep warisan. Setiap hidangan dibuat dengan cinta dan dedikasi.</p>
          <p class="text-sm text-gray-600">Beroperasi sejak 2018</p>
        </div>
      </div>
    </section>

    <!-- Services Section -->
    <section class="py-16">
      <div class="container mx-auto px-4">
        <h2 class="text-3xl font-bold text-center mb-12">Layanan Kami</h2>
        <div class="grid md:grid-cols-3 gap-8">
          <UCard>
            <div class="text-center">
              <div class="text-blue-600 text-4xl mb-4">⭐</div>
              <h3 class="text-xl font-semibold mb-2">Menu Spesial</h3>
              <p class="text-gray-600">Pilihan hidangan signature kami yang paling diminati</p>
            </div>
          </UCard>

          <UCard>
            <div class="text-center">
              <div class="text-blue-600 text-4xl mb-4">👥</div>
              <h3 class="text-xl font-semibold mb-2">Layanan Keluarga</h3>
              <p class="text-gray-600">Ruang nyaman untuk makan bersama keluarga dan teman</p>
            </div>
          </UCard>

          <UCard>
            <div class="text-center">
              <div class="text-blue-600 text-4xl mb-4">📞</div>
              <h3 class="text-xl font-semibold mb-2">Pesanan Online</h3>
              <p class="text-gray-600">Pesan dari rumah, kami siapkan untuk Anda</p>
            </div>
          </UCard>
        </div>
      </div>
    </section>

    <!-- Gallery Section -->
    <section class="py-16 bg-gray-50">
      <div class="container mx-auto px-4">
        <h2 class="text-3xl font-bold text-center mb-12">Galeri</h2>
        <div class="grid md:grid-cols-3 gap-4">
          <img
            src="https://images.unsplash.com/photo-1517248135467-4c7edcad34c4?w=800"
            alt="Galeri 1"
            class="rounded-lg shadow-md w-full h-48 object-cover"
          >
          <img
            src="https://images.unsplash.com/photo-1555396273-367ea4eb4db5?w=800"
            alt="Galeri 2"
            class="rounded-lg shadow-md w-full h-48 object-cover"
          >
          <img
            src="https://images.unsplash.com/photo-1559339352-11d035aa65de?w=800"
            alt="Galeri 3"
            class="rounded-lg shadow-md w-full h-48 object-cover"
          >
        </div>
      </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="py-16">
      <div class="container mx-auto px-4">
        <h2 class="text-3xl font-bold text-center mb-12">Hubungi Kami</h2>
        <div class="max-w-2xl mx-auto">
          <UCard>
            <div class="space-y-4">
              <div class="flex items-center gap-4">
                <div class="text-blue-600 text-2xl">📞</div>
                <div>
                  <p class="text-sm text-gray-600">Telepon</p>
                  <p class="font-semibold">0838-6928-4154</p>
                </div>
              </div>
              <div class="flex items-center gap-4">
                <div class="text-blue-600 text-2xl">✉️</div>
                <div>
                  <p class="text-sm text-gray-600">Email</p>
                  <p class="font-semibold">info@rumahmakansunda.com</p>
                </div>
              </div>
              <div class="flex items-center gap-4">
                <div class="text-blue-600 text-2xl">📍</div>
                <div>
                  <p class="text-sm text-gray-600">Alamat</p>
                  <p class="font-semibold">Jl. Raya Bekasi No. 123</p>
                </div>
              </div>
            </div>
          </UCard>
        </div>
      </div>
    </section>
  </div>
</template>

<script setup lang="ts">
useSeoMeta({
  title: 'Rumah Makan Khas Sunda - Citarasa Asli Sunda di Bekasi',
  description: 'Nikmati hidangan lezat dengan cita rasa otentik Sunda di Bekasi'
})
</script>
