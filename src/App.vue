<template>
  <v-app>
    <header class="header">
      <div class="header-top">
        <div class="container">
          <div class="d-flex justify-space-between align-center py-2">
            <v-sheet class="d-flex">
              <v-sheet class="header-item d-flex align-center py-1 pr-8"><svg class="mr-2" viewBox="0 0 32 32" xmlns="http://www.w3.org/2000/svg"><title/><g data-name="Layer 15" id="Layer_15"><path class="cls-1" d="M16,31A15,15,0,1,1,31,16,15,15,0,0,1,16,31ZM16,3A13,13,0,1,0,29,16,13,13,0,0,0,16,3Z"/><path class="cls-1" d="M20.24,21.66l-4.95-4.95A1,1,0,0,1,15,16V8h2v7.59l4.66,4.65Z"/></g></svg>Mon - Fri 8:00 - 18:00 / Sunday 8:00 - 14:00</v-sheet>
              <v-sheet class="header-item d-flex align-center py-1 pr-8">
                <svg class="mr-2" viewBox="0 0 512 512" xmlns="http://www.w3.org/2000/svg"><title/><g data-name="1" id="_1"><path d="M348.73,450.06a198.63,198.63,0,0,1-46.4-5.85c-52.43-12.65-106.42-44.74-152-90.36s-77.71-99.62-90.36-152C46.65,146.75,56.15,99.61,86.69,69.07l8.72-8.72a42.2,42.2,0,0,1,59.62,0l50.11,50.1a42.18,42.18,0,0,1,0,59.62l-29.6,29.59c14.19,24.9,33.49,49.82,56.3,72.63s47.75,42.12,72.64,56.31L334.07,299a42.15,42.15,0,0,1,59.62,0l50.1,50.1a42.16,42.16,0,0,1,0,59.61l-8.73,8.72C413.53,439,383.73,450.06,348.73,450.06ZM125.22,78a12,12,0,0,0-8.59,3.56l-8.73,8.72c-22.87,22.87-29.55,60-18.81,104.49,11.37,47.13,40.64,96.1,82.41,137.86s90.73,71,137.87,82.41c44.5,10.74,81.61,4.06,104.48-18.81l8.72-8.72a12.16,12.16,0,0,0,0-17.19l-50.09-50.1a12.16,12.16,0,0,0-17.19,0l-37.51,37.51a15,15,0,0,1-17.5,2.72c-30.75-15.9-61.75-39.05-89.65-66.95s-51-58.88-66.94-89.63a15,15,0,0,1,2.71-17.5l37.52-37.51a12.16,12.16,0,0,0,0-17.19l-50.1-50.11A12.07,12.07,0,0,0,125.22,78Z"/><path d="M364.75,269.73a15,15,0,0,1-15-15,99.37,99.37,0,0,0-99.25-99.26,15,15,0,0,1,0-30c71.27,0,129.25,58,129.25,129.26A15,15,0,0,1,364.75,269.73Z"/><path d="M428.15,269.73a15,15,0,0,1-15-15c0-89.69-73-162.66-162.65-162.66a15,15,0,0,1,0-30c106.23,0,192.65,86.43,192.65,192.66A15,15,0,0,1,428.15,269.73Z"/></g></svg>
                <a href="tel:180045856987">1-800-458-56987</a>
              </v-sheet>
              <v-sheet class="header-item d-flex align-center py-1 pr-8">
                <svg class="mr-2" viewBox="0 0 32 32" xmlns="http://www.w3.org/2000/svg"><title/><g data-name="Layer 21" id="Layer_21"><path class="cls-1" d="M16,31a3,3,0,0,1-2.21-1C10.14,26,4,18.39,4,13.36A12.19,12.19,0,0,1,16,1,12.19,12.19,0,0,1,28,13.36c0,5-6.14,12.59-9.79,16.65A3,3,0,0,1,16,31ZM16,3A10.2,10.2,0,0,0,6,13.36c0,3.14,3.47,8.86,9.28,15.31a1,1,0,0,0,1.44,0C22.53,22.22,26,16.5,26,13.36A10.2,10.2,0,0,0,16,3Z"/><path class="cls-1" d="M16,19a6,6,0,1,1,6-6A6,6,0,0,1,16,19ZM16,9a4,4,0,1,0,4,4A4,4,0,0,0,16,9Z"/></g></svg>
                47 Bakery Street, London, UK</v-sheet>
            </v-sheet>
            <v-sheet class="d-flex">
              <v-sheet class="d-flex justify-center align-center header-social facebook"><svg height="30px" id="Layer_1" style="enable-background:new 0 0 512 512;" version="1.1" viewBox="0 0 512 512" width="512px" xml:space="preserve" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink"><path d="M288,192v-38.1c0-17.2,3.8-25.9,30.5-25.9H352V64h-55.9c-68.5,0-91.1,31.4-91.1,85.3V192h-45v64h45v192h83V256h56.4l7.6-64  H288z"/></svg></v-sheet>
              <v-sheet class="d-flex justify-center align-center header-social twitter"><svg enable-background="new 0 0 56.693 56.693" height="30px" id="Layer_1" version="1.1" viewBox="0 0 56.693 56.693" width="56.693px" xml:space="preserve" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink"><path d="M52.837,15.065c-1.811,0.805-3.76,1.348-5.805,1.591c2.088-1.25,3.689-3.23,4.444-5.592c-1.953,1.159-4.115,2-6.418,2.454  c-1.843-1.964-4.47-3.192-7.377-3.192c-5.581,0-10.106,4.525-10.106,10.107c0,0.791,0.089,1.562,0.262,2.303  c-8.4-0.422-15.848-4.445-20.833-10.56c-0.87,1.492-1.368,3.228-1.368,5.082c0,3.506,1.784,6.6,4.496,8.412  c-1.656-0.053-3.215-0.508-4.578-1.265c-0.001,0.042-0.001,0.085-0.001,0.128c0,4.896,3.484,8.98,8.108,9.91  c-0.848,0.23-1.741,0.354-2.663,0.354c-0.652,0-1.285-0.063-1.902-0.182c1.287,4.015,5.019,6.938,9.441,7.019  c-3.459,2.711-7.816,4.327-12.552,4.327c-0.815,0-1.62-0.048-2.411-0.142c4.474,2.869,9.786,4.541,15.493,4.541  c18.591,0,28.756-15.4,28.756-28.756c0-0.438-0.009-0.875-0.028-1.309C49.769,18.873,51.483,17.092,52.837,15.065z"/></svg></v-sheet>
              <v-sheet class="d-flex justify-center align-center header-social dribbble"><svg enable-background="new 0 0 56.693 56.693" height="30px" id="Layer_1" version="1.1" viewBox="0 0 56.693 56.693" width="56.693px" xml:space="preserve" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink"><path clip-rule="evenodd" d="M52.43,24.152c-0.324-1.588-0.811-3.152-1.441-4.646  c-0.619-1.467-1.387-2.879-2.279-4.199c-0.885-1.309-1.9-2.539-3.018-3.656c-1.117-1.119-2.348-2.135-3.656-3.018  c-1.32-0.895-2.734-1.66-4.199-2.281c-1.494-0.629-3.057-1.117-4.646-1.439c-1.627-0.334-3.303-0.504-4.977-0.504  c-1.676,0-3.35,0.17-4.979,0.504c-1.588,0.322-3.152,0.811-4.645,1.439c-1.465,0.621-2.879,1.387-4.201,2.281  c-1.309,0.883-2.539,1.898-3.656,3.018c-1.118,1.117-2.132,2.348-3.016,3.656c-0.893,1.32-1.66,2.732-2.279,4.199  C4.805,21,4.32,22.564,3.995,24.152c-0.333,1.625-0.502,3.301-0.502,4.976c0,1.678,0.169,3.354,0.502,4.98  c0.325,1.588,0.811,3.152,1.442,4.645c0.619,1.465,1.387,2.881,2.279,4.201c0.884,1.309,1.898,2.537,3.016,3.656  c1.117,1.117,2.348,2.131,3.656,3.016c1.322,0.893,2.736,1.66,4.201,2.279c1.492,0.633,3.057,1.115,4.645,1.441  c1.629,0.336,3.303,0.504,4.979,0.504c1.674,0,3.35-0.168,4.977-0.504c1.59-0.326,3.152-0.809,4.646-1.441  c1.465-0.619,2.879-1.387,4.199-2.279c1.309-0.885,2.539-1.898,3.656-3.016c1.117-1.119,2.133-2.348,3.018-3.656  c0.893-1.32,1.66-2.736,2.279-4.201c0.631-1.492,1.117-3.057,1.441-4.645c0.334-1.627,0.502-3.303,0.502-4.98  C52.932,27.453,52.764,25.777,52.43,24.152z M49.316,28.919c-0.305-0.066-7.449-1.604-14.703-0.692  c-0.148-0.361-0.299-0.725-0.455-1.09c-0.439-1.033-0.912-2.057-1.404-3.062c8.338-3.402,11.723-8.297,11.762-8.355  C47.477,19.314,49.268,23.908,49.316,28.919z M42.156,13.285c-0.053,0.082-3.059,4.658-11.027,7.645  c-3.609-6.631-7.574-11.898-7.891-12.316c1.596-0.387,3.26-0.596,4.975-0.596C33.559,8.018,38.436,10.01,42.156,13.285z   M23.156,8.631c0,0.002-0.004,0.004-0.004,0.004s-0.023,0.006-0.062,0.014C23.111,8.643,23.135,8.639,23.156,8.631z M19.205,10.035  c0.281,0.377,4.186,5.67,7.84,12.164c-10.137,2.693-18.934,2.588-19.492,2.578C8.925,18.238,13.318,12.816,19.205,10.035z   M7.102,29.128c0-0.225,0.01-0.445,0.018-0.667c0.372,0.008,10.804,0.245,21.673-3.008c0.605,1.184,1.184,2.387,1.713,3.589  c-0.279,0.078-0.557,0.162-0.832,0.252c-11.393,3.682-17.172,13.934-17.172,13.934s0.008,0.006,0.008,0.01  C9.149,39.497,7.102,34.552,7.102,29.128z M28.213,50.241c-5.109,0-9.795-1.816-13.447-4.838c0.277,0.225,0.473,0.369,0.473,0.369  s4.047-8.826,16.566-13.188c0.047-0.018,0.094-0.031,0.141-0.045c2.971,7.719,4.197,14.184,4.51,16.029  C33.922,49.646,31.137,50.241,28.213,50.241z M40.01,46.64c-0.215-1.275-1.34-7.471-4.109-15.08  c6.814-1.09,12.721,0.779,13.156,0.922C48.117,38.364,44.75,43.438,40.01,46.64z" fill-rule="evenodd"/></svg></v-sheet>
              <v-sheet class="d-flex justify-center align-center header-social instagram"><svg version="1.1" id="Layer_1" xmlns="http://www.w3.org/2000/svg" height="30px" xmlns:xlink="http://www.w3.org/1999/xlink" x="0px" y="0px" viewBox="0 0 56.7 56.7" enable-background="new 0 0 56.7 56.7" xml:space="preserve"><g><path d="M28.2,16.7c-7,0-12.8,5.7-12.8,12.8s5.7,12.8,12.8,12.8S41,36.5,41,29.5S35.2,16.7,28.2,16.7z M28.2,37.7 c-4.5,0-8.2-3.7-8.2-8.2s3.7-8.2,8.2-8.2s8.2,3.7,8.2,8.2S32.7,37.7,28.2,37.7z"/><circle cx="41.5" cy="16.4" r="2.9"/><path d="M49,8.9c-2.6-2.7-6.3-4.1-10.5-4.1H17.9c-8.7,0-14.5,5.8-14.5,14.5v20.5c0,4.3,1.4,8,4.2,10.7c2.7,2.6,6.3,3.9,10.4,3.9 h20.4c4.3,0,7.9-1.4,10.5-3.9c2.7-2.6,4.1-6.3,4.1-10.6V19.3C53,15.1,51.6,11.5,49,8.9z M48.6,39.9c0,3.1-1.1,5.6-2.9,7.3 s-4.3,2.6-7.3,2.6H18c-3,0-5.5-0.9-7.3-2.6C8.9,45.4,8,42.9,8,39.8V19.3c0-3,0.9-5.5,2.7-7.3c1.7-1.7,4.3-2.6,7.3-2.6h20.6 c3,0,5.5,0.9,7.3,2.7c1.7,1.8,2.7,4.3,2.7,7.2V39.9L48.6,39.9z"/></g></svg></v-sheet>
            </v-sheet>
          </div>
        </div>
      </div>
      <div class="header-bottom py-5">
        <div class="container">
          <div class="d-flex justify-space-between align-center">
            <a href="#">
              <img src="./assets/images/logo.png" alt="logo">
            </a>
            <div class="d-flex align-center">
              <div class="header-link header-menu">
                <a href="#" class="link active">Home</a>
                <div class="header-menu-items">
                  <div class="header-menu-link active">
                    <a class="link" href="#">Retreat Center</a>
                  </div>
                  <div class="header-menu-link">
                    <a class="link" href="#">Spiritual Healing Retreat</a>
                  </div>
                  <div class="header-menu-link">
                    <a class="link" href="#">Yoga Retreat</a>
                  </div>
                </div>
              </div>
              <div class="header-link header-menu">
                <a href="#" class="link">Activities</a>
                <div class="header-menu-items">
                  <div class="header-menu-link">
                    <a class="link" href="#">All Activities</a>
                  </div>
                  <div class="header-menu-link">
                    <a class="link" href="#">Camps</a>
                  </div>
                  <div class="header-menu-link">
                    <a class="link" href="#">Retreats</a>
                  </div>
                  <div class="header-menu-link">
                    <a class="link" href="#">Yoga Retreats</a>
                  </div>
                  <div class="header-menu-link">
                    <a class="link" href="#">For Children</a>
                  </div>
                  <div class="header-menu-link">
                    <a class="link" href="#">Community</a>
                  </div>
                  <div class="header-menu-link">
                    <a class="link" href="#">Health & Wellbeing</a>
                  </div>
                </div>
              </div>
              <div class="header-link">
                <a href="#" class="link">Memberships</a>
              </div>
              <div class="header-link">
                <a href="#" class="link">Events</a>
              </div>
              <div class="header-link">
                <a href="#" class="link">About Us</a>
              </div>
              <div class="header-link">
                <a href="#" class="link">News</a>
              </div>
              <div class="header-link">
                <a href="#" class="link">Store</a>
              </div>
              <div class="header-link">
                <a href="#" class="link">Contact Us</a>
              </div>
              <div class="ml-6 mr-1 header-link shop">
                <v-badge :content="products.length" @click="showModal = true">
                  <svg viewBox="0 0 384 512" height="22px" fill="#fff" xmlns="http://www.w3.org/2000/svg"><path d="M320 64h-49.61C262.1 27.48 230.7 0 192 0S121 27.48 113.6 64H64C28.65 64 0 92.66 0 128v320c0 35.34 28.65 64 64 64h256c35.35 0 64-28.66 64-64V128C384 92.66 355.3 64 320 64zM192 48c13.23 0 24 10.77 24 24S205.2 96 192 96S168 85.23 168 72S178.8 48 192 48zM336 448c0 8.82-7.178 16-16 16H64c-8.822 0-16-7.18-16-16V128c0-8.82 7.178-16 16-16h18.26C80.93 117.1 80 122.4 80 128v16C80 152.8 87.16 160 96 160h192c8.836 0 16-7.164 16-16V128c0-5.559-.9316-10.86-2.264-16H320c8.822 0 16 7.18 16 16V448z"/></svg>
                </v-badge>
                <transition name="fade">                
                <div class="shop-cart" v-if="showModal">
                  <div class="shop-cart-close" @click="showModal = false"></div>
                  <div class="shop-cart-empty my-16" v-if="products.length < 1">
                    <div class="shop-cart-empty-content d-flex justify-center align-center flex-column">
                      <svg viewBox="0 0 384 512" height="28px" fill="#fff" xmlns="http://www.w3.org/2000/svg"><path d="M320 64h-49.61C262.1 27.48 230.7 0 192 0S121 27.48 113.6 64H64C28.65 64 0 92.66 0 128v320c0 35.34 28.65 64 64 64h256c35.35 0 64-28.66 64-64V128C384 92.66 355.3 64 320 64zM192 48c13.23 0 24 10.77 24 24S205.2 96 192 96S168 85.23 168 72S178.8 48 192 48zM336 448c0 8.82-7.178 16-16 16H64c-8.822 0-16-7.18-16-16V128c0-8.82 7.178-16 16-16h18.26C80.93 117.1 80 122.4 80 128v16C80 152.8 87.16 160 96 160h192c8.836 0 16-7.164 16-16V128c0-5.559-.9316-10.86-2.264-16H320c8.822 0 16 7.18 16 16V448z"/></svg>
                      <span class="mt-3">No products in the cart.</span>
                    </div>
                  </div>
                  <div class="shop-cart-content" v-else>
                    <div class="shop-cart-items">
                      <div v-for="product in products" :key="product.id" class="d-flex shop-cart-item mb-5">
                        <div class="shop-cart-item-icon mr-4">
                          <img :src="product.imgSrc" alt="img">
                        </div>
                        <div>
                          <h4 class="shop-cart-item-title">{{ product.title }}</h4>
                          <div class="shop-cart-item-price">
                            <span>1</span>
                            <svg height="11px" viewBox="0 0 16 16" fill="#fff" width="13" xmlns="http://www.w3.org/2000/svg"><polygon fill-rule="evenodd" points="8 9.414 3.707 13.707 2.293 12.293 6.586 8 2.293 3.707 3.707 2.293 8 6.586 12.293 2.293 13.707 3.707 9.414 8 13.707 12.293 12.293 13.707 8 9.414"/></svg>
                            <span>${{ product.price }}</span>
                          </div>
                        </div>
                        <div class="shop-cart-item-delete" @click="removeProduct(product.id)">
                          <svg class="feather feather-x" height="15px" stroke="#323641" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" viewBox="0 0 24 24" width="24" xmlns="http://www.w3.org/2000/svg"><line x1="18" x2="6" y1="6" y2="18"/><line x1="6" x2="18" y1="6" y2="18"/></svg>
                        </div>
                      </div>
                    </div>
                    <div class="shop-cart-subtotal">
                      <span>Subtotal: </span><span>${{ totalPrice }}</span>
                    </div>
                    <div class="d-flex">
                      <a href="#" class="shop-cart-button green">View cart</a>
                      <a href="#" class="shop-cart-button basic ml-2">Checkout</a>
                    </div>
                  </div>
                </div>
              </transition>
              </div>
              <div class="header-link">
                <svg height="30px" fill="#fff" enable-background="new 0 0 32 32" id="Glyph" version="1.1" viewBox="0 0 32 32" xml:space="preserve" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink"><path d="M27.414,24.586l-5.077-5.077C23.386,17.928,24,16.035,24,14c0-5.514-4.486-10-10-10S4,8.486,4,14  s4.486,10,10,10c2.035,0,3.928-0.614,5.509-1.663l5.077,5.077c0.78,0.781,2.048,0.781,2.828,0  C28.195,26.633,28.195,25.367,27.414,24.586z M7,14c0-3.86,3.14-7,7-7s7,3.14,7,7s-3.14,7-7,7S7,17.86,7,14z" id="XMLID_223_"/></svg>
              </div>
            </div>
          </div>
        </div>
      </div>
    </header>
    <MySlider />
    <Modal />
  </v-app>
</template>

<script setup>
import MySlider from './components/MySlider.vue';
import Modal from './components/Modal.vue'
import { ref } from 'vue';

const showModal = ref(false)

const products = ref([
  {id: 1, imgSrc: 'https://chakra.ancorathemes.com/wp-content/uploads/2020/05/product-copyright-500x500.jpg', title: 'Meditation Candle', price: 80},
  {id: 2, imgSrc: 'https://chakra.ancorathemes.com/wp-content/uploads/2020/05/product-copyright-1-500x500.jpg', title: 'Tourist Tent', price: 160},
])

const totalPrice = products.value.reduce((acc, product) => acc + product.price, 0);

function removeProduct(id) {
  const index = products.value.findIndex(product => product.id === id);
  if (index !== -1) {
    products.value.splice(index, 1);
  }
}

</script>

<style lang="scss">
@import './assets/scss/main.scss'
</style>