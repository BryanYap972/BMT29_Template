<template>
  <div class="card-container">
    <div class="gradient-container">
      <div class="content-container">
        <div class="title-text">Interfaith Blood Donation Drive</div>
        <div class="desc-tag">
          <div class="desc-text">Coming Soon</div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {}
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Baloo+2&display=swap');
.card-container {
  position: relative;
  width: 505px;
  height: 337px;
  border-radius: 20px;
  background-image: url('~/assets/images/blood-donation.png');
  background-size: cover;
  background-repeat: no-repeat;
  background-position: center;
  filter: drop-shadow(0px 2px 10px rgba(51, 51, 51, 0.3));
}

.gradient-container {
  position: absolute;
  bottom: 0;
  background: linear-gradient(1.43deg, #000000 17.51%, rgba(0, 0, 0, 0) 94.04%);
  border-radius: 20px;
  width: 505px;
  height: 207px;
}

.content-container {
  position: absolute;
  bottom: 0;
  padding-left: 40px;
  padding-bottom: 24px;
}

.title-text {
  font-family: 'Baloo 2', cursive;
  font-weight: bold;
  font-size: 28px;
  line-height: 39px;
  color: #ffffff;
  padding-bottom: 8px;
}

.desc-tag {
  display: flex;
  justify-content: center;
  align-items: center;
  background: #ff7a00;
  border-radius: 32px;
  width: 145px;
  height: 36px;
}

.desc-text {
  font-family: 'Baloo 2', cursive;
  font-size: 20px;
  line-height: 28px;
  color: #ffffff;
  width: 113px;
  height: 28px;
}
</style>
