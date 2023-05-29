<template>
  <div class="carousel-wrapper">
    <div class="carousel">
      <transition name="slide">
        <div :key="currentIndex">
          <img :src="items[currentIndex].src" alt="">
        </div>
      </transition>
      <button class="prev" @click="prevSlide">PREV</button>
      <button class="next" @click="nextSlide">NEXT</button>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      items: [
        { src: 'https://picsum.photos/id/1018/1000/600/' },
        { src: 'https://picsum.photos/id/1015/1000/600/' },
        { src: 'https://picsum.photos/id/1019/1000/600/' },
      ],
      currentIndex: 0,
    };
  },
  methods: {
    prevSlide() {
      this.currentIndex = (this.currentIndex - 1 + this.items.length) % this.items.length;
    },
    nextSlide() {
      this.currentIndex = (this.currentIndex + 1) % this.items.length;
    },
  },
};
</script>

<style scoped>
.carousel-wrapper {
  height: 100vh;
}

.carousel {
  height: 100%;
  display: flex;
  flex-direction: column;
}

.slide-enter-active,
.slide-leave-active {
  transition: transform 1s;
}

.slide-enter,
.slide-leave-to {
  transform: translateY(100%);
}

.prev,
.next {
  position: absolute;
  top: calc(50% - 20px);
  width: 40px;
  height: 40px;
  background-color: rgba(255,255,255,0.5);
  border-radius: 50%;
}

.prev:hover,
.next:hover {
  background-color: rgba(255,255,255,0.8);
}

.prev {
  left: 20px;
}

.next {
  right: 20px;
}
</style>
