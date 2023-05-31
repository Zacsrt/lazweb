<template>
          <div class="dropright">
            <ul>
               <li class="drr"><a href="#">อุปกรณ์ อิเล็กทรอนิกส์</a>
                <ul>
                    <li><a href="#">โทรศัพท์มือถือ</a></li>
                    <li><a href="#">แท็บเล็ต</a></li>
                    <li><a href="#">แล็ปท็อป</a></li>
                    <li><a href="#">คอมพิวเตอร์ตั้งโต๊ะ</a></li>
                    <li><a href="#">กล้อง DSLR</a></li>
                    <li><a href="#">กล้องมิลเลอร์เลส</a></li>
                    <li><a href="#">กล้องคอมแพค</a></li>
                    <li><a href="#">กล้องอินสแตนท์</a></li>
                    <li><a href="#">กล้องแอ็คชั่นแคม</a></li>
                    <li><a href="#">โดรน</a></li>
                    <li><a href="#">กล้องรักษาความปลอดภัย</a></li>
                    <li><a href="#">เครื่องเล่นเกมคอนโซล</a></li>
                </ul>
                </li> 

               <li><a href="#">อุปกรณ์เสริม อิเล็กทรอนิกส์</a></li> 
               <li><a href="#">ทีวีและเครื่องใช้ ไฟฟ้าในบ้าน</a></li> 
               <li><a href="#">สุขภาพและความงาม</a></li> 
               <li><a href="#">เด็กอ่อน และของเล่น</a></li> 
               <li><a href="#">ซูเปอร์มาร์เก็ต และสัตว์เลี้ยง</a></li> 
               <li><a href="#">บ้านและไลฟ์สไตล์</a></li> 
               <li><a href="#">แฟชั่น และ เครื่องประดับผู้หญิง</a></li> 
               <li><a href="#">แฟชั่น และ เครื่องประดับผู้ชาย</a></li> 
               <li><a href="#">แฟชั่น และ เครื่องประดับสำหรับเด็ก</a></li> 
               <li><a href="#">กีฬาและ การเดินทาง</a></li> 
               <li><a href="#">ยานยนต์ และอุปกรณ์</a></li> 
            </ul>
        </div>
        <div class="photos">
        <img src="https://lzd-img-global.slatic.net/g/icms/images/ims-web/d96db672-bb31-4d9d-a1c6-f635cb4f258d.jpg_1200x1200q90.jpg_.webp" alt="sale">
        </div>
</template>

<script>
export default {
  name: "dropMenu.vue",
};
</script>

<style>
@import "./layout.css";
.b3{
      width: 100%;
      background-color: #96a8ea;
  }
  .b3 .photos{ 
  width: auto;
  }
  .b3 img{
      float: left;
  }
  .dropright{
      width: 20%;
      float: left;
      
  }
  .dropright ul{
    margin-bottom: 0;
    margin-top: 0px;
      float: right;
      text-align: left;
  list-style-type: none;

  width: max-content;
  height: 418px;
  background-color: white;
  
  /* margin-right: 100px; */
  }
  .dropright ul a{
    text-decoration: none;
    color: #959595;
    padding: 1px;
    height: 30px;
  }
  .dropright ul ul{
      padding-left: 50px;
      display: none;
      position: absolute;
      float: left;
      box-shadow: 0 2px 10px rgba(0, 0, 0, 0.25);
  }
  .dropright .drr:hover  > ul{
  display: initial;
  }
  .dropright ul .drr-2 ul{
      display: none;
    position: absolute;
    float: left;
  }
  .dropright ul .drr-2:hover .drr-22{
  display: initial;
  }
</style>