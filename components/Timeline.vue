<template>
  <section div="timeline">
    <div class="grah">
      <div class="timeline-block timeline-block-right">
        <div class="marker"></div>
      </div>

      <div class="timeline-block timeline-block-right">
        <div class="marker"></div>
      </div>

      <div class="timeline-block timeline-block-right">
        <div class="marker"></div>
      </div>

      <div class="timeline-block timeline-block-right">
        <div class="marker"></div>
      </div>
    </div>
  </section>
</template>

<style scoped>
section {
  background: #0322dc !important;
  width: 100vw;
  margin-top: -60px;
  margin-left: -22vw;
}

.grah {
  width: 100%;
  margin-top: 200px;
  padding: 250px 0;
  position: relative;
  overflow: hidden;
  left: -20%;
}

.grah:before {
  content: "";
  position: absolute;
  top: 0;
  left: 50%;
  margin-left: -1px;
  width: 2px;
  height: 100%;
  background: #ccd1d9;
  z-index: 1;
}

.timeline-block {
  width: -webkit-calc(50% + 8px);
  width: -moz-calc(50% + 8px);
  width: calc(50% + 8px);
  display: -webkit-box;
  display: -webkit-flex;
  display: -moz-box;
  display: flex;
  -webkit-box-pack: justify;
  -webkit-justify-content: space-between;
  -moz-box-pack: justify;
  justify-content: space-between;
  clear: both;
}

.timeline-block-right {
  float: right;
}

.timeline-block-left {
  float: left;
  direction: rtl;
}

.marker {
  width: 16px;
  height: 16px;
  border-radius: 50%;
  border: 2px solid #fff;
  background: #fff;
  margin-top: 80px;
  z-index: 9999;
}
</style>
