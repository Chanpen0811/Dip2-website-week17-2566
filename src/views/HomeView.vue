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
    <img src="https://www.jmthaifood.com/wp-content/uploads/2020/01/%E0%B8%95%E0%B9%89%E0%B8%A1%E0%B8%A2%E0%B8%B3%E0%B8%81%E0%B8%B8%E0%B9%89%E0%B8%87-1.jpg" class="card-img-top" alt="...">
    <div class="card-body">
      <h5 class="card-title">ต้มยำกุ้ง</h5>
      <p class="card-text">ต้มยำ เป็นแกงไทยที่มีรสเปรี้ยวเผ็ด ต้มยำเป็นอาหารที่รู้จัก และมีชื่อเสียงไปทั่วโลก คำว่า "ต้มยำ" มาจากคำภาษาไทย 2 คำ คือ "ต้ม" และ "ยำ" คำว่า "ต้ม" หมายถึง กิริยาเอาของเหลวใส่ภาชนะแล้วทำให้ร้อนให้เดือดหรือสุก ขณะที่ "ยำ" หมายถึงอาหารไทยประเภทที่มีรสเปรี้ยวเผ็ด ดังนั้น "ต้มยำ" คือแกงไทยที่มีความเผ็ดร้อนและเปรี้ยว</p>
      <p class="card-text"><small class="text-body-secondary">สุดยอดอาหาร</small></p>
    </div>
  </div>
  <div class="card">
    <img src="https://www.unileverfoodsolutions.co.th/th/chef-inspiration/simple-tips-for-great-flavour/somtum-green-papaya-salad-recipes/jcr:content/listImage.transform/jpeg-optimized/image.1684754238037.jpg" alt="...">
    <div class="card-body">
      <h5 class="card-title">ส้มตำ</h5>
      <p class="card-text">ส้มตำ เป็นอาหารปรุงมาจากการทำตำส้ม คือการทำให้เปรี้ยวและเผ็ด ในลาวและอีสานจะเรียกว่าตำหมากหุ่ง ปรุงโดยนำมะละกอดิบที่สับแล้วฝานหรือขูดเป็นเส้นมาตำในครกเป็นหลัก พร้อมด้วยวัตถุดิบอื่น ๆ คือ มะเขือเทศลูกเล็ก มะเขือสีดา มะเขือเปราะ พริกสดหรือพริกแห้ง ถั่วฝักยาว กระเทียม และปรุงรสด้วยน้ำตาลปี๊บ น้ำปลา และมะนาว</p>
      <p class="card-text"><small class="text-body-secondary">สุดยอดอาหาร</small></p>
    </div>
  </div>
  <div class="card">
    <img src="https://www.jmthaifood.com/wp-content/uploads/2019/12/%E0%B8%9C%E0%B8%B1%E0%B8%94%E0%B9%84%E0%B8%97%E0%B8%A2%E0%B8%81%E0%B8%B8%E0%B9%89%E0%B8%87%E0%B8%AA%E0%B8%94-2.jpg" class="card-img-top" alt="...">
    <div class="card-body">
      <h5 class="card-title">ผัดไทกุ้งสด</h5>
      <p class="card-text">ผัดไทย  เป็นอาหารไทยที่หารับประทานได้ทั่วประเทศไทย โดยเฉพาะในภาคกลาง และอาจพบได้ในร้านอาหารไทยในต่างประเทศบางแห่งผัดไทยโดยทั่วไปจะนำเส้นเล็กมาผัดด้วยไฟแรงกับไข่ ใบกุยช่ายสับ ถั่วงอก หัวไชโป๊สับ เต้าหู้เหลือง ถั่วลิสงคั่ว และกุ้งแห้ง ปรุงรสด้วยพริก น้ำปลา และน้ำตาล เสิร์ฟพร้อมกับมะนาว ใบกุยช่าย ถั่วงอกสด และหัวปลีเป็นเครื่องเคียง </p>
      <p class="card-text"><small class="text-body-secondary">สุดยอดอาหาร</small></p>
    </div>
  </div>
</div>
  </div>
</template>
