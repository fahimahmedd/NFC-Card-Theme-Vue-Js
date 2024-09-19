<template>
    <div ref="header" class="header" >
        <div class="Container">
            <div class="header_wrapper">
                <div class="header_logo">
                    <img src="../assets/image/logo.png" alt="" />
                </div>
                <div class="header_content">
                    <ul>
                        <li><RouterLink to="">Home</RouterLink></li>
                        <li><RouterLink to="">About</RouterLink></li>
                        <li><RouterLink to="">Contact</RouterLink></li>

                    </ul>
                    <div class="login_btn">
                        Login
                    </div>
                </div>
            </div>
          </div>
     </div>
</template>

<script setup>
import { onMounted, ref } from 'vue';
const header = ref(null)
const stickNavbar = () => {
    // if (window !== undefined) {
    //   let windowHeight = window.scrollY;
    //   windowHeight > 300 ?
    //   windowHeight > 300 ? setStickyClass('sticky-nav') : setStickyClass('');
    // }
  };
onMounted(() => {
  window.addEventListener('scroll', stickNavbar())
})
</script>
