<template>
  <div>
    <h1>Dashboard Admin</h1>
    <div class="row">
      <div class="col-lg-3 col-6">
        <!-- small box -->
        <div class="small-box bg-info">
          <div class="inner">
            <h3>150</h3>
            <p>Pengguna</p>
          </div>
          <div class="icon">
            <i class="fas fa-users"></i>
          </div>
        </div>
      </div>

      <div class="col-lg-3 col-6">
        <div class="small-box bg-success">
          <div class="inner">
            <h3>53<sup style="font-size: 20px">%</sup></h3>
            <p>Transaksi Sukses</p>
          </div>
          <div class="icon">
            <i class="fas fa-chart-line"></i>
          </div>
        </div>
      </div>

      <!-- Tambahkan lebih banyak box jika perlu -->
    </div>
  </div>
</template>

<script>
export default {
  name: "Index"
}
</script>

<style scoped>
.small-box {
  border-radius: 0.5rem;
  padding: 1rem;
  color: #fff;
}
</style>
