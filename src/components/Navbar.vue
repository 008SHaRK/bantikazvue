<template>
  <div class="container">
    <nav class="navbar navbar-expand-lg navbar-light bg-light border-bottom">
    <div class="container-fluid d-flex flex-column p-0">

      <!-- Top Info Row -->
      <div class="w-100 d-flex justify-content-between align-items-center px-3 py-2 bg-light-subtle small; ">
        <div class="d-flex align-items-center gap-2">
          <img src="https://flagcdn.com/16x12/az.png" alt="AZ" />
          <span>Azərbaycan</span>
        </div>
        <div class="d-flex gap-3">
          <a href="#">Şirkət haqqında</a>
          <a href="#">Çatdırılma ilə bağlı məlumat</a>
        </div>
        <div class="d-flex align-items-center gap-2">
          <i class="bi bi-telephone text-danger"></i>
          <span>+994 55 000 00 00</span>
          <a href="#" class="ms-2">Kömək</a>
        </div>
      </div>

      <!-- Middle Row -->
      <div class="w-100 d-flex align-items-center justify-content-between px-3 py-2">
        <div class="d-flex align-items-center">
          <button class="btn btn-outline-danger d-flex align-items-center gap-2">
            <i class="bi bi-list"></i> Bütün məhsullar
          </button>
        </div>

        <div class="input-group w-50">
          <input type="text" class="form-control" placeholder="Üz üçün xüsusi..." />
          <button class="btn btn-danger"><i class="bi bi-search"></i></button>
        </div>

        <div class="d-flex align-items-center gap-3">
         <router-link to="/login" class="nav-link">
      <i class="bi bi-person"></i> Giriş
    </router-link>
          <a href="#"><i class="bi bi-bookmark"></i> Sevimlilər</a>
          <a href="#"><i class="bi bi-cart"></i> Səbət</a>
        </div>
      </div>

      <!-- Bottom Menu -->
      <div class="w-100 d-flex justify-content-center gap-4 bg-light py-2">
        <a href="#">Saç</a>
        <a href="#">MakiYaj</a>
        <a href="#">Üz</a>
        <a href="#">Günəş</a>
        <a href="#">Bədən</a>
        <a href="#">Parfum</a>
        <a href="#">K-Beauty</a>
        <a href="#">Uşaq və ana</a>
        <a href="#">Markalar</a>
        <a href="#">Kampaniyalar</a>
        <a href="#">Hədiyyəlik dəstlər</a>
      </div>

    </div>
  </nav>
  </div>
</template>

<script setup>
// Bootstrap iconları üçün daxil olun:
// https://cdnjs.cloudflare.com/ajax/libs/bootstrap-icons/1.10.5/font/bootstrap-icons.min.css
</script>

<style scoped>
a {
  text-decoration: none;
  color: #333;
}
a:hover {
  color: #d63384;
}
input::placeholder {

}
</style>
