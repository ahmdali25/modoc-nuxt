<template>
  <div class="bg-main min-h-screen max-w-600px mx-auto">
    <TheNavbar />
    <div class="bg-image">
      <div class="bg-profile">
        <img src="../assets/images/user.png" alt="User Profile">
        <p class="mt-2 text-base name">PIDA LUBIS</p>
        <p class="text-xs date">Joined 17 Maret 2023</p>
      </div>
    </div>
    <div class="grid grid-cols-2 gap-4 p-4">
      <div class="badge p-2">
        <p class="text-xs">Level</p>
        <p class="text-base">2</p>
      </div>
      <div class="badge p-2">
        <p class="text-base">Rank </p>
        <p class="text-base">Speed Beginner 1</p>
      </div>
    </div>
    <div class="profile p-4">
      <p class="label">Nama</p>
      <p class="mt-1">Afridha Permata Lubis</p>

      <p class="label mt-4">Gender</p>
      <p class="mt-1">Perempuan</p>

      <p class="label mt-4">Tentang Saya</p>
      <p class="mt-1">An Automative Addict. Part of Velozity </p>
    </div>

    <TheFooter />

    <TheBottomNav />
  </div>
</template>

<script>
export default {
  name: 'IndexPage',
}
</script>

<style>
.bg-main {
  background-color: #f3f6fa;
}

.bg-image {
  background: url("../assets/images/bg.jpg"), #00AEFF;
  background-size: cover;
  background-repeat: no-repeat;
  width: 600px;
  height: 400px;
}

.bg-profile {
  position: absolute;
  top: 20%;
  left: 45%;
  font-family: 'Lato', sans-serif;
  color: #FFFFFF;
}

.bg-profile .name {
  font-weight: 700;
  display: flex;
  flex-direction: row;
  justify-content: center;
}

.bg-profile .date {
  font-weight: 900;
  display: flex;
  flex-direction: row;
  justify-content: center;
}

.badge {
  font-family: 'Lato', sans-serif;
  background: #44CCFE;
  border-radius: 10px;
  font-weight: 900;
  color: #FFFFFF;
}

.badge p { 
  display: flex;
  justify-content: center;
}

.profile {
  font-family: 'Roboto', sans-serif;
  color: #333333;
}

.profile .label {
  font-weight: 600;
}
</style>
