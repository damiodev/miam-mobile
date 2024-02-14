<template>
  <div class="restaurant--card">
    <div class="restaurant--image"></div>
    <div class="restaurant--information">
      <div class="top">
        <p class="name">Subway</p>
        <p class="note"><span>4.5</span></p>
      </div>
      <p class="time"><span>20-30 min</span></p>
    </div>
  </div>
</template>

<script>
export default {

}
</script>

<style lang="scss">
.restaurant--card {
  width: 400px;
  height: 200px;
  .restaurant--image {
    background-image: url('./../assets/img/subway.png');
    height: 100px;
    background-size: cover;
    background-position: center;
  }
  .restaurant--information {
    .top {
      margin: 10px 10px;
      display: flex;
      align-items: center;
      justify-content: space-between;
    }
    .name {
      font-size: 1.2rem;
      font-weight: 600;
    }
    .note {
      background-color: #5bee56;
      height: 30px;
      width: 30px;
      display: flex;
      justify-content: center;
      align-items: center;
      font-size: 0.8rem;
      border-radius: 50%;
    }
    .time {
      font-size: 0.9rem;
      margin: 10px 10px;
      span {
        font-weight: 600;
        background-color:rgba(127, 255, 212, 0.411);
      }
    }
  }
}
</style>