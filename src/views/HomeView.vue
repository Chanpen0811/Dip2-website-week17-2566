<script setup>
import { toast } from 'vue3-toastify';
import 'vue3-toastify/dist/index.css';

toast.info("ยินดีต้อนรับเข้าสู่สุดยอดอาหาร", {
  autoClose: 1500,
  position:toast.POSITION.TOP_CENTER
})

</script>
<template>
  <div class="container my-5">
    <div class="card-group">
  <div class="card">
    <img src="https://img.kapook.com/u/2017/sarinee/July/week3/cok2.jpg" class="card-img-top" alt="...">
    <div class="card-body">
      <h5 class="card-title">ต้มยำกุ้ง</h5>
      <p class="card-text">อาหารไทยอับดับต้นๆที่คนชอบมากที่สุด รสชาติจัดจ้าน อร่อยสุดๆ</p>
      <p class="card-text"><small class="text-body-secondary">สุดยอดอาหาร</small></p>
    </div>
  </div>
  <div class="card">
    <img src="https://www.unileverfoodsolutions.co.th/th/chef-inspiration/simple-tips-for-great-flavour/somtum-green-papaya-salad-recipes/jcr:content/listImage.transform/jpeg-optimized/image.1684754238037.jpg" alt="...">
    <div class="card-body">
      <h5 class="card-title">ส้มตำ</h5>
      <p class="card-text">มีหลายตำให้เลยกันเลยไม่ว่าจะเป็น ตำไทย ตำปูปลาร้า ตำป่า ตำโคราช และอื่นๆ</p>
      <p class="card-text"><small class="text-body-secondary">สุดยอดอาหาร</small></p>
    </div>
  </div>
  <div class="card">
    <img src="https://we-rworldtour.com/wp-content/uploads/2021/06/%E0%B8%9C%E0%B8%B1%E0%B8%94%E0%B9%84%E0%B8%97%E0%B8%A2-Pad-Thai-Birds-Eye-View-1-1024x683.jpg" class="card-img-top" alt="...">
    <div class="card-body">
      <h5 class="card-title">ผัดไทกุ้งสด</h5>
      <p class="card-text">เส้นนุ่มๆ ซอสที่มีรสชาติกลมกล่อนมีความตัดเปรี้ยวด้วยมะนาวกลิ่นหอมของกระทะ</p>
      <p class="card-text"><small class="text-body-secondary">สุดยอดอาหาร</small></p>
    </div>
  </div>
</div>
  </div>
</template>
