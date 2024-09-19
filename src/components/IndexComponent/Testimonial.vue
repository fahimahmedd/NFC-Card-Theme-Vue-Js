<template>
  <div class="review">
    <div class="Container">
      <div class="review_wrapper">
        <div class="rev_tag">
          <span>Customer Satisfaction</span>
        </div>
        <h2>Testimonials 😍</h2>
        <h3>Here from our happy Customers. They are already using our product <br /> and happy to share their feelings
          with us.</h3>
      </div>
      <div class="review_slider">
        <swiper :slidesPerView="1" :spaceBetween="30" :loop="true" :navigation="true" :modules="modules" class="mySwiper">
          <swiper-slide>
            <div class="review_item">
              <div class="item_content">
                <div class="review_text">
                  <span>"</span>
                  Lorem ipsum dolor sit, amet consectetur adipisicing elit. Lorem ipsum dolor sit, amet consectetur
                  adipisicing elit. Ipsam a voluptate corrupti dignissimos magnam esse impedit atque, sit ipsum
                  voluptatum!
                  <span>"</span>
                </div>
                <div class="reviewer_profile">
                  <div class="profile_img">
                    <img src="../../assets/image/user.jpeg" alt="" />
                  </div>
                  <div class='content_div'>
                    <div class="profile_name">
                      Naeem Munshi
                    </div>
                    <div class="profile_desgination">
                      <span>CEO</span> Of <span>DMK LTD.</span>
                    </div>
                  </div>
                </div>
              </div>
              <div class="item_bottom">
                <div class="star_contant">
                  <q-icon name="star"/>
                  <q-icon name="star"/>
                  <q-icon name="star"/>
                  <q-icon name="star"/>
                  <q-icon name="star"/>
                </div>
              </div>
            </div>
          </swiper-slide>
          <swiper-slide>
            <div class="review_item">
              <div class="item_content">
                <div class="review_text">
                  <span>"</span>
                  Lorem ipsum dolor sit, amet consectetur adipisicing elit. Lorem ipsum dolor sit, amet consectetur
                  adipisicing elit. Ipsam a voluptate corrupti dignissimos magnam esse impedit atque, sit ipsum
                  voluptatum!
                  <span>"</span>
                </div>
                <div class="reviewer_profile">
                  <div class="profile_img">
                    <img src="../../assets/image/profile.png" alt="" />
                  </div>
                  <div class='content_div'>
                    <div class="profile_name">
                      Naeem Munshi
                    </div>
                    <div class="profile_desgination">
                      <span>CEO</span> Of <span>DMK LTD.</span>
                    </div>
                  </div>
                </div>
              </div>
              <div class="item_bottom">
                <div class="star_contant">
                  <i>
                    <StarIcon />
                  </i>
                  <i>
                    <StarIcon />
                  </i>
                  <i>
                    <StarIcon />
                  </i>
                  <i>
                    <StarIcon />
                  </i>
                  <i>
                    <StarIcon />
                  </i>
                </div>
              </div>
            </div>
          </swiper-slide>
          <swiper-slide>
            <div class="review_item">
              <div class="item_content">
                <div class="review_text">
                  <span>"</span>
                  Lorem ipsum dolor sit, amet consectetur adipisicing elit. Lorem ipsum dolor sit, amet consectetur
                  adipisicing elit. Ipsam a voluptate corrupti dignissimos magnam esse impedit atque, sit ipsum
                  voluptatum!
                  <span>"</span>
                </div>
                <div class="reviewer_profile">
                  <div class="profile_img">
                    <img src={profile} alt="" />
                  </div>
                  <div class='content_div'>
                    <div class="profile_name">
                      Naeem Munshi
                    </div>
                    <div class="profile_desgination">
                      <span>CEO</span> Of <span>DMK LTD.</span>
                    </div>
                  </div>
                </div>
              </div>
              <div class="item_bottom">
                <div class="star_contant">
                  <i>
                    <StarIcon />
                  </i>
                  <i>
                    <StarIcon />
                  </i>
                  <i>
                    <StarIcon />
                  </i>
                  <i>
                    <StarIcon />
                  </i>
                  <i>
                    <StarIcon />
                  </i>
                </div>
              </div>
            </div>
          </swiper-slide>
        </swiper>
      </div>
    </div>
  </div>
</template>

<script>
// Import Swiper Vue.js components
import { Swiper, SwiperSlide } from 'swiper/vue';
// Import Swiper styles
import 'swiper/css';
import 'swiper/css/pagination';
import 'swiper/css/navigation';
// import required modules
import { Pagination, Navigation } from 'swiper/modules';

export default {
  components: {
    Swiper,
    SwiperSlide,
  },
  setup() {
    return {
      modules: [Pagination, Navigation],
    };
  },
};
</script>
