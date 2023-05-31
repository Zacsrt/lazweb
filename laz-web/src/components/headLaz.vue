<template>
  <div class="headerlaz">
    <ul>
        <li>
          <a href="#">ช้อปคุ้มกว่าเดิมบนแอป</a>
        </li>
        <li>
          <a href="#">ขายสินค้ากับลาซาด้า</a>
        </li>
        <li><a href="#">ช่วยเหลือ</a></li>
        <li><a href="#">ติดตามสินค้า</a></li>
        <li><a href="#">ลงชื่อเข้าใช้</a></li>
        <li><a href="#">สมัครสมาชิก</a></li>
        <li><a href="#">CHANGE LANGUAGE</a></li>
      </ul>
  </div>
</template>

<script>
export default {
    name:'headLaz',

}
</script>

<style>
.headerlaz{
  background-color:#f7f7f7 ;
}
.headerlaz ul{
  float: right;
}
.headerlaz ul li {
  margin-top: 0;
  display: inline-block;
  margin-right: 10px;
}
.headerlaz ul li a {
  font-size: 15px;
  color: #000;
  text-decoration: none;
}

</style>